# chrisshi.com — placeholder

Holding page for chrisshi.com while the main site stays at
[czhs.github.io](https://czhs.github.io/) (source: `czhs/czhs.github.io`).

To hand the domain back to the real site:
1. Clear the custom domain on this repo (Settings -> Pages), or delete this repo.
2. Restore the root `CNAME` file containing `chrisshi.com` in `czhs/czhs.github.io`
   and set `url:` in `_config.yml` back to `https://chrisshi.com`.

Cloudflare DNS needs no changes either way; it already points at GitHub Pages.
