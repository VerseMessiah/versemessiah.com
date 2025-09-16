# VerseMessiah — Static Site (GitHub Pages)

This is a minimal, professional landing site for **versemessiah.com**.

## Quick deploy
1. Create a **public** GitHub repo (e.g., `versemessiah-site`).
2. Upload these files (or drag the ZIP contents). Ensure `index.html` is at repo root.
3. In **Settings → Pages**, set **Source** = Deploy from a branch; **Branch** = `main` (root). Save.
4. In **Settings → Pages → Custom domain**, enter `versemessiah.com` and Save (adds a `CNAME` file).
5. Configure DNS at your registrar (apex domain): create **A** records to:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
   (Optional) add AAAA records if your registrar supports GitHub Pages IPv6 endpoints.
6. Wait for DNS + HTTPS. Then your site is live on `https://versemessiah.com`.

— You can edit text directly in `index.html` and `privacy.html`. Styling is in `styles.css`.
