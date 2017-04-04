# api documentation for  [modernizr (v3.4.0)](https://github.com/Modernizr/Modernizr#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-modernizr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-modernizr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-modernizr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-modernizr)
#### Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

[![NPM](https://nodei.co/npm/modernizr.png?downloads=true)](https://www.npmjs.com/package/modernizr)

[![apidoc](https://npmdoc.github.io/node-npmdoc-modernizr/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-modernizr_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-modernizr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-modernizr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-modernizr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Modernizr",
        "url": "https://modernizr.com/"
    },
    "bin": {
        "modernizr": "./bin/modernizr"
    },
    "bugs": {
        "url": "https://github.com/Modernizr/Modernizr/issues"
    },
    "contributors": [
        {
            "name": "Faruk Ates",
            "url": "https://twitter.com/KuraFire"
        },
        {
            "name": "Paul Irish",
            "url": "https://twitter.com/paul_irish"
        },
        {
            "name": "Alex Sexton",
            "url": "https://twitter.com/SlexAxton"
        },
        {
            "name": "Ryan Seddon",
            "url": "https://twitter.com/ryanseddon"
        },
        {
            "name": "Patrick Kettner",
            "url": "https://twitter.com/patrickkettner"
        },
        {
            "name": "Stu Cox",
            "url": "https://twitter.com/stucoxmedia"
        },
        {
            "name": "Richard Herrera",
            "url": "https://twitter.com/doctyper"
        }
    ],
    "dependencies": {
        "doctrine": "1.2.3",
        "file": "0.2.2",
        "find-parent-dir": "0.3.0",
        "lodash": "4.17.4",
        "mkdirp": "0.5.1",
        "remarkable": "^1.6.2",
        "requirejs": "2.1.22",
        "yargs": "6.6.0"
    },
    "description": "Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.",
    "devDependencies": {
        "@alrra/travis-scripts": "1.1.1",
        "expect.js": "0.3.1",
        "grunt": "1.0.1",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-connect": "1.0.2",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-jade": "1.0.0",
        "grunt-coveralls": "1.0.1",
        "grunt-env": "0.4.4",
        "grunt-eslint": "^18.1.0",
        "grunt-istanbul": "0.7.1",
        "grunt-mocha": "0.4.15",
        "grunt-mocha-test": "0.12.7",
        "grunt-saucelabs": "9.0.0",
        "joi": "6.10.0",
        "jquery": "1.12.4",
        "json3": "3.3.2",
        "load-grunt-tasks": "3.5.2",
        "proxyquire": "1.7.11",
        "serve-static": "^1.10.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "2eb7617677a6b6bb72a2d3b60fe4e702c4c9d067",
        "tarball": "https://registry.npmjs.org/modernizr/-/modernizr-3.4.0.tgz"
    },
    "gitHead": "32fd455750c53a6233b8a9ebd5742adc5b9af054",
    "greenkeeper": {
        "ignore": [
            "joi",
            "grunt-eslint"
        ]
    },
    "homepage": "https://github.com/Modernizr/Modernizr#readme",
    "inch": {
        "files": {
            "included": [
                "feature-detects/",
                "src/"
            ]
        }
    },
    "keywords": [
        "html5",
        "css3",
        "browser",
        "feature detection"
    ],
    "license": "MIT",
    "main": "./lib/cli",
    "maintainers": [
        {
            "name": "patrickkettner",
            "email": "patrickkettner@gmail.com"
        },
        {
            "name": "paulirish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "slexaxton",
            "email": "alexsexton@gmail.com"
        },
        {
            "name": "ryanseddon",
            "email": "seddon.ryan@gmail.com"
        },
        {
            "name": "doctyper",
            "email": "rich@doctyper.com"
        },
        {
            "name": "stucox",
            "email": "stuart.cox@gmail.com"
        }
    ],
    "name": "modernizr",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Modernizr/Modernizr.git"
    },
    "scripts": {
        "test": "grunt test --stack"
    },
    "version": "3.4.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module modernizr](#apidoc.module.modernizr)
1.  [function <span class="apidocSignatureSpan">modernizr.</span>build ()](#apidoc.element.modernizr.build)
1.  [function <span class="apidocSignatureSpan">modernizr.</span>metadata (cb)](#apidoc.element.modernizr.metadata)
1.  [function <span class="apidocSignatureSpan">modernizr.</span>options (cb, allMetadata)](#apidoc.element.modernizr.options)



# <a name="apidoc.module.modernizr"></a>[module modernizr](#apidoc.module.modernizr)

#### <a name="apidoc.element.modernizr.build"></a>[function <span class="apidocSignatureSpan">modernizr.</span>build ()](#apidoc.element.modernizr.build)
- description and source-code
```javascript
function build() {
  return _build(generate, generateBanner, pkg).apply(undefined, arguments);
}
```
- example usage
```shell
...
#### Building

A 'build' method is exposed for generating custom Modernizr builds. Example:

'''javascript
var modernizr = require("modernizr");

modernizr.build({}, function (result) {
  console.log(result); // the build
});
'''

The first parameter takes a JSON object of options and feature-detects to include. See ['lib/config-all.json'](lib/config-all.json
) for all available options.

The second parameter is a function invoked on task completion.
...
```

#### <a name="apidoc.element.modernizr.metadata"></a>[function <span class="apidocSignatureSpan">modernizr.</span>metadata (cb)](#apidoc.element.modernizr.metadata)
- description and source-code
```javascript
function metadata(cb) {
  var tests = [];
  var md = new Remarkable();
  file.walkSync(viewRoot, function(start, dirs, files) {
    files.forEach(function(file) {
      if (file === '.DS_Store') {
        return;
      }
      var test = fs.readFileSync(start + '/' + file, 'utf8');
      // TODO :: make this regex not suck
      var metaRE = /\/\*\!([\s\S]*)\!\*\//m;
      var matches = test.match(metaRE);
      var docRE = /\/\*\sDOC([\s\S]*?)\*\//m;
      var docmatches = test.match(docRE);
      var depRE = /define\((\[[^\]]*\]),/;
      var depMatches = test.match(depRE);

      var metadata;

      if (matches && matches[1]) {
        try {
          metadata = JSON.parse(matches[1]);
        } catch (e) {
          throw new Error('Error Parsing Metadata: ' + file + '\nInput: '' + matches[1] + ''');
        }
      }
      else {
        metadata = {};
      }

      var docs = null;

      if (docmatches && docmatches[1]) {
        docs = md.render(docmatches[1].trim());
      }

      metadata.doc = docs;

      var deps = [];
      var matchedDeps;

      if (depMatches && depMatches[1]) {
        try {
          matchedDeps = JSON.parse(depMatches[1].replace(/'/g, '"'));
        } catch (e) {
          throw new Error('Couldn\'t parse dependencies for '' + file + '':\n'' + depMatches[1] + '\n'');
        }
        matchedDeps.forEach(function(dep) {
          if (dep === 'Modernizr') {
            return;
          }
          deps.push(dep);
        });
      } else {
        throw new Error('Couldn\'t find the define for '' + file + ''');
      }
      metadata.deps = deps;

      var baseDir = __dirname.replace(/lib$/, '');
      metadata.path = './' + (start + '/' + file).replace(baseDir, '').replace(/\\/g, '/');
      metadata.amdPath = metadata.path.replace(/^\.\/feature\-detects/, 'test').replace(/\.js$/i, '');

      if (!metadata.name) {
        metadata.name = metadata.amdPath;
      }

      var pfs = [];
      if (metadata.polyfills && metadata.polyfills.length) {
        metadata.polyfills.forEach(function(polyname) {
          if (polyfills[polyname]) {
            pfs.push(polyfills[polyname]);
          }
          else {
            throw new Error(metadata.name + ': Polyfill not found in '' + file + '': ' + polyname);
          }
        });
      }
      metadata.polyfills = pfs;

      if (!metadata.async) {
        metadata.async = false;
      }

      if (!metadata.notes) {
        metadata.notes = [];
      }

      if (!metadata.warnings) {
        metadata.warnings = [];
      }

      if (!metadata.caniuse) {
        metadata.caniuse = null;
      }

      if (!metadata.cssclass && metadata.property) {
        metadata.cssclass = metadata.property;
      } else {
        metadata.cssclass = null;
      }

      // Maybe catch a bug
      if (!metadata.doc && metadata.docs) {
        metadata.doc = metadata.docs;
        delete metadata.docs;
      }

      // If you want markdown parsed code minus the docs and metadata, this'll do it.
      // Off by default for now.
      // metadata.code =  md.render(''''javascript\n' + test.replace(metaRE, '').replace(docRE, '') + '\n'''');

      if (!metadata.tags) {
        metadata.tags = [];
      }

      if (!metadata.authors) {
        metadata.authors = [];
      }

      if (!metadata.knownBugs) {
        metadata.knownBugs = [];
      }

      tests.push(metadata);
    });
  });

  if (cb && typeof cb == 'function') {
    return cb(tests);
  }
  return tests;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.modernizr.options"></a>[function <span class="apidocSignatureSpan">modernizr.</span>options (cb, allMetadata)](#apidoc.element.modernizr.options)
- description and source-code
```javascript
function options(cb, allMetadata) {
  var opts;

  file.walkSync(srcRoot, function(start, dirs, files) {
    opts = _.chain(files)
      .map(function(file) {
        var srcFile = fs.readFileSync(start + '/' + file, 'utf8');
        var docs = srcFile.match(jsdocRE);

        if (docs) {
          docs = docs
            .map(stripComments)
            .map(function(str) {
              return jsdoc.parse(str, {
                sloppy: true,
                tags: [
                  'access',
                  'author',
                  'class',
                  'example',
                  'function',
                  'memberOf',
                  'memberof',
                  'name',
                  'optionName',
                  'optionProp',
                  'param',
                  'params',
                  'preserve',
                  'private',
                  'returns',
                  'type'
                ]
              });
            });

          var option = _.chain(docs)
            .flatten()
            .filter(function(doc) {
              if (allMetadata) {
                return true;
              } else {
                return doc && _.some(doc.tags, {title: 'optionName'});
              }
            })
            .map(function(opt) {
              if (allMetadata) {
                return opt;
              } else {
                var tags = opt.tags.filter(function(tag) {
                  return tag.title.indexOf('option') === 0;
                });

                return {
                  name: _.filter(tags, {title: 'optionName'})[0].description,
                  property: _.filter(tags, {title: 'optionProp'})[0].description
                };
              }
            })
            .value();

          return option;
        }
      })
      .filter(function(doc) {
        return doc && doc.length;
      })
      .flatten()
      .value();

  });

  if (cb) {
    cb(opts);
  }

  return opts;

}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
