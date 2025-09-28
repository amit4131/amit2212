# BioHack Fit MVP

This repository contains a static HTML prototype for the BioHack Fit dashboard.

## Running the in-app self-tests

The UI includes a built-in `runTests()` harness that can be triggered from the "התאמה אישית" tab. To execute it locally:

1. Serve the project (for example `python -m http.server 8000`).
2. Open `http://localhost:8000/index.html` in a browser.
3. Switch to the customization tab ("התאמה אישית"). The tests run automatically and render their latest results inside the "בדיקות" panel. You can also execute them manually from the console with `window.runTests()`.

All tests should pass; if any fail, inspect the console output for details.
