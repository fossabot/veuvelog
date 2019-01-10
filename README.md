# Venvelog - Logging for Golang
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Flamjack%2Fveuvelog.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Flamjack%2Fveuvelog?ref=badge_shield)


## Installation

Install the latest version with

```bash
$ go get -u github.com/lamjack/veuvelog
```

## Basic Usage

```go
import (
	"github.com/lamjack/veuvelog"
	"github.com/lamjack/veuvelog/handler"
)

lvl := log.DEBUG
h := handler.NewConsoleHandler(logLevel)
ConsoleLogger = log.NewLogger("logger name")
ConsoleLogger.PushHandler(h)
```

## About

### Author

Jack Lam - <jack@wizmacau.com> - <http://lamjack.github.io/>

### License

Venvelog is licensed under the MIT License - see the `LICENSE` file for details

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Flamjack%2Fveuvelog.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Flamjack%2Fveuvelog?ref=badge_large)