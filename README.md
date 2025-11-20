
## How to Run This (Important!)

PWAs will not work if you just double-click `app.html` from your file explorer. They must be served over HTTP/HTTPS.

  1. Create a folder and put `app.html`, `manifest.json`, and `sw.js` inside.

  2. Add an icon: Add any PNG image (192x192 pixels is best) to that folder and name it `icon.png`.

  3. Start a local server:

    * VS Code: Right-click `app.html` and select "Open with Live Server".

    * Python: Open your terminal in that folder and type `python -m http.server`.

  4. Install: Open the URL (e.g., `http://127.0.0.1:8000`) in Chrome or Edge. You will see an install icon in the address bar. Click it to install the app to your desktop.


## Command line support

  \#% open -a "YAML Diff Viewer" --args "/abs/path/to/file1.yaml" "/abs/path/to/file2.yaml"
  
  \#%% not work because of file handler issue

  alias yamldiff='/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --app-id=ebkggbkgjehkpdoekihefdnkghbnjeko'
