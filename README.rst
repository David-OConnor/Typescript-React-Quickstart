The bare minimum to get Typescript and React, and ES6 imports working
=====================================================================

Based on the official Typescript guide `Here: <https://www.typescriptlang.org/docs/handbook/react-&-webpack.html>`_

The goal of this repo is to provide a simple starting point for coding in Typescript and optionally,
React, with working ES6-style imports. Setup can be a pain; this covers the basics.

In addition to what's included in this repo, you'll need to have node.js installed, and 
run 'npm install -g typescript' in a console to install Typescript globally.

To use: run 'webpack' in a console in the main directory; this will cause Typescript's built-in transpiler (TSC)
to convert all Typescript files in the src directory into ES5-compatible Javascript. Webpack will then convert React's JSX into javascript,
and combine the files in a way that allows imports to work, in the dist directory.