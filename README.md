# awesome-osint-ai [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版 / Japanese](README.ja.md)

A curated list of **AI / LLM / MCP tools for OSINT** (open-source intelligence): agents, MCP servers, situational-awareness dashboards, GEOINT, local LLMs for private analysis, and Japan-focused public data sources.

Star badges are live (shields.io). Pull requests welcome.

> **Ethics & legality**: Use these resources only for lawful, authorized purposes (security research, journalism, due diligence, trust & safety). Respect privacy, platform terms of service, and local law (e.g. APPI in Japan, GDPR in the EU). Do not use them to stalk, harass, or dox.

## Contents

- [Related awesome lists](#related-awesome-lists)
- [AI agents & frameworks](#ai-agents--frameworks)
- [MCP servers](#mcp-servers)
- [Situational awareness & GEOINT](#situational-awareness--geoint)
- [Local LLM for private analysis](#local-llm-for-private-analysis)
- [Japan-focused public sources](#japan-focused-public-sources)
- [Classic OSINT tools (building blocks)](#classic-osint-tools-building-blocks)
- [Contributing](#contributing)
- [shvyac's awesome lists](#shvyacs-awesome-lists)

## Related awesome lists

- [jivoi/awesome-osint](https://github.com/jivoi/awesome-osint) ![stars](https://img.shields.io/github/stars/jivoi/awesome-osint?style=social) - The long-standing general OSINT list.
- [Astrosp/Awesome-OSINT-List](https://github.com/Astrosp/Awesome-OSINT-List) ![stars](https://img.shields.io/github/stars/Astrosp/Awesome-OSINT-List?style=social) - Broad OSINT tools collection, includes AI tools.
- [ubikron/Awesome-AI-OSINT](https://github.com/ubikron/Awesome-AI-OSINT) ![stars](https://img.shields.io/github/stars/ubikron/Awesome-AI-OSINT?style=social) - Articles, videos, and tools on using AI for OSINT.
- [soxoj/awesome-osint-mcp-servers](https://github.com/soxoj/awesome-osint-mcp-servers) ![stars](https://img.shields.io/github/stars/soxoj/awesome-osint-mcp-servers?style=social) - Curated list of OSINT MCP servers.
- [shvyac/awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=social) - Local LLM tools list (companion list).
- [llm-jp/awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) ![stars](https://img.shields.io/github/stars/llm-jp/awesome-japanese-llm?style=social) - Overview of Japanese LLMs.
- [taishi-i/awesome-japanese-nlp-resources](https://github.com/taishi-i/awesome-japanese-nlp-resources) ![stars](https://img.shields.io/github/stars/taishi-i/awesome-japanese-nlp-resources?style=social) - Japanese NLP libraries, LLMs, dictionaries, corpora, and datasets.

## AI agents & frameworks

- [OpenOSINT/OpenOSINT](https://github.com/OpenOSINT/OpenOSINT) ![stars](https://img.shields.io/github/stars/OpenOSINT/OpenOSINT?style=social) - AI-powered OSINT agent with REPL, MCP server, and CLI; works with hosted or local models. Authorized research only.
- [7onez/cti-expert](https://github.com/7onez/cti-expert) ![stars](https://img.shields.io/github/stars/7onez/cti-expert?style=social) - Cyber threat intelligence and OSINT analysis skill for Claude Code / Codex with a deterministic case pipeline.
- [ThreatRecall/zettelforge](https://github.com/ThreatRecall/zettelforge) ![stars](https://img.shields.io/github/stars/ThreatRecall/zettelforge?style=social) - Agentic memory for CTI: STIX knowledge graphs, offline-first RAG, MCP server.

## MCP servers

- [marc-shade/world-intel-mcp](https://github.com/marc-shade/world-intel-mcp) ![stars](https://img.shields.io/github/stars/marc-shade/world-intel-mcp?style=social) - 120-tool MCP server for real-time global intelligence with cited situation briefs and geofences.
- [damionrashford/RivalSearchMCP](https://github.com/damionrashford/RivalSearchMCP) ![stars](https://img.shields.io/github/stars/damionrashford/RivalSearchMCP?style=social) - Research MCP server: multi-engine web search, social search, academic DBs, entity profiles. No API keys.

## Situational awareness & GEOINT

- [koala73/worldmonitor](https://github.com/koala73/worldmonitor) ![stars](https://img.shields.io/github/stars/koala73/worldmonitor?style=social) - Real-time global intelligence dashboard: AI news aggregation, geopolitical and infrastructure monitoring.
- [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) ![stars](https://img.shields.io/github/stars/bilawalsidhu/gods-eye-view?style=social) - Browser-based 3D globe with live open spatial-intelligence data (satellites, flights).

## Local LLM for private analysis

Running models on your own machine keeps sensitive investigation material (documents, notes, case files) off third-party servers. Pair these with the agents above.

- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) ![stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=social) - LLM inference in C/C++; the foundation of many local tools.
- [ollama/ollama](https://github.com/ollama/ollama) ![stars](https://img.shields.io/github/stars/ollama/ollama?style=social) - Get up and running with open-weight models locally.
- [vllm-project/vllm](https://github.com/vllm-project/vllm) ![stars](https://img.shields.io/github/stars/vllm-project/vllm?style=social) - High-throughput, memory-efficient inference and serving engine (GPU servers).
- [open-webui/open-webui](https://github.com/open-webui/open-webui) ![stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social) - Self-hosted AI interface supporting Ollama and OpenAI-compatible APIs, with RAG.
- [janhq/jan](https://github.com/janhq/jan) ![stars](https://img.shields.io/github/stars/janhq/jan?style=social) - Open-source ChatGPT alternative that runs 100% offline.
- [mozilla-ai/llamafile](https://github.com/mozilla-ai/llamafile) ![stars](https://img.shields.io/github/stars/mozilla-ai/llamafile?style=social) - Distribute and run LLMs as a single file.
- [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) ![stars](https://img.shields.io/github/stars/zylon-ai/private-gpt?style=social) - API layer for private AI apps on local models: RAG, tools, MCP.

## Japan-focused public sources

Official Japanese open data and registries that are useful for lawful research and due diligence. These are web services (not GitHub repos); many offer APIs or bulk downloads, so they combine well with the local LLM and agent tools above. Check each site's terms of use and attribution rules.

### Geospatial (GEOINT)

- [GSI Maps (地理院地図)](https://maps.gsi.go.jp/) - Geospatial Information Authority of Japan (GSI) web map: topographic maps, aerial photos (including multi-era comparisons and prewar Tokyo imagery), terrain, hazard layers, and 1,800+ selectable layers.
- [GSI portal](https://www.gsi.go.jp/) - Entry point to GSI services such as the map and aerial photo viewing service and the Fundamental Geospatial Data / DEM downloads (the latter require user registration).

### Official gazette & legal

- [Kanpō (官報) official guidance](https://www.cao.go.jp/others/soumu/kanpo/) - Cabinet Office page. Since April 1, 2025 the gazette is published digitally on the "Kanpō publication site" (官報発行サイト, https://www.kanpo.go.jp/), whose electronic data is the official original. The former Internet Kanpō (インターネット版官報) ended on March 31, 2025; past issues remain available on the new site. Some notices contain personal information; do not compile or republish it as a list of individuals.
- [NDL Digital Collections (国立国会図書館デジタルコレクション)](https://dl.ndl.go.jp/) - Historical gazettes and other digitized materials from the National Diet Library.

### Corporate & company data

- [National Tax Agency Corporate Number Publication Site (法人番号公表サイト)](https://www.houjin-bangou.nta.go.jp/) - Search and bulk download of corporate numbers, names, and head-office addresses for corporations in Japan; Web-API available.
- [gBizINFO](https://info.gbiz.go.jp/) - METI service linking government-held corporate data by corporate number: subsidies, certifications, patents, procurement, financials, workplace info; REST API available.
- [EDINET](https://disclosure2.edinet-fsa.go.jp/) - Financial Services Agency disclosure system for securities reports of listed and large companies.
- [e-Stat (政府統計の総合窓口)](https://www.e-stat.go.jp/) - Japanese government statistics portal with API access.

## Classic OSINT tools (building blocks)

Many AI agents above wrap these.

- [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) ![stars](https://img.shields.io/github/stars/sherlock-project/sherlock?style=social) - Find social media accounts by username.
- [soxoj/maigret](https://github.com/soxoj/maigret) ![stars](https://img.shields.io/github/stars/soxoj/maigret?style=social) - Collect a username-based profile from thousands of sites.
- [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) ![stars](https://img.shields.io/github/stars/smicallef/spiderfoot?style=social) - Automated OSINT for threat intelligence and attack-surface mapping.
- [laramies/theHarvester](https://github.com/laramies/theHarvester) ![stars](https://img.shields.io/github/stars/laramies/theHarvester?style=social) - Emails, subdomains, and names harvesting.
- [lissy93/web-check](https://github.com/lissy93/web-check) ![stars](https://img.shields.io/github/stars/lissy93/web-check?style=social) - All-in-one website analysis.
- [gildas-lormeau/SingleFile](https://github.com/gildas-lormeau/SingleFile) ![stars](https://img.shields.io/github/stars/gildas-lormeau/SingleFile?style=social) - Save a faithful single-file copy of a web page (evidence preservation).

## Contributing

Add entries via pull request: one line per tool, alphabetical within a section, with a short factual description. Offensive-only or privacy-invasive tools targeting individuals will not be accepted.

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

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
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
