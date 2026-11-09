# Autonomous Software Factory

Public showcase of an autonomous software factory that designs, builds, tests, audits and documents
production-grade software overnight, with a human approving what gets built and reviewing every pull request.

**Live page:** https://trysac.github.io/autonomous-software-factory/

- First run (line A, Anthropic): 100 of 100 open-source utilities delivered across 12 engineering domains
  (Python, TypeScript, Go), USD 0.94 of API cost per utility.
- Second run (line B, Google Gemini): 100 of 100 delivered, 84 by the pipeline alone, USD 0.27 per utility.
- Challenge run (line B): 10 size-L systems; 1 fit in one generation, 6 after fixing the line, all 10 after the
  architect re-planned the last 4 into 22 modules; 5 of the 10 were delivered with no human fix.
- Unreal Engine agent toolsets (line A): 4 of 4 delivered by the pipeline alone, USD 4.52 in total.
- Overall: 214 projects delivered; 82 % of all 245 items with no human fix. Every hand fix is recorded as an
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
