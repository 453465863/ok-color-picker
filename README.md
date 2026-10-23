# OK Color Picker

An interactive color picking and palette workspace for digital art. The current release is the single-file version running on PythonAnywhere, including the responsive mobile layout.

**Status:** source-available release. The source matches the current PythonAnywhere tool file byte for byte.

## Preview

- **Online demo:** https://studyez.pythonanywhere.com/apps/ok-color-board/ (the TOOL BOX access gate may require an invitation)
- **Source file:** [`index.html`](./index.html)

The page is self-contained and has no build step or third-party runtime dependency. Open `index.html` in a modern browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data and backend behavior

- Work in progress is stored in the browser's local IndexedDB database (`hue-studio-r1`). Personal color points and saved projects are not included in this repository.
- Feedback submission and visit statistics call the TOOL BOX PythonAnywhere API. Those features work on the hosted demo when access is granted; they are not provided by GitHub Pages.
- No API key, server secret, user database, exported project, or private TOOL BOX server code is included here.

## License

This source is provided under the [PolyForm Noncommercial License 1.0.0](./LICENSE). Noncommercial use, modification, and distribution are allowed under its terms. Commercial use is not granted by this license; contact the copyright holder to request separate permission.

This is **source-available**, not OSI-defined open-source software, because the license restricts commercial use.

## Attribution

This is an independent project and is not affiliated with or endorsed by TourBox. The original page title and source comments mention TourBox when describing design inspiration; the source explicitly does not claim to reproduce TourBox's private algorithm.
