# api documentation for  [node-bourbon (v4.2.8)](https://github.com/lacroixdesign/node-bourbon#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-bourbon.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-bourbon) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-bourbon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-bourbon)
#### node-sass wrapper for thoughtbot's bourbon library

[![NPM](https://nodei.co/npm/node-bourbon.png?downloads=true)](https://www.npmjs.com/package/node-bourbon)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-bourbon/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-bourbon_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-bourbon/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-bourbon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-bourbon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael LaCroix",
        "email": "michael@lacroixdesign.net",
        "url": "http://www.lacroixdesign.net"
    },
    "bugs": {
        "url": "https://github.com/lacroixdesign/node-bourbon/issues"
    },
    "dependencies": {
        "bourbon": "^4.2.6"
    },
    "description": "node-sass wrapper for thoughtbot's bourbon library",
    "devDependencies": {
        "chai": "^1.10.0",
        "mocha": "^2.1.0",
        "node-sass": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e444f1f09434ab7650ea318c28e2e103d3f942cd",
        "tarball": "https://registry.npmjs.org/node-bourbon/-/node-bourbon-4.2.8.tgz"
    },
    "gitHead": "bbc9c8aa31a7678e1d0edde2f60ed3dfe391afb5",
    "homepage": "https://github.com/lacroixdesign/node-bourbon#readme",
    "keywords": [
        "sass",
        "css"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "iamlacroix",
            "email": "michael@lacroixdesign.net"
        }
    ],
    "name": "node-bourbon",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/lacroixdesign/node-bourbon.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --recursive --growl"
    },
    "version": "4.2.8"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-bourbon](#apidoc.module.node-bourbon)
1.  [function <span class="apidocSignatureSpan">node-bourbon.</span>with ()](#apidoc.element.node-bourbon.with)
1.  object <span class="apidocSignatureSpan">node-bourbon.</span>includePaths



# <a name="apidoc.module.node-bourbon"></a>[module node-bourbon](#apidoc.module.node-bourbon)

#### <a name="apidoc.element.node-bourbon.with"></a>[function <span class="apidocSignatureSpan">node-bourbon.</span>with ()](#apidoc.element.node-bourbon.with)
- description and source-code
```javascript
with = function () {
  var paths  = Array.prototype.slice.call(arguments);
  return [].concat.apply([bourbon.includePaths], paths);
}
```
- example usage
```shell
...
The 'with()' function will include any additional paths you pass as arguments.

Returns an array of paths.

'''javascript
var bourbon = require('node-bourbon');
// Any of these will return an array of Bourbon paths plus your custom path(s)
bourbon.with('path/to/stylesheets')
bourbon.with('path/to/stylesheets1', 'path/to/stylesheets2')
bourbon.with(['path/to/stylesheets1', 'path/to/stylesheets2'])
'''

### includePaths Property

The 'includePaths' property returns an array of Bourbon's paths to use in your config.
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
