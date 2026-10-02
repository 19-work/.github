# 19-work

**Building large systems from scratch, to understand them deeply.**

I'm **Seba Gedeon Matsoula Malonga**, a software engineer and tech lead based in Brazzaville, Republic of the Congo.

This organization hosts a long-term program: rebuilding the systems that run the world (an interpreter, Git, a cache, a database, Raft, a mini-Kubernetes, a mail server, a collaborative editor...) in reduced but working versions. The goal is not to ship products. It is to understand these systems well enough to explain them on a whiteboard, and to lead a team that builds them for real.

## Rules

- **I write the core code myself.** AI is used to explain, review and generate tests, never to build the system.
- **Every line is explainable.** If I can't explain it, it doesn't stay.
- **Plan before code.** Each project starts with a written breakdown into milestones and small tasks.
- **Every project ships five deliverables:** the plan, the code with tests, a design document (C4 + ADRs), a public article, and a 45-minute talk.

## Projects

| # | Repository | What it rebuilds | Language | Status |
|---|---|---|---|---|
| 1 | [go-fundamentals](https://github.com/19-work/go-fundamentals) | Go foundations | Go | 🚧 In progress |
| 2 | [tree-walk-interpreter](https://github.com/19-work/tree-walk-interpreter) | A programming language interpreter | Go | 🔜 Planned |
| 3 | [bytecode-vm](https://github.com/19-work/bytecode-vm) | A bytecode virtual machine with garbage collection | C | 🔜 Planned |
| 4 | [mini-git](https://github.com/19-work/mini-git) | Git | Go | 🔜 Planned |
| 5 | [unix-shell](https://github.com/19-work/unix-shell) | A Unix shell | C | 🔜 Planned |
| 6 | [kv-cache](https://github.com/19-work/kv-cache) | Redis | Go | 🔜 Planned |
| 7 | [btree-db](https://github.com/19-work/btree-db) | SQLite | Go | 🔜 Planned |
| 8 | [raft-kv](https://github.com/19-work/raft-kv) | etcd / Raft | Go | 🔜 Planned |
| 9 | [mini-kube](https://github.com/19-work/mini-kube) | Kubernetes | Go | 🔜 Planned |
| 10 | [mail-server](https://github.com/19-work/mail-server) | SMTP + IMAP server | Go | 🔜 Planned |
| 11 | [headless-cms](https://github.com/19-work/headless-cms) | A headless CMS | Go / TypeScript | 🔜 Planned |
| 12 | [collab-editor](https://github.com/19-work/collab-editor) | Google Docs (CRDT) | TypeScript / Go | 🔜 Planned |
| 13 | [backend-framework](https://github.com/19-work/backend-framework) | NestJS | TypeScript | 🔜 Planned |

**Later:** my own language, a Linux distribution, a Wayland desktop, a cross-platform Dart framework, a toy browser.

## Learning in public

- [algorithms](https://github.com/19-work/algorithms): solved problems, organized by pattern
- [system-design](https://github.com/19-work/system-design): architecture katas and interview designs
- [paper-notes](https://github.com/19-work/paper-notes): notes on research papers (Raft, Dynamo, Borg, B-trees, CRDTs...)
- [talks](https://github.com/19-work/talks): 45-minute explanations of each system
- [handbook](https://github.com/19-work/handbook): the program, templates and quarterly reviews
