# Awesome Mate [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for [Symfony AI Mate](https://github.com/symfony/ai-mate) — the MCP server for AI-powered PHP development.

## What is Symfony AI Mate?

**Symfony AI Mate** is a [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) server that gives AI assistants deep knowledge about your PHP applications. It enables AI to understand your Symfony projects, analyze code, and provide contextual assistance.

**MatesOfMate** is the community hub for building and sharing extensions that add framework-specific, CMS-specific, or domain-specific capabilities to Symfony AI Mate.

### What Can It Do?

- 🔍 **Code Understanding** - AI analyzes your application structure, entities, services, and configurations
- 🛠️ **Smart Assistance** - Context-aware code generation, refactoring suggestions, and debugging help
- 🔌 **Extensible** - Community extensions add support for frameworks, CMSs, and libraries
- 🤖 **AI-Powered** - Works with Claude, JetBrains AI Assistant, and other MCP-compatible AI tools

---

## Quick Start

```bash
# Install Symfony AI Mate
composer require --dev symfony/ai-mate

# Start the MCP server
vendor/bin/mate serve

# Install official extensions
composer require --dev symfony/ai-symfony-mate-extension
composer require --dev symfony/ai-monolog-mate-extension

# Install community extensions (optional)
composer require --dev matesofmate/phpunit-extension

# Discover available tools
vendor/bin/mate discover

# Configure your AI assistant to connect to the MCP server
# See Integration Guide: https://symfony.com/doc/current/ai/components/mate/integration.html
```

---

## Contents

