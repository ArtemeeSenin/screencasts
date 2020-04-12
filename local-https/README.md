# Use local ssl certificates

Create certificate using [mkcert](https://github.com/FiloSottile/mkcert) or [cfssl](https://github.com/cloudflare/cfssl)

```
mkcert -install
mkcert disired.domain "*.desired.domain"
```

Check that everyting works by creating simple node server with nginx as reverse-proxy
