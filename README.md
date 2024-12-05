# matthew-gerstbrein.github.io
This repository contains the underlying data for creating the webpage.
Here is the basic philosophy for website design structuring:
-Structure = HTML
-Presentation = CSS
-Behavior = JavaScript

The scripts.js file currently updates the first 'h1' heading to be the color black. But in principle, such aesthetic choices should be specified in the .css file.
But this is just a simple use case that incorporates a JavaScript file; most likely we won't need to leverage many genuine use cases of JavaScript, if at all.

Separately, I made a _config.yml file. This type of file allows for some configuration settings to be specified, if desired. I planned to use it, but ended up not seeing the (net) benefit of it yet.
The basic idea is that it could be used to ignore certain files so as to revert to the 'layouts/default.html' layout file. (The file equivalent of 'commenting out' code.) So the option is there, just hasn't seemed worth it yet.
