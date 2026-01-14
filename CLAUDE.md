# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is **awesome-mate** - a curated list of resources for Symfony AI Mate and the MCP ecosystem. It follows the [Awesome List](https://github.com/sindresorhus/awesome) format and standards.

## Repository Type

This is a **resource curation repository**, not a code repository. Users contribute by:
- Adding links to relevant resources
- Organizing content into categories
- Maintaining quality standards for listed resources

## Structure

```
awesome-mate/
├── README.md           # Main awesome list with all resources
├── CONTRIBUTING.md     # Contribution guidelines
└── [documentation]     # CLAUDE.md, AGENTS.md
```

### README.md Sections

1. **Official Resources** - Symfony AI Mate core documentation and repositories
2. **Extensions** - MatesOfMate community extensions
   - CMS (Sulu, etc.)
   - Frameworks (API Platform, EasyAdmin, etc.)
   - Libraries (Doctrine, Messenger, etc.)
3. **Tools & Integrations** - AI assistants and MCP ecosystem tools
4. **Articles & Tutorials** - Blog posts, guides, tutorials
5. **Videos** - Conference talks, screencasts, demos
6. **Community** - Discussion forums, chat channels

## Maintenance Tasks

### Adding a New Extension

When a new MatesOfMate extension is published:

1. Add to appropriate category (CMS/Frameworks/Libraries)
2. Use format: `[matesofmate/{name}-extension](link) - Brief description`
3. Keep description under 100 characters
4. Alphabetize within category if multiple entries exist

### Adding Resources

Format for different resource types:

**Extensions**:
```markdown
- [matesofmate/sulu-extension](https://github.com/matesofmate/sulu-extension) - Sulu CMS tools for content types and webspaces
```

**Articles**:
```markdown
- [Article Title](https://example.com) - Brief description of content
```

**Videos**:
```markdown
- [Video Title](https://youtube.com/...) - Conference/channel name and brief description
```

**Tools**:
```markdown
- [Tool Name](https://example.com) - What it does and why it's useful
```

## Quality Standards

Resources added must be:

- **Relevant** - Directly related to Symfony AI Mate, MCP, or AI-assisted PHP development
- **Maintained** - Actively maintained and currently working
- **Documented** - Has clear documentation or instructions
- **Useful** - Provides genuine value to the community

### What to Accept

✅ Official Symfony AI documentation
✅ MatesOfMate community extensions
✅ MCP protocol resources
✅ AI assistant integrations supporting MCP
✅ Tutorials about using Symfony AI Mate
✅ Conference talks about AI-assisted development
✅ Tools that enhance MCP development workflow

### What to Reject

❌ Generic PHP resources not related to AI/MCP
❌ Abandoned or unmaintained projects
❌ Duplicate entries
❌ Self-promotional content without value
❌ Resources without documentation
❌ Broken or non-functional links

## Formatting Guidelines

### Link Format
```markdown
[Resource Name](url) - Description
```

### Description Guidelines
- Start with capital letter
- No period at the end (unless multiple sentences)
- Be objective and factual
- Avoid superlatives ("amazing", "best", "awesome")
- Keep under 100 characters
- Focus on what it does, not opinion

### Category Organization

- Alphabetize entries within categories when there are 3+ items
- Create new categories when there are 3+ related items
- Keep category names clear and specific
- Use existing awesome-list conventions

## Common Operations

### Verifying Links

Before adding or when reviewing:
```bash
# Check if link is accessible (manual verification preferred)
curl -I https://example.com
```

### Checking for Duplicates

Search README.md for:
- Similar resource names
- Same URLs
- Related content in different categories

### Updating Broken Links

When a link breaks:
1. Try to find the new location
2. Update URL if resource moved
3. Remove entry if resource is gone and no archive exists
4. Consider adding archived version if historically important

## Awesome List Standards

Follow official awesome-list guidelines:
- Include awesome badge in README
- Maintain CONTRIBUTING.md
- Keep list focused and curated
- Quality over quantity
- Review PRs for quality
- Remove dead/unmaintained resources

## Commit Message Convention

**Important**: Keep commit messages clean without AI attribution.

**Format**:
```
Short summary (50 chars or less)

- Conceptual change description
- Another concept or improvement
- More changes as needed
```

**✅ Good Examples**:
```
Add MCP debugging tools section

- Include MCP Inspector
- Add server testing utilities
- Reference development tools
```

```
Expand Symfony AI Mate tutorials

- Add getting started guides
- Include integration tutorials
- Reference best practices articles
```

**❌ Bad Examples**:
```
Update README.md

Co-Authored-By: Claude Code <noreply@anthropic.com>
```

```
Add resources - coded by claude-code
```

**Rules**:
- ❌ NO AI attribution (no "Co-Authored-By: Claude", "coded by claude-code", etc.)
- ✅ Short, descriptive summary line
- ✅ Bullet list describing concepts/improvements, not file names
- ✅ Natural language explaining what changed
- ✅ Focus on the WHY and WHAT, not technical details

## Cross-Repository Awareness

When extensions are added to this list, ensure:
- Extension exists in MatesOfMate organization
- Extension is published on Packagist
- Extension has proper README and documentation
- Extension follows MatesOfMate quality standards (see .github repository)
