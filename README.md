# blueSheet.js
Simple python kivy like (hopefully) js framework

# Html usage Structure
```mermaid
graph TD;
    A["Import 'blueSheet.js'"]-->B["Import 'blueSheet.cssc"];
    B-->C["Import custom css (if any)"];
    C-->D["Add 'Data class' and other class to use in 'App.js'"];
    D-->E["Add 'App.js' that init and customize the page look theme and behavior"];
```

# Requirements
The js will try to load it's requirements auto with best optimization (that I know)
* hammer.js

# Browser support
* Since it uses `class`, so say goodbye to ES6 unsupported browsers. I'm too lazy to support older ones.
* List will be available in future
* Using pure js till now, jQuery may be used later
