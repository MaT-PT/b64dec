# b64dec
## A simple Python base64 decoder that supports binary output

Since the `base64` utility can have problems when redirecting binary data to a file, this Python script aims to be a reliable way to do just that.


Usage:

```
b64dec FILE_IN [FILE_OUT]
```

Using "-" as a filename will either take input from STDIN or write output to STDOUT accordingly.

If OUT_FILE is missing, defaults to STDOUT.