# Groppello Liguria Website

Sito web ufficiale di Groppello Liguria - Agricoltura Rigenerativa di Eccellenza

## 🚀 Deployed Site
Visit at: [groppelloliguria.github.io](https://groppelloliguria.github.io)

## 🎨 Design
Il sito è stato progettato con uno stile moderno e pulito, ispirato a siti professionali come developmentseed.org, con:
- Layout responsive e mobile-friendly
- Navigazione moderna e intuitiva
- Hero section con immagini impattanti
- Design a card per prodotti e contenuti
- Tipografia pulita e leggibile
- Animazioni e transizioni fluide

## 📝 Completamento Contenuti

### Sezioni da Completare
Cerca nel codice `[insert_yours: ...]` per trovare tutte le sezioni che richiedono i tuoi contenuti specifici:

#### Immagini
- Hero image della homepage
- Immagini prodotti (zafferano, piante aromatiche, prodotti trasformati)
- Immagini blog post
- Logo (opzionale)

#### Informazioni Azienda
- Storia dettagliata della famiglia
- Presentazione membri del team
- Località precisa dell'azienda
- Indicazioni stradali
- Descrizione location dettagliata

#### Dati Prodotti
- Prezzi dei vari prodotti
- Dettagli coltivazione zafferano
- Periodo piantagione e fioritura
- Temperatura essiccazione
- Durata conservazione
- Ente certificatore biologico

#### Servizi e Funzionalità
- Orari di apertura
- Elenco mercati dove trovare i prodotti
- Google Maps embed URL
- Formspree ID per form contatti
- Newsletter service URL
- Google Analytics ID

#### Social Media
- Verifica username Facebook e Instagram

## 🛠️ Sviluppo Locale

### Prerequisiti
- Ruby >= 2.7
- Bundler

### Installazione
```bash
gem install bundler
bundle install
```

### Avvio Server Locale
```bash
bundle exec jekyll serve
```
Il sito sarà disponibile su http://localhost:4000

## 📁 Struttura File

```
.
├── _layouts/          # Layout HTML per diverse tipologie di pagine
│   ├── default.html   # Layout base
│   ├── home.html      # Layout homepage con hero
│   ├── page.html      # Layout pagine standard
│   └── post.html      # Layout articoli blog
├── _includes/         # Componenti riutilizzabili
│   ├── header.html    # Header e navigazione
│   └── footer.html    # Footer
├── _posts/            # Articoli del blog
├── _prodotti/         # Collezione prodotti
├── assets/
│   ├── css/
│   │   └── main.css   # Stili CSS principali
│   ├── js/
│   │   └── main.js    # JavaScript per interattività
│   └── images/        # Immagini del sito
├── index.md           # Homepage
├── chi-siamo/         # Pagina chi siamo
├── prodotti/          # Pagina prodotti
├── blog.md            # Lista blog
├── contatti.md        # Pagina contatti
└── _config.yml        # Configurazione Jekyll
```

## 🎯 Funzionalità Implementate

- ✅ Design responsive mobile-first
- ✅ Menu di navigazione con hamburger menu su mobile
- ✅ Hero section con immagini di sfondo
- ✅ Sezioni features con icone SVG
- ✅ Card layout per prodotti
- ✅ Sistema blog con post in italiano
- ✅ Form di contatto (richiede configurazione Formspree)
- ✅ Footer completo con informazioni e social media
- ✅ Smooth scrolling
- ✅ Animazioni e transizioni
- ✅ SEO ottimizzato
- ✅ Tutto in italiano

## 📱 Pagine Principali

- **Home**: Hero section + features + prodotti in evidenza + storia
- **Chi Siamo**: Storia aziendale, valori, team, certificazioni
- **Prodotti**: Griglia di tutti i prodotti con filtri
- **Blog**: Elenco articoli con preview
- **Contatti**: Form contatti + mappa + info

## 🔧 Personalizzazione

### Colori
Modifica le variabili CSS in `assets/css/main.css`:
```css
:root {
    --primary-color: #2c5f2d;
    --accent-color: #97be5a;
    /* ... */
}
```

### Contenuti
Modifica i file Markdown nelle rispettive cartelle per aggiornare i contenuti.

## 📦 Deploy

Il sito viene automaticamente deployato su GitHub Pages quando si effettua push sul branch main.

## 📞 Supporto

Per domande o supporto, contatta: info@groppelloliguria.it

---

Made with ❤️ for Groppello Liguria

