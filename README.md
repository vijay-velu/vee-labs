# vee-labs.github.io

> Source for **[vee-labs.github.io](https://vee-labs.github.io)** — the public face of Vee Labs.

---

## What this repo is

This is the GitHub Pages site for [vee-labs](https://github.com/vee-labs).  
No build pipeline. No framework. Just Jekyll + a dark theme + real project content.

The site exists to surface two things clearly:
- What Vee Labs builds
- How it's built

---

## Stack

| Layer | Choice |
| --- | --- |
| Site engine | Jekyll (GitHub Pages native) |
| Theme | [`jekyll-theme-midnight`](https://github.com/pages-themes/midnight) |
| Hosting | GitHub Pages (auto-build on push to `main`) |
| Config | `_config.yml` |

No `npm install`. No CI workflow. Push Markdown, GitHub builds it.

---

## Pages

| File | URL | Purpose |
| --- | --- | --- |
| `index.md` | `/` | Homepage — projects + about |
| `themes.md` | `/themes` | All 13 supported GitHub Pages Jekyll themes |

---

## Projects on the site

**[BreachGuard](https://github.com/vee-labs/BreachGuard)**  
Privacy-first breach monitor. Passwords never leave the device — k-anonymity via HaveIBeenPwned.  
`Flutter · Dart · Firebase · RevenueCat · AdMob`

**[ACServiceApp](https://github.com/vee-labs/ACServiceApp)**  
Field service ticketing for AC technicians. Role-gated UI, real-time Firestore, finance screen, recycle bin.  
`Kotlin · Android · Firebase Firestore · Room · MVVM`

---

## Changing the theme

Edit one line in `_config.yml`:

```yaml
theme: jekyll-theme-cayman
```

Push. GitHub rebuilds in ~60 seconds. All 13 supported themes are listed at [/themes](https://vee-labs.github.io/themes).

---

## Local preview

```bash
gem install bundler jekyll
bundle init
bundle add jekyll jekyll-theme-midnight
bundle exec jekyll serve
```

Visit `http://localhost:4000`.

---

*Built and maintained by [@vee-labs](https://github.com/vee-labs)*
