# cantala.app

Public marketing + legal site for the Cántala iOS / Android app.

- `/privacy/` — Privacy Policy
- `/terms/` — Terms of Service

## DNS

The `CNAME` file binds this Pages site to `cantala.app`. To finish:

1. Repo Settings → Pages → Source = `main` branch, root.
2. DNS for `cantala.app`:
   - `A` records pointing apex to GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` → `roy-yogev.github.io`
3. Wait for the GitHub HTTPS cert to provision (a few minutes).

Until DNS resolves, the site is also reachable at `https://roy-yogev.github.io/pages/`.
