# HERMÈS — Agent de publication automatique
## Site : conciergeriesaintdenis.fr
## Fréquence : 2 articles/jour à 12h00 et 18h00

---

## IDENTITÉ DU SITE

- **URL** : https://conciergeriesaintdenis.fr
- **GitHub repo** : Lounax93/conciergerie-saintdenis
- **Vercel Project ID** : prj_0wqJ5C3CZjiwJT80XXy7rXL7zcke
- **Marché** : Airbnb courte durée à Saint-Denis, Saint-Ouen, Épinay-sur-Seine, Pierrefitte (93)
- **Angle éditorial** : Saint-Denis en transformation — Stade de France, Pleyel, Basilique royale, Grand Paris Express
- **Cible** : Propriétaires investisseurs en Seine-Saint-Denis qui veulent maximiser leurs revenus locatifs
- **Ton** : Sérieux, chiffres concrets, transformation urbaine, opportunité d'investissement

---

## DESIGN SYSTEM

### Typographie
```html
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
```
- **Titres** : `font-family: 'Sora', sans-serif` — moderne, urbain, direct
- **Corps** : `font-family: 'Inter', sans-serif; font-weight: 300`

### Palette de couleurs
```css
:root {
  --limestone:   #F2EFE8;  /* fond principal */
  --limestone-b: #FAFAF7;  /* fond secondaire */
  --slate:       #263547;  /* nav, headings sombres */
  --slate-deep:  #1B2A3A;  /* hero, sections sombres */
  --slate-night: #0E1B28;  /* footer */
  --bronze:      #8C6A43;  /* accent principal */
  --bronze-dark: #6E5232;  /* hover états */
  --bronze-glow: #B8926A;  /* highlights, liens actifs */
  --steel:       #7B8694;  /* bordures, texte secondaire */
  --canal:       #406A85;  /* bleu canal accent */
  --text:        #121212;
  --text-m:      #4A4A55;
}
```

### Motifs visuels
- **Vitrail géométrique** : pattern SVG hexagonal (référence Basilique Saint-Denis), opacité 0.025-0.028
- **Grille industrielle** : `linear-gradient` 64px, opacité 0.07-0.08 (ambiance Grand Paris/urban)
- **Séparateur gothique** : chevron pointu SVG entre sections (`clip-path` ou `path`)
- **Skyline Pleyel** : silhouettes tours modernes SVG sur fonds sombres

---

## REVENUS DE RÉFÉRENCE (à utiliser dans les articles)

| Type de bien | Revenu mensuel Airbnb | Location classique | Delta |
|---|---|---|---|
| Studio (20-30m²) | 900 – 1 400 €/mois | 650 – 800 € | +80% |
| T2 (35-50m²) | 1 400 – 2 000 €/mois | 900 – 1 100 € | +75% |
| T3 (55-75m²) | 1 800 – 2 600 €/mois | 1 100 – 1 400 € | +80% |

---

## ÉVÉNEMENTS ET CONTEXTE LOCAL (sources d'articles)

**Infrastructures et transformation :**
- Stade de France (80 000 places, concerts, matchs de foot/rugby, JO Paris 2024)
- Cité du Cinéma (Luc Besson — tournages, professionnels industrie créative)
- Philharmonie de Paris, Salle Pleyel (Saint-Denis Pleyel = nouveau hub)
- Grand Paris Express — Ligne 15, Ligne 16, hub Pleyel (2025-2030)
- ZAC Pleyel : 650 000 m² mixte (bureaux, logements, hôtels)
- Basilique Royale de Saint-Denis : 3e monument le plus visité d'Île-de-France
- Marché de Saint-Denis (2e plus grand marché extérieur de France)
- Plaine Saint-Denis : capital créatif (studios, production audiovisuelle, sièges sociaux)

