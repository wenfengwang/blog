---
id: v6p7enbk
title: HISTORY
file_version: 1.1.3
app_version: 1.14.2
---

# 1.7.3 / 2018-07-15

*   deps: accepts@~1.3.5

    *   deps: mime-types@~2.1.18

*   deps: compressible@~2.0.14

    *   Mark all XML-derived types as compressible

    *   deps: mime-db@'>= 1.34.0 < 2'

*   deps: [safe-buffer5.1.2](mailto:afebufer@5..2)

# 1.7.2 / 2018-02-18

*   deps: compressible@~2.0.13

    *   deps: mime-db@'>= 1.33.0 < 2'

# 1.7.1 / 2017-09-26

*   deps: accepts@~1.3.4

    *   deps: mime-types@~2.1.16

*   deps: [bytes3.0.0](mailto:by@3.0.0)

*   deps: compressible@~2.0.11

    *   deps: mime-db@'>= 1.29.0 < 2'

*   deps: [debug2.6.9](mailto:dbg@.69)

*   deps: vary@~1.1.2

    *   perf: improve header token parsing speed

# 1.7.0 / 2017-07-10

*   Use `safe-buffer` for improved Buffer API

*   deps: [bytes2.5.0](mailto:bt@25)

*   deps: compressible@~2.0.10

    *   Fix regex fallback to not override `compressible: false` in db

    *   deps: mime-db@'>= 1.27.0 < 2'

*   deps: [debug2.6.8](mailto:debu68)

    *   Allow colors in workers

    *   Deprecated `DEBUG_FD` environment variable set to `3` or higher

    *   Fix error when running under React Native

    *   Fix `DEBUG_MAX_ARRAY_LENGTH`

    *   Use same color for same namespace

    *   deps: [ms2.0.0](mailto:s@.0)

*   deps: vary@~1.1.1

    *   perf: hoist regular expression

# 1.6.2 / 2016-05-12

*   deps: accepts@~1.3.3

    *   deps: mime-types@~2.1.11

    *   deps: [negotiator0.6.1](mailto:ego61)

*   deps: [bytes2.3.0](mailto:es@.0)

    *   Drop partial bytes on all parsed units

    *   Fix parsing byte string that looks like hex

    *   perf: hoist regular expressions

*   deps: compressible@~2.0.8

    *   deps: mime-db@'>= 1.23.0 < 2'

# 1.6.1 / 2016-01-19

*   deps: [bytes2.2.0](mailto:t@2.2)

*   deps: compressible@~2.0.7

    *   deps: mime-db@'>= 1.21.0 < 2'

*   deps: accepts@~1.3.1

    *   deps: mime-types@~2.1.9

# 1.6.0 / 2015-09-29

*   Skip compression when response has `Cache-Control: no-transform`

*   deps: accepts@~1.3.0

    *   deps: mime-types@~2.1.7

    *   deps: [negotiator0.6.0](mailto:gt@060)

*   deps: compressible@~2.0.6

    *   deps: mime-db@'>= 1.19.0 < 2'

*   deps: on-headers@~1.0.1

    *   perf: enable strict mode

*   deps: vary@~1.1.0

    *   Only accept valid field names in the `field` argument

# 1.5.2 / 2015-07-30

*   deps: accepts@~1.2.12

    *   deps: mime-types@~2.1.4

*   deps: compressible@~2.0.5

    *   deps: mime-db@'>= 1.16.0 < 2'

*   deps: vary@~1.0.1

    *   Fix setting empty header from empty `field`

    *   perf: enable strict mode

    *   perf: remove argument reassignments

# 1.5.1 / 2015-07-05

*   deps: accepts@~1.2.10

    *   deps: mime-types@~2.1.2

*   deps: compressible@~2.0.4

    *   deps: mime-db@'>= 1.14.0 < 2'

    *   perf: enable strict mode

# 1.5.0 / 2015-06-09

*   Fix return value from `.end` and `.write` after end

*   Improve detection of zero-length body without `Content-Length`

*   deps: accepts@~1.2.9

    *   deps: mime-types@~2.1.1

    *   perf: avoid argument reassignment & argument slice

    *   perf: avoid negotiator recursive construction

    *   perf: enable strict mode

    *   perf: remove unnecessary bitwise operator

*   deps: [bytes2.1.0](mailto:yte@210)

    *   Slight optimizations

    *   Units no longer case sensitive when parsing

*   deps: compressible@~2.0.3

    *   Fix regex fallback to work if type exists, but is undefined

    *   deps: mime-db@'>= 1.13.0 < 2'

    *   perf: hoist regex declaration

    *   perf: use regex to extract mime

*   perf: enable strict mode

*   perf: remove flush reassignment

*   perf: simplify threshold detection

