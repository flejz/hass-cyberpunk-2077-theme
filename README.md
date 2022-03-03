# Cyberpunk 2077 Home Assistant Theme

[![Build Status](https://github.com/flejz/hass-cyberpunk-2077-theme/workflows/.github/workflows/workflow.yml/badge.svg)](https://github.com/flejz/hass-cyberpunk-2077-theme/actions)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

> The Cyberpunk 2077 Theme by @flejz

## Reference GUI

![Reference](docs/reference.png)

## Screenshots

### Overview

![Theme - Overview](docs/theme-overview.png)

### Logbook

![Theme - Logbook](docs/theme-logbook.png)

### History

![Theme - History](docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](docs/theme-configuration.png)

### Profile

![Theme - Profile](docs/theme-profile.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Cyberpunk 2077`.
3. Navigate to `Cyberpunk 2077` theme.
4. Press `Install`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/flejz/hass-cyberpunk-2077-theme.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/flejz/hass-cyberpunk-2077-theme.git
```

### Font

Optionally you can add the [Rajdhani](https://fonts.google.com/specimen/Rajdhani) font as a resource to have yet a closer experience:

`https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap`
