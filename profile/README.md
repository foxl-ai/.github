<div align="center">

<img src="./foxl-mark.png" width="88" height="88" alt="Foxl" />

# Foxl

### Ask for the outcome. Get the finished work.

An AI agent that lives on your own machine, keeps working while you are away,
and answers when you check in from your phone.

[foxl.ai](https://foxl.ai) &nbsp;·&nbsp;
[Web app](https://app.foxl.ai) &nbsp;·&nbsp;
[Foxl Code](https://code.foxl.ai) &nbsp;·&nbsp;
[Docs](https://docs.foxl.ai) &nbsp;·&nbsp;
[Status](https://status.foxl.ai) &nbsp;·&nbsp;
[Discord](https://discord.gg/6J53VyV2Fy)

<a href="https://github.com/foxl-ai/foxl/releases/latest"><img alt="Latest Foxl release" src="https://img.shields.io/github/v/release/foxl-ai/foxl?style=flat&label=latest%20release&color=0969E3&logo=github&logoColor=white" /></a>
<a href="https://github.com/foxl-ai/foxl/releases"><img alt="Total downloads" src="https://img.shields.io/github/downloads/foxl-ai/foxl/total?style=flat&label=downloads&color=0969E3&logo=github&logoColor=white" /></a>
<a href="https://foxl.ai"><img alt="Runs on macOS, Windows, Linux, iOS and Android" src="https://img.shields.io/badge/macOS%20%7C%20Windows%20%7C%20Linux%20%7C%20iOS%20%7C%20Android-0969E3?style=flat&label=runs%20on" /></a>
<a href="https://docs.foxl.ai"><img alt="Documentation" src="https://img.shields.io/badge/docs.foxl.ai-0969E3?style=flat&label=docs&logo=readthedocs&logoColor=white" /></a>
<a href="https://discord.gg/6J53VyV2Fy"><img alt="Join the Foxl Discord" src="https://img.shields.io/badge/join%20us-5865F2?style=flat&label=discord&logo=discord&logoColor=white" /></a>

</div>

<br />

## Agents for the rest of us

Agents today are built for the people who build agents. They live in terminals,
behind API keys and configuration files, and they ask you to learn a new
vocabulary before they will do a single thing for you.

We think that is backwards. An agent should sit where the work already is: your
files, your terminal, a real browser with your logins already in it, the apps
you open every morning. It should keep going while you are asleep, and it should
be able to show you what it did in the time it takes to unlock a phone.

That is the barrier we are taking away. Not the model and not the tooling, but
the distance between an ordinary person and an agent that actually finishes
something.

We call it **agents for the rest of us**, because the hard part should belong to
us and never to the person asking.

<br />

## What we build

| | | |
|---|---|---|
| **Foxl Desktop** | A local-first agent that runs 24/7 on your own machine. Multi-provider chat, a real browser it can drive, an approval-gated shell, built-in tools, installable skills, and a scheduler for work that should happen without you. | [foxl.ai](https://foxl.ai) |
| **Foxl Notes** | AI meeting notes that just work. Records the meeting, transcribes it, and writes it up with the context your chat already has. | [foxl.ai/notes](https://foxl.ai/notes) |
| **Foxl Code** | From a task. To a pull request. Cloud coding agents that pick up an issue, work in parallel, and hand back changes you review like any other PR. Private beta. | [code.foxl.ai](https://code.foxl.ai) |

One version number, one changelog, three products that share the same agent.

<br />

## What we hold to

- **Local-first.** Conversations, files, memory and API keys stay on your
  device. The desktop app runs on your machine, not in our cloud.
- **Bring your own model.** Claude, GPT, Gemini, or a model running locally on
  your own hardware. Your keys, your choice.
- **Ask before acting.** Shell commands and browser actions are approval-gated.
  An agent with real access needs a real brake.
- **Reachable, not exposed.** Check in from any browser on your phone through an
  encrypted relay. Your work does not move to reach you.
- **Auditable where it counts.** The pieces that ask for access to your machine
  are public, even though the product is not.

<br />

## Open at the edges

| Repository | What it is |
|---|---|
| [**foxl**](https://github.com/foxl-ai/foxl) | Desktop releases for macOS, Windows and Linux, plus the iOS TestFlight build and the Android APK |
| [**skills**](https://github.com/foxl-ai/skills) | The installable skill library the agent loads. MIT-0 |
| [**browser-extension**](https://github.com/foxl-ai/browser-extension) | Lets the agent act in your real Chrome tabs. Apache-2.0, auditable |
| [**homebrew-tap**](https://github.com/foxl-ai/homebrew-tap) | The Homebrew cask, published by the release pipeline |
| [**signal-cli**](https://github.com/foxl-ai/signal-cli) | A lightweight Signal CLI in Rust, with MCP support |

<br />

## Start in one line

```sh
brew install --cask foxl-ai/tap/foxl
```

Or take the direct download for
[macOS](https://github.com/foxl-ai/foxl/releases/latest/download/Foxl-latest-universal.dmg),
[Windows](https://github.com/foxl-ai/foxl/releases/latest/download/Foxl-latest-setup.exe),
[Linux](https://github.com/foxl-ai/foxl/releases/latest/download/Foxl-latest.AppImage),
[iOS](https://testflight.apple.com/join/VpG4EK19) or
[Android](https://github.com/foxl-ai/foxl/releases/latest/download/Foxl-latest.apk).
Nothing to install to try it in a browser: [app.foxl.ai](https://app.foxl.ai).

<br />

## Talk to us

Bug reports and feature requests are welcome in the
[Discord](https://discord.gg/6J53VyV2Fy). Anything else:
[support@foxl.ai](mailto:support@foxl.ai).

<div align="center">
<br />
<sub>Built by <a href="https://github.com/foxl-ai">foxl-ai</a> in San Francisco. No cloud lock-in. Your work stays on your machine.</sub>
</div>
