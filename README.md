## Lewis Olden

I build production AI systems inside real businesses and own them end to end: from the first conversation with the operator, through the data, the agent loop and the evals, to the interface people use every day.

I run an investment firm managing CEE equity funds, so I come at AI from the operator's side. I know what it takes for a system to be trusted with real money and real decisions, and I build to that bar. Over the past year I've shipped agentic platforms for my own firm and for clients across finance, media, music and healthcare, working embedded with each team.

### Systems I've shipped

**Fund operations platform with a Claude research agent** · *my own firm*  
Runs two funds day to day. It ingests messy administrator packs (Excel, PDFs, broker tickets), reconciles positions, repo financing, collateral and NAV against them, and marks the book live. The Claude-powered research agent sits on top with an eval dataset and test suite in CI. It sends an automated daily P&L and weekly investor report, all of it fully derived from source tables. Security includes MFA, row-level security and an audit log.

**Agent orchestration platform** · *AI services firm*  
A monorepo running a dedicated orchestrator service, agent surfaces for staff and clients, an evals dashboard and a written agent-quality standard. OpenTelemetry tracing and AWS infrastructure are defined in CDK.

**Agent desk with a cost-aware model gateway** · *AI services firm*  
An internal operating desk where agents propose actions for human approval. It routes calls through a gateway with per-agent budgets and cost tracking, covered by tests.

**Artist operating system** · *music and media*  
An AWS-native rebuild on Lambda, API Gateway, RDS, SQS and EventBridge. It runs an agent registry with structured outputs that powers career-planning, daily-plan and creative agents for artists.

**Leadership operations platform** · *client engagement*  
Covers reporting across performance, people, commercial, finance and legal, plus the revenue pipeline. Claude agents run on events and schedules, for example a weekly leadership brief and a partnership scout.

Other builds include a cultural intelligence subscription product with research agents, and a compliance platform for a CQC-regulated remote healthcare provider.

### How I work

- **Evals and observability from day one.** I don't ship an agent I can't measure.
- **Prototype to production fast**, using Claude Code and the latest models the week they land.
- **Comfortable in messy data and other people's systems:** APIs, SQL and spreadsheets nobody else wants to touch.
- **Equally at home with an investment committee and a codebase.**

### Stack

TypeScript · Next.js · React · Node.js · Claude API · agents and tool use · evals · PostgreSQL / Supabase · SQL · AWS (Lambda, CDK, RDS, SQS, EventBridge) · Vercel · OpenTelemetry · GitHub Actions

### Note

My work is proprietary or for clients, so those repositories are private. I'm happy to walk through the architecture, code and outcomes of any of these in conversation.
