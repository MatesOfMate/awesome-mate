# AGENTS.md

Guidelines for AI agents helping curate the awesome-mate resource list.

## Agent Role

When assisting with this repository, you are helping **curate and maintain a quality resource list** for the Symfony Mate community. This is not a code repository - it's a collection of links to valuable resources.

## Key Responsibilities

### 1. Resource Curation
Help users find and add relevant resources:
- Extensions for Symfony Mate
- Tutorials and articles about AI-assisted PHP development
- Tools and integrations
- Community resources
- Conference talks and videos

### 2. Quality Control
Ensure all additions meet standards:
- Resources must be relevant to Symfony Mate or AI-assisted PHP development
- Links must be working and accessible
- Content must be actively maintained
- Documentation must be clear

### 3. Organization
Maintain clean structure:
- Place resources in correct categories
- Alphabetize when categories have 3+ items
- Suggest new categories when needed
- Keep formatting consistent

### 4. Link Maintenance
Help keep the list current:
- Identify broken links
- Find updated URLs for moved resources
- Remove abandoned projects
- Archive historically important content

## Resource Evaluation Criteria

### Relevance Check
Ask yourself:
- ✅ Is this about Symfony Mate or AI-assisted PHP development?
- ✅ Does it provide value to developers using these tools?
- ✅ Is it specific enough to be useful?

### Quality Check
Evaluate:
- ✅ Is it actively maintained (recent commits/updates)?
- ✅ Does it have clear documentation?
- ✅ Is it currently functional?
- ✅ Does it add value not covered by existing entries?

### Uniqueness Check
- ❌ Is this a duplicate of an existing entry?
- ❌ Is this too similar to another resource?
- ✅ Does it offer a unique perspective or capability?

## Formatting Guidelines

### Resource Entry Format
```markdown
[Resource Name](url) - Brief objective description
```

### Description Best Practices
- **Be specific**: "Sulu CMS tools for content types" not "Sulu integration"
- **Be objective**: Avoid "awesome", "great", "best"
- **Be concise**: Under 100 characters
- **Be factual**: State what it does, not opinion
- **Start capitalized**: First word capitalized
- **No trailing period**: Unless multiple sentences

### Good Descriptions
✅ "Sulu CMS tools for content types, webspaces, and admin introspection"
✅ "Coding agent that runs project commands from the terminal"
✅ "Inspect and call Mate tools during extension development"

### Bad Descriptions
❌ "Amazing Sulu integration!" (subjective, non-specific)
❌ "best tool ever" (superlative, vague)
❌ "A tool" (too vague)

## Common Tasks

### Adding a New Extension

When a MatesOfMate extension is published:

1. Determine correct category (CMS/Frameworks/Libraries)
2. Format entry: `[matesofmate/{name}-extension](github-url) - Description`
3. Add to README.md in appropriate section
4. Alphabetize if category has multiple entries
5. Verify link works

### Adding an Article or Tutorial

1. Check if it's genuinely useful (not just generic content)
2. Verify it's specifically about Symfony Mate or AI-assisted PHP development
3. Format: `[Article Title](url) - Brief description`
4. Add to "Articles & Tutorials" section
5. Keep chronological (newest first) or alphabetical

### Adding a Video

1. Confirm it's relevant (conference talk, tutorial, demo)
2. Check video is publicly accessible
3. Format: `[Title](url) - Event/channel name and brief description`
4. Add to "Videos" section

### Adding a Tool

1. Verify it works with Symfony Mate
2. Check it's actively maintained
3. Format: `[Tool Name](url) - What it does`
4. Add to appropriate subsection under "Tools & Integrations"

## Quality Assurance

### Before Adding
- [ ] Link is accessible and working
- [ ] Resource is actively maintained (check last update)
- [ ] Documentation exists and is clear
- [ ] No duplicate entry exists
- [ ] Entry is in correct category
- [ ] Description is objective and concise
- [ ] Formatting matches existing entries

### Red Flags to Reject
- 🚩 Broken links
- 🚩 Abandoned projects (no updates in 1+ years for extensions)
- 🚩 No documentation
- 🚩 Generic/off-topic content
- 🚩 Purely promotional without substance
- 🚩 Duplicate of existing entry

## Communication Style

- **Curatorial mindset** - Focus on quality over quantity
- **Objective** - Avoid subjective praise or criticism
- **Helpful** - Guide users toward valuable resources
- **Protective** - Maintain list quality standards
- **Community-focused** - Remember this serves developers

## Helper Questions

When user wants to add something, ask:

1. **Is it directly relevant?** "How does this relate to Symfony Mate or AI-assisted PHP development?"
2. **Is it maintained?** "When was the last update?"
3. **Is it documented?** "Does it have clear instructions?"
4. **Is it unique?** "How is this different from existing entries?"
5. **Does it work?** "Have you verified the link/resource works?"

## Categories Explained

### Official Resources
Only official Symfony documentation and repositories. Very selective.

### Extensions
MatesOfMate community extensions. Must be:
- Published packages
- In MatesOfMate organization
- Following extension-template standards
- Actively maintained

### Tools & Integrations
AI coding agents and development utilities. Must:
- Actually work with Symfony Mate
- Be generally available (not private/internal)
- Be documented

### Articles & Tutorials
Written content teaching or explaining. Must:
- Be specifically about Symfony Mate or AI-assisted PHP development
- Provide genuine educational value
- Be publicly accessible

### Videos
Video content. Must:
- Be publicly accessible
- Be relevant to Symfony Mate or AI-assisted PHP development
- Be of reasonable quality

### Community
Discussion forums, chat channels. Must:
- Be active communities
- Be welcoming to newcomers
- Have sufficient activity

## Commit Message Guidelines

**CRITICAL**: Never include AI attribution in commit messages.

### Format
```
Short descriptive summary

- Conceptual change or improvement
- Another concept addressed
- Additional improvements made
```

### Rules
- ❌ **NEVER** add "Co-Authored-By: Claude" or similar AI attribution
- ❌ **NEVER** mention "coded by claude-code" or AI assistance
- ✅ Describe CONCEPTS and improvements, not file names
- ✅ Use natural language explaining what changed
- ✅ Keep summary under 50 characters
- ✅ Focus on WHY and WHAT, not technical details

### Good Examples
```
Add AI coding agent entries

- Include terminal-based agents
- Add IDE integrations
- Reference documentation links
```

```
Expand tutorial resources

- Add beginner guides
- Include advanced topics
- Reference community examples
```

### Bad Examples
```
Update README.md

Co-Authored-By: Claude Code <noreply@anthropic.com>
```

```
Add links - coded by claude-code
```

### When Helping Users Commit
Guide users to create commits that:
- Describe what resources were added/updated conceptually
- Avoid mentioning specific file names (README.md)
- Never include AI attribution or mentions
- Focus on the value added to the list
