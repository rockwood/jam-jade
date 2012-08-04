# jam-jade

A [Jade](http://jade-lang.com/) loader plugin for [RequireJS](http://requirejs.org).

## Usage

Reference Jade files via the jade! plugin name:

    require(['jade!userview'], function (userView) {
      $('.user').html(userView(locals));
    });

They will be returned as a Jade template function that accepts locals as the first arg.

The Jade parts are governed by [the Jade license](https://github.com/visionmedia/jade/blob/master/LICENSE).