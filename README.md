# shunit.ai

Personal website, served via GitHub Pages at [shunit.ai](https://shunit.ai).

## Setup

Static site — just `index.html`. No build step.

### Deploy (GitHub Pages)

1. Push to the default branch.
2. In the repo's **Settings → Pages**, set the source to the default branch, `/ (root)`.
3. The `CNAME` file points the site at `shunit.ai`. In your DNS provider, add:
   - Four `A` records for the apex `shunit.ai` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - (optional) a `CNAME` record for `www` → `<username>.github.io`
4. Enable **Enforce HTTPS** once the certificate is provisioned.
