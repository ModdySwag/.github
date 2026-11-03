# Security policy

## Supported versions

The latest release of each project gets fixes. Older releases stay downloadable so nothing
disappears, but they are not patched. If you are on an old build, updating is the first step of
any report.

## Reporting a problem

**Do not open a public issue.** Mail **admin@moddys.net** with `SECURITY` at the start of the
subject line, and include:

- the project and the version (release tag, or the version line in the app)
- what the problem lets someone do
- the steps to reproduce it, or a proof of concept
- what it was running on
- how you would like to be credited, or "no credit"

You will get an acknowledgement within seven days. If a fix is needed you will get either a
patch or an explanation of why it is not a bug, and a rough date for the release. If you ask to
be credited, the release notes will name you when the fix ships.

## In scope

| Area | Examples |
|:--|:--|
| The applications | A malicious radio stream, feed or podcast URL that escapes its sandbox; a parser crash that is reachable from remote data |
| The installers | A build that writes outside its own directory, or an uninstaller that leaves something running |
| The update feeds | A way to make an app fetch and run something that did not come from this account |
| Keys and sessions | A path that writes credentials, session files or SSH keys somewhere they can be read by another user |

## Out of scope

- Anything that needs physical access to an unlocked machine, or an already-compromised account.
- Findings from an automated scanner with no working case behind it.
- Third-party services the apps talk to (a station's stream host, a podcast's feed host, GitHub,
  Cloudflare).
- Social engineering of anyone who works on these projects.

## No bounty

There is no bug bounty. There is a thank-you, a credit in the release notes, and a fix as fast as
one person can write it.
