Sizzle
======

[Sizzle](http://wiki.github.com/jeresig/sizzle) packaged for [CommonJS](http://www.commonjs.org).


Usage
-----

    var SIZZLE = require("sizzle"),
        $ = SIZZLE.init(document);

    $(".test").forEach(function(el) {
        print(el.innerHTML);
    });


Credits
-------

Copyright (c) John Resig.
Copyright (c) Dojo Foundation.
