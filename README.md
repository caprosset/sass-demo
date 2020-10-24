# SASS DEMO

### Presentation
Find the slides [here](https://docs.google.com/presentation/d/1Rma9AUsuwSWOzHzDwPvmyrLfaBCkLX2g5Y3L1jcYV_8/)

### Concepts
* Variables
* Modules
* Nesting
* Inheritance
* Mixins

### File structure
```
.
├── login.html
├── signup.html
├── scss
│   ├── style.scss
│   ├── _variables.scss
│   └── _mixins.scss
└── css
    └── style.css
```

### Settings.json

In VS Code, open the file settings.json with `Ctrl (or Cmd) + shift + P`    
and select "Preferences: Open Settings (JSON)"

Add the following lines:

```json
  "liveSassCompile.settings.autoprefix": [],
   "liveSassCompile.settings.formats": [
       {
           "format": "expanded",
           "extensionName": ".css",
           "savePath": "/css"
       }
   ],
   "liveSassCompile.settings.generateMap": false,
   "liveServer.settings.donotVerifyTags": true
```