<p align="center"><img src="https://avatars.githubusercontent.com/u/91626055?v=4" width="128" /></p>

<div align="center">

# AikoR
AikoR Projects

[![](https://img.shields.io/badge/Telegram-group-green?style=flat-square)](https://t.me/AikoXrayR)
[![](https://img.shields.io/badge/Telegram-channel-blue?style=flat-square)](https://t.me/AikoCute_Support)
[![](https://img.shields.io/github/downloads/Github-Aiko/AikoR/total.svg?style=flat-square)](https://github.com/Github-Aiko/AikoR/releases)
[![](https://img.shields.io/github/v/release/Github-Aiko/AikoR?style=flat-square)](https://github.com/Github-Aiko/AikoR/releases)
[![docker](https://img.shields.io/docker/v/aikocute/aikor?label=Docker%20image&sort=semver)](https://hub.docker.com/r/aikocute/aikor)
[![Go-Report](https://goreportcard.com/badge/github.com/Github-Aiko/AikoR?style=flat-square)](https://goreportcard.com/report/github.com/Github-Aiko/AikoR)
</div>


# Description of AikoR
AikoR Supports Various Panels (V2board, ProxyPanel, sspanel, Pmpanel...)

An Xray-based back-end framework, supporting V2ay, Trojan, Shadowsocks protocols, extremely easily extensible and supporting multi-panel connectionã€‚

If you like this project, you can click the star + view in the upper right corner to track the progress of this project.

## Disclaimer

This project is for my personal learning, development and maintenance only, I do not guarantee the availability and I am not responsible for any consequences resulting from using this software.

## Featured
* Open source `This version depends on the happy mood`
* Supports multiple protocols V2ray, Trojan, Shadowsocks.
* Supports new features like Vless and XTLS.
* Supports single connection to multiple boards and nodes without rebooting.
* Online IP support is limited
* Support node port level, user level rate limit.
* Simple and clear configuration.
* Modify the configuration to automatically restart the instance.
* Easy to compile and upgrade, can quickly update core version, support new Xray-core features.
* Support UDP and many other functions

## Featured

| Featured                                       | v2ray | trojan | shadowsocks |
| -------------------------------------------    | ----- | ------ | ----------- |
| Get button info                                | âˆš     | âˆš      | âˆš           |
| Get user information                           | âˆš     | âˆš      | âˆš           |
| User traffic statistics                        | âˆš     | âˆš      | âˆš           |
| Report server information                      | âˆš     | âˆš      | âˆš           |
| Automatic registration of TLS certificates     | âˆš     | âˆš      | âˆš           |
| auto-renew tls certificate                     | âˆš     | âˆš      | âˆš           |
| Number of people online                        | âˆš     | âˆš      | âˆš           |
| Online User Restrictions                       | âˆš     | âˆš      | âˆš           |
| Audit rules                                    | âˆš     | âˆš      | âˆš           |
| Node port speed limit                          | âˆš     | âˆš      | âˆš           |
| User speed limit                               | âˆš     | âˆš      | âˆš           |
| Custom DNS                                     | âˆš     | âˆš      | âˆš           |
## User interface support

| Panel                                                  | v2ray | trojan | shadowsocks                                 |
| ------------------------------------------------------ | ----- | ------ | ------------------------------------------- |
| [sspanel-uim](https://github.com/Anankke/SSPanel-Uim)  | âˆš     | âˆš      | âˆš (Single-port multi-user and V2ray-Plugin) |
| [v2board](https://github.com/v2board/v2board)          | âˆš     | âˆš      | âˆš                                           |
| [PMPanel](https://github.com/ByteInternetHK/PMPanel)   | âˆš     | âˆš      | âˆš                                           |
| [ProxyPanel](https://github.com/ProxyPanel/ProxyPanel) | âˆš     | âˆš      | âˆš                                           |

## Software installation - release
```
wget --no-check-certificate -O AikoR.sh https://raw.githubusercontent.com/Github-Aiko/AikoR-Install/master/AikoR.sh && bash AikoR.sh
```
### One main installation - docker
```
docker pull aikocute/aikor:latest && docker run --restart=always --name aikor -d -v ${PATCH_TO_CONFIG}/aiko.json:/etc/AikoR/aiko.json --network=host aikocute/aikor:latest
```
### Configuration file and detailed instructions
Comming Soon
## Telgram

Comming Soon

## Stargazers over time

[![Stargazers over time](https://starchart.cc/Github-Aiko/AikoR.svg)](https://starchart.cc/Github-Aiko/AikoR)
