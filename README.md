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

## Status (bootstrap 2026-09-10)
- Seed survey recorded; core tools JSONL: **7** (crawl expansion in flight)
- Papers/vulns/datasets: filling via multi-agent crawl

## Quick start
```bash
python scripts/validate_catalog.py
python scripts/render_catalogs.py
```

## License
Docs: CC BY 4.0. Scripts: MIT. Upstream projects keep their licenses.
