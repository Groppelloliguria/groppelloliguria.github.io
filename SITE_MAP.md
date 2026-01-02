# 🗺️ Mappa del Sito

## Struttura delle Pagine

```
Groppello Liguria
│
├── 🏠 Home (/)
│   ├── Hero section
│   ├── Filosofia (features)
│   ├── Prodotti in evidenza
│   └── La nostra storia
│
├── 👥 Chi Siamo (/chi-siamo/)
│   ├── La nostra storia
│   ├── I nostri valori
│   ├── Il nostro team
│   ├── La nostra posizione
│   └── Certificazioni
│
├── 🌾 Prodotti (/prodotti/)
│   ├── Griglia prodotti
│   ├── Perché scegliere i nostri prodotti
│   ├── Come acquistare
│   └── Dettagli prodotti individuali:
│       └── Zafferano del Groppello (/prodotti/zafferano/)
│
├── 📝 Blog (/blog/)
│   ├── Lista articoli
│   ├── Categorie
│   ├── Newsletter signup
│   └── Articoli individuali:
│       └── Benvenuti nel Blog (/novità/agricoltura/2025/09/02/benvenuti/)
│
├── 📧 Contatti (/contatti/)
│   ├── Informazioni di contatto
│   ├── Form di contatto
│   ├── Mappa
│   └── Social media
│
├── 🔒 Privacy Policy (/privacy/)
│   └── Informativa GDPR
│
└── ❌ 404 (/404.html)
    └── Pagina errore
```

## Layout Utilizzati

### default.html
- Layout base per tutte le pagine
- Include header e footer
- Gestisce meta tags e SEO

### home.html
- Estende default.html
- Aggiunge hero section con immagine di sfondo
- Supporta CTA buttons

### page.html
- Estende default.html
- Header della pagina con titolo e subtitle
- Usato per pagine statiche (Chi Siamo, Contatti, etc.)

### post.html
- Estende default.html
- Header con metadata (data, autore, categorie)
- Footer con tags
- Usato per articoli del blog

## Componenti Riutilizzabili

### header.html
- Logo/nome sito
- Navigazione principale
- Menu hamburger mobile

### footer.html
- Informazioni azienda
- Link rapidi
- Contatti
- Social media
- Copyright

## Assets

### CSS
- `assets/css/main.css` - Tutti gli stili del sito
  - Variabili CSS
  - Typography
  - Layout components
  - Responsive design
  - Utility classes

### JavaScript
- `assets/js/main.js` - Funzionalità interattive
  - Mobile menu toggle
  - Smooth scroll
  - Form validation
  - Lazy loading images
  - Scroll animations

### Immagini
- `assets/images/` - Tutte le immagini del sito
  - og-image.jpg (Open Graph)
  - favicon.ico
  - products/
  - blog/
  - team/
  - logo/

## Navigazione Principale

1. **Home** - Homepage con hero e panoramica
2. **Chi Siamo** - Storia e valori dell'azienda
3. **Prodotti** - Catalogo prodotti
4. **Blog** - Articoli e news
5. **Contatti** - Form e informazioni di contatto

## Funzionalità Implementate

✅ Design responsive mobile-first
✅ Menu navigazione con hamburger su mobile
✅ Hero section dinamico
✅ Card layout per prodotti e blog
✅ Form di contatto con validazione
✅ SEO ottimizzato con meta tags
✅ Open Graph per social media
✅ Smooth scrolling
✅ Animazioni al scroll
✅ Footer completo
✅ Privacy policy GDPR compliant
✅ Pagina 404 personalizzata
✅ Sistema blog con Jekyll
✅ Collezione prodotti personalizzata

## URL Structure

- Homepage: `/`
- Pagine statiche: `/nome-pagina/`
- Prodotti: `/prodotti/nome-prodotto/`
- Blog posts: `/categoria/anno/mese/giorno/titolo/`

## Tecnologie

- **Jekyll** - Generatore di siti statici
- **Liquid** - Template engine
- **Markdown** - Formato contenuti
- **HTML5/CSS3** - Markup e stili
- **JavaScript** - Interattività
- **GitHub Pages** - Hosting
