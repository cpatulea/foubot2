To compile for foubot's hardware, set the following:

	export GOARCH=arm; export GOARM=5;

_using go 1.10_

Running on an NSLU2 slug with the I2C exposed to an LED sign to receive messages.

Some people are horrible.

To build:
```
$ mkdir foubot; cd foubot
$ export GOPATH=$PWD
$ go get github.com/tools/godep
$ go get github.com/FOULAB/foubot2

# To compile for foubot's hardware, set the following:
$ GOARCH=arm GOARM=5 go build github.com/FOULAB/foubot2
```

**Click.**
**Boom.**
**Amazebuilds.**
