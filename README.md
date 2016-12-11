# rnc
Reconnecting netcat.

## Installation
```bash
npm -g install rnc
```

## Usage
```bash
rnc 127.0.0.1 7777
```

Options:

* `RNC_NC` - which nc binary to use, defaults to `"nc"`
* `RNC_TIMEOUT` - what timeout to use between reconnects, defaults to `1`
* `RNC_MAX_TRIES` - maximum number of retries, defaults to infinity