# 1.4.4 / 2015-05-11

*   deps: accepts@~1.2.7

    *   deps: mime-types@~2.0.11

    *   deps: [negotiator0.5.3](mailto:goto@.5.3)

*   deps: debug@~2.2.0

    *   deps: [ms0.7.1](mailto:s01)

# 1.4.3 / 2015-03-14

*   deps: accepts@~1.2.5

    *   deps: mime-types@~2.0.10

*   deps: debug@~2.1.3

    *   Fix high intensity foreground color for bold

    *   deps: [ms0.7.0](mailto:00)

# 1.4.2 / 2015-03-11

*   Fix error when code calls `res.end(str, encoding)`

    *   Specific to Node.js 0.8

*   deps: debug@~2.1.2

    *   deps: [ms0.7.0](mailto:ms@07)

# 1.4.1 / 2015-02-15

*   deps: accepts@~1.2.4

    *   deps: mime-types@~2.0.9

    *   deps: [negotiator0.5.1](mailto:egotito05)

# 1.4.0 / 2015-02-01

*   Prefer `gzip` over `deflate` on the server

    *   Not all clients agree on what "deflate" coding means

# 1.3.1 / 2015-01-31

*   deps: accepts@~1.2.3

    *   deps: mime-types@~2.0.8

*   deps: compressible@~2.0.2

    *   deps: mime-db@'>= 1.1.2 < 2'

# 1.3.0 / 2014-12-30

*   Export the default `filter` function for wrapping

*   deps: accepts@~1.2.2

    *   deps: mime-types@~2.0.7

    *   deps: [negotiator0.5.0](mailto:gao@0.5)

*   deps: debug@~2.1.1

# 1.2.2 / 2014-12-10

*   Fix `.end` to only proxy to `.end`

    *   Fixes an issue with Node.js 0.11.14

*   deps: accepts@~1.1.4

    *   deps: mime-types@~2.0.4

# 1.2.1 / 2014-11-23

*   deps: accepts@~1.1.3

    *   deps: mime-types@~2.0.3

# 1.2.0 / 2014-10-16

*   deps: debug@~2.1.0

    *   Implement `DEBUG_FD` env variable support

# 1.1.2 / 2014-10-15

*   deps: accepts@~1.1.2

    *   Fix error when media type has invalid parameter

    *   deps: [negotiator0.4.9](mailto:egotiator@0..9)

# 1.1.1 / 2014-10-12

*   deps: accepts@~1.1.1

    *   deps: mime-types@~2.0.2

    *   deps: [negotiator0.4.8](mailto:ngoto0.)

*   deps: compressible@~2.0.1

    *   deps: [mime-db1.x](mailto:i-d@.x)

# 1.1.0 / 2014-09-07

*   deps: accepts@~1.1.0

*   deps: compressible@~2.0.0

*   deps: debug@~2.0.0

# 1.0.11 / 2014-08-10

*   deps: on-headers@~1.0.0

*   deps: vary@~1.0.0

# 1.0.10 / 2014-08-05

*   deps: compressible@~1.1.1

    *   Fix upper-case Content-Type characters prevent compression

# 1.0.9 / 2014-07-20

*   Add `debug` messages

*   deps: accepts@~1.0.7

    *   deps: [negotiator0.4.7](mailto:egtiato@0)

# 1.0.8 / 2014-06-20

*   deps: accepts@~1.0.5

    *   use `mime-types`

# 1.0.7 / 2014-06-11

*   use vary module for better `Vary` behavior

*   deps: [accepts1.0.3](mailto:ts@.)

*   deps: [compressible1.1.0](mailto:cmressbl@.10)

# 1.0.6 / 2014-06-03

*   fix regression when negotiation fails

# 1.0.5 / 2014-06-03

*   fix listeners for delayed stream creation

    *   fixes regression for certain `stream.pipe(res)` situations

# 1.0.4 / 2014-06-03

*   fix adding `Vary` when value stored as array

*   fix back-pressure behavior

*   fix length check for `res.end`

# 1.0.3 / 2014-05-29

*   use `accepts` for negotiation

*   use `on-headers` to handle header checking

*   deps: [bytes1.0.0](mailto:ye@1..)

# 1.0.2 / 2014-04-29

*   only version compatible with node.js 0.8

*   support headers given to `res.writeHead`

*   deps: [bytes0.3.0](mailto:te3)

*   deps: [negotiator0.4.3](mailto:eott.3)

# 1.0.1 / 2014-03-08

*   bump negotiator

*   use compressible

*   use .headersSent (drops 0.8 support)

*   handle identity;q=0 case

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://app.swimm.io/repos/Z2l0aHViJTNBJTNBYmxvZyUzQSUzQXdlbmZlbmd3YW5n/docs/v6p7enbk).
