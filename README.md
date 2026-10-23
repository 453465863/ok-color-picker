# OK Color Picker

**A browser-based color study workspace for digital artists, created by [Study EZ](https://github.com/453465863).** Turn a visual reference into an interactive palette: sample colors from an image, arrange palette cards, and save your exploration in the browser.

> **Current release:** Chinese interface. An English version is planned for a future release.

## What you can do

- Bring in a reference image and place or move color-sampling points.
- Build and adjust interactive palette cards beside the image.
- Save projects in the browser and continue on desktop or mobile.

## Try the live demo

Welcome to try OK Color Picker and watch the short project PV:

| 🎨 **Try the live demo** | 🎬 **Watch the project PV** |
| --- | --- |
| [**Open OK Color Picker**](https://studyez.pythonanywhere.com/#/invite/CwTZsb-krTD7gadyzjmRdeTKJ9iw5m3gKaAUeJnlYVQ) | [**▶ Watch the OK Color Picker preview**](./assets/ok-color-picker-promo.mov) |
| Use the invitation link to open the hosted tool. | See the color-picking workspace and its desktop/mobile presentation. |

Or open the [main site](https://studyez.pythonanywhere.com/) and enter the TOOL BOX access key `ookk` if prompted.

These access details are intentionally public for the demo: anyone who can view this public repository can use them. The hosted demo includes the responsive desktop and mobile layouts.

## Source and local use

The current source matches the PythonAnywhere tool file byte for byte. The page is self-contained and has no build step or third-party runtime dependency. Open [`index.html`](./index.html) in a modern browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data and backend behavior

- Work in progress is stored in the browser's local IndexedDB database (`hue-studio-r1`). Personal color points and saved projects are not included in this repository.
- Feedback submission and visit statistics call the TOOL BOX PythonAnywhere API. Those features work on the hosted demo when access is granted; they are not provided by GitHub Pages or by opening the downloaded HTML locally.
- No API key, server secret, user database, exported project, or private TOOL BOX server code is included here.

## License

This source is provided under the [PolyForm Noncommercial License 1.0.0](./LICENSE). Noncommercial use, modification, and distribution are allowed under its terms. Commercial use is not granted by this license; contact the copyright holder to request separate permission.

This is **source-available**, not OSI-defined open-source software, because the license restricts commercial use.

## Attribution

This is an independent project and is not affiliated with or endorsed by TourBox. The original page title and source comments mention TourBox when describing design inspiration; the source explicitly does not claim to reproduce TourBox's private algorithm.
