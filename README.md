# Hi, I'm Thomas Chacko

**Senior AI Engineer (Ex-Meta).** I design and ship production AI systems: RAG, multi-agent workflows, evals and LLMOps. Quality first, then velocity.

**Austin, TX** · **Remote US** · W2, contract or C2C · [LinkedIn](https://www.linkedin.com/in/tchacko1/) for roles and conversations

### Recent work

- **Feedonomics, Senior AI Engineer.** Built GenAI product categorization from the ground up and owned it to production across 14+ marketplaces. Cut LLM cost up to 92% ($2,500+ → $199 per 1M products), backed by 113 automated tests and LLM-as-judge evals.
- **AI-native engineering at scale.** 10,000+ hours building with coding agents (Claude Code, Cursor, Codex). I run them in parallel worktrees under short written rules, with blind reviewer agents and a test or eval behind every "done".

### How I work

- **Make the machine prove it.** Evidence comes from tests and evals, not from the agent's own report.
- **Measure, then claim.** Retrieval and model choices are scored on golden sets with pass criteria fixed in advance.
- **Bug fixes ship with a test that fails on the old code.**
- **Rules that must always hold are enforced in code and CI, not in prompts.**

### Featured projects

**[Mechanic RAG](https://github.com/Alpha-W0lf/mechanic_rag)**: Ask a car question and get an answer that cites the exact manual page. Live hybrid RAG over the complete Honda S2000 manuals, hardened for production on a $0 stack.
→ [Live demo](https://mechanic-rag.vercel.app)

**[mcp-audit](https://github.com/Alpha-W0lf/mcp-audit)**: A test kit that checks whether an MCP server really does what it advertises. Run against the official MCP reference servers, it flagged two known bugs ([#4651](https://github.com/modelcontextprotocol/servers/issues/4651), [#4686](https://github.com/modelcontextprotocol/servers/issues/4686)) before their fixes shipped, and I recommended #4652, the fix that merged. [Results](https://github.com/Alpha-W0lf/mcp-audit/blob/main/docs/REAL_SERVER_RESULTS.md)

**[Eyeglass Finder](https://github.com/Alpha-W0lf/eyeglass_finder)**: A computer-vision pipeline that finds people wearing eyeglasses in 39,258 Wikipedia images, tuned to ~17× throughput (9.8 → 167.5 images/sec).
→ [See the finds](https://alpha-w0lf.github.io/eyeglass_finder/docs/latest_run_showcase/qualitative_analysis/final_targets/index.html)

**[AI Knowledge Base](https://github.com/Alpha-W0lf/ai-knowledge-base-public)**: Production-grade local hybrid search for coding agents, served through a read-only MCP server.

**[AlphaGuard](https://github.com/Alpha-W0lf/alphaguard)**: A harness for testing AI trade ideas without fooling yourself: an LLM analyst proposes, a code-owned risk veto decides, and floors are held fixed across experiments. Its own audit caught a label leak, now fixed and guarded by tests.

### Stack

- **Core:** Python, Go, JavaScript (Node.js), TypeScript
- **AI & Gen AI:** Generative AI, LLMs, RAG, Multimodal RAG, Multi-Agent Systems, Agentic AI, AI Agents, LangGraph, MCP, AI Evaluation, LLM-as-judge, LLMOps, MLOps, Prompt Engineering, Context Engineering, Fine-Tuning, LoRA, NLP, Semantic Search, Vector Search, Vector Databases, Embeddings, Knowledge Graphs, LangChain, CrewAI, OpenAI API, Anthropic Claude, Google Gemini, Hugging Face, PyTorch, TensorFlow
- **Agentic tooling:** Claude Code, Anthropic Claude, Cursor, Grok Bot, OpenAI Codex, Google Gemini, Windsurf, Cline, Roo Code, OpenCode, OpenClaw, GitHub Copilot, Spec Driven Development, Intent Engineering, Loop Engineering
- **Software:** Software Engineering, Backend Development, Full Stack, System Design, Systems Architecture, Distributed Systems, Microservices, REST APIs, GraphQL, CI/CD, Git, Observability

Project and C2C engagements through [Lowd Code LLC](https://lowdcode.com), a Texas S-Corp, fully insured.
