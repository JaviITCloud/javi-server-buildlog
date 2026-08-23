# javi-server-buildlog

> A practical SysAdmin laboratory built, administered, documented and improved over time.

## Overview

`javi-server-buildlog` is the technical portfolio and build log for my SysAdmin training laboratory.

The central system is **`javi-server`**, a real Linux server that I am progressively administering and documenting as I work through the SysAdmin Phase 1 roadmap.

This repository is intended to show **real work and progression**, not a collection of copied tutorials. Documentation is added as tasks are actually completed in the laboratory.

---

## Laboratory

| Component | Current information |
|---|---|
| Main laboratory server | `javi-server` |
| Operating system | Ubuntu Server |
| Additional environments | Virtual machines when required for safe experimentation |

`javi-server` is the real physical laboratory system. Virtual machines are used when an experiment could unnecessarily affect the physical server or when an isolated environment is more appropriate.

---

## What this repository documents

The repository follows the **SysAdmin Phase 1 roadmap** and will progressively document areas such as:

- Linux system administration
- Command-line administration
- Users, groups and permissions
- Processes and services
- Package management
- System configuration
- Networking
- SSH
- Logs and troubleshooting
- Storage and filesystems
- Backups and recovery
- Automation and scripting
- Virtualization
- Windows Server and Active Directory
- Infrastructure security
- System monitoring

These are roadmap areas. They are **not a claim that every area has already been completed**. The build log is the source of truth for what has actually been practiced and demonstrated.

---

## Documentation approach

The work is documented chronologically by **date**, rather than by roadmap week.

```text
buildlog/
└── YYYY/
    └── MM/
        └── DD-MM-YYYY.md
```

Each entry records the work performed on that date and, when relevant, references the corresponding roadmap topic.

The documentation aims to capture:

1. Objective
2. Initial state
3. Work performed
4. Commands and configuration
5. Problems encountered
6. Troubleshooting and reasoning
7. Result
8. Verification
9. Lessons learned

The level of detail will grow with the project. Early entries are intentionally simple because the laboratory is still being built from a very basic starting point.

---

## Current status

**Roadmap:** SysAdmin — Phase 1  
**Current progress:** Week 2  
**Main laboratory:** `javi-server`

The project is currently in the early Linux administration stage. The repository will evolve alongside the laboratory rather than being populated retrospectively with work that was not actually performed.

---

## Repository structure

```text
.
├── README.md
├── buildlog/
│   └── YYYY/MM/
├── documentation/
├── scripts/
├── configs/
├── diagrams/
└── .gitignore
```

Directories will receive technical content only when there is real material to document. The repository is deliberately kept small during the early stages instead of being filled with empty or speculative content.

---

## Principles

- **Real laboratory first:** documentation reflects work actually performed.
- **No invented infrastructure:** hostnames, addresses, services and configurations are documented only when known.
- **Troubleshooting matters:** failures and the diagnostic process are part of the portfolio.
- **Security matters:** secrets, credentials and private keys are never committed.
- **Progressive complexity:** the project grows as my skills grow.
- **Reproducibility:** important configurations and procedures will be documented clearly enough to understand how the result was achieved.

---

## Training roadmap

This repository is limited to the **SysAdmin Phase 1** of my training roadmap.

The purpose is to build practical administration skills progressively while developing the knowledge required for the certifications and junior SysAdmin responsibilities covered by that phase.

---

## About the build log

The detailed history lives under [`buildlog/`](buildlog/).

Each dated entry represents actual work performed during the project. Roadmap weeks may be referenced inside entries for traceability, but **dates are the primary organization of the portfolio**.
