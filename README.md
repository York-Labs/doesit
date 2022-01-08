# V2Ray 而已

**垃圾VLESS 明文传输。**

## 概述

 V2Ray一键脚本

部署完成后，每次启动应用时，运行的 V2Ray 将始终为最新版本

## 部署

### 步骤

 1. 直接点击部署好吧



> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/bclswl0827/v2ray-heroku)

 4. 回到专案首页，点击上面的链接以部署 V2Ray

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |

## 接入 CloudFlare

以下两种方式均可以将应用接入 CloudFlare，从而在一定程度上提升速度。

 1. 为应用绑定域名，并将该域名接入 CloudFlare
 2. 通过 CloudFlare Workers 反向代理

## 注意

 1. **请勿滥用本专案，类似 PaaS 的免费服务少之又少，且用且珍惜**
 2. 若使用域名接入 CloudFlare，请考虑启用 TLS 1.3
 3. AWS 绝大部分 IPv4 地址已被 Twitter 屏蔽
