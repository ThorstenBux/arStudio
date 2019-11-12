

cd into editor/liteserver/src
php -S localhost:8081

## Start editor with:

http-server -S -C [path/to/]cert.pem -K [path/to/]key-noenc.pem
http-server -S -C ~/Desktop/zaphod\ cert/zaphod-cert.pem -K ~/Desktop/zaphod\ cert/zaphod-key-noenc.pem

```
-S or --ssl Enable https
-C or --cert Path to ssl cert file (default: cert.pem)
-K or --key Path to ssl key file (default: key.pem)
```


## User
U: Test12345
P: test12345