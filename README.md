# Hi, I'm Joel Martinez

**GTM engineer. I turn public hiring and funding signals into pipeline, with small, testable tools instead of another SaaS seat.**

Independent at [pushtomain.xyz](https://pushtomain.xyz).

## What I build

| Project | What it does | Stack |
|---|---|---|
| [**connie**](https://github.com/saiwrd/connie) | Hiring-signal scanner for Ashby, Greenhouse, Lever and Workable. Remembers every posting in a SQLite Registry (`first_seen` / `last_seen` / `closed_at`), so a scheduled run becomes a "who started hiring for what, today" feed. | Go, SQLite |
| **Merlin** | Funding-signal engine on Cloudflare: watches public SEC Form D filings, enriches companies, scores ICP fit with an LLM agent, serves a ranked dashboard. Sanitized public version coming. | Workers, Workflows, D1, Workers AI |
| **Lamplighter** | Passive tech-stack fingerprinting for any domain (headers, HTML markers, public DNS) plus a two-sentence "how to sell to them" read. | Workers, Workers AI |

Also: forks I actually use, with upstream credited and my changes listed in each README: [context-sync](https://github.com/saiwrd/context-sync), [llm-council](https://github.com/saiwrd/llm-council), [clickup-cli](https://github.com/saiwrd/clickup-cli) (MCP).

## Stack

`Go` · `TypeScript` · `SQLite` · `MCP` · Cloudflare Workers/D1 · GitHub Actions

## How I work

- Public, unauthenticated data sources only; identify yourself in the User-Agent; back off on 429s.
- Conservative state machines over clever heuristics (see connie's Registry lifecycle rules, each pinned by a test).
- Tests run offline against recorded fixtures.

## Contact

- Web: [pushtomain.xyz](https://pushtomain.xyz)
- Email: joel@pushtomain.xyz
