Xslt Library for Enonic XP
==========================

[![Build Status](https://travis-ci.org/enonic/lib-xslt.svg?branch=master)](https://travis-ci.org/enonic/lib-xslt)
[![codecov](https://codecov.io/gh/enonic/lib-xslt/branch/master/graph/badge.svg)](https://codecov.io/gh/enonic/lib-xslt)
[![License](https://img.shields.io/github/license/enonic/lib-xslt.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

This library implements an xslt rendering method that can be used in your apps. See documentation
here: https://enonic-docs.s3.amazonaws.com/com.enonic.lib/lib-xslt/index.html

## Releases and compatibility

| App Version   | XP version |
| ------------- | ---------- |
| 1.0.0 | 6.11.0 |

## Building

To build this project, execute the following:

```
./gradlew clean build
```

## Publishing

To release this project, execute the following:

```
./gradlew clean build uploadArchives
```

## Documentation

Building the documentation is done executing the following:

```
./gradlew buildDoc
```

And publishing the docs to S3:

```
./gradlew publishDoc
```

