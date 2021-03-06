
# loadtest Changelog

## Ancient History

Versions prior to 0.2.0 were not tracked using this file. Please check:
  https://github.com/alexfernandez/loadtest/commits/master
to find individual commits.

## Version History

Release date, version number and changes.

### 2013-08-30: version 0.2.0

* Added option -C to send cookies.
* Added options -T, -p and -u to send POST and PUT requests.

### 2013-09-01: version 0.2.1

* Added bin/ files to avoid cross-platform issues.
  Parse arguments using `optimist`.
  Pull request #9 by https://github.com/zaphod1984
* Use native process.hrtime() instead of Microtime.
  Pull request #8 by to https://github.com/zaphod1984
* Changed binary testserver to testserver-loadtest, to avoid conflicts.
  Issue #4. Thanks to https://github.com/zaphod1984

### 2013-09-02: version 0.2.2

* Emergency fix for binary paths.
  Pull request #10 by to https://github.com/zaphod1984
* Fix library paths.
* Added #env lines to binary paths to run on Unix-like systems.

### 2013-09-06: version 0.2.3

* Update sample.js: fix option key for POST body.
  Pull request #11 by https://github.com/danieltdt
* Fix maxSeconds option, added test.
  Pull request #12 by https://github.com/danieltdt
* Show more complete information: concurrency, agent...
* Clean up for loadtest.run(), should not be used.

### 2013-09-??: version 0.2.4

* Remove cloneextend since it is not used.
  Pull request #13 by https://github.com/zaphod1984

