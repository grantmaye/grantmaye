# Grant Maye

I build web applications and tools that make operational work easier to inspect: clear interfaces, explicit business rules, and tests for the ways a workflow can fail.

These public projects focus on React and Next.js interfaces, Node.js APIs, relational data, and Python tooling. Each featured application includes local run instructions, implementation notes, and test coverage to explore.

## Start with these three

| Project | What it does | Engineering focus |
| --- | --- | --- |
| [Fulfillment Routing Engine](https://github.com/grantmaye/Fulfillment-Routing-Engine#readme) | Compare warehouses, reserve stock, explain decisions, and handle overrides and cancellation. | Next.js · TypeScript · GraphQL · PostgreSQL transactions |
| [Inspect / QA Dashboard](https://github.com/grantmaye/QA-Dashboard#readme) | Scan sample websites, review evidence, assign findings, and retain triage history across scans. | Next.js · GraphQL · background jobs · PostgreSQL · DataLoader |
| [Evaluation Explorer](https://github.com/grantmaye/Course-Evaluation-Explorer#readme) | Explore fictional course evaluations and compare equivalent reporting queries. | React · Node.js · SQL Server procedures · portable SQLite preview |

For a quick review, open a README screenshot and walkthrough. For a deeper review, follow its architecture and test links, then run the local demo. These are independent portfolio projects with fictional data and documented limits; the local previews do not require paid services.

## More focused tools

- [Webhook Reliability Lab](https://github.com/grantmaye/Webhook-Reliability-Lab#readme) — Node.js receiver and Python client demonstrating signed requests, retries, and durable duplicate handling.
- [Catalog Sync API](https://github.com/grantmaye/Catalog-Sync-API#readme) — Validate supplier feeds, import atomically, and preserve product change history with Node.js and SQLite.
- [photo-toolkit](https://github.com/grantmaye/photo-toolkit#readme) — Python CLI for inspecting and organizing media libraries, with dry runs and reviewable execution plans. Currently alpha.

## What to look for in the code

- **Correctness when requests repeat or compete:** stock reservations, import replay handling, and webhook deduplication.
- **Interfaces that explain state:** evidence, review queues, empty/error states, and visible decision history.
- **Verifiable behavior:** service tests, database integration checks, and browser workflows, with current results linked in each repository.

[LinkedIn](https://www.linkedin.com/in/grantmaye/)
