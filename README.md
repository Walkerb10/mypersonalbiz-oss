# MyPersonalBiz — open source starter (v1)

The core loop, open and free: name your business, pick a color, see it live.
No account, no backend, no build step — one HTML file you can open directly
in a browser or drop on any static host.

This is the open piece of a bigger idea. The full hosted platform at
[mypersonalbiz.com](https://mypersonalbiz.com) builds on this same loop with
real accounts, a real address for your business, and a done-for-you tier
where a real person actually builds and iterates on your site for you. This
repo is the part that should always be free and yours to run: the "name it,
brand it, see it" moment, with nothing locked behind a login.

## Run it

```bash
open index.html
```

That's the whole install. No dependencies, no `npm install`, no server.

## What this is not (yet)

This v1 is intentionally bare: no persistence beyond your own browser
(`localStorage`), no real hosting/domain provisioning, no payments, no
multi-user accounts. Those are the pieces that make the hosted product a real
business rather than a demo, and they're deliberately not in scope for v1.
Contributions toward a real, self-hostable version (a backend, real deploys,
real accounts) are welcome — open an issue with what you want to build before
sending a large PR, so effort doesn't collide.

## License

MIT — see [LICENSE](./LICENSE). Use it, fork it, build your own thing on it.
