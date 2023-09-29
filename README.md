# tiny
tiny npm module

# install
    $ npm install @bamblehorse/tiny

# usage
    const tiny = require("@bamblehorse/tiny");

    tiny("So much space!");
    //=> "Somuchspace!"

    tiny(1337);
    //=> Uncaught TypeError: Tiny wants a string!
    //    at tiny (<anonymous>:2:41)
    //    at <anonymous>:1:1