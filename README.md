# linux-kernel-atlas

Living map of **Linux kernel security research** — fuzzers, sanitizers, exploit indexes, corpora — closed-loop taxonomy, not a flat awesome dump.

Sibling of [`uefi-firmware-atlas`](https://github.com/vulragrag-star/uefi-firmware-atlas) / [`oss-atlas`](https://github.com/vulragrag-star/oss-atlas).

## Why another list?
We first survey existing awesome/index repos (see `data/seeds/SOURCES.md`), then build a **machine-readable closed-loop atlas** that those lists are not: JSONL schema, use-tags, setting book, smoke notes, explicit domain fences.

## Inclusion / exclusion
- **IN:** Linux kernel source/security tooling (syzkaller, KASAN/KMSAN/KFENCE, syzbot, kernel CTF, LPE research indexes, rootkit research).
- **OUT:** UEFI/BIOS, IoT router firmware dumps, RTOS, MCU bare-metal, userspace-only Awesome-Linux software lists.

## Closed-loop map
See [`docs/MAP.md`](docs/MAP.md), [`docs/TAXONOMY.md`](docs/TAXONOMY.md), [`docs/SETTING.md`](docs/SETTING.md), [`docs/SMOKE.md`](docs/SMOKE.md).

## Status (crawl merge 2026-09-10)
- Tools: **130** (fringe flagged: **35**; core focus remains syzkaller/LPE/rootkit/sanitizer research)
- Papers / vulns / datasets: **28** / **12** / **7**
- Seeds surveyed first: see `data/seeds/SOURCES.md` · crawl notes: `docs/CRAWL_SUMMARY.md`

### Tool counts by stage

| Stage | n |
|---|---|
| acquire | 1 |
| dataset | 1 |
| defend_harden | 9 |
| emulate_fuzz | 38 |
| lab_teaching | 13 |
| offense_poc | 24 |
| paper_map | 5 |
| parse | 4 |
| runtime_assess | 15 |
| spec | 3 |
| static_re | 11 |
| vuln_intel | 6 |
| **total** | **130** |


## Quick start
```bash
python scripts/validate_catalog.py
python scripts/render_catalogs.py
```

## License
Docs: CC BY 4.0. Scripts: MIT. Upstream projects keep their licenses.
