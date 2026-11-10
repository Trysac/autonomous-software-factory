# Autonomous Software Factory

Public showcase of an autonomous software factory that designs, builds, tests, audits and documents
production-grade software overnight, with a human approving what gets built and reviewing every pull request.

**Live page:** https://trysac.github.io/autonomous-software-factory/

- First run (line A, Anthropic): 100 of 100 open-source utilities delivered across 12 engineering domains
  (Python, TypeScript, Go), USD 0.94 of API cost per utility.
- Second run (line B, Google Gemini): 100 of 100 delivered, 81 by the pipeline alone, USD 0.27 per utility
  (later hand fixes are recorded as interventions).
- Third run (line C, DeepSeek, in progress): 41 of 45 delivered so far, all by the pipeline alone, USD 0.11 per
  project; calls only in DeepSeek's off-peak window at half price.
- Fourth run (line D, Google Vertex AI, in progress): 7 of 13 delivered so far, all by the pipeline alone,
  USD 1.74 per project; generation on a stronger model puts code quality before cost, and the figure includes
  early infrastructure problems fixed the same day.
- Median time from submission to pull request, one definition for every line: A 2.6 h, B 0.3 h, C 0.6 h, D 1.0 h.
- Coming lines, built but not yet run: OpenRouter, and two independent self-hosted lines (a rented cloud GPU and
  a local laptop GPU).
- Challenge run (line B): 10 size-L systems; 1 fit in one generation, 6 after fixing the line, all 10 after the
  architect re-planned the last 4 into 22 modules; 5 of the 10 were delivered with no human fix.
- Unreal Engine agent toolsets (line A): 4 of 4 delivered by the pipeline alone, USD 4.52 in total.
- Overall: 263 projects delivered. 82 % of all 304 started items delivered with no human fix (249). Every hand fix is recorded as an
  intervention and excluded from that rate.
- The page also describes the factory's roles: analyst, architect, generator, fixer, auditor, docs writer,
  security engineer and visual QA, and the deterministic planner, gates, publisher, release manager and
  maintenance; and its two fields, libraries and web applications.
- Every project passes lint, types, tests with at least 80% coverage, a documentation standard, a secret scan,
  a dependency audit and an independent specification audit, then CI on Linux and Windows.
- Browse them: [repositories with the `autonomous-software-factory` topic](https://github.com/Trysac?tab=repositories&q=topic%3Aautonomous-software-factory).

The factory itself (source code, prompts, rules and operating data) is private. This repository holds only the
public page, generated from the factory's measured results.

Designed and operated by José Miguel Gómez ([LinkedIn](https://www.linkedin.com/in/jose-miguel-gomez-architect)).
