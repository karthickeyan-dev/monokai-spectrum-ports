# Monokai Pro Spectrum Ports

Ports of [Monokai Pro](https://monokai.pro) **Filter Spectrum** for various apps.

Canonical colors live in [`palette/spectrum.json`](palette/spectrum.json). Each app folder is a standalone port.

## Ports

| App | Path |
| --- | ---- |
| [Zed](https://zed.dev/) | [`zed/`](zed/) |
| [OpenCode](https://opencode.ai/) | [`opencode/`](opencode/) |

## Zed

1. Copy `zed/monokai-pro-spectrum.json` into your Zed themes directory:
   - macOS / Linux: `~/.config/zed/themes/`
   - Windows: `%APPDATA%\Zed\themes\`
2. Restart Zed (or reload windows), then pick **Monokai Pro (Filter Spectrum)** from the theme selector.

## OpenCode

1. Copy `opencode/monokai-pro-spectrum.json` into your OpenCode themes directory:
   - macOS / Linux: `~/.config/opencode/themes/`
   - Windows: `%APPDATA%\opencode\themes\`
2. Restart OpenCode, then pick **monokai-pro-spectrum** with `/themes`, or set it in `tui.json`:

```json
{
  "$schema": "https://opencode.ai/tui.json",
  "theme": "monokai-pro-spectrum"
}
```
