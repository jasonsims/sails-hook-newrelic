# sails-hook-newrelic

[![Build Status](http://img.shields.io/travis/Kikobeats/sails-hook-newrelic/master.svg?style=flat)](https://travis-ci.org/Kikobeats/sails-hook-newrelic)
[![Dependency status](http://img.shields.io/david/Kikobeats/sails-hook-newrelic.svg?style=flat)](https://david-dm.org/Kikobeats/sails-hook-newrelic)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/sails-hook-newrelic.svg?style=flat)](https://david-dm.org/Kikobeats/sails-hook-newrelic#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/sails-hook-newrelic.svg?style=flat)](https://www.npmjs.org/package/sails-hook-newrelic)
[![Gittip](http://img.shields.io/gittip/Kikobeats.svg?style=flat)](https://www.gittip.com/Kikobeats/)

> Integrates newrelic with your Sails application

## Install

```bash
npm install sails-hook-newrelic
```

## Usage

Just setup your settings in `config/newrelic` following the rules of [newrelic](https://github.com/newrelic/node-newrelic) package like:

```js
module.exports.newrelic = {
  app_name: ['your-app-name'],
  license_key: 'your-license-key',
  logging: {
    level: 'warn', // can be error, warn, info, debug or trace
    rules: {
      ignore: ['^/socket.io/*/xhr-polling']
    }
  }
};
```


## License

MIT © [Kiko Beats](http://www.kikobeats.com)


