# Reply First Digital website

Static site served by GitHub Pages.

- `index.html` — landing page; the request form posts to the Supabase `lead-intake` function
- `privacy/` — POPIA privacy notice
- `demo/` — Seaview Properties AI assistant demo (Supabase `demo-chat` function)
- `.github/workflows/keepalive.yml` — daily ping so the free Supabase project never pauses

To use the custom domain, add a file named `CNAME` containing `replyfirstdigital.co.za` once the domain's DNS points at GitHub Pages.
