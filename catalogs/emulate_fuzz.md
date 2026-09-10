# emulate_fuzz

_84 entries_

- **[oss-fuzz](https://github.com/google/oss-fuzz)** ★12636 — Continuous fuzzing for open source (hosts many projects)  
  tags: `daily-ops, reference-impl`  
  smoke: No clone; metadata-only smoke

- **[AFLplusplus](https://github.com/AFLplusplus/AFLplusplus)** ★6750 — AFL++ community fuzzer (QEMU/Unicorn modes used for kernels)  
  tags: `lab-usable, paper-repro, reference-impl`  
  smoke: No clone; metadata-only smoke

- **[syzkaller](https://github.com/google/syzkaller)** ★6319 — Unsupervised coverage-guided kernel fuzzer (syzkaller/syzbot)  
  tags: `paper-repro, lab-usable, reference-impl, daily-ops`  
  smoke: Run qemu/repro on lab VM; full syzbot needs infra.

- **[linux](https://github.com/lkl/linux)** ★916 — Linux Kernel Library (userspace library Linux)  
  tags: `lab-usable, paper-repro, reference-impl`  
  smoke: No clone; metadata-only smoke

- **[trinity](https://github.com/kernelslacker/trinity)** ★910 — Classic Linux system-call fuzzer  
  tags: `lab-usable, paper-repro`  
  smoke: No clone; metadata-only smoke

- **[kAFL](https://github.com/IntelLabs/kAFL)** ★812 — Hardware-assisted feedback fuzzing for OS kernels (kAFL/Nyx lineage)  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: No clone; metadata-only smoke

- **[TriforceAFL](https://github.com/nccgroup/TriforceAFL)** ★644 — Sibling of atlas TriforceLinuxSyscallFuzzer; full-system AFL/QEMU  
  tags: `paper-repro`  
  smoke: CONSIDER confidence from survey cross-check.

- **[kAFL](https://github.com/RUB-SysSec/kAFL)** ★595 — Original/academic kAFL kernel fuzzer tree  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: No clone; metadata-only smoke

- **[buzzer](https://github.com/google/buzzer)** ★477 — eBPF bytecode fuzzer from Google  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[kernel-fuzzer-for-xen-project](https://github.com/intel/kernel-fuzzer-for-xen-project)** ★474 — Kernel fuzzer for Xen (KF/x) using Intel PT  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: No clone; metadata-only smoke

- **[kernel-sanitizers](https://github.com/google/kernel-sanitizers)** ★468 — Dedicated Linux kernel sanitizer docs/tree; atlas has google/sanitizers + torvalds/linux but not this repo  
  tags: `paper-repro`  
  smoke: CONSIDER confidence from survey cross-check.

- **[RedQueen](https://github.com/RUB-SysSec/redqueen)** ★402 — Input-to-state correspondence; survey Table 6 lists Linux target; general AFL-family (not Linux-only)  
  tags: `paper-repro`  
  smoke: CONSIDER confidence from survey cross-check.

- **[difuze](https://github.com/ucsb-seclab/difuze)** ★385 — Interface-aware fuzzing for kernel drivers  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[razzer](https://github.com/compsec-snu/razzer)** ★377 — Fuzzer for kernel data races  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[unicorefuzz](https://github.com/fgsect/unicorefuzz)** ★305 — Unicorn-based kernelspace fuzzing  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[healer](https://github.com/SunHao-0/healer)** ★292 — Syzkaller-inspired coverage-guided kernel fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[Lucid](https://github.com/h0mbre/Lucid)** ★255 — Snapshot fuzzing / research fuzzer (Lucid)  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[janus](https://github.com/sslab-gatech/janus)** ★238 — File-system fuzzer combining metadata+data mutations  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[Nyx](https://github.com/RUB-SysSec/Nyx)** ★208 — Nyx snapshot fuzzing framework (successor lineage to kAFL)  
  tags: `paper-repro, hw-required`  
  smoke: No clone; metadata-only smoke

- **[nyx-net](https://github.com/RUB-SysSec/nyx-net)** ★205 — Nyx-Net network snapshot fuzzer  
  tags: `paper-repro, hw-required`  
  smoke: No clone; metadata-only smoke

- **[KernelGPT](https://github.com/ise-uiuc/KernelGPT)** ★179 — LLM-enhanced kernel fuzzing (ASPLOS 2025).  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[TriforceLinuxSyscallFuzzer](https://github.com/nccgroup/TriforceLinuxSyscallFuzzer)** ★179 — AFL+QEMU full-system Linux syscall fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[Hydra](https://github.com/sslab-gatech/hydra)** ★177 — FS semantic fuzzer (SibylFS/B3 checkers); Janus lineage  
  tags: `paper-repro, lab-usable`  
  smoke: FS semantic fuzzer (SibylFS/B3 checkers); Janus lineage

- **[vUSBf](https://github.com/schumilo/vUSBf)** ★170 — USB host-stack fuzzer (vUSBf)  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[VirtFuzz](https://github.com/seemoo-lab/VirtFuzz)** ★135 — VirtIO-device fuzzing of Linux wireless stacks  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[USBFuzz](https://github.com/HexHive/USBFuzz)** ★130 — USB driver fuzzing via device emulation  
  tags: `paper-repro, lab-usable`  
  smoke: USB driver fuzzing via device emulation

- **[agamotto](https://github.com/securesystemslab/agamotto)** ★129 — Accelerates kernel driver fuzzing with VM checkpoints  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[FuZZan](https://github.com/HexHive/FuZZan)** ★128 — Efficient sanitizer metadata design for fuzzing  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[kernel-fuzzing](https://github.com/oracle/kernel-fuzzing)** ★119 — Oracle kernel fuzzing tools/harnesses  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[MoonShine](https://github.com/shankarapailoor/moonshine)** ★109 — Trace distillation seed selection for syzkaller  
  tags: `paper-repro, lab-usable`  
  smoke: Trace distillation seed selection for syzkaller

- **[StateFuzz](https://github.com/vul337/StateFuzz)** ★101 — State-variable guided Linux driver fuzzing  
  tags: `paper-repro, lab-usable`  
  smoke: State-variable guided Linux driver fuzzing

- **[kbdysch](https://github.com/atrosinenko/kbdysch)** ★85 — Partition-based kernel fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[ebpf-fuzzer](https://github.com/snorez/ebpf-fuzzer)** ★83 — eBPF subsystem fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[GREBE](https://github.com/Markakd/GREBE)** ★82 — Object-driven multi-error-behavior / exploitability exploration  
  tags: `paper-repro, lab-usable`  
  smoke: Object-driven multi-error-behavior / exploitability exploration

- **[PeriScope](https://github.com/securesystemslab/periscope)** ★71 — Hardware-OS boundary probing/fuzzing (Android Wi-Fi drivers); Linux kernel hooks  
  tags: `paper-repro, lab-usable`  
  smoke: Hardware-OS boundary probing/fuzzing (Android Wi-Fi drivers); Linux kernel hooks

- **[SyzGPT](https://github.com/QGrain/SyzGPT)** ★63 — SyzGPT — LLM+RAG seeds for low-frequency syscalls (ISSTA 2025).  
  tags: `paper-repro, lab-usable`  
  smoke: Research prototype; pair with syzkaller.

- **[vock](https://github.com/yskzalloc/vock)** ★62 — VOCK kernel concurrency fuzzing research  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[PrIntFuzz](https://github.com/vul337/PrIntFuzz)** ★61 — Virtual device simulation for Linux driver probe/IRQ paths  
  tags: `paper-repro, lab-usable`  
  smoke: Virtual device simulation for Linux driver probe/IRQ paths

- **[SyzDescribe](https://github.com/seclab-ucr/SyzDescribe)** ★60 — Static auto generation of syzlang for drivers  
  tags: `paper-repro, lab-usable`  
  smoke: Static auto generation of syzlang for drivers

- **[deadline](https://github.com/sslab-gatech/deadline)** ★48 — Kernel fuzzing / concurrency research from SSLab  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[SyzDirect](https://github.com/seclab-fudan/SyzDirect)** ★41 — Directed greybox fuzzing for Linux kernel  
  tags: `paper-repro, lab-usable`  
  smoke: Directed greybox fuzzing for Linux kernel

- **[actor](https://github.com/ucsb-seclab/actor)** ★41 — Action-guided kernel fuzzing  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[FuzzUSB](https://github.com/purseclab/fuzzusb)** ★37 — Hybrid stateful USB gadget stack fuzzing  
  tags: `paper-repro, lab-usable`  
  smoke: Hybrid stateful USB gadget stack fuzzing

- **[kafl.fuzzer](https://github.com/IntelLabs/kafl.fuzzer)** ★37 — Modular kAFL fuzzer component  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: No clone; metadata-only smoke

- **[FuzzNG](https://github.com/BUseclab/FuzzNG)** ★36 — Spec-free Linux syscall fuzzing (NDSS'23)  
  tags: `paper-repro, lab-usable`  
  smoke: Spec-free Linux syscall fuzzing (NDSS'23)

- **[BoKASAN](https://github.com/seclab-yonsei/BoKASAN)** ★35 — Binary-only Kernel Address Sanitizer for fuzzing  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[kafl.targets](https://github.com/IntelLabs/kafl.targets)** ★34 — Target configs/harnesses for kAFL  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[Krace](https://github.com/sslab-gatech/krace)** ★32 — Data-race fuzzing for kernel file systems  
  tags: `paper-repro, lab-usable`  
  smoke: Data-race fuzzing for kernel file systems

- **[SegFuzz](https://github.com/casys-kaist/segfuzz)** ★32 — Segmentized thread-interleaving concurrency fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: Segmentized thread-interleaving concurrency fuzzer

- **[Countdown](https://github.com/PSU-Security-Universe/countdown)** ★29 — Refcount-guided temporal memory error fuzzer (CCS'24)  
  tags: `paper-repro, lab-usable`  
  smoke: Refcount-guided temporal memory error fuzzer (CCS'24)

- **[Dr.Fuzz](https://github.com/secsysresearch/DRFuzz)** ★29 — Semantic-informed device-free driver fuzzing (NDSS'22)  
  tags: `paper-repro, lab-usable`  
  smoke: Semantic-informed device-free driver fuzzing (NDSS'22)

- **[SyzVegas](https://github.com/SoveraNia/SyzVegas)** ★29 — RL/MAB task+seed scheduling for syzkaller  
  tags: `paper-repro, lab-usable`  
  smoke: RL/MAB task+seed scheduling for syzkaller

- **[Snowboard](https://github.com/rssys/snowboard)** ★28 — Kernel concurrency via inter-thread communication analysis  
  tags: `paper-repro, lab-usable`  
  smoke: Kernel concurrency via inter-thread communication analysis

- **[Monarch](https://github.com/rs3lab/Monarch)** ★26 — Distributed file-system multi-node fuzzer (ATC'24)  
  tags: `paper-repro, lab-usable`  
  smoke: Distributed file-system multi-node fuzzer (ATC'24)

- **[BRF](https://github.com/trusslab/brf)** ★24 — BPF Runtime Fuzzer (eBPF runtime beyond verifier)  
  tags: `paper-repro, lab-usable`  
  smoke: BPF Runtime Fuzzer (eBPF runtime beyond verifier)

- **[MOCK](https://github.com/m0ck1ng/mock)** ★24 — Context-aware dependency mutation (NDSS'24)  
  tags: `paper-repro, lab-usable`  
  smoke: Context-aware dependency mutation (NDSS'24)

- **[lxfuzz](https://github.com/b17fr13nds/lxfuzz)** ★22 — Linux kernel fuzzing experiments  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[SyzGenPlusPlus](https://github.com/seclab-ucr/SyzGenPlusPlus)** ★21 — Dependency inference for augmenting kernel driver fuzzing  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[kafl.linux](https://github.com/IntelLabs/kafl.linux)** ★20 — Linux kernel tree patches/targets for kAFL  
  tags: `paper-repro, lab-usable, hw-required`  
  smoke: No clone; metadata-only smoke

- **[Snowcat](https://github.com/rssys/snowcat)** ★16 — Learned coverage predictor for kernel concurrency testing  
  tags: `paper-repro, lab-usable`  
  smoke: Learned coverage predictor for kernel concurrency testing

- **[sys2syz](https://github.com/ais2397/sys2syz)** ★16 — Automate generation of syzkaller grammar  
  tags: `paper-repro, lab-usable`  
  smoke: No clone; metadata-only smoke

- **[DEVFUZZ](https://github.com/yiluwusbu/DEVFUZZ)** ★14 — Automatic device model-guided driver fuzzing (S&P'23)  
  tags: `paper-repro, lab-usable`  
  smoke: Automatic device model-guided driver fuzzing (S&P'23)

- **[SyzRisk](https://github.com/HexHive/SyzRisk)** ★12 — Change-pattern continuous regression fuzzer  
  tags: `paper-repro, lab-usable`  
  smoke: Change-pattern continuous regression fuzzer

- **[hfsplus-kernel-fuzzing-demo](https://github.com/sl4v/hfsplus-kernel-fuzzing-demo)** ★12 — Demo of fuzzing Linux HFS+ kernel module  
  tags: `lab-usable, paper-repro`  
  smoke: No clone; metadata-only smoke

- **[DDRace](https://github.com/vul337/DDRace)** ★11 — Directed concurrency-UAF fuzzing for Linux drivers  
  tags: `paper-repro, lab-usable`  
  smoke: Directed concurrency-UAF fuzzing for Linux drivers

- **[StepStone](https://github.com/seclab-ucr/StepStone)** ★11 — LLM-based GPU kernel driver fuzzing via user-space libraries  
  tags: `paper-repro`  
  smoke: No clone; metadata-only smoke

- **[Drifuzz](https://github.com/buszk/Drifuzz)** ★9 — Golden-seed / peripheral-boundary fuzzing without hardware; also buszk/drifuzz-concolic  
  tags: `paper-repro, lab-usable`  
  smoke: Golden-seed / peripheral-boundary fuzzing without hardware; also buszk/drifuzz-concolic

- **[BSOD](None)** ★? — Binary-only scalable driver fuzzing (RAID'21); no public repo found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[BVF](None)** ★? — Sanitizer coverage gap work in Table 4; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[Charm](None)** ★? — Mobile/Android driver dynamic analysis (USENIX Sec'18); no public repo found; Android-leaning  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[Conzzer](None)** ★? — Concurrency call-pair metric fuzzer; no public repo found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[Dogfood](None)** ★? — Listed in survey Table 5; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[G-Fuzz](None)** ★? — Directed fuzzing for gVisor (+Linux); public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[HEALER (index)](https://github.com/search?q=HEALER+syzkaller)** ★? — HEALER syscall-relation kernel fuzzer (index; canonical repo path noisy).  
  tags: `paper-repro`  
  smoke: INDEX ONLY — verify upstream before citing as installable.

- **[HFL](None)** ★? — Hybrid fuzzing on Linux (NDSS'20); no public GitHub found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[Horus](None)** ★? — Host-VM memory access acceleration; no public repo found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[KBinCov](None)** ★? — Binary coverage/state feedback; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[KSG](None)** ★? — Syscall spec generation (ATC'22, Hao Sun et al.); code not released (author has healer only)  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[Lfuzz](None)** ★? — FS fuzzer mentioned with JANUS/Hydra; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[PLA](None)** ★? — Seed-scheduling entry in Table 6; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[ReUSB](None)** ★? — Replay-guided USB driver fuzzing (USENIX Sec'23); no public repo found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[SATURN](None)** ★? — Host-gadget synergistic USB fuzzing (S&P'24); no public repo found  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[SECT](None)** ★? — eBPF-based scheduling; public code not located  
  tags: `paper-repro`  
  smoke: No public code per survey cross-check.

- **[SyzParam](https://github.com/Symatrix6/SyzParam)** ★0 — Prototype only (0 stars); runtime parameters into driver fuzzing  
  tags: `paper-repro`  
  smoke: CONSIDER confidence from survey cross-check.
