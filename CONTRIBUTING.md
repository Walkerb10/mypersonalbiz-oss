# Contributing

This moves slower than the hosted platform on purpose — the paid product at
[mypersonalbiz.com](https://mypersonalbiz.com) is where fast iteration
happens; this repo is the part meant to be shared, reviewed, and built on
by other people, which means changes here get read carefully, not shipped
fast.

## Before you write code

Open an issue first if the change is more than a small fix. Say what you
want to build and why. This avoids two people building the same thing, and
avoids a large PR getting rejected after the work is already done because it
didn't fit where the project is headed.

Small, obvious fixes (a typo, a broken link, an accessibility bug) can just
be a PR directly.

## What belongs here vs. what doesn't

This repo is the **core loop only**: name a business, brand it, see it live,
no account required. That boundary is deliberate, not an oversight — real
accounts, real payments, real hosting/domains, and a done-for-you human
service are what make the hosted platform an actual business, and they stay
there. Contributions that try to add a backend, accounts, or payments to
this repo will get redirected rather than merged; that's a different project
than what this one is for.

Good contributions:
- Making the core loop itself better (the form, the preview, the interaction)
- Accessibility, performance, browser-compatibility fixes
- Documentation, translations
- A genuinely separable improvement to the visual design

## Code style

Plain HTML/CSS/JS, no build step, no dependencies. Keep it that way — the
entire point of this repo is "open it directly in a browser," and a build
step or a package.json is the first thing that breaks that promise.

## Questions

Open an issue. There's no separate contributor chat yet — if this repo gets
enough activity to need one, that'll get set up then, not preemptively.
