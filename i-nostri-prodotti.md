---
layout: page
title: "I Nostri Prodotti"
subtitle: "Eccellenza biologica dalla terra ligure"
permalink: /prodotti/
---

<div class="card-grid">
    {% for prodotto in site.prodotti %}
    <div class="product-card">
        {% if prodotto.image %}
        <img src="{{ prodotto.image }}" alt="{{ prodotto.title }}" class="product-image">
        {% else %}
        <img src="[insert_yours: default_product_image]" alt="{{ prodotto.title }}" class="product-image">
        {% endif %}
        <div class="product-content">
            <h3 class="product-title">{{ prodotto.title }}</h3>
            {% if prodotto.price %}
            <div class="product-price">{{ prodotto.price }}</div>
            {% endif %}
            <p class="product-description">{{ prodotto.description }}</p>
            <a href="{{ prodotto.url | relative_url }}" class="btn btn-primary">Scopri di più</a>
        </div>
    </div>
    {% endfor %}
</div>

## Perché Scegliere i Nostri Prodotti?

<div class="feature-grid mt-5">
    <div class="feature">
        <svg class="feature-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
        </svg>
        <h4 class="feature-title">Certificazione Biologica</h4>
        <p class="feature-description">Tutti i nostri prodotti sono certificati biologici e coltivati senza l'uso di pesticidi o sostanze chimiche.</p>
    </div>
    
    <div class="feature">
        <svg class="feature-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
        </svg>
        <h4 class="feature-title">Raccolta Manuale</h4>
        <p class="feature-description">Ogni prodotto è raccolto a mano al momento giusto per garantire la massima qualità e freschezza.</p>
    </div>
    
    <div class="feature">
        <svg class="feature-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/>
        </svg>
        <h4 class="feature-title">Km Zero</h4>
        <p class="feature-description">Coltiviamo e trasformiamo i nostri prodotti direttamente in azienda, riducendo l'impatto ambientale.</p>
    </div>
</div>

## Come Acquistare

Per acquistare i nostri prodotti, puoi:

- **Contattarci direttamente**: Invia una email a [{{ site.email }}](mailto:{{ site.email }}) o chiama al [{{ site.phone }}](tel:{{ site.phone }})
- **Visitare l'azienda**: [insert_yours: orari_visite_e_vendita_diretta]
- **Mercati locali**: [insert_yours: elenco_mercati_dove_trovare_prodotti]

[Contattaci per maggiori informazioni](/contatti/){: .btn .btn-primary}

