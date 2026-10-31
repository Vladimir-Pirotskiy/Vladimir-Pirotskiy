### Vladimir Pirotskiy

Lead developer at a US agricultural e-commerce company. I own the storefront, the search API and the
backend services in production, and I build them with agentic engineering: AI coding agents that work
in parallel from written specs, with review agents and strict CI gates checking the result.

**Stack:** TypeScript, Next.js, React, Rust (axum), Bun, PostgreSQL, Google Cloud (Cloud Run),
GitHub Actions, Vercel

#### What I build
- **E-commerce storefront:** Next.js and React; technical SEO (structured data, crawl control,
  Core Web Vitals); Stripe checkout
- **Search:** product search API moved from TypeScript to Rust (axum) on Cloud Run
- **Platform:** TypeScript microservices behind an OpenAPI gateway, PostgreSQL, alerting, self-hosted
  CI runners
- **Internal tools:** server-rendered Rust with [Topcoat](https://github.com/tokio-rs/topcoat) in
  production

#### How I work with AI agents
- **Plan, build, verify:** a stronger model plans and writes the spec, faster models implement in
  separate git worktrees, review agents check the diff and the claims before it merges
- **Context engineering:** AGENTS.md and CLAUDE.md files, reusable skills, a curated project memory
- **Guardrails as code:** hooks that enforce git, commit and review rules; fixes ship with a regression
  test that failed before the fix
- **Cost control:** model choice per task and a token budget per run
- **Tools:** Claude Code, subagents, MCP servers

#### Open source
- [tokio-rs/topcoat](https://github.com/tokio-rs/topcoat): verify the default Tailwind CLI download
  ([#575](https://github.com/tokio-rs/topcoat/pull/575)), accessibility gaps in topcoat-ui
  ([#576](https://github.com/tokio-rs/topcoat/issues/576)), repeated form keys
  ([#573](https://github.com/tokio-rs/topcoat/issues/573))
