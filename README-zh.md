# Awesome MCP (模型上下文协议) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

精选的模型上下文协议（MCP）资源、工具和服务器实现列表。

[English](README.md) | [简体中文](README-zh.md)

## 什么是MCP？

MCP（模型上下文协议）是一种开放协议，通过标准化的服务器实现，使AI模型能够安全地与本地和远程资源交互。这使AI助手能够通过访问文件、数据库、API和其他上下文服务来扩展其功能。

## 目录

- [客户端](#客户端)
- [官方资源](#官方资源)
- [教程](#教程)
- [社区](#社区)
- [服务器实现](#服务器实现)
- [框架](#框架)
- [技巧与窍门](#技巧与窍门)

## 客户端

*使用MCP服务的应用程序和工具。*

<!-- 客户端部分将在后续填充 -->

## 官方资源

*关于MCP的官方文档和资源。*

- [模型上下文协议文档](https://docs.anthropic.com/claude/docs/model-context-protocol) - Anthropic的官方文档。

## 教程

*关于MCP使用的指南和教程。*

<!-- 教程部分将在后续填充 -->

## 社区

*关于MCP的社区资源和讨论平台。*

<!-- 社区部分将在后续填充 -->

## 服务器实现

*适用于不同用例的各种MCP服务器实现。*

### 图例说明

- 🏅 – 官方实现
- **编程语言**
  - <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> – Python代码库
  - <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> – TypeScript（或JavaScript）代码库
  - <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> – Go代码库
  - <img src="https://cdn.simpleicons.org/rust/000000" width="16" height="16"/> – Rust代码库
  - <img src="https://cdn.simpleicons.org/csharp/239120" width="16" height="16"/> - C#代码库
  - <img src="https://cdn.simpleicons.org/java/007396" width="16" height="16"/> - Java代码库
- **范围**
  - <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> - 云服务
  - <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 本地服务
  - <img src="https://cdn.simpleicons.org/arduino/00979D" width="16" height="16"/> - 嵌入式系统
- **操作系统**
  - <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> – 适用于macOS
  - <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> – 适用于Windows
  - <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> – 适用于Linux

### 生产力与工作

<!-- 生产力与工作部分将在后续填充高质量的MCP服务器实现 -->

### 开发与API

* [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream) ![GitHub stars](https://img.shields.io/github/stars/PipedreamHQ/pipedream?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP 服务器，提供与 2,500+ 个 API 的连接，通过 8,000+ 个预构建工具。使用低代码集成工作流平台将您的 AI 代理连接到 SaaS 应用、数据库和 API。
* [get-convex/convex-backend](https://github.com/get-convex/convex-backend) ![GitHub stars](https://img.shields.io/github/stars/get-convex/convex-backend?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP服务器，允许检查和查询部署在Convex上的应用程序，Convex是一个具有自动持久化、实时订阅等功能的后端应用开发平台。
* [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python) ![GitHub stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 提供安全沙箱环境执行Python代码的MCP服务器，专为AI代理设计，允许LLM编写和运行Python代码进行数据分析、可视化和原型开发，同时确保安全隔离。

### 数据与知识

* [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) ![GitHub stars](https://img.shields.io/github/stars/mindsdb/mindsdb?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MindsDB 内置 MCP 服务器功能，使 MCP 应用程序能够连接、统一并回答来自不同数据源的问题，包括数据库、数据仓库和 SaaS 应用程序的大规模联合数据。
* [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 提供对PostgreSQL数据库只读访问的MCP服务器，具有模式检查功能，使AI助手能够在保持安全的同时查询和分析数据。
* [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 具有商业智能功能的SQLite数据库交互MCP服务器，允许LLM在本地数据库上执行数据分析，支持查询生成和结果解释。
* [prisma/prisma](https://github.com/prisma/prisma) ![GitHub stars](https://img.shields.io/github/stars/prisma/prisma?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/nodejs/339933" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Prisma CLI包含内置MCP服务器，使AI代理能够管理Prisma Postgres数据库，创建数据库实例，运行模式迁移，以及执行数据操作。
* [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) ![GitHub stars](https://img.shields.io/github/stars/supabase-community/supabase-mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 提供对Supabase管理API和PostgreSQL数据库访问的MCP服务器，允许AI助手管理和交互Supabase项目和数据。
* [devflowinc/trieve](https://github.com/devflowinc/trieve) ![GitHub stars](https://img.shields.io/github/stars/devflowinc/trieve?style=social) <img src="https://cdn.simpleicons.org/rust/000000" width="16" height="16"/> <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 通过API提供搜索、推荐和RAG的全方位基础设施，具有MCP服务器功能，使AI代理能够从自定义知识库中搜索和检索上下文。

### 媒体与娱乐

* [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) ![GitHub stars](https://img.shields.io/github/stars/zcaceres/markdownify-mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 用于将各种文件类型转换为Markdown的模型上下文协议服务器。支持PDF、图像、音频（带转录）、Office文档、网页内容等。
* [mckinsey/vizro-mcp](https://github.com/mckinsey/vizro/tree/main/vizro-mcp) ![GitHub stars](https://img.shields.io/github/stars/mckinsey/vizro?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 用于使用Vizro创建和操作数据可视化和仪表板的MCP服务器，Vizro是一个用于构建高质量数据可视化应用的低代码Python工具包。
* [mickaelkerjean/filestash](https://github.com/mickael-kerjean/filestash) ![GitHub stars](https://img.shields.io/github/stars/mickael-kerjean/filestash?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 适用于多种存储协议的文件管理器网络客户端，包括SFTP、S3、FTP、WebDAV、Git、Minio、LDAP、CalDAV、CardDAV、Mysql等。
* [microsoft/markitdown](https://github.com/microsoft/markitdown) ![GitHub stars](https://img.shields.io/github/stars/microsoft/markitdown?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 具有MCP服务器功能的Python工具，用于将文件和办公文档转换为Markdown，支持PDF、Office格式、图像、音频等。
* [markmap/markmap](https://github.com/markmap/markmap) ![GitHub stars](https://img.shields.io/github/stars/markmap/markmap?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 用于将Markdown内容可视化为交互式思维导图的MCP服务器，使AI助手能够从纯文本创建、操作和渲染思维导图。
* [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/blazickjp/arxiv-mcp-server?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 用于搜索和分析arXiv研究论文的MCP服务器。使AI助手能够查询arXiv存储库，访问论文内容并执行结构化论文分析。

<!-- 媒体与娱乐部分将在后续填充高质量的MCP服务器实现 -->

### 系统与硬件

* [seifip/kilobat-cli](https://github.com/seifip/kilobat-cli) ![GitHub stars](https://img.shields.io/github/stars/seifip/kilobat-cli?style=social) <img src="https://cdn.simpleicons.org/swift/F05138" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> - 通过本地 stdio MCP 服务监测和诊断 macOS 网络。

* [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=social) 🏅 <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 基于Playwright的MCP服务器，提供浏览器自动化功能。该服务器使LLM能够通过结构化的可访问性快照与网页交互，无需使用截图或视觉调优模型。
* [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) ![GitHub stars](https://img.shields.io/github/stars/executeautomation/mcp-playwright?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - Playwright MCP服务器，使LLM能够与网页交互、截取屏幕截图、生成测试代码、网页抓取，以及使用自然语言命令执行API测试。
* [browsermcp/mcp](https://github.com/browsermcp/mcp) ![GitHub stars](https://img.shields.io/github/stars/browsermcp/mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 提供本地Chrome浏览器自动化的MCP服务器。允许LLM直接控制您的浏览器进行网页导航、表单填写、数据提取和其他基于浏览器的任务。
* [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 基于Puppeteer的MCP服务器，用于浏览器自动化、网页抓取和网页内容交互。提供导航到URL、截取屏幕截图、提取数据以及以编程方式与网页元素交互的工具。
* [awslabs/mcp](https://github.com/awslabs/mcp) ![GitHub stars](https://img.shields.io/github/stars/awslabs/mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - AWS官方MCP服务器，提供对AWS服务的访问。使LLM能够通过标准化接口与AWS资源交互，支持AWS服务集成和云资源管理。
* [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ![GitHub stars](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 提供与Cloudflare开发者平台交互的MCP服务器，支持部署、配置和管理Cloudflare资源，包括Workers、KV、R2和D1。
* [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ![GitHub stars](https://img.shields.io/github/stars/wonderwhy-er/DesktopCommanderMCP?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 提供终端控制、文件系统搜索和精细代码编辑功能的MCP服务器。使AI能够执行终端命令、管理进程并通过基于模式的替换编辑文件。
* [ezyang/codemc](https://github.com/ezyang/codemcp) ![GitHub stars](https://img.shields.io/github/stars/ezyang/codemcp?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 为Claude Desktop设计的编码助手MCP。通过允许Claude实现功能、修复错误和对本地代码仓库执行重构，实现AI驱动的结对编程。
* [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 提供频道管理和消息功能的Slack MCP服务器。使AI助手能够与Slack工作区交互，检索消息并发送通信。
* [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) ![GitHub stars](https://img.shields.io/github/stars/lharries/whatsapp-mcp?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - WhatsApp MCP服务器，允许AI代理搜索和读取个人WhatsApp消息，发送文本和媒体消息，以及管理联系人。使用WhatsApp Web多设备API直接连接到您的个人WhatsApp账户。
* [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) ![GitHub stars](https://img.shields.io/github/stars/GLips/Figma-Context-MCP?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 提供对Figma设计文件访问的MCP服务器，使AI代理能够分析设计元素、提取UI规范并使用准确规格实现设计。
* [alibaba/higress](https://github.com/alibaba/higress) ![GitHub stars](https://img.shields.io/github/stars/alibaba/higress?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 具有MCP服务器功能的云原生API网关，为微服务架构提供服务发现、流量管理和安全功能。
* [elie222/inbox-zero](https://github.com/elie222/inbox-zero) ![GitHub stars](https://img.shields.io/github/stars/elie222/inbox-zero?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 电子邮件AI助手MCP服务器，用于批量Gmail管理，包括自动回复草稿、阻止冷邮件、批量取消订阅以及跟踪需要回复的邮件，帮助用户更快地实现收件箱零负担。
* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) ![GitHub stars](https://img.shields.io/github/stars/sooperset/mcp-atlassian?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 用于Atlassian工具(Confluence、Jira)的MCP服务器，使AI助手能够搜索、创建和更新Confluence页面和Jira问题，同时支持Cloud和Server/Data Center部署。
* [github/github-mcp-server](https://github.com/github/github-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/github/github-mcp-server?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - GitHub官方MCP服务器，提供与GitHub API的无缝集成，使AI助手能够通过自然语言管理仓库、问题、拉取请求和代码。
* [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) ![GitHub stars](https://img.shields.io/github/stars/anaisbetts/mcp-installer?style=social) <img src="https://cdn.simpleicons.org/javascript/F7DF1E" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 一个元MCP服务器，可以按需安装其他MCP服务器，通过自然语言请求轻松发现和安装来自npm或PyPI的MCP服务器。
* [AgentDeskAI/browser-tools-mcp](https://github.com/AgentDeskAI/browser-tools-mcp) ![GitHub stars](https://img.shields.io/github/stars/AgentDeskAI/browser-tools-mcp?style=social) <img src="https://cdn.simpleicons.org/javascript/F7DF1E" width="16" height="16"/> <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 浏览器监控和交互MCP服务器，集成Chrome扩展功能。捕获控制台日志、网络流量、屏幕截图，并提供SEO、性能和可访问性审计，使AI助手能够直接从MCP客户端与网页内容交互。
* [stagewise-io/stagewise](https://github.com/stagewise-io/stagewise) ![GitHub stars](https://img.shields.io/github/stars/stagewise-io/stagewise?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - 基于浏览器的MCP服务器，使AI代理（Cursor、Github Copilot、Windsurf）能够与浏览器交互。允许在DOM元素上添加评论，向AI工具提供真实上下文，并支持多种框架，包括React、Next.js、Vue和Nuxt.js。

### AI与机器学习工具

<!-- AI与机器学习工具部分将在后续填充高质量的MCP服务器实现 -->

## 框架

*用于构建MCP服务器的框架和库。*

* [volcengine/mcp-server](https://github.com/volcengine/mcp-server) ![GitHub stars](https://img.shields.io/github/stars/volcengine/mcp-server?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - 火山引擎大模型生态广场的MCP Server共享仓库，目前已上线100+个MCP服务器，涵盖搜索工具、位置服务、内容生成、源码管理、数据查询、文件管理、协作沟通等多种类别，支持用户探索与体验大模型丰富生态服务。

## 技巧与窍门

*使用MCP的有用技巧和窍门。*

<!-- 技巧与窍门部分将在后续填充 -->

## 贡献

在提交拉取请求之前，请阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 