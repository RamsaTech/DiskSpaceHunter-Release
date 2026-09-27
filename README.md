<p align="center">
  <img src="assets/icon.png" width="128" height="128" alt="GigaHunter app icon: Byte the beagle on a green tile">
</p>

<h1 align="center">GigaHunter</h1>

<p align="center"><b>Find the gigabytes hiding in macOS System Data, and get them back safely.</b></p>

<p align="center">
  <a href="https://github.com/RamsaTech/DiskSpaceHunter-Release/releases/download/v0.2.0-beta.1/GigaHunter-0.2.0-beta.1.dmg"><b>Download GigaHunter 0.2.0-beta.1</b></a>
  &nbsp;·&nbsp; <a href="https://github.com/RamsaTech/DiskSpaceHunter-Release/releases">All releases and notes</a>
  <br><sub>Test build · September 27, 2026 · macOS 15 Sequoia or later · Apple silicon and Intel</sub>
</p>

---

When your Mac's storage shows a huge **System Data** bar, GigaHunter shows you what's actually in it (caches, developer tools, simulators, old iPhone updates, AI models, logs and more), explains each item in plain words, and clears only what you approve.

- **Everything explained.** What it is, whether it's safe to remove, and whether it comes back.
- **Tagged for you.** *Safe to delete* items rebuild themselves. *Needs review* items might still matter, so you decide.
- **When you last used it.** Every item shows its age, and one click selects everything unused for 90 days (or any number you pick).
- **Trash first.** Cleaned items go to the Trash, so you can put them back from Activity.
- **Your files stay yours.** Documents, photos and messages are never touched.

<p align="center"><img src="assets/byte.png" width="160" alt="Byte the beagle, happy"><br><sub>Meet Byte, the beagle who sniffs out hidden gigabytes.</sub></p>

## Install

1. Download **GigaHunter-0.2.0-beta.1.dmg**, open it, and drag **GigaHunter** into **Applications**.
2. Open GigaHunter. Test builds aren't notarized yet, so macOS says it can't verify the app. Click **Done**.
3. Open **System Settings › Privacy & Security**, click **Open Anyway** next to "GigaHunter was blocked", and confirm.

Or run this once in Terminal after copying the app: `xattr -dr com.apple.quarantine /Applications/GigaHunter.app`

## Updates

GigaHunter checks this page's releases once a day (you can turn that off in Settings › Updates) and offers the download when a newer version is out. The check is one anonymous request to GitHub: no account, no tracking, nothing about your Mac is sent.

## Help

Found a problem or have an idea? [Open an issue](https://github.com/RamsaTech/DiskSpaceHunter-Release/issues) with your macOS version, your Mac model and a screenshot.

---

<sub>Made by <a href="https://www.techdna.com/">TechDNA.Com</a>, a unit of Agroha Tech Ventures Pvt. Ltd., Mount Abu, India. · <a href="mailto:info@techdna.com">info@techdna.com</a><br>This repository hosts GigaHunter's downloads and update feed.</sub>
