# Offensive Finds

Offensive security / red-team tools I've come across on GitHub — not my own projects, just useful finds.

## Red Team / Offensive Security

- [blackhatethicalhacking/TerminatorZ](https://github.com/blackhatethicalhacking/TerminatorZ) — Passive scanner that checks Wayback Machine URLs for a domain against 24 high-priority CVE patterns (RCE, LFI, SQLi, SSRF, XXE, Log4j, and more).
- [blackhatethicalhacking/CF-GeoBypasser](https://github.com/blackhatethicalhacking/CF-GeoBypasser) — Modular toolkit for discovering and bypassing Cloudflare geo-restrictions using country-specific proxies.
- [blackhatethicalhacking/AdminPBuster](https://github.com/blackhatethicalhacking/AdminPBuster) — Multithreaded brute-forcer for hidden admin panels, with a wordlist that updates itself from GitHub.
- [blackhatethicalhacking/D0rkerR3con-Framework](https://github.com/blackhatethicalhacking/D0rkerR3con-Framework) — Offline Google Dorking toolkit with an interactive terminal UI and 68+ categorized dorks.
- [evilsocket/nyx](https://github.com/evilsocket/nyx) — ⚠️ alpha. Self-contained script to wipe forensic traces on Linux/macOS/Windows (shell history, system/web/DB logs, audit, temp, network, browsers, SSH, containers). Post-exploitation / OPSEC — dual-use, kept as reference.
- [caido/skills — caido-mode](https://github.com/caido/skills/tree/main/skills/caido-mode) — Official Caido AI skill: full SDK CLI for [Caido](https://caido.io/) (search HTTP history, curl requests through the proxy, match & replace, replay sessions/collections, scopes/filters/environments, findings, fuzzing) — all from the terminal.

## Mobile / APK & Agent-driven Audit

- [KekisSecurity/apk-audit-leads](https://github.com/KekisSecurity/apk-audit-leads) — A Claude Code skill for fast, entry-point-driven Android APK security audits. Give it a bare `.apk` and it returns an `OUTPUT.md` of bug-bounty-style *leads* only (impact chain + reward tier + exploitation method + buildable PoC plan). Runs decompile (`jadx`/`apkid`/`droidasc`) → classify → entry-point inventory → parallel hunt subagents → disprove pass.
- [MG1937/ASC — Droid ASC](https://github.com/MG1937/ASC) — Super-fast Android decompiler front-end for agents / mobile researchers (Black Hat EU Arsenal). Treats the APK as a read-only database with zero preprocessing: global cross-refs in ~1.8 s and class decompilation in ~177 ms on a 352 MB APK. CLI `droidasc` (`getclass` / `listclass` / `getmanifest` / `findrefs`).
- [GitHubSecurityLab/seclab-taskflows (audit)](https://github.com/GitHubSecurityLab/seclab-taskflows/tree/main/src/seclab_taskflows/taskflows/audit) — Example YAML taskflows for the GitHub Security Lab Taskflow Agent: AI-driven code/library/mobile/web audits (classify → entry-points → GHSA variant analysis → severity filter → audit issue). A reference for building agent-driven code review.

## My Own Compilations

- [russian-offensive-security-questions.md](./russian-offensive-security-questions.md) — A compilation of offensive-security interview questions (in Russian), covering networks, operating systems, web applications, cloud, and cryptography. Open and growing — forks/suggestions welcome.
