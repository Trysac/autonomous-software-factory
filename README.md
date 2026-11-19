# Autonomous Software Factory

Public showcase of an autonomous software factory that designs, builds, tests, audits and documents
software overnight, with a human approving what gets built and reviewing every pull request.

**Live page:** https://trysac.github.io/autonomous-software-factory/

Figures as of 2026-11-18, recomputed from the factory's ledger.

- 374 tested and audited open-source projects delivered as pull requests, measured on four model providers.
- 82 % of all 405 work items (projects, relaunches and modules) delivered with no human fix (334). Every hand fix
  is recorded as an intervention (60 so far) and excluded from that rate.
- Anthropic: 100 of 100 utilities delivered, all with no human fix, USD 0.94 of API cost per project.
- Gemini: 100 of 100 delivered, 81 with no human fix, USD 0.27 per project.
- DeepSeek: 100 of 100 delivered, 96 with no human fix, USD 0.12 per project; calls only in DeepSeek's off-peak
  window at half price.
- Vertex AI: 59 of 59 delivered, 38 with no human fix, USD 1.43 per project; generation on a stronger model puts
  code quality before cost. Its run took the factory to thirteen languages: Python, TypeScript, Go, Java, Kotlin,
  Scala, C#, C++, Rust, PHP, Ruby, Elixir and Dart (one more project of that run was built on the Anthropic line).
- Median time from submission to pull request, one definition for every line: Anthropic 2.6 h, Gemini 0.3 h,
  DeepSeek 0.6 h, Vertex AI 1.6 h.
- Large systems: 10 size-L systems, from a SQL engine to a WebAssembly interpreter; the last 4 were re-planned by
  the architect into 22 modules. Unreal Engine agent toolsets: 4 of 4 delivered.
- Coming lines, built but not yet run: OpenRouter, and two self-hosted lines (a rented cloud GPU and a local
  laptop GPU).
- The page also describes the factory's roles: analyst, architect, generator, fixer, auditor, docs writer,
  security engineer and visual QA, and the deterministic planner, gates, publisher, release manager and
  maintenance.
- Every project passes lint, types, tests with at least 80% coverage, a documentation standard, a secret scan,
  a dependency audit and an independent specification audit, then CI.
- Browse them: [repositories with the `autonomous-software-factory` topic](https://github.com/Trysac?tab=repositories&q=topic%3Aautonomous-software-factory),
  or the [catalog](https://trysac.github.io/autonomous-software-factory/catalog.html).

The factory itself (source code, prompts, rules and operating data) is private. This repository holds only the
public page, generated from the factory's measured results.

Designed and operated by José Miguel Gómez ([LinkedIn](https://www.linkedin.com/in/jose-miguel-gomez-architect)).
