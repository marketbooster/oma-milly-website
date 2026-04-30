# SEO klaar! Wat nu?

## ✅ Wat ik al heb gedaan

In je `index.html` staan nu:
- **SEO meta-tags** — Google ziet titel, beschrijving en zoekwoorden
- **Open Graph tags** — bij delen op WhatsApp/Facebook/LinkedIn verschijnt een mooi voorbeeld met titel, beschrijving en afbeelding
- **Twitter Card tags** — zelfde maar voor Twitter/X
- **Structured Data (JSON-LD)** — vertelt Google dat dit een BOEK is, met auteur, prijs, leeftijd, taal etc. Hiermee kun je in Google verschijnen met een speciale "boek-kaart"
- **Schildpad-favicon** 🐢 — het kleine icoontje in het browser-tabblad

Twee nieuwe bestanden in je map:
- `sitemap.xml` — een lijst van alle pagina's voor Google
- `robots.txt` — vertelt zoekmachines welke pagina's ze mogen indexeren

## 📤 Stap 1 — Upload de nieuwe bestanden

1. Ga naar je Netlify-tab
2. Sleep de hele map `oma-milly-website` (alle 4 bestanden tegelijk: `index.html`, `sitemap.xml`, `robots.txt`, en eventuele andere) op het Production deploys vakje
3. Wacht tot Netlify klaar is

Test of de bestanden goed staan door deze URLs te bezoeken:
- https://omamilly.netlify.app/sitemap.xml
- https://omamilly.netlify.app/robots.txt

Beide moeten zichtbaar zijn (geen 404).

## 🖼️ Stap 2 — Upload een Open Graph afbeelding (BELANGRIJK!)

Op dit moment staat in je site dat een afbeelding op `omamilly.netlify.app/og-image.jpg` zou moeten staan, maar dat bestand is er nog niet. Zonder die afbeelding zien delingen op WhatsApp/Facebook er saai uit.

**Wat je nodig hebt:** een afbeelding van **1200 x 630 pixels** (dat is de standaard voor delingen).

**Idee:** je boekomslag plus de tekst "Oma Milly en de Grote Zee — voor iedereen die iemand moet missen" op een mooie watercolor achtergrond.

**Hoe maak je hem:**
- Optie 1: Maak hem in Canva (gratis sjablonen voor "Open Graph image")
- Optie 2: Vraag mij om er één te maken op basis van je boekomslag
- Optie 3: Gebruik de boekomslag uit je PDF, exporteer als JPG, schaal naar 1200x630

Sla het op als `og-image.jpg` en zet hem in dezelfde map als `index.html`. Sleep de map opnieuw naar Netlify.

## 🔍 Stap 3 — Aanmelden bij Google Search Console

Hiermee laat je Google weten dat je site bestaat. Zonder dit kan het wel weken duren voordat Google je vindt.

1. Ga naar **search.google.com/search-console**
2. Log in met je Google account (gewoon je Gmail)
3. Klik **"Eigendom toevoegen"** of **"Add property"**
4. Kies **"URL-prefix"** (de rechter optie)
5. Vul in: `https://omamilly.netlify.app`
6. Klik **Doorgaan**
7. Google vraagt om verificatie. Kies **"HTML-tag"** als methode
8. Je krijgt een meta-tag te zien zoals:
   ```html
   <meta name="google-site-verification" content="ABC123xyz...">
   ```
9. **Stuur die tag naar mij** in de chat — dan voeg ik hem toe aan je site
10. Upload de bijgewerkte site naar Netlify
11. Klik in Search Console op **"Verifiëren"**
12. ✅ Klaar — Google weet nu dat je site van jou is

## 📋 Stap 4 — Sitemap indienen bij Google

Nadat je geverifieerd bent in Search Console:

1. In Search Console: links menu → **Sitemaps**
2. Bij "Nieuwe sitemap toevoegen" vul je in: `sitemap.xml`
3. Klik **Indienen**
4. Google gaat nu je site indexeren — dat kan 1-7 dagen duren

## 🎯 Stap 5 — Bij Bing aanmelden (bonus)

Bing is kleiner maar wordt gebruikt door bijvoorbeeld DuckDuckGo en Yahoo:

1. Ga naar **bing.com/webmasters**
2. Inloggen met je Microsoft of Google account
3. **"Site importeren uit Google Search Console"** — als je dat hebt gedaan, neemt Bing alles automatisch over
4. Anders: handmatig site toevoegen, vergelijkbaar als Google

## 🧪 Stap 6 — Testen of alles werkt

Test je SEO setup met deze gratis tools:

- **OG-tags checker**: opengraph.dev — plak je URL, kijk hoe je site eruitziet bij delen
- **Google Rich Results Test**: search.google.com/test/rich-results — controleert je Structured Data
- **Mobile-friendly test**: search.google.com/test/mobile-friendly — kijkt of je site goed werkt op telefoons
- **PageSpeed Insights**: pagespeed.web.dev — meet hoe snel je site laadt

## 💡 Tips voor betere vindbaarheid op lange termijn

1. **Voeg vaker content toe** — een blogje over rouwverwerking, signeersessies, of nieuwe boeken zorgt dat Google je site regelmatig bezoekt
2. **Vraag andere sites om naar je te linken** — kindertherapeuten, leesblogs, kinderboekenwinkels
3. **Maak Instagram/TikTok content** — kort filmpje over het boek met link in bio
4. **Bibliotheken aanschrijven** — vraag of ze je boek willen opnemen, plus een link op hun site
5. **Echte recensies** — laat lezers reviews achter op je site (niet alleen plaatsvervangers)

## 🆘 Hulp nodig?

Voor elke stap mag je terugkomen met vragen:
- "Hoe upload ik de bijgewerkte map naar Netlify?"
- "Ik heb de Google verificatie-tag, hoe voeg je die toe?"
- "Wil je een Open Graph afbeelding voor me ontwerpen?"

Eén stap per keer. Geen haast.
