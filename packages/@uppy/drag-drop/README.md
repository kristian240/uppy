# @uppy/drag-drop

<img src="https://uppy.io/images/logos/uppy-dog-head-arrow.svg" width="120" alt="Uppy logo: a superman puppy in a pink suit" align="right">

<a href="https://www.npmjs.com/package/@uppy/drag-drop"><img src="https://img.shields.io/npm/v/@uppy/drag-drop.svg?style=flat-square"></a>
<img src="https://github.com/transloadit/uppy/workflows/Tests/badge.svg" alt="CI status for Uppy tests"> <img src="https://github.com/transloadit/uppy/workflows/Companion/badge.svg" alt="CI status for Companion tests"> <img src="https://github.com/transloadit/uppy/workflows/End-to-end%20tests/badge.svg" alt="CI status for browser tests">

Droppable zone UI for Uppy. Drag and drop files into it to upload.

**[Read the docs](https://uppy.io/docs/dragdrop)** | **[Try it](https://uppy.io/examples/dragdrop/)**

Uppy is being developed by the folks at [Transloadit](https://transloadit.com), a versatile file encoding service.

## Example

```js
import Uppy from '@uppy/core'
import DragDrop from '@uppy/drag-drop'

const uppy = new Uppy()
uppy.use(DragDrop, {
  target: '#upload',
})
```

## Installation

```bash
$ npm install @uppy/drag-drop
```

We recommend installing from npm and then using a module bundler such as [Webpack](https://webpack.js.org/), [Browserify](http://browserify.org/) or [Rollup.js](http://rollupjs.org/).

Alternatively, you can also use this plugin in a pre-built bundle from Transloadit's CDN: Edgly. In that case `Uppy` will attach itself to the global `window.Uppy` object. See the [main Uppy documentation](https://uppy.io/docs/#Installation) for instructions.

## Documentation

Documentation for this plugin can be found on the [Uppy website](https://uppy.io/docs/dragdrop).

## License

[The MIT License](./LICENSE).
