# Dotfiles

NixOS system and user configuration for my Arch Linux WSL setup, managed with Nix flakes.

## What It Does

Declaratively configures a complete WSL development environment — system settings, shell, editor, and developer tools — all reproducible from a single `flake.nix`.

## What's Configured

### System (`system/`)
- Locale, networking, security hardening
- Podman container runtime
- User accounts and permissions
- WSL-specific settings

### User — hanna (`users/hanna/`)
- **Shell:** Starship prompt, custom shell config
- **Editor:** Helix
- **Tools:** btop, direnv, fastfetch, git, jj (version control), lsd, npm
- **XDG:** Proper XDG directory setup

## Tech Stack

- **Language:** Nix
- **System:** NixOS on WSL
- **Tools:** Nix Flakes, Home Manager

