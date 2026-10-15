# Fine Findings & Décor coming-soon page

Single static public landing page for Estate & Resale Service. The public heading is provisional website branding; it does not change the LLC's legal name.

## Publication

- Repository: `theojdev1517/ffdcle-site`.
- Established GitHub Pages source: `main`, `/ (root)`, with HTTPS enforced.
- Keep `CNAME` as `www.ffdcle.com`. The existing apex `ffdcle.com` redirects here.
- Deploy by pushing the verified commit to `origin main`; no build dependencies or custom workflow.
- `404.html` routes former or unknown paths to the one current landing page. GitHub Pages returns HTTP 404 for those paths before the browser redirects.
- The former preview at `theotest.ffdcle.com` is retired to a redirect in `theojdev1517/ffdcle-preview`.

## Content and recovery

The only contact link is `sms:+14402303901`. There are no forms, scripts, third-party fonts, analytics, or email integrations.

The previous production source is preserved in Git at `30987e393cd9966f3968fd2860b1d54951a40e64`. Revert the replacement commit to restore it. Old branding assets are removed from the deployed tree. Do not put source archives or old public pages inside the publishing root.

Domain registration, DNS, Google Workspace and Google Voice are managed separately; this site replacement makes no changes to them.