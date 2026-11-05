<div align="center">

# Jaunchun

**Local-first developer tools. No account, no telemetry.**

[Website](https://codezy.kajtgorski.workers.dev/) · [Latest release](https://github.com/jaunchun/Codezy/releases/latest) · [GitHub](https://github.com/jaunchun) · [npm](https://www.npmjs.com/package/codezy-cli)

</div>

---

## CODEZY

A coding agent for your desktop and terminal, running on the models you already
have. Local **Ollama** by default, any **OpenAI-compatible** endpoint if you
prefer. It reads your folder, proposes real diffs, runs commands, and asks
before it writes.

[**Download the latest CODEZY for Windows →**](https://github.com/jaunchun/Codezy/releases/latest/download/CODEZY-Setup.exe)

[All releases](https://github.com/jaunchun/Codezy/releases) · [Website](https://codezy.kajtgorski.workers.dev/) · [Source](https://github.com/jaunchun/Codezy)

### What it does

- **Agent, chat, plan and auto modes** — switch without restarting the session.
- **Real approvals** — every write and command lands in an approval card first.
- **One palette everywhere** — graphite, paper, contrast and singularity on the
  desktop; the same themes in the terminal.
- **Local by default** — prompts stay on `127.0.0.1` unless you choose a cloud
  provider.
- **Scriptable** — `codezy exec` writes the answer to stdout, activity to
  stderr, and returns stable exit codes.

### Install the CLI

```bash
npm i -g codezy-cli
ollama pull qwen2.5-coder:7b
codezy
```

[`codezy-cli` on npm](https://www.npmjs.com/package/codezy-cli) · [CLI source](https://github.com/jaunchun/codezy-cli)

---

## Links

| | |
| --- | --- |
| **Website** | [codezy.kajtgorski.workers.dev](https://codezy.kajtgorski.workers.dev/) |
| **Download** | [Latest CODEZY release](https://github.com/jaunchun/Codezy/releases/latest) |
| **Direct installer** | [CODEZY-Setup.exe](https://github.com/jaunchun/Codezy/releases/latest/download/CODEZY-Setup.exe) |
| **Desktop source** | [github.com/jaunchun/Codezy](https://github.com/jaunchun/Codezy) |
| **CLI source** | [github.com/jaunchun/codezy-cli](https://github.com/jaunchun/codezy-cli) |
| **npm** | [codezy-cli](https://www.npmjs.com/package/codezy-cli) |

<sub>Built for people who want their tools to stay on their machine.</sub>
