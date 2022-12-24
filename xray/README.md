###### Tips
* [caddy](https://github.com/caddyserver/caddy/releases)|[xray](https://github.com/XTLS/Xray-core/releases)|[acme.sh](https://github.com/acmesh-official/acme.sh)

`vless(xtls) + vmess + trojan + ss+v2ray-plugin + naiveproxy + web` Port **443 & 80**  

* Reference：[xray](https://github.com/XTLS/Xray-examples)  &&  [lxhao61](https://github.com/lxhao61/integrated-examples) &&  [azoway](https://github.com/azoway/across)
* Install:
```bash
bash <(curl -s https://raw.githubusercontent.com/laintuv/across/main/xray/xray_whatever_uuid.sh) my.domain.com
```
OR
```bash
bash <(curl -s https://raw.githubusercontent.com/laintuv/across/main/xray/xray_whatever_uuid.sh) uuid my.domain.com
```
* Uninstall:
```bash
bash <(curl -s https://raw.githubusercontent.com/laintuv/across/main/xray/xray_whatever_uuid.sh) remove_purge
```

* Notes

UUID for all config

Port 80 for Non-TLS: Vless WS, Vmess WS, Vmess HTTP, Shadowsocks

Port 443 for TLS: Trojan, Trojan WS, Vless WS, Vless H2, Vmess WS, Vmess H2, Vmess HTTP, Shadowsocks, Naive

CDN support for WS only

UDP Supported
