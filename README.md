# fast-decimal 

[![PkgGoDev](https://pkg.go.dev/badge/github.com/xenking/fast-decimal)](https://pkg.go.dev/github.com/xenking/fast-decimal)
[![Go Report Card](https://goreportcard.com/badge/github.com/xenking/fast-decimal)](https://goreportcard.com/report/github.com/xenking/fast-decimal)
[![Build Status](https://travis-ci.com/xenking/fast-decimal.svg?branch=master)](https://travis-ci.com/xenking/fast-decimal)
[![codecov](https://codecov.io/gh/xenking/fast-decimal/branch/master/graph/badge.svg)](https://codecov.io/gh/xenking/fast-decimal)

`fast-decimal` implements arbitrary precision, decimal floating-point numbers, per 
the [General Decimal Arithmetic](http://speleotrove.com/decimal/) specification.

## Features

 * Useful zero values.
   The zero value of a `decimal.Big` is 0, just like `math/big`.

 * Multiple operating modes.
   Different operating modes allow you to tailor the package's behavior to your
   needs. The GDA mode strictly implements the GDA specification, while the Go
   mode implements familiar Go idioms.

 * High performance.
   `decimal` is consistently one of the fastest arbitrary-precision decimal 
   floating-point libraries, regardless of language.

 * An extensive math library.
   The `math/` subpackage implements elementary and trigonometric functions,
   continued fractions, and more.

 * A familiar, idiomatic API.
   `decimal`'s API follows `math/big`'s API, so there isn't a steep learning 
   curve.

## Installation

`go install github.com/xenking/fast-decimal/v3@latest`

## Documentation

[GoDoc](http://godoc.org/github.com/xenking/fast-decimal)

## Versioning

`decimal` uses Semantic Versioning. The current version is 3.4.1.

`decimal` only explicitly supports the two most recent major Go 1.X versions.

## License

[BSD 3-clause](https://github.com/xenking/fast-decimal/blob/master/LICENSE)
