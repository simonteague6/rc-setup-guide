# RC Setup Guide

Static site for Rowdy Creators members setting up a laptop and practicing their first pull request. No build step: `index.html` and `first-pr.html` share a simple deployment root.

## Site flow

- `index.html`: macOS installs Xcode Command Line Tools and VS Code (Homebrew or direct download). Windows installs WSL/Ubuntu, Git in Ubuntu, VS Code on Windows, and Microsoft's WSL extension. Members connect VS Code to Ubuntu before opening the terminal or cloning. Shared steps clone the practice repo, verify Git, tour the editor, and link to the first-PR guide.
- `first-pr.html`: OS-aware GitHub account and SSH setup, clone, branch, create `names/<github-username>.txt`, commit, push, open a PR, handle feedback. Simon must invite a member as a collaborator before that member can push a branch to this repository. The page saves progress in browser localStorage.
- Practice repository: https://github.com/simonteague6/rc-first-pr-practice (public). Contains a README and `names/.gitkeep`; contributions go to individual text files in `names/`.

## Windows rule

The editor is installed on Windows; the WSL extension connects it to Ubuntu. The bottom-left VS Code status bar should read `WSL: Ubuntu`. New terminals inside this remote window run in Ubuntu. Clone under `~/projects`, not `/mnt/c/`. Ubuntu's default Bash is sufficient; no shell change required.

## Maintenance

Keep installation links current, avoid editor-specific screenshots until replacements exist, and test both OS paths after edits. The HTML files are the source of truth. The setup-guide repository is `simonteague6/rc-setup-guide`; GitHub Pages deploys its `main` branch from the repository root.
