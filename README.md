# Northguard

Meertalige website (NL / EN / TR) voor Northguard — bouw & constructie.

## Structuur

```
northguard/
├── index.html        # Complete one-page site met taalswitcher
├── assets/
│   └── logo.png      # Logo (N-schild)
└── README.md
```

## Lokaal bekijken

Open `index.html` in je browser. Klik rechtsboven op **NL / EN / TR** om van taal te wisselen.

## Naar GitHub pushen

De repo `northguard` (owner `yciftci111`) maak je aan zoals in je screenshot. Daarna:

```bash
cd northguard
git init
git add .
git commit -m "Initial commit: Northguard website"
git branch -M main
git remote add origin https://github.com/yciftci111/northguard.git
git push -u origin main
```

## Gratis online zetten (GitHub Pages)

1. Ga in de repo naar **Settings → Pages**.
2. Bij *Source* kies **Branch: main** en map **/(root)**.
3. Opslaan. Na ~1 minuut staat de site op `https://yciftci111.github.io/northguard/`.

## Nog aanpassen

Placeholders die je nog wilt invullen staan in `index.html`:

- Telefoon: `+31 (0)10 000 00 00`
- E-mail: `info@northguard.nl`
- Adres: `Rotterdam, Nederland`
- Statistieken (15+ jaar, 250+ projecten) en teksten in Over ons.

Alle vertaalteksten staan gebundeld in het `TR`-object onderaan `index.html` — pas ze daar aan voor alle drie de talen.

Het contactformulier toont nu een bevestiging via JavaScript. Voor echt versturen koppel je een dienst als [Formspree](https://formspree.io) of [Netlify Forms](https://docs.netlify.com/forms/setup/).
