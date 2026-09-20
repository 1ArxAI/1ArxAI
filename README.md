# shieldspprt

Full-stack AI engineer. I build at the seam between LLMs and Solana, and I ship the whole thing: agents, APIs, and the frontend that wraps them.

Right now I am building SolHunt, tooling that helps people recover forgotten SOL, sweep dust, revoke risky approvals, and reclaim rent without giving up custody. I also turn that work into AI agent skills so a model can read wallet health and give plain, actionable advice instead of noise.

Open to full-stack AI engineering roles and small, useful teams.

## What I do

- Design and ship AI agents (RAG, evals, tool use) that solve real tasks, not toy demos
- Build full-stack apps in TypeScript with React up front and Bun or Node behind
- Ship on Solana: Solidity and Rust programs, wallet tooling, trustless recovery flows
- Automate the boring parts with scheduled agents, MCP servers, and CI

## Selected work

- **[SolHunt](https://github.com/shieldspprt/solhunt-recovery)**: recover forgotten SOL, sweep dust, reclaim rent, and revoke approvals without custody.
- **[solhunt-skill](https://github.com/shieldspprt/solhunt-skill)**: AI agent skill for wallet health checks and approval auditing.
- **[Yellex](https://github.com/shieldspprt/yellex)**: AI pickup-line game built around Solana legends and historical figures.

## Stack I reach for

TypeScript · React / Next.js · Bun / Node · Postgres / Prisma · Solana / Solidity / Rust · Docker · Cloudflare · AWS · GitHub Actions

## Find me

- X: [@solhuntdev](https://x.com/solhuntdev)

<!-- OPEN COMPUTER DAILY -->

## Open Computer Daily

### 2026 09 20: GitHub Actions and Open Computer

[GitHub Actions](https://docs.github.com/actions) is good at automating, customising and executing software development workflows in a repository. Its focus is CI and CD, with reusable actions that combine into build, test and deployment pipelines.

[Open Computer](https://github.com/shieldspprt/open-computer) provides a broader persistent workspace around that workflow. On your own Linux server, an agent can research a change, edit files in a real terminal, run tests, connect MCP tools, schedule recurring checks and supervise 24 hour processes after the browser session ends. Project folders preserve the work, while self hosting and Cloudflare Tunnel support give practical control over the workspace. For example, an agent can prepare a repository change, test it, schedule a daily report and retain the logs in one place.

[Explore Open Computer](https://github.com/shieldspprt/open-computer).

### 2026 09 19: Docker and Open Computer

[Docker](https://www.docker.com/) is good at building, sharing and running containerised applications. Its focus is packaging software with its dependencies so teams can develop and deploy consistently across environments.

[Open Computer](https://github.com/shieldspprt/open-computer) provides a broader persistent workspace around that workload. On your own Linux server, an agent can use a real terminal, edit files, run Docker workloads, connect MCP tools, and leave scheduled automations or supervised 24 hour processes running after the browser session ends. Project folders keep work organised, while self hosting and Cloudflare Tunnel support give you control over where the workspace runs and how it is reached. For example, an agent can research a service, write its Docker configuration, test it, schedule a monitor and retain the logs in one place.

### 2026 09 18: Make and Open Computer

[Make](https://www.make.com/en) is a capable visual workflow automation platform, letting teams connect apps and services through a drag and drop scenario builder, API management, and thousands of prebuilt integrations. That focus suits businesses automating SaaS triggers and data flows without writing code.

[Open Computer](https://github.com/shieldspprt/open-computer) gives that kind of automation a fuller operating base to run from. On your own Linux server, one browser workspace lets an agent draft and send outbound email, publish social content, and supervise the whole pipeline as a 24 hour background process, backed by a real terminal, file manager and code editor. Self hosting and Cloudflare Tunnel support keep credentials and data on infrastructure you control.

### 2026 09 17: Zapier and Open Computer

[Zapier](https://zapier.com/) connects over 9000 apps and lets teams route AI agents, chatbots and workflows through one governed platform, with audit trails, action restrictions and role based access built for enterprise IT. That focus suits teams who want no code automation across existing SaaS tools without waiting on engineering.

[Open Computer](https://github.com/shieldspprt/open-computer) gives that same reach for automation a persistent home to run from. On your own Linux server, one browser workspace holds a real terminal, a file manager with a code editor, and 24 hour background daemons, so a script can be written, tested and left running without separate hosting. Self hosting and Cloudflare Tunnel support keep the workspace and its credentials under your own control.

### 2026 09 16: n8n and Open Computer

[n8n](https://n8n.io/) is a strong visual workflow automation platform: a no-code builder with over 500 app integrations, plus JavaScript or Python code steps when you need more than the visual canvas offers. That focus suits teams connecting apps and automating triggers within a defined SaaS workflow.

[Open Computer](https://github.com/shieldspprt/open-computer) gives that automation a broader home to run from. On your own Linux server, one browser workspace holds a real terminal, a file editor, MCP and API integrations, and BYOK model freedom across Anthropic, OpenAI, DeepSeek and local Ollama. An agent can write and test a script in the terminal, save it to the workspace, and schedule it to run daily, all without separate hosting. Self hosting and Cloudflare Tunnel support keep credentials and the workspace under your control.

### 2026 09 15: LangChain and Open Computer

[LangChain](https://www.langchain.com) is a strong open source framework for building agents: any model provider, built in observability and evaluation, and tools to ship agents to production. That focus suits developers who want full control over an agent's own reasoning code.

[Open Computer](https://github.com/shieldspprt/open-computer) gives that agent a persistent home to actually run in. Its own real Linux terminal, file editor, scheduled automations and supervised 24 hour background processes sit inside one browser workspace on your own server. A LangChain agent can be coded there, scheduled to check a task every morning, and left running with logs you can check from any browser. Self hosting and Cloudflare Tunnel support keep the credentials and the workspace under your control.

### 2026 09 14: CrewAI and Open Computer

[CrewAI](https://crewai.com) is good at orchestrating specialised AI agents with tools, memory, knowledge and structured output. That focus suits teams building a defined multi agent process with explicit roles and workflow controls.

[Open Computer](https://github.com/shieldspprt/open-computer) gives that process a broader place to live. On your own Linux server, its agent can research on the web, edit files, run code, schedule recurring work and supervise persistent services from one browser workspace. A campaign can gather evidence, prepare email and social content, wait for approval, publish through connected tools and keep monitoring after the chat closes. Self hosting, local model support and Cloudflare Tunnel support provide practical control over where the workspace runs and how it is reached.

<!-- /OPEN COMPUTER DAILY -->

## Engineering Log

<!-- STREAK -->
*Live, automated full-stack AI engineering micro-lessons. 90 entries, 32-day streak (last: 2026-08-12).*
<!-- /STREAK -->

<!-- LOGS -->
 - 2026-08-12: [Use a serializable plan object to separate agent reasoning from tool execution](entries/2026-08-12-slot2.md)
 - 2026-08-12: [Stream structured tool results to the client as typed events](entries/2026-08-12-slot1.md)
 - 2026-08-12: [Compile prompt templates into typed TypeScript functions](entries/2026-08-12-slot0.md)
 - 2026-08-11: [Avoid async context leakage by binding task-scoped data to the async call chain](entries/2026-08-11-slot1.md)
 - 2026-08-11: [Route each task to the smallest model that meets your quality threshold](entries/2026-08-11-slot0.md)
 - 2026-08-10: [Offload CPU-bound work in async agent loops to a dedicated thread pool](entries/2026-08-10-slot2.md)
 - 2026-08-10: [Set per-call LLM timeouts that respect your total request budget and fail fast on slow providers](entries/2026-08-10-slot1.md)
 - 2026-08-10: [Validate structured LLM output with a schema gate and retry on failure](entries/2026-08-10-slot0.md)
 - 2026-08-09: [Prompt versioning with git-style diffs catches regressions before deploy](entries/2026-08-09-slot1.md)
 - 2026-08-09: [Stream LLM responses with an AbortController so the client can cancel mid-flight](entries/2026-08-09-slot1.md)
 - 2026-08-09: [Structured concurrency with task groups prevents leaked agent tasks](entries/2026-08-09-slot0.md)
 - 2026-08-08: [Version prompt templates and log the rendered prompt so evals can reproduce exact model inputs](entries/2026-08-08-slot1.md)
 - 2026-08-08: [Trace ID Propagation Across Async Boundaries](entries/2026-08-08-slot0.md)
 - 2026-08-07: [Attach a unique request ID to every LLM call to correlate retries, timeouts, and cost](entries/2026-08-07-slot2.md)
 - 2026-08-07: [Rate limits are contracts not suggestions](entries/2026-08-07-slot1.md)
 - 2026-08-07: [Request-scoped caches dedupe identical in-flight LLM calls](entries/2026-08-07-slot0.md)
 - 2026-08-06: [Request-scoped context with contextvars propagates trace IDs across async boundaries](entries/2026-08-06-slot2.md)
 - 2026-08-06: [Idempotent webhook handlers with a dedupe key prevent duplicate processing when retries arrive out of order](entries/2026-08-06-slot0.md)
 - 2026-08-05: [Deterministic agent replay lets you re-run a failed session with the exact same LLM outputs to debug without burning tokens or hitting rate limits](entries/2026-08-05-slot2.md)
 - 2026-08-05: [An eval harness that runs on every PR catches agent regressions before they reach production](entries/2026-08-05-slot1.md)
 - 2026-08-04: [Batch database writes from agent tool calls into a single transaction to reduce round trips and avoid partial commits when retries occur](entries/2026-08-04-slot2.md)
 - 2026-08-04: [Store the raw LLM response alongside the parsed output so evals can catch parsing drift without re-running the model](entries/2026-08-04-slot1.md)
 - 2026-08-04: [Fan out independent LLM calls with a bounded semaphore and collect results in order](entries/2026-08-04-slot0.md)
 - 2026-08-03: [Propagate trace IDs and user identity through async call chains with a request-scoped context](entries/2026-08-03-slot2.md)
 - 2026-08-03: [Use Postgres advisory locks to coordinate distributed agent workers](entries/2026-08-03-slot0.md)
 - 2026-08-02: [A circuit breaker around external API calls in agent tools prevents cascade failures when a downstream service degrades](entries/2026-08-02-slot2.md)
 - 2026-08-02: [A typed event bus lets you observe agent behaviour without coupling instrumentation to business logic](entries/2026-08-02-slot1.md)
 - 2026-08-02: [Eval driven prompt iteration beats manual tuning](entries/2026-08-02-slot0.md)
 - 2026-08-01: [Prefetch and cache embeddings for known query patterns](entries/2026-08-01-slot2.md)
 - 2026-08-01: [Stream partial tool call results to the client instead of buffering everything](entries/2026-08-01-slot1.md)
 - 2026-08-01: [Structured error envelopes make agent failures debuggable](entries/2026-08-01-slot0.md)
 - 2026-07-31: [Agent checkpointing](entries/2026-07-31-slot1.md)
 - 2026-07-30: [Structured logging with correlation IDs traces a request across service boundaries](entries/2026-07-30-slot2.md)
 - 2026-07-30: [Bounded concurrency for parallel tool execution prevents resource exhaustion](entries/2026-07-30-slot1.md)
 - 2026-07-30: [Backpressure on LLM token streams keeps memory bounded](entries/2026-07-30-slot0.md)
 - 2026-07-29: [Graceful degradation keeps your agent useful when the primary LLM provider degrades](entries/2026-07-29-slot2.md)
 - 2026-07-29: [Handle partial tool call failures with compensating actions](entries/2026-07-29-slot1.md)
 - 2026-07-29: [Execute independent tool calls in parallel to reduce agent loop latency](entries/2026-07-29-slot0.md)
 - 2026-07-28: [Optimistic UI Updates with Server Reconciliation for Chat](entries/2026-07-28-slot2.md)
 - 2026-07-28: [Use a Typed Tool Layer So Agents Never Guess a Schema](entries/2026-07-28-slot0.md)
 - 2026-07-27: [Prefill the Assistant Message to Steer JSON Output Reliably](entries/2026-07-27-slot2.md)
 - 2026-07-27: [Stream partial tool call results to the client instead of buffering the full response](entries/2026-07-27-slot1.md)
 - 2026-07-27: [Register Tool Schemas at Startup and Validate Every Agent Call Against Them](entries/2026-07-27-slot0.md)
 - 2026-07-26: [Use a Request Scoped Dedupe Cache for Identical In Flight LLM Calls](entries/2026-07-26-slot1.md)
 - 2026-07-26: [Stream Tool Call Results to the Client Instead of Buffering the Full Response](entries/2026-07-26-slot1.md)
 - 2026-07-26: [Run Async LLM Calls in Batches with a Bounded Semaphore and collect results in order](entries/2026-07-26-slot0.md)
 - 2026-07-25: [Validate Tool Call Arguments Against a JSON Schema Before Execution](entries/2026-07-25-slot2.md)
 - 2026-07-25: [Prefill the Assistant Message to Steer JSON Output Reliably](entries/2026-07-25-slot1.md)
 - 2026-07-25: [Batch LLM Calls with a Bounded Semaphore](entries/2026-07-25-slot0.md)
 - 2026-07-24: [Circuit Breaker for LLM Provider Failures](entries/2026-07-24-slot2.md)
 - 2026-07-24: [Structured Output Validation with Pydantic and Retry Logic](entries/2026-07-24-slot0.md)
 - 2026-07-23: [Rate limit LLM calls per user with a token bucket](entries/2026-07-23-slot2.md)
 - 2026-07-23: [Semantic caching cuts LLM costs for near duplicate prompts](entries/2026-07-23-slot1.md)
 - 2026-07-23: [Token budgets keep agent loops from spiraling](entries/2026-07-23-slot0.md)
 - 2026-07-22: [Validate structured LLM output with a strict schema before it reaches your database](entries/2026-07-22-slot1.md)
 - 2026-07-22: [Use a request scoped cache to deduplicate identical LLM calls within a single user request](entries/2026-07-22-slot0.md)
 - 2026-07-21: [Stream partial JSON from LLMs with a tolerant parser so the UI updates token by token](entries/2026-07-21-slot2.md)
 - 2026-07-21: [Coalesce identical in flight LLM requests to share one upstream call](entries/2026-07-21-slot1.md)
 - 2026-07-21: [Stream tool call results to the client instead of buffering the full response](entries/2026-07-21-slot0.md)
 - 2026-07-20: [Eval driven prompt design beats prompt engineering by feel](entries/2026-07-20-slot2.md)
 - 2026-07-20: [Stream tool call results to the client instead of buffering the full response](entries/2026-07-20-slot0.md)
 - 2026-07-19: [Ship a typed tool layer so agents never guess a schema](entries/2026-07-19-slot2.md)
 - 2026-07-19: [Keep your RAG retriever honest with a score floor](entries/2026-07-19_slot0.md)
 - 2026-07-18: [Backend idempotency keys stop duplicate writes from retries](entries/2026-07-18_slot2.md)
 - 2026-07-18: [Cache your LLM responses at the edge to cut cost and latency](entries/2026-07-18_slot1.md)
 - 2026-07-17: [Design idempotent webhook handlers with a dedupe key](entries/2026-07-17_slot2.md)
 - 2026-07-17: [Backend idempotency keys stop duplicate writes under retry storms](entries/2026-07-17_slot1.md)
 - 2026-07-17: [Gzip your server sent event stream, or you pay 10x for tokens you never read](entries/2026-07-17-slot0.md)
 - 2026-07-16: [Cache LLM tool call schemas at the gateway, not per request](entries/2026-07-16-slot2.md)
 - 2026-07-16: [Backpressure saves your LLM service when a downstream API throttles you](entries/2026-07-16-slot1.md)
 - 2026-07-16: [Colocate compute with data to avoid shipping rows you never render](entries/2026-07-16-slot0.md)
 - 2026-07-15: [A prompt cache turns repeat questions into instant, free hits](entries/2026-07-15-slot2.md)
 - 2026-07-15: [Constrain LLM output with a JSON schema instead of parsing prose](entries/2026-07-15-slot1.md)
 - 2026-07-15: [Order a composite Postgres index to match your query shape](entries/2026-07-15-slot0.md)
 - 2026-07-14: [Bounded concurrency beats Promise.all for LLM batches](entries/2026-07-14-slot2.md)
 - 2026-07-14: [Idempotency keys keep LLM retries from double firing](entries/2026-07-14-slot1.md)
 - 2026-07-14: [Deduplicate near duplicate chunks before embedding to cut RAG cost and retrieval noise](entries/2026-07-14-slot0.md)
 - 2026-07-13: [Retry LLM calls with jittered exponential backoff, not fixed sleeps](entries/2026-07-13-slot2.md)
 - 2026-07-13: [Cut LLM cost and latency with prompt caching](entries/2026-07-13-slot1.md)
 - 2026-07-13: [Make agent tool calls idempotent with a deterministic key](entries/2026-07-13-slot0.md)
 - 2026-07-12: [Idempotent API endpoints with an idempotency key](entries/2026-07-12-slot2.md)
 - 2026-07-12: [Streaming LLM tokens to the browser with the Fetch API](entries/2026-07-12-slot1.md)
<!-- /LOGS -->

*Updated automatically every 8 hours. Full archive in the entries folder.*