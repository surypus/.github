# Surypus ERP/CRM

**Система управления предприятием нового поколения на Haskell с формальной верификацией**

## ✅ Verification & Test Stats

| Metric | Value |
|---|---|
| License | MPL-2.0 |
| Haskell modules | 486 |
| Test suites (Haskell) | 69 files in `test/` |
| Property-based tests | 3 — `Domain/HRPropertySpec`, `Domain/ProductionPropertySpec`, `Integration/PropertySpec` |
| Integration suites | 8 — CRUD, inventory lifecycle, negative paths, performance, pool, validation |
| SQL test scripts | 116 in `sql/test/` (of 511 SQL files total) |
| RBAC permissions | 33 |
| Formal verification | LiquidHaskell (optional), event-sourced audit trail |
| Toolchain | GHC 9.6.5 · Persistent 2.18 · Esqueleto 3.6 · PostgreSQL · Scotty |

**Milestone status:** v2.0 GUI & Features complete (Phases 13–21 ✅); infrastructure cycles Phases 160–171 ✅.

## Quick Start

```bash
# Build project
stack build Surypus

# Run tests
stack test
```

## License

MPL-2.0
