# Northguard Materieel B.V. — Website

Meertalige (NL / EN / TR) bedrijfswebsite voor **Northguard Materieel B.V.**
Dutch Engineering · European Manufacturing · Industrial Material Handling Solutions.

## Structuur

```
northguard/
├── index.html          # Home
├── producten.html      # Producten (FlatWagon, HandWagon, SteelPallet, AutoRack, opslagrekken, maatwerk)
├── diensten.html       # Industriële dienstverlening (isolatie, fireproofing, betonwerk)
├── over-ons.html       # Over ons / Engineering & Manufacturing
├── media.html          # Video's + fotogalerij
├── contact.html        # Contact + formulier
├── assets/
│   ├── logo-ng.png     # Logo (transparant)
│   ├── favicon.png
│   ├── img/            # Geoptimaliseerde foto's
│   └── video/          # 3 video's + posterframes
└── README.md
```

De logo is als transparante afbeelding **direct in elke pagina ingesloten**, zodat hij altijd laadt — ook los geopend of in een preview.

## Bekijken

Open `index.html` in je browser. De taalkeuze (NL / EN / TR, rechtsboven) wordt onthouden tussen pagina's. De navigatie is gecentreerd met losse pagina's per tab.

## Naar GitHub pushen

Repo `northguard` (owner `yciftci111`) is aangemaakt. Daarna:

```bash
cd northguard
git init
git add .
git commit -m "Northguard website (NL/EN/TR)"
git branch -M main
git remote add origin https://github.com/yciftci111/northguard.git
git push -u origin main
```

## Gratis online zetten (GitHub Pages)

Repo → **Settings → Pages** → Source: **Branch main / (root)** → Save.
Na ~1 minuut live op `https://yciftci111.github.io/northguard/`.

## Inhoud & aandachtspunten

- **Contact:** mobiel +31 (0)6 444 50 245 · info@northguard.nl · Nederland (HQ) · Productie: Kayseri Free Zone, Türkiye.
- **Producten** gebruiken de aangeleverde praktijkfoto's. Voor **NG AutoRack System** zijn geen CAD-beelden aangeleverd — daar staat "CAD-beelden op aanvraag"; lever je ze aan, dan plaats ik ze.
- Er zijn geen technische specificaties verzonnen: overal staat "Technische specificaties op aanvraag".
- Alle teksten (3 talen) staan gebundeld in het `T`-object onderaan elke pagina. Wil je 1 centrale vertaalbron? Dan splits ik het naar `assets/i18n.js`.
- Het contactformulier toont nu een bevestiging via JavaScript. Voor echt versturen koppel je [Formspree](https://formspree.io) of Netlify Forms (form `action` aanpassen).

## Accentkleur

De site gebruikt het **oranje/antraciet** uit het logo. In de merkbeschrijving werd ook een groen accent genoemd; wil je de site naar groen? Dat is één variabele (`--orange` in de `<style>`) — laat het weten en ik zet het om.
