# Security Policy

## Supported Versions

This project page has no versioned releases. Fixes land on `main` only.

| Version | Supported |
|---|---|
| `main` (the live site) | Yes |
| Older commits | No |

## Reporting a Vulnerability

Please do not report security problems in public issues, discussions, or pull
requests.

Report them privately through GitHub:
[Report a vulnerability](https://github.com/MASkillBlender/maskillblender.github.io/security/advisories/new)
(the **Security** tab, then **Report a vulnerability**).

Include what you can of:

- the affected file or page section, and the commit you tested;
- steps to reproduce, and the browser used;
- the impact, and a suggested fix if you have one.

## What to Expect

- Responses are best effort.
- Updates as the report is triaged and fixed, through the private advisory.
- Coordinated disclosure: the advisory is published once a fix is on `main`,
  with credit to you unless you prefer otherwise.

## Scope

In scope: the page's own HTML, CSS, and JavaScript, and anything in this
repository that could leak identifying information about the authors.

Out of scope: vulnerabilities in the vendored libraries (Bulma, Font Awesome,
Academicons) and in GitHub Pages itself; report those upstream.
