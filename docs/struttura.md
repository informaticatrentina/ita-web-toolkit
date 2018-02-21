---
order: 30
title: Struttura del file system
label: Struttura del file system
---

La directory `src` contiene le sotto-directory:

- **components** - componenti base (CSS/HTML) quali form, bottoni, griglia responsive, tipografia, ...
- **fonts** - il font Titillium Web e le direttive CSS @font-face relative
- **icons** - le icone svg / png utilizzate nel progetto e il CSS per l'*icon font*
- **legacy** - CSS per supportare i vecchi browser
- **modules** - CSS/Javascript per i vari elementi dell'interfaccia (es. accordion, carousel, ...)
- **scripts** - Javscript "globali" (non legati a una particolare componente dell'interfaccia)
- **templates** - template HTML per elementi del layout e pagine web
- **themes** - il foglio di stile con le personalizzazioni per uno specifico tema (es. colore principale dal quale viene declinata l'intera *palette*)
- **utils** - CSS contenenti classi di utilità generica (margini, padding, tipografia responsive, ...)
- **vendor** - Javascript da incorporare per garantire un minimo grado di compatibilità con i browser obsoleti (IE8/9)

```
.
├── docs
└── src
    ├── components
    │   ├── button
    │   ├── form
    │   ├── grid
    │   ├── heading
    │   └── ...
    ├── fonts
    │   └── titillium
    │       └── font
    ├── icons
    │   └── ita
    │       ├── font
    │       ├── png
    │       └── svg
    ├── legacy
    ├── modules
    │   ├── accordion
    │   └── ...
    ├── scripts
    ├── templates
    │   ├── layout
    │   ├── pages
    │   └── ...
    ├── themes
    │   └── pac
    ├── utils
    │   ├── borders
    │   ├── colors
    │   └── ...
    └── vendor
```

[Realizzare un tema](tema)

{% include '_footer.md' %}
