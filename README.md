[![Build Status](https://travis-ci.org/writeas/go-epub.svg?branch=master)](https://travis-ci.org/writeas/go-epub)
[![Coverage Status](https://coveralls.io/repos/github/writeas/go-epub/badge.svg?branch=master)](https://coveralls.io/github/writeas/go-epub?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/writeas/go-epub)](https://goreportcard.com/report/github.com/writeas/go-epub)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/writeas/go-epub/blob/master/LICENSE)
[![GoDoc](https://godoc.org/github.com/writeas/go-epub?status.svg)](https://godoc.org/github.com/writeas/go-epub)
---

### Features
- [Documented API](https://godoc.org/github.com/writeas/go-epub)
- Creates valid EPUB 3.0 files
- Adds an additional EPUB 2.0 table of contents ([as seen here](https://github.com/bmaupin/epub-samples)) for maximum compatibility
- Includes support for adding CSS, images, and fonts

For an example of actual usage, see https://github.com/bmaupin/go-docs-epub

### Installation

    go get github.com/writeas/go-epub

### Development

    go get github.com/writeas/go-epub
    cd $GOPATH/src/github.com/writeas/go-epub

Dependencies are managed using [Go modules](https://github.com/golang/go/wiki/Modules)

### Testing

1. (Optional) Install EpubCheck

       wget https://github.com/IDPF/epubcheck/releases/download/v4.0.2/epubcheck-4.0.2.zip
       unzip epubcheck-4.0.2.zip

2. Run tests

       go test
