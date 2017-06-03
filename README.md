# cow
Rule based proxy utility client

## Fetures
* use [go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2) as shadowsocks library.
* rule based, support `DOMAIN` `IP` `IP-CIDR` `DOMAIN-SUFFIX` `DOMAIN-KEYWORD`
* Support HTTP front and socks5 front
* BlackList mode

## Example
comma-separated rules without any whitespace

`DOMAIN,cdn.v2ex.co`

`IP,8.8.8.8`

`IP-CIDR,91.108.56.0/22`

`DOMAIN-SUFFI,googlevideo.com`

`DOMAIN-KEYWORD,twitter`

## Acknowledgements
* Dependencies
  - [go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2)
  - [goproxy](https://github.com/elazarl/goproxy)
  - [proxy](https://github.com/golang/proxy)
  - [syncmap](https://github.com/golang/sync/blob/master/syncmap/map.go)
* Code reference
  - [http2socks](https://github.com/mischief/http2socks)
  - [cow](https://github.com/cyfdecyf/cow)
