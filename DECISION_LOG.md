### 2026-11-13

- Candidates considered:
  - infiniflow/ragflow — 49/50 — Agent-native RAG database, 94,097★, Apache-2.0, pushed 2026-11-13, Go + TypeScript + Python (NEW category: RAG Infrastructure / Data Engineering)
  - rtk-ai/rtk — 48/50 — CLI proxy reducing LLM tokens 60-90%, 86,408★, Apache-2.0, pushed 2026-11-12, Rust (NEW category: Developer Tools / AI Cost Optimization)
  - Graphify-Labs/graphify — 49/50 — Code to knowledge graph, 146,853★, Apache-2.0, pushed 2026-11-11, Python (NEW category: Code Intelligence / AST Analysis)
  - pbakaus/impeccable — 49/50 — AI agent design vocabulary, anti-slop, 109,123★, Apache-2.0, pushed 2026-11-13, Rust (NEW category: AI Code Quality / Anti-Slop)
  - ruvnet/RuView — 46/50 — WiFi spatial intelligence, IoT, 104,185★, MIT, pushed 2026-11-13, Rust + TypeScript (NEW category: IoT / Edge AI)
  - ollama/ollama — 44/50 — LLM model runner, 186,833★, MIT, pushed 2026-11-13, Go (LLM Infrastructure, very large scope)
  - langgenius/dify — 43/50 — Agentic workflow platform, 161,072★, NOASSERTION, pushed 2026-11-13, Python (License unclear)
  - langflow-ai/langflow — 45/50 — Visual AI agent builder, 156,585★, MIT, pushed 2026-11-13, Python (AI Low-code, good but similar to openappa category)
  - microsoft/markitdown — 44/50 — Document to Markdown converter, 195,151★, MIT, pushed 2026-11-07, Python (Document processing, smaller scope)

- Selected: infiniflow/ragflow
- Mode: B (Substantial Enhancement Fork — Apache-2.0 permissive license)
- Score summary: 49/50
  - Momentum 5/5 (94,097 stars, pushed today 2026-11-13, active development, enterprise adoption)
  - Improvement potential 5/5 (African language tokenizers/embeddings, MCP server enhancement (stdio + HTTP/SSE), benchmark regression detection, interactive architecture visualization, comprehensive documentation, enhanced CI/CD with govulncheck/TruffleHog/SBOM, African domain document processors)
  - Portfolio fit 5/5 (NEW category: RAG Infrastructure / Data Engineering / Context Engineering — distinct from Computer-Use Agents, AI Agent Security, Cloud/FinOps, AI Context, 3D CAD, Web App, Desktop/DB, Mobile/API; Go + RAG + Agent orchestration aligns with Senior Software Engineering + AI Engineering + Data Engineering + African Technology)
  - License freedom 5/5 (Apache-2.0, fully permissive for fork/enhancement/redistribution with attribution)
  - Complexity fit 4/5 (Mature Go workspace with clear extension points: internal/tokenizer, internal/parser, internal/deepdoc, internal/mcp, internal/rag, internal/agentic_rag, Python SDK, web frontend, CLI; native C++/ONNX backend adds depth)
  - Demo potential 5/5 (RAG pipeline demos, African language document processing, agent orchestration, architecture visualization, before/after retrieval quality)
  - Documentation/case-study potential 5/5 (Architecture viz, before/after, case study, interactive tree, MCP guide, benchmark reports, African language RAG guide)
  - Category diversification 5/5 (RAG Infrastructure / Data Engineering — COMPLETELY NEW category; last 7 days: Computer-Use Agents, AI Agent Security, Cloud/FinOps, AI Context, 3D CAD, Web App, AI Security, Desktop/DB, Mobile/API)
  - Security/AI learning value 5/5 (RAG security, document processing sandboxing, agent orchestration security, data privacy, supply chain)
  - Legal/ethical safety 5/5 (Apache-2.0, defensive RAG focus, responsible AI data handling, no exploit tooling)

- Why selected:
  - hermers.md §148-158: Category rotation — RAG Infrastructure / Data Engineering / Context Engineering not covered in portfolio (last 7 days: Computer-Use, AI Security, Cloud/FinOps, AI Context, 3D CAD, Web App, AI Security, Desktop, Mobile)
  - Strong alignment with portfolio goals: Senior Software Engineering (Go workspace, RAG engine, document processing, native C++/ONNX, CLI, benchmarks, CI/CD), AI Engineering (Agent orchestration, MCP server for RAG skills, agentic RAG, context engineering), Data Engineering (Vector search, document ingestion, embedding pipelines, knowledge compilation), African Technology (African language tokenizers, embeddings, document processors for mobile money statements, healthcare records, multilingual RAG)
  - Clear, well-scoped improvement opportunities: African language tokenizer support (7 languages), African embedding models, African domain document parsers (mobile money, healthcare, logistics), MCP server enhancement (stdio + HTTP/SSE transports, 15+ tools for RAG orchestration), benchmark regression detection (Go benchmark suite with SQLite/PostgreSQL storage, 5% threshold), interactive architecture visualization (React Flow, 50+ nodes), comprehensive documentation suite (Design Doc, Case Study, Before/After, Interactive Tree), enhanced CI/CD (govulncheck, TruffleHog, SBOM, dependency review, gosec), security hardening (document sandboxing, input validation, rate limiting)
  - Go + RAG + Agent orchestration demonstrates senior engineering breadth beyond typical web stacks
  - Built-in benchmark infrastructure (test/benchmark/) provides immediate foundation for regression detection
  - Project is production-adjacent with active maintenance, comprehensive test infrastructure, enterprise adoption
  - Native DeepDoc backend (C++/ONNX) provides measurable before/after for document processing improvements
  - Existing MCP server (internal/mcp/) provides natural extension point for RAG skill orchestration

- Why others rejected:
  - rtk-ai/rtk: Excellent developer tool but narrower scope (single CLI binary), less visual demo potential
  - Graphify-Labs/graphify: Strong code intelligence but Python-only, AST analysis category less differentiated from existing agent work
  - pbakaus/impeccable: Good AI code quality but very new, smaller community, "anti-slop" niche harder to demonstrate
  - ruvnet/RuView: IoT/Edge hardware focus makes demos harder in 5-hour window, requires ESP32 hardware
  - ollama/ollama: LLM serving infrastructure too large scope for quality enhancement in 5 hours
  - langgenius/dify: License unclear (NOASSERTION), workflow platform overlaps with n8n category
  - langflow-ai/langflow: Visual agent builder overlaps with openappa-enhanced AI agent security category
  - microsoft/markitdown: Document converter good but smaller scope, less architectural depth

- Category focus: RAG Infrastructure / Data Engineering / Context Engineering, Go RAG Engine, African Language Tokenizers/Embeddings, African Domain Document Processors, MCP Server Enhancement (stdio + HTTP/SSE), Benchmark Regression Detection (Go + SQLite), Interactive Architecture Visualization (React Flow), Comprehensive Documentation Suite, Multi-platform CI/CD (govulncheck, TruffleHog, SBOM, gosec), Agent Orchestration Security

- Outcome: STARTING