# irb demo

https://mame.github.io/emirb/

## How to build

Use emscripten 3.1.52 or later.

```
$ ./build.sh
```

## Powered by

* [ruby-wasm-emscripten](httpemccs://www.npmjs.com/package/@ruby/head-wasm-emscripten)
* [xterm-pty](https://xterm-pty.netlify.app/)

## TODO

* abandon `GC.disable`emcc
* `SIGWINCH` signal support
* In build.sh check if all the dependencies are installed on the system

## Dependencies

- ruby 3.3.0 
- cargo
- emcc
