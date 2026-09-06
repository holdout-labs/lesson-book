# Changelog

## [0.1.2] - 2026-09-05
- fix: PyPI description still carried pre-rename `foolproof-labs` org links — rebuilt and bumped to 0.1.2.
- fix: pyproject version line synced to `__version__` (missed in the previous commit).
- ci: wheel-smoke job — version consistency (pyproject vs `__version__`) + fresh-venv wheel install smoke.
- docs: README.zh-CN (simplified Chinese translation); README status line aligned to 0.1.2.

## [0.1.1] / [0.1.0] - 2026-08-18
- Initial public release: local-first, zero-dependency tuition ledger for
  traders — record what a mistake cost, tag it, and let `lb match` remind
  you before the same situation shows up again. No LLM, no cloud, no
  statistics; deterministic and auditable.
