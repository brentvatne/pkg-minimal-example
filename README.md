# pkg-minimal-example

Minimal example using [zeit/pkg](https://github.com/zeit/pkg) to package
node project as an executable.

## Build it yourself

```
npm i -g pkg

# cd into this repo
pkg . --out-dir output
```

# Size of executables

Using pkg@3.0.0-beta.33

```
32M answer-linux
33M answer-macos
20M answer-win.exe
```
