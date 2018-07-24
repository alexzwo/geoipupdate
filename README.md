[![Build Status](https://travis-ci.com/maxmind/geoipupdate2.svg?branch=master)](https://travis-ci.com/maxmind/geoipupdate2)

# GeoIP Update

The GeoIP Update program performs automatic updates of GeoIP2 and GeoIP Legacy
binary databases. CSV databases are _not_ supported.

This is the new version of GeoIP Update. If for some reason you need the
legacy C version, you can find it
[here](https://github.com/maxmind/geoipupdate).

## Installation from source or Git

You need the Go compiler (1.8+). You can get it at the [Go
website](https://golang.org).

The easiest way is via `go get`:

    $ go get github.com/maxmind/geoipupdate2/cmd/geoipupdate

The program will be installed to `$GOPATH/bin/geoipupdate`.

# Configuring

Please see our [online guide](https://dev.maxmind.com/geoip/geoipupdate/) for
directions on how to configure GeoIP Update.

# Bug Reports

Please report bugs by filing an issue with our GitHub issue tracker at
https://github.com/maxmind/geoipupdate2/issues

# Copyright and License

This software is Copyright (c) 2018 by MaxMind, Inc.

This is free software, licensed under both the Apache License, Version 2.0
and the MIT license.

Please see [LICENSE-APACHE](LICENSE-APACHE) and [LICENSE-MIT](LICENSE-MIT).
