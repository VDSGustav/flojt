# flojt
Example of showing how the modelviewer looks on a website.
# How to run:
Modelviewer can not load models in localhost so you either have to run it in something like xampp, wamp or put on a server.
We have one running at https://cgpackshot.se:447/flojt/
Though it may not be up to date.

# Using the modelviewer:
These are needed to load the modelviewer
```
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
<script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
```
This script doesn't do anything but is where we'd put additional functionality related to the modelviewer
```
<script src="scripts/flojtScript.js">
```

To implement into your own website copy the <model-viewer> element found in index.html, link src="" to where the .glb is found, in our case it would be models="flojt.glb", it can be loaded from other servers as well.
