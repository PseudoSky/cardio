Cardio
======

Cardio is a web application health tool. It provides a snapshot (via a bunch of
metrics) of how "healthy" your application is by measuring HTML/CSS/JS
complexity.

Installation
------------

    npm install -g cardio

If you get installation errors for node-canvas, don't despair. It's an optional
dependency used by [Assetgraph](https://github.com/One-com/assetgraph) to do
some other cool stuff that isn't used in Cardio.

Usage
-----

    $ cardio »url-or-webroot-or-html-file« > output.json
    $ cardio-report2array output.json # Reformats for metrics-friendly digestion

License
-------

[MIT](LICENSE)
