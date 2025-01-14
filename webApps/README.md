# Web App Store

This `apps.json` file and the other files and subdirectories in this folder are used as the default
app repository for the OpenCloud Web App Store.

## `apps.json` file

At the moment there is no tooling around the `apps.json` file. It follows the json schema defined in
the [app store types](https://github.com/opencloud-eu/web/blob/main/packages/web-app-app-store/src/types.ts).
If you want to add your own app feel free to make a pull request in this repository.

## Assets of your app

We currently support having a cover image and screenshots for each app.

### Image formats

All images should have a 3:2 aspect ratio. All native image formats are supported. We recommend to use PNG or JPEG.
An animated GIF as cover image will only be accepted if the animation is subtle.

### Folder structure

To keep maintenance efforts low we've decided to use a certain folder structure (see below) and ask you to follow it
as well when adding assets for your app.

- `<org-name>/<repo-name>/<app-name if needed>/cover.png` for your cover image
- `<org-name>/<repo-name>/<app-name if needed>/screenshots/1.png` for your screenshots

We stick to the rule that if a repo is a monorepo hosting multiple apps we include the app name in the path. If the repo
hosts only one app we don't include the app name in the path.

### Licensing

Please make sure that the assets you add to this repo have a license that allows us to keep them in this repository
and to show them in the OpenCloud Web App Store. If you are not sure about the license of an asset, please do not add it.

## Downloadable app versions

Our Web Apps have certain requirements for serving them via OpenCloud. See the
[developer documentation](https://docs.opencloud.eu/services/web/#web-apps) for details. Your app must follow
these requirements to be served via the Web App Store, otherwise we cannot accept your app. Simply put,
your app must be downloadable as a `.zip` file and must contain a `manifest.json` file in the root of the zip file
which specifies the entry point of your app. Downloadable app versions should be referenced under the `versions` key
in the `apps.json` file.
