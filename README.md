# PFS launch pages (T942, T322, T603)

These pages give the phone home-screen icon the PFS logo. Each one opens its app right away, so the logo shows only while Google loads the app. They hold no code or data: every app still asks for the Premier Google sign-in and checks access on PFS HQ.

They are published from the public repo `jdpremier/pfs-launch` with GitHub Pages. That repo is a byte-for-byte copy of this folder. The Hub chat keeps this folder as the source.

| Page | Opens |
|---|---|
| `/` | PFS HQ |
| `/fire/` | Fire Reports Field (`?view=tech`) |
| `/truck/` | Truck Stock (Parts app, `?page=stock&view=check`) |
| `/walk/` | Site Walk |
| `/guide.html` | One-page Add to Home Screen guide; its links add `?add` so the page stays put for saving |

Anything after `?` or `#` on a launch page is passed on to the app. The only exception is `add`.

A new app's deployment ID only changes on a New deployment, which the rules don't allow. So these links stay good across versions.
