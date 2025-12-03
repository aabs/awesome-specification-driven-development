# Awesome Specification Driven Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and resources for Specification Driven Development (SDD) - the practice of creating software by starting with specifications and using them to drive the entire development process.

Specification Driven Development emphasizes creating clear, executable specifications first, then using these specifications to generate code, tests, documentation, and other artifacts. This approach ensures consistency, reduces bugs, and improves collaboration between teams.

## Contents

- [Popular Frameworks](#popular-frameworks)
- [Theory and Methodologies](#theory-and-methodologies)
- [Agentic Programming](#agentic-programming)
- [MCP Servers](#mcp-servers)
- [IDE Support](#ide-support)
- [Blog Posts](#blog-posts)
- [Community](#community)
- [Contract Testing](#contract-testing)
- [API-First Tools](#api-first-tools)
- [Contributing](#contributing)

## Popular Frameworks

### Specification-First Development Frameworks

- **[GitHub Spec-Kit](https://github.com/github/spec-kit)** - A Toolkit to help you get started with Spec-Driven Development. ![GitHub stars](https://img.shields.io/github/stars/github/spec-kit)
- **[OpenSpec](https://github.com/Fission-AI/OpenSpec)** - OpenSpec aligns humans and AI coding assistants with spec-driven development so you agree on what to build before any code is written. ![GitHub stars](https://img.shields.io/github/stars/Fission-AI/OpenSpec)
- **[SpecPulse](https://github.com/specpulse/specpulse)** - Specification-Driven Development (SDD) Framework for Python. ![GitHub stars](https://img.shields.io/github/stars/specpulse/specpulse)
- **[Falcon Heavy](https://github.com/NotJustAToy/falcon-heavy)** - Framework for building app backends and microservices by specification-first API design approach based on OpenAPI Specification 3. ![GitHub stars](https://img.shields.io/github/stars/NotJustAToy/falcon-heavy)

### OpenAPI and Swagger Tools

- **[Swagger Core](https://github.com/swagger-api/swagger-core)** - Examples and server integrations for generating the Swagger API Specification, which enables easy access to your REST API. ![GitHub stars](https://img.shields.io/github/stars/swagger-api/swagger-core)
- **[Swagger TypeScript API](https://github.com/acacode/swagger-typescript-api)** - Generate the API Client for Fetch or Axios from an OpenAPI Specification. ![GitHub stars](https://img.shields.io/github/stars/acacode/swagger-typescript-api)
- **[OpenAPI TypeScript Codegen](https://github.com/ferdikoomen/openapi-typescript-codegen)** - NodeJS library that generates TypeScript or JavaScript clients based on the OpenAPI specification. ![GitHub stars](https://img.shields.io/github/stars/ferdikoomen/openapi-typescript-codegen)
- **[oapi-codegen](https://github.com/oapi-codegen/oapi-codegen)** - Generate Go client and server boilerplate from OpenAPI 3 specifications. ![GitHub stars](https://img.shields.io/github/stars/oapi-codegen/oapi-codegen)

### Behavior Driven Development (BDD)

- **[Concordion](https://github.com/concordion/concordion)** - Open source framework for Java that lets you turn a plain English description of a requirement into an automated test. ![GitHub stars](https://img.shields.io/github/stars/concordion/concordion)
- **[JGiven](https://github.com/TNG/JGiven)** - Behavior-Driven Development in plain Java. ![GitHub stars](https://img.shields.io/github/stars/TNG/JGiven)
- **[Lettuce](https://github.com/gabrielfalcao/lettuce)** - Behavior-driven-development tool for Python, inspired by Cucumber for Ruby. ![GitHub stars](https://img.shields.io/github/stars/gabrielfalcao/lettuce)
- **[Mamba](https://github.com/nestorsalceda/mamba)** - The definitive testing tool for Python. Born under the banner of Behavior Driven Development (BDD). ![GitHub stars](https://img.shields.io/github/stars/nestorsalceda/mamba)

## Theory and Methodologies
- **[Augmented Coding Patterns](https://lexler.github.io/augmented-coding-patterns/)** - A collection of emerging patterns, anti-patterns and obstacles for effective AI-augmented software development.
- **[A Plan-Do-Check-Act Framework for AI Code Generation](https://www.infoq.com/articles/PDCA-AI-code-generation/)**

### Core Concepts
- **Specification by Example** - A collaborative approach to defining requirements and business-oriented functional tests
- **Contract-Driven Development** - Development approach where API contracts are defined first and used to drive implementation
- **Design-First API Development** - Creating API specifications before implementation to ensure consistent design
- **Domain-Driven Design (DDD)** - Software design approach focusing on modeling software to match a domain according to input from domain experts

### Academic Resources
- **[Shriek-fx](https://github.com/ElderJames/shriek-fx)** - .NET Core framework following domain-driven design (DDD) specifications with CQRS architecture. ![GitHub stars](https://img.shields.io/github/stars/ElderJames/shriek-fx)
- **[Archived Specmatic Documentation](https://github.com/znsio/archived-specmatic-documentation)** - Turn your contracts into executable specifications. Contract Driven Development approach. ![GitHub stars](https://img.shields.io/github/stars/znsio/archived-specmatic-documentation)

## Agentic Programming

### Frameworks and Tools

- **[AgentScope](https://github.com/agentscope-ai/agentscope)** - Agent-Oriented Programming for Building LLM Applications. ![GitHub stars](https://img.shields.io/github/stars/agentscope-ai/agentscope)
- **[MetaGPT](https://github.com/FoundationAgents/MetaGPT)** - The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming. ![GitHub stars](https://img.shields.io/github/stars/FoundationAgents/MetaGPT)
- **[Microsoft AutoGen](https://github.com/microsoft/autogen)** - A programming framework for agentic AI. ![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen)
- **[Langroid](https://github.com/langroid/langroid)** - Harness LLMs with Multi-Agent Programming. ![GitHub stars](https://img.shields.io/github/stars/langroid/langroid)
- **[Serena](https://github.com/oraios/serena)** - A powerful coding agent toolkit providing semantic retrieval and editing capabilities (MCP server & other integrations). ![GitHub stars](https://img.shields.io/github/stars/oraios/serena)
- **[LLM4S](https://github.com/llm4s/llm4s)** - Agentic and LLM Programming in Scala. ![GitHub stars](https://img.shields.io/github/stars/llm4s/llm4s)

### Specification-Driven Agent Development

- **[DafnckMachine - AGF 2.0](https://github.com/DafnckStudio/DafnckMachine---AGF-2.0)** - Agentic Coding Framework powered by Pheromind – a revolutionary system designed to orchestrate fully autonomous, specification-driven software development. ![GitHub stars](https://img.shields.io/github/stars/DafnckStudio/DafnckMachine---AGF-2.0)

## MCP Servers

- **[Awesome MCP Servers](https://github.com/wong2/awesome-mcp-servers)** - A curated list of Model Context Protocol (MCP) servers. ![GitHub stars](https://img.shields.io/github/stars/wong2/awesome-mcp-servers)
- **[Awesome MCP Servers (Alternative)](https://github.com/appcypher/awesome-mcp-servers)** - Another curated list of Model Context Protocol servers with extensive collection. ![GitHub stars](https://img.shields.io/github/stars/appcypher/awesome-mcp-servers)
- **[MCP Registry](https://github.com/modelcontextprotocol/registry)** - A community driven registry service for Model Context Protocol (MCP) servers. ![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/registry)
- **[Context7](https://github.com/upstash/context7)** - Up-to-date code documentation for LLMs and AI code editors  ![GitHub stars](https://img.shields.io/github/stars/upstash/context7)
- **[Excel MCP Server](https://github.com/haris-musa/excel-mcp-server)** - A Model Context Protocol server for Excel file manipulation. ![GitHub stars](https://img.shields.io/github/stars/haris-musa/excel-mcp-server)
- **[Qdrant MCP Server](https://github.com/qdrant/mcp-server-qdrant)** - An official Qdrant Model Context Protocol (MCP) server implementation. ![GitHub stars](https://img.shields.io/github/stars/qdrant/mcp-server-qdrant)
- **[Exa MCP Server](https://github.com/exa-labs/exa-mcp-server)** - Exa Web Search API MCP (Model Context Protocol) server. ![GitHub stars](https://img.shields.io/github/stars/exa-labs/exa-mcp-server)
- **[Markdownify MCP](https://github.com/zcaceres/markdownify-mcp)** - A Model Context Protocol server for converting almost anything to Markdown. ![GitHub stars](https://img.shields.io/github/stars/zcaceres/markdownify-mcp)
- **[ArXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server)** - A Model Context Protocol server for searching and analyzing arXiv papers. ![GitHub stars](https://img.shields.io/github/stars/blazickjp/arxiv-mcp-server)
- **[Microsoft MCP](https://github.com/microsoft/mcp)** - Catalog of official Microsoft MCP (Model Context Protocol) server implementations for AI-powered data access and tool integration. ![GitHub stars](https://img.shields.io/github/stars/microsoft/mcp)
- **[Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server)** - Model Context Protocol (MCP) server for Kubernetes and OpenShift. ![GitHub stars](https://img.shields.io/github/stars/containers/kubernetes-mcp-server)

## IDE Support

### VSCode Extensions
- **Swagger Viewer** - Preview Swagger/OpenAPI specifications in VSCode
- **OpenAPI (Swagger) Editor** - Edit OpenAPI specifications with validation and preview
- **REST Client** - Send HTTP requests and view responses directly in VSCode

### JetBrains IDEs
- **OpenAPI Specifications** - Built-in support for OpenAPI specification editing and validation
- **HTTP Client** - Built-in HTTP client for testing APIs defined in specifications

### Specialized Tools
- **Stoplight Studio** - Visual OpenAPI specification editor
- **Insomnia Designer** - Collaborative API design platform
- **Postman** - API development environment with specification support

## Blog Posts & Videos

### Getting Started
- [API-First Development: Benefits and Best Practices](https://swagger.io/blog/api-development/api-first-development/)
- [Contract-Driven Development: A Guide](https://docs.pact.io/getting_started/what_is_pact)
- [Specification by Example: An Introduction](https://gojko.net/books/specification-by-example/)
- [Spec-driven development: Using Markdown as a programming language when building with AI](https://github.blog/ai-and-ml/generative-ai/spec-driven-development-using-markdown-as-a-programming-language-when-building-with-ai/)

### Advanced Topics
- [Building Microservices with Contract Testing](https://martinfowler.com/articles/microservice-testing/)
- [Domain-Driven Design and Specification Patterns](https://martinfowler.com/bliki/SpecificationPattern.html)
- [Behavior-Driven Development in Practice](https://cucumber.io/blog/bdd/bdd-vs-tdd/)
- [Chris Yaowen Zhang - The limits of specification driven development](https://dev.to/chrisywz/the-limits-of-spec-driven-development-3b16)

## Community

### Forums and Discussion
- **[OpenAPI Community](https://community.openapis.org/)** - Official OpenAPI specification community
- **[Pact Foundation](https://docs.pact.io/pact_broker/overview)** - Consumer-driven contract testing community
- **[BDD Community](https://cucumber.io/blog/community/)** - Behavior-driven development discussions

### Conferences and Events
- **API World** - Annual API development conference
- **OpenAPI Initiative Meetups** - Local meetups for OpenAPI enthusiasts
- **BDD Exchange** - Conference focused on behavior-driven development

## Contract Testing

### Pact Ecosystem
- **[Pact JVM](https://github.com/pact-foundation/pact-jvm)** - JVM version of Pact for consumer driven contract testing. ![GitHub stars](https://img.shields.io/github/stars/pact-foundation/pact-jvm)
- **[Pact Ruby](https://github.com/pact-foundation/pact-ruby)** - Ruby implementation providing a mock service and DSL for consumer-driven contract testing. ![GitHub stars](https://img.shields.io/github/stars/pact-foundation/pact-ruby)
- **[Pact .NET](https://github.com/pact-foundation/pact-net)** - .NET version of Pact for consumer driven contract testing. ![GitHub stars](https://img.shields.io/github/stars/pact-foundation/pact-net)
- **[Pact Python](https://github.com/pact-foundation/pact-python)** - Python version of Pact enabling consumer driven contract testing. ![GitHub stars](https://img.shields.io/github/stars/pact-foundation/pact-python)
- **[Pact PHP](https://github.com/pact-foundation/pact-php)** - PHP version of Pact for consumer driven contract testing. ![GitHub stars](https://img.shields.io/github/stars/pact-foundation/pact-php)

### Contract Testing Resources
- **[Awesome Contract Testing](https://github.com/lirantal/awesome-contract-testing)** - Awesome resources for Consumer-Driven Contract Testing. ![GitHub stars](https://img.shields.io/github/stars/lirantal/awesome-contract-testing)

## API-First Tools

### Design and Specification
- **[Panacloud CLI](https://github.com/panacloud/cli)** - Uses the design-first approach for developing APIs, generating Modern Multi-Tenant Serverless Cloud API infrastructure. ![GitHub stars](https://img.shields.io/github/stars/panacloud/cli)
- **[API Codeflow Node.js](https://github.com/RepreZen/API-Codeflow-Node.js)** - Build and evolve a REST API design-first with OpenAPI-Generator and Node.js. ![GitHub stars](https://img.shields.io/github/stars/RepreZen/API-Codeflow-Node.js)

### Code Generation
- **[Swagger JSDoc](https://github.com/Surnet/swagger-jsdoc)** - Generates swagger/openapi specification based on jsDoc comments and YAML files. ![GitHub stars](https://img.shields.io/github/stars/Surnet/swagger-jsdoc)
- **[ApiSpec](https://github.com/marshmallow-code/apispec)** - A pluggable API specification generator supporting OpenAPI Specification. ![GitHub stars](https://img.shields.io/github/stars/marshmallow-code/apispec)
- **[OpenAPI Diff](https://github.com/OpenAPITools/openapi-diff)** - Utility for comparing two OpenAPI specifications. ![GitHub stars](https://img.shields.io/github/stars/OpenAPITools/openapi-diff)

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### How to Contribute
1. Fork this repository
2. Add your awesome resource to the appropriate section
3. Ensure the resource follows the format: `**[Name](link)** - Description. ![GitHub stars](shield-url)`
4. Submit a pull request

### Criteria for Inclusion
- Resource must be related to specification-driven development
- Active maintenance and community support
- Clear documentation and examples
- Open source preferred (but not required for learning resources)
