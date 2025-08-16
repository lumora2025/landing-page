# aspsri.kr — GitHub Pages landing

Multi-file static site ready for GitHub Pages.

## Structure
```
aspsri-landing/
├─ index.html
├─ assets/
│  ├─ css/style.css
│  └─ js/main.js
├─ CNAME
└─ README.md
```

## Deploy
1. Create a **public** repo (e.g., `aspsri-landing`) and upload all files.
2. GitHub **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `(root)` → **Save**
3. In **Custom domain**, set **aspsri.kr** and **Save**.
4. In your DNS, set A (and optional AAAA) records to GitHub Pages IPs. When it’s active, enable **Enforce HTTPS**.

## DNS (root `aspsri.kr`)
A:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
AAAA (optional):
```
2606:50c0:8000::153
2606:50c0:8001::153
2606:50c0:8002::153
2606:50c0:8003::153
```

## Optional `www`
```
www  CNAME  <your-github-username>.github.io
```

© 2025 Lumora
