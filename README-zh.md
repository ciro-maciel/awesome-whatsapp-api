# Awesome WhatsApp API

> WhatsApp 集成指南：官方 Meta API、服务提供商、非官方库及各条路径的风险。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E8%AE%A2%E9%98%85-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-cartas) [![支持我们](https://img.shields.io/badge/%E6%94%AF%E6%8C%81%E6%88%91%E4%BB%AC-%E8%AF%B7%E6%88%91%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/wapi-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/wapi-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/wapi-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/zh.xml) ![26 项](https://img.shields.io/badge/%E9%A1%B9-26-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh-on.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

面向需要通过程序收发 WhatsApp 消息的人，在写代码之前先选好路径。官方 API 是企业唯一允许使用的方式；非官方库虽然能用，但号码可能被封禁。本列表将两者分开，并在每个部分中说明这一点。

## 目录

- [Meta 官方](#meta-官方)
- [官方 API 的库](#官方-api-的库)
- [官方 API 的服务商](#官方-api-的服务商)
- [非官方的库](#非官方的库)
- [开箱即用的 REST 服务器](#开箱即用的-rest-服务器)
- [客服](#客服)
- [免费工具](#免费工具)
- [标签](#标签)
- [如何贡献](#如何贡献)
- [其他列表](#其他列表)
- [由 Ciro Cesar Maciel 制作](#由-ciro-cesar-maciel-制作)
- [许可证](#许可证)

## Meta 官方

Meta 允许企业以程序方式与客户交流的唯一途径。

- [WhatsApp Business Platform](https://go.mymarketing.click/wapi-whatsapp-business-platform) - Cloud API 文档：发送、接收、消息模板和 webhooks。 `官方` `API`
- [Preços da plataforma](https://go.mymarketing.click/wapi-precos-da-plataforma) - Meta 如何按消息和对话类别收费。 `官方`
- [Política do WhatsApp Business](https://go.mymarketing.click/wapi-politica-do-whatsapp-business) - 企业在 WhatsApp 上允许和禁止的行为。 `官方`
- [Termos do WhatsApp Business](https://go.mymarketing.click/wapi-termos-do-whatsapp-business) - 商业账户的服务条款。 `官方`
- [WhatsApp Business](https://go.mymarketing.click/wapi-whatsapp-business) - WhatsApp 企业版网站，包括应用和平台。 `官方`

## 官方 API 的库

开源，用于 Meta 的 Cloud API。

- [whatsapp-api-js](https://go.mymarketing.click/wapi-whatsapp-api-js) - 轻量、无依赖的 TypeScript Cloud API 库。 `开源` `免费`
- [whatsapp-cloud-api](https://go.mymarketing.click/wapi-whatsapp-cloud-api) - 使用 PHP 通过 Cloud API 收发消息。 `开源` `免费`

## 官方 API 的服务商

Meta 的合作伙伴，转售并运营该 API。按字母顺序排列。

- [360dialog](https://go.mymarketing.click/wapi-360dialog) - 直接访问官方 API，按号码收费。 `API` `付费`
- [Blip](https://go.mymarketing.click/wapi-blip) - 巴西的 WhatsApp 客服和聊天机器人平台。 `付费`
- [Gupshup](https://go.mymarketing.click/wapi-gupshup) - 基于 WhatsApp 的消息 API 和聊天机器人。 `API` `付费`
- [Infobip](https://go.mymarketing.click/wapi-infobip) - WhatsApp 全渠道 API。 `API` `付费`
- [Twilio](https://go.mymarketing.click/wapi-twilio) - 通过 Twilio API 使用 WhatsApp，同时支持短信和语音。 `API` `付费`
- [Zenvia](https://go.mymarketing.click/wapi-zenvia) - 巴西的 WhatsApp、短信和电子邮件通信平台。 `付费`

## 非官方的库

它们模拟 WhatsApp Web 连接。Meta 不允许企业这样使用，号码可能被封禁；仅适用于个人使用、测试和自有自动化。

- [Baileys](https://go.mymarketing.click/wapi-baileys) - TypeScript API，通过 socket 使用 WhatsApp Web 协议，无需浏览器。 `开源` `免费`
- [whatsapp-web.js](https://go.mymarketing.click/wapi-whatsapp-web-js) - Node.js 客户端，通过受控浏览器连接 WhatsApp Web。 `开源` `免费`
- [whatsmeow](https://go.mymarketing.click/wapi-whatsmeow) - 用于 WhatsApp Web 多设备 API 的 Go 库。 `开源` `免费`
- [WPPConnect](https://go.mymarketing.click/wapi-wppconnect) - 由一支巴西团队开发的 Node.js 和 TypeScript WhatsApp Web 自动化工具。 `开源` `免费`
- [Venom](https://go.mymarketing.click/wapi-venom) - 用 JavaScript 编写、用于创建 WhatsApp Web 机器人的系统。 `开源` `免费`
- [wacli](https://go.mymarketing.click/wapi-wacli) - 用于同步、搜索和发送消息的命令行工具。 `开源` `免费`

## 开箱即用的 REST 服务器

在上述库的基础上提供 HTTP API。适用相同的限制。

- [Evolution API](https://go.mymarketing.click/wapi-evolution-api) - 开源且在巴西开发的 WhatsApp 集成 API。 `开源` `免费`
- [WAHA](https://go.mymarketing.click/wapi-waha) - WhatsApp HTTP API，支持多种引擎和多个会话。 `开源` `免费`
- [WPPConnect Server](https://go.mymarketing.click/wapi-wppconnect-server) - 基于 WPPConnect 的自托管 REST API。 `开源` `免费`

## 客服

供团队回复的收件箱。

- [Chatwoot](https://go.mymarketing.click/wapi-chatwoot) - 开源客服中心，支持 WhatsApp、电子邮件和网站在线聊天。 `开源` `免费`

## 免费工具

无需注册，直接在浏览器中使用。

- [Gerador de link de WhatsApp](https://go.mymarketing.click/wapi-gerador-de-link-de-whatsapp) - 带有预填消息的 wa.me 链接和可打印的 QR code。 `免费` `作者自制`
- [QR Code do WhatsApp](https://go.mymarketing.click/wapi-qr-code-do-whatsapp) - 生成 QR code，扫码即可打开你的对话并带上预先写好的消息，支持 PNG 或 SVG 格式。 `免费` `作者自制`
- [Nome, descrição e regras para grupo](https://go.mymarketing.click/wapi-nome-descricao-e-regras-para-grupo) - 群名创意、群简介和可直接粘贴到群里的群规。 `免费` `作者自制`

## 标签

每个条目都说明了它是什么。旁边的标签可帮助你选择：官方表示由制定标准的一方提供，开源表示代码已公开，免费或付费按使用模式划分，API 和 SDK 则按集成方式划分。带有“作者自制”标签的条目由 Ciro Cesar Maciel 制作，并遵循与其他条目相同的规则。

## 如何贡献

发现缺少的内容、有变动或已失效的条目？请使用新增条目表单提交 issue，或编辑 data/list.json 后提交 pull request。每种语言的 README 都是根据该文件生成的。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 其他列表

同样格式的精选列表，包括葡萄牙语版本以及另外 14 种语言的版本。

- [Awesome IA no trabalho](https://go.mymarketing.click/wapi-lista-ia-no-trabalho) - 按职业划分的工作中的 AI：助手、隐私、规范以及用于核对 AI 输出的官方来源。
- [Awesome IA na advocacia](https://go.mymarketing.click/wapi-lista-ia-advocacia) - 律师的 AI：助手、隐私、律师行业和司法系统中有关 AI 的规范，以及用于核对的官方来源。
- [Awesome IA na contabilidade](https://go.mymarketing.click/wapi-lista-ia-contabilidade) - 会计师的 AI：助手、隐私、CFC 规范，以及用于核对的税务局、eSocial 和 Simples 来源。
- [Awesome IA na sala de aula](https://go.mymarketing.click/wapi-lista-ia-sala-de-aula) - 教师的 AI：各类助手的最低使用年龄和隐私政策，以及用于核对的教育规范。
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/wapi-lista-ia-atendimento-e-vendas) - 服务与销售人员的 AI：助手、隐私、消费者权益，以及柜台、收银和电话岗位的工作规定。
- [Awesome IA no escritório](https://go.mymarketing.click/wapi-lista-ia-escritorio) - 秘书、助理和行政人员的 AI：助手、隐私、公文写作规范，以及通过电子邮件传来的诈骗。
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/wapi-lista-ia-pequeno-negocio) - MEI 和小企业主的 AI：助手、隐私，以及适用于小微企业的 MEI、Simples、消费者权益和 LGPD 规定。
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/wapi-lista-ia-primeiro-trabalho) - 刚开始工作的人的 AI：助手、隐私、求职渠道、初次就业的权利，以及虚假招聘诈骗。
- [Awesome Pix](https://go.mymarketing.click/wapi-lista-pix) - 面向集成人员的 Pix：规范、API、SDK、服务提供商和工具，逐一核实。
- [Awesome MCP Brasil](https://go.mymarketing.click/wapi-lista-mcp-brasil) - 面向巴西服务的 MCP 服务器：公共数据、CNPJ、税务、法律、金融市场、商务和支付。
- [Awesome livros de IA](https://go.mymarketing.click/wapi-lista-livros-ia) - 关于人工智能的葡萄牙语图书：从初次使用到职业发展，从构建者到大众讨论。
- [Awesome ferramentas online](https://go.mymarketing.click/wapi-lista-ferramentas-online) - 无需安装、直接在浏览器中打开的免费工具：图片、PDF、文本、代码、网站、电子邮件、视频和销售。
- [Awesome NF-e](https://go.mymarketing.click/wapi-lista-nfe) - 面向集成商的电子发票：官方门户、各语言的库、开票 API 和 MCP 服务器。
- [Awesome APIs Brasil](https://go.mymarketing.click/wapi-lista-apis-brasil) - 巴西公共 API：CEP、CNPJ、中央银行、IBGE、立法、司法、节假日和开放数据。
- [Awesome Claude Code BR](https://go.mymarketing.click/wapi-lista-claude-code-br) - 葡萄牙语 Claude Code：文档、课程、skills、规则、插件和巴西制作的 MCP 服务器。
- [Awesome pagamentos Brasil](https://go.mymarketing.click/wapi-lista-pagamentos-brasil) - 面向集成商的巴西支付：规范、网关、收单机构、boleto、订阅、split 和反欺诈。
- [Awesome Open Finance Brasil](https://go.mymarketing.click/wapi-lista-open-finance-brasil) - 巴西的 Open Finance 和 Open Insurance：规范、标准说明、开放数据、聚合器和开源代码。
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/wapi-lista-empresa-de-uma-pessoa) - 用 AI 智能体经营整个企业所需的工具：上线、收款、衡量、推广，并被找到。

## 由 Ciro Cesar Maciel 制作

使用我所开发的内容，也是支持这些列表的一种方式。

如果这个列表帮你节省了时间，请喝杯咖啡来支持维护。捐赠者可自行选择金额，支持 Pix 或银行卡付款。 [![支持我们](https://img.shields.io/badge/%E6%94%AF%E6%8C%81%E6%88%91%E4%BB%AC-%E8%AF%B7%E6%88%91%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-agents)

## 许可证

本列表采用 CC0 1.0 许可：你可以随意复制、改编和再分发，无需征得许可。生成器代码位于 awesome-kit 中，采用 MIT 许可。

<sub>更新于 2026-11-10.</sub>
