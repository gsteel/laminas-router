# laminas-router

[![Build Status](https://travis-ci.org/laminas/laminas-router.svg?branch=master)](https://travis-ci.org/laminas/laminas-router)
[![Coverage Status](https://coveralls.io/repos/laminas/laminas-router/badge.svg?branch=master)](https://coveralls.io/r/laminas/laminas-router?branch=master)

laminas-router provides flexible HTTP and console routing.

HTTP-based routing currently works against the
[laminas-http](https://github.com/laminas/laminas-http) request and responses,
and provides capabilities around:

- Literal path matches
- Path segment matches (at path boundaries, and optionally validated using regex)
- Regular expression path matches
- HTTP request scheme
- HTTP request method
- Hostname

Additionally, it supports combinations of different route types in tree
structures, allowing for fast, b-tree lookups.

Console routing leverages [laminas-console's routing capabilities](http://docs.laminas.dev/laminas-console/routes/),
providing a unified mechanism for working with routes regardless of the
enviornment.

- File issues at https://github.com/laminas/laminas-router/issues
- Documentation is at https://docs.laminas.dev/laminas-router/
