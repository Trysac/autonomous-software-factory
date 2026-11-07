# Autonomous Software Factory

Public showcase of an autonomous software factory that designs, builds, tests, audits and documents
production-grade software overnight, with a human approving what gets built and reviewing every pull request.

**Live page:** https://trysac.github.io/autonomous-software-factory/

- First run (line A, Anthropic): 100 of 100 open-source utilities delivered across 12 engineering domains
  (Python, TypeScript, Go), USD 0.94 of API cost per utility.
- Second run (line B, Google Gemini): 100 of 100 delivered, 84 by the pipeline alone, USD 0.27 per utility.
- Every utility passes lint, types, tests with at least 80% coverage, a documentation standard, a secret scan,
  a dependency audit and an independent specification audit, then CI on Linux and Windows.
- Browse them: [repositories with the `autonomous-software-factory` topic](https://github.com/Trysac?tab=repositories&q=topic%3Aautonomous-software-factory).

The factory itself (source code, prompts, rules and operating data) is private. This repository holds only the
public page, generated from the factory's measured results.

Designed and operated by José Miguel Gómez ([LinkedIn](https://www.linkedin.com/in/jose-miguel-gomez-architect)).
