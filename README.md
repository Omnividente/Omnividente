# Omnividente

**Infrastructure & automation · Windows/Linux · Networking**

I build tools for administering systems, controlling network access, and simplifying technical workflows. My focus is predictable operation, explicit changes, and recoverability.

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=000000)
![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?logo=tauri&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?logo=opnsense&logoColor=white)

## Selected projects

### [OMP Desktop](https://github.com/Omnividente/omp-desktop)

A desktop workspace for [Oh My Pi](https://github.com/can1357/oh-my-pi), bringing projects, session history, and native PTY terminals together on Windows and Linux.

**Engineering focus:** process lifecycle, session integrity, and signed update delivery.

*Rust · Tauri · React* · [Releases](https://github.com/Omnividente/omp-desktop/releases/latest) · [Update verification](https://github.com/Omnividente/omp-desktop/actions/workflows/updater-e2e.yml)

### [OPNsense Client Control](https://github.com/Omnividente/opnsense-client-control)

Per-client network access and bandwidth management using native OPNsense firewall and traffic-shaping objects.

**Engineering focus:** preview before apply, conflict detection, configuration rollback, and an audit trail. Platform compatibility is documented rather than assumed.

*PHP · OPNsense · FreeBSD* · [Usage and compatibility](https://github.com/Omnividente/opnsense-client-control/blob/main/docs/USAGE_RU.md)

### [PyCombiner](https://github.com/Omnividente/PyCombiner)

A Windows application for launching scripts, monitoring logs, and managing processes. Workloads can start before user login and be monitored through the desktop interface afterward.

**Engineering focus:** headless/GUI coordination, bounded logs, and process-tree cleanup.

*Python · PySide6 · Windows* · [Releases](https://github.com/Omnividente/PyCombiner/releases/latest) · [English documentation](https://github.com/Omnividente/PyCombiner/blob/master/README.en.md)

### [RustDesk Bootstrap](https://github.com/Omnividente/rustdesk-bootstrap)

A Windows bootstrap installer for repeatable RustDesk deployment with preconfigured server settings and local installer support.

**Engineering focus:** deployment on existing Windows environments, including offline installation and x86/x64 systems.

*Rust · Windows · Deployment* · [Setup and constraints](https://github.com/Omnividente/rustdesk-bootstrap#en)

## Engineering approach

- **Make changes explicit.** Separate configuration from application, show the intended changes, and surface conflicts instead of silently overwriting them.
- **Design for recovery.** Preserve user data, handle process failures, and document rollback paths where they apply.
- **Verify at the operating boundary.** Use the target platform and real workflows to check behavior; distinguish automated checks from runtime acceptance and state what remains unverified.

## Contact

[Telegram: @Omnividente](https://t.me/Omnividente) — infrastructure tooling, deployment automation, and project feedback.
