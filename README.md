# Awesome Apps

An opinionated list of awesome [OpenCloud](https://github.com/opencloud-eu/opencloud) apps, extensions, services and other resources.

## Attention please!

> :warning: While we are proud to present you these resources, we can't give any guarantees that they will work for you or that they will be stable. Feel free to open issues in the respective, linked repositories or contribute to the projects in any other way.

If you'd like to contribute to this list, please feel free to make a pull request.

## Table of Contents

* [Build your own](#build-your-own)
* [Viewers & Editors](#viewers--editors)
* [File Actions](#file-actions)
* [File Sidebar Panels](#file-sidebar-panels)
* [Global Progress Bars](#global-progress-bars)

---

## OpenCloud Apps and Extensions

Please follow the steps provided in our [developer documentation](https://docs.opencloud.eu/services/web/#web-apps) if you want to install any of the
following apps and extensions. For some of them there are released artifacts, others still need to be built from source code.

### Build your own

If you want to build your own apps and extensions, the place to start is our [app boilerplate](https://github.com/opencloud-eu/web-app-skeleton).
Reach out to us if you need any help. And don't forget to add your apps and extensions to this document. :-)

### Viewers & Editors

* [3D Model Viewer](https://github.com/saw-jan/web-app-3dmodel-viewer) - View 3D models based on [three.js](https://threejs.org)
* [Dicom Viewer](https://github.com/opencloud-eu/web-app-dicom-viewer) - Preview medical images based on [Cornerstone3D](https://www.cornerstonejs.org)
* [Draw.io](https://github.com/opencloud-eu/web-extensions/tree/main/packages/web-app-draw-io) - View and edit [draw.io](https://www.draw.io) diagrams
* [EPub Reader](https://github.com/opencloud-eu/web/tree/main/packages/web-app-epub-reader) - Read eBooks in .epub format using [epub.js](https://github.com/futurepress/epub.js)
* [GPX Viewer](https://github.com/dschmidt/web-app-gpx-viewer) - Render GPX files in a map view with [Leaflet](https://leafletjs.com)
* [PDF Viewer](https://github.com/opencloud-eu/web/tree/main/packages/web-app-pdf-viewer) - Read PDFs utilizing native browser pdf rendering 
* [Presentation Viewer](http://github.com/JankariTech/web-app-presentation-viewer) - Render markdown presentations with [reveal.js](https://revealjs.com)
* [Preview](https://github.com/opencloud-eu/web/tree/main/packages/web-app-preview) - View images, watch videos and listen to audio files
* [Text Editor](https://github.com/opencloud-eu/web/tree/main/packages/web-app-text-editor) - Edit markdown and plain text file types using [TOAST UI Editor](https://ui.toast.com/tui-editor) 

### File Actions

* [Cast](https://github.com/opencloud-eu/web-extensions/tree/main/packages/web-app-cast) - Send images and videos from your OpenCloud to your Chrome Cast.
* [Unzip](https://github.com/opencloud-eu/web-extensions/tree/main/packages/web-app-unzip) - Unzip .zip files directly into the current folder.

### File Sidebar Panels

* [Audio Information](https://github.com/opencloud-eu/web/blob/2137305f8ded7f845dc262c424b196742c76c9a0/packages/web-app-files/src/composables/extensions/useFileSideBars.ts#L166) - See audio file information like duration, author or title
* [EXIF / Image Information](https://github.com/opencloud-eu/web/blob/2137305f8ded7f845dc262c424b196742c76c9a0/packages/web-app-files/src/composables/extensions/useFileSideBars.ts#L145) - See EXIF information of photos

### Global Progress Bars

* [Nyan Cat](https://github.com/opencloud-eu/web-extensions/tree/main/packages/web-app-progress-bars) - A JS+CSS only Nyan Cat progress bar for the global loading state. 