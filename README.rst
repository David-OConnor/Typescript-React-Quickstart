The bare minimum to get Typescript and React, and ES6 imports working
=====================================================================

Based on the official Typescript guide `Here: <https://www.typescriptlang.org/docs/handbook/react-&-webpack.html>`_

The goal of this repo is to provide a simple starting point for coding in Typescript and optionally,
React, with working ES6-style imports. Setup can be a pain; this covers the basics.

In addition to what's included in this repo, you'll need to have node.js installed, and 
run 'npm install -g typescript' or 'yarn global add typescript' in a console to install Typescript globally. 
Install the packages for this repo (as defined in package.json) with 'npm install', or 'yarn'.

To use: run 'webpack' in a console in the main directory; this will cause Typescript's built-in transpiler (TSC)
to convert all Typescript files in the src directory into ES5-compatible Javascript, and parse JSX.
Webpack will then combine the files in a way that allows imports to work, in the dist directory. Use 'webpack --watch'
to keep webpack running; it'll automatically update your transpiled files when you make changes to your source files.