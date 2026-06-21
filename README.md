<p align="center">
  <img src="https://backgrind.com/logo.svg" width="84" alt="Backgrind logo" />
</p>

<h1 align="center">Backgrind</h1>

<p align="center">
  <strong>Code while you grind.</strong> Run your AI coding agent — Claude Code or Cursor —
  in an always-on-top overlay over any game.
  <br />
  <a href="https://backgrind.com"><strong>backgrind.com</strong></a> ·
  <a href="https://backgrind.com/#demo">Live demo</a> ·
  <a href="../../releases"><strong>Download</strong></a>
</p>

---

Backgrind is a desktop overlay (macOS & Windows) that floats your **AI coding agent** — a real
terminal, file tree, and code preview — over any borderless-fullscreen app, games included. The
agent grinds through your repo in the background; the window flashes and chimes **only when it
needs a decision**. No more babysitting a terminal, no more alt-tabbing every ninety seconds.

## Features

- 🎮 **Always-on-top overlay** over borderless-fullscreen games — summon and hide with a hotkey.
- 👻 **Click-through "glance" mode** — the window fades and your mouse/keys pass to the game.
- 🧠 **Bring your own CLI** — wraps the real Claude Code / Cursor login you already have.
- 📱 **Live mode** (Plus) — drive your agents from any browser/phone, **end-to-end encrypted**.
- ⚡ **Hosted Grindy models** (Pro) — `grindy-1` and `grindy-1-pro`, no API key needed.
- 🗂 **Workspaces & parallel agents** — several tasks grinding at once, tabbed.
- 🔔 **Ambient notifications** — a flash + chime when an agent needs a yes/no or finishes.
- 🎙 **Push-to-talk voice input** — on-device Whisper, nothing leaves your machine.
- 🔒 **`.grindignore`** — paths listed there (your `.env`, keys) never leave the machine.

## Download

These always point at the **latest** release:

- 🍎 **macOS — Apple Silicon**: **[Download .dmg](https://github.com/Backgrind/backgrind/releases/latest/download/Backgrind-mac-arm64.dmg)**
- 🍎 **macOS — Intel**: **[Download .dmg](https://github.com/Backgrind/backgrind/releases/latest/download/Backgrind-mac-intel.dmg)**
- 🪟 **Windows** (x64): **[Download .exe](https://github.com/Backgrind/backgrind/releases/latest/download/Backgrind-windows.exe)**

All builds + release notes: **[Releases](../../releases/latest)**. The **Free** tier is a full demo —
connect your own Claude Code or Cursor CLI and try it over a real game.

## Will it get me banned?

No — and the *how* matters. Backgrind is a plain always-on-top window composited by the OS, the
same mechanism as picture-in-picture video. It **never reads game memory, never injects code into
the game process, and never automates input** — the behaviors anti-cheat actually looks for. The
game just runs underneath an ordinary window. Long version:
[Will a coding overlay get me banned?](https://backgrind.com/blog/will-a-coding-overlay-get-me-banned)

The one requirement: the game must run in **borderless fullscreen** (not exclusive). Identical
picture, ten seconds in the video settings — explainer:
[Borderless vs exclusive fullscreen](https://backgrind.com/blog/borderless-vs-exclusive-fullscreen).

## Privacy

Local-first by design. In bring-your-own-CLI mode your agent talks **directly to your provider** —
prompts, code, and history never touch Backgrind's servers; the overlay is a thin client that
renders and forwards. Only the hosted Grindy models (Pro) send prompts to our backend, and
`.grindignore` still applies. Details: [Privacy Policy](https://backgrind.com/privacy).

## Pricing

| Plan | Price | What you get |
| --- | --- | --- |
| **Free** | $0 | The full overlay with your own Claude Code / Cursor. 1 agent, session-only — nothing saved between launches. |
| **Plus** | **$9/mo** | The complete local app: workspaces, unlimited parallel agents, voice, customization, and **Live mode** — drive your agents from any browser, end-to-end encrypted. Bring your own CLI. |
| **Pro** | **$59/mo** | Everything in Plus **+ Grindy**: the hosted **`grindy-1` · `grindy-1-pro`** models (no API key needed) and cloud chat sync. |

Full comparison: [backgrind.com/#pricing](https://backgrind.com/#pricing).

## Learn more

- [How to run Claude Code while playing a game](https://backgrind.com/blog/run-claude-code-while-gaming)
- [Live demo — whack a grindloc while the agent works](https://backgrind.com/#demo)
- Questions: [hello@backgrind.com](mailto:hello@backgrind.com)

## License

See [LICENSE](LICENSE). Backgrind is a closed-source product; this repository hosts the downloads
and this page.