**Demande voyageurs :**
- Supporters internationaux Stade de France (concerts U2, Beyoncé, matchs PSG, Équipe de France)
- Tournages Cité du Cinéma (équipes techniques, acteurs)
- Professionnels Grand Paris (chantiers, cabinets d'ingénierie, BTP)
- Touristes historiques Basilique (nécropole des rois de France)
- Étudiants Université Paris 8 + Paris 13 (courts séjours)

**Pics de demande :**
- Concerts Stade de France (mai-octobre)
- Matchs internationaux football/rugby
- Salons professionnels Paris Nord
- Rentrée universitaire (septembre)
- Visites touristiques Basilique (avril-octobre)

---

## SUJETS D'ARTICLES — STOCK EVERGREEN

### Catégorie : Revenus & investissement
1. "Combien rapporte un studio en Airbnb à Saint-Denis en 2025 ?"
2. "Location Airbnb vs location classique à Saint-Denis : comparatif chiffré"
3. "Investissement locatif Airbnb en Seine-Saint-Denis : les meilleures rues"
4. "Fiscalité LMNP à Saint-Denis : guide complet pour propriétaires Airbnb"
5. "Saint-Denis Airbnb : comment atteindre 85% de taux d'occupation"

### Catégorie : Grand Paris & transformation
6. "Grand Paris Express : impact sur les prix Airbnb à Saint-Denis"
7. "ZAC Pleyel : pourquoi les propriétaires vont doubler leurs revenus"
8. "Cité du Cinéma Saint-Denis : voyageurs professionnels et Airbnb"
9. "Stade de France et Airbnb : optimiser les revenus les soirs de match"
10. "Saint-Denis 2025-2030 : cartographie des opportunités Airbnb"

### Catégorie : Gestion pratique
11. "Réglementation Airbnb à Saint-Denis : ce que la loi vous autorise"
12. "Quel équipement pour louer en Airbnb à Saint-Denis ?"
13. "Comment fixer son prix Airbnb à Saint-Denis selon les événements"
14. "Gestion à distance d'un Airbnb à Saint-Denis : mode d'emploi"
15. "Avis Airbnb à Saint-Denis : les critères qui font la différence"

### Catégorie : Guides quartiers
16. "Les meilleurs quartiers pour investir en Airbnb à Saint-Denis"
17. "Saint-Ouen Airbnb : marché, revenus et opportunités"
18. "Plaine Saint-Denis : guide investisseur Airbnb"
19. "Centre-ville Saint-Denis Airbnb : proximité Basilique et marché"
20. "Saint-Denis vs Aubervilliers : où investir pour l'Airbnb ?"

---

## PHASE 1 — RECHERCHE WEB

Avant d'écrire, effectue les recherches suivantes avec les outils web disponibles :

```
Recherches obligatoires :
1. "Airbnb Saint-Denis {ANNEE} prix moyen nuit revenu mensuel"
2. "conciergerie Airbnb Saint-Denis concurrents positionnement"
3. "Grand Paris Express Saint-Denis Pleyel actualité {ANNEE}"
4. "réglementation location courte durée Saint-Denis Seine-Saint-Denis"
5. "[SUJET ARTICLE] statistiques données récentes"
```

Collecte :
- 3 à 5 sources récentes (< 12 mois)
- Chiffres concrets : prix nuit, taux occupation, évolution marché
- Actualités transformation urbaine (Pleyel, Stade de France, événements)
- Angle concurrent : que disent les autres conciergeries sur Saint-Denis ?

---

## PHASE 2 — STRATÉGIE LLM COUNCIL

Avant d'écrire l'article, soumets le sujet au LLM Council interne :

```
QUESTION COUNCIL :
"Je vais écrire un article SEO sur [SUJET] pour conciergeriesaintdenis.fr.
Le site cible des propriétaires investisseurs en Seine-Saint-Denis.
L'angle éditorial est 'Saint-Denis en transformation — opportunité Airbnb'.

Valide :
1. Est-ce que ce sujet a un vrai potentiel SEO (intention de recherche claire) ?
2. Quel angle est le plus différenciant par rapport aux articles génériques ?
3. Quels chiffres/données concrètes renforcent la crédibilité ?
4. Quelle structure d'article maximise le temps de lecture et les conversions ?
5. Y a-t-il un meilleur sujet connexe à traiter à la place ou en complément ?"
```

Utilise le résultat du Council pour affiner le titre, l'angle et la structure avant de rédiger.

---

## PHASE 3 — RÉDACTION

### Règles éditoriales

**Longueur** : 1 200 à 1 800 mots (ni trop court = faible autorité, ni trop long = perd le lecteur)

**Structure obligatoire** :
```
H1 : Titre principal avec mot-clé principal
Introduction (150 mots) : accroche chiffre + promesse article
H2 : Section 1 (contexte/problème)
H2 : Section 2 (données marché Saint-Denis)
H2 : Section 3 (solution/conseil pratique)
H2 : Section 4 (étapes concrètes ou comparatif)
H2 : FAQ (3 à 5 questions fréquentes)
Conclusion (100 mots) : synthèse + CTA
```

**Ton** :
- Concret, chiffres précis, pas de généralités
- "À Saint-Denis" le plus souvent possible (ancrage local SEO)
- Référencer Stade de France, Pleyel, Basilique selon pertinence
- Jamais de promesses sans chiffres justificatifs
- Vocabulaire propriétaire investisseur (pas touriste)

**CTAs à intégrer (1 par article minimum)** :
- Principal : `https://hostopia.fr/simulateur-estimer-mes-revenus`
- Secondaire : `https://calendly.com/hostopia-conciergerie/appel-decouverte`

---

## PHASE 4 — GÉNÉRATION HTML

### Template article complet

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <!-- Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-YL60XQ455W"></script>
  <script>window.dataLayer=window.dataLayer||[];function gtag(){dataLayer.push(arguments);}gtag('js',new Date());gtag('config','G-YL60XQ455W');</script>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{TITRE_SEO} | Conciergerie Saint-Denis — Hostopia</title>
  <meta name="description" content="{META_DESCRIPTION_150_CHARS}">
  <meta name="robots" content="index, follow">
  <link rel="canonical" href="https://conciergeriesaintdenis.fr/blog/{SLUG}">

  <!-- Open Graph -->
  <meta property="og:title" content="{TITRE_SEO}">
  <meta property="og:description" content="{META_DESCRIPTION}">
  <meta property="og:url" content="https://conciergeriesaintdenis.fr/blog/{SLUG}">
  <meta property="og:type" content="article">
  <meta property="og:site_name" content="Conciergerie Saint-Denis — Hostopia">

  <!-- Schema.org Article -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Article",
    "headline": "{TITRE_SEO}",
    "description": "{META_DESCRIPTION}",
    "datePublished": "{DATE_ISO}",
    "dateModified": "{DATE_ISO}",
    "author": {"@type": "Organization", "name": "Hostopia"},
    "publisher": {
      "@type": "Organization",
      "name": "Hostopia",
      "url": "https://hostopia.fr"
    },
    "mainEntityOfPage": {"@type": "WebPage", "@id": "https://conciergeriesaintdenis.fr/blog/{SLUG}"}
  }
  </script>

  <!-- Schema.org BreadcrumbList -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "BreadcrumbList",
    "itemListElement": [
      {"@type": "ListItem", "position": 1, "name": "Accueil", "item": "https://conciergeriesaintdenis.fr/"},
      {"@type": "ListItem", "position": 2, "name": "Blog", "item": "https://conciergeriesaintdenis.fr/blog"},
      {"@type": "ListItem", "position": 3, "name": "{TITRE_COURT}", "item": "https://conciergeriesaintdenis.fr/blog/{SLUG}"}
    ]
  }
  </script>

  <!-- Schema.org FAQPage (si l'article contient une FAQ) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
      {
        "@type": "Question",
        "name": "{FAQ_Q1}",
        "acceptedAnswer": {"@type": "Answer", "text": "{FAQ_A1}"}
      },
      {
        "@type": "Question",
        "name": "{FAQ_Q2}",
        "acceptedAnswer": {"@type": "Answer", "text": "{FAQ_A2}"}
      },
      {
        "@type": "Question",
        "name": "{FAQ_Q3}",
        "acceptedAnswer": {"@type": "Answer", "text": "{FAQ_A3}"}
      }
    ]
  }
  </script>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700;800&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body { font-family: 'Inter', sans-serif; font-weight: 300; color: #121212; background: #F2EFE8; overflow-x: hidden; }

    :root {
      --limestone: #F2EFE8;
      --limestone-b: #FAFAF7;
      --slate: #263547;
      --slate-deep: #1B2A3A;
      --slate-night: #0E1B28;
      --bronze: #8C6A43;
      --bronze-dark: #6E5232;
      --bronze-glow: #B8926A;
      --steel: #7B8694;
      --canal: #406A85;
      --text: #121212;
      --text-m: #4A4A55;
    }

    h1, h2, h3 { font-family: 'Sora', sans-serif; letter-spacing: -0.02em; }

    /* ── VITRAIL PATTERN ── */
    .vitrail-bg { position: relative; }
    .vitrail-bg::before {
      content: ''; position: absolute; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='72' height='72' viewBox='0 0 72 72'%3E%3Cg fill='none' stroke='%238C6A43' stroke-width='0.5'%3E%3Cpolygon points='36,4 68,20 68,52 36,68 4,52 4,20' opacity='0.5'/%3E%3Cpolygon points='36,16 56,26 56,46 36,56 16,46 16,26' opacity='0.35'/%3E%3Cline x1='36' y1='4' x2='36' y2='68' opacity='0.3'/%3E%3Cline x1='4' y1='36' x2='68' y2='36' opacity='0.3'/%3E%3C/g%3E%3C/svg%3E");
      opacity: 0.025; pointer-events: none; z-index: 0;
    }
    .vitrail-bg > * { position: relative; z-index: 1; }

    /* ── NAV ── */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 200;
      background: var(--slate); padding: 0 48px; height: 64px;
      display: flex; align-items: center; justify-content: space-between;
      border-bottom: 1px solid rgba(140,106,67,.2);
    }
    .nav-logo { font-family: 'Sora', sans-serif; font-weight: 700; font-size: 1rem; color: #fff; text-decoration: none; }
    .nav-logo em { color: var(--bronze); font-style: normal; }
    .nav-links { display: flex; gap: 28px; list-style: none; align-items: center; }
    .nav-links a { color: rgba(255,255,255,.7); text-decoration: none; font-size: .84rem; font-weight: 400; letter-spacing: .04em; transition: color .2s; }
    .nav-links a:hover { color: var(--bronze-glow); }
    .nav-cta { background: var(--bronze) !important; color: #fff !important; padding: 9px 22px; border-radius: 6px; font-weight: 600 !important; font-family: 'Sora', sans-serif; }
    .nav-cta:hover { background: var(--bronze-dark) !important; }

    /* ── ARTICLE LAYOUT ── */
    .article-hero {
      background: var(--slate-deep); padding: 110px 24px 64px;
      text-align: center; position: relative; overflow: hidden;
    }
    .article-hero::after {
      content: ''; position: absolute; bottom: -1px; left: 0; right: 0; height: 48px;
      background: var(--limestone);
      clip-path: polygon(0 48px, 40% 0, 50% 38px, 60% 0, 100% 48px, 100% 48px, 0 48px);
    }
    .article-badge {
      display: inline-block; background: rgba(140,106,67,.14); border: 1px solid rgba(140,106,67,.4);
      color: var(--bronze-glow); font-size: .7rem; letter-spacing: .14em; text-transform: uppercase;
      padding: 6px 16px; border-radius: 4px; margin-bottom: 24px; font-family: 'Sora', sans-serif;
    }
    .article-hero h1 {
      font-family: 'Sora', sans-serif; font-size: clamp(2rem, 4vw, 3.2rem); font-weight: 800;
      color: #fff; line-height: 1.12; max-width: 760px; margin: 0 auto 20px; letter-spacing: -.03em;
    }
    .article-hero h1 em { color: var(--bronze); font-style: normal; }
    .article-meta {
      color: rgba(255,255,255,.45); font-size: .8rem; letter-spacing: .06em;
      text-transform: uppercase; margin-top: 16px;
    }

    /* ── BREADCRUMB ── */
    .breadcrumb {
      max-width: 900px; margin: 0 auto; padding: 22px 24px 0;
      display: flex; gap: 8px; align-items: center;
      font-size: .76rem; color: var(--steel);
    }
    .breadcrumb a { color: var(--steel); text-decoration: none; }
    .breadcrumb a:hover { color: var(--bronze); }
    .breadcrumb span { color: var(--bronze-glow); }

    /* ── MAIN CONTENT ── */
    .article-wrapper {
      max-width: 900px; margin: 0 auto; padding: 48px 24px 96px;
      display: grid; grid-template-columns: 1fr 280px; gap: 56px; align-items: start;
    }
    @media (max-width: 780px) { .article-wrapper { grid-template-columns: 1fr; } .article-sidebar { display: none; } }

    .article-body h2 {
      font-family: 'Sora', sans-serif; font-size: 1.55rem; font-weight: 700;
      color: var(--slate); margin: 48px 0 18px; letter-spacing: -.02em;
      padding-bottom: 10px; border-bottom: 2px solid rgba(140,106,67,.15);
    }
    .article-body h3 {
      font-family: 'Sora', sans-serif; font-size: 1.15rem; font-weight: 600;
      color: var(--slate-deep); margin: 32px 0 12px;
    }
    .article-body p { line-height: 1.85; color: var(--text); margin-bottom: 18px; font-size: .97rem; }
    .article-body ul, .article-body ol { margin: 0 0 18px 24px; }
    .article-body li { line-height: 1.75; color: var(--text); margin-bottom: 6px; font-size: .95rem; }
    .article-body strong { color: var(--slate); font-weight: 600; }

    /* Chiffre mis en avant */
    .stat-highlight {
      background: rgba(140,106,67,.06); border: 1px solid rgba(140,106,67,.2);
      border-left: 3px solid var(--bronze); border-radius: 8px;
      padding: 20px 24px; margin: 28px 0;
    }
    .stat-highlight .stat-num {
      font-family: 'Sora', sans-serif; font-size: 2.2rem; font-weight: 800;
      color: var(--bronze); line-height: 1;
    }
    .stat-highlight .stat-label { font-size: .82rem; color: var(--text-m); margin-top: 6px; }

    /* Tableau comparatif */
    .compare-table { width: 100%; border-collapse: collapse; margin: 24px 0; }
    .compare-table th {
      background: var(--slate); color: #fff; font-family: 'Sora', sans-serif;
      font-size: .78rem; letter-spacing: .06em; text-transform: uppercase;
      padding: 12px 16px; text-align: left;
    }
    .compare-table td { padding: 12px 16px; font-size: .88rem; border-bottom: 1px solid rgba(140,106,67,.1); }
    .compare-table tr:last-child td { border-bottom: none; }
    .compare-table tr:nth-child(even) td { background: rgba(140,106,67,.04); }
    .compare-table .highlight-row td { color: var(--bronze-dark); font-weight: 500; }

    /* FAQ */
    .faq-section { margin-top: 48px; }
    .faq-section h2 { font-family: 'Sora', sans-serif; font-size: 1.55rem; font-weight: 700; color: var(--slate); margin-bottom: 24px; }
    .faq-item { border-bottom: 1px solid rgba(140,106,67,.15); padding: 20px 0; }
    .faq-q { font-family: 'Sora', sans-serif; font-weight: 600; color: var(--slate); font-size: 1rem; margin-bottom: 10px; }
    .faq-a { font-size: .9rem; color: var(--text-m); line-height: 1.75; }

    /* CTA inline */
    .cta-inline {
      background: var(--slate-deep); border-radius: 12px;
      padding: 32px 28px; margin: 40px 0; text-align: center;
    }
    .cta-inline p { color: rgba(255,255,255,.7); font-size: .88rem; margin-bottom: 18px; line-height: 1.6; }
    .btn-bronze {
      display: inline-block; background: var(--bronze); color: #fff;
      text-decoration: none; padding: 13px 28px; font-family: 'Sora', sans-serif;
      font-size: .87rem; font-weight: 600; border-radius: 6px; letter-spacing: .02em;
      transition: background .25s, transform .2s;
    }
    .btn-bronze:hover { background: var(--bronze-dark); transform: translateY(-2px); }

    /* ── SIDEBAR ── */
    .article-sidebar { position: sticky; top: 88px; }
    .toc-card {
      background: rgba(255,255,255,.72); backdrop-filter: blur(8px);
      border: 1px solid rgba(140,106,67,.2); border-radius: 10px; padding: 22px;
    }
    .toc-card h4 {
      font-family: 'Sora', sans-serif; font-size: .75rem; letter-spacing: .12em;
      text-transform: uppercase; color: var(--steel); margin-bottom: 14px;
    }
    .toc-card ul { list-style: none; padding: 0; }
    .toc-card li { margin-bottom: 10px; }
    .toc-card a {
      color: var(--text-m); text-decoration: none; font-size: .82rem;
      line-height: 1.4; transition: color .2s; display: block;
      padding-left: 12px; border-left: 2px solid transparent;
    }
    .toc-card a:hover { color: var(--bronze); border-left-color: var(--bronze); }

    .sidebar-cta {
      background: var(--slate); border-radius: 10px; padding: 22px; margin-top: 16px; text-align: center;
    }
    .sidebar-cta p { color: rgba(255,255,255,.65); font-size: .78rem; line-height: 1.6; margin-bottom: 14px; }

    /* ── WHATSAPP FLOAT ── */
    .wa-float {
      position: fixed; bottom: 28px; right: 28px; z-index: 999;
      background: #25D366; color: #fff; width: 56px; height: 56px;
      border-radius: 28px; display: flex; align-items: center; justify-content: center;
      text-decoration: none; box-shadow: 0 4px 20px rgba(37,211,102,.4);
      transition: transform .25s, width .3s, padding .3s; overflow: hidden; white-space: nowrap;
    }
    .wa-float svg { width: 26px; height: 26px; flex-shrink: 0; }
    .wa-label { display: none; font-size: .82rem; font-weight: 500; margin-left: 10px; margin-right: 4px; }
    .wa-float:hover { transform: scale(1.04); width: auto; padding: 0 18px 0 14px; }
    .wa-float:hover .wa-label { display: inline; }

    /* ── FOOTER ── */
    footer {
      background: var(--slate-night); padding: 44px 24px; text-align: center;
      border-top: 1px solid rgba(140,106,67,.1);
    }
    .footer-logo { font-family: 'Sora', sans-serif; font-weight: 700; font-size: 1rem; color: rgba(255,255,255,.4); margin-bottom: 14px; }
    .footer-logo em { color: var(--bronze); font-style: normal; }
    .footer-links { display: flex; gap: 24px; justify-content: center; margin-bottom: 20px; flex-wrap: wrap; }
    .footer-links a { color: rgba(255,255,255,.3); text-decoration: none; font-size: .77rem; transition: color .2s; }
    .footer-links a:hover { color: rgba(255,255,255,.7); }
    .footer-copy { font-size: .7rem; color: rgba(255,255,255,.18); }

    @media (max-width: 860px) {
      nav { padding: 0 20px; } .nav-links { display: none; }
    }
  </style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="/" class="nav-logo">Conciergerie <em>Saint-Denis</em></a>
  <ul class="nav-links">
    <li><a href="/">Accueil</a></li>
    <li><a href="/qui-sommes-nous">Qui sommes-nous</a></li>
    <li><a href="/blog" class="active">Blog</a></li>
    <li><a href="https://hostopia.fr/simulateur-estimer-mes-revenus" class="nav-cta" target="_blank">Estimer mes revenus</a></li>
  </ul>
</nav>

<!-- HERO ARTICLE -->
<section class="article-hero vitrail-bg">
  <div class="article-badge">{CATEGORIE} · Saint-Denis, 93</div>
  <h1>{TITRE_H1_AVEC_EM_OPTIONNEL}</h1>
  <div class="article-meta">Par Hostopia · {DATE_FR} · {TEMPS_LECTURE} min de lecture</div>
</section>

<!-- BREADCRUMB -->
<nav aria-label="breadcrumb">
  <div class="breadcrumb">
    <a href="/">Accueil</a> › <a href="/blog">Blog</a> › <span>{TITRE_COURT}</span>
  </div>
</nav>

<!-- ARTICLE + SIDEBAR -->
<div class="article-wrapper">
  <article class="article-body">

    <!-- INTRODUCTION -->
    <p>{INTRODUCTION_ACCROCHEUSE_AVEC_CHIFFRE}</p>
    <p>{CONTEXTE_SAINT_DENIS_TRANSFORMATION}</p>

    <!-- SECTION 1 -->
    <h2 id="s1">{TITRE_SECTION_1}</h2>
    <p>{CONTENU_S1}</p>
    <div class="stat-highlight">
      <div class="stat-num">{CHIFFRE_CLE}</div>
      <div class="stat-label">{DESCRIPTION_CHIFFRE}</div>
    </div>

    <!-- SECTION 2 -->
    <h2 id="s2">{TITRE_SECTION_2}</h2>
    <p>{CONTENU_S2}</p>
    <table class="compare-table">
      <thead>
        <tr><th>Type de bien</th><th>Location classique</th><th>Airbnb optimisé</th><th>Gain</th></tr>
      </thead>
      <tbody>
        <tr><td>Studio (25m²)</td><td>700 €/mois</td><td>1 100 €/mois</td><td class="highlight-row">+57%</td></tr>
        <tr><td>T2 (40m²)</td><td>950 €/mois</td><td>1 650 €/mois</td><td class="highlight-row">+74%</td></tr>
        <tr><td>T3 (60m²)</td><td>1 200 €/mois</td><td>2 100 €/mois</td><td class="highlight-row">+75%</td></tr>
      </tbody>
    </table>

    <!-- SECTION 3 -->
    <h2 id="s3">{TITRE_SECTION_3}</h2>
    <p>{CONTENU_S3}</p>

    <!-- CTA INLINE -->
    <div class="cta-inline">
      <p>Vous êtes propriétaire à Saint-Denis ? Estimez gratuitement vos revenus Airbnb en moins de 2 minutes.</p>
      <a href="https://hostopia.fr/simulateur-estimer-mes-revenus" class="btn-bronze" target="_blank" rel="noopener">
        Estimer mes revenus gratuitement →
      </a>
    </div>

    <!-- SECTION 4 -->
    <h2 id="s4">{TITRE_SECTION_4}</h2>
    <p>{CONTENU_S4}</p>

    <!-- FAQ -->
    <div class="faq-section">
      <h2>Questions fréquentes</h2>
      <div class="faq-item">
        <div class="faq-q">{FAQ_Q1}</div>
        <div class="faq-a">{FAQ_A1}</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">{FAQ_Q2}</div>
        <div class="faq-a">{FAQ_A2}</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">{FAQ_Q3}</div>
        <div class="faq-a">{FAQ_A3}</div>
      </div>
    </div>

    <!-- CONCLUSION -->
    <h2 id="conclusion">Conclusion</h2>
    <p>{CONCLUSION_AVEC_SYNTHESE}</p>
    <p><strong>Prochaine étape :</strong> {PROCHAINE_ETAPE_CTA_NATUREL}</p>

    <!-- CTA FINAL -->
    <div class="cta-inline">
      <p>Confiez la gestion de votre bien à Saint-Denis à une équipe spécialisée. Résultat moyen : +70% de revenus vs location classique.</p>
      <a href="https://calendly.com/hostopia-conciergerie/appel-decouverte" class="btn-bronze" target="_blank" rel="noopener">
        Prendre rendez-vous avec un expert →
      </a>
    </div>

  </article>

  <!-- SIDEBAR -->
  <aside class="article-sidebar">
    <div class="toc-card">
      <h4>Dans cet article</h4>
      <ul>
        <li><a href="#s1">{TITRE_S1_COURT}</a></li>
        <li><a href="#s2">{TITRE_S2_COURT}</a></li>
        <li><a href="#s3">{TITRE_S3_COURT}</a></li>
        <li><a href="#s4">{TITRE_S4_COURT}</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
      </ul>
    </div>
    <div class="sidebar-cta">
      <p>Estimez vos revenus Airbnb à Saint-Denis en 2 min.</p>
      <a href="https://hostopia.fr/simulateur-estimer-mes-revenus" class="btn-bronze" target="_blank" rel="noopener" style="font-size:.82rem; padding:10px 18px;">
        Simulateur gratuit →
      </a>
    </div>
  </aside>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">Conciergerie <em>Saint-Denis</em></div>
  <div class="footer-links">
    <a href="/">Accueil</a>
    <a href="/qui-sommes-nous">Qui sommes-nous</a>
    <a href="/blog">Blog</a>
    <a href="https://hostopia.fr" target="_blank" rel="noopener">hostopia.fr</a>
    <a href="https://calendly.com/hostopia-conciergerie/appel-decouverte" target="_blank" rel="noopener">Prendre RDV</a>
  </div>
  <div class="footer-copy">© 2025 Hostopia — Conciergerie Airbnb Saint-Denis · Tous droits réservés</div>
</footer>

<!-- WHATSAPP FLOAT -->
<a href="https://wa.me/33767209266" class="wa-float" target="_blank" rel="noopener" aria-label="WhatsApp">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
  <span class="wa-label">WhatsApp</span>
</a>

<!-- REVEAL SCRIPT -->
<script>
  const obs = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); obs.unobserve(e.target); } });
  }, { threshold: 0.1 });
  document.querySelectorAll('.reveal').forEach(el => obs.observe(el));
