# Tempelløb 3D

Et 3D-løbespil i stil med Temple Run, bygget med Three.js i én enkelt fil (`index.html`).

**Spil:** åbn `index.html` i en browser (mobil eller computer). Ingen build nødvendig.

## Deploy på Vercel
Projektet er en statisk side og kræver ingen build. Three.js ligger i `vendor/`, så spillet ikke afhænger af en CDN.

1. Gå til [vercel.com/new](https://vercel.com/new) og importér GitHub-repoet `mikk563h/holdbar`.
2. Vælg branchen med spillet, og lad **Framework Preset** stå på **Other**. Build Command og Output Directory skal være tomme.
3. Tryk **Deploy**. Spillet ligger nu på `https://<projekt>.vercel.app`.

Eller fra terminalen: `npx vercel` (preview) og `npx vercel --prod` (produktion).

## Styring
- **Swipe op** / ↑ / W / mellemrum – hop (over stammer, bål og huller)
- **Swipe ned** / ↓ / S – buk dig (under bjælker)
- **Swipe venstre/højre** / ← → / A D – skift bane

## Indhold
- Tre baner med forhindringer: stammer, stenblokke, bjælker, bålfelter og huller i banen
- Farten stiger jo længere du løber
- Saml mønter – de gemmes mellem spil
- **Butik:** ekstra liv, skjold, magnet og dobbelt mønter
- Når du dør, kan du bruge et liv (eller købe et med mønter) og fortsætte løbet
