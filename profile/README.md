# Wherefore

**Your product changes. Your site, docs and deck don't.**

Code has one source of truth and a pipeline that checks every change.
Everything else your company says - the site, the docs, the deck, the app's
own words - is a copy of a copy, and every copy drifts. Wherefore gives the
rest of your company the pipeline your code already has: change something
once, and everything that says it follows.

Agents already run your code's pipeline. Wherefore lets them run the rest.

**See what has already drifted on your site.** No setup, no account:

```
curl -fsSL https://wherefore.sh | sh
wherefore scan https://your-site.example
```

Or with pip: `pip install wherefore-build`

| | |
|---|---|
| [**wherefore**](https://github.com/wherefore-build/wherefore) | The engine: the command line, its checks, and the skill that teaches Claude Code and Codex the rules. Apache-2.0, on PyPI as `wherefore-build`. |
| [**web**](https://github.com/wherefore-build/web) | [wherefore.build](https://wherefore.build), compiled by Wherefore from one facts file - a real client to read. |

[wherefore.build](https://wherefore.build) · [Changelog](https://wherefore.build/changelog/) · [Contributing](https://github.com/wherefore-build/wherefore/blob/main/CONTRIBUTING.md)
