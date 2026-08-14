# BootstrapAgent raw website

This is a dependency-free static website designed to replace GoDaddy's default "Launching Soon" page.

## Upload to GoDaddy
1. Open GoDaddy Hosting → cPanel / File Manager.
2. Open the domain's `public_html` directory (or the document root for the domain).
3. Remove/rename the existing default `index.html` / placeholder page.
4. Upload `index.html` and `styles.css`.
5. Make sure `index.html` is directly inside the document root.
6. Visit the domain. If the old page still appears, clear the browser/CDN cache.

## Before publishing
- Replace `hello@bootstrapagent.com` with the real inbox.
- Add your final logo/favicon if you have one.
- If the domain uses a different document root, upload there instead.

No framework, build step, database, or npm install is required.
