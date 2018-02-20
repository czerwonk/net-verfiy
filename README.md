# net-verfiy
[![Build Status](https://travis-ci.org/czerwonk/net-verify.svg)](https://travis-ci.org/czerwonk/net-verify)
[![Go Report Card](https://goreportcard.com/badge/github.com/czerwonk/net-verify)](https://goreportcard.com/report/github.com/czerwonk/net-verify)

Simple network verification tool

## Description
net-verify compares an actual network setup to definition (JSON file). It exits with exit code 0 if all expectations are met. 

## Install
```
go get -u github.com/czerwonk/net-verify
```

## Usage
Given a definition file called my-definition.json:

```
net-verify -file my-definition.json
```

## License
(c) Daniel Czerwonk, 2017. Licensed under [MIT](LICENSE) license.