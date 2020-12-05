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

### SASS installation

#### Option 1: NPM package “sass”
To install sass globally:
```
$ npm install -g sass 
```
To make sure it's correctly installed:
```
$ sass --version
````
To compile:
```
$ sass scss/input.scss css/output.cs
```

#### Option 2: VS Code “Live Sass Compiler” extension  
Download it here:
[https://github.com/ritwickdey/vscode-live-sass-compiler](https://github.com/ritwickdey/vscode-live-sass-compiler)

and just click the "Watch SASS" button on the bottom of the code editor to compile your scss files.

### Customize SASS setttings in your settings.json file

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
