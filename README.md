# Akıl Dostum — Marketing Site

Static landing page for [akildostum.com](https://akildostum.com) — Türkçe yapay zeka destekli Instagram botu.

## Yapı

- `index.html` — Anasayfa
- `privacy.html` — Gizlilik Politikası (KVKK + GDPR uyumlu)
- `terms.html` — Kullanım Şartları
- `style.css` — Paylaşımlı stil
- `logo.svg`, `favicon.svg` — Marka grafikleri
- `vercel.json` — Vercel deploy yapılandırması

## Lokal preview

```powershell
python -m http.server 8080
```

Sonra <http://localhost:8080> aç.

## Deploy

Vercel'e bağlı, `main` branch'e push edilen her şey otomatik deploy olur.
