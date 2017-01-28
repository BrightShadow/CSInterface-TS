# Custom implementation of Adobe extensions CSInterface library, in Typescript

Related pages, and additional resource where you can find more information about Adobe HTML extensions.

[![CSInterface-TS](https://github.com/BrightShadow/CSInterface-TS/blob/master/docs/npm-logo.png)](https://www.npmjs.com/package/csinterface-ts)
[![TypeScript](https://github.com/BrightShadow/CSInterface-TS/blob/master/docs/TS-logo.png)](https://www.typescriptlang.org/)
[![Adobe Creative Cloud](https://github.com/BrightShadow/CSInterface-TS/blob/master/docs/adobe-cc-logo.png)](http://www.adobe.com/creativecloud.html)
[![CEP Team](https://github.com/BrightShadow/CSInterface-TS/blob/master/docs/CEP-logo.png)](https://github.com/Adobe-CEP)

The implementation has 1:1 functionality as [`CSInterface.js`](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_7.x/CSInterface.js)
which can be found [`here`](https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_7.x).

The implementation is fully documented - the documentation is based on original Adobe documentation from .js file.

## Usage

Just install [my NPM package](https://www.npmjs.com/package/csinterface-ts):
```bash
npm install csinterface-ts
```

### When using with Aurelia

1. Install package first
```bash
npm install csinterface-ts
```

2. Add package to your bundles aurelia configuration in your root directory, so that you will get this loaded when your plugin/extension will be deployed. In this case edit `aurelia_project/aurelia.json`. Add one line in the section `"bundles"`, in subsection `"name": "vendor-bundle.js"` inside a subsection `"dependencies"`:
```js
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
                  
                  "csinterface-ts",  // <-- add it here
                  
                  ....
              ]
          }
      ]
```

Found bugs/issues? Please report them here on Github in section [Issues](https://github.com/BrightShadow/CSInterface-TS/issues).
