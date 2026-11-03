# Contributing

These repositories are small tools, most of them written and maintained by one person. A good
bug report is worth more than a patch, and a small patch that respects the house style is worth
more than a large one that doesn't.

## Reporting a bug

Open an issue with the bug template. Include:

- the version — the release tag, or the version line in the app's About or Check panel
- what it was running on: the Windows build, the Android version, the browser and its version
- the steps that led to it, in order
- what you expected, and what happened instead
- a screenshot, or the log text, if you have one

If it is a security problem, stop and mail **admin@moddys.net** instead of opening an issue.
See [SECURITY.md](SECURITY.md).

## Asking for a feature

Open a feature request and describe the problem before the solution. "I want to do X and I
can't, because Y" tells me more than a mock-up does.

Two kinds of request get declined, politely: anything that needs an account, a cloud service or
telemetry to work, and anything that replaces a small hand-written file with a framework.

## Sending a patch

- **One concern per pull request.** A fix and a refactor in the same diff will be asked to split.
- **Match the file you are editing** — the same naming, the same comment density, the same plain
  HTML/CSS/JS or C# style. There is no formatter to hide behind.
- **Do not bump version numbers, changelogs or release notes.** That happens at release time, in
  one place, so the tag, the notes and the hash all agree.
- **Say how you tested it.** "It builds" is a start; "I ran it on Windows 11 and did X" is better.
- **Licence.** By sending a patch you agree it can ship under the repository's licence — MIT,
  AGPL-3.0-or-later or GPL-2.0-or-later, whichever that repository uses.

## What happens next

Best effort, usually within a week. If a patch sits unanswered for a fortnight, comment on it —
a ping is not rude.

Cheers Moddy !