</script>

</body>
</html>
```

---

## PHASE 5 — MISE À JOUR BLOG INDEX

**RÈGLE CRITIQUE — ne jamais régénérer ce fichier en entier.** Insertion chirurgicale uniquement : récupérer le contenu tel quel (GET), repérer l'ancre existante (bloc "coming soon" s'il existe encore, sinon la carte la plus récente), insérer la/les nouvelle(s) carte(s) juste avant cette ancre sans modifier un seul autre caractère du fichier. Avant le PUT, valider que `nouveau_contenu.count('class="article-card"') == ancien_contenu.count('class="article-card"') + (nombre d'articles publiés ce run)`. Si la validation échoue, ne pas publier.

Après génération du fichier article, mettre à jour `blog/index.html`.

### Localiser la section des articles publiés

Chercher dans `blog/index.html` la section contenant les articles (ou la "coming soon card" si aucun article n'existe encore).

### Card article à insérer (ajouter en tête de liste)

```html
<a href="/blog/{SLUG}" class="article-card reveal">
  <div class="article-card-meta">
    <span class="topic-tag">{CATEGORIE}</span>
    <span class="article-date">{DATE_FR}</span>
  </div>
  <h3>{TITRE_H1}</h3>
  <p class="article-excerpt">{RESUME_2_PHRASES}</p>
  <span class="article-read-more">Lire l'article →</span>
</a>
```

Si la section articles n'existe pas encore dans `blog/index.html`, la créer avant la section newsletter :

```html
<!-- ARTICLES PUBLIÉS -->
<section class="blog-section vitrail-bg" id="articles">
  <div class="container">
    <div class="articles-grid">
      <!-- {CARD_ARTICLE} -->
    </div>
  </div>
</section>
```

Avec les styles associés :
```css
.articles-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 24px; margin-bottom: 56px; }
.article-card { background: rgba(255,255,255,.72); backdrop-filter: blur(8px); border: 1px solid rgba(140,106,67,.18); border-radius: 12px; padding: 28px 24px; text-decoration: none; color: inherit; transition: transform .25s, border-color .25s; display: block; }
.article-card:hover { transform: translateY(-3px); border-color: rgba(140,106,67,.38); }
.article-card-meta { display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px; }
.article-date { font-size: .74rem; color: var(--steel); }
.article-card h3 { font-family: 'Sora', sans-serif; font-size: 1.05rem; font-weight: 700; color: var(--slate); line-height: 1.35; margin-bottom: 10px; }
.article-excerpt { font-size: .82rem; color: var(--text-m); line-height: 1.7; margin-bottom: 14px; }
.article-read-more { font-family: 'Sora', sans-serif; font-size: .78rem; font-weight: 600; color: var(--bronze); }
```

---

## PHASE 6 — MISE À JOUR SITEMAP

**RÈGLE CRITIQUE — ne jamais régénérer ce fichier en entier.** Le fichier contient déjà des dizaines d'entrées `<url>` ; le retaper intégralement (ancienne méthode) est la cause confirmée de sitemaps corrompus en production sur plusieurs sites de ce réseau (tags mal fermés, entrées perdues silencieusement). La seule opération autorisée est une insertion chirurgicale :

1. Récupérer le contenu actuel de `sitemap.xml` tel quel (GET, voir PHASE 7).
2. Pour chaque nouvel article publié dans ce run, construire un bloc :

```xml
  <url>
    <loc>https://conciergeriesaintdenis.fr/blog/{SLUG}</loc>
    <lastmod>{DATE_YYYY-MM-DD}</lastmod>
    <changefreq>monthly</changefreq>
    <priority>0.7</priority>
  </url>
```

3. Construire le nouveau contenu = contenu récupéré au GET, avec la sous-chaîne littérale `</urlset>` remplacée par : (tous les blocs `<url>` de l'étape 2, concaténés) + `</urlset>`.
4. **Ne modifier aucun autre caractère du fichier.** Toutes les entrées `<url>` déjà présentes doivent rester strictement identiques, caractère pour caractère, à ce qui a été récupéré au GET. Ne jamais retaper une entrée existante.
5. Avant le PUT, valider :
   - `nouveau_contenu.count("<url>") == ancien_contenu.count("<url>") + (nombre d'articles publiés ce run)`
   - `nouveau_contenu.count("<urlset") == 1` et `nouveau_contenu.count("</urlset>") == 1`
   - Si une validation échoue : NE PAS publier ce fichier. Passer à PHASE 9 (échec) et signaler l'erreur au lieu d'écrire un XML invalide.

Fichier : `sitemap.xml` à la racine du repo.

Ajouter l'entrée suivante dans `<urlset>` :

```xml
<url>
  <loc>https://conciergeriesaintdenis.fr/blog/{SLUG}</loc>
  <lastmod>{DATE_ISO}</lastmod>
  <changefreq>monthly</changefreq>
  <priority>0.7</priority>
</url>
```

---

## PHASE 7 — PUBLICATION GITHUB

### 7a. Vérifier si le fichier existe déjà (GET)

```
GET https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/blog/{SLUG}.html
Authorization: token {GITHUB_TOKEN}
```

Si la réponse contient un champ `sha` → fichier existant (UPDATE, méthode PUT avec sha).
Si 404 → nouveau fichier (CREATE, méthode PUT sans sha).

### 7b. Encoder le contenu HTML en base64

```python
import base64
content_b64 = base64.b64encode(html_content.encode('utf-8')).decode('utf-8')
```

### 7c. Créer ou mettre à jour l'article

```
PUT https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/blog/{SLUG}.html
Authorization: token {GITHUB_TOKEN}
Content-Type: application/json

{
  "message": "feat: article '{TITRE_COURT}' — {DATE_ISO}",
  "content": "{CONTENT_BASE64}",
  "sha": "{SHA_SI_UPDATE}"  // omettre si nouveau fichier
}
```

### 7d. Mettre à jour blog/index.html

```
GET https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/blog/index.html
→ récupérer sha
PUT https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/blog/index.html
→ contenu mis à jour + sha récupéré
→ message: "feat: ajout article '{TITRE_COURT}' dans blog index"
```

### 7e. Mettre à jour sitemap.xml

```
GET https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/sitemap.xml
→ récupérer sha
PUT https://api.github.com/repos/Lounax93/conciergerie-saintdenis/contents/sitemap.xml
→ contenu mis à jour + sha récupéré
→ message: "chore: sitemap — ajout {SLUG}"
```

---

## PHASE 8 — DÉPLOIEMENT VERCEL

### Trigger deploy

```
POST https://api.vercel.com/v1/deployments
Authorization: Bearer {VERCEL_TOKEN}
Content-Type: application/json

{
  "name": "conciergerie-saintdenis",
  "gitSource": {
    "type": "github",
    "repoId": "Lounax93/conciergerie-saintdenis",
    "ref": "main"
  },
  "projectId": "prj_0wqJ5C3CZjiwJT80XXy7rXL7zcke",
  "target": "production"
}
```

### Vérifier le statut du déploiement

```
GET https://api.vercel.com/v13/deployments/{DEPLOYMENT_ID}
Authorization: Bearer {VERCEL_TOKEN}
```

Attendre que `status` passe à `READY` (polling toutes les 15 secondes, timeout 5 minutes).

### Vérification finale

```
GET https://conciergeriesaintdenis.fr/blog/{SLUG}
```

Vérifier HTTP 200 + présence du titre dans le HTML.

---

## GESTION DES ERREURS

### Erreur GitHub API 422 (sha manquant sur update)
→ Refaire GET pour récupérer le sha actuel, puis relancer le PUT avec le sha.

### Erreur Vercel deploy timeout (> 5 min)
→ Vérifier les logs Vercel :
```
GET https://api.vercel.com/v2/deployments/{DEPLOYMENT_ID}/events
```
Identifier l'erreur, corriger le fichier HTML si nécessaire, relancer.

### Article non accessible après déploiement (404)
→ Vérifier que le fichier est bien dans `blog/` et non à la racine.
→ Vérifier `vercel.json` : `"cleanUrls": true` gère l'extension `.html` automatiquement.
→ L'URL finale doit être `https://conciergeriesaintdenis.fr/blog/{SLUG}` (sans `.html`).

### Erreur base64 encoding
→ Toujours encoder en UTF-8 avant base64. Vérifier les caractères spéciaux français (é, è, à, ç).

### Aucun article publié après 10 tentatives
→ Logger l'erreur complète, notifier via Telegram avec le message d'erreur exact.
→ Mettre l'article en file d'attente et réessayer au prochain créneau horaire.

---

## BOUCLE D'AUTO-AMÉLIORATION

Après chaque publication réussie, évaluer :

1. **Performance SEO** : Titre contient-il le mot-clé principal ? Meta description < 160 chars ? H1 unique ?
2. **Lisibilité** : Article > 1 200 mots ? Au moins 1 chiffre concret ? CTA présent ?
3. **Ancrage local** : "Saint-Denis" apparaît dans H1 ? Au moins 3 fois dans le corps ?
4. **Liens** : Article pointe vers le simulateur Hostopia ? Lien interne vers blog/index ?

Si un critère échoue → noter le problème + appliquer la correction sur l'article suivant.

**Log de performance** (à maintenir en mémoire inter-sessions) :
```json
{
  "date": "{DATE_ISO}",
  "slug": "{SLUG}",
  "mots": {NB_MOTS},
  "cta_present": true,
  "saint_denis_count": {N},
  "deploy_success": true,
  "deploy_time_sec": {T}
}
```

---

## INSTRUCTIONS FINALES

1. **Ne jamais sauter une phase** — chaque phase dépend de la précédente.
2. **Toujours vérifier l'URL finale** en HTTP GET avant de marquer la tâche comme terminée.
3. **En cas d'échec** : logger l'erreur, corriger, relancer. Ne jamais passer la journée sans les 2 articles.
4. **Varier les sujets** : alterner entre revenus, transformation urbaine, gestion pratique, guides quartiers.
5. **Ancrage local obligatoire** : chaque article doit mentionner au moins l'un des landmarks : Stade de France, Pleyel, Basilique, Grand Paris Express.
6. **Mise à jour du stock** : après 20 articles publiés, générer 20 nouveaux sujets avec une recherche web actualisée.
