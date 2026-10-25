# HeroSupplement

Protein tozu, kreatin, Omega-3 balık yağı ve BCAA satan landing page.

- Düz HTML, CSS ve JavaScript. Framework yok, build adımı yok.
- Kaydırdıkça ilerleyen hero videosu (`assets/hero-scrub.mp4`, telefonda `assets/hero-scrub-mobile.mp4`).
- Siparişler WhatsApp'a hazır mesaj olarak gider. Ödeme: kapıda ödeme ve havale/EFT.
- 4 ve üzeri üründe %15 indirim.

## Yerelde açmak

Kaydırmalı videoyu görmek için klasörü bir yerel sunucuyla aç:

```
npx http-server . -p 8080
```

Sonra tarayıcıda `http://localhost:8080` adresine git. `index.html` dosyasına çift tıklamak videosuz, sabit görselli sürümü gösterir.

## Yayına almadan önce

`index.html`, `robots.txt` ve `sitemap.xml` içindeki `SITE-URL` yazan yerleri canlı adresle değiştir (`DEPLOY STEP` yorumlarına bak).
