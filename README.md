![](asserts/logo1.png)

# Awesome MCP Servers with stars

[![Powered by DartNode](https://dartnode.com/branding/DN-Open-Source-sm.png)](https://dartnode.com "Powered by DartNode - Free VPS for Open Source")

A curated, community-driven list of awesome Model Context Protocol (MCP) servers, tools, frameworks, clients, and utilities. MCP is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations.

***

BTW, we provide a [full list of MCP (Master Control Program) Servers](https://github.com/YuzeHao2023/Awesome-MCP-Servers/blob/main/Full-List-of-MCP-Servers.xlsx) ⭐ 1,057 | 🐛 258 | 📅 2026-08-07, which is compiled by a web crawler and contains approximately 6000 entries.

***

## All Documents

> Call for translators! [We're looking for translators](https://github.com/YuzeHao2023/Awesome-MCP-Servers/issues/1) ⭐ 1,057 | 🐛 258 | 📅 2026-08-07 to help translate this spec for everyone!

**Read our documentation in the following languages:**

| Language | Link                                                                                                                    |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| English  | [English](https://github.com/YuzeHao2023/Awesome-MCP-Servers?tab=readme-ov-file) ⭐ 1,057 \| 🐛 258 \| 📅 2026-08-07     |
| 简体中文     | [简体中文](https://github.com/YuzeHao2023/Awesome-MCP-Servers/blob/main/README_zh_CN.md) ⭐ 1,057 \| 🐛 258 \| 📅 2026-08-07 |
| 繁體中文     | [繁體中文](https://github.com/YuzeHao2023/Awesome-MCP-Servers/blob/main/README_zh_TW.md) ⭐ 1,057 \| 🐛 258 \| 📅 2026-08-07 |
| 日本語      | [日本語](https://github.com/YuzeHao2023/Awesome-MCP-Servers/blob/main/README_ja.md) ⭐ 1,057 \| 🐛 258 \| 📅 2026-08-07     |
| 한국어      | [한국어](https://github.com/YuzeHao2023/Awesome-MCP-Servers/blob/main/README_ko.md) ⭐ 1,057 \| 🐛 258 \| 📅 2026-08-07     |

***

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access,  database connections, API integrations, and other contextual services.

***

# Contents

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

***

## ⚠️ Security Warning

When running MCP servers without proper sandboxing, they can execute arbitrary code on your system with the same permissions as the host process. This creates significant security risks.

Warning summary:

* System Access: Full access to files, network, and system resources
* Code Execution: Can run commands on your machine
* Prompt Injection: Malicious prompts could trigger unintended server actions
* Data Exposure: Sensitive data may be accessed or leaked

Best practices:

* Use official implementations (marked with ⭐) when available
* Run servers in VMs or isolated containers
* Review code and configuration before installation
* Limit permissions to the minimum required
* Monitor server activity and logs

***

## Examples of Supported Clients

Many MCP clients and UIs can connect to servers listed here. Examples include (but are not limited to):

* Claude Desktop / Claude clients
* Zed
* Sourcegraph Cody
* Cursor
* Visual Studio Code
* LibreChat
* Various CLI and browser-based clients

(Icons and links for specific clients are commonly shown on the individual server/project pages.)

***

## Server Implementations (Categories)

* 📂 File Systems
* 📦 Sandbox & Virtualization
* 🔄 Version Control
* ☁️ Cloud Storage
* 🗄️ Databases
* 💬 Communication
* 📈 Monitoring
* 🔍 Search & Web
* 🗺️ Location Services
* 🎯 Marketing
* 📝 Note Taking
* ⚡ Cloud Platforms
* ⚙️ Workflow Automation
* 🤖 System Automation
* 📱 Social Media
* 🎮 Gaming
* 💹 Finance
* 🧬 Research & Data
* 🤝 AI Services
* 💻 Development Tools
* 📊 Data Visualization
* 🆔 Identity
* 🔗 Aggregators
* 💬 Language & Translation
* 🔒 Security
* 🔌 IoT
* 🧑‍🎨 Art & Literature
* 🛒 E-Commerce
* 📦 Data Platforms
* 🤖 Robotics & Physical AI

Legend:

* ⭐ Official protocol implementation
* 1,2,3,... Implementation ordering when multiple exist

***

# Reference Servers

These are example/reference servers and core SDK examples demonstrating MCP features.

* Everything (Reference / test server with prompts, resources, and tools)
  * <https://github.com/modelcontextprotocol/servers/blob/main/src/everything> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Fetch
  * <https://github.com/modelcontextprotocol/servers/tree/main/src/fetch> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Filesystem
  * <https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Git
  * <https://github.com/modelcontextprotocol/servers/tree/main/src/git> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Memory
  * <https://github.com/modelcontextprotocol/servers/tree/main/src/memory> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Sequential Thinking
  * <https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Time
  * <https://github.com/modelcontextprotocol/servers/blob/main/src/time> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10

***

# Official Servers

Official integrations are maintained by companies building production-ready MCP servers for their platforms. (Marked with ⭐ when present)

* GitHub — <https://github.com/github/github-mcp-server> ⭐ 32,310 | 🐛 379 | 🌐 Go | 📅 2026-08-17 (official)
* 21st.dev Magic — <https://github.com/21st-dev/magic-mcp> ⭐ 5,684 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-31
* Notion — <https://github.com/makenotion/notion-mcp> ⭐ 4,592 | 🐛 185 | 🌐 TypeScript | 📅 2026-07-25 (official)
* Cloudflare — <https://github.com/cloudflare/mcp-server-cloudflare> ⭐ 4,085 | 🐛 57 | 🌐 TypeScript | 📅 2026-08-11 (⭐)
* Apify Actors — <https://github.com/apify/actors-mcp-server> ⭐ 3,988 | 🐛 138 | 🌐 TypeScript | 📅 2026-08-17
* Stripe — <https://github.com/stripe/agent-toolkit/tree/main> ⭐ 1,748 | 🐛 77 | 🌐 TypeScript | 📅 2026-08-15 (⭐)
* PayPal — <https://github.com/paypal/agent-toolkit/tree/main> ⭐ 190 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-10 (⭐)
* AgentQL — <https://github.com/tinyfish-io/agentql-mcp> ⭐ 177 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-17
* AlibabaCloud DevOps MCP — <https://github.com/aliyun/alibabacloud-devops-mcp-server> ⭐ 153 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-17
* AgentRPC — <https://github.com/agentrpc/agentrpc> ⭐ 134 | 🐛 22 | 🌐 TypeScript | 📅 2026-06-22
* Box — <https://github.com/box-community/mcp-server-box> ⚠️ Archived (⭐)
* Tinybird — <https://github.com/tinybirdco/mcp-tinybird> ⚠️ Archived (⭐)
* 1mcpserver — <https://github.com/particlefuture/1mcpserver> ⭐ 53 | 🐛 2 | 🌐 Python | 📅 2025-12-31
* Aiven — <https://github.com/Aiven-Open/mcp-aiven> ⭐ 26 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-11
* Adfin — <https://github.com/Adfin-Engineering/mcp-server-adfin> ⭐ 11 | 🐛 3 | 🌐 Python | 📅 2025-03-20
* 4everland/4everland-hosting-mcp — <https://github.com/4everland/4everland-hosting-mcp> ⭐ 2 | 🐛 3 | 🌐 TypeScript | 📅 2025-06-19
* Agent Mindshare — <https://agentmindshare.com>
* Cloud-run, AWS, Azure, Google offerings — various official MCP servers in the awslabs and Google repos under modelcontextprotocol.

(For a full list of official servers and vendor-maintained implementations, see the "Official Servers" and "Reference Servers" in this document and the linked repos.)

***

# Tools & Utilities

Helpful utilities to discover, install, manage, and work with MCP servers.

Server Managers:

* ToolHive — Lightweight utility to simplify deployment & management — <https://github.com/StacklokLabs/toolhive> ⭐ 2,022 | 🐛 384 | 🌐 Go | 📅 2026-08-17
* MCP Installer — <https://github.com/anaisbetts/mcp-installer> ⭐ 1,529 | 🐛 22 | 🌐 JavaScript | 📅 2024-11-26
* mcp-get — CLI tool to install and manage MCP servers (Claude Desktop oriented) — <https://github.com/michaellatman/mcp-get> ⚠️ Archived
* Remote MCP — Solution for remote MCP communication — <https://github.com/ssut/Remote-MCP> ⭐ 209 | 🐛 6 | 🌐 TypeScript | 📅 2025-03-27
* mxcp — An open-source framework for building secure enterprise MCP tools — <http://github.com/raw-labs/mxcp> ⭐ 70 | 🐛 45 | 🌐 Python | 📅 2026-06-30
* yamcp — Model Context Workspace Manager — <https://github.com/hamidra/yamcp> ⭐ 66 | 🐛 4 | 🌐 TypeScript | 📅 2025-05-27

Other utilities:

* mcp-cli — CLI inspector for MCP servers — <https://github.com/wong2/mcp-cli> ⭐ 443 | 🐛 11 | 🌐 JavaScript | 📅 2026-06-08
* Secure Fetch — secure fetch to prevent access to local resources — <https://github.com/appsec-innovation-labs/secure-mcp-fetch> ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-04-25
* mcp-get, mcp-installer, and similar utilities to simplify installation and discovery.

***

## Category: File Systems (📂)

Provides access to local or remote file systems with configurable permissions.

* FileSystem (modelcontextprotocol reference) — <https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10 (1)
* FileStash — <https://github.com/mickael-kerjean/filestash/tree/master/server/plugin/plg_handler_mcp> ⭐ 14,497 | 🐛 122 | 🌐 Go | 📅 2026-08-17
* FileSystem (mark3labs) — <https://github.com/mark3labs/mcp-filesystem-server> ⭐ 678 | 🐛 25 | 🌐 Go | 📅 2025-11-24 (2)
* Everything Search — <https://github.com/mamertofabian/mcp-everything-search> ⭐ 356 | 🐛 24 | 🌐 Python | 📅 2025-10-20
* llm-context — <https://github.com/cyberchitta/llm-context.py> ⭐ 306 | 🐛 5 | 🌐 Python | 📅 2026-08-02
* fast-filesystem-mcp — <https://github.com/efforthye/fast-filesystem-mcp> ⭐ 59 | 🐛 9 | 🌐 TypeScript | 📅 2026-05-23
* Backup — <https://github.com/hexitex/MCP-Backup-Server> ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-08

***

## Category: Sandbox & Virtualization (📦)

Secure sandbox environments for code execution.

* Microsandbox (⭐) — <https://github.com/microsandbox/microsandbox> ⭐ 7,570 | 🐛 77 | 🌐 Rust | 📅 2026-08-17
* Docker (QuantGeekDev) — <https://github.com/QuantGeekDev/docker-mcp> ⭐ 499 | 🐛 13 | 🌐 Python | 📅 2024-12-14
* E2B (⭐) — <https://github.com/e2b-dev/mcp-server> ⚠️ Archived

***

## Category: Version Control (🔄)

Git and version control related MCP servers.

* GitLab — <https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Git (direct) — <https://github.com/modelcontextprotocol/servers/tree/main/src/git> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* GitHub (1) — <https://github.com/github/github-mcp-server> ⭐ 32,310 | 🐛 379 | 🌐 Go | 📅 2026-08-17 (official)
* Gitingest-MCP — <https://github.com/puravparab/Gitingest-MCP> ⭐ 136 | 🐛 3 | 🌐 Python | 📅 2025-03-21
* GitHub Repos Manager — <https://github.com/kurdin/github-repos-manager-mcp> ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-25
* Phabricator — <https://github.com/baba786/phabricator-mcp-server>

***

## Category: Cloud Storage (☁️)

Access to cloud storage platforms.

* Google Drive — <https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Microsoft 365 — <https://github.com/softeria/ms-365-mcp-server> ⭐ 914 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-13
* VideoDB (agent-toolkit) — <https://github.com/video-db/agent-toolkit/tree/main/modelcontextprotocol> ⭐ 47 | 🐛 7 | 🌐 Python | 📅 2026-03-26 (⭐)
* Box (⭐) — <https://developer.box.com/guides/box-mcp/>

***

## Category: Databases (🗄️)

Database access with schema inspection and query capabilities.

* PostgreSQL — <https://github.com/modelcontextprotocol/servers/tree/main/src/postgres> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* SQLite — <https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Excel — <https://github.com/haris-musa/excel-mcp-server> ⭐ 4,113 | 🐛 69 | 🌐 Python | 📅 2026-04-12
* Qdrant (⭐) — <https://github.com/qdrant/mcp-server-qdrant/> ⭐ 1,503 | 🐛 72 | 🌐 Python | 📅 2026-08-14
* MySQL — <https://github.com/designcomputer/mysql_mcp_server> ⭐ 1,360 | 🐛 1 | 🌐 Python | 📅 2026-08-02
* Neon (⭐) — <https://github.com/neondatabase/mcp-server-neon> ⭐ 624 | 🐛 32 | 🌐 TypeScript | 📅 2026-08-17
* Redis (⭐) — <https://github.com/redis/mcp-redis> ⭐ 576 | 🐛 15 | 🌐 Python | 📅 2026-08-05
* Airtable — <https://github.com/domdomegg/airtable-mcp-server> ⭐ 455 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-11
* MongoDB — <https://github.com/kiliczsh/mcp-mongo-server> ⭐ 283 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-29
* MongoDB Lens — <https://github.com/furey/mongodb-lens> ⭐ 205 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-23
* Snowflake — <https://github.com/isaacwasserman/mcp-snowflake-server> ⭐ 185 | 🐛 14 | 🌐 Python | 📅 2025-10-07
* DuckDB — <https://github.com/ktanaka101/mcp-server-duckdb> ⭐ 178 | 🐛 6 | 🌐 Python | 📅 2025-05-05
* BigQuery — <https://github.com/LucasHild/mcp-server-bigquery> ⭐ 128 | 🐛 12 | 🌐 Python | 📅 2026-03-26 (1) & <https://github.com/ergut/mcp-bigquery-server> ⭐ 146 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-22 (2)
* DBUtils — <https://github.com/donghao1393/mcp-dbutils> ⭐ 90 | 🐛 14 | 🌐 Python | 📅 2025-05-12
* NocoDB — <https://github.com/edwinbernadus/nocodb-mcp-server> ⭐ 75 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-30
* Couchbase (⭐) — <https://github.com/Couchbase-Ecosystem/mcp-server-couchbase> ⭐ 34 | 🐛 3 | 🌐 Python | 📅 2026-08-17
* TiDB — <https://github.com/c4pt0r/mcp-server-tidb> ⭐ 24 | 🐛 5 | 🌐 Python | 📅 2025-04-15
* Many other DB-specific servers are listed in Community Servers.

***

## Category: Communication (💬)

Integration with chat and messaging platforms.

* Atlassian — <https://github.com/sooperset/mcp-atlassian> ⭐ 5,753 | 🐛 186 | 🌐 Python | 📅 2026-08-17
* Slack — <https://github.com/korotovsky/slack-mcp-server> ⭐ 1,783 | 🐛 60 | 🌐 Go | 📅 2026-07-16
* LINE Official Account (⭐) — <https://github.com/line/line-bot-mcp-server> ⭐ 766 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-17
* Linear — <https://github.com/jerhadf/linear-mcp-server> ⭐ 347 | 🐛 20 | 🌐 JavaScript | 📅 2025-05-01
* ntfy — <https://github.com/gitmotion/ntfy-me-mcp> ⭐ 72 | 🐛 2 | 🌐 TypeScript | 📅 2026-04-11
* Carbon Voice (⭐) — <https://github.com/PhononX/cv-mcp-server> ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27

***

## Category: Monitoring (📈)

Access observability and monitoring systems.

* Sentry — <https://github.com/modelcontextprotocol/servers/tree/main/src/sentry> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* VictoriaMetrics — <https://github.com/VictoriaMetrics-Community/mcp-victoriametrics> ⭐ 214 | 🐛 20 | 🌐 Go | 📅 2026-07-19
* Metoro — <https://github.com/metoro-io/metoro-mcp-server> ⭐ 51 | 🐛 3 | 🌐 Go | 📅 2026-06-02
* Raygun — <https://github.com/MindscapeHQ/mcp-server-raygun> ⭐ 22 | 🐛 3 | 📅 2026-03-02
* Signoz — <https://github.com/DrDroidLab/signoz-mcp-server> ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-03-04
* sslmon — <https://github.com/firesh/sslmon-mcp> ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-25

***

## Category: Search & Web (🔍)

Web fetching, scraping, and search.

* Puppeteer — <https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Brave Search — <https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Fetch — <https://github.com/modelcontextprotocol/servers/tree/main/src/fetch> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* Playwright — <https://github.com/executeautomation/mcp-playwright> ⭐ 5,632 | 🐛 32 | 🌐 TypeScript | 📅 2025-12-13
* Exa Search (⭐) — <https://github.com/exa-labs/exa-mcp-server> ⭐ 4,879 | 🐛 32 | 🌐 TypeScript | 📅 2026-08-17
* Apify Actors & RAG Web Browser — <https://github.com/apify/actors-mcp-server> ⭐ 3,988 | 🐛 138 | 🌐 TypeScript | 📅 2026-08-17 and <https://github.com/apify/mcp-server-rag-web-browser> ⚠️ Archived
* ArXiv — <https://github.com/blazickjp/arxiv-mcp-server> ⭐ 3,063 | 🐛 17 | 🌐 Python | 📅 2026-08-14
* Bright Data — <https://github.com/luminati-io/brightdata-mcp> ⭐ 2,594 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-12
* Search1API — <https://github.com/fatwang2/search1api-mcp> ⭐ 173 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11
* Scrapeless — <https://github.com/scrapeless-ai/scrapeless-mcp-server> ⭐ 168 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-23
* Google News — <https://github.com/ChanMeng666/server-google-news> ⭐ 126 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-08
* RivalSearchMCP — <https://github.com/damionrashford/RivalSearchMCP> ⭐ 121 | 🐛 10 | 🌐 Python | 📅 2026-08-16
* Tavily — <https://github.com/Tomatio13/mcp-server-tavily> ⭐ 50 | 🐛 1 | 🌐 Python | 📅 2025-08-19
* Kagi Search — <https://github.com/ac3xx/mcp-servers-kagi> ⭐ 45 | 🐛 5 | 🌐 TypeScript | 📅 2024-12-13
* Websearch (SearXNG) — <https://github.com/mnhlt/WebSearch-MCP> ⭐ 40 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-30 and <https://github.com/ihor-sokoliuk/mcp-searxng> ⭐ 1,141 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-17
* Dumpling AI — <https://github.com/Dumpling-AI/mcp-server-dumplingai> ⭐ 31 | 🐛 7 | 🌐 JavaScript | 📅 2025-07-10
* PapersWithCode — <https://github.com/hbg/mcp-paperswithcode> ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2025-06-07
* NYTimes — <https://github.com/angheljf/nyt> ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-23
* Coupang MCP — <https://github.com/uju777/coupang-mcp> ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2026-04-13 - Korean e-commerce search with Rocket Delivery filtering
* Naver Search MCP — <https://github.com/uju777/mcp-server-naver-search> ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-12 - Naver Shopping, Cafe, News search for Korean users
* Scrapeless and many web-scraping-focused MCP servers are listed in Community Servers.

***

## Category: Location Services (🗺️)

Mapping and geolocation.

* Google Maps — <https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps> ⭐ 89,638 | 🐛 518 | 🌐 TypeScript | 📅 2026-08-10
* QGIS — <https://github.com/jjsantos01/qgis_mcp> ⭐ 1,061 | 🐛 16 | 🌐 Python | 📅 2025-10-01
* IPLocate — <https://github.com/iplocate/mcp-server-iplocate> ⭐ 19 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-29
* Campertunity — <https://github.com/campertunity/mcp-server> ⭐ 16 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-15
* IP2Location.io — <https://github.com/ip2location/mcp-ip2location-io> ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2026-05-26

***

## Category: Marketing (🎯)

Marketing and analytics tools.

* Facebook Ads — <https://github.com/gomarble-ai/facebook-ads-mcp-server> ⭐ 353 | 🐛 4 | 🌐 Python | 📅 2026-08-05
* Google Ads — <https://github.com/gomarble-ai/google-ads-mcp-server> ⭐ 143 | 🐛 2 | 🌐 Python | 📅 2026-08-05
* Fathom Analytics — <https://github.com/mackenly/mcp-fathom-analytics> ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-17
* Agent Mindshare — <https://agentmindshare.com>
* Open Strategy Partners Marketing Tools — <https://github.com/open-strategy-partners/osp_mark>

***

## Category: Note Taking (📝)

Personal knowledge and notes integrations.

* Obsidian (1/2) — <https://github.com/MarkusPfundstein/mcp-obsidian> ⭐ 4,310 | 🐛 101 | 🌐 Python | 📅 2026-05-15 and <https://github.com/calclavia/mcp-obsidian>
* Todoist — <https://github.com/abhiz123/todoist-mcp-server> ⭐ 392 | 🐛 17 | 🌐 JavaScript | 📅 2025-04-20
* eBook-mcp — <https://github.com/onebirdrocks/ebook-mcp> ⭐ 390 | 🐛 5 | 🌐 Python | 📅 2026-01-10
* Notion (1/2) — <https://github.com/danhilse/notion_mcp> ⭐ 207 | 🐛 5 | 🌐 Python | 📅 2024-12-18 and <https://github.com/suekou/mcp-notion-server> ⭐ 920 | 🐛 8 | 🌐 TypeScript | 📅 2026-07-31
* OMEGA — <https://github.com/omega-memory/core> ⭐ 204 | 🐛 7 | 🌐 Python | 📅 2026-08-16 (Persistent memory for AI coding agents. #1 on LongMemEval benchmark (95.4%). 12 MCP tools with semantic search, auto-capture, and intelligent forgetting. Local-first, zero cloud dependency.)
* Apple Notes — <https://github.com/sirmews/apple-notes-mcp> ⚠️ Archived (macOS)
* Google Keep — <https://github.com/feuerdev/keep-mcp> ⭐ 89 | 🐛 2 | 🌐 Python | 📅 2026-08-07
* Slite — <https://github.com/fajarmf/slite-mcp> ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-12

***

## Category: Cloud Platforms (⚡)

Cloud vendors and orchestration.

* Cloudflare (⭐) — <https://github.com/cloudflare/mcp-server-cloudflare> ⭐ 4,085 | 🐛 57 | 🌐 TypeScript | 📅 2026-08-11
* Google Cloud Run — <https://github.com/GoogleCloudPlatform/cloud-run-mcp> ⭐ 625 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-14
* Kubernetes (multiple implementations) — <https://github.com/strowk/mcp-k8s-go> ⭐ 386 | 🐛 11 | 🌐 Go | 📅 2025-12-22 (1), <https://github.com/weibaohui/k8m> ⭐ 871 | 🐛 25 | 🌐 Go | 📅 2026-08-14 (2), <https://github.com/StacklokLabs/mkp> ⭐ 59 | 🐛 12 | 🌐 Go | 📅 2026-08-17 (3)
* Tinybird (⭐) — <https://github.com/tinybirdco/mcp-tinybird> ⚠️ Archived
* Render — <https://render.com/docs/mcp-server>

***

## Category: Workflow Automation (⚙️)

Automation platforms and workflow tools.

* Pipedream — <https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol> ⭐ 11,627 | 🐛 4,300 | 🌐 JavaScript | 📅 2026-08-17
* Make (⭐) — <https://github.com/integromat/make-mcp-server> ⭐ 168 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-10
* Taskade (⭐) — <https://github.com/taskade/mcp> ⭐ 164 | 🐛 9 | 🌐 TypeScript | 📅 2026-07-29
* Make (2) — <https://github.com/danishashko/make-mcp> ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-14 — Unofficial community fork with 200+ modules, auto-healing, and router support
* Zapier — <https://zapier.com/mcp>
* Tool aggregators like Rube, Rube/Composio and MCPJungle are listed in Aggregators.

***

## Category: System Automation (🤖)

Shell, OS, and task automation.

* Shell (wcgw) — <https://github.com/rusiaaman/wcgw> ⭐ 673 | 🐛 3 | 🌐 Python | 📅 2026-08-07
* Apple Shortcuts — <https://github.com/recursechat/mcp-server-apple-shortcuts> ⭐ 342 | 🐛 6 | 🌐 JavaScript | 📅 2024-12-22
* Windows Control — <https://github.com/Cheffromspace/nutjs-windows-control> ⭐ 331 | 🐛 41 | 🌐 TypeScript | 📅 2025-12-02
* Command Line — <https://github.com/phialsbasement/cmd-mcp-server> ⭐ 25 | 🐛 3 | 🌐 JavaScript | 📅 2025-02-14
* Windows CLI — <https://github.com/SimonB97/win-cli-mcp>

***

## Category: Social Media (📱)

Social platforms integration.

* Spotify — <https://github.com/varunneal/spotify-mcp> ⭐ 612 | 🐛 27 | 🌐 Python | 📅 2026-03-11
* YouTube — <https://github.com/anaisbetts/mcp-youtube> ⭐ 541 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-16 and <https://github.com/kimtaeyoon83/mcp-server-youtube-transcript> ⭐ 582 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-21
* TikTok — <https://github.com/Seym0n/tiktok-mcp> ⭐ 191 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-27
* Instagram DMs — <https://github.com/trypeggy/instagram_dm_mcp> ⭐ 177 | 🐛 3 | 🌐 Python | 📅 2025-08-13
* BlueSky — <https://github.com/keturiosakys/bluesky-context-server> ⭐ 33 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-10
* X/Twitter — <https://github.com/mbelinky/x-mcp-server> ⭐ 21 | 🐛 5 | 🌐 TypeScript | 📅 2025-06-27
* Social Neuron (52 MCP tools for AI-powered social media content lifecycle — ideation, creation, distribution, analytics, and optimization with closed-loop learning) — <https://github.com/socialneuron/mcp-server> ⭐ 4 | 🐛 30 | 🌐 TypeScript | 📅 2026-08-12 \[npm: @socialneuron/mcp-server]

***

## Category: Gaming (🎮)

Game engines and tooling.

* Unity Engine (various) — <https://github.com/IvanMurzak/Unity-MCP> ⭐ 3,932 | 🐛 53 | 🌐 C# | 📅 2026-08-17, <https://github.com/CoderGamester/mcp-unity> ⭐ 1,866 | 🐛 3 | 🌐 C# | 📅 2026-08-10, <https://github.com/codemaestroai/advanced-unity-mcp> ⭐ 93 | 🐛 2 | 📅 2026-03-30

***

## Category: Finance (💹)

Payments, market data, and finance tools.

* Stripe (⭐) — <https://github.com/stripe/agent-toolkit> ⭐ 1,748 | 🐛 77 | 🌐 TypeScript | 📅 2026-08-15
* awesome-x402 (curated directory of x402 payment protocol MCP servers and tools) — <https://github.com/xpaysh/awesome-x402> ⭐ 279 | 🐛 288 | 📅 2026-07-28
* PayPal (⭐) — <https://github.com/paypal/agent-toolkit> ⭐ 190 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-10
* Octagon (⭐) — <https://github.com/OctagonAI/octagon-mcp-server> ⭐ 146 | 🐛 4 | 🌐 TypeScript | 📅 2026-07-09
* CoinMarket — <https://github.com/anjor/coinmarket-mcp-server> ⭐ 50 | 🐛 1 | 🌐 Python | 📅 2025-06-24
* Chargebee (⭐) — <https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol> ⚠️ Archived
* LongPort OpenAPI (⭐) — <https://github.com/longportapp/openapi/tree/main/mcp> ⭐ 7 | 🐛 4 | 🌐 Rust | 📅 2026-08-12
* AgentFund — <https://github.com/RioBot-Grind/agentfund-mcp> ⭐ 1 | 🐛 6 | 🌐 JavaScript | 📅 2026-02-03
* x402engine-mcp (50+ pay-per-call APIs for AI agents via HTTP 402 micropayments) — <https://github.com/agentc22/x402engine-mcp> ⭐ 0 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-25
* Omnis Venture Intelligence MCP — <https://github.com/HCS412/ventureautomated> (remote venture intelligence for autonomous agents: startup discovery, company scoring, monitoring, and enterprise workspace automation) [glama](https://glama.ai/mcp/connectors/io.github.HCS412/ventureautomated-omnis)
* DexPaprika (⭐) — <https://github.com/donbagger/dexpaprika-mcp-server>
* Mercado Pago — <https://mcp.mercadopago.com/>

***

## Category: Research & Data (🧬)

Papers, datasets, and domain data.

* ArXiv — <https://github.com/blazickjp/arxiv-mcp-server> ⭐ 3,063 | 🐛 17 | 🌐 Python | 📅 2026-08-14
* OpenNutrition — <https://github.com/deadletterq/mcp-opennutrition> ⭐ 200 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28
* Ancestry — <https://github.com/reeeeemo/ancestry-mcp> ⚠️ Archived
* Congress (legislative data) — <https://github.com/amurshak/congressMCP> ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2026-08-06
* Probe.dev — <https://mcp.probe.dev>

***

## Category: AI Services (🤝)

AI model & ML service integrations.

* HuggingFace Spaces — <https://github.com/evalstate/mcp-hfspace> ⭐ 388 | 🐛 12 | 🌐 TypeScript | 📅 2025-06-13
* OpenAI Compatible Chat — <https://github.com/pyroprompts/any-chat-completions-mcp> ⭐ 155 | 🐛 8 | 🌐 JavaScript | 📅 2025-05-01
* NeuroLink — <https://github.com/juspay/neurolink> ⭐ 121 | 🐛 65 | 🌐 TypeScript | 📅 2026-08-17
* Chronulus AI — <https://github.com/ChronulusAI/chronulus-mcp> ⭐ 110 | 🐛 3 | 🌐 Python | 📅 2025-07-19
* Perplexity — <https://github.com/tanigami/mcp-server-perplexity> ⭐ 94 | 🐛 3 | 🌐 Python | 📅 2024-12-25
* LlamaCloud — <https://github.com/run-llama/mcp-server-llamacloud> ⚠️ Archived
* OpenAI — <https://github.com/pierrebrunelle/mcp-server-openai> ⭐ 84 | 🐛 6 | 🌐 Python | 📅 2024-11-28
* PiAPI — <https://github.com/apinetwork/piapi-mcp-server> ⭐ 73 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-10
* ZenML (⭐) — <https://github.com/zenml-io/mcp-zenml> ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2026-08-04
* Agentset AI — <https://github.com/agentset-ai/mcp-server> ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-16
* Creatify — <https://github.com/TSavo/creatify-mcp> ⭐ 22 | 🐛 3 | 🌐 TypeScript | 📅 2025-05-26

***

## Category: Development Tools (💻)

Developer-focused MCP servers and tools.

* Mastra/mcp (⭐) — <https://github.com/mastra-ai/mastra/tree/main/packages/mcp> ⭐ 27,251 | 🐛 476 | 🌐 TypeScript | 📅 2026-08-17
* Figma — <https://github.com/GLips/Figma-Context-MCP> ⭐ 15,670 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-07
* Octocode — <https://github.com/bgauryy/octocode-mcp> ⭐ 913 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-12
* CentralMind/Gateway — <https://github.com/centralmind/gateway> ⭐ 544 | 🐛 15 | 🌐 Go | 📅 2025-07-18
* flutter-skill — <https://github.com/ai-dashboad/flutter-skill> ⭐ 352 | 🐛 11 | 🌐 Dart | 📅 2026-07-23 — AI-powered E2E testing bridge for any app. Supports Flutter, iOS, Android, Web, Electron, Tauri, KMP, React Native, .NET MAUI.
* VSCode Devtools — <https://github.com/biegehydra/BifrostMCP> ⭐ 224 | 🐛 8 | 🌐 TypeScript | 📅 2026-03-27
* Comet Opik (⭐) — <https://github.com/comet-ml/opik-mcp> ⭐ 218 | 🐛 34 | 🌐 Python | 📅 2026-08-14
* DefangLabs/defang — <https://github.com/DefangLabs/defang> ⭐ 163 | 🐛 212 | 🌐 Go | 📅 2026-08-17
* Postman — <https://github.com/delano/postman-mcp-server> ⭐ 159 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-11
* marimo (⭐) — <https://github.com/marimo-team/codemirror-mcp> ⭐ 79 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28
* OpenAPI Schema Explorer — <https://github.com/kadykov/mcp-openapi-schema-explorer> ⭐ 77 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-17
* Bucket — <https://github.com/bucketco/bucket-javascript-sdk/tree/main/packages/cli#model-context-protocol> ⭐ 25 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-16
* QA Sphere (⭐) — <https://github.com/Hypersequent/qasphere-mcp> ⭐ 23 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-21
* Currents (⭐) — <https://github.com/currents-dev/currents-mcp> ⭐ 19 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-17
* HendryAvila/Hoofy — <https://github.com/HendryAvila/Hoofy> ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2026-03-12 — Spec-driven development companion with persistent memory (SQLite + FTS5 + knowledge graph), adaptive change pipeline (12 flow variants), greenfield project pipeline with Clarity Gate, and business rules extraction. 32 MCP tools. Single Go binary.
* jarp-mcp — <https://github.com/tersePrompts/jarp-mcp> ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-01-30
* OpenRPC — <https://github.com/shanejonas/openrpc>
* many others in Community Servers and Official Servers

***

## Category: Data Visualization (📊)

Charting and diagram tools.

* Chart (AntV) — <https://github.com/antvis/mcp-server-chart> ⭐ 4,319 | 🐛 16 | 🌐 TypeScript | 📅 2026-05-06
* Mermaid — <https://github.com/hustcc/mcp-mermaid> ⭐ 627 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-15
* ECharts — <https://github.com/hustcc/mcp-echarts> ⭐ 260 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-30
* VegaLite — <https://github.com/isaacwasserman/mcp-vegalite-server> ⭐ 100 | 🐛 7 | 🌐 Python | 📅 2025-05-16
* unified-diff-mcp — <https://github.com/gorosun/unified-diff-mcp> ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-02

***

## Category: Identity (🆔)

Identity and access management.

* Keycloak — <https://github.com/ChristophEnglisch/keycloak-model-context-protocol> ⭐ 46 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-09

***

## Category: Aggregators (🔗)

Single MCP endpoints that expose many integrations.

* Pipedream — <https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol> ⭐ 11,627 | 🐛 4,300 | 🌐 JavaScript | 📅 2026-08-17
* MCPJungle — <https://github.com/mcpjungle/MCPJungle> ⭐ 1,211 | 🐛 94 | 🌐 Go | 📅 2026-08-02
* Magg — <https://github.com/sitbon/magg> ⭐ 142 | 🐛 7 | 🌐 Python | 📅 2026-08-02
* Plugged.in — <https://github.com/VeriTeknik/pluggedin-mcp-proxy> ⭐ 134 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-10
* MCP Aggregator / Combine — <https://github.com/nazar256/combine-mcp> ⭐ 34 | 🐛 2 | 🌐 Go | 📅 2025-11-24
* SkillBoss — <https://github.com/heeyo-life/skillboss-mcp> ⚠️ Archived — One API key for 100+ AI services (Claude, GPT, Gemini, DeepSeek, images, video, data scraping, payments, email, and more). OpenAI-compatible. Works in Claude Code, Cursor, Windsurf.
* Rube — <https://rube.composio.dev>
* Zapier — <https://zapier.com/mcp>

***

## Category: Language & Translation (💬)

Translation and language services.

* Lara (⭐) — <https://github.com/translated/lara-mcp> ⭐ 96 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-11

***

## Category: Security (🔒)

Security-focused servers and scanning tools.

* Semgrep — <https://github.com/semgrep/mcp> ⚠️ Archived
* Agent OS — <https://github.com/imran-siddique/agent-os> ⚠️ Archived — Kernel-level governance MCP server for AI agents — enforces deterministic policies (tool filtering, budget caps, rate limits, audit logging) instead of prompt-based guardrails. Part of microsoft/agent-lightning (14k★). Run via `npx agentos-mcp-server`.
* OSV — <https://github.com/StacklokLabs/osv-mcp> ⭐ 38 | 🐛 21 | 🌐 Go | 📅 2026-08-13
* Netwrix (⭐) — <https://github.com/netwrix/mcp-server-naa> ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2025-07-15
* Microsoft Entra ID — Microsoft-related MCPs for identity
* Vulert — <https://vulert.com>
* Thales / CDSP servers — various MCP integrations for secrets & keys

***

## Category: IoT (🔌)

MCP servers for device and IoT integration.

* Coreflux MQTT — <https://github.com/CorefluxCommunity/CorefluxMCPServer> ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-08-01

***

## Category: Art & Literature (🧑‍🎨)

Books, libraries, and creative tools.

* MCP Open Library — <https://github.com/8enSmith/mcp-open-library> ⭐ 88 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-14
* Pollinations — <https://github.com/pollinations/model-context-protocol>

***

## Category: E-Commerce (🛒)

Commerce and marketplace integrations.

* ShopSavvy (⭐) — <https://github.com/shopsavvy/shopsavvy-mcp-server> ⭐ 8 | 🐛 2 | 🌐 JavaScript | 📅 2026-04-04
* Gunsnation — <https://github.com/DynamicDeals/mcp-server-gunsnation> ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23
* Mercado Libre — <https://mcp.mercadolibre.com/>

***

## Category: Data Platforms (📦)

Orchestration and data pipeline platforms.

* Keboola (⭐) — <https://github.com/keboola/keboola-mcp-server> ⭐ 86 | 🐛 38 | 🌐 Python | 📅 2026-08-17

***

## Category: Robotics & Physical AI (🤖)

Robotics and device control.

* Bagel — <https://github.com/Extelligence-ai/bagel> ⭐ 390 | 🐛 26 | 🌐 Python | 📅 2026-08-16

***

# Community Servers

A broad collection of community-maintained MCP servers (selected highlights — many more are available in the ecosystem):

* bytebase/dbhub — <https://github.com/bytebase/dbhub> ⭐ 3,369 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-15
* Android MCP — <https://github.com/minhalvp/android-mcp-server> ⭐ 800 | 🐛 7 | 🌐 Python | 📅 2025-05-28
* Airtable — <https://github.com/domdomegg/airtable-mcp-server> ⭐ 455 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-11
* Binary Ninja integration — <https://github.com/fosdickio/binary_ninja_mcp> ⭐ 421 | 🐛 33 | 🌐 Python | 📅 2026-04-05
* Apple Notes — <https://github.com/RafalWilinski/mcp-apple-notes> ⭐ 411 | 🐛 21 | 🌐 TypeScript | 📅 2024-12-17
* BloodHound-MCP — <https://github.com/MorDavid/BloodHound-MCP-AI> ⭐ 374 | 🐛 0 | 🌐 Python | 📅 2025-06-02
* Apple Shortcuts — <https://github.com/recursechat/mcp-server-apple-shortcuts> ⭐ 342 | 🐛 6 | 🌐 JavaScript | 📅 2024-12-22
* Calculator — <https://github.com/githejie/mcp-server-calculator> ⭐ 155 | 🐛 7 | 🌐 Python | 📅 2026-08-08
* BigQuery servers — <https://github.com/LucasHild/mcp-server-bigquery> ⭐ 128 | 🐛 12 | 🌐 Python | 📅 2026-03-26 and <https://github.com/ergut/mcp-bigquery-server> ⭐ 146 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-22
* CalDAV MCP — <https://github.com/dominik1001/caldav-mcp> ⭐ 97 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-17
* Basecamp — <https://github.com/georgeantonopoulos/Basecamp-MCP-Server> ⭐ 96 | 🐛 7 | 🌐 Python | 📅 2026-08-09
* AniList — <https://github.com/yuna0x0/anilist-mcp> ⭐ 84 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-13
* Algorand — <https://github.com/GoPlausible/algorand-mcp> ⭐ 44 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-08
* APISIX-MCP — <https://github.com/api7/apisix-mcp> ⭐ 38 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-16
* Bluesky — <https://github.com/keturiosakys/bluesky-context-server> ⭐ 33 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-10
* Agentset — <https://github.com/agentset-ai/mcp-server> ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-16
* Alertmanager — <https://github.com/ntk148v/alertmanager-mcp-server> ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2026-06-16
* AnkiConnect — <https://github.com/spacholski1225/anki-connect-mcp> ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-20
* AWS EC2 Pricing — <https://github.com/trilogy-group/aws-pricing-mcp> ⭐ 21 | 🐛 3 | 🌐 Python | 📅 2025-07-24
* Bing Webmaster Tools — <https://github.com/isiahw1/mcp-server-bing-webmaster> ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2026-02-10
* Currents — <https://github.com/currents-dev/currents-mcp> ⭐ 19 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-17
* Backup — <https://github.com/hexitex/MCP-Backup-Server> ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-08
* Box community server — <https://github.com/hmk/box-mcp-server> ⭐ 11 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-22
* AllInOneMCP / MCP Discovery / MCP of MCPs — <https://github.com/particlefuture/MCPDiscovery>
* Browser MCPs — multiple implementations for local and remote browser automation
* Context-aware & discovery servers (context-awesome, ref, etc.)
* DINO-X, Digma, Driflyte, DreamFactory, Dash0, DB-specific servers, and many more.

(For the exhaustive long list of community servers and links, refer to the aggregated listings in community and official sections across the MCP ecosystem. This README collects and organizes the major categories and many example projects; the community maintains a rapidly growing set of servers — check the linked repos for the latest.)

***

# Clients

Clients and UI tools that consume MCP servers:

* Zed — <https://github.com/zed-industries/zed> ⭐ 88,759 | 🐛 3,250 | 🌐 Rust | 📅 2026-08-17
* Continue — <https://github.com/continuedev/continue> ⭐ 35,519 | 🐛 948 | 🌐 TypeScript | 📅 2026-08-17
* gpt-computer-assistant — <https://github.com/Upsonic/gpt-computer-assistant> ⭐ 7,941 | 🐛 30 | 🌐 Python | 📅 2026-06-18
* genkit — <https://github.com/firebase/genkit> ⭐ 6,342 | 🐛 712 | 🌐 TypeScript | 📅 2026-08-17
* mcphub.nvim — <https://github.com/ravitemer/mcphub.nvim> ⭐ 1,783 | 🐛 24 | 🌐 Lua | 📅 2026-01-18
* Nerve — <https://github.com/evilsocket/nerve> ⚠️ Archived
* MCP-Bridge — <https://github.com/SecretiveShell/MCP-Bridge> ⭐ 930 | 🐛 36 | 🌐 Python | 📅 2025-12-08
* mcp-cli — <https://github.com/wong2/mcp-cli> ⭐ 443 | 🐛 11 | 🌐 JavaScript | 📅 2026-06-08
* Shinkai — <http://github.com/dcSpark/shinkai-apps/> ⭐ 431 | 🐛 16 | 🌐 TypeScript | 📅 2026-06-15
* MCP-Chatbot (⭐ CLI) — <https://github.com/3choff/mcp-chatbot> ⭐ 251 | 🐛 2 | 🌐 Python | 📅 2024-12-05
* MCP-Connect — <https://github.com/EvalsOne/mcp-connect> ⭐ 239 | 🐛 1 | 🌐 Python | 📅 2026-03-18
* MBro — <https://github.com/sitbon/magg/blob/main/docs/mbro.md> ⭐ 142 | 🐛 7 | 🌐 Python | 📅 2026-08-02
* codemirror-mcp — <https://github.com/marimo-team/codemirror-mcp> ⭐ 79 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28
* mcp-client — <https://github.com/rakesh-eltropy/mcp-client> ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2025-03-11
* LibreChat — <https://www.librechat.ai/>
* mcps-playground — <https://mcpsplayground.com/chat>

***

# Frameworks

Frameworks and scaffolding for building MCP servers:

* PraisonAI MCP — <https://github.com/MervinPraison/praisonai-mcp> ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-01-13 (AI Agents framework with 64+ built-in tools for search, memory, workflows, code execution)

Frameworks and scaffolding for building MCP servers:

* ToolHive — <https://github.com/Stacklok/toolhive> ⭐ 2,022 | 🐛 384 | 🌐 Go | 📅 2026-08-17
* mcp-framework — <https://github.com/QuantGeekDev/mcp-framework> ⭐ 928 | 🐛 23 | 🌐 TypeScript | 📅 2026-04-16
* centralmind/gateway — <https://github.com/centralmind/gateway> ⭐ 544 | 🐛 15 | 🌐 Go | 📅 2025-07-18
* LiteMCP — <https://github.com/wong2/litemcp> ⭐ 185 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-27
* oatpp-mcp — <https://github.com/oatpp/oatpp-mcp> ⭐ 50 | 🐛 2 | 🌐 C++ | 📅 2024-12-13
* MCP Plexus — <https://github.com/super-i-tech/mcp_plexus> ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2025-06-09
* create-mcp-ts — <https://github.com/stephencme/create-mcp-ts> ⭐ 21 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-23
* fastMCP4J — <https://github.com/tersePrompts/fastMCP4J> ⭐ 8 | 🐛 1 | 🌐 Java | 📅 2026-02-11
* many others to simplify server creation, type-safety, and security best practices

***

# Notes & Recommendations

* Always run untrusted or community MCP servers in an isolated environment (container or VM) and restrict access to sensitive resources.
* Prefer official vendor-maintained servers (marked with ⭐) for production use.
* Check each server repo for documentation about transports (stdio, SSE, HTTP), authentication, and example clients.
* This ecosystem evolves rapidly — many new servers, clients, and frameworks are added frequently. If you maintain a server, ensure the repo has clear installation and security instructions.
* [SkillFlow MCP Server](https://github.com/rafsilva85/skillflow-mcp-server) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-26 - Search and discover AI agent skills from the SkillFlow marketplace. Browse 500+ skills with trust metrics, categories, and ratings.

<div align="right">
    <b><a href="#Contents">↥ back to top</a></b>
</div>

## Contributors

<a href="https://github.com/YuzeHao2023/Awesome-MCP-Servers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=YuzeHao2023/Awesome-MCP-Servers" />
</a>

If this project is helpful for you, please cite:

```bib
@misc{hao2025mcp,
      title={Awesome-MCP-Servers}, 
      author={All Awesome-MCP-Servers Contributors},
      year={2025},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/YuzeHao2023/Awesome-MCP-Servers}},
}
```

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
