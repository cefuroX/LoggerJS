# Browser Library specifics
[return to LoggerJS README](https://github.com/luscus/LoggerJS/blob/master/README.md)


## Usage

### Set Dependency

Add following entry to your `bower.json` in the `dependencies` property

    "dependencies": {
      "LoggerJS" : "https://github.com/luscus/LoggerJS.git"
    },


### Bind Library

    <script type="application/javascript" src="..bower_components/LoggerJS/lib/browser/loggerjs.js"></script>

Or the minified version

    <script type="application/javascript" src="..bower_components/LoggerJS/lib/browser/loggerjs.min.js"></script>

### Instanciate

Create a Logger instance

    var options = {
      namespace :    'my.awsome.project',
      uniqueLogKeys: <boolean>,
      status :       <boolean>,
      logLevel :     LoggerJS.<LEVEL>,
      logServerUrl : '<logging_service_url>',
      tags :         ['myproject', 'gui', 'something']
    },
    logger = new LoggerJS.Logger(options);

please refer to the [LoggerJS README](https://github.com/luscus/LoggerJS/blob/master/README.md#instanciation-options) for a full list of options.

## API

please refer to the [LoggerJS README](https://github.com/luscus/LoggerJS/blob/master/README.md#api) for an up to date API description.
