# kit-assets

Public asset store for the **kit-m365-tenant-baseline** Windows / Microsoft 365 security baseline.

Holds device-fetchable static files (wallpapers, lock-screen images, branding icons) that Intune
policies reference by **raw GitHub URL**. Those URLs must be reachable **without authentication**, which
is why this repo is public and kept separate from the (private) baseline kit.

**No secrets, ever** — only public branding / UX assets belong here.

## Wallpapers
- `wallpapers/ca-prism-3840x2160.png` — desktop + lock screen (CFG16 Personalization policy).
  `https://raw.githubusercontent.com/Cloud-Architecture-UK/kit-assets/main/wallpapers/ca-prism-3840x2160.png`
- `wallpapers/paw-c-chevron-3840x2160.png` — PAW desktop + lock screen, to visually distinguish a Privileged Access Workstation from a standard device.
  `https://raw.githubusercontent.com/Cloud-Architecture-UK/kit-assets/main/wallpapers/paw-c-chevron-3840x2160.png`
