# go-template

[![Build Status](https://github.com/bool64/go-template/workflows/test-unit/badge.svg)](https://github.com/bool64/go-template/actions?query=branch%3Amaster+workflow%3Atest-unit)
[![Coverage Status](https://codecov.io/gh/bool64/go-template/branch/master/graph/badge.svg)](https://codecov.io/gh/bool64/go-template)
[![GoDevDoc](https://img.shields.io/badge/dev-doc-00ADD8?logo=go)](https://pkg.go.dev/github.com/bool64/go-template)
[![Time Tracker](https://wakatime.com/badge/github/bool64/go-template.svg)](https://wakatime.com/badge/github/bool64/go-template)
![Code lines](https://sloc.xyz/github/bool64/go-template/?category=code)
![Comments](https://sloc.xyz/github/bool64/go-template/?category=comments)

<!--- TODO Update README.md -->

Project template with GitHub actions for Go.

## Install

```
go install github.com/bool64/go-template@latest
$(go env GOPATH)/bin/go-template --help
```

Or download binary from [releases](https://github.com/bool64/go-template/releases).

### Linux AMD64

```
wget https://github.com/bool64/go-template/releases/latest/download/linux_amd64.tar.gz && tar xf linux_amd64.tar.gz && rm linux_amd64.tar.gz
./go-template -version
```

### Macos Intel

```
wget https://github.com/bool64/go-template/releases/latest/download/darwin_amd64.tar.gz && tar xf darwin_amd64.tar.gz && rm darwin_amd64.tar.gz
codesign -s - ./go-template
./go-template -version
```

### Macos Apple Silicon (M1, etc...)

```
wget https://github.com/bool64/go-template/releases/latest/download/darwin_arm64.tar.gz && tar xf darwin_arm64.tar.gz && rm darwin_arm64.tar.gz
codesign -s - ./go-template
./go-template -version
```


## Usage

Create a new repository from this template, check out it and run `./run_me.sh` to replace template name with name of
your repository.
