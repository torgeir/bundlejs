# bundle.js

Simplistic tool for bundling javascripts and css files

## Installation

    npm install bundlejs

## Usage

awesome.js

    var awesome;

all.js

      // bundle awesome.js
    (function () {
    })();

bundle.js

    var bundle = require('bundlejs');
    bundle('all.js')
    // (function () {
    //   var awesome;
    //  })();
