---
layout: page
title: "Blog"
subtitle: "Storie, ricette e consigli dalla nostra azienda agricola"
permalink: /blog/
---

<div class="blog-grid" style="display: grid; gap: 2rem;">
    {% for post in site.posts %}
    <article class="blog-post-preview" style="display: grid; grid-template-columns: 300px 1fr; gap: 2rem; padding: 2rem; background-color: var(--background-light); border-radius: 0.5rem;">
        {% if post.image %}
        <img src="{{ post.image }}" alt="{{ post.title }}" style="width: 100%; height: 200px; object-fit: cover; border-radius: 0.375rem;">
        {% else %}
        <div style="width: 100%; height: 200px; background: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-dark) 100%); border-radius: 0.375rem;"></div>
        {% endif %}
        
        <div>
            <div style="margin-bottom: 1rem;">
                <time style="color: var(--text-light); font-size: 0.95rem;">{{ post.date | date: "%d %B %Y" }}</time>
                {% if post.categories %}
                <span style="margin-left: 1rem;">
                    {% for category in post.categories %}
                    <span class="tag">{{ category }}</span>
                    {% endfor %}
                </span>
                {% endif %}
            </div>
            
            <h2 style="margin-bottom: 1rem;">
                <a href="{{ post.url | relative_url }}" style="color: var(--text-color);">{{ post.title }}</a>
            </h2>
            
            {% if post.excerpt %}
            <p style="color: var(--text-light); margin-bottom: 1rem;">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
            {% endif %}
            
            <a href="{{ post.url | relative_url }}" class="btn btn-secondary">Leggi di più</a>
        </div>
    </article>
    {% endfor %}
</div>

{% if site.posts.size == 0 %}
<div style="text-align: center; padding: 4rem 0;">
    <p style="font-size: 1.25rem; color: var(--text-light);">Nessun articolo pubblicato ancora. Torna presto per leggere le nostre storie!</p>
</div>
{% endif %}

## Categorie

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 3rem 0;">
    {% for category in site.categories %}
    <a href="{{ site.baseurl }}/blog/categoria/{{ category[0] | slugify }}/" class="tag" style="font-size: 1rem; padding: 0.5rem 1rem;">
        {{ category[0] }} ({{ category[1].size }})
    </a>
    {% endfor %}
</div>

## Iscriviti alla Newsletter

Ricevi aggiornamenti sui nostri prodotti, eventi e novità dall'azienda.

<form action="https://example.com/newsletter" method="POST" style="max-width: 500px; margin: 2rem auto; display: flex; gap: 1rem;">
    <input type="email" name="email" placeholder="Il tuo indirizzo email" required style="flex: 1; padding: 0.875rem; border: 1px solid var(--border-color); border-radius: 0.375rem; font-size: 1rem;">
    <button type="submit" class="btn btn-primary">Iscriviti</button>
</form>
