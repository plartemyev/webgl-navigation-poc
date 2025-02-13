WebGL navigational cube proof of concept
===
![screenshot]  
Just a little experiment.  
You could play with it on my [demo page](https://peekytoe.crabdance.com/webgl-navigation-poc).

NOTES
----
The idea was to detect mouse clicks on a rotating cube's faces.  
Cube faces under mouse cursor are highlighted by a moving point light, which is hovering
with the mouse cursor projected to the second, invisible cube, which is slightly bigger in
size than the visible one. It was made so the point light would be slightly above the main
cube to light it more uniformly.

Based on [three.js](http://github.com/mrdoob/three.js/)

[screenshot]: screenshot.png "Usage illustration"
