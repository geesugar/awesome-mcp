# Awesome MCP (Model Context Protocol) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Model Context Protocol (MCP) resources, tools, and server implementations.

[English](README.md) | [简体中文](README-zh.md)

## What is MCP?

MCP (Model Context Protocol) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This allows AI assistants to extend their capabilities by accessing files, databases, APIs, and other contextual services.

## Contents

- [Clients](#clients)
- [Official Resources](#official-resources)
- [Tutorials](#tutorials)
- [Community](#community)
- [Server Implementations](#server-implementations)
- [Frameworks](#frameworks)
- [Tips & Tricks](#tips--tricks)

## Clients

*Applications and tools that consume MCP services.*

<!-- Client section will be filled later -->

## Official Resources

*Official documentation and resources about MCP.*

- [Model Context Protocol Documentation](https://docs.anthropic.com/claude/docs/model-context-protocol) - Official documentation from Anthropic.

## Tutorials

*Guides and tutorials for working with MCP.*

<!-- Tutorials section will be filled later -->

## Community

*Community resources and discussion platforms about MCP.*

<!-- Community section will be filled later -->

## Server Implementations

*Various MCP server implementations for different use cases.*

### Legend

- 🏅 – Official implementation
- **Programming language**
  - <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> – Python codebase
  - <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> – TypeScript (or JavaScript) codebase
  - <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> – Go codebase
  - <img src="https://cdn.simpleicons.org/rust/000000" width="16" height="16"/> – Rust codebase
  - <img src="https://cdn.simpleicons.org/csharp/239120" width="16" height="16"/> - C# codebase
  - <img src="https://cdn.simpleicons.org/java/007396" width="16" height="16"/> - Java codebase
- **Scope**
  - <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> - Cloud Service
  - <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Local Service
  - <img src="https://cdn.simpleicons.org/arduino/00979D" width="16" height="16"/> - Embedded Systems
- **Operating system**
  - <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> – For macOS
  - <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> – For Windows
  - <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> – For Linux

### Productivity & Work

<!-- Productivity & Work section will be filled later with high-quality MCP server implementations -->

### Development & APIs

* [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream) ![GitHub stars](https://img.shields.io/github/stars/PipedreamHQ/pipedream?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server that provides connectivity with 2,500+ APIs through 8,000+ prebuilt tools. Connect your AI agents to SaaS apps, databases, and APIs with low-code integration workflow platform.
* [get-convex/convex-backend](https://github.com/get-convex/convex-backend) ![GitHub stars](https://img.shields.io/github/stars/get-convex/convex-backend?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server that allows introspection and querying of applications deployed to Convex, a backend application development platform with automatic persistence, realtime subscriptions, and more.

### Data & Knowledge

* [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) ![GitHub stars](https://img.shields.io/github/stars/mindsdb/mindsdb?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MindsDB provides built-in MCP server functionality, enabling MCP applications to connect, unify, and answer questions from different data sources, including large-scale federated data from databases, data warehouses, and SaaS applications.
* [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server providing read-only access to PostgreSQL databases with schema inspection capabilities, enabling AI assistants to query and analyze data while maintaining security.
* [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for SQLite database interactions with business intelligence capabilities, allowing LLMs to perform data analysis on local databases with query generation and result interpretation.
* [prisma/prisma](https://github.com/prisma/prisma) ![GitHub stars](https://img.shields.io/github/stars/prisma/prisma?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/nodejs/339933" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - The Prisma CLI includes a built-in MCP server, enabling AI agents to manage Prisma Postgres databases, create database instances, run schema migrations, and perform data operations.
* [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) ![GitHub stars](https://img.shields.io/github/stars/supabase-community/supabase-mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server providing access to Supabase management API and PostgreSQL databases, allowing AI assistants to manage and interact with Supabase projects and data.
* [devflowinc/trieve](https://github.com/devflowinc/trieve) ![GitHub stars](https://img.shields.io/github/stars/devflowinc/trieve?style=social) <img src="https://cdn.simpleicons.org/rust/000000" width="16" height="16"/> <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - All-in-one infrastructure for search, recommendations, and RAG offered via API with MCP server capabilities, enabling AI agents to search and retrieve context from customized knowledge bases.

### Media & Entertainment

* [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) ![GitHub stars](https://img.shields.io/github/stars/zcaceres/markdownify-mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - A Model Context Protocol server for converting various file types to Markdown. Supports PDFs, images, audio (with transcription), Office documents, web content and more.
* [mckinsey/vizro-mcp](https://github.com/mckinsey/vizro/tree/main/vizro-mcp) ![GitHub stars](https://img.shields.io/github/stars/mckinsey/vizro?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for creating and manipulating data visualizations and dashboards with Vizro, a low-code Python toolkit for building high-quality data visualization apps.
* [mickaelkerjean/filestash](https://github.com/mickael-kerjean/filestash) ![GitHub stars](https://img.shields.io/github/stars/mickael-kerjean/filestash?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - A file manager web client for a wide range of storage protocols including SFTP, S3, FTP, WebDAV, Git, Minio, LDAP, CalDAV, CardDAV, Mysql, and more.
* [microsoft/markitdown](https://github.com/microsoft/markitdown) ![GitHub stars](https://img.shields.io/github/stars/microsoft/markitdown?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Python tool with MCP server capability for converting files and office documents to Markdown, supporting PDFs, Office formats, images, audio, and more.
* [markmap/markmap](https://github.com/markmap/markmap) ![GitHub stars](https://img.shields.io/github/stars/markmap/markmap?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for visualizing Markdown content as interactive mindmaps, allowing AI assistants to create, manipulate and render mindmaps from plain text.
* [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/blazickjp/arxiv-mcp-server?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for searching and analyzing arXiv research papers. Enables AI assistants to query arXiv's repository, access paper content and perform structured paper analysis.

<!-- Media & Entertainment section will be filled later with high-quality MCP server implementations -->

### System & Hardware

* [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=social) 🏅 <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - MCP server that provides browser automation capabilities using Playwright. This server enables LLMs to interact with web pages through structured accessibility snapshots, bypassing the need for screenshots or visually-tuned models.
* [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) ![GitHub stars](https://img.shields.io/github/stars/executeautomation/mcp-playwright?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - Playwright MCP server that enables LLMs to interact with web pages, take screenshots, generate test code, web scrape, and execute API tests with natural language commands.
* [browsermcp/mcp](https://github.com/browsermcp/mcp) ![GitHub stars](https://img.shields.io/github/stars/browsermcp/mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - MCP server that provides local Chrome browser automation. Allows LLMs to directly control your browser for web navigation, form filling, data extraction, and other browser-based tasks.
* [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - Puppeteer-based MCP server for browser automation, web scraping, and web content interaction. Provides tools for navigating to URLs, taking screenshots, extracting data, and programmatically interacting with web elements.
* [awslabs/mcp](https://github.com/awslabs/mcp) ![GitHub stars](https://img.shields.io/github/stars/awslabs/mcp?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Official AWS MCP server providing access to AWS services. Enables LLMs to interact with AWS resources through a standardized interface, supporting AWS service integration and cloud resource management.
* [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ![GitHub stars](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server that provides interaction with Cloudflare's developer platform, enabling deployment, configuration, and management of Cloudflare resources including Workers, KV, R2, and D1.
* [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ![GitHub stars](https://img.shields.io/github/stars/wonderwhy-er/DesktopCommanderMCP?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - MCP server providing terminal control, file system search and surgical code editing capabilities. Enables AI to execute terminal commands, manage processes, and edit files with pattern-based replacements.
* [ezyang/codemc](https://github.com/ezyang/codemcp) ![GitHub stars](https://img.shields.io/github/stars/ezyang/codemcp?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - Coding assistant MCP for Claude Desktop. Enables AI-powered pair programming by allowing Claude to implement features, fix bugs, and perform refactoring on local code repositories.
* [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Slack MCP server providing channel management and messaging capabilities. Enables AI assistants to interact with Slack workspaces, retrieve messages, and send communications.
* [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) ![GitHub stars](https://img.shields.io/github/stars/GLips/Figma-Context-MCP?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - MCP server that provides access to Figma design files, enabling AI agents to analyze design elements, extract UI specifications, and implement designs with accurate specifications.
* [alibaba/higress](https://github.com/alibaba/higress) ![GitHub stars](https://img.shields.io/github/stars/alibaba/higress?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - Cloud-native API gateway with MCP server capabilities, providing service discovery, traffic management, and security features for microservices architectures.
* [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) ![GitHub stars](https://img.shields.io/github/stars/exa-labs/exa-mcp-server?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> <img src="https://cdn.simpleicons.org/apple/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/windows/999" width="16" height="16"/> <img src="https://cdn.simpleicons.org/linux/999" width="16" height="16"/> - MCP server that enables AI assistants to perform web searches using the Exa API. Provides real-time access to web information with tools for general web search, research papers, company information, and more.
* [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ![GitHub stars](https://img.shields.io/github/stars/LaurieWired/GhidraMCP?style=social) <img src="https://cdn.simpleicons.org/java/007396" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for Ghidra that allows AI assistants to autonomously reverse engineer applications. Provides tools for decompiling binaries, analyzing code, and automatically renaming methods and data in Ghidra.
* [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) ![GitHub stars](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp?style=social) <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server for IDA Pro that enables AI assistants to perform reverse engineering tasks. Provides tools for decompiling functions, disassembling code, analyzing binaries, and manipulating code elements like variables, comments, and types.

<!-- System & Hardware section will be filled later with high-quality MCP server implementations -->

### AI & ML Tools

* [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai) ![GitHub stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - MCP server providing a sandboxed Python interpreter that can run arbitrary code with a focus on security and safety. Enables AI models to execute Python code in a controlled environment.

### Communication & Productivity

* [elie222/inbox-zero](https://github.com/elie222/inbox-zero) ![GitHub stars](https://img.shields.io/github/stars/elie222/inbox-zero?style=social) <img src="https://cdn.simpleicons.org/typescript/3178C6" width="16" height="16"/> <img src="https://cdn.simpleicons.org/icloud/3693F3" width="16" height="16"/> - AI personal assistant for email that helps reach inbox zero. Open source platform with AI-powered email management, offering assistance for drafting replies, labeling, archiving, and managing communications across multiple accounts.
* [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) ![GitHub stars](https://img.shields.io/github/stars/lharries/whatsapp-mcp?style=social) <img src="https://cdn.simpleicons.org/go/00ADD8" width="16" height="16"/> <img src="https://cdn.simpleicons.org/python/3776AB" width="16" height="16"/> <img src="https://cdn.simpleicons.org/homeassistant/41BDF5" width="16" height="16"/> - WhatsApp MCP server that enables AI assistants to search and read personal WhatsApp messages, manage contacts, and send messages to individuals or groups. Supports media handling including images, videos, documents, and audio messages.

<!-- AI & ML Tools section will be filled later with high-quality MCP server implementations -->

## Frameworks

*Frameworks and libraries for building MCP servers.*

<!-- Frameworks section will be filled later -->

## Tips & Tricks

*Useful tips and tricks for working with MCP.*

<!-- Tips & Tricks section will be filled later -->

## Contributing

Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 