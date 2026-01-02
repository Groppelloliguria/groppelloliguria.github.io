# Cartella Immagini

Questa cartella contiene le immagini utilizzate nel sito web.

## Immagini Obbligatorie

### Open Graph Image
**File richiesto**: `og-image.jpg`  
**Dimensioni**: 1200x630px  
**Descrizione**: Immagine utilizzata quando il sito viene condiviso sui social media (Facebook, Twitter, LinkedIn, etc.)

### Favicon
**File richiesto**: `favicon.ico`  
**Dimensioni**: 32x32px o 16x16px  
**Descrizione**: Icona che appare nel tab del browser

## Struttura Consigliata

```
assets/images/
├── og-image.jpg            # [OBBLIGATORIO] Open Graph per social media
├── favicon.ico             # [OBBLIGATORIO] Favicon del sito
├── hero/                   # Immagini hero per homepage
│   └── hero-main.jpg
├── products/               # Immagini prodotti
│   ├── zafferano.jpg
│   ├── piante-aromatiche.jpg
│   └── conserve.jpg
├── blog/                   # Immagini articoli blog
│   └── post-*.jpg
├── team/                   # Foto membri del team
│   └── *.jpg
└── logo/                   # Logo aziendale
    └── logo.svg
```

## Linee Guida per le Immagini

### Dimensioni Consigliate

- **Open Graph Image**: 1200x630px (obbligatorio)
- **Hero Image**: 1920x1080px (o superiore)
- **Immagini Prodotti**: 800x600px
- **Immagini Blog**: 1200x630px
- **Foto Team**: 400x400px (quadrate)
- **Logo**: SVG o PNG con sfondo trasparente
- **Favicon**: 32x32px o 16x16px

### Formato

- Usa **JPEG** per foto (con compressione 80-90%)
- Usa **PNG** per immagini con trasparenza
- Usa **SVG** per loghi e icone
- Usa **ICO** per favicon

### Ottimizzazione

Prima di caricare le immagini, ottimizzale usando strumenti come:
- [TinyPNG](https://tinypng.com/)
- [ImageOptim](https://imageoptim.com/)
- [Squoosh](https://squoosh.app/)

### Nomi File

Usa nomi descrittivi in minuscolo con trattini:
- ✅ `zafferano-del-groppello.jpg`
- ❌ `IMG_1234.jpg`

## Copyright

Assicurati di avere i diritti per tutte le immagini che carichi.
