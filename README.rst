The bare minimum to get Typescript and React, and ES6 imports working
=====================================================================

Based on the Typescript guide .. _Here: https://www.typescriptlang.org/docs/handbook/react-&-webpack.html

The goal of this repo is to provide a simple starting point for coding in Typescript and optionally,
React, with working ES-6-style imports. Setup can be a pain; this covers the basics.

In addition to what's included in this file, you'll need to have node.js installed, and 
run 'npm install -g typescript' in a console.

To use: run 'webpack' in a console in the main directory; this will cause Typescript's built-in transpiler (TSC)
to convert all Typescript files in the src directory into ES5-compatible Javascript. Webpack will then convert React's JSX into javascript,
and combine the files in a way that allows imports to work, in the dist directory.