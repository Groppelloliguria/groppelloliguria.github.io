# 📋 Lista Contenuti da Completare

Questo documento elenca tutti i contenuti che devono essere forniti dal proprietario per completare il sito web.

## 🖼️ Immagini Necessarie

### Obbligatorie
- [ ] **Open Graph Image** (`assets/images/og-image.jpg`) - 1200x630px
  - Immagine che appare quando il sito viene condiviso sui social media
- [ ] **Favicon** (`assets/images/favicon.ico`) - 32x32px
  - Icona che appare nel tab del browser
- [ ] **Hero Image Homepage** - 1920x1080px
  - Immagine di sfondo per la sezione hero della homepage

### Prodotti
- [ ] **Zafferano** (`assets/images/products/zafferano.jpg`) - 800x600px
- [ ] **Piante Aromatiche** (`assets/images/products/piante-aromatiche.jpg`) - 800x600px
- [ ] **Prodotti Trasformati** (`assets/images/products/conserve.jpg`) - 800x600px

### Opzionali
- [ ] **Logo aziendale** (SVG o PNG con trasparenza)
- [ ] **Foto team** (400x400px quadrate)
- [ ] **Immagini blog posts**

## 📝 Informazioni Azienda

### Dati di Contatto (_config.yml)
- [ ] **Indirizzo completo**: Via [...]
- [ ] **Google Analytics ID**: GA_MEASUREMENT_ID

### Storia e Chi Siamo (about.markdown)
- [ ] Storia dettagliata della famiglia e dell'azienda
- [ ] Presentazione membri del team
- [ ] Località precisa dell'azienda
- [ ] Indicazioni stradali dettagliate
- [ ] Descrizione location e territorio
- [ ] Ente certificatore biologico
- [ ] Altre certificazioni

### Prodotti (_prodotti/zafferano.md)
- [ ] Descrizione dettagliata processo coltivazione zafferano
- [ ] Periodo piantagione (es: "settembre-ottobre")
- [ ] Periodo fioritura (es: "ottobre-novembre")
- [ ] Temperatura essiccazione (es: "35-40°C")
- [ ] Durata conservazione (es: "2-3 anni")
- [ ] Prezzi altri prodotti
- [ ] Descrizioni altri prodotti

### Contatti (contatti.md)
- [ ] **Orari di apertura** dettagliati
- [ ] **Elenco mercati** dove sono venduti i prodotti
- [ ] **Google Maps embed URL** per la mappa
- [ ] **Formspree ID** per il form di contatto (es: `f/YOUR_FORM_ID`)

### Blog (_posts/)
- [ ] Nome autore post blog
- [ ] Path immagini blog posts

### Privacy (privacy.md)
- [ ] Ragione sociale completa
- [ ] Indirizzo sede legale completo

## 🔧 Servizi da Configurare

### Form di Contatto
1. Vai su [Formspree.io](https://formspree.io/)
2. Crea un account gratuito
3. Crea un nuovo form
4. Copia il form ID
5. Sostituisci `[insert_yours: formspree_id]` in `contatti.md`

### Newsletter (opzionale)
1. Scegli un servizio (es: Mailchimp, Sendinblue)
2. Configura il form
3. Sostituisci `[insert_yours: newsletter_service_url]` in `blog.md`

### Google Analytics (opzionale)
1. Vai su [Google Analytics](https://analytics.google.com/)
2. Crea una proprietà per il sito
3. Copia il Measurement ID
4. Sostituisci in `_config.yml`

### Google Maps
1. Vai su [Google Maps](https://www.google.com/maps)
2. Cerca la tua località
3. Clicca su "Condividi" → "Incorpora una mappa"
4. Copia il codice iframe
5. Estrai solo l'URL src
6. Sostituisci in `contatti.md`

## 🔍 Come Trovare i Placeholder

Cerca nel codice la stringa `[insert_yours:` per trovare tutti i punti da completare.

Comando da terminale:
```bash
grep -r "\[insert_yours" . --exclude-dir=.git --exclude-dir=_site
```

## 📄 File da Modificare

1. **_config.yml** - Configurazione generale
2. **index.md** - Homepage
3. **about.markdown** - Chi Siamo
4. **i-nostri-prodotti.md** - Lista prodotti
5. **_prodotti/zafferano.md** - Dettaglio prodotto zafferano
6. **contatti.md** - Pagina contatti
7. **blog.md** - Blog
8. **privacy.md** - Privacy policy
9. **_posts/2025-09-02-benvenuti.markdown** - Post blog

## ✅ Checklist Finale Prima del Lancio

- [ ] Tutte le immagini caricate e ottimizzate
- [ ] Tutti i placeholder `[insert_yours]` sostituiti
- [ ] Form di contatto testato
- [ ] Link social media verificati
- [ ] Google Analytics configurato (se desiderato)
- [ ] Privacy policy completata con dati legali
- [ ] Sito testato su mobile e desktop
- [ ] Contenuti rivisti per errori grammaticali

## 🆘 Supporto

Per domande o assistenza, fare riferimento al README.md principale o contattare lo sviluppatore.
