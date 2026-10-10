# awesome-osint-ai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md)

OSINT(オープンソースインテリジェンス)に使える **AI / LLM / MCP ツール** のキュレーションリストです。AIエージェント、MCPサーバー、状況把握ダッシュボード、GEOINT、およびそれらの土台となる定番ツールを掲載しています。

スターバッジは shields.io による自動更新です。プルリクエスト歓迎。

> **倫理と法令遵守**: 掲載ツールは、合法かつ正当な目的(セキュリティ研究、報道、デューデリジェンス、トラスト&セーフティ)にのみ使用してください。プライバシー、各サービスの利用規約、国内法(個人情報保護法など)を尊重し、ストーキング・嫌がらせ・個人情報の晒しには使わないでください。

## 目次

- [関連するawesomeリスト](#関連するawesomeリスト)
- [AIエージェント・フレームワーク](#aiエージェントフレームワーク)
- [MCPサーバー](#mcpサーバー)
- [状況把握・GEOINT](#状況把握geoint)
- [定番OSINTツール(土台)](#定番osintツール土台)
- [コントリビュート](#コントリビュート)

## 関連するawesomeリスト

- [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint) ![stars](https://img.shields.io/github/stars/jivoi/awesome-osint?style=social) - 長年続く総合OSINTリスト。
- [Astrosp/Awesome-OSINT-List](https://github.com/Astrosp/Awesome-OSINT-List) ![stars](https://img.shields.io/github/stars/Astrosp/Awesome-OSINT-List?style=social) - 幅広いOSINTツール集。AIツールも含む。
- [ubikron/Awesome-AI-OSINT](https://github.com/ubikron/Awesome-AI-OSINT) ![stars](https://img.shields.io/github/stars/ubikron/Awesome-AI-OSINT?style=social) - AI×OSINTの記事・動画・ツール集。
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ![stars](https://img.shields.io/github/stars/soxoj/awesome-osint-mcp-servers?style=social) - OSINT向けMCPサーバーのリスト。

## AIエージェント・フレームワーク

- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) ![stars](https://img.shields.io/github/stars/OpenOSINT/OpenOSINT?style=social) - REPL・MCPサーバー・CLIを備えたAI OSINTエージェント。クラウド/ローカルモデル対応。許可された調査のみ。
- [7onez/cti-expert](https://github.com/7onez/cti-expert) ![stars](https://img.shields.io/github/stars/7onez/cti-expert?style=social) - Claude Code / Codex 用のサイバー脅威インテリジェンス・OSINT分析スキル。
- [ThreatRecall/zettelforge](https://github.com/ThreatRecall/zettelforge) ![stars](https://img.shields.io/github/stars/ThreatRecall/zettelforge?style=social) - CTI向けエージェント記憶。STIXナレッジグラフ、オフラインRAG、MCPサーバー。

## MCPサーバー

- [marc-shade/world-intel-mcp](https://github.com/marc-shade/world-intel-mcp) ![stars](https://img.shields.io/github/stars/marc-shade/world-intel-mcp?style=social) - 120ツールのMCPサーバー。出典付きの状況ブリーフやジオフェンスに対応。
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) ![stars](https://img.shields.io/github/stars/damionrashford/RivalSearchMCP?style=social) - 複数エンジンのWeb検索、SNS検索、学術DB、エンティティ調査。APIキー不要。

## 状況把握・GEOINT

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) ![stars](https://img.shields.io/github/stars/koala73/worldmonitor?style=social) - リアルタイムのグローバル情報ダッシュボード。AIによるニュース集約、地政学・インフラ監視。
- [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) ![stars](https://img.shields.io/github/stars/bilawalsidhu/gods-eye-view?style=social) - 実データを使うブラウザ上の3D地球儀(衛星・航空機など)。

## 定番OSINTツール(土台)

上記のAIエージェントの多くが内部で利用しています。

- [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) ![stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=social) - ユーザー名からSNSアカウントを検索。
- [soxoj/maigret](https://github.com/soxoj/maigret) ![stars](https://img.shields.io/github/stars/soxoj/maigret?style=social) - 多数のサイトからユーザー名ベースのプロファイルを収集。
- [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) ![stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=social) - 脅威インテリジェンス・攻撃対象領域把握のためのOSINT自動化。
- [laramies/theHarvester](https://github.com/laramies/theHarvester) ![stars](https://img.shields.io/github/stars/laramies/theHarvester?style=social) - メール・サブドメイン・氏名の収集。
- [lissy93/web-check](https://github.com/lissy93/web-check) ![stars](https://img.shields.io/github/stars/lissy93/web-check?style=social) - Webサイト解析のオールインワンツール。
- [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) ![stars](https://img.shields.io/github/stars/gildas-lormeau/SingleFile?style=social) - Webページを単一HTMLで保存(証拠保全向け)。

## コントリビュート

プルリクエストで追加してください。1ツール1行、セクション内はアルファベット順、事実に基づく短い説明を添えてください。攻撃目的のみのツールや、個人を標的にするプライバシー侵害型のツールは受け付けません。
