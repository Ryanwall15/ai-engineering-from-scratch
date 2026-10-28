# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
"I'm a software engineer and ramping up my AI skills. I need this to ramp up for my next project." Build goal: "Start with an agent but move into a full app."

## Placement
- Date: 2026-10-28
- Score: 6/10 (Math & Statistics 1/2, Classical ML 1/2, Deep Learning 1/2, NLP & Transformers 1/2, Applied AI 2/2)
- Entry point: Phase 11: LLM Engineering (work lane) and Phase 1: Math Foundations (foundations lane), in parallel
- Pace: ~5 hours/week

## How to pick the next lesson
Tutor: this learner follows a two-lane, lesson-level plan (revised 2026-10-28).
Do NOT pick the next lesson by phase number, and do NOT teach lessons that are not
listed under "Lesson plan" below. Choose the next lesson like this:
1. If the learner names a lesson, lane, or topic, teach that.
2. Otherwise, take the first unlogged lesson in the Work lane core list, in the
   order given (Phase 11 comes before Phase 13 and 14 on purpose).
3. Roughly one session in four (weeks 1 to 8), take the first unlogged lesson in
   the Foundations lane instead. From week 9 on, alternate the two lanes.
4. "Work lane, later" lessons are only taught when the learner asks for them or
   the core work lane is fully logged.

## Path
| Phase | Name | Status | Lane | Est. hours |
|-------|------|--------|------|------------|
| 0 | Setup & Tooling | Skip | -- | -- |
| 1 | Math Foundations | Do (10 lessons) | Foundations | 10 |
| 2 | ML Fundamentals | Do (7 lessons) | Foundations | 8 |
| 3 | Deep Learning Core | Do (8 lessons) | Foundations | 10 |
| 4 | Computer Vision | Skip | -- | -- |
| 5 | NLP — Foundations to Advanced | Do (4 lessons) | Foundations | 4 |
| 6 | Speech & Audio | Skip | -- | -- |
| 7 | Transformers Deep Dive | Do (9 lessons) | Foundations | 8 |
| 8 | Generative AI | Skip | -- | -- |
| 9 | Reinforcement Learning | Skip | -- | -- |
| 10 | LLMs from Scratch | Do (8 lessons) | Foundations | 9 |
| 11 | LLM Engineering | Do (11 core + 4 later) | Work | 16 |
| 12 | Multimodal AI | Skip | -- | -- |
| 13 | Tools & Protocols | Do (13 core + 11 later) | Work | 41 |
| 14 | Agent Engineering | Do (34 core + 2 later) | Work | 36 |
| 15 | Autonomous Systems | Later (5 lessons) | Work | 6 |
| 16 | Multi-Agent & Swarms | Later (5 lessons) | Work | 6 |
| 17 | Infrastructure & Production | Later (5 lessons) | Work | 6 |
| 18 | Ethics, Safety & Alignment | Skip (read 15 once) | -- | -- |
| 19 | Capstone Projects | Skip (FED Cert Tracker is the capstone) | -- | -- |

## Lesson plan

### Work lane, core (in this order)
1. Phase 11: 01-prompt-engineering, 03-structured-outputs, 04-embeddings, 05-context-engineering, 06-rag, 07-advanced-rag, 09-function-calling, 10-evaluation, 12-guardrails, 13-production-app, 14-model-context-protocol
2. Phase 13: 01-the-tool-interface, 05-tool-schema-design, 06-mcp-fundamentals, 07-building-an-mcp-server, 08-building-an-mcp-client, 09-mcp-transports, 10-mcp-resources-and-prompts, 15-mcp-security-tool-poisoning, 16-mcp-security-oauth-2-1, 18-mcp-auth-production, 28-mcp-tool-contracts-and-content, 29-mcp-reliability-cancellation-and-flow-control, 23-capstone-tool-ecosystem
3. Phase 14 (agent systems): 01-the-agent-loop, 06-tool-use-and-function-calling, 07-memory-virtual-context-memgpt, 12-anthropic-workflow-patterns, 17-claude-agent-sdk, 26-failure-modes-agentic, 27-prompt-injection-defense, 28-orchestration-patterns, 30-eval-driven-agent-development, 24-agent-observability-platforms
4. Phase 14 (agent-assisted engineering): 31 through 46, in numeric order
5. Phase 14 (product judgment): 47 through 54, in numeric order

### Work lane, later (only when asked or core is done)
- Phase 11: 02-few-shot-cot, 15-prompt-caching, 16-langgraph-state-machines, 17-agent-framework-tradeoffs
- Phase 13: 02-function-calling-deep-dive, 03-parallel-and-streaming-tool-calls, 11-mcp-sampling, 12-mcp-roots-and-elicitation, 13-mcp-async-tasks, 14-mcp-apps, 17-mcp-gateways-and-registries, 19-a2a-protocol, 20-opentelemetry-genai, 30-mcp-registry-supply-chain-and-drift, 31-mcp-conformance-versioning-and-operations
- Phase 14: 13-langgraph-stateful-graphs, 29-production-runtimes
- Phase 15: 10-claude-code-permission-modes, 12-durable-execution, 13-cost-governors, 15-propose-then-commit, 16-checkpoints-rollback
- Phase 16: 01-why-multi-agent, 05-supervisor-orchestrator-pattern, 11-handoffs-and-routines, 22-production-scaling-queues-checkpoints, 23-failure-modes-mast-groupthink
- Phase 17: 13-llm-observability, 19-ai-gateways, 20-shadow-canary-progressive, 23-sre-for-ai, 25-security-secrets-audit

### Foundations lane (in this order)
1. Phase 1: 01-linear-algebra-intuition, 02-vectors-matrices-operations, 03-matrix-transformations, 04-calculus-for-ml, 05-chain-rule-and-autodiff, 06-probability-and-distributions, 08-optimization, 09-information-theory, 12-tensor-operations, 14-norms-and-distances
2. Phase 2: 01-what-is-machine-learning, 02-linear-regression, 03-logistic-regression, 09-model-evaluation, 10-bias-variance, 12-hyperparameter-tuning, 19-ml-system-design
3. Phase 3: 01-the-perceptron, 02-multi-layer-networks, 03-backpropagation, 04-activation-functions, 05-loss-functions, 06-optimizers, 10-mini-framework, 11-intro-to-pytorch
4. Phase 5: 03-word-embeddings-word2vec, 10-attention-mechanism, 19-subword-tokenization, 22-embedding-models-deep-dive
5. Phase 7: 01-why-transformers, 02-self-attention-from-scratch, 03-multi-head-attention, 04-positional-encoding, 05-full-transformer, 07-gpt-causal-language-modeling, 12-kv-cache-flash-attention, 13-scaling-laws, 14-build-a-transformer-capstone
6. Phase 10: 01-tokenizers, 02-building-a-tokenizer, 04-pre-training-mini-gpt, 06-instruction-tuning-sft, 07-rlhf, 08-dpo, 10-evaluation, 11-quantization

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|

## Review queue
<!-- empty for now; learn adds lessons the quizzes flag -->
