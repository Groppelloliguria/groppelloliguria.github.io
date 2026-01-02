---
layout: page
title: "Contatti"
subtitle: "Mettiti in contatto con noi"
permalink: /contatti/
---

## Informazioni di Contatto

<div class="contact-info-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; margin: 3rem 0;">
    <div class="contact-card" style="padding: 2rem; background-color: var(--background-light); border-radius: 0.5rem;">
        <svg class="icon" style="width: 40px; height: 40px; color: var(--primary-color); margin-bottom: 1rem;" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
        </svg>
        <h3>Email</h3>
        <p><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
    </div>
    
    <div class="contact-card" style="padding: 2rem; background-color: var(--background-light); border-radius: 0.5rem;">
        <svg class="icon" style="width: 40px; height: 40px; color: var(--primary-color); margin-bottom: 1rem;" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
        </svg>
        <h3>Telefono</h3>
        <p><a href="tel:{{ site.phone }}">{{ site.phone }}</a></p>
    </div>
    
    <div class="contact-card" style="padding: 2rem; background-color: var(--background-light); border-radius: 0.5rem;">
        <svg class="icon" style="width: 40px; height: 40px; color: var(--primary-color); margin-bottom: 1rem;" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
            <path d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
        </svg>
        <h3>Indirizzo</h3>
        <p>{{ site.address }}</p>
    </div>
</div>

## Orari di Apertura

[insert_yours: orari_apertura_dettagliati]

**Importante:** Per le visite in azienda è consigliata la prenotazione.

## Scrivici

Hai domande sui nostri prodotti o vuoi organizzare una visita? Compila il modulo qui sotto e ti risponderemo al più presto.

<form action="https://formspree.io/f/[insert_yours: formspree_id]" method="POST" class="contact-form" style="max-width: 600px; margin: 2rem auto;">
    <div style="margin-bottom: 1.5rem;">
        <label for="name" style="display: block; margin-bottom: 0.5rem; font-weight: 500;">Nome *</label>
        <input type="text" id="name" name="name" required style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem;">
    </div>
    
    <div style="margin-bottom: 1.5rem;">
        <label for="email" style="display: block; margin-bottom: 0.5rem; font-weight: 500;">Email *</label>
        <input type="email" id="email" name="email" required style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem;">
    </div>
    
    <div style="margin-bottom: 1.5rem;">
        <label for="phone" style="display: block; margin-bottom: 0.5rem; font-weight: 500;">Telefono</label>
        <input type="tel" id="phone" name="phone" style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem;">
    </div>
    
    <div style="margin-bottom: 1.5rem;">
        <label for="subject" style="display: block; margin-bottom: 0.5rem; font-weight: 500;">Oggetto *</label>
        <input type="text" id="subject" name="subject" required style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem;">
    </div>
    
    <div style="margin-bottom: 1.5rem;">
        <label for="message" style="display: block; margin-bottom: 0.5rem; font-weight: 500;">Messaggio *</label>
        <textarea id="message" name="message" rows="6" required style="width: 100%; padding: 0.75rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem; resize: vertical;"></textarea>
    </div>
    
    <div style="margin-bottom: 1.5rem;">
        <label style="display: flex; align-items: center; gap: 0.5rem;">
            <input type="checkbox" name="privacy" required>
            <span>Acconsento al trattamento dei miei dati personali secondo la <a href="/privacy/">Privacy Policy</a> *</span>
        </label>
    </div>
    
    <button type="submit" class="btn btn-primary" style="width: 100%;">Invia Messaggio</button>
</form>

## Come Raggiungerci

[insert_yours: indicazioni_stradali_dettagliate]

<div style="margin: 3rem 0;">
    <iframe src="[insert_yours: google_maps_embed_url]" width="100%" height="450" style="border:0; border-radius: 0.5rem;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

## Social Media

Seguici sui social per rimanere aggiornato sulle novità, gli eventi e la vita quotidiana in azienda:

<div class="social-links-large" style="display: flex; gap: 1rem; justify-content: center; margin: 2rem 0;">
    {% if site.social_media.facebook %}
    <a href="https://facebook.com/{{ site.social_media.facebook }}" target="_blank" rel="noopener" class="btn btn-secondary">
        Facebook
    </a>
    {% endif %}
    {% if site.social_media.instagram %}
    <a href="https://instagram.com/{{ site.social_media.instagram }}" target="_blank" rel="noopener" class="btn btn-secondary">
        Instagram
    </a>
    {% endif %}
</div>
