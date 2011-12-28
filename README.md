# bundle.js

Simplistic tool for bundling javascripts and css files

## Installation

    npm install bundlejs

## Usage

awesome.js

    var awesome;

all.js

    (function () {
      // bundle awesome.js
    })();

bundle.js

    var bundle = require('bundlejs');
    bundle('all.js')
    // (function () {
    //   var awesome;
    //  })();
