# 100Hires Portfolio Project — Setup Documentation

**Candidate:** Maythee Nualnao
**Date:** June 2026
**Task:** Install and configure AI development tools, document the process

---

## Tools Installed

| Tool | Status |
|------|--------|
| Cursor IDE | ✅ Installed |
| Claude Code (Cursor Extension) | ✅ Installed & Logged In |
| Codex (Cursor Extension) | ✅ Installed & Logged In |

---

## Steps Completed

### 1. Installed Cursor IDE
- Downloaded from https://cursor.com/
- Completed initial setup and account configuration

### 2. Added Claude Code Extension
- Opened the Extensions panel inside Cursor
- Searched "Claude Code", installed, and logged in

### 3. Added Codex Extension
- Searched "Codex" in the Extensions panel
- Installed and authenticated successfully

### 4. Created Public GitHub Repository
- Created a new public repository at https://github.com/
- Initialized with a README.md file

### 5. Opened Repository in Cursor
- Cloned the repository into local machine using Git
- Opened the project folder inside Cursor workspace

### 6. Created and Committed README.md
- Wrote this documentation file inside Cursor
- Committed and pushed to GitHub via terminal

---

## Issues Encountered & How I Solved Them

**Issue 1: Finding the Extensions panel in Cursor**
- **Problem:** Cursor's UI layout looked different from VS Code, so the Extensions panel was not immediately obvious to locate.
- **Solution:** Because I have prior experience with vibe coding and AI-assisted development workflows, I was already familiar with how modern code editors are structured. I found the Extensions panel quickly by exploring the sidebar icons — it did not take long to get oriented.

**Issue 2: Cloning the GitHub repository into Cursor**
- **Problem:** I was not immediately sure of the exact steps to clone a GitHub repository directly into Cursor, particularly which command to use and where to run it.
- **Solution:** I looked up the correct `git clone` command and ran it through Cursor's built-in terminal. Once I had the repository URL from GitHub and ran `git clone [URL]`, the folder appeared locally and I was able to open it in Cursor without further issues.

**Issue 3: `fatal: not a git repository` error when running git commands**
- **Problem:** After opening the terminal in Cursor and attempting to run `git add README.md`, the terminal returned `fatal: not a git repository (or any of the parent directories): .git`. The commands were being run from the parent directory (`E:\100hire`) rather than from inside the cloned repository folder.
- **Solution:** Used `cd 100hires-portfolio-project` to navigate into the correct folder, then ran `git status` to confirm the terminal was now inside a valid git repository. Once confirmed, the `git add` and `git commit` commands ran without errors.

**Issue 4: `git push` rejected due to remote conflict**
- **Problem:** When running `git push origin main`, the push was rejected with the error: `Updates were rejected because the remote contains work that you do not have locally`. This happened because GitHub had automatically created a README.md when the repository was initialized, which created a commit history that differed from the local version.
- **Solution:** Since this is a personal repository with no collaborative history to protect, I resolved the conflict by running `git push --force origin main`. This overwrote the remote with the local version, successfully publishing the updated README to GitHub.

---

## Reflections

This task tested the ability to independently set up a modern AI-assisted development environment from scratch, without prior instruction or hand-holding. Key takeaways:
- Cursor IDE integrates cleanly with both Claude Code and Codex, enabling a powerful AI-assisted coding workflow
- Even with prior coding experience, new tools always come with small friction points — the important skill is knowing how to navigate them quickly
- Git error messages, while sometimes intimidating, contain enough information to diagnose the problem and find a targeted fix
- GitHub remains the standard for version control and public portfolio work
- Independent problem-solving — whether through prior experience, documentation, or searching — is what separates candidates who can ship from those who cannot

---

*This repository is part of the 100Hires candidate evaluation process.*