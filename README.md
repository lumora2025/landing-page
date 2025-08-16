# aspsri.kr — GitHub Pages landing (with diagram)

Multi-file static site ready for GitHub Pages, including the concept diagram.

## Structure
```
aspsri-landing-with-diagram/
├─ index.html
├─ assets/
│  ├─ css/style.css
│  ├─ js/main.js
│  └─ img/sig-flow.png
├─ CNAME
└─ README.md
```

## Deploy
1. Create a **public** repo and upload all files (keep **CNAME** as `aspsri.kr`).
2. GitHub **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `(root)` → **Save**
3. In **Custom domain**, set **aspsri.kr** and **Save**.
4. In your DNS, set A (and optional AAAA) records to GitHub Pages IPs. When it’s active, enable **Enforce HTTPS**.

© 2025 Lumora
