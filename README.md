# Microbundle Library Test

- Create a library that works in browser/node using latest technologies (esm etc)
- Hopefully work on CDN, new browsers, old browsers
- Figure out how to handle polyfills
  - To fix unsupported browser stuff
  - Node equilavent replacement of browser apis
- using "exports" in package.json
  - and typescript equilavent

Does this bundle dependencies?
https://github.com/developit/microbundle/wiki/How-Microbundle-decides-which-dependencies-to-bundle

Things to polyfill/substitute
- fetch
  - node is implementing, so may exist on newer versions
- crypto
  - node vs browser?
- localStorage
  - does not exit in node: see https://github.com/lmaccherone/node-localstorage


# Plan

- Start with simple library, like add(a, b)
- Add more bits as I go