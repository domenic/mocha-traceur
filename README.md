# Mocha Traceur

A simple plugin for [Mocha](http://mochajs.org/) to pass JS files through the [Traceur](https://github.com/google/traceur-compiler) compiler. Note that dependencies of your project (i.e., files that include `node_modules` in their file path) will not be transpiled.

Traceur is intentionally not included in this package so you can install your preferred version alongside Mocha Traceur.

Use with Mocha from the command line like so:

    mocha --compilers js:mocha-traceur my_test_dir/*.js
