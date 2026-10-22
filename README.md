VLESS-Reality-TCP（端口 443）：使用 xtls-rprx-vision 流控，搭配 TCP 传输。

VLESS-Reality-gRPC（端口 444）：使用 gRPC 传输，配置了服务名 hugogrpc。

XTLS-Reality-Extra（端口 8881）：额外的 VLESS-Reality 备份节点，同样使用 xtls-rprx-vision。

VMess（端口 3443）：经典标准的 VMess 传输协议，具有出色的客户端兼容性。

Hysteria 2（端口 8443）：基于 HTTP/3 (h3) 的高性能拥塞控制协议。

TUIC v5（端口 9443）：基于 QUIC 协议、支持 BBR 拥塞控制的高性能代理。

Shadowsocks 2022（端口 6443）：使用 2022-blake3-aes-128-gcm 加密算法。

Trojan（端口 7443）：传统的 TLS 代理协议。

SOCKS5 / HTTP Mixed（端口 5443）：通用的混合代理端口，支持用户名和密码认证。
9协议
```
curl -sSL https://raw.githubusercontent.com/zhugo1982/sub-9/refs/heads/main/sub -o /usr/local/bin/sub && chmod +x /usr/local/bin/sub; sub
```
或者
```
bash <(curl -Ls https://raw.githubusercontent.com/zhugo1982/hugo-sub-8/main/sub.sh)
```
