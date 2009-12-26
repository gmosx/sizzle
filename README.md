Sizzle
======

[Sizzle](http://wiki.github.com/jeresig/sizzle) packaged for [CommonJS](http://www.commonjs.org).


Usage
-----

    var html = '<html>...</html>',
        document = require("htmlparser").parse(html),
        $ = require("sizzle").sizzle(document);

    $(".test").forEach(function(el) {
        print(el.innerHTML);
    });


Credits
-------

Copyright (c) John Resig.
Copyright (c) Dojo Foundation.
