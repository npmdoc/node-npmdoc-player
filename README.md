# npmdoc-player

#### api documentation for  player (v0.6.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-player.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-player) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-player.svg)](https://travis-ci.org/npmdoc/node-npmdoc-player)

#### a command line player, supports play mp3 both from url and local stream.

[![NPM](https://nodei.co/npm/player.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/player)

- [https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-player/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-player/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "player",
    "version": "0.6.1",
    "description": "a command line player, supports play mp3 both from url and local stream.",
    "main": "dist/player.js",
    "bin": "bin/cli",
    "scripts": {
        "build": "node_modules/.bin/babel libs --out-dir dist --source-maps",
        "build-watch": "node_modules/.bin/babel libs --out-dir dist --source-maps --watch",
        "example-add": "DEBUG=player,player:* node examples/add.js",
        "example-shuffle": "DEBUG=player,player:* node examples/shuffle.js",
        "example-local": "DEBUG=player,player:* node examples/local.js",
        "example-stop": "DEBUG=player,player:* node examples/stop.js",
        "example-stop-at-last": "DEBUG=player,player:* node examples/stop-at-last.js",
        "example-playlist": "DEBUG=player,player:* node examples/playlist.js",
        "example-online": "DEBUG=player,player:* node examples/online.js",
        "example-online-proxy": "DEBUG=player,player:* node examples/online-proxy.js",
        "example-next": "DEBUG=player,player:* node examples/next.js",
        "example-metadata": "DEBUG=player,player:* node examples/metadata.js",
        "example-stream": "DEBUG=player,player:* node examples/stream.js 2>/dev/null"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/turingou/player.git"
    },
    "keywords": [
        "mp3",
        "cli",
        "audio",
        "player",
        "cli player"
    ],
    "author": "turing <o.u.turing@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/turingou/player/issues"
    },
    "files": [
        "bin",
        "libs",
        "dist",
        "README.md",
        "package.json"
    ],
    "dependencies": {
        "async": "^0.9.0",
        "follow-redirects": "0.0.7",
        "home": "^0.1.3",
        "keypress": "^0.2.1",
        "lame": "^1.2.2",
        "pcm-volume": "^1.0.0",
        "pool_stream": "0.0.2",
        "speaker": "^0.2.6",
        "underscore": "~1.6.0"
    },
    "devDependencies": {
        "babel": "^5.2.17",
        "debug": "^2.1.0",
        "musicmetadata": "1.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
