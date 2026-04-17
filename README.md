# geeViz Agent — Public Pages

Public-facing pages for the [geeViz Agent](https://geevizagent.askterra.io/geeviz) geospatial analysis assistant. Hosted via GitHub Pages at `policies.askterra.io`.

## Pages

| Page | URL | Purpose |
|------|-----|---------|
| Homepage | `policies.askterra.io/` | Product overview, feature list, link to the agent |
| Privacy Policy | `policies.askterra.io/privacy.html` | Data collection, retention, and contact info |
| Terms of Service | `policies.askterra.io/terms.html` | Acceptable use, disclaimers, IP |

## Why these exist

Google's OAuth consent screen requires publicly accessible privacy policy and terms of service URLs. The geeViz Agent itself is behind Identity-Aware Proxy (IAP), so these pages are hosted separately on GitHub Pages to be accessible without authentication.

## Setup

1. Push this repo to GitHub
2. Enable GitHub Pages (Settings → Pages → Source: main branch)
3. Set custom domain to `policies.askterra.io`
4. Add Cloudflare CNAME: `policies` → `<username>.github.io` (DNS only)
5. Update OAuth branding with the policy URLs

## Updating

Edit the HTML files directly and push. GitHub Pages deploys automatically.
