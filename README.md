# api documentation for  [node-gyp (v3.6.0)](https://github.com/nodejs/node-gyp#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-gyp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-gyp)
#### Node.js native addon build tool

[![NPM](https://nodei.co/npm/node-gyp.png?downloads=true)](https://www.npmjs.com/package/node-gyp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gyp/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node_gyp_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gyp/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-node-gyp/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "email": "nathan@tootallnate.net",
        "url": "http://tootallnate.net"
    },
    "bin": {
        "node-gyp": "./bin/node-gyp.js"
    },
    "bugs": {
        "url": "https://github.com/nodejs/node-gyp/issues"
    },
    "dependencies": {
        "fstream": "^1.0.0",
        "glob": "^7.0.3",
        "graceful-fs": "^4.1.2",
        "minimatch": "^3.0.2",
        "mkdirp": "^0.5.0",
        "nopt": "2 || 3",
        "npmlog": "0 || 1 || 2 || 3 || 4",
        "osenv": "0",
        "request": "2",
        "rimraf": "2",
        "semver": "~5.3.0",
        "tar": "^2.0.0",
        "which": "1"
    },
    "description": "Node.js native addon build tool",
    "devDependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.0.0",
        "require-inject": "~1.3.0",
        "tape": "~4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7474f63a3a0501161dda0b6341f022f14c423fa6",
        "tarball": "https://registry.npmjs.org/node-gyp/-/node-gyp-3.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "8d04acfdf59ff1015d209feb23acd88d593095a1",
    "homepage": "https://github.com/nodejs/node-gyp#readme",
    "installVersion": 9,
    "keywords": [
        "native",
        "addon",
        "module",
        "c",
        "c++",
        "bindings",
        "gyp"
    ],
    "license": "MIT",
    "main": "./lib/node-gyp.js",
    "maintainers": [
        {
            "name": "TooTallNate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "bnoordhuis",
            "email": "info@bnoordhuis.nl"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "isaacs",
            "email": "i@izs.me"
        },
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        }
    ],
    "name": "node-gyp",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nodejs/node-gyp.git"
    },
    "scripts": {
        "test": "tape test/test-*"
    },
    "version": "3.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-gyp](#apidoc.module.node-gyp)
