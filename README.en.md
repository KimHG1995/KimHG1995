# Hyung Gyun Kim

**Backend Engineer / AI Developer Tooling / Automation**

[한국어](README.md)

I build backend systems primarily with TypeScript and NestJS.

My AI work is focused on **integrating existing coding-agent tools into real development workflows and measuring whether they actually help.**

## Selected Projects

| Project | What it solves |
| --- | --- |
| [ts-graph-tools](https://github.com/KimHG1995/ts-graph-tools) | External host and MCP registration setup for using the existing `@ttsc/graph` tool with Codex/Claude without installing it into the target repository |
| [agent-bench](https://github.com/KimHG1995/agent-bench) | Evaluates whether connecting `@ttsc/graph` to a coding agent actually helps versus file-only exploration. In one measured run, tool calls dropped while tokens and latency increased, exposing where the integration still needs work. |
| [codex-quality-setup](https://github.com/KimHG1995/codex-quality-setup) | Runs change-scoped type checks, linting, and tests to verify Codex changes against explicit completion criteria |
| [PaperTrail](https://github.com/KimHG1995/papertrail) | Document generation platform with asynchronous rendering, versioning, idempotency, and audit trails |
| [LogLens](https://github.com/KimHG1995/loglens) | ClickHouse Materialized View-based backend for API traffic, latency, and error analytics |
| [NetBox Cloud Inventory](https://github.com/KimHG1995/netbox-cloud-inventory) | Infrastructure inventory PoC that normalizes AWS and NAVER Cloud assets into a common model |
| [Work History](https://github.com/KimHG1995/work-history) | Engineering records covering problems, responsibilities, implementation decisions, and outcomes |

## AI Developer Tooling

I am working on the integration and evaluation layer around existing AI developer tools.

```text
Explore repository
  ↓
Connect MCP / code-graph tools
  ↓
Coding Agent implements a change
  ↓
Typecheck / Lint / Test verifies it
  ↓
Agent Eval measures whether the tooling helped
```

Current work includes:

- MCP hosting and integration around `@ttsc/graph`
- repository context for coding agents
- change-scoped automated verification
- agent evaluation and repeated experiments
- tool-call, token, and latency measurement

I am interested in making AI development workflows measurable: how existing tools are integrated, where they help, and where they add cost.

## Backend

**Language / Runtime**

`TypeScript` `JavaScript` `Node.js`

**Backend**

`NestJS` `Express`

**Database / Data**

`MySQL` `PostgreSQL` `Redis` `DynamoDB` `ClickHouse`

**Cloud / Infrastructure**

`AWS` `NAVER Cloud Platform` `Docker` `Nginx`

**Engineering**

`REST API` `Async Processing` `Observability` `Automation` `MCP`

## Experience

I currently work on backend development and operations for a public-sector education platform serving more than 1.5 million active users.

Previously, I worked on EdTech and B2B/B2C platforms across backend services, admin systems, settlement, data automation, deployment, and operational improvements. I also worked on a platform during its Series A to B growth stage, serving around 300K MAU in normal periods and up to 1M MAU at peak.

**[View Engineering Work History](https://kimhg1995.github.io/work-history/)**

---

I focus on backend systems that are reliable to operate and on tools that reduce repetitive engineering work.
