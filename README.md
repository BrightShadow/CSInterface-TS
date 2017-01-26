# Custom implementation of Adobe extensions CSInterface library, in Typescript

The implementation has 1:1 functionality as [`CSInterface.js`](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_7.x/CSInterface.js)
which can be found [`here`](https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_7.x).

The implementation is fully documented - the documentation is based on original Adobe documentation from .js file.

## Usage

Just install [my NPM package](https://www.npmjs.com/package/csinterface-ts):
```
npm install csinterface-ts
```

### When using with Aurelia

1. Install package first
```
npm install csinterface-ts
```

2. Add package to your bundles aurelia configuration in your root directory, so that you will get this loaded when your plugin/extension will be deployed. In this case edit `aurelia_project/aurelia.json`. Add one line in the section `"bundles"`, in subsection `"name": "vendor-bundle.js"` inside a subsection `"dependencies"`:
```
        "bundles": [
            {
                "name": "app-bundle.js",
                
                ....
            },
            {
              "name": "vendor-bundle.js",
              
              ....
              
              "dependencies": [
                  
                  ....
                  
                  "csinterface-ts",
                  
                  ....
              ]
          }
      ]
```

Found bugs/issues? Please report them here on Github in section [Issues](https://github.com/BrightShadow/CSInterface-TS/issues).
