# awesome-osint-ai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md)

OSINT(オープンソースインテリジェンス)に使える **AI / LLM / MCP ツール** のキュレーションリストです。AIエージェント、MCPサーバー、状況把握ダッシュボード、GEOINT、ローカルLLM、日本の公的情報源を掲載しています。

⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。release バッジは GitHub の最新リリース日(YYYY/MM/DD、最終更新時点)を示します。last commit バッジは最新コミット日をリアルタイム表示します(shields.io)。プルリクエスト歓迎。

> **倫理と法令遵守**: 掲載ツールは、合法かつ正当な目的(セキュリティ研究、報道、デューデリジェンス、トラスト&セーフティ)にのみ使用してください。プライバシー、各サービスの利用規約、国内法(個人情報保護法など)を尊重し、ストーキング・嫌がらせ・個人情報の晒しには使わないでください。

## 目次

- [関連するawesomeリスト](#関連するawesomeリスト)
- [AIエージェント・フレームワーク](#aiエージェントフレームワーク)
- [MCPサーバー](#mcpサーバー)
- [状況把握・GEOINT](#状況把握geoint)
- [ローカルLLM(非公開データの分析用)](#ローカルllm非公開データの分析用)
- [日本の公的情報源](#日本の公的情報源)
- [定番OSINTツール(土台)](#定番osintツール土台)
- [コントリビュート](#コントリビュート)
- [shvyac の awesome リスト](#shvyac-の-awesome-リスト)

## 関連するawesomeリスト

- [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint) ![GitHub stars](https://img.shields.io/github/stars/jivoi/awesome-osint?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F19-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/jivoi/awesome-osint?style=flat) - 長年続く総合OSINTリスト。
- [Astrosp/Awesome-OSINT-List](https://github.com/Astrosp/Awesome-OSINT-List) ![GitHub stars](https://img.shields.io/github/stars/Astrosp/Awesome-OSINT-List?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Astrosp/Awesome-OSINT-List?style=flat) - 幅広いOSINTツール集。AIツールも含む。
- [ubikron/Awesome-AI-OSINT](https://github.com/ubikron/Awesome-AI-OSINT) ![GitHub stars](https://img.shields.io/github/stars/ubikron/Awesome-AI-OSINT?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/ubikron/Awesome-AI-OSINT?style=flat) - AI×OSINTの記事・動画・ツール集。
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ![GitHub stars](https://img.shields.io/github/stars/soxoj/awesome-osint-mcp-servers?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/soxoj/awesome-osint-mcp-servers?style=flat) - OSINT向けMCPサーバーのリスト。
- [shvyac/awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/shvyac/awesome-local-llm?style=flat) - ローカルLLMツール集(姉妹リスト)。
- [llm-jp/awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) ![GitHub stars](https://img.shields.io/github/stars/llm-jp/awesome-japanese-llm?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/llm-jp/awesome-japanese-llm?style=flat) - 日本語LLMまとめ。
- [taishi-i/awesome-japanese-nlp-resources](https://github.com/taishi-i/awesome-japanese-nlp-resources) ![GitHub stars](https://img.shields.io/github/stars/taishi-i/awesome-japanese-nlp-resources?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/taishi-i/awesome-japanese-nlp-resources?style=flat) - 日本語NLPのライブラリ・LLM・辞書・コーパス・データセット集。
- [frangelbarrera/OSINT-BIBLE](https://github.com/frangelbarrera/OSINT-BIBLE) ![GitHub stars](https://img.shields.io/github/stars/frangelbarrera/OSINT-BIBLE?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/frangelbarrera/OSINT-BIBLE?style=flat) - ツール、AI活用、調査ワークフロー、検証、GEOINT、OPSEC、倫理をまとめたOSINTフィールドガイド。

## AIエージェント・フレームワーク

- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) ![GitHub stars](https://img.shields.io/github/stars/OpenOSINT/OpenOSINT?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F15-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/OpenOSINT/OpenOSINT?style=flat) - オープンソースのOSINTエージェント。21の公開情報ツールを自然言語チャット・MCPサーバー・Claude Codeプラグインで利用可能。デフォルトはパッシブ調査で、APIキーなしで開始可能。クラウド/ローカルモデル対応。許可された調査のみ。
- [7onez/cti-expert](https://github.com/7onez/cti-expert) ![GitHub stars](https://img.shields.io/github/stars/7onez/cti-expert?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/7onez/cti-expert?style=flat) - Claude Code / Codex 用のサイバー脅威インテリジェンス・OSINT分析スキル。120以上のコマンド、79の型付きMCPツール、決定論的なケースパイプライン、ICD-203形式のレポート。コア機能はAPIキー不要。
- [ThreatRecall/zettelforge](https://github.com/ThreatRecall/zettelforge) ![GitHub stars](https://img.shields.io/github/stars/ThreatRecall/zettelforge?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F06%2F27-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/ThreatRecall/zettelforge?style=flat) - CTI向けエージェント記憶。STIXナレッジグラフ、脅威アクターの別名解決、オフラインRAG、MCPサーバー。

## MCPサーバー

- [marc-shade/world-intel-mcp](https://github.com/marc-shade/world-intel-mcp) ![GitHub stars](https://img.shields.io/github/stars/marc-shade/world-intel-mcp?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F02-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/marc-shade/world-intel-mcp?style=flat) - 無料の公開APIを使う160ツールのMCPサーバー(有料APIキー不要)。出典付きの状況ブリーフ、日付付きの観測履歴、ジオフェンスに対応。
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) ![GitHub stars](https://img.shields.io/github/stars/damionrashford/RivalSearchMCP?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F04%2F17-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/damionrashford/RivalSearchMCP?style=flat) - 決定論的なリサーチ用MCPサーバー(FastMCP 3)。5エンジンのWeb検索、9プラットフォームのSNS検索、6つの学術DB、ニュース集約、エンティティ調査。APIキー不要。
- [publicrecords/company-social-profile-finder](https://apify.com/publicrecords/company-social-profile-finder) - 会社名や Web サイトから、その会社の LinkedIn、X、YouTube、Instagram、Facebook のアカウントを根拠付きで特定する MCP / Apify Actor（従量課金、Apify 無料枠あり）。
- [w0h1v/mcp-shodan](https://github.com/w0h1v/mcp-shodan) ![GitHub stars](https://img.shields.io/github/stars/w0h1v/mcp-shodan?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F08-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/w0h1v/mcp-shodan?style=flat) - Shodan用MCPサーバー。インターネット接続機器の検索、IP調査、DNS検索、CVE/CPE脆弱性情報(Shodan APIキーが必要)。
- [w0h1v/mcp-maigret](https://github.com/w0h1v/mcp-maigret) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/w0h1v/mcp-maigret?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/w0h1v/mcp-maigret?style=flat) - AIエージェントからmaigret(多数のサイトを横断するユーザー名検索)をDocker経由で実行するMCPサーバー。Claude Codeなど各種MCPクライアントに対応。

## 状況把握・GEOINT

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) ![GitHub stars](https://img.shields.io/github/stars/koala73/worldmonitor?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F04-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/koala73/worldmonitor?style=flat) - リアルタイムのグローバル情報ダッシュボード。AIによるニュース集約、地政学・インフラ監視。
- [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) ![GitHub stars](https://img.shields.io/github/stars/bilawalsidhu/gods-eye-view?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F28-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/bilawalsidhu/gods-eye-view?style=flat) - 実データを使うブラウザ上の3D地球儀(衛星・航空機など)。
- [AndrewCTF/velocity](https://github.com/AndrewCTF/velocity) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/AndrewCTF/velocity?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F22-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/AndrewCTF/velocity?style=flat) - 独自の履歴を保持して巻き戻し再生できる、セルフホスト型の航空機・船舶トラッカー(ADS-B / AIS)。3D地球儀とMCPサーバー付き。APIキー不要。

## ローカルLLM(非公開データの分析用)

自分のマシンでモデルを動かせば、調査資料やメモ、案件ファイルなどの機微な情報を外部サーバーに送らずに済みます。上記のエージェントと組み合わせて使えます。

- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) ![GitHub stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F13-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/ggml-org/llama.cpp?style=flat) - C/C++によるLLM推論。多くのローカルツールの基盤。
- [ollama/ollama](https://github.com/ollama/ollama) ![GitHub stars](https://img.shields.io/github/stars/ollama/ollama?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F09-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/ollama/ollama?style=flat) - オープンウェイトモデルをローカルで手軽に実行。
- [vllm-project/vllm](https://github.com/vllm-project/vllm) ![GitHub stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F16-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/vllm-project/vllm?style=flat) - 高スループット・省メモリな推論/サービングエンジン(GPUサーバー向け)。
- [open-webui/open-webui](https://github.com/open-webui/open-webui) ![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F17-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?style=flat) - OllamaやOpenAI互換APIに対応するセルフホスト型AIインターフェース。RAG対応。
- [janhq/jan](https://github.com/janhq/jan) ![GitHub stars](https://img.shields.io/github/stars/janhq/jan?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F10%2F28-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/janhq/jan?style=flat) - 完全オフラインで動くオープンソースのChatGPT代替。
- [mozilla-ai/llamafile](https://github.com/mozilla-ai/llamafile) ![GitHub stars](https://img.shields.io/github/stars/mozilla-ai/llamafile?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F15-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/mozilla-ai/llamafile?style=flat) - LLMを単一ファイルで配布・実行。
- [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) ![GitHub stars](https://img.shields.io/github/stars/zylon-ai/private-gpt?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F06%2F18-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/zylon-ai/private-gpt?style=flat) - ローカルモデル上のプライベートAI用APIレイヤー。RAG・ツール・MCP対応。

## 日本の公的情報源

合法的な調査やデューデリジェンスに役立つ、日本の公的なオープンデータ・登録情報です。GitHubリポジトリではなくWebサービスですが、APIや一括ダウンロードを備えるものが多く、上記のローカルLLMやエージェントと組み合わせやすいものです。各サイトの利用規約と出典明示のルールを確認してください。

### 地理空間(GEOINT)

- [地理院地図](https://maps.gsi.go.jp/) - 国土地理院のウェブ地図。地形図、空中写真(年代別の比較や戦前の東京の写真を含む)、標高、地形分類、災害情報など1,800以上のレイヤーを重ねて閲覧可能。
- [国土地理院](https://www.gsi.go.jp/) - 地図・空中写真閲覧サービスや、基盤地図情報・標高(DEM)データのダウンロード(利用者登録が必要)への入口。

### 官報・法令

- [官報の公式案内(内閣府)](https://www.cao.go.jp/others/soumu/kanpo/) - 2025年4月1日から官報は電子化され、「官報発行サイト」(https://www.kanpo.go.jp/)への掲載をもって発行されます。同サイトの電子データが正本です。旧「インターネット版官報」は2025年3月31日に公開を終了しましたが、過去の官報は新サイトで引き続き提供されています。個人情報を含む公告があるため、個人の一覧として収集・再公開しないでください。
- [国立国会図書館デジタルコレクション](https://dl.ndl.go.jp/) - 過去の官報など、国立国会図書館のデジタル化資料。

### 企業・法人データ

- [国税庁 法人番号公表サイト](https://www.houjin-bangou.nta.go.jp/) - 日本の法人の法人番号・商号・本店所在地を検索・一括ダウンロード可能。Web-APIも提供。
- [gBizINFO](https://info.gbiz.go.jp/) - 経済産業省の法人情報サービス。法人番号をキーに、補助金・届出認定・特許・調達・財務・職場情報などを横断取得。REST API対応。
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - 金融庁の開示書類閲覧システム。上場企業・大企業の有価証券報告書など。
- [e-Stat(政府統計の総合窓口)](https://www.e-stat.go.jp/) - 政府統計のポータル。APIで取得可能。

## 定番OSINTツール(土台)

上記のAIエージェントの多くが内部で利用しています。

- [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) ![GitHub stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F08-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/sherlock-project/sherlock?style=flat) - ユーザー名からSNSアカウントを検索。
- [soxoj/maigret](https://github.com/soxoj/maigret) ![GitHub stars](https://img.shields.io/github/stars/soxoj/maigret?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F09%2F18-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/soxoj/maigret?style=flat) - 約6,000のサイトからユーザー名ベースのプロファイルを収集。
- [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) ![GitHub stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2022%2F04%2F07-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/smicallef/spiderfoot?style=flat) - 脅威インテリジェンス・攻撃対象領域把握のためのOSINT自動化。
- [laramies/theHarvester](https://github.com/laramies/theHarvester) ![GitHub stars](https://img.shields.io/github/stars/laramies/theHarvester?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F06%2F03-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/laramies/theHarvester?style=flat) - メール・サブドメイン・氏名の収集。
- [lissy93/web-check](https://github.com/lissy93/web-check) ![GitHub stars](https://img.shields.io/github/stars/lissy93/web-check?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F05-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/lissy93/web-check?style=flat) - Webサイト解析のオールインワンツール。
- [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) ![GitHub stars](https://img.shields.io/github/stars/gildas-lormeau/SingleFile?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F17-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/gildas-lormeau/SingleFile?style=flat) - Webページを単一HTMLで保存(証拠保全向け)。

## コントリビュート

プルリクエストで追加してください。1ツール1行、セクション内はアルファベット順、事実に基づく短い説明を添えてください。攻撃目的のみのツールや、個人を標的にするプライバシー侵害型のツールは受け付けません。

## shvyac の awesome リスト

[shvyac](https://github.com/shvyac) が管理しているキュレーションリストの一覧:

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-mcp-ai](https://github.com/shvyac/awesome-mcp-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-mcp-ai?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-physical-ai-kaizen](https://github.com/shvyac/awesome-physical-ai-kaizen) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-physical-ai-kaizen?style=flat&label=%E2%AD%90)
- [awesome-quantum](https://github.com/shvyac/awesome-quantum) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-quantum?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
- [awesome-web-app-design](https://github.com/shvyac/awesome-web-app-design) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-web-app-design?style=flat&label=%E2%AD%90)
