---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# Aujourd’hui je vous raconte une histoire

Regarde ce vidéo

---

# HTML est facile à apprendre mais aussi facile à oublier

On a oublié d'utiliser correctement HTML, regarde cette code magnifique 

```html
<div class="header"></div>
<div class="nav">
    <div class="menu">
        <div class="menu-item"></div>
        <div class="menu-item"></div>
        <div class="menu-item"></div>
    </div>
    <div class="button"></div>
    <div class="paragraph">Here is a long paragraph</div>
</div>
<div class="footer"></div>
```
---

# Vous vous rappelez toutes les tags HTML?

Il y a plusieurs semaines, je vous ai demandé de faire un test HTML pour voir de combien de balises HTML vous vous souvenez

---

# On n'a pas seulement div

Utiliser les bons tags pour construire votre page plus sémantiques

```html
<header></header>
<nav>
    <menu>
        <li class="menu-item"></li>
        <li class="menu-item"></li>
        <li class="menu-item"></li>
    </menu>
    <button></button>
    <p>Here is a long paragraph</p>
</nav>
<footer></footer>
```

---

# Fautes souvent trouver sur 1 millions sites, que faire ?

|          WCAG Failure Type          | % of home pages in 2022 | % of home pages in 2021 | % of home pages in 2020 | % of home pages in 2019 |
|:-----------------------------------:|:-----------------------:|:-----------------------:|:-----------------------:|:-----------------------:|
| Low contrast text                   | 83.9%                   | 86.4%                   | 86.3%                   | 85.3%                   |
| Missing alternative text for images | 55.4%                   | 60.6%                   | 66.0%                   | 68.0%                   |
| Empty links                         | 50.1%                   | 51.3%                   | 59.9%                   | 58.1%                   |
| Missing form input labels           | 46.1%                   | 54.4%                   | 53.8%                   | 52.8%                   |
| Empty buttons                       | 27.2%                   | 26.9%                   | 28.7%                   | 25.0%                   |
| Missing document language           | 22.3%                   | 28.9%                   | 28.0%                   | 33.1%                   |

---

# Quelque mots importants

> 96,5 % de toutes les erreurs détectées entrent dans ces six catégories. Ces erreurs les plus courantes sont les mêmes depuis 4 ans. La résolution de ces quelques types de problèmes améliorerait considérablement l'accessibilité sur le Web.
>
> -- <cite>Web Aim</cite>

Pour comprendre bien les problèmes et chercher les solutions, accéder le lien ci-dessous:

[https://webaim.org/projects/million/](https://webaim.org/projects/million/)

Alors, n'oublier pas d'utiliser correctement HTML tags 

# Et encore un truc important, comment sauver notre Terre ?

> Le numérique représente 4% des émissions de gaz à effet de serre dans le monde. Et ce chiffre risque de doubler d’ici à 2025.
>
> -- <cite>[Hello Carbon](https://www.hellocarbo.com/blog/calculer/impact-du-numerique-sur-l-environnement/)</cite>

Et en France:

> 3% de la consommation d’énergie finale de la France en croissance de 25 % entre 2015 et 2030
>
> -- <cite>[Sobriété énergétique : comment réduire la consommation électrique du numérique ?](https://www.greenit.fr/2022/09/13/sobriete-energetique-comment-reduire-la-consommation-electrique-du-numerique-4-4/)</cite>

---

# Qu'est ce qu'on peut faire pour réduire l'utilisation d'énergie ?

Réduire la quantité de ressources nécessaires au fonctionnement du service:

- Construire des architectures et applicatifs efficients
- Optimiser application pour consumer moins de ressources
- Rechercher des sources d'efficience à tous les niveaux de l'application et dans tous les métiers
- Éliminer les fonctionnalités non essentielles
- Un design simple et épuré
- Fluidifier le parcours de l'utilisateur 
- Fournir une alternative texte aux contenus multimédia
- Être compatible avec les "vieux" appareils et logiciels
- Mobile firsts

---

# Les outils

- L'outil de "Compatibility" de Firefox 98
- Green IT analysis 