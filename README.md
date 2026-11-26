# Does every Collatz sequence reach 1?

Pick a positive whole number. If it is even, halve it. If it is odd, triple it and add one. Does every starting number eventually reach 1?

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/collatz-conjecture/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-collatz-conjecture/pulls)

## Why this matters

A proof that every starting number above 1 eventually drops below itself would settle the conjecture by induction. The starter uses exact algebra to prove this descent for whole families of numbers at once. Terence Tao proved an almost-all result. The conjecture asks about every positive integer.

## What to contribute

Choose one residue class left uncovered by the starter at depth 12. Split it into smaller classes and look for a sequence of steps that takes every member of one subclass below its starting value. Record which cases remain.

## How reviewers check it

Give the residue and modulus, the odd and even steps, and the exact formula for the resulting value. Check the parity at each step and prove strict descent for every starting number above 1 in the claimed class. Report how much previously uncovered territory the certificate covers.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/collatz-conjecture
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/collatz-conjecture/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-collatz-conjecture/security/advisories/new) for security reports.

## Sources

- [Terence Tao on almost all Collatz orbits](<https://arxiv.org/abs/1909.03562>)
- [David Bařina on computational verification of the Collatz problem](<https://doi.org/10.1007/s11227-025-07337-0>)

## Starter

[Check descent for whole families of starting numbers](contributions/collatz-descent/README.md)
