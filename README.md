# jke-neutrino-preset-react-mobx
[![NPM version](https://img.shields.io/npm/v/jke-neutrino-preset-react-mobx.svg)](https://www.npmjs.com/package/jke-neutrino-preset-react-mobx) [![Build status](https://img.shields.io/travis/joakimkemeny/jke-neutrino-preset-react-mobx/master.svg)](https://travis-ci.org/joakimkemeny/jke-neutrino-preset-react-mobx)

This project provides a [Neutrino](https://neutrino.js.org) preset for building [React](https://facebook.github.io/react) applications with [MobX](https://mobx.js.org) using decorators. It uses the official React preset and extends it with support for decorators (including support for class properties).

## Usage

Create a project with a `package.json` like this.

```javascript
{
   "name": "myapp",
   "version": "1.0.0",
   "config": {
      "presets": [
         "jke-neutrino-preset-react-mobx"
      ]
   },
   "scripts": {
      "build": "neutrino build",
      "start": "neutrino start"
   },
   "dependencies": {
      "mobx": "^3.1.2",
      "mobx-react": "^4.1.1",
      "react": "^15.4.2",
      "react-dom": "^15.4.2",
      "react-hot-loader": "next"
   },
   "devDependencies": {
      "neutrino": "^4.3.1",
      "neutrino-preset-react-mobx": "0.1.0"
   }
}
```

Now you are ready to put your React components into `src/` and start coding. Be aware that Neutrino creates the HTML template for you automatically. For more information see the web sites for [Neutrino](https://neutrino.js.org), [React](https://facebook.github.io/react) and [MobX](https://mobx.js.org).

## License
Copyright 2017 Joakim Kemeny

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Dependencies
This project relies on the work of great people who have created the following dependencies.

### Dependencies
[![dependency status](https://img.shields.io/david/joakimkemeny/jke-neutrino-preset-react-mobx/master.svg)](https://david-dm.org/joakimkemeny/jke-neutrino-preset-react-mobx/master#info=dependencies)

- [babel-plugin-transform-class-properties](https://www.npmjs.com/package/babel-plugin-transform-class-properties): Used to allow class properties to be decorated
- [babel-plugin-transform-decorators-legacy](https://www.npmjs.com/package/babel-plugin-transform-decorators-legacy): Used to transform decorators into valid JavaScript
- [neutrino-preset-react](https://www.npmjs.com/package/neutrino-preset-react): The base preset that provides support for React in Neutrino

### Peer dependencies
[![peerDependency status](https://img.shields.io/david/peer/joakimkemeny/jke-neutrino-preset-react-mobx/master.svg)](https://david-dm.org/joakimkemeny/jke-neutrino-preset-react-mobx/master#info=peerDependencies)

- [neutrino](https://www.npmjs.com/package/neutrino): Used to run this project
