nodeimu
=========

Nodejs bindings for accessing IMU/pressure/humidity/temperature data using [RTIMULib2](https://github.com/richards-tech/RTIMULib2.git). The addon uses [nodejs/nan](https://github.com/nodejs/nan.git). It has been tested on [Sense HAT](https://www.raspberrypi.org/products/sense-hat/) and on [GrovePi+](http://www.dexterindustries.com/grovepi/) for Raspberry Pi.

## Note

This is a fork of rupnikj/nodeimu that updates dependencies for at least Node v12. The most recent version of the https://github.com/RTIMULib/RTIMULib2 repository is included in this repo for convenience (as of 2/18/2020). 

## Install

```
git clone https://github.com/trbll/nodeimu --recursive && cd nodeimu
npm install node-gyp -g
npm install
```

## Test

```
node test.js
node testSync.js
```

[npm-image]: https://img.shields.io/npm/v/nodeimu.svg
[npm-url]: https://npmjs.org/package/nodeimu
[travis-linux-image]: https://img.shields.io/travis/rupnikj/nodeimu/master.svg?label=linux
[travis-linux-url]: https://travis-ci.org/rupnikj/nodeimu