- [Official Resources](#official-resources)
- [Extensions](#extensions)
  - [CMS](#cms)
  - [Frameworks](#frameworks)
  - [Libraries](#libraries)
- [Development Tools](#development-tools)
  - [Testing](#testing)
  - [Static Analysis](#static-analysis)
- [Extension Development](#extension-development)
- [Tools & Integrations](#tools--integrations)
  - [MCP-Compatible AI Assistants](#mcp-compatible-ai-assistants)
  - [MCP Ecosystem](#mcp-ecosystem)
  - [Related AI Tools](#related-ai-tools)
- [Articles & Tutorials](#articles--tutorials)
- [Videos](#videos)
- [Community](#community)
- [Contributing](#contributing)

---

## Official Resources

- [symfony/ai-mate](https://github.com/symfony/ai-mate) - Official MCP server implementation
- [Symfony AI Documentation](https://symfony.com/doc/current/ai/index.html) - Complete guide to Symfony AI components
- [AI Mate Component Guide](https://symfony.com/doc/current/ai/components/mate.html) - Detailed Mate documentation
- [Integration Guide](https://symfony.com/doc/current/ai/components/mate/integration.html) - Setup with Claude, JetBrains, and other AI assistants
- [Creating Extensions](https://symfony.com/doc/current/ai/components/mate/creating-extensions.html) - Build your own MCP extensions
- [symfony/ai](https://github.com/symfony/ai) - Symfony AI components for embeddings, LLM integrations, and more
- [symfony/ai-demo](https://github.com/symfony/ai-demo) - Demo application showcasing Symfony AI capabilities

---

## Extensions

Community-built extensions that add framework-specific, CMS-specific, or domain-specific tools and resources.

### CMS

*No extensions yet. Want to contribute? Check out the [extension-template](https://github.com/matesofmate/extension-template)!*

<!-- Want to add your CMS extension? Examples we'd love to see:
- Sulu CMS - Content types, webspaces, and admin introspection
- WordPress integration
- Drupal extension
- TYPO3 tools
-->

### Frameworks

- [symfony/ai-symfony-mate-extension](https://packagist.org/packages/symfony/ai-symfony-mate-extension) - Official Symfony framework integration tools and resources

<!-- Want to add your framework extension? Examples we'd love to see:
- API Platform - REST/GraphQL API discovery and schema tools
- EasyAdmin - Admin panel introspection and configuration
- Sylius - E-commerce platform entity and workflow tools
- Laravel - Cross-framework PHP support
-->

### Libraries

- [symfony/ai-monolog-mate-extension](https://packagist.org/packages/symfony/ai-monolog-mate-extension) - Official Monolog logging integration for log analysis and debugging

<!-- Want to add your library extension? Examples we'd love to see:
- Doctrine - Advanced entity schema, migration, and query tools
- Messenger - Queue, handler, and transport introspection
- Workflow - State machine and workflow analysis
- Validator - Validation constraint discovery
-->

---

## Development Tools

MCP extensions for testing, static analysis, and code quality tools.

### Testing

- [matesofmate/phpunit-extension](https://packagist.org/packages/matesofmate/phpunit-extension) - PHPUnit testing tools with test discovery and token-optimized output

<!-- Want to add your testing tool extension? Examples we'd love to see:
- Behat - BDD testing and scenario tools
- Codeception - Acceptance, functional, and unit testing
- PHPSpec - Specification-based testing
-->

### Static Analysis

- [matesofmate/phpstan-extension](https://packagist.org/packages/matesofmate/phpstan-extension) - PHPStan static analysis with error reporting and token-optimized output

<!-- Want to add your static analysis extension? Examples we'd love to see:
- Psalm - Alternative static analysis tool
- PHP CS Fixer - Code style analysis and fixing
- Rector - Automated refactoring and modernization
- PHP_CodeSniffer - Code standards checking
-->

---

## Extension Development

Want to build your own Symfony AI Mate extension?

### Getting Started

1. **Use the Template** - Start from [extension-template](https://github.com/matesofmate/extension-template)
2. **Read the Guide** - Follow the [Creating Extensions](https://symfony.com/doc/current/ai/components/mate/creating-extensions.html) documentation
3. **Submit Your Extension** - Share it with the community via [issue submission](https://github.com/matesofmate/.github/issues)

### Resources

- [Extension Template](https://github.com/matesofmate/extension-template) - Starter template with examples
- [Contributing Guidelines](https://github.com/matesofmate/.github/blob/main/CONTRIBUTING.md) - Standards and best practices
- [MatesOfMate Organization](https://github.com/matesofmate) - Browse existing extensions

---

## Tools & Integrations

### MCP-Compatible AI Assistants

AI assistants with native Model Context Protocol support:

- [Claude Desktop](https://claude.ai/download) - Desktop application with built-in MCP support for AI conversations
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Command-line interface for autonomous AI-powered development
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) - IDE-integrated AI with MCP support for PhpStorm, IntelliJ, and more

### MCP Ecosystem

Core MCP protocol resources and tools:

- [Model Context Protocol](https://modelcontextprotocol.io/) - Official protocol specification and documentation
- [MCP Specification](https://github.com/modelcontextprotocol/specification) - Technical specification on GitHub
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - Official reference server implementations
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Debug and test MCP servers during development
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Build MCP servers and clients in TypeScript
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Build MCP servers and clients in Python

---

## Articles & Tutorials

*Know a great article? [Submit a PR](https://github.com/matesofmate/awesome-mate/pulls)!*

<!-- Example format:
- [Getting Started with Symfony AI Mate](https://example.com) - Beginner's guide to AI-assisted PHP development
- [Building MCP Extensions](https://example.com) - Tutorial on creating custom Symfony AI Mate extensions
- [AI-Powered Symfony Development](https://example.com) - Advanced workflows and best practices
-->

---

## Videos

*Know a great video? [Submit a PR](https://github.com/matesofmate/awesome-mate/pulls)!*

<!-- Example format:
- [SymfonyCon 2025: AI-Powered Development](https://youtube.com/...) - Conference talk introducing Symfony AI
- [Building with Symfony AI Mate](https://youtube.com/...) - Screencast demonstrating MCP integration
- [Creating MCP Extensions](https://youtube.com/...) - Tutorial on extension development
-->

---

## Community

Connect with the Symfony AI Mate and MatesOfMate community:

- 🐙 [MatesOfMate GitHub](https://github.com/matesofmate) - Browse extensions and contribute
- 💼 [Symfony Slack #ai-initiative](https://symfony.com/slack) - Chat with the Symfony AI community

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) for details on:

- 📝 Adding resources to this list
- 🔍 Quality standards for submissions
- ✅ Review process and requirements

**TL;DR**: Search for duplicates, use the format `[Name](url) - Description`, keep descriptions objective and concise, submit a PR.

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This work is licensed under the MIT License.

---

*"Because every Mate needs Mates"* 🤝
