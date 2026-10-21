# awesome-osint-ai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md)

OSINT(オープンソースインテリジェンス)に使える **AI / LLM / MCP ツール** のキュレーションリストです。AIエージェント、MCPサーバー、状況把握ダッシュボード、GEOINT、ローカルLLM、日本の公的情報源を掲載しています。

スターバッジは shields.io による自動更新です。プルリクエスト歓迎。

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

- [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint) ![stars](https://img.shields.io/github/stars/jivoi/awesome-osint?style=social) - 長年続く総合OSINTリスト。
- [Astrosp/Awesome-OSINT-List](https://github.com/Astrosp/Awesome-OSINT-List) ![stars](https://img.shields.io/github/stars/Astrosp/Awesome-OSINT-List?style=social) - 幅広いOSINTツール集。AIツールも含む。
- [ubikron/Awesome-AI-OSINT](https://github.com/ubikron/Awesome-AI-OSINT) ![stars](https://img.shields.io/github/stars/ubikron/Awesome-AI-OSINT?style=social) - AI×OSINTの記事・動画・ツール集。
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ![stars](https://img.shields.io/github/stars/soxoj/awesome-osint-mcp-servers?style=social) - OSINT向けMCPサーバーのリスト。
- [shvyac/awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=social) - ローカルLLMツール集(姉妹リスト)。
- [llm-jp/awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) ![stars](https://img.shields.io/github/stars/llm-jp/awesome-japanese-llm?style=social) - 日本語LLMまとめ。
- [taishi-i/awesome-japanese-nlp-resources](https://github.com/taishi-i/awesome-japanese-nlp-resources) ![stars](https://img.shields.io/github/stars/taishi-i/awesome-japanese-nlp-resources?style=social) - 日本語NLPのライブラリ・LLM・辞書・コーパス・データセット集。

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

## ローカルLLM(非公開データの分析用)

自分のマシンでモデルを動かせば、調査資料やメモ、案件ファイルなどの機微な情報を外部サーバーに送らずに済みます。上記のエージェントと組み合わせて使えます。

- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) ![stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=social) - C/C++によるLLM推論。多くのローカルツールの基盤。
- [ollama/ollama](https://github.com/ollama/ollama) ![stars](https://img.shields.io/github/stars/ollama/ollama?style=social) - オープンウェイトモデルをローカルで手軽に実行。
- [vllm-project/vllm](https://github.com/vllm-project/vllm) ![stars](https://img.shields.io/github/stars/vllm-project/vllm?style=social) - 高スループット・省メモリな推論/サービングエンジン(GPUサーバー向け)。
- [open-webui/open-webui](https://github.com/open-webui/open-webui) ![stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social) - OllamaやOpenAI互換APIに対応するセルフホスト型AIインターフェース。RAG対応。
- [janhq/jan](https://github.com/janhq/jan) ![stars](https://img.shields.io/github/stars/janhq/jan?style=social) - 完全オフラインで動くオープンソースのChatGPT代替。
- [mozilla-ai/llamafile](https://github.com/mozilla-ai/llamafile) ![stars](https://img.shields.io/github/stars/mozilla-ai/llamafile?style=social) - LLMを単一ファイルで配布・実行。
- [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) ![stars](https://img.shields.io/github/stars/zylon-ai/private-gpt?style=social) - ローカルモデル上のプライベートAI用APIレイヤー。RAG・ツール・MCP対応。

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

- [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) ![stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=social) - ユーザー名からSNSアカウントを検索。
- [soxoj/maigret](https://github.com/soxoj/maigret) ![stars](https://img.shields.io/github/stars/soxoj/maigret?style=social) - 多数のサイトからユーザー名ベースのプロファイルを収集。
- [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) ![stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=social) - 脅威インテリジェンス・攻撃対象領域把握のためのOSINT自動化。
- [laramies/theHarvester](https://github.com/laramies/theHarvester) ![stars](https://img.shields.io/github/stars/laramies/theHarvester?style=social) - メール・サブドメイン・氏名の収集。
- [lissy93/web-check](https://github.com/lissy93/web-check) ![stars](https://img.shields.io/github/stars/lissy93/web-check?style=social) - Webサイト解析のオールインワンツール。
- [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) ![stars](https://img.shields.io/github/stars/gildas-lormeau/SingleFile?style=social) - Webページを単一HTMLで保存(証拠保全向け)。

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
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
