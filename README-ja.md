# Awesome WhatsApp API

> WhatsApp連携を行う方向け: Metaの公式API、プロバイダー、非公式ライブラリ、それぞれの経路のリスク。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E8%B3%BC%E8%AA%AD-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-cartas) [![応援する](https://img.shields.io/badge/%E5%BF%9C%E6%8F%B4%E3%81%99%E3%82%8B-%E3%82%B3%E3%83%BC%E3%83%92%E3%83%BC1%E6%9D%AF-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/wapi-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/wapi-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/wapi-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/ja.xml) ![26 項目](https://img.shields.io/badge/%E9%A0%85%E7%9B%AE-26-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja-on.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

プログラムからWhatsAppの送受信をしたい人向けで、コードを書く前に経路を選ぶ必要がある人のためのリストです。公式APIは企業に唯一認められた方法です。非公式ライブラリは動きますが、番号がBANされるおそれがあります。このリストは両者を分けて、各セクションでそのことを明記しています。

## 目次

- [Meta公式](#meta公式)
- [公式APIのライブラリ](#公式apiのライブラリ)
- [公式APIのプロバイダー](#公式apiのプロバイダー)
- [非公式ライブラリ](#非公式ライブラリ)
- [すぐ使えるRESTサーバー](#すぐ使えるrestサーバー)
- [カスタマーサポート](#カスタマーサポート)
- [無料のツール](#無料のツール)
- [ラベル](#ラベル)
- [貢献方法](#貢献方法)
- [他のリスト](#他のリスト)
- [作者: Ciro Cesar Maciel](#作者-ciro-cesar-maciel)
- [ライセンス](#ライセンス)

## Meta公式

Metaがプログラムから顧客とやり取りすることを認めている唯一の方法。

- [WhatsApp Business Platform](https://go.mymarketing.click/wapi-whatsapp-business-platform) - Cloud APIのドキュメント: 送信、受信、メッセージテンプレート、webhook。 `公式` `API`
- [Preços da plataforma](https://go.mymarketing.click/wapi-precos-da-plataforma) - Metaがメッセージと会話カテゴリーごとに料金を請求する仕組み。 `公式`
- [Política do WhatsApp Business](https://go.mymarketing.click/wapi-politica-do-whatsapp-business) - WhatsAppで企業が許可されていること、禁止されていること。 `公式`
- [Termos do WhatsApp Business](https://go.mymarketing.click/wapi-termos-do-whatsapp-business) - ビジネスアカウント向けの利用規約。 `公式`
- [WhatsApp Business](https://go.mymarketing.click/wapi-whatsapp-business) - 企業向けWhatsAppのサイト。アプリとプラットフォームを含む。 `公式`

## 公式APIのライブラリ

オープンで、Meta Cloud API向け。

- [whatsapp-api-js](https://go.mymarketing.click/wapi-whatsapp-api-js) - Cloud API向けの軽量で依存関係のないTypeScriptライブラリ。 `オープンソース` `無料`
- [whatsapp-cloud-api](https://go.mymarketing.click/wapi-whatsapp-cloud-api) - PHPでCloud APIを使った送受信。 `オープンソース` `無料`

## 公式APIのプロバイダー

Metaのパートナーで、APIを再販売・運用している企業。アルファベット順。

- [360dialog](https://go.mymarketing.click/wapi-360dialog) - 番号ごとに課金される公式APIへの直接アクセス。 `API` `有料`
- [Blip](https://go.mymarketing.click/wapi-blip) - WhatsApp上のカスタマーサポートとチャットボットのためのブラジル製プラットフォーム。 `有料`
- [Gupshup](https://go.mymarketing.click/wapi-gupshup) - WhatsAppとチャットボットのためのメッセージAPI。 `API` `有料`
- [Infobip](https://go.mymarketing.click/wapi-infobip) - WhatsAppに対応したomnichannel API。 `API` `有料`
- [Twilio](https://go.mymarketing.click/wapi-twilio) - TwilioのAPIを通じたWhatsApp。SMSと音声も含む。 `API` `有料`
- [Zenvia](https://go.mymarketing.click/wapi-zenvia) - WhatsApp、SMS、メールに対応したブラジル製のコミュニケーションプラットフォーム。 `有料`

## 非公式ライブラリ

WhatsApp Webとして接続します。Metaは企業でのこの利用を認めておらず、番号がBANされる可能性があります。個人利用、テスト、自分の自動化向けです。

- [Baileys](https://go.mymarketing.click/wapi-baileys) - ブラウザを使わず、socket経由でWhatsApp Webのプロトコルを扱うTypeScript API。 `オープンソース` `無料`
- [whatsapp-web.js](https://go.mymarketing.click/wapi-whatsapp-web-js) - 制御されたブラウザでWhatsApp Webに接続するNode.jsクライアント。 `オープンソース` `無料`
- [whatsmeow](https://go.mymarketing.click/wapi-whatsmeow) - WhatsApp WebのマルチデバイスAPI向けのGoライブラリ。 `オープンソース` `無料`
- [WPPConnect](https://go.mymarketing.click/wapi-wppconnect) - ブラジルのチームによる、Node.jsとTypeScriptで書かれたWhatsApp Webの自動化。 `オープンソース` `無料`
- [Venom](https://go.mymarketing.click/wapi-venom) - WhatsApp Web向けのボットを作るJavaScriptのシステム。 `オープンソース` `無料`
- [wacli](https://go.mymarketing.click/wapi-wacli) - メッセージの同期、検索、送信を行うコマンドラインツール。 `オープンソース` `無料`

## すぐ使えるRESTサーバー

上記のライブラリを包むHTTP APIを提供します。同じ制限が適用されます。

- [Evolution API](https://go.mymarketing.click/wapi-evolution-api) - オープンソースでブラジル製のWhatsApp連携API。 `オープンソース` `無料`
- [WAHA](https://go.mymarketing.click/wapi-waha) - 複数のエンジンと複数セッションに対応したWhatsApp HTTP API。 `オープンソース` `無料`
- [WPPConnect Server](https://go.mymarketing.click/wapi-wppconnect-server) - WPPConnect上に構築したセルフホスト型REST API。 `オープンソース` `無料`

## カスタマーサポート

チームが返信するための受信トレイ。

- [Chatwoot](https://go.mymarketing.click/wapi-chatwoot) - WhatsApp、メール、サイト上のチャットに対応したオープンソースのカスタマーサポート窓口。 `オープンソース` `無料`

## 無料のツール

登録不要、ブラウザで使えます。

- [Gerador de link de WhatsApp](https://go.mymarketing.click/wapi-gerador-de-link-de-whatsapp) - メッセージが入力済みのwa.meリンクと、印刷用のQRコード。 `無料` `作者作成`
- [QR Code do WhatsApp](https://go.mymarketing.click/wapi-qr-code-do-whatsapp) - メッセージが入力済みの状態で会話を開くQRコード。PNGまたはSVG形式。 `無料` `作者作成`
- [Nome, descrição e regras para grupo](https://go.mymarketing.click/wapi-nome-descricao-e-regras-para-grupo) - グループに貼り付けられる、名前のアイデア、説明文、ルール。 `無料` `作者作成`

## ラベル

各項目には内容が書かれています。横のラベルは選ぶ際の参考になります。公式は標準を定めている側から提供されるもの、オープンソースはコードが公開されているもの、無料と有料は利用モデルによるもの、APIとSDKは連携の方法を表します。「作者作成」のラベルが付いた項目はCiro Cesar Macielが作成したもので、他のすべての項目と同じルールに従っています。

## 貢献方法

足りないもの、変わったもの、使えなくなったものはありますか？新規追加フォームからissueを開くか、data/list.jsonを編集してpull requestを送ってください。各言語のREADMEはこのファイルから生成されています。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 他のリスト

同じ形式のキュレーションリストで、ポルトガル語と他14言語があります。

- [Awesome IA no trabalho](https://go.mymarketing.click/wapi-lista-ia-no-trabalho) - 職業別の仕事でのAI: アシスタント、プライバシー、規範、そしてAIの書いた内容を確認するための公式情報源。
- [Awesome IA na advocacia](https://go.mymarketing.click/wapi-lista-ia-advocacia) - 弁護士向けのAI: アシスタント、プライバシー、法律事務所と司法におけるAIの規範、そして確認のための公式情報源。
- [Awesome IA na contabilidade](https://go.mymarketing.click/wapi-lista-ia-contabilidade) - 会計士向けのAI: アシスタント、プライバシー、CFCの規範、そして確認のための国税庁、eSocial、Simplesの情報源。
- [Awesome IA na sala de aula](https://go.mymarketing.click/wapi-lista-ia-sala-de-aula) - 教師向けのAI: 各アシスタントの利用最低年齢とプライバシー、そして確認のための教育分野の規範。
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/wapi-lista-ia-atendimento-e-vendas) - 接客・販売に携わる人向けのAI: アシスタント、プライバシー、消費者の権利、そして窓口、レジ、電話対応をする人の労働規則。
- [Awesome IA no escritório](https://go.mymarketing.click/wapi-lista-ia-escritorio) - 秘書、アシスタント、事務職向けのAI: アシスタント、プライバシー、公式文書の書き方、そしてメールで届く詐欺。
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/wapi-lista-ia-pequeno-negocio) - MEIと小規模事業者向けのAI: アシスタント、プライバシー、小規模事業者にとってのMEIとSimplesの規則、消費者保護、LGPD。
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/wapi-lista-ia-primeiro-trabalho) - 働き始める人向けのAI: アシスタント、プライバシー、求人の探し方、初めての仕事の権利、そして偽の求人詐欺。
- [Awesome Pix](https://go.mymarketing.click/wapi-lista-pix) - Pixの連携を行う方向け: 規範、API、SDK、プロバイダー、ツールを一つずつ確認したリストです。
- [Awesome MCP Brasil](https://go.mymarketing.click/wapi-lista-mcp-brasil) - ブラジルのサービス向けMCPサーバー: 公開データ、CNPJ、税務、法務、金融市場、商取引、決済。
- [Awesome livros de IA](https://go.mymarketing.click/wapi-lista-livros-ia) - ポルトガル語で読める人工知能の本: 最初の利用から職業での活用、作る人から議論まで。
- [Awesome ferramentas online](https://go.mymarketing.click/wapi-lista-ferramentas-online) - ブラウザで開くだけでインストール不要の無料ツール: 画像、PDF、テキスト、コード、サイト、メール、動画、販売。
- [Awesome NF-e](https://go.mymarketing.click/wapi-lista-nfe) - 統合する開発者向けの電子インボイス: 公式ポータル、言語別ライブラリ、発行API、MCPサーバー。
- [Awesome APIs Brasil](https://go.mymarketing.click/wapi-lista-apis-brasil) - ブラジルの公開API: CEP、CNPJ、中央銀行、IBGE、立法、司法、祝日、オープンデータ。
- [Awesome Claude Code BR](https://go.mymarketing.click/wapi-lista-claude-code-br) - ポルトガル語のClaude Code: ドキュメント、コース、skills、ルール、プラグイン、ブラジル製のMCPサーバー。
- [Awesome pagamentos Brasil](https://go.mymarketing.click/wapi-lista-pagamentos-brasil) - ブラジルで決済を統合する開発者向け: 規則、ゲートウェイ、アクワイアラー、boleto、電子署名、split、不正検知。
- [Awesome Open Finance Brasil](https://go.mymarketing.click/wapi-lista-open-finance-brasil) - ブラジルのOpen FinanceとOpen Insurance: 規則、仕様、オープンデータ、アグリゲーター、オープンソースコード。
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/wapi-lista-empresa-de-uma-pessoa) - AIエージェントだけで事業を回すために使うもの: 公開、課金、計測、宣伝、見つけてもらうこと。

## 作者: Ciro Cesar Maciel

私の仕事を利用することも、これらのリストを応援する一つの方法です。

このリストで時間が節約できたなら、コーヒー1杯でリストの維持を支えられます。寄付はPixまたはカードで、金額は自由に選べます。 [![応援する](https://img.shields.io/badge/%E5%BF%9C%E6%8F%B4%E3%81%99%E3%82%8B-%E3%82%B3%E3%83%BC%E3%83%92%E3%83%BC1%E6%9D%AF-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/wapi-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/wapi-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/wapi-por-agents)

## ライセンス

このリストはCC0 1.0の下にあります。許可を求めることなく、自由にコピー、改変、再配布できます。ジェネレーターのコードはawesome-kitにあり、MITの下にあります。

<sub>最終更新 2026-11-10.</sub>
