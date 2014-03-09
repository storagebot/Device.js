Device.js
=========

Detect and Query mobile device spec.

# Document

- https://github.com/uupaa/Spec.js/wiki/Spec
- https://github.com/uupaa/UserAgent.js/wiki/UserAgent
- https://github.com/uupaa/Device.js/wiki/Device
- https://github.com/uupaa/Browser.js/wiki/Browser
- https://github.com/uupaa/OS.js/wiki/OS

# How to use

```js
<script src="lib/Spec.js">
<script src="lib/Device.js">
<script>
// for Browser
console.log( Device(Spec()) );
</script>
```

```js
// for WebWorkers
importScripts("lib/Spec.js");
importScripts("lib/Device.js");
console.log( Device(Spec()) );
```

```js
// for Node.js
var Spec = require("lib/Spec.js");
var Device = require("lib/Device.js");
console.log( Device(Spec()) );
```

# for Developers

1. Install development dependency tools

    ```sh
    $ brew install closure-compiler
    $ brew install node
    $ npm install -g plato
    ```

2. Clone Repository and Install

    ```sh
    $ git clone git@github.com:uupaa/Xxx.js.git
    $ cd Xxx.js
    $ npm install
    ```

3. Build and Minify

    `$ npm run build`

4. Test

    `$ npm run test`

5. Lint

    `$ npm run lint`

