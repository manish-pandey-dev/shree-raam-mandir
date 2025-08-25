# Shree Raam Mandir — Temporary Under Construction Page

This repository hosts a single static page for **GitHub Pages** and maps to the custom domain **shreeraammandir.nl**.

## Deploy Steps (quick)
1. Create a repo on GitHub (public): `mandir-landing` (any name is fine).
2. Upload `index.html` and `CNAME` to the repo root.
3. In the repo: Settings → Pages → Source: **Deploy from branch** → Branch: **main** → **/ (root)**.
4. In **Custom domain**, enter: `shreeraammandir.nl` and save. HTTPS will be configured automatically when DNS is correct.
5. In your **Namecheap** DNS, set:
   - Four **A** records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One **CNAME** record for `www` → `<your-github-username>.github.io`
6. After DNS is active, your domain will load this page.
