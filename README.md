### Vladimir Pirotskiy

**Lead Full-Stack Developer** · Next.js, TypeScript, Node.js and Rust · AI coding agents in production

Dubai, UAE · [pirotskiy.com](https://pirotskiy.com) · [CV](https://pirotskiy.com/cv) · [LinkedIn](https://www.linkedin.com/in/pirotskiy-vladimir/) · [YouTube](https://www.youtube.com/@pirotskiy) · [X](https://x.com/PirotskiyV)

Seven years of commercial development since 2019. At the outstaff company Abraham Int. from 2022 to
October 2026 I worked on client projects; on the last one I led development of a US agritech
e-commerce platform end to end: storefront, search API, backend services, deploys and cloud operations.

- Rust search API over 1.8M parts: p95 of full search queries cut 4.5x (2.2 s to 0.5 s, 170-query benchmark)
- Compute, hosting and CI spend cut by 64% (database excluded), phone LCP p75 from 2.5 s to 1.7 s
- 2,300+ pull requests merged in 91 days across storefront, search and services, with AI coding agents
  under review gates, test-first rules and CI
- 26K+ unit and 1,520 browser e2e tests, 63 CI workflows

That work is in the client's private repositories, so it does not show in the contribution graph here.

**Stack:** TypeScript, Next.js, React, Node.js, Rust (axum), Bun, PostgreSQL, Google Cloud Run,
Terraform, GitHub Actions, Stripe, Playwright

#### Open source

14 pull requests in 11 projects of the Rust and JavaScript ecosystems; 5 merged, 9 in review.

Merged:
- [tokio-rs/topcoat #575](https://github.com/tokio-rs/topcoat/pull/575): verify the default Tailwind CLI download against a shipped checksum
- [fallow #4038](https://github.com/fallow-rs/fallow/pull/4038): credit generateStaticParams in Next.js metadata routes
- [rolldown #11456](https://github.com/rolldown/rolldown/pull/11456): reset plugin module options when modules are fetched again in watch mode
- [tokio #8755](https://github.com/tokio-rs/tokio/pull/8755), [#8756](https://github.com/tokio-rs/tokio/pull/8756): documentation of Sleep after completion and of a kept Command's pipe writer

In review:
- [goose #13624](https://github.com/aaif-goose/goose/pull/13624): pass the tool result and the error to PostToolUse hooks
- [sqlx #4533](https://github.com/transact-rs/sqlx/pull/4533): keep the scale of NUMERIC when decoding into BigDecimal
- [Biome #13279](https://github.com/biomejs/biome/pull/13279): allow void as a type parameter constraint in noConfusingVoidType
- [napi-rs #3685](https://github.com/napi-rs/napi-rs/pull/3685): require a Send resolver in SendableResolver::new (soundness fix)
- [Next.js #101005](https://github.com/vercel/next.js/pull/101005), [#101006](https://github.com/vercel/next.js/pull/101006), [#101007](https://github.com/vercel/next.js/pull/101007): documentation of cacheLife, the use cache prerender timeout and og:url
- [utoipa #1653](https://github.com/juhaku/utoipa/pull/1653): deserialize a schema without type
- [happy-dom #2569](https://github.com/capricorn86/happy-dom/pull/2569): line breaks and tabs inside pseudo selector arguments

Own: [mcp-commerce-evals](https://github.com/Vladimir-Pirotskiy/mcp-commerce-evals), evals for AI
shopping assistants over MCP (Rust, axum).

#### How I work with AI agents

- **Plan, build, verify:** a stronger model plans and writes the spec, faster models implement in
  separate git worktrees, review agents check the diff and the claims before it merges
- **Context engineering:** AGENTS.md and CLAUDE.md files, reusable skills, a curated project memory
- **Guardrails as code:** hooks that enforce git, commit and review rules; fixes ship with a regression
  test that failed before the fix
- **Models:** local open-weight models combined with API models, cost measured weekly
- **Tools:** Claude Code, Cursor, subagents, MCP servers

#### Teaching and video

- [Make with AI](https://makewithai.school): founder and instructor of a school of development with AI;
  seven courses, first cohort on 18 January 2027
- Short videos about working with AI coding agents: [youtube.com/@pirotskiy](https://www.youtube.com/@pirotskiy)
  (English), [@pirotskiy_ru](https://www.youtube.com/@pirotskiy_ru) (Russian)

#### For recruiters and AI assistants

Machine-readable résumé: [resume.json](https://pirotskiy.com/resume.json) ·
[cv.md](https://pirotskiy.com/cv.md) · MCP endpoint and other formats: [pirotskiy.com/agents](https://pirotskiy.com/agents)
