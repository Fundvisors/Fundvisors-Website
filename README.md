# Fundvisors — the path from idea to a running business

A static site (`index.html` + `assets/logo.png` — no build step, no dependencies) built for GitHub Pages. The page is built around one idea: a business travels a path from "idea" to "running business," illustrated with original artwork, and Fundvisors' six services sit at the exact points founders get stuck along it.

## Host it on GitHub Pages (free)

1. Create a new GitHub repository, e.g. `fundvisors-site` (or `yourusername.github.io` for the root of your GitHub domain).
2. Upload **both** `index.html` and the `assets/` folder (with `logo.png` inside) to the repo, keeping the same structure:
   ```
   git add .
   git commit -m "site"
   git push
   ```
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
6. Within a minute, GitHub shows your live URL at the top of that page — typically:
   `https://yourusername.github.io/fundvisors-site/`

Any time you edit `index.html` and push, the live site updates automatically.

## What's on the page

- **Sticky nav** with your logo, phone number, and a "Get support" button
- **Hero illustration** — an original hand-built SVG scene: a winding road climbing hills from a lightbulb (idea) up to a flag at the summit, with six numbered milestones along the way and a little walking figure — no stock photography, so nothing to license
- **Wavy stepper strip** with a soft illustrated background, previewing all 8 points on the journey
- **The path** (main section) — a vertical, alternating timeline over a soft dot-grid backdrop. Every marker is a two-tone illustrated icon with a soft glow behind it, growing and tilting slightly on hover
- **Asset Verification & Tagging** — a dedicated spotlight section for this specialist service (physical asset verification, barcode/QR tagging, reconciliation reporting, audit-ready documentation), with its own illustration and a WhatsApp CTA, positioned as an add-on alongside the six core path services
- **Why Fundvisors strip** — with matching glowing icon badges
- **FAQ accordion** — five real, informative Q&As
- **Contact band** with a subtle rising-growth-line illustration behind the content, plus email, phone and a WhatsApp CTA
- **Floating WhatsApp widget** (bottom-right)
- Fully responsive — the path timeline collapses to a single left-aligned column on mobile, and the hero illustration hides gracefully on small screens

## A note on the artwork

Everything visual on this page — the road illustration, the stepper wave, every icon — is original SVG built for this site, not stock photography. That keeps the page copyright-clean and fast-loading (no image downloads at all), and matches your red-and-black theme exactly. If you'd like real photography added later (your team, your office), send the photos over and I can slot them in.

## Before you go live, check

- Confirm `support@fundvisors.com` and `+91-9953879916` are correct everywhere (search `index.html` if you ever need to change them).
- Each stage's WhatsApp link has its own pre-filled message — edit the `text=` query parameter on any `wa.me` link to change it.
- The FAQ answers are general, accurate information about Indian business registration — update the text inside `<div class="faq-a">` if your actual process differs.
- **Custom domain (optional)** — if you own a domain, add a `CNAME` file to the repo containing just that domain, then point your DNS at GitHub Pages per [GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
