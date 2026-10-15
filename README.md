# Awesome-AI-Diagramming-Tools

## Top AI Diagramming Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Editorial Diagram Generation, Agent-Native Design & Code-to-Visual Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Diagramming Tools**. These tools enable developers and technical teams to generate professional, editorial-quality diagrams from code, natural language, or agent prompts—without wrestling with manual layout or importing "Mermaid slop" into documentation.



**Examples** include Lucidchart, Miro, Mural, Microsoft Visio, Gliffy, Creately, Draw.io, MindMeister, Whimsical, and Cacoo (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, agent-native diagram generation, and open text-to-diagram pipelines—ideal for technical writers, architects, and developers seeking transparent, vendor-independent diagramming infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global diagramming and visual collaboration software market is estimated at **$4.5B to $6.0B** (with dedicated diagramming at ~$1.5B–$1.8B and collaborative visual workspaces/whiteboards at ~$3.5B–$4.1B, expanding at 10%–15% CAGR). The sector is **moderately concentrated at the enterprise layer**, dominated by foundational platform giants (Microsoft, Miro, Lucid) that hold enterprise-wide procurement locks, while exhibiting a fragmented long-tail of specialized niche, indie, and developer-focused text-to-visual tools.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing (Starting Tier) | Free Tier Limits | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Visio](https://www.microsoft.com/en-us/microsoft-365/visio/)** | **~$3.1 Trillion** market cap / $245B+ rev (Microsoft parent) | $5.00/user/month (Visio Plan 1, annual billing) | 30-day free trial for Visio Plan 1/2; or Visio for M365 included with M365 commercial licenses (basic browser editing, limited templates) | Deep Microsoft 365 ecosystem integration, enterprise data-linking, industry-standard governance. |
| **[Lucidchart](https://www.lucidchart.com/)** | **$3.0 Billion** valuation / ~$200M+ ARR (Lucid Software) | $7.95/user/month (Individual plan, annual billing) | 3 editable documents, capped at 60 shapes per document, 100 basic templates | Web-based diagramming standard with robust enterprise integrations (ServiceNow, LeanIX, Confluence). |
| **[Mural](https://www.mural.co/)** | **$2.0 Billion** valuation / ~$100M–$125M ARR | $9.99/member/month (Team+ plan, annual billing) | 3 active murals, unlimited members, open workspace rooms only (no private rooms) | Facilitated visual collaboration platform tailored for workshops, agile ceremonies, and team planning. |
| **[Miro](https://miro.com/)** | **$1.355 Billion** acquisition EV / ~$600M ARR (acquired by Bending Spoons) | $8.00/member/month (Starter plan, annual billing) | 3 editable boards, unlimited team members, 10 AI credits per month, public team boards only | Dominant visual canvas and whiteboarding platform with extensive diagramming templates and AI widgets. |
| **[Gliffy](https://www.gliffy.com/)** | **~$100M+** (subsidiary of Perforce Software, private PE-backed) | $8.00/user/month (up to 50 users for Confluence Cloud, annual) / $10.00/mo standalone | Free for up to 10 users on Atlassian Confluence/Jira Cloud; 14-day free trial on standalone cloud | Native Confluence and Jira diagramming integration with drag-and-drop modeling. |
| **[Whimsical](https://whimsical.com/)** | **~$100M–$250M** valuation / ~$7M+ ARR | $10.00/editor/month (Pro plan, annual billing) | 50 board objects/month, 50 doc blocks/month, 10 one-time AI credits, unlimited boards & viewers | High-speed, minimalist canvas combining flowcharts, wireframes, mind maps, and docs. |
| **[Cacoo](https://cacoo.com/)** | **~$50M–$55M** market cap / ~$28M–$30M rev (Nulab, TYO: 5033) | $6.00/user/month (Pro/Team plan, annual billing) | 6 sheets (diagrams) total, unlimited users, PNG export only, 14-day trial for paid tiers | Real-time collaborative diagramming with multi-user cursors and Confluence/Jira/Google Drive integrations. |
| **[Draw.io Pro (Atlassian)](https://www.drawio.com/)** | **~$15M–$30M** estimated commercial rev (independent draw.io Ltd / AG) | $5.00/month flat (11–20 users on Confluence Cloud) scaling tiered | Free forever for teams of up to 10 users on Atlassian Confluence/Jira Cloud; web standalone is 100% free | Commercial Atlassian marketplace plugin for the Apache-2.0 draw.io/diagrams.net core engine. |
| **[Creately](https://creately.com/)** | **~$10M–$20M** estimated valuation / ~$5.1M ARR (Cinergix) | $5.00/user/month (Starter plan, annual billing) | Unlimited canvases & collaborators, capped at 45 items/shapes per canvas, 1 folder, JPEG/PNG export only | Multi-purpose visual workspace with AI modeling assistants and extensive template sets. |
| **[MindMeister](https://www.mindmeister.com/)** | **Bootstrapped SMB** / ~$5M–$10M ARR (MeisterLabs) | $6.00/user/month (Personal plan, annual billing) | 3 mind maps total, real-time collaboration, no export options (PDF/Word/image exports locked) | Dedicated structured mind mapping tool integrated with MeisterTask project management. |



## Open-Source GitHub Projects



- **[Diagram Design (cathrynlavery)](https://github.com/cathrynlavery/diagram-design)**  

  **The most important open-source diagramming project for coding agents in 2026** (121+ GitHub stars). **Editorial diagram design specifically tuned for Claude Code, Codex, GitHub Copilot, Factory Droid, and Pi** — "No shadows. No Mermaid slop" . **42 diagram types** covering architecture, flowcharts, sequence diagrams, state machines, ER/data models, timelines, swimlanes, quadrants, radar/spider charts, Sankey diagrams, fishbone diagrams, Wardley maps, kanban boards, user journeys, deployment diagrams, dependency graphs, UML class diagrams, story maps, and database schemas . **Self-contained HTML + SVG output** — no external dependencies, no runtime rendering. **Brand token onboarding** from any website for consistent styling. **Import/redraw** from `.drawio`, `.drawio.png`, `.drawio.svg`, and Mermaid `.mmd` sources . **Cross-agent installation** via marketplace commands for Codex, GitHub Copilot, Factory Droid, Claude Cowork, Pi, Kiro, OpenCode, and any Agent Skills host (`npx skills add cathrynlavery/diagram-design`) . **The reference implementation for agent-native editorial diagramming.**



- **[drawio-mcp (yohasacura)](https://pypi.org/project/drawio-mcp/)**  

  **MCP server for programmatic draw.io/diagrams.net diagram generation** (PyPI) . **The most feature-complete open-source MCP server for diagramming.** Works with GitHub Copilot (agent mode), Claude Desktop, Cursor, and any MCP-compatible client. **310+ shape presets**, **44 edge styles**, **21 color themes**. **Auto-layout engines**: Sugiyama DAG, tree, horizontal, vertical, grid, flowchart. **Smart routing** with obstacle-aware orthogonal edge routing. **Full editing** after creation — add, move, resize, delete, restyle any element. **Multi-page and multi-layer** support. **One-click cleanup** (`polish` command) that auto-fixes layout, overlaps, edges, and labels. **Import/export** existing `.drawio` files .



- **[draw.io (jgraph)](https://github.com/jgraph/drawio)**  

  **The world's most widely used open-source diagramming application** (Apache 2.0) . Started in 2005, independently owned and developed by draw.io Ltd (UK) and draw.io AG (Switzerland). **Free for everyone, no artificial scarcity, no Enterprise tier for SSO** . **Privacy-first** — app.diagrams.net stores nothing on their servers; diagrams stay on your device or chosen cloud storage . **Extensive shape libraries** covering flowchart, UML, cloud services, containers, network topology, and more . **Storage flexibility** — Google Drive, OneDrive, local desktop app, or any cloud . **Atlassian integration** for Confluence and Jira . **Note**: does not support real-time collaborative editing in this version; icon sets have Atlassian marketplace restrictions .



- **[Excalidraw](https://github.com/excalidraw/excalidraw)**  

  **Virtual whiteboard for sketching hand-drawn-like diagrams** (MIT). **The most popular open-source sketching tool** for technical diagrams, system design, and brainstorming . **Arrow binding** for connected diagrams, **multi-point lines**, **free-hand drawing**, **dark mode**, and **grid/stats** for precision . **React component package** (`@excalidraw/excalidraw`) for embedding in applications . **Gatsby plugin** for embedding diagrams as inline SVG at build time . **Self-hosting** available via Excalidraw Plus or open-source editor . **Extensive community ecosystem** — Obsidian plugins, VS Code integration, JetBrains plugin, CLI converters, and self-hosted Docker stacks .



- **[Mermaid](https://github.com/mermaid-js/mermaid)**  

  **JavaScript-based diagramming and charting from Markdown-inspired text definitions** (MIT). **90,000+ GitHub stars** . **The de facto standard for text-to-diagram in documentation** — helps documentation "catch up with development" by making diagrams modifiable and part of production scripts . **JS Open Source Awards 2019 winner** for "most exciting use of technology" . **CDN deployable** with a single script tag; npm/yarn/pnpm installable . **Mermaid Live Editor** for non-programmers . **Security consideration**: user-generated content can contain embedded malicious scripts; sanitization is an ongoing effort .



- **[PlantUML](https://plantuml.com/)**  

  **Component for quickly writing UML diagrams from text** (multiple licenses: GPLv3, LGPL, ASL, EPL, MIT) . **The most established open-source text-to-UML tool.** Supports all UML diagram types plus Ditaa, Jcckit, Sudoku, and ELK integration . **Semantic versioning** with releases like v1.2026.8 . **Java 8 version available**; GraphViz-free version under LGPL . **The standard for rigorous UML diagram generation from source.**



### Additional Strong Open-Source Options



- **[Archy (phxdev1)](https://www.npmjs.com/package/@iflow-mcp/phxdev1-archy)** — MCP server for Mermaid diagram generation from text, code, and GitHub repositories . **AI-enhanced generation** via OpenRouter/LangChain for sophisticated diagrams, code-to-diagram analysis, and diff visualization . **Repository evolution tracking** — clone and analyze Git repositories without filesystem writes, track commit history and file evolution . **Image export** to PNG, SVG, and PDF with customizable dimensions .

- **[excalidraw-converter (sindrel)](https://github.com/sindrel/excalidraw-converter)** — CLI tool for porting Excalidraw diagrams to Gliffy and draw.io .

- **[excalidraw-jetbrains-plugin (bric3)](https://github.com/bric3/excalidraw-jetbrains-plugin)** — Create or edit Excalidraw files within IntelliJ, CLion, WebStorm, GoLand .

- **[vscode-excalidraw (brijeshb42)](https://github.com/brijeshb42/vscode-excalidraw)** — Excalidraw integration for VS Code .

- **[excalidraw-self-hosted (Someone0nEarth)](https://github.com/Someone0nEarth/excalidraw-self-hosted)** — Docker-compose configuration for a fully self-hosted Excalidraw stack .

- **[system-design-templates-excalidraw (aretecode)](https://github.com/aretecode/system-design-templates-excalidraw)** — Rough shapes for rapid system design in front-end, full-stack, back-end, distributed, and product settings .

- Community **n8n** workflows for diagram generation automation and documentation pipeline integration.



**Frameworks for building custom systems**: Combine **Diagram Design** for agent-native editorial output with **drawio-mcp** for programmatic draw.io generation, **Mermaid** for text-to-diagram in documentation, **Excalidraw** for hand-drawn sketching, and **PlantUML** for rigorous UML—creating a comprehensive technical diagramming stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI diagramming tools handling proprietary architecture and system design data must comply with data protection regulations and internal security policies.

- **Open-source diagramming is mature and production-ready.** draw.io has been developed since 2005 and is the world's most widely used diagramming application . Mermaid has 90,000+ GitHub stars and is embedded in GitHub, GitLab, and countless documentation platforms . **These are genuine alternatives to Lucidchart and Visio.**

- **"Mermaid slop" is a real problem.** Diagram Design exists specifically because Mermaid's default rendering produces generic, unpolished output unsuitable for editorial and customer-facing documentation . **For professional documentation, diagram rendering quality matters.**

- **Agent-native diagramming is a new category.** Diagram Design and drawio-mcp represent a shift from "human draws diagram" to "agent generates diagram, human refines." The MCP protocol enables Claude, Copilot, and Cursor to create diagrams directly from code analysis . **This is the emerging pattern for AI-assisted architecture documentation.**

- **Text-to-diagram is the open-source sweet spot.** Mermaid and PlantUML store diagrams as text, making them version-controllable, diffable, and embeddable in production scripts . **This is fundamentally more maintainable than binary diagram files.**

- Self-hosted open-source solutions require proper security hardening, especially when rendering user-generated diagram definitions (Mermaid sanitization is an ongoing challenge ). **Validate diagram inputs from untrusted sources before rendering.**



---



**Made for technical writers, architects, and developers building transparent AI diagramming solutions.**  

Let's make AI Diagramming Tools more open, data-driven, and editorial-quality.
