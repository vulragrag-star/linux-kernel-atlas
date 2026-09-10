# Linux-kernel-atlas crawl summary

- Date: 2026-09-10 (Asia/Shanghai)
- Method: gh API + gh search + seed README harvest; **no clones**
- Domain fences: IN linux kernel security (syzkaller/KASAN/KMSAN/KFENCE/kernel CTF/LPE/rootkits/corpora); OUT UEFI/IoT-dumps/RTOS/MCU/userspace-only lists

## Counts
- tools: **130** (fringe flagged: 35; core non-fringe: 95)
- papers: **28**
- datasets: **7**
- vulns: **12**

## Stage counts
| stage | count |
|---|---|
| spec | 3 |
| acquire | 1 |
| parse | 4 |
| static_re | 11 |
| emulate_fuzz | 38 |
| runtime_assess | 15 |
| offense_poc | 24 |
| defend_harden | 9 |
| vuln_intel | 6 |
| dataset | 1 |
| paper_map | 5 |
| lab_teaching | 13 |

## Top 15 tools by stars (all)
| stars | name | stage | fringe | url |
|---|---|---|---|---|
| 247662 | linux | spec | False | https://github.com/torvalds/linux |
| 22656 | bcc | runtime_assess | True | https://github.com/iovisor/bcc |
| 16309 | lynis | defend_harden | True | https://github.com/CISOfy/lynis |
| 13686 | pwntools | offense_poc | True | https://github.com/Gallopsled/pwntools |
| 12636 | oss-fuzz | emulate_fuzz | True | https://github.com/google/oss-fuzz |
| 12471 | sanitizers | spec | True | https://github.com/google/sanitizers |
| 10850 | pwndbg | runtime_assess | True | https://github.com/pwndbg/pwndbg |
| 10317 | bpftrace | runtime_assess | True | https://github.com/bpftrace/bpftrace |
| 9356 | falco | defend_harden | True | https://github.com/falcosecurity/falco |
| 8348 | gef | runtime_assess | True | https://github.com/hugsy/gef |
| 8290 | sysdig | runtime_assess | True | https://github.com/draios/sysdig |
| 6750 | AFLplusplus | emulate_fuzz | True | https://github.com/AFLplusplus/AFLplusplus |
| 6632 | linux-kernel-exploitation | paper_map | False | https://github.com/xairy/linux-kernel-exploitation |
| 6609 | linux-exploit-suggester | vuln_intel | False | https://github.com/The-Z-Labs/linux-exploit-suggester |
| 6319 | syzkaller | emulate_fuzz | False | https://github.com/google/syzkaller |

## Top 15 non-fringe (core kernel-security)
| stars | name | stage | url |
|---|---|---|---|
| 247662 | linux | spec | https://github.com/torvalds/linux |
| 6632 | linux-kernel-exploitation | paper_map | https://github.com/xairy/linux-kernel-exploitation |
| 6609 | linux-exploit-suggester | vuln_intel | https://github.com/The-Z-Labs/linux-exploit-suggester |
| 6319 | syzkaller | emulate_fuzz | https://github.com/google/syzkaller |
| 5652 | linux-kernel-exploits | offense_poc | https://github.com/SecWiki/linux-kernel-exploits |
| 4630 | security-research | offense_poc | https://github.com/google/security-research |
| 4170 | meltdown | offense_poc | https://github.com/isec-tugraz/meltdown |
| 3198 | Kernelhub | offense_poc | https://github.com/Ascotbe/Kernelhub |
| 2727 | Reptile | offense_poc | https://github.com/f0rb1dd3n/Reptile |
| 2494 | weggli | static_re | https://github.com/weggli-rs/weggli |
| 2455 | Diamorphine | offense_poc | https://github.com/m0nad/Diamorphine |
| 2131 | kernel-hardening-checker | defend_harden | https://github.com/a13xp0p0v/kernel-hardening-checker |
| 2098 | awesome-linux-rootkits | paper_map | https://github.com/milabs/awesome-linux-rootkits |
| 1979 | TripleCross | offense_poc | https://github.com/h3xduck/TripleCross |
| 1974 | linux-exploit-suggester-2 | vuln_intel | https://github.com/jondonas/linux-exploit-suggester-2 |

## Seeds used
- xairy/linux-kernel-exploitation
- milabs/awesome-linux-rootkits
- tkmru/awesome-linux-rootkits
- SecWiki/linux-kernel-exploits
- tttturtle-russ/awesome-kernel-security
- hygoni/awesome-linux-kernel
- a13xp0p0v/kernel-hack-drill

## Queries
syzkaller, KASAN, kernel fuzzer, linux kernel CTF, kernel exploitation, linux rootkit, KFENCE, KMSAN, syzbot, linux kernel corpus (+ topic/keyword expansions: kAFL, kernelCTF, syzgen, …)

## Exclusions (representative)
- SoftSec-KAIST/NTFuzz (Windows kernel — OUT)
- UEFI/EDK2, IoT firmware unpackers, RTOS/MCU trees (other atlases)
- Pure userspace awesome-linux / general CTF kitchen sinks (zardus/ctf-tools, pwncollege/dojo)
- Password crackers / TTY utilities (openwall/john, nelhage/reptyr)
- Duplicate/renamed trees (a13xp0p0v/kconfig-hardened-check → kernel-hardening-checker; mzet- → The-Z-Labs)
- Near-empty forks (0dayResearchLab/kafl.*, 0-star syzbot scrapers)

## Gaps
- acquire stage sparse (1: easylkb) — kernel image acquisition often overlaps IoT atlas device dumps (fenced out).
- dataset stage in tools catalog sparse (1) though datasets.jsonl has 7 entries (syzbot is dashboard-hosted).
- KASAN/KMSAN/KFENCE live in-tree (torvalds/linux) rather than standalone repos.
- Paper artifacts 404 at crawl: SyzBridge, SyzDescribe, Krace, Snowcat/Snowboard, kernelctf dedicated repo.
- No clone/smoke of syzkaller+QEMU (prompt forbids clones).
- tkmru awesome-linux-rootkits & SecWiki exploit tree stale (last push ~2020).
- Star-ranked top list dominated by fringe eBPF/observability/exploit-dev libs; see non-fringe top15.
- Userspace LD_PRELOAD rootkits included only as fringe from rootkit indexes.

## Output paths
- `/workspace/firmware-atlas-work/linux/catalog_tools.jsonl`
- `/workspace/firmware-atlas-work/linux/papers.jsonl`
- `/workspace/firmware-atlas-work/linux/datasets.jsonl`
- `/workspace/firmware-atlas-work/linux/vulns.jsonl`
- `/workspace/firmware-atlas-work/linux/crawl_summary.md`
