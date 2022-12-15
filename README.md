# b64dec
## A simple Python base64 decoder that supports binary output

Since the `base64` utility can have problems when redirecting binary data to a file, this Python script aims to be a reliable way to do just that.


Usage:

```
usage: b64dec [-h] [file_in] [file_out]

Decode base-64 input from a file or STDIN.

positional arguments:
  file_in     Input base-64 file, defaults to STDIN if - or unspecified.
              If filename is invalid or points to a non-existing file, it is interpreted as base-64 data.
  file_out    Output file, defaults to STDOUT if - or unspecified.

options:
  -h, --help  show this help message and exit
```