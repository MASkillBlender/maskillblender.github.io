# Contributing

Thanks for helping improve the MASkillBlender project page. This guide covers
how to propose a change and what a change must satisfy before it is merged.

By taking part you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
Report security problems privately as described in [SECURITY.md](SECURITY.md),
never in a public issue.

## Ways to Contribute

- **Report a problem**: open an issue with the page section, what you
  expected, what you saw, and your browser and device.
- **Suggest a change**: open an issue first for anything larger than a small
  fix, so the approach can be agreed before you write it.
- **Send a pull request**: fixes to typos, broken links, layout, and
  accessibility are all welcome.

## Development Setup

There is nothing to build. Serve the repository root and open the page:

```bash
python3 -m http.server 8000
# then open http://127.0.0.1:8000/
```

## Workflow

1. Fork the repository and clone your fork.
2. Wire up the commit template: `git config commit.template .gitmessage`.
3. Optionally create a short-lived branch off `main`, named per the Branch
   Naming section of `.gitmessage` (`<type>/<short-desc>`, for example
   `bugfix/video-grid-mobile`); the `git-branch-create` skill does this for you.
4. Commit in the `.gitmessage` format, `<type>(<scope>): <subject>`, one
   logical change per commit; the `git-commit` skill drafts these for you.
5. Push to your fork and open a pull request against `main`. Describe what
   changed and why, and link the issue it resolves.

## Change Rules

- **Anonymity**: never add a personal name, email address, affiliation,
  personal account, or identifying link, in files, commit messages, or media
  metadata. Author and copyright text says `MASkillBlender`.
- **Vendored files**: leave the third-party files under `static/` unchanged;
  edit `static/css/index.css` and `static/js/index.js` instead.
- **Artifacts**: code, comments, skills, and in-repo docs are English and
  ASCII only; README files may use emoji, as `AGENTS.md` (Conventions)
  describes.
- **One source**: edit canonical files only (`AGENTS.md`, `.agents/skills`),
  never an adapter.
- **Docs move with the change**: when a change makes a doc inaccurate, fix it
  in the same pull request.

## Before You Open a Pull Request

- [ ] The page renders in the local preview, on desktop and phone widths.
- [ ] No non-ASCII text outside the README files:
      `LC_ALL=C git grep -nI --untracked '[^[:print:][:space:]]' -- . ':!README.md' ':!static'`
      prints nothing.
- [ ] Commit messages follow `.gitmessage`.

## License

Contributions are accepted under the repository's
[CC BY-SA 4.0 license](LICENSE).
