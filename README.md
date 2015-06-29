xiNET interaction viewer
========================

see demos of our interaction viewer at http://interactionviewer.org

We are working towards a general purpose web component for visualising interactions between biomolecules. 
The aim is to represent the data present in the PSI-MI standards.

Join us!

----------------
Build Process

Bower must installed globally: $ npm install -g bower

1. Clone the repository.
2. $ cd /interaction-viewer
3. $ npm install
4. $ bower install
5. $ npm start

This starts a grunt task to watch the /src folder for changes. When a file changes (is saved), grunt will browserify the folder and save the compiled version in /build.

To build the minified version in /build, run:

1. $ grunt package
