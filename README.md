# Unpause feedback

This is where Unpause players report bugs and crashes and share ideas, thoughts and questions. Unpause's code lives
elsewhere; the conversation lives here, in public, so you can see what others asked for and add your 👍.

**New to Unpause?** Downloads, install steps, update channels, the FAQ and patch notes are in
[unpause-releases](https://github.com/GigaRho/unpause-releases).

## The easy way: from inside Unpause

Open **Settings › Help & feedback** (or **Report this** on the screen Unpause shows after a launch goes wrong). Unpause
fills in the form for you with a diagnostics block: versions, your device, your library in numbers, the last launch
and recent log lines. Game names, folders and your user name are scrubbed out, and you see every line before anything is
sent. You need a free GitHub account to post.

## By hand

| You want to… | Go to |
|---|---|
| Report something that broke | [Bug report](https://github.com/GigaRho/unpause-feedback/issues/new?template=bug.yml) |
| Report a crash (Unpause or a launch) | [Crash report](https://github.com/GigaRho/unpause-feedback/issues/new?template=crash.yml) |
| Suggest a feature | [Ideas](https://github.com/GigaRho/unpause-feedback/discussions/categories/ideas) |
| Ask how to do something | [Q&A](https://github.com/GigaRho/unpause-feedback/discussions/categories/q-a) |
| Share a thought or show your setup | [Discussions](https://github.com/GigaRho/unpause-feedback/discussions) |
| Report a security problem | Privately, see [SECURITY.md](https://github.com/GigaRho/unpause-feedback/blob/main/.github/SECURITY.md) |

Before you post, search the [issues](https://github.com/GigaRho/unpause-feedback/issues?q=is%3Aissue) and [discussions](https://github.com/GigaRho/unpause-feedback/discussions): if someone got there
first, a 👍 on theirs counts, and a comment with your diagnostics helps even more. [How to write a report that gets fixed
fast](https://github.com/GigaRho/unpause-feedback/blob/main/.github/CONTRIBUTING.md).

## What happens next

Every new report gets a first answer within a week. The labels tell you where it stands:

| Label | Meaning |
|---|---|
| `needs-info` | We need something from you to go on; reports that stay silent for a month are closed. |
| `confirmed` | We reproduced it. |
| `planned` | It is on the roadmap; the comment says roughly when. |
| `shipped` | It is in a release; the comment links the patch note. |
| `bug`, `crash`, `regression` | What kind of problem it is (`regression`: it worked in an earlier version). |
| `device:…` | Where it happened; added from your diagnostics. |

Ideas start in Discussions, where people vote on them. The most‑wanted ones become `idea` issues, and those are what
Unpause's "What people asked for" list shows, with their status. Reporters who tick the box are thanked by name in the
patch notes.

## House rules

- Keep game file names, folders and anything personal out of your report.
- Nothing here may point at where to get game files, BIOS files or keys. Such posts are removed.
- Emulator bugs belong on the emulator's own tracker; Unpause reports what it saw when it launched one.
- Be kind: [CODE_OF_CONDUCT.md](https://github.com/GigaRho/unpause-feedback/blob/main/.github/CODE_OF_CONDUCT.md).
