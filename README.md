# RFS - Rust File System

Cloned from [simple-http-server](https://github.com/TheWaWaR/simple-http-server) for my use & rust learning.

Thanks to [TheWaWaR](https://github.com/TheWaWaR). If you need use software like this, please use [simple-http-server](https://github.com/TheWaWaR/simple-http-server).

### Screenshot
<img src="./screenshot.png" width="80%" height="80%">

### Command Line Arguments
```
Rust File System 0.0.1

USAGE:
    rfs [FLAGS] [OPTIONS] [--] [root]

FLAGS:
        --cors       Enable CORS via the "Access-Control-Allow-Origin" header
    -h, --help       Prints help information
    -i, --index      Enable automatic render index page [index.html, index.htm]
        --nocache    Disable http cache
        --norange    Disable header::Range support (partial request)
        --nosort     Disable directory entries sort (by: name, modified, size)
    -s, --silent     Disable all outputs
    -u, --upload     Enable upload files (multiple select) (CSRF token required)
    -V, --version    Prints version information

OPTIONS:
    -a, --auth <auth>                              HTTP Basic Auth (username:password)
        --cert <cert>                              TLS/SSL certificate (pkcs#12 format)
        --certpass <certpass>                      TLS/SSL certificate password
    -c, --compress <compress>...
            Enable file compression: gzip/deflate
                Example: -c=js,d.ts
                Note: disabled on partial request!
        --ip <ip>                                  IP address to bind [default: 0.0.0.0]
    -p, --port <port>                              Port number [default: 8000]
        --redirect <redirect>                      takes a URL to redirect to using HTTP 301 Moved Permanently
    -t, --threads <threads>                        How many worker threads [default: 3]
        --try-file <PATH>
            serve this file (server root relative) in place of missing files (useful for single page apps) [aliases:
            try-file-404]
    -l, --upload-size-limit <upload_size_limit>    Upload file size limit [bytes] [default: 8000000]
```