1.  [function <span class="apidocSignatureSpan">node-gyp.</span>Gyp ()](#apidoc.element.node-gyp.Gyp)
1.  object <span class="apidocSignatureSpan">node-gyp.</span>Gyp.prototype
1.  object <span class="apidocSignatureSpan">node-gyp.</span>Gyp.prototype.configDefs
1.  object <span class="apidocSignatureSpan">node-gyp.</span>Gyp.prototype.configDefs.arch.prototype

#### [module node-gyp.Gyp](#apidoc.module.node-gyp.Gyp)
1.  [function <span class="apidocSignatureSpan">node-gyp.</span>Gyp ()](#apidoc.element.node-gyp.Gyp.Gyp)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.</span>super_ ()](#apidoc.element.node-gyp.Gyp.super_)

#### [module node-gyp.Gyp.prototype](#apidoc.module.node-gyp.Gyp.prototype)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>parseArgv (argv)](#apidoc.element.node-gyp.Gyp.prototype.parseArgv)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>spawn (command, args, opts)](#apidoc.element.node-gyp.Gyp.prototype.spawn)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>usage ()](#apidoc.element.node-gyp.Gyp.prototype.usage)
1.  object <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>aliases
1.  object <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>configDefs
1.  object <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>package
1.  object <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>shorthands
1.  string <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>version

#### [module node-gyp.Gyp.prototype.configDefs](#apidoc.module.node-gyp.Gyp.prototype.configDefs)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>arch ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>cafile ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.cafile)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>debug ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.debug)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>devdir ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.devdir)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>directory ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.directory)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>dist-url ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.dist-url)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>ensure ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.ensure)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>help ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.help)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>jobs ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.jobs)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>loglevel ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.loglevel)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>make ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.make)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>msvs_version ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.msvs_version)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>nodedir ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.nodedir)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>proxy ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.proxy)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>python ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.python)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>solution ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.solution)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>tarball ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.tarball)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>thin ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.thin)

#### [module node-gyp.Gyp.prototype.configDefs.arch.prototype](#apidoc.module.node-gyp.Gyp.prototype.configDefs.arch.prototype)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>entityify ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.entityify)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>isAlpha ( )](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isAlpha)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>isDigit ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isDigit)
1.  [function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>supplant (e)](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.supplant)



# <a name="apidoc.module.node-gyp"></a>[module node-gyp](#apidoc.module.node-gyp)

#### <a name="apidoc.element.node-gyp.Gyp"></a>[function <span class="apidocSignatureSpan">node-gyp.</span>Gyp ()](#apidoc.element.node-gyp.Gyp)
- description and source-code
```javascript
function Gyp() {
  var self = this

  this.devDir = ''
  this.commands = {}

  commands.forEach(function (command) {
    self.commands[command] = function (argv, callback) {
      log.verbose('command', command, argv)
      return require('./' + command)(self, argv, callback)
    }
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-gyp.Gyp"></a>[module node-gyp.Gyp](#apidoc.module.node-gyp.Gyp)

#### <a name="apidoc.element.node-gyp.Gyp.Gyp"></a>[function <span class="apidocSignatureSpan">node-gyp.</span>Gyp ()](#apidoc.element.node-gyp.Gyp.Gyp)
- description and source-code
```javascript
function Gyp() {
  var self = this

  this.devDir = ''
  this.commands = {}

  commands.forEach(function (command) {
    self.commands[command] = function (argv, callback) {
      log.verbose('command', command, argv)
      return require('./' + command)(self, argv, callback)
    }
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.super_"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.</span>super_ ()](#apidoc.element.node-gyp.Gyp.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-gyp.Gyp.prototype"></a>[module node-gyp.Gyp.prototype](#apidoc.module.node-gyp.Gyp.prototype)

#### <a name="apidoc.element.node-gyp.Gyp.prototype.parseArgv"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>parseArgv (argv)](#apidoc.element.node-gyp.Gyp.prototype.parseArgv)
- description and source-code
```javascript
function parseOpts(argv) {
  this.opts = nopt(this.configDefs, this.shorthands, argv)
  this.argv = this.opts.argv.remain.slice()

  var commands = this.todo = []

  // create a copy of the argv array with aliases mapped
  argv = this.argv.map(function (arg) {
    // is this an alias?
    if (arg in this.aliases) {
      arg = this.aliases[arg]
    }
    return arg
  }, this)

  // process the mapped args into "command" objects ("name" and "args" props)
  argv.slice().forEach(function (arg) {
    if (arg in this.commands) {
      var args = argv.splice(0, argv.indexOf(arg))
      argv.shift()
      if (commands.length > 0) {
        commands[commands.length - 1].args = args
      }
      commands.push({ name: arg, args: [] })
    }
  }, this)
  if (commands.length > 0) {
    commands[commands.length - 1].args = argv.splice(0)
  }

  // support for inheriting config env variables from npm
  var npm_config_prefix = 'npm_config_'
  Object.keys(process.env).forEach(function (name) {
    if (name.indexOf(npm_config_prefix) !== 0) return
    var val = process.env[name]
    if (name === npm_config_prefix + 'loglevel') {
      log.level = val
    } else {
      // add the user-defined options to the config
      name = name.substring(npm_config_prefix.length)
      // gyp@741b7f1 enters an infinite loop when it encounters
      // zero-length options so ensure those don't get through.
      if (name) this.opts[name] = val
    }
  }, this)

  if (this.opts.loglevel) {
    log.level = this.opts.loglevel
  }
  log.resume()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.spawn"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>spawn (command, args, opts)](#apidoc.element.node-gyp.Gyp.prototype.spawn)
- description and source-code
```javascript
function spawn(command, args, opts) {
  if (!opts) opts = {}
  if (!opts.silent && !opts.stdio) {
    opts.stdio = [ 0, 1, 2 ]
  }
  var cp = child_process.spawn(command, args, opts)
  log.info('spawn', command)
  log.info('spawn args', args)
  return cp
}
```
- example usage
```shell
...
      return path.extname(arg) == '.sln'
    })
    if (!hasSln) {
      argv.unshift(gyp.opts.solution || guessedSolution)
    }
  }

  var proc = gyp.spawn(command, argv)
  proc.on('exit', onExit)
}

/**
 * Invoked after the make/msbuild command exits.
 */
...
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.usage"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.</span>usage ()](#apidoc.element.node-gyp.Gyp.prototype.usage)
- description and source-code
```javascript
function usage() {
  var str = [
      ''
    , '  Usage: node-gyp <command> [options]'
    , ''
    , '  where <command> is one of:'
    , commands.map(function (c) {
        return '    - ' + c + ' - ' + require('./' + c).usage
      }).join('\n')
    , ''
    , 'node-gyp@' + this.version + '  ' + path.resolve(__dirname, '..')
    , 'node@' + process.versions.node
  ].join('\n')
  return str
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-gyp.Gyp.prototype.configDefs"></a>[module node-gyp.Gyp.prototype.configDefs](#apidoc.module.node-gyp.Gyp.prototype.configDefs)

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.arch"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>arch ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.cafile"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>cafile ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.cafile)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.debug"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>debug ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.debug)
- description and source-code
```javascript
function Boolean() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.devdir"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>devdir ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.devdir)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.directory"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>directory ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.directory)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.dist-url"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>dist-url ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.dist-url)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.ensure"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>ensure ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.ensure)
- description and source-code
```javascript
function Boolean() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.help"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>help ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.help)
- description and source-code
```javascript
function Boolean() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.jobs"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>jobs ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.jobs)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.loglevel"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>loglevel ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.loglevel)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.make"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>make ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.make)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.msvs_version"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>msvs_version ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.msvs_version)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.nodedir"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>nodedir ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.nodedir)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.proxy"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>proxy ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.proxy)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.python"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>python ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.python)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.solution"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>solution ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.solution)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.tarball"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>tarball ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.tarball)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.thin"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.</span>thin ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.thin)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-gyp.Gyp.prototype.configDefs.arch.prototype"></a>[module node-gyp.Gyp.prototype.configDefs.arch.prototype](#apidoc.module.node-gyp.Gyp.prototype.configDefs.arch.prototype)

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.entityify"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>entityify ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.entityify)
- description and source-code
```javascript
entityify = function (){return this.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;"
)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isAlpha"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>isAlpha ( )](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isAlpha)
- description and source-code
```javascript
isAlpha = function ( ){return this>="a"&&this<="z\uffff"||this>="A"&&this<="Z\uffff"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isDigit"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>isDigit ()](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.isDigit)
- description and source-code
```javascript
isDigit = function (){return this>="0"&&
this<="9"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.supplant"></a>[function <span class="apidocSignatureSpan">node-gyp.Gyp.prototype.configDefs.arch.prototype.</span>supplant (e)](#apidoc.element.node-gyp.Gyp.prototype.configDefs.arch.prototype.supplant)
- description and source-code
```javascript
supplant = function (e){return this.replace(/\{([^{}]*)\}/g,function(t,n){var r=e[n];return typeof
r=="string"||typeof r=="number"?r:t})}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
