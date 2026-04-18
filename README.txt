# Familiedans - Taastrup Medborgerhus

En smuk, levende webside til Familiedans arrangementet i Taastrup Medborgerhus.

## 📁 Filer

- `index.html` - Hovedwebsiden (HTML, CSS og JavaScript i én fil)
- `images/` - Mappe til billeder (oprettes automatisk)
- `download_images.py` - Python script til at hente billeder

## 🚀 Sådan bruger du siden

### Mulighed 1: Online hosting (nemmest)
Upload hele mappen (`familiedans/`) til din webhost (GitHub Pages, Netlify, etc.).
Billederne hentes automatisk fra internettet.

### Mulighed 2: Lokalt på din computer
1. Kør scriptet for at hente billeder:
   ```bash
   python download_images.py
   ```
2. Dobbeltklik på `index.html` for at åbne i browseren

### Mulighed 3: Manuel download af billeder
Hvis scriptet ikke virker, kan du downloade billederne manuelt:

1. **Hero billede** (storslået billede øverst):
   https://kimi-web-img.moonshot.cn/img/images.stockcake.com/ec40e6742f4c944b92f47f84c6531f827812d292.jpg
   → Gem som `images/hero.jpg`

2. **Galleri billede 1** (børn med farved tørklæder):
   https://kimi-web-img.moonshot.cn/img/media.istockphoto.com/58f40537971a9ff80b40f981b89c87df0f11531a.jpg
   → Gem som `images/gallery1.jpg`

3. **Galleri billede 2** (børn holder hinanden i hænderne):
   https://kimi-web-img.moonshot.cn/img/thumbs.dreamstime.com/7286a1a10a4ab1bf126eb310a6c69a4eddd136c0.jpg
   → Gem som `images/gallery2.jpg`

4. **Galleri billede 3** (magisk dans):
   https://kimi-web-img.moonshot.cn/img/images.stockcake.com/808693f218777bbb80dd7ea3461411a340c862e1.jpg
   → Gem som `images/gallery3.jpg`

## ✨ Funktioner

- Smuk gradient titel med animation
- Flydende partikler og organisk baggrund
- Biodanza-inspireret farvepalet (vinrød, terrakotta, varme toner)
- Tilmeldingsformular der åbner email til anamahb@gmail.com
- Konfetti-animation ved tilmelding
- Responsivt design (virker på mobil og computer)

## 📧 Kontakt

Spørgsmål? Skriv til anamahb@gmail.com
