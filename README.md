# OWASP AI Top 10 Comparator

Interactive tool that lays all five OWASP AI security Top 10 lists side by side so you can see where they overlap, where the gaps are, and which ones matter for your stack.

Live at [owaspai.matt-adams.co.uk](https://owaspai.matt-adams.co.uk)

## Lists covered

| List | Status | Version |
|------|--------|---------|
| [LLM Applications Top 10](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/) | Flagship | 2026 |
| [Agentic Applications Top 10](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) | Peer-reviewed | 2026 |
| [MCP Top 10](https://owasp.org/www-project-mcp-top-10/) | Beta | v0.1 |
| [Agentic Skills Top 10](https://owasp.org/www-project-agentic-skills-top-10/) | New project | 2026 |
| [ML Security Top 10](https://owasp.org/www-project-machine-learning-security-top-10/) | Incubator | v0.3 |

## Features

- **Relevance quiz** - tick what you're building and what concerns you to get personalised relevance scores
- **Maturity comparison** - see which lists are battle-tested and which are still in beta
- **Overlap matrix** - find where lists agree on the same risk themes
- **Risk cards** - browse all 50 risks with cross-references to related items in other lists
- **Gap analysis** - discover what each list uniquely covers and where it goes quiet

## Running locally

It's a single `index.html` file with no build step or dependencies. Open it in a browser.

```sh
open index.html
```

## Deployment

Deployed on [Vercel](https://vercel.com).

## Disclaimer

Built from OWASP project data. Not affiliated with OWASP Foundation.
