# MCP Servers Schemas

This document provides a list of different MCP servers. For each server, we provide a schema definition that includes the latest basic information and tool definitions.

## Usage Scenario

This document is intended for users who want to quickly access the latest MCP server definitions without needing to install the MCP server locally. By reviewing the schema definitions provided in this document, users can easily obtain the most up-to-date server information and tool definitions.

## Official Integrations

| Name | Description | Repo URL | Schema |
|---|---|---|---|
| Axiom | Query and analyze your Axiom logs, traces, and all other event data in natural language | [https://github.com/axiomhq/mcp-server-axiom](https://github.com/axiomhq/mcp-server-axiom) | [Schema](schemas/mcp-server-axiom.json) |
| Browserbase | Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more) | [https://github.com/browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | [Schema](schemas/mcp-server-browserbase.json) |
| Cloudflare | Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1) | [https://github.com/cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | [Schema](schemas/mcp-server-cloudflare.json) |
| Raygun | Interact with your crash reporting and real using monitoring data on your Raygun account | [https://github.com/MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) |  |
| Obsidian Markdown Notes | Read and search through your Obsidian vault or any directory containing Markdown notes | [https://github.com/calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) | [Schema](schemas/mcp-obsidian.json) |
| E2B | Run code in secure sandboxes hosted by [E2B](https://e2b.dev) | [https://github.com/e2b-dev/mcp-server](https://github.com/e2b-dev/mcp-server) |  |
| Exa | Search Engine made for AIs by [Exa](https://exa.ai) | [https://github.com/exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) | [Schema](schemas/exa-mcp-server.json) |
| JetBrains | – Work on your code with JetBrains IDEs | [https://github.com/JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) | [Schema](schemas/mcp-jetbrains.json) |
| Needle | Production-ready RAG out of the box to search and retrieve data from your own documents. | [https://github.com/JANHMS/needle-mcp](https://github.com/JANHMS/needle-mcp) | [Schema](schemas/needle-mcp.json) |
| Neon | Interact with the Neon serverless Postgres platform | [https://github.com/neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) | [Schema](schemas/mcp-server-neon.json) |
| Neo4j | Neo4j graph database server (schema + read/write-cypher) and separate graph database backed memory | [https://github.com/neo4j-contrib/mcp-neo4j/](https://github.com/neo4j-contrib/mcp-neo4j/) |  |
| Tinybird | Interact with Tinybird serverless ClickHouse platform | [https://github.com/tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) | [Schema](schemas/mcp-tinybird.json) |
| Search1API | One API for Search, Crawling, and Sitemaps | [https://github.com/fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) | [Schema](schemas/search1api-mcp.json) |
| Qdrant | Implement semantic memory layer on top of the Qdrant vector search engine | [https://github.com/qdrant/mcp-server-qdrant/](https://github.com/qdrant/mcp-server-qdrant/) |  |
| Metoro | Query and interact with kubernetes environments monitored by Metoro | [https://github.com/metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) |  |

## Community Servers

| Name | Description | Repo URL | Schema |
|---|---|---|---|
| MCP Installer | This server is a server that installs other MCP servers for you. | [https://github.com/anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) |  |
| NS Travel Information | Access Dutch Railways (NS) real-time train travel information and disruptions through the official NS API. | [https://github.com/r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) | [Schema](schemas/ns-mcp-server.json) |
| Spotify | This MCP allows an LLM to play and use Spotify. | [https://github.com/varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) |  |
| Inoyu | Interact with an Apache Unomi CDP customer data platform to retrieve and update customer profiles | [https://github.com/sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) | [Schema](schemas/inoyu-mcp-unomi-server.json) |
| Vega-Lite | Generate visualizations from fetched data using the VegaLite format and renderer. | [https://github.com/isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) | [Schema](schemas/mcp-vegalite-server.json) |
| Snowflake | This MCP server enables LLMs to interact with Snowflake databases, allowing for secure and controlled data operations. | [https://github.com/isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) | [Schema](schemas/mcp-snowflake-server.json) |
| MySQL | MySQL database integration in Python with configurable access controls and schema inspection | [https://github.com/designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) | [Schema](schemas/mysql_mcp_server.json) |
| MySQL | MySQL database integration in NodeJS with configurable access controls and schema inspection | [https://github.com/benborla/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | [Schema](schemas/mcp-server-mysql.json) |
| MSSQL | MSSQL database integration with configurable access controls and schema inspection | [https://github.com/aekanun2020/mcp-server/](https://github.com/aekanun2020/mcp-server/) |  |
| BigQuery | This server enables LLMs to inspect database schemas and execute queries on BigQuery. | [https://github.com/LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) | [Schema](schemas/mcp-server-bigquery.json) |
| BigQuery | Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities | [https://github.com/ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) | [Schema](schemas/mcp-bigquery-server.json) |
| Todoist | Interact with Todoist to manage your tasks. | [https://github.com/abhiz123/todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) | [Schema](schemas/todoist-mcp-server.json) |
| Tavily search | An MCP server for Tavily's search & news API, with explicit site inclusions/exclusions | [https://github.com/RamXX/mcp-tavily](https://github.com/RamXX/mcp-tavily) | [Schema](schemas/mcp-tavily.json) |
| Linear | Allows LLM to interact with Linear's API for project management, including searching, creating, and updating issues. | [https://github.com/jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) |  |
| Playwright | This MCP Server will help you run browser automation and webscraping using Playwright | [https://github.com/executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) | [Schema](schemas/mcp-playwright.json) |
| AWS | Perform operations on your AWS resources using an LLM | [https://github.com/rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) | [Schema](schemas/mcp-server-aws.json) |
| LlamaCloud | Integrate the data stored in a managed index on [LlamaCloud](https://cloud.llamaindex.ai/) | [https://github.com/run-llama/mcp-server-llamacloud](https://github.com/run-llama/mcp-server-llamacloud) | [Schema](schemas/mcp-server-llamacloud.json) |
| Any Chat Completions | Interact with any OpenAI SDK Compatible Chat Completions API like OpenAI, Perplexity, Groq, xAI and many more. | [https://github.com/pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) | [Schema](schemas/any-chat-completions-mcp.json) |
| Windows CLI | MCP server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells. | [https://github.com/SimonB97/win-cli-mcp-server](https://github.com/SimonB97/win-cli-mcp-server) |  |
| OpenRPC | Interact with and discover JSON-RPC APIs via [OpenRPC](https://open-rpc.org). | [https://github.com/shanejonas/openrpc-mpc-server](https://github.com/shanejonas/openrpc-mpc-server) | [Schema](schemas/openrpc-mpc-server.json) |
| FireCrawl | Advanced web scraping with JavaScript rendering, PDF support, and smart rate limiting | [https://github.com/vrknetha/mcp-server-firecrawl](https://github.com/vrknetha/mcp-server-firecrawl) |  |
| AlphaVantage | MCP server for stock market data API [AlphaVantage](https://www.alphavantage.co) | [https://github.com/calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) |  |
| Docker | Integrate with Docker to manage containers, images, volumes, and networks. | [https://github.com/ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) | [Schema](schemas/mcp-server-docker.json) |
| Kubernetes | Connect to Kubernetes cluster and manage pods, deployments, and services. | [https://github.com/Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) | [Schema](schemas/mcp-server-kubernetes.json) |
| OpenAPI | Interact with [OpenAPI](https://www.openapis.org/) APIs. | [https://github.com/snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) |  |
| Pandoc | MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, and plain text, with other formats like PDF, csv and docx in development. | [https://github.com/vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) | [Schema](schemas/mcp-pandoc.json) |
| Pinecone | MCP server for searching and uploading records to Pinecone. Allows for simple RAG features, leveraging Pinecone's Inference API. | [https://github.com/sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) | [Schema](schemas/mcp-pinecone.json) |
| HuggingFace Spaces | Server for using HuggingFace Spaces, supporting Open Source Image, Audio, Text Models and more. Claude Desktop mode for easy integration. | [https://github.com/evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) |  |
| ChatSum | Query and Summarize chat messages with LLM. by [mcpso](https://mcp.so) | [https://github.com/chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) | [Schema](schemas/mcp-server-chatsum.json) |
| Rememberizer AI | An MCP server designed for interacting with the Rememberizer data source, facilitating enhanced knowledge retrieval. | [https://github.com/skydeckai/mcp-server-rememberizer](https://github.com/skydeckai/mcp-server-rememberizer) | [Schema](schemas/mcp-server-rememberizer.json) |
| FlightRadar24 | A Claude Desktop MCP server that helps you track flights in real-time using Flightradar24 data. | [https://github.com/sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) | [Schema](schemas/flightradar24-mcp-server.json) |
| X (Twitter) | Create, manage and publish X/Twitter posts directly through Claude chat. | [https://github.com/vidhupv/x-mcp](https://github.com/vidhupv/x-mcp) | [Schema](schemas/x-mcp.json) |
| X (Twitter) | Interact with twitter API. Post tweets and search for tweets by query. | [https://github.com/EnesCinr/twitter-mcp](https://github.com/EnesCinr/twitter-mcp) | [Schema](schemas/twitter-mcp.json) |
| RAG Web Browser | An MCP server for Apify's RAG Web Browser Actor to perform web searches, scrape URLs, and return content in Markdown. | [https://github.com/apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) | [Schema](schemas/mcp-server-rag-web-browser.json) |
| XMind | Read and search through your XMind directory containing XMind files. | [https://github.com/apeyroux/mcp-xmind](https://github.com/apeyroux/mcp-xmind) | [Schema](schemas/mcp-xmind.json) |
| oatpp-mcp | C++ MCP integration for Oat++. Use [Oat++](https://oatpp.io) to build MCP servers. | [https://github.com/oatpp/oatpp-mcp](https://github.com/oatpp/oatpp-mcp) |  |
| Contentful-mcp | Read, update, delete, publish content in your [Contentful](https://contentful.com) space(s) from this MCP Server. | [https://github.com/ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) |  |
| Home Assistant | Interact with [Home Assistant](https://www.home-assistant.io/) including viewing and controlling lights, switches, sensors, and all other Home Assistant entities. | [https://github.com/tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) | [Schema](schemas/homeassistant-mcp.json) |
| cognee-mcp | GraphRAG memory server with customizable ingestion, data processing and search | [https://github.com/topoteretes/cognee-mcp-server](https://github.com/topoteretes/cognee-mcp-server) | [Schema](schemas/cognee-mcp-server.json) |
| Airtable | Read and write access to [Airtable](https://airtable.com/) databases, with schema inspection. | [https://github.com/domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) |  |
| mcp-k8s-go | Golang-based Kubernetes server for MCP to browse pods and their logs, events, namespaces and more. Built to be extensible. | [https://github.com/strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) |  |
| Notion | Notion MCP integration. Search, Read, Update, and Create pages through Claude chat. | [https://github.com/v-3/notion-server](https://github.com/v-3/notion-server) |  |
| Notion | Interact with Notion API. | [https://github.com/suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) |  |
| TMDB | This MCP server integrates with The Movie Database (TMDB) API to provide movie information, search capabilities, and recommendations. | [https://github.com/Laksh-star/mcp-server-tmdb](https://github.com/Laksh-star/mcp-server-tmdb) | [Schema](schemas/mcp-server-tmdb.json) |
| MongoDB | A Model Context Protocol Server for MongoDB. | [https://github.com/kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) | [Schema](schemas/mcp-mongo-server.json) |
| Airtable | Airtable Model Context Protocol Server. | [https://github.com/felores/airtable-mcp](https://github.com/felores/airtable-mcp) | [Schema](schemas/airtable-mcp.json) |
| Atlassian | Interact with Atlassian Cloud products (Confluence and Jira) including searching/reading Confluence spaces/pages, accessing Jira issues, and project metadata. | [https://github.com/sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) |  |
| Google Tasks | Google Tasks API Model Context Protocol Server. | [https://github.com/zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) | [Schema](schemas/gtasks-mcp.json) |
| Fetch | A server that flexibly fetches HTML, JSON, Markdown, or plaintext | [https://github.com/zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) | [Schema](schemas/fetch-mcp.json) |

