# Heimdal Test Fixtures

This repository contains test fixtures for comprehensive testing of Heimdal.

## Purpose

This repository is used by the Heimdal comprehensive test suite to validate all functionality across multiple platforms.

**IMPORTANT:** The `heimdal.yaml` configuration intentionally **omits** the `repo:` field to validate the v1.1.1 bugfix where the repo field became optional.

## Test Configuration

- **Profile:** test (basic) and development (advanced)
- **Packages:** git, vim, curl, ripgrep, fd-find
- **Dotfiles:** .bashrc, .vimrc, .config/nvim, .config/zsh, .gitconfig
- **Stow compatibility:** enabled

## Usage

This repository is automatically cloned and used by GitHub Actions during Heimdal's comprehensive test workflow.
