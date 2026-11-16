# Contributing to WeWriteApp/.github

This repository holds the WeWrite organization's community health files. It has no app code. The two files that matter most are the organization readme (`README.md`) and the profile readme shown on the [WeWriteApp organization page](https://github.com/WeWriteApp) (`profile/README.md`).

## Setup

There is nothing to install. This repo is Markdown files only, with no build, test suite, or deploy.

```bash
git clone https://github.com/WeWriteApp/.github.git
cd .github
git checkout main
```

Edit with any text editor. Preview Markdown before you open a pull request so headings, links, and lists render as intended.

## Branch and pull request flow

- `main` is the default branch. Open every pull request against `main`.
- Work on a short-lived branch off `main`, for example `docs/short-name`.
- Keep each pull request to one change. Say what changed and why.
- Do not push directly to `main` and do not force-push.
- Do not merge your own pull request without review.

## What to change, and what not to

- Good changes: fixing a broken link or outdated fact in the profile readme, improving the wording, adding an organization-wide template.
- Keep edits small and focused. Do not rename, move, or rewrite files that are not part of the requested change.
- Check every link you add or change. Never guess a URL.
- Never add a secret, token, password, or private key to any file.
- Never promise a feature, date, or price in the profile readme unless it has been confirmed.

## Code style

- Plain language, short sentences, short paragraphs.
- Match the tone of the existing profile readme: welcoming, plain, and about what WeWrite is.
- Use one top-level heading per file and keep heading levels in order.

## Review expectations

- A reviewer checks that the wording is accurate, links work, and the change does only what the pull request says.
- Answer review comments on the pull request. If you disagree with a requested change, say why in the thread instead of ignoring it.
- A pull request is ready to merge when review comments are resolved and it changes only what it sets out to change.
