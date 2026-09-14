# DataPorter website

Public site for **https://dataporter.info** — DataPorter is a data migrator.

Static HTML/CSS hosted on GitHub Pages ($0). Custom domain: `dataporter.info`.

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

## DNS for dataporter.info

At your registrar or Cloudflare DNS, point the apex at GitHub Pages:

**A records** for `@` / `dataporter.info`:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

**AAAA records** (optional):

- `2606:50c0:8000::153`
- `2606:50c0:8001::153`
- `2606:50c0:8002::153`
- `2606:50c0:8003::153`

**CNAME** for `www` → `sinhaashish.github.io`
