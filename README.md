# Awesome Postman [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for [Postman](https://www.postman.com) — the API platform for building and using APIs.
>
> Inspired by [@sindresorhus](https://github.com/sindresorhus)'s [awesome](https://github.com/sindresorhus/awesome).
>
> Your [contributions](https://github.com/dawitnida/awesome-postman/blob/master/.github/CONTRIBUTING.md) are welcome!

---

## Contents

- [Official Resources](#official-resources)
- [What's New in 2025–2026](#whats-new-in-20252026)
- [Tools & CLI](#tools--cli)
- [Libraries](#libraries)
- [Converters](#converters)
- [Newman Reporters](#newman-reporters)
- [Collections](#collections)
- [Tutorials & Blog Posts](#tutorials--blog-posts)
- [Books](#books)
- [Videos & Courses](#videos--courses)
- [CI/CD Integrations](#cicd-integrations)
- [IDE Extensions](#ide-extensions)
- [Community](#community)
- [License](#license)

---

## Official Resources

- [Postman](https://www.postman.com) - Main platform site.
- [Postman Blog](https://blog.postman.com) - Product updates, API guides, and engineering articles.
- [Postman Learning Center](https://learning.postman.com) - Comprehensive documentation and tutorials.
- [Postman Academy](https://academy.postman.com) - Interactive courses, live workshops, and certifications for all skill levels.
- [Postman API Network](https://www.postman.com/explore) - Explore thousands of public APIs and collections.
- [Postman Downloads](https://www.postman.com/downloads) - Desktop app for Mac, Windows, and Linux.
- [Postman on GitHub](https://github.com/postmanlabs) - All official open-source projects.
- [Postman YouTube Channel](https://www.youtube.com/@postman-platform) - Video tutorials, product demos, and conference talks.
- [Postman Community Forum](https://community.postman.com) - Official Q&A and discussions.
- [Release Notes](https://www.postman.com/release-notes/postman-app) - Full changelog of all app releases.

## What's New in 2025–2026

- **New Postman Platform (March 2026)** - Full relaunch built for the agentic era. Introduces the API Catalog (a live management plane for all APIs and services), Git-connected Workspaces, and a redesigned Private API Network.
- **Agent Mode** - Replaces Postbot in Postman v12. Natural-language AI interface for writing tests, generating documentation, fixing errors, building Flows, and interacting with APIs.
- **Full MCP Support** - Create and send MCP requests directly in Postman, generate MCP servers from 100,000+ APIs, and use deployed Flows as MCP tools for AI agents.
- **Flow Actions** - Deploy Flows to the cloud and trigger them via API endpoints; use deployed Flows as tools in AI agent pipelines.
- **Spec Hub** - Centralized spec management with Spectral linting, OpenAPI 3.0 and AsyncAPI 2.0 support, multi-file references, and bidirectional sync between specs and collections.
- **CLI Generator** - Generate fully functional CLI applications directly from Postman collections or OpenAPI specs.
- **Microsoft Collaboration (April 2026)** - Agent Mode now supports OpenAI models on Microsoft Foundry; Azure API Management integration is generally available; new Postman app for Microsoft Teams.
- **Fern Acquisition (January 2026)** - Postman acquired Fern to strengthen API documentation and SDK generation capabilities.
- **API Governance** - Enforce style, security, and design rules across your entire API portfolio.
- **Postman Flows** - Visual, no-code tool to chain API calls and build automated workflows.

> **Note:** As of March 2026, the free plan supports only one user. Team collaboration requires the paid Team plan.

## Tools & CLI

- [Newman](https://github.com/postmanlabs/newman) - Official command-line runner for Postman collections. Widely used in CI/CD pipelines.
- [Postman CLI](https://learning.postman.com/docs/postman-cli/postman-cli-overview) - First-party CLI with built-in Postman authentication, reporting, and performance testing support. Separate from Newman.
- [postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) - Official MCP server that connects AI assistants to your Postman APIs and workspaces.
- [postman-code-generators](https://github.com/postmanlabs/postman-code-generators) - Generate code snippets (curl, Python, Go, JavaScript, and more) from any Postman request.
- [postman-sandbox](https://github.com/postmanlabs/postman-sandbox) - Sandboxed execution environment that powers Postman pre-request and test scripts.
- [postman-request](https://github.com/postmanlabs/postman-request) - HTTP request library used internally by Postman.
- [postman-external-require](https://github.com/matt-ball/postman-external-require) - Import external Node.js packages inside Postman scripts.
- [postman-util-lib](https://joolfe.github.io/postman-util-lib) - Cryptography utility library for use in Postman pre-request scripts.

## Libraries

- [postman-collection](https://github.com/postmanlabs/postman-collection) - JavaScript SDK for working with the Postman Collection format programmatically.
- [All-Things-Postman](https://github.com/DannyDainton/All-Things-Postman) - Extensive repository of Postman examples, scripts, and patterns.

## Converters

- [openapi-to-postman](https://github.com/postmanlabs/openapi-to-postman) - Official tool to convert OpenAPI 3.x specs to Postman Collections.
- [postman-to-openapi](https://github.com/joolfe/postman-to-openapi) - Convert Postman Collections to OpenAPI 3.0 spec.
- [postman2openapi](https://github.com/kevinswiber/postman2openapi) - CLI and web tool to convert Postman 2.x collections to OpenAPI 3.0.
- [specmatic](https://specmatic.io) - Contract testing tool that works with OpenAPI specs and Postman collections.

## Newman Reporters

- [newman-reporter-html](https://github.com/postmanlabs/newman-reporter-html) - Official minimal HTML report for Newman runs.
- [newman-reporter-htmlextra](https://github.com/DannyDainton/newman-reporter-htmlextra) - Feature-rich HTML reporter with request/response detail, iteration charts, and custom handlebars templates.
- [newman-reporter-junitfull](https://github.com/martindgar/newman-reporter-junitfull) - Full JUnit XML reporter for integration with CI dashboards (Jenkins, Azure DevOps, etc.).
- [newman-reporter-allure](https://github.com/errrror/newman-reporter-allure) - Allure framework reporter for rich, visual test results.

## Collections

- [Postman Public Workspace](https://www.postman.com/postman/postman-public-workspace) - Official templates, examples, and API reference collections maintained by Postman.
- [Postman API Collection](https://www.postman.com/postman/workspace/postman-public-workspace/collection/i2uqzpp/postman-api) - Collection for interacting with the Postman REST API itself.
- [Flows Templates](https://www.postman.com/postman/postman-flows-template-workspace) - Library of 100+ Flows templates for common API workflow patterns.
- [HERE REST APIs](https://github.com/heremaps/postman-collections) - Official HERE Maps platform API collections.

## Tutorials & Blog Posts

- [Postman Blog](https://blog.postman.com) - Official articles on API design, testing, platform updates, and engineering.
- [Postman Learning Center Tutorials](https://learning.postman.com/docs/getting-started/first-steps/overview) - Step-by-step guides from basic setup to advanced scripting and automation.
- [Postman Tutorial for Beginners with API Testing Example](https://www.guru99.com/postman-tutorial.html) - Practical beginner walkthrough covering the core UI and request workflow.
- [All-Things-Postman Examples](https://github.com/DannyDainton/All-Things-Postman) - Practical collection of real-world Postman scripts and patterns.
- [End-to-End API Test Automation with Postman and GitHub Actions](https://www.velotio.com/engineering-blog/a-guide-to-end-to-end-api-test-automation-with-postman-and-github-actions) - CI/CD automation walkthrough.
- [Postman Flows: The Next Generation of Software Development](https://blog.postman.com/postman-flows-the-next-generation-of-software-development) - Conceptual introduction to Flows.
- [Full MCP Support in Postman](https://blog.postman.com/postman-launches-full-support-for-model-context-protocol-mcp-build-better-ai-agents-faster/) - How to use Postman to build and test AI agents with MCP.
- [New Postman is Here](https://blog.postman.com/new-postman-is-here/) - Overview of the March 2026 platform relaunch and the agentic-era architecture.

## Books

- [API Testing and Development with Postman, 2nd Edition](https://www.packtpub.com/en-us/product/api-testing-and-development-with-postman-9781804617908) by Dave Westerveld - Updated coverage of API testing, scripting, data-driven testing, Newman, CI integration, and security testing. (Packt, June 2024)
- [Automating and Testing a REST API](https://www.eviltester.com/page/books/automating-testing-api-book/) by Alan Richardson - Practical guide to API test automation using Postman and other tools.

## Videos & Courses

- [Postman Beginner's Course — API Testing](https://www.youtube.com/watch?v=VywxIQ2ZXw4) - Free, full beginner course on YouTube.
- [Postman Beginner Tutorial Playlist](https://www.youtube.com/playlist?list=PLhW3qG5bs-L-oT0GenwPLcJAPD_SiFK3C) - Official step-by-step series from the Postman YouTube channel.
- [Postman: The Complete Guide — REST API Testing](https://www.udemy.com/course/postman-the-complete-guide/) - Comprehensive Udemy course covering scripting, Newman, environments, and CI/CD.
- [Postman Flows Video Tutorials](https://learning.postman.com/docs/postman-flows/tutorials/video/create-first-flow) - Official video guide to building your first Flow.

## CI/CD Integrations

- [GitHub Actions](https://learning.postman.com/docs/integrations/available-integrations/ci-integrations/github-actions) - Run Postman collections in GitHub Actions workflows using the Postman CLI.
- [Jenkins](https://learning.postman.com/docs/integrations/available-integrations/ci-integrations/jenkins) - Integrate Newman or the Postman CLI into Jenkins pipelines.
- [GitLab CI/CD](https://learning.postman.com/docs/integrations/available-integrations/ci-integrations/gitlab-ci) - Run collections inside GitLab pipelines.
- [CircleCI](https://learning.postman.com/docs/integrations/available-integrations/ci-integrations/circleci) - CircleCI integration for collection runs via Newman.
- [Azure Pipelines](https://learning.postman.com/docs/integrations/available-integrations/ci-integrations/azure-pipelines) - Azure DevOps integration for automated API testing.
- [postman-cli-action](https://github.com/postmanlabs/postman-cli-action) - Official GitHub Action for running the Postman CLI in workflows.

## IDE Extensions

- [Postman for VS Code](https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode) - Official extension to send HTTP, gRPC, and WebSocket requests, manage collections and environments, and write tests without leaving the editor.
- [VS Code Extension Docs](https://learning.postman.com/docs/developer/vs-code-extension/overview) - Official documentation for the VS Code extension, including MCP server integration.

## Community

- [Postman Discord](https://discord.com/invite/bKjz3CXbB6) - Real-time community chat with 17,000+ members.
- [Postman on X / Twitter](https://x.com/getpostman) - Official account for news and platform updates.
- [Postman on LinkedIn](https://www.linkedin.com/company/postman-platform) - Professional updates and API industry content.
- [POST/CON](https://www.postman.com/postcon) - Postman's annual API conference. POST/CON 25 was held June 3–4, 2025 in Los Angeles, CA.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
