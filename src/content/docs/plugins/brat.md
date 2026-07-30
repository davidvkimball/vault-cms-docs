---
title: BRAT
description: Load beta plugins from GitHub repositories.
---

[BRAT](https://github.com/TfTHacker/obsidian42-brat) (Beta Reviewer's Auto-update Tool) installs and manages beta versions of Obsidian plugins and themes directly from GitHub repositories.

Vault CMS uses BRAT for a small number of plugins that cannot come from the official Obsidian community directory:

- The [Vault CMS plugin](/plugins/vault-cms/) itself, which is still in beta.
- The theme settings plugins, Astro Modular Settings and Axis Settings, which ship with their respective themes rather than standing alone.
- The [Data Files Editor](/plugins/data-files-editor/) fork, which is ahead of the version currently in the community directory.

Every other companion plugin is in the official directory and installs and updates through the standard Community Plugins browser.

### Features

- **Install beta plugins** by providing a GitHub repository path.
- **Auto-update** beta plugins and themes at startup.
- **Version freezing** to pin a plugin to a specific release.
- **GitHub token support** for private repositories and higher API rate limits.

### Commands

- **Add a beta plugin for testing**: Install a plugin from a GitHub repository.
- **Check for updates to all beta plugins and update**: Update all tracked plugins.
- **Choose a single plugin version to update**: Update one specific plugin.
- **Restart a plugin**: Reload a plugin without toggling it off and on.
- **Enable/disable a plugin**: Quick toggle for any installed plugin.
- **Open GitHub repository for a plugin**: Open the repo in your browser.
