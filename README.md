## ChainerIO

ChainerIO is an IO abstraction library for Chainer, optimized for deep
learning training with batteries included. It supports

- Filesystem API abstraction with unified error semantics,
- Explicit user-land caching system,
- IO performance tracing and metrics stats, and
- Fileset container utilities to save metadata.


## Dependency

- HDFS client and libhdfs for HDFS access
- Python 3

## Installation and Document build

Installation

```shell
$ git clone git:github.com:pfnet/chainerio.git
$ cd chainerio
$ pip install .
```

Documentation
```sh
$ cd chainerio/docs
$ sphinx-apidoc -o source/api ../chainerio
$ make html
$ open build/html/index.html
```

Test
```sh
$ cd chainerio
$ pip install .[test]
$ pytest
```

## How to use

Please refer to the `Documentation` for more information about the usage.
Also you can find some examples in
`examples` directory for usage in Chainer training script examples.