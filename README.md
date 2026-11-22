# Gemini 4 Neon for T3 Code

A true neon-gas orange theme for [T3 Code](https://github.com/pingdotgg/t3code) (web & desktop), inspired by the warm incandescent glow of a real glass neon tube against a dark smoked-umber wall.

## Highlights

- **True neon-gas palette:** Smoked obsidian-umber canvas (`#0b0705`) lit by incandescent neon orange (`#ff6a1a`), ember falloff, and cream-hot (`#ffe7c4`) highlights.
- **Glowing composer bar:** Always-on layered neon-tube glow on the prompt bar that gently hums/pulses when focused (`opacity`-only GPU-composited animation, respecting `prefers-reduced-motion`).
- **Dual-mode ready:** Includes a warm alabaster `variants.light` (`#fdf8f3`) with burnt-orange (`#d94b0c`) accents.
- **Release-safe CSS:** Targets only T3 Code's documented stable `data-*` selectors and semantic color roles.

## Install

### Option 1: Publish as an environment theme (recommended)

```bash
mkdir -p ~/.t3/userdata/themes
curl -fsSL https://raw.githubusercontent.com/itsthecsguy/t3code-neon-theme/main/gemini-4-neon.json \
  -o ~/.t3/userdata/themes/gemini-4-neon.json
t3 theme set gemini-4-neon
```

### Option 2: Import in the T3 Code UI

1. Download [`gemini-4-neon.json`](./gemini-4-neon.json).
2. Open **Settings → Appearance → Import theme** in T3 Code and select the file.

### Switch back / uninstall

Press **Cmd+Option+A** (macOS) or **Ctrl+Alt+A** (Linux/Windows) to pick another theme, or run:

```bash
t3 theme set t3-code
```

## Palette

| Role | Dark | Light |
| --- | --- | --- |
| `canvas` | `#0b0705` | `#fdf8f3` |
| `sidebar` / `chrome` | `#100906` | `#f8efe6` |
| `surface` | `#140c08` | `#fffaf5` |
| `accent` | `#ff6a1a` | `#d94b0c` |
| `messageSurface` | `#24130b` | `#f7e6d7` |
| `codeBackground` | `#130b07` | `#f7ede3` |
| `terminalBackground` | `#090503` | `#fcf4ec` |
| `terminalCursor` | `#ffe7c4` | `#d94b0c` |

## License

[MIT](./LICENSE)
