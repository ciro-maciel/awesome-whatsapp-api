# Awesome WhatsApp API

> WhatsApp 연동 개발자를 위한 목록: Meta의 공식 API, 서비스 제공업체, 비공식 라이브러리와 각 방식의 위험성.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%EA%B5%AC%EB%8F%85-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-cartas) [![후원하기](https://img.shields.io/badge/%ED%9B%84%EC%9B%90%ED%95%98%EA%B8%B0-%EC%BB%A4%ED%94%BC%20%ED%95%9C%20%EC%9E%94-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/wapi-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/wapi-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/wapi-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/ko.xml) ![26 항목](https://img.shields.io/badge/%ED%95%AD%EB%AA%A9-26-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko-on.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

프로그램으로 WhatsApp 메시지를 보내고 받고 싶은데 코드를 쓰기 전에 방식을 먼저 골라야 하는 분들을 위한 목록입니다. 기업은 공식 API만 사용할 수 있습니다. 비공식 라이브러리도 동작하지만 번호가 차단될 수 있습니다. 이 목록은 두 방식을 나누어 각 섹션에서 그 점을 설명합니다.

## 콘텐츠

- [Meta 공식](#meta-공식)
- [공식 API용 라이브러리](#공식-api용-라이브러리)
- [공식 API 제공업체](#공식-api-제공업체)
- [비공식 라이브러리](#비공식-라이브러리)
- [바로 쓰는 REST 서버](#바로-쓰는-rest-서버)
- [상담](#상담)
- [무료 도구](#무료-도구)
- [태그](#태그)
- [기여 방법](#기여-방법)
- [다른 목록](#다른-목록)
- [Ciro Cesar Maciel 제작](#ciro-cesar-maciel-제작)
- [라이선스](#라이선스)

## Meta 공식

Meta가 허용하는 기업과 고객 간 프로그램 대화의 유일한 방법.

- [WhatsApp Business Platform](https://go.mymarketing.click/wapi-whatsapp-business-platform) - Cloud API 문서: 메시지 전송과 수신, 메시지 템플릿, webhook. `공식` `API`
- [Preços da plataforma](https://go.mymarketing.click/wapi-precos-da-plataforma) - Meta가 메시지와 대화 카테고리별로 요금을 청구하는 방식. `공식`
- [Política do WhatsApp Business](https://go.mymarketing.click/wapi-politica-do-whatsapp-business) - WhatsApp에서 기업이 허용되는 것과 금지되는 것. `공식`
- [Termos do WhatsApp Business](https://go.mymarketing.click/wapi-termos-do-whatsapp-business) - 비즈니스 계정의 서비스 약관. `공식`
- [WhatsApp Business](https://go.mymarketing.click/wapi-whatsapp-business) - 기업용 WhatsApp 공식 사이트, 앱과 플랫폼 포함. `공식`

## 공식 API용 라이브러리

Cloud API용 Meta 공개 라이브러리.

- [whatsapp-api-js](https://go.mymarketing.click/wapi-whatsapp-api-js) - 의존성이 없는 가벼운 Cloud API용 TypeScript 라이브러리. `오픈 소스` `무료`
- [whatsapp-cloud-api](https://go.mymarketing.click/wapi-whatsapp-cloud-api) - PHP로 Cloud API를 통해 메시지를 보내고 받기. `오픈 소스` `무료`

## 공식 API 제공업체

Meta의 파트너로, API를 재판매하고 운영합니다. 가나다순.

- [360dialog](https://go.mymarketing.click/wapi-360dialog) - 번호별 과금으로 공식 API에 직접 접속. `API` `유료`
- [Blip](https://go.mymarketing.click/wapi-blip) - WhatsApp 상담과 챗봇을 위한 브라질 플랫폼. `유료`
- [Gupshup](https://go.mymarketing.click/wapi-gupshup) - WhatsApp 및 챗봇용 메시지 API. `API` `유료`
- [Infobip](https://go.mymarketing.click/wapi-infobip) - WhatsApp을 포함한 옴니채널 API. `API` `유료`
- [Twilio](https://go.mymarketing.click/wapi-twilio) - Twilio API로 WhatsApp 사용, SMS 및 음성 포함. `API` `유료`
- [Zenvia](https://go.mymarketing.click/wapi-zenvia) - WhatsApp, SMS, 이메일을 아우르는 브라질 커뮤니케이션 플랫폼. `유료`

## 비공식 라이브러리

WhatsApp Web처럼 연결합니다. Meta는 기업의 이런 사용을 허용하지 않으며 번호가 차단될 수 있습니다. 개인 사용, 테스트, 자체 자동화용입니다.

- [Baileys](https://go.mymarketing.click/wapi-baileys) - 브라우저 없이 소켓으로 WhatsApp Web 프로토콜을 사용하는 TypeScript API. `오픈 소스` `무료`
- [whatsapp-web.js](https://go.mymarketing.click/wapi-whatsapp-web-js) - 제어되는 브라우저에서 WhatsApp Web으로 연결하는 Node.js 클라이언트. `오픈 소스` `무료`
- [whatsmeow](https://go.mymarketing.click/wapi-whatsmeow) - WhatsApp Web 멀티 디바이스 API용 Go 라이브러리. `오픈 소스` `무료`
- [WPPConnect](https://go.mymarketing.click/wapi-wppconnect) - 브라질 팀이 만든 Node.js 및 TypeScript용 WhatsApp Web 자동화. `오픈 소스` `무료`
- [Venom](https://go.mymarketing.click/wapi-venom) - WhatsApp Web 봇을 만드는 JavaScript 시스템. `오픈 소스` `무료`
- [wacli](https://go.mymarketing.click/wapi-wacli-2) - WhatsApp Web 기기처럼 연결되는 Go 명령줄 도구입니다. 대화 기록을 로컬 SQLite에 저장하고 검색할 수 있으며, 메시지, 미디어, 그룹을 보낼 수 있습니다. 터미널, 스크립트, AI 에이전트에서 사용할 수 있습니다. `오픈 소스` `무료`

## 바로 쓰는 REST 서버

위의 라이브러리를 감싸는 HTTP API를 제공합니다. 같은 제약이 적용됩니다.

- [Evolution API](https://go.mymarketing.click/wapi-evolution-api) - 브라질에서 만든 오픈 소스 WhatsApp 연동 API. `오픈 소스` `무료`
- [WAHA](https://go.mymarketing.click/wapi-waha) - 여러 엔진과 여러 세션을 지원하는 WhatsApp HTTP API. `오픈 소스` `무료`
- [WPPConnect Server](https://go.mymarketing.click/wapi-wppconnect-server) - WPPConnect 기반의 자체 호스팅 REST API. `오픈 소스` `무료`

## 상담

팀이 응답할 수 있는 공유 受信함.

- [Chatwoot](https://go.mymarketing.click/wapi-chatwoot) - WhatsApp, 이메일, 웹사이트 채팅을 지원하는 오픈소스 고객 지원 센터. `오픈 소스` `무료`

## 무료 도구

회원가입 없이 브라우저에서 사용.

- [Gerador de link de WhatsApp](https://go.mymarketing.click/wapi-gerador-de-link-de-whatsapp) - 메시지가 미리 입력된 wa.me 링크와 인쇄용 QR code. `무료` `작성자 제작`
- [QR Code do WhatsApp](https://go.mymarketing.click/wapi-qr-code-do-whatsapp) - 메시지가 미리 준비된 대화를 여는 QR code, PNG 또는 SVG 형식. `무료` `작성자 제작`
- [Nome, descrição e regras para grupo](https://go.mymarketing.click/wapi-nome-descricao-e-regras-para-grupo) - 이름 아이디어, 설명, 그리고 그룹에 바로 붙여넣을 수 있는 규칙. `무료` `작성자 제작`

## 태그

각 항목에는 무엇인지 설명이 있습니다. 옆의 태그가 고르는 데 도움을 줍니다. 표준을 정하는 곳에서 나온 것은 공식, 코드가 공개된 것은 오픈 소스, 사용 방식에 따라 무료 또는 유료, 연동 방식에 따라 API와 SDK로 표시합니다. "작성자 제작" 태그가 달린 항목은 Ciro Cesar Maciel이 만들었으며 다른 모든 항목과 같은 기준을 따릅니다.

## 기여 방법

빠진 것, 바뀐 것, 사라진 것을 알고 계신가요? 새 항목 양식으로 이슈를 열거나 data/list.json을 수정하는 풀 리퀘스트를 보내 주세요. 각 언어의 README는 이 파일에서 생성됩니다.

[CONTRIBUTING.md](CONTRIBUTING.md)

## 다른 목록

같은 형식으로 큐레이션한 목록들이며, 포르투갈어와 14개 다른 언어로 제공됩니다.

- [Awesome IA no trabalho](https://go.mymarketing.click/wapi-lista-ia-no-trabalho) - 직업별 업무 AI: 어시스턴트, 개인정보, 규정, 그리고 AI가 쓴 내용을 확인할 공식 자료.
- [Awesome IA na advocacia](https://go.mymarketing.click/wapi-lista-ia-advocacia) - 변호사를 위한 AI: 어시스턴트, 개인정보, 법률 및 사법부의 AI 규정, 그리고 확인할 공식 자료.
- [Awesome IA na contabilidade](https://go.mymarketing.click/wapi-lista-ia-contabilidade) - 회계사를 위한 AI: 어시스턴트, 개인정보, CFC 규정, 그리고 확인할 Receita, eSocial, Simples 자료.
- [Awesome IA na sala de aula](https://go.mymarketing.click/wapi-lista-ia-sala-de-aula) - 교사를 위한 AI: 각 도구의 어시스턴트, 최소 연령, 개인정보, 그리고 확인할 교육 규정.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/wapi-lista-ia-atendimento-e-vendas) - 응대와 판매를 하는 분들을 위한 AI: 어시스턴트, 개인정보, 소비자 권리, 그리고 창구, 계산대, 전화 업무의 근무 규칙.
- [Awesome IA no escritório](https://go.mymarketing.click/wapi-lista-ia-escritorio) - 비서, 어시스턴트, 사무보조를 위한 AI: 어시스턴트, 개인정보, 공문서 작성, 이메일로 오는 사기.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/wapi-lista-ia-pequeno-negocio) - MEI와 소규모 사업자를 위한 AI: 어시스턴트, 개인정보, MEI와 Simples 규정, 소비자 및 LGPD 규정.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/wapi-lista-ia-primeiro-trabalho) - 일을 막 시작한 분들을 위한 AI: 어시스턴트, 개인정보, 구직처, 첫 직장의 권리, 가짜 채용 사기.
- [Awesome Pix](https://go.mymarketing.click/wapi-lista-pix) - Pix 연동 개발자를 위한 목록: 규정, API, SDK, 서비스 제공업체, 도구를 하나씩 확인했습니다.
- [Awesome MCP Brasil](https://go.mymarketing.click/wapi-lista-mcp-brasil) - 브라질 서비스를 위한 MCP 서버: 공공 데이터, CNPJ, 세무, 법률, 금융 시장, 상거래, 결제.
- [Awesome livros de IA](https://go.mymarketing.click/wapi-lista-livros-ia) - 포르투갈어로 된 인공지능 관련 도서: 처음 사용하는 법부터 직업, 만드는 사람과 논쟁까지.
- [Awesome ferramentas online](https://go.mymarketing.click/wapi-lista-ferramentas-online) - 설치 없이 브라우저에서 열리는 무료 도구: 이미지, PDF, 텍스트, 코드, 웹사이트, 이메일, 동영상, 판매.
- [Awesome NF-e](https://go.mymarketing.click/wapi-lista-nfe) - 전자 송장(NF-e)을 연동하는 개발자를 위한 자료: 공식 포털, 언어별 라이브러리, 발행 API, MCP 서버.
- [Awesome APIs Brasil](https://go.mymarketing.click/wapi-lista-apis-brasil) - 브라질 공개 API 모음: CEP, CNPJ, 중앙은행, IBGE, 입법부, 사법부, 공휴일 및 공개 데이터.
- [Awesome Claude Code BR](https://go.mymarketing.click/wapi-lista-claude-code-br) - 포르투갈어로 보는 Claude Code: 문서, 강좌, 스킬, 규칙, 플러그인, 브라질에서 만든 MCP 서버.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/wapi-lista-pagamentos-brasil) - 브라질 결제를 연동하는 개발자를 위한 자료: 규정, 게이트웨이, 매입사, boleto, 구독, split, 사기 방지.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/wapi-lista-open-finance-brasil) - 브라질의 Open Finance 및 Open Insurance: 규정, 명세, 공개 데이터, 어그리게이터, 오픈 소스.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/wapi-lista-empresa-de-uma-pessoa) - AI 에이전트로 사업 전체를 운영하는 데 필요한 도구: 서비스 공개, 결제, 측정, 홍보, 검색 노출.

## Ciro Cesar Maciel 제작

제가 만든 것을 사용해 주시는 것도 이 목록을 지원하는 방법입니다.

목록이 시간을 아껴 주셨다면 커피 한 잔으로 모든 목록을 유지하는 데 도움을 주세요. 후원 금액은 직접 정하며 Pix 또는 카드로 보내실 수 있습니다. [![후원하기](https://img.shields.io/badge/%ED%9B%84%EC%9B%90%ED%95%98%EA%B8%B0-%EC%BB%A4%ED%94%BC%20%ED%95%9C%20%EC%9E%94-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-agents)

## 라이선스

이 목록은 CC0 1.0 라이선스를 따릅니다. 허락을 구하지 않고 복사, 수정, 재배포하셔도 됩니다. 생성기 코드는 MIT 라이선스로 awesome-kit에 있습니다.

<sub>업데이트 날짜 2026-11-10.</sub>
