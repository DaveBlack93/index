# Index of available BuckleScript bindings and Libraries (and also some tooling)

- [Bindings](#bindings)
  - [Frontend (browser)](#frontend-browser)
  - [Backend (node)](#backend-node)
  - [Other platforms](#other-platforms)
  - [General purpose](#general-purpose)
  - [Testing](#testing)
- [Libraries](#libraries)
  - [Frontend (browser)](#frontend-browser-1)
  - [Backend (node)](#backend-node-1)
  - [Other platforms](#other-platforms-1)
  - [General purpose](#general-purpose-1)
  - [Testing](#testing-1)
- [Tooling](#tooling)
- [Related links](#related-links)
- [Contribute](#contribute)

## Bindings

### Frontend (browser)
Name | Description | Status
--- | --- | ---
[bs-webapi-incubator](https://github.com/reasonml-community/bs-webapi-incubator) | (Incomplete) [Web APIs](https://developer.mozilla.org/en-US/docs/Web/Specification_list) | Incomplete (but then that's kind of the point)
[bs-director](https://github.com/reasonml-community/bs-director) | [Director](https://github.com/flatiron/director) - Routing | Basic, Usable
[bs-leaflet](https://github.com/reasonml-community/bs-leaflet) | [Leaflet.js](http://leafletjs.com/) - Interactive maps | "WIP"
[bs-fetch](https://github.com/reasonml-community/bs-fetch) | [Fetch API](https://developer.mozilla.org/en/docs/Web/API/Fetch_API) | Feature complete, probably buggy
[reason-react](https://github.com/reasonml/reason-react) | [React](https://facebook.github.io/react/) with some flavor | Mostly complete, but not stable
[ReWebRTC](https://github.com/bsansouci/ReWebRTC) | [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) | "Super simple"
[reasongl](https://github.com/bsansouci/reasongl) | [OpenGL 2.0](https://www.khronos.org/registry/OpenGL/specs/gl/glspec20.pdf) and [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) | Unknown, probably usable
[bucklescript-jquery](https://github.com/nebuta/bucklescript-jquery) | [jQuery](https://jquery.com/) - Swiss army knife | Unknown, Out of date build process
[bs-dom](https://github.com/0zat/bs-dom) | [DOM API](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) | Very incomplete, "not test yet"
[bucklescript-phx](https://github.com/phoenix-china/bucklescript-phx) | [Phoenix](http://www.phoenixframework.org/) client API | "work in progress"
[bs-rebass](https://github.com/MasterOfPoppets/bs-rebass) | [Rebass](https://rebass-beta.now.sh/) - Stateless Component Library | Usable, Not complete
[bs-glamor](https://github.com/poeschko/bs-glamor) | [glamor](https://github.com/threepointone/glamor) - inline css for react | Incomplete, but fully functional
[bs-snabbdom](https://github.com/jordwest/bs-snabbdom) | [Snabbdom](https://github.com/snabbdom/snabbdom) - Virtual DOM | "highly experimental and incomplete"
[bs-blueprintjs](https://github.com/shanewilson/bs-blueprintjs) | [Blueprint.js](https://github.com/palantir/blueprint) - React-based UI toolkit for the web | Unknown, seems comprehensive
[reason-vue](https://github.com/aweary/reason-vue) | [Vue.js](https://vuejs.org/) - "progressive" UI framework | Unknown, basic?
[reason-react-toolbox](https://github.com/astrada/reason-react-toolbox) | [react-toolbox](https://github.com/react-toolbox/react-toolbox) - React component library implementing Material Design | Automatically generated
[bs-react-pdf](https://github.com/meafmira/bs-react-pdf) | [react-pdf](https://github.com/diegomura/react-pdf) | Usable, Incomplete original library
[bs-d3](https://github.com/af/bs-d3) | [D3](https://github.com/d3/d3) - Data visualization library using SVG, Canvas and HTML | "Extremely incomplete and experimental"
[bs-storybook](https://github.com/splish-me/bs-storybook) | [Storybook for React](https://github.com/storybooks/storybook) - Development environment for UI components | "Highly experimental and WIP"

### Backend (node)
Name | Description | Status
--- | --- | ---
[bs-node](https://github.com/reasonml-community/bs-node) | [Node API](https://nodejs.org/docs/latest/api/) | Barely started
[bs-express](https://github.com/reasonml-community/bs-express) | [Express](https://expressjs.com/) - Web application framework | Usable, Not complete, Unit Tested
[bs-discord.js](https://github.com/reasonml-community/bs-discord.js) | [Discord.js](https://discord.js.org) - JS Discord API | Functional but incomplete
[bs-socket.io](https://github.com/reasonml-community/bs-socket.io) | [socket.io](https://github.com/socketio/socket.io) - Event-based communication | Mostly complete, "dead simple"
[bs-spotify-web-api](https://github.com/ryb73/bs-spotify-web-api) | [spotify-web-api-node](https://github.com/thelinmichael/spotify-web-api-node) - [Spotify Web API](https://developer.spotify.com/web-api/) | Unknown
[bs-glob](https://github.com/reasonml-community/bs-glob) | [node-glob](https://github.com/isaacs/node-glob) - File matching with glob patterns | Basic, Usable
[bs-next](https://github.com/ulrikstrid/bs-next) | [Next.js](https://github.com/zeit/next.js) - Server-rendered React application framework | Complete?
[bs-chalk](https://github.com/AndrewKvalheim/bs-chalk) | [Chalk](https://github.com/chalk/chalk) - Terminal string styling done right | Archived, undocumented, basic?
[bs-puppeteer](https://github.com/zploskey/bs-puppeteer) | [Puppeteer](https://github.com/GoogleChrome/puppeteer) - API for Headless Chrome | "work in progress, and most features probably don't work yet"

### Other platforms
Name | Description | Status
--- | --- | ---
[bs-react-native](https://github.com/reasonml-community/bs-react-native) | [React Native](https://facebook.github.io/react-native/) Native mobile application framework | Nearly usable
[bucklescript-electron](https://github.com/freebroccolo/bucklescript-electron) | [Electron](https://electron.atom.io/) | Cross-platform desktop application framework | Unknown
[bs-vscode](https://github.com/glennsl/bs-vscode) | [Visual Studio Code extension API](https://code.visualstudio.com/docs/extensionAPI/vscode-api) | Incomplete
[bs-atom](https://github.com/glennsl/bs-atom) | [Atom package API](https://atom.io/docs/api) | Barely started

### General purpose
Name | Description | Status
--- | --- | ---
[bs-moment](https://github.com/reasonml-community/bs-moment) | [Moment.js](https://momentjs.com/) - Date processing | Unknown
[bs-immutablejs](https://github.com/reasonml-community/bs-immutablejs) | [Immutable.js](https://facebook.github.io/immutable-js/) - Immutable collections | Unknown, probably usable
[bs-axios](https://github.com/meafmira/bs-axios) | [Axios](https://github.com/mzabriskie/axios) - Promise based HTTP client for the browser and node.js | Basic, Usable
[bs-json](https://github.com/reasonml-community/bs-json) | Low-level JSON encoding and decoding | Usable, Very experimental
[bs-transit-js](https://github.com/reasonml-community/bs-transit-js) | [transit.js](https://github.com/cognitect/transit-js) - Marshaling | "rudimentary"
[bs-history](https://github.com/reasonml-community/bs-history) | [history](https://github.com/reacttraining/history) - Cross-platform abstraction over the HTML history API | "WIP"
[bs-numeral](https://github.com/drwlrsn/bs-numeral) | [Numeral.js](https://numeraljs.com/) - Formatting and manipulation of numbers | "Work in progress"
[bs-most](https://github.com/Lokeh/bs-most) | [Most.js](https://github.com/cujojs/most) - Reactive programming toolkit | At least basic
[bs-geofire](https://github.com/AndrewKvalheim/bs-geofire) | [GeoFire](https://github.com/firebase/geofire-js/) - Realtime location queries with Firebase | Complete, Maintained

### Testing
Name | Description | Status
--- | --- | ---
[bs-jest](https://github.com/reasonml-community/bs-jest) | [Jest](https://github.com/facebook/jest) | Incomplete, but fully functional
[bs-react-test-renderer](https://github.com/reasonml-community/bs-react-test-renderer) | [react-test-renderer](https://github.com/facebook/react/tree/master/packages/react-test-renderer) | Mostly complete?
[bs-benchmarkjs](https://github.com/glennsl/bs-benchmarkjs) | [Benchmark.js](https://benchmarkjs.com/) | Very very basic
[bs-enzyme](https://github.com/rpowelll/bs-enzyme) | [Enzyme](https://github.com/airbnb/enzyme) - Testing utilities for React | "Very experimental"


## Libraries

### Frontend (browser)
Name | Description | Status
--- | --- | ---
[bucklescript-tea](https://github.com/OvermindDL1/bucklescript-tea) | Implementation of [The Elm Architecture](https://guide.elm-lang.org/architecture/) (ie. TEA, ya get it?) | Usable but incomplete. Alpha maybe?
[reprocessing](https://github.com/Schmavery/reprocessing) | High-level drawing library inspired by [Processing](https://github.com/Schmavery/reprocessing) | "100% a work in progress"
[tween.re](https://github.com/xuu/tween.re) | Reimplementation of [tween.js](https://github.com/tweenjs/tween.js) in Reason | Demoable, Basic?

### Backend (node)

### Other platforms
Name | Description | Status
--- | --- | ---
[reason-react-native-navigation](https://github.com/szymonzmyslony/reason-react-native-navigation) | "Simple React Native navigation" | Basic? Seems well documented

### General purpose
Name | Description | Status
--- | --- | ---
[bs-batteries](https://github.com/meafmira/bs-batteries) | [Batteries](http://batteries.forge.ocamlcore.org/) - community-driven effort to standardize on an consistent, documented, and comprehensive development platform for the OCaml | Very Basic (only `Option`, `BatList`, `BatArray` available), WIP
[immutable-re](https://github.com/facebookincubator/immutable-re) | Pure Reason implementation of persistent immutable data structures | Early alpha
[reductive](https://github.com/reasonml/reductive) | [Redux](http://redux.js.org/) reimplementation | Proof of concept?
[transducers.re](https://github.com/IwanKaramazow/transducers.re) | Clojure transducers in Reason | Unknown
[bs-ocaml-protoc-json](https://github.com/mransan/bs-ocaml-protoc-json) | Runtime library for the [ocaml-protoc](https://github.com/mransan/ocaml-protoc) [Protocol Buffers](https://developers.google.com/protocol-buffers) code generator | Very usable, unit + conformance tests
[bs-re:vamp](https://github.com/glennsl/bs-revamp) | Safe and functional API for JavaScript regexes | Full-featured, but experimental
[vow](https://github.com/wokalski/vow) | Almost sound Promises for Bucklescript | Full-featured, Documented
[rebug](https://github.com/glennsl/rebug) | Port of [debug](https://github.com/visionmedia/debug), a library for debug logging | Browser-only, missing a few advanced features
[rebase](https://github.com/glennsl/rebase) | Minimal, cross-platform, BuckleScript-first replacement base library | BS only, incomplete, largely undocumented, untested and prone to change

### Testing
Name | Description | Status
--- | --- | ---
[infinite-jest](https://github.com/glennsl/infinite-jest) | Cross-platform native/bs test framework | Usable, Alpha

## Tooling
Name | Description | Status
--- | --- | ---
[bucklescript-brunch](https://github.com/OvermindDL1/bucklescript-brunch) | [Brunch](http://brunch.io/) plugin to compile Bucklescript code | Unknown
[ocaml-language-server](https://github.com/freebroccolo/ocaml-language-server) | [Language Server Protocol](https://github.com/Microsoft/language-server-protocol) implementation for OCaml | Feature complete
[vscode-reasonml](https://github.com/freebroccolo/vscode-reasonml) | Reason support for Visual Studio Code | Feature complete
[reason-tools](https://github.com/freebroccolo/reason-tools) | Refmt in the browser | Continuously improving
[babel-plugin-transform-bucklescript](https://github.com/freebroccolo/babel-plugin-transform-bucklescript) | Babel postprocessing transformations for BuckleScript generated JavaScript | Unknown
[bs-loader](https://github.com/reasonml-community/bs-loader) | Bucklescript loader for Webpack | Usable
[jeason](https://github.com/chenglou/jeason) | Converts JavaScript it into really bad Reason code | "crappy"
[reason](https://github.com/facebook/reason) | Ocaml skin | Alpha? Very usable, but still also very much in flux
[qnd](https://github.com/kennetpostigo/qnd) | Quick and Dirty development builds for reason | Usable
[grunt-bucklescript](https://github.com/askucher/grunt-bucklescript) | Grunt plugin | Unknown
[ReasonablyTyped](https://github.com/rrdelaney/ReasonablyTyped) | Converts Flow and TypeScript library definitions to Bucklescript interfaces | Basic
[ts2re](https://github.com/joshaber/ts2re) | Convert TypeScript type declaration files to Reason externals | "super not ready for real use"
[reason-scripts](https://github.com/reasonml-community/reason-scripts) | Create React App-like development environment setup script | Feature-rich and well-supported
[bucklescript-tea-starter-kit](https://github.com/tcoopman/bucklescript-tea-starter-kit) | Starter kit for BuckleScript with [TEA (The Elm Architecture)](https://github.com/OvermindDL1/bucklescript-tea) | Fully working
[rollup-plugin-bucklescript](https://github.com/shrynx/rollup-plugin-bucklescript) | rollup plugin for bucklescript complier | Functional but not well tested
## Related Links
- [awesome-reasonml](https://github.com/vramana/awesome-reasonml)
- [BuckleScript API](https://bucklescript.github.io/bucklescript/api/index.html)
- [ReasonML Community wiki/FAQ](https://github.com/reasonml-community/wiki)

## Contribute
Have you written a binding or library that's not listed here? Or come across one? Or found a mistake, however unlikely that might be? Then just submit a PR! It'll be very appreciated and probably even accepted!
