# micro-base Change Log

All notable changes to this project will be documented in this file.

micro-base is in a pre-1.0 state. This means that its APIs and behavior are subject to breaking changes without deprecation notices. Until 1.0, version numbers will follow a [Semver][]-ish `0.y.z` format, where `y` is incremented when new features or breaking changes are introduced, and `z` is incremented for lesser changes or bug fixes.

## [0.2.4][] (2016-05-25)

* Simplified jobs definition
* Added "data" section to error responses
* Allow the server to start under the 'lab' testing tool
* Added option to use REST style endpoints.
* Added two example services
* Restored the "ping" operation

## [0.2.3][] (2016-05-20)

* Improve documentation

## [0.2.2][] (2016-05-19)

* Initial Workers service based on [cron](https://github.com/ncb000gt/node-cron) and [monq](https://github.com/scttnlsn/monq)

## [0.2.1][] (2016-05-19)

* Services service
  * Added a `loadModule` method, to define several operations at once
* Logger service
  * Added `isDebugEnabled` helper method

## [0.2.0][] (2016-05-14)

* Services service
  * Changed seneca in favor of [hapi](https://github.com/hapijs/hapi) to define and call services
* Initial DB service based on [mongoose](https://github.com/Automattic/mongoose)

## [0.1.2][] (2016-05-11)

* Application bootstrap
* Initial Config service based on [nconf](https://github.com/indexzero/nconf)
* Initial Logger service based on [winston](https://github.com/winstonjs/winston)
* Initial Services service based on [seneca](https://github.com/senecajs/seneca)
* Added JSON Schema validation with [tv4](https://github.com/geraintluff/tv4)