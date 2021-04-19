# VLESS / Trojan-Go / Shadowsocks
automated script for xray-core and trojan-go

## Usage
```sh
curl -fsSL https://raw.staticdn.net/potpot1/v2-pot/main/src/xPOT.sh -o ~/xPOT.sh && bash ~/xPOT.sh
```
To run the script again once downloaded, just use the following command:
```
bash ~/xPOT.sh
```



## Supported Protocols
| Protocol | Transport | Mux | Direct | CDN | Qv2ray | Shadowrocket | Clash | v2rayN(G) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| VLESS | XTLS | ❌ | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ |
| VLESS | TLS | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ |
| VLESS | WSS | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| Trojan | TLS | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ |
| Trojan | WSS | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ |
| Shadowsocks | WSS | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |


## Credit
+ [@MASTER_LILONE]
+ [@phlinhng](https://github.com/phlinhng)
+ [Project V](https://www.v2fly.org/)
+ [V2Ray 配置指南](https://toutyrater.github.io/)
+ [新 V2Ray 白话文指南](https://guide.v2fly.org/)
+ [templated.co](https://templated.co)
+ [@liberal-boy/tls-shunt-proxy](https://github.com/liberal-boy/tls-shunt-proxy)
+ [@atrandys/trojan](https://github.com/atrandys/trojan)
+ [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)
+ [@mack-a/v2ray-agent](https://github.com/mack-a/v2ray-agent)
+ [@chiakge/Linux-NetSpeed](https://github.com/chiakge/Linux-NetSpeed)
+ [@ylx2016/Linux-NetSpeed](https://github.com/ylx2016/Linux-NetSpeed)
+ [@LemonBench/LemonBench](https://github.com/LemonBench/LemonBench)
+ [@tindy2013/subconverter](https://github.com/tindy2013/subconverter)
+ [@p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go)
+ [@rprx/v2ray-vless](https://github.com/rprx/v2ray-vless)
+ [@acmesh-official/acme.sh](https://github.com/acmesh-official/acme.sh)
+ [@nginx/nginx](https://github.com/nginx/nginx)
+ [@charlieethan/firewall-proxy](https://github.com/charlieethan/firewall-proxy)
+ [@XTLS/xray-core](https://github.com/XTLS/xray-core)



## Stargazers over time
[![Stargazers over time](https://starchart.cc/phlinhng/v2ray-tcp-tls-web.svg)](https://starchart.cc/phlinhng/v2ray-tcp-tls-web)
