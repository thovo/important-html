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
  ## Important of HTML and Green IT
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
fonts:
  # basically the text
  sans: 'Robot'
  # use with `font-serif` css class from windicss
  serif: 'Robot Slab'
  # for code blocks, inline code, etc.
  mono: 'Fira Code'
---

# Paris Web 2022, les sujets intéressants

- Est-ce que vous savez l'important d'HTML?
- Green IT, comment développer le façon durable ?

---

# L'histoire d'HTML

- HTML a été créé par Sir Tim Berners-Lee avec les 19 premières tags
- Facile à apprendre et aussi facile à oublier d'utiliser correctement

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
<SlideCurrentNo /> / <SlidesTotal />
---

# Vous vous rappelez toutes les tags HTML?

Il y a plusieurs semaines, je vous ai demandé de faire un test HTML pour voir de combien de balises HTML vous vous souvenez. Vous pouvez trouver l'HTML Memory Test [ici](https://codepen.io/plfstr/full/zYqQeRw)

![HTML Memory Test](/assets/images/html-memory-test.png)

<SlideCurrentNo /> / <SlidesTotal />
---

# Div n'est pas le seul élément qu'on peut utiliser

- Utiliser les bons tags pour construire votre page plus sémantiques
- Donner une visualization direct comment la page va être présenté sur navigateur

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

<SlideCurrentNo /> / <SlidesTotal />
---

# Green IT, comment on comprends ce sujet ?

Premièrement, je vous présente quelque images importants:

<div grid="~ cols-2 gap-4">
<div>
<img src="/assets/images/sketchnote_surface_réchauffée_par_GES-Sophie_Sorel-Giffo-web-total.webp" class="m-auto h-60"/>
<a href="https://www.greenit.fr/2020/11/03/100-portables-rechauffent-1-hectare-de-planete-dun-degre-pendant-60-ans/">100 portables réchauffent 1 hectare de planète d’un degré pendant 60 ans</a>
</div>

<div>
<img src="/assets/images/The_Global_E-wasteMonitor2020-world.webp" class="m-auto h-60"/>
<a href="https://www.greenit.fr/2020/07/03/dechets-electroniques-21-en-5-ans/">Déchets électroniques + 21 % en 5 ans</a>
</div>
</div>

<SlideCurrentNo /> / <SlidesTotal />
---

# Les citations importants
> Le numérique représente 4% des émissions de gaz à effet de serre dans le monde. Et ce chiffre risque de doubler d’ici à 2025.
>
> -- <cite>[Hello Carbo](https://www.hellocarbo.com/blog/calculer/impact-du-numerique-sur-l-environnement/)</cite>

Et en France:

> 3% de la consommation d’énergie finale de la France en croissance de 25 % entre 2015 et 2030
>
> -- <cite>[Sobriété énergétique : comment réduire la consommation électrique du numérique ?](https://www.greenit.fr/2022/09/13/sobriete-energetique-comment-reduire-la-consommation-electrique-du-numerique-4-4/)</cite>

<img src="/assets/images/inum2020-kpi.webp" class="m-auto h-60"/>

<SlideCurrentNo /> / <SlidesTotal />
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

<SlideCurrentNo /> / <SlidesTotal />
---

# Les outils

- L'outil de "Compatibility" de Firefox 98
- Green IT analysis 

<img src="/assets/images/green-it-analyses.png" class="m-auto h-80"/>

<SlideCurrentNo /> / <SlidesTotal />
---

# References

- Paris Web Green IT: https://www.paris-web.fr/2022/conferences/greenit-que-faire-en-tant-que-professionnel-du-web.php
- Paris Web Lost in Translation: https://www.paris-web.fr/2022/conferences/lost-in-translation.php
- Green IT:
  - Les impacts environnementaux en France: https://www.greenit.fr/2020/06/23/quels-sont-les-impacts-environnementaux-du-numerique-en-france/
  - Déchets électroniques : + 21 % en 5 ans: https://www.greenit.fr/2020/07/03/dechets-electroniques-21-en-5-ans/
  - 100 portables réchauffent 1 hectare de planète d’un degré pendant 60 ans: https://www.greenit.fr/2020/11/03/100-portables-rechauffent-1-hectare-de-planete-dun-degre-pendant-60-ans/

<SlideCurrentNo /> / <SlidesTotal />
---

# Questions ? Et merci beaucoup de votre attention !

<img src="/assets/images/thanks.jpeg" class="m-auto h-80"/>
