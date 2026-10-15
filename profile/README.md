# Visual Capitalist — GitHub Organization

Welcome to the Visual Capitalist GitHub organization. This is the home for our internal codebases, tools, and scripts. If you've landed here, you're probably a member of the VC team looking for something specific — read on.

---

## What lives here

| Repository | What it is | Who uses it |
|---|---|---|
| `vctracking` | Plugin to handle newsletter click tracking and utm link generation | Developers |
| `Visual-Capitalist` | WordPress theme and custom code for visualcapitalist.com | Developers |
| `vc-editorial-plugin` | Visual Capitalist editorial skills plugin for ChatGPT Work  | Editorial |
| `design` | Illustrator scripts, Python utilities, and other design tooling | Design team |

If you're looking for something and can't find it, reach out to the dev team.

---

## For the design team

The `vc-design` repository is your home for shared scripts and tools. You don't need to know Git deeply to use it — **GitHub Desktop** is the recommended way to interact with it.

- **Downloading GitHub Desktop:** [desktop.github.com](https://desktop.github.com)
- Once installed, you can browse files, save new versions of scripts, and see a history of changes — no command line needed.
- If you're adding a new script, drop a brief comment at the top of the file explaining what it does and how to use it. Future you will be grateful.

If you run into trouble, ask the dev team rather than pushing directly to the main branch.

---

## For developers

The `website` repo contains the WordPress child theme and custom plugin code deployed to visualcapitalist.com via CI/CD. A few things to know before you touch anything:

- **The repo is the source of truth.** Changes made directly via SFTP to production will be overwritten on the next deploy. All changes go through Git.
- **Never push directly to `main`.** Open a pull request and get a review, even for small changes.
- **Staging first, always.** Test on `visualcapstg.wpengine.com` before anything goes to production.
- Each repo has its own `README` with setup instructions, deployment details, and environment-specific notes. Start there.

---

## Access & permissions

Access is managed per-repository. If you need access to something you can't see, contact the dev team — don't ask someone to share credentials or add you as an org owner.

| Role | What they can do |
|---|---|
| Developers | Read/write on `website` and `design` |
| Design team | Read/write on `design` only |

---

## Questions?

Reach out to the dev team via Slack. For urgent site issues, message the #website channel.
