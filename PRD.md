# RC Setup Guide

## Goal

Get a new Rowdy Creators member from a fresh macOS or Windows laptop to a working VS Code environment, then through a first GitHub pull request. Keep the first contribution to one text file so the focus stays on the Git workflow.

## Paths

- macOS: Xcode Command Line Tools (Git), optional Homebrew, VS Code, open the integrated terminal and clone the practice repo. If `code .` is unavailable, install the VS Code shell command from the Command Palette.
- Windows: install WSL/Ubuntu first. If installation fails because virtualization is disabled, use the collapsed BIOS troubleshooting guide. Then update Ubuntu and install Git, install VS Code on Windows, install Microsoft's WSL extension, and connect using `WSL: Connect to WSL`. Open VS Code's integrated terminal with Ctrl+backtick and clone under the Linux home directory. Check `WSL: Ubuntu` in the status bar before working; do not use `/mnt/c/` for projects.
- Shared: clone `simonteague6/rc-first-pr-practice` to `~/projects`, verify `git status`, tour Explorer, Command Palette, Source Control, and terminal. Next Steps keeps links to introductory Git resources and `first-pr.html`.

## First PR

The public practice repo has a `names/` folder. A member asks Simon for collaborator access, configures Git and SSH, creates a branch, adds `names/<github-username>.txt` with any short sentence, commits and pushes it, then opens a pull request. The guide covers review, merge, sync, and common failures. No HTML authoring is required. Each member uses a unique filename.

## Delivery

Static HTML and CSS, no build step. Text-based editor and WSL connection instructions until accurate VS Code screenshots are available. Copy buttons for commands, accessible OS-specific instructions, and progress tracking in the first-PR guide. GitHub Pages publishes the root of `main` from `simonteague6/rc-setup-guide`.
