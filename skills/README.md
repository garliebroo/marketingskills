# Marketing Skills

A curated collection of marketing skills and frameworks for Claude AI. This repository contains skills that help with marketing strategy, copywriting, SEO, social media, and more.

## What are Skills?

Skills are structured prompts and workflows that extend Claude's capabilities for specific marketing tasks. Each skill is defined in a JSON file and can be installed via the Claude plugin marketplace.

## Available Skills

| Skill | Category | Description |
|-------|----------|-------------|
| Coming soon... | — | — |

## Contributing a Skill

Want to add a new marketing skill? We'd love your contribution!

### Skill Categories

- **copywriting** — Ad copy, email copy, landing pages, CTAs
- **seo** — Keyword research, meta descriptions, content optimization
- **social-media** — Post templates, campaign planning, engagement strategies
- **analytics** — Reporting, KPI tracking, data interpretation
- **strategy** — Go-to-market, positioning, competitive analysis
- **content** — Blog posts, content calendars, editorial planning
- **email** — Drip campaigns, newsletters, subject lines
- **paid-ads** — Google Ads, Meta Ads, campaign structure

### How to Submit

1. Fork this repository
2. Create a new JSON file in the `skills/` directory following the [skill schema](#skill-schema)
3. Open a pull request using the **New Skill** template
4. Wait for review and approval

### Skill Schema

Each skill file should follow this structure:

```json
{
  "id": "unique-skill-id",
  "name": "Human Readable Name",
  "description": "Short description of what this skill does",
  "category": "copywriting",
  "version": "1.0.0",
  "author": "your-github-username",
  "prompt": "The system prompt or instruction set for this skill",
  "examples": [
    {
      "input": "Example user input",
      "output": "Expected output example"
    }
  ],
  "tags": ["tag1", "tag2"]
}
```

## License

MIT — see [LICENSE](../LICENSE) for details.
