# Salon Gospođica — marketing sajt (MVP)

Statički marketing sajt za **Salon lepote Gospođica** (Beograd — Žarkovo i Vračar).  
Kopija na srpskom, booking CTA ka SrediMe za obe lokacije.

**Repo:** https://github.com/markmarvik/salon-gospodjica

## Lokalni pregled

Nije potreban build — otvorite `index.html` u pregledaču ili pokrenite lokalni server:

```bash
# Python
python3 -m http.server 8080 --directory .

# ili Node
npx --yes serve .
```

Zatim otvorite http://localhost:8080

## Struktura

| Fajl | Opis |
|------|------|
| `index.html` | Single-page sajt (Početna, Usluge, Lokacije, Recenzije, Kontakt / Zakaži) |
| `styles.css` | Stilovi (mobile-first, elegantna estetika) |
| `script.js` | Mobilni meni, godina u footeru, navigacija |
| `favicon.svg` | Ikona |
| `og-image.svg` | Open Graph slika |
| `README.md` | Ovaj fajl |

## GitHub Pages — objavljivanje

1. Otvorite repo na GitHubu → **Settings** → **Pages**.
2. Under **Build and deployment** → **Source**: izaberite **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Posle 1–2 minuta sajt će biti na:

   **https://markmarvik.github.io/salon-gospodjica/**

Custom domen (opciono): Settings → Pages → Custom domain.

## Lokacije (NAP)

### Žarkovo (glavni)
- Ace Joksimovića 46b, Beograd 11030
- Tel: [063 698 460](tel:+38163698460)
- Radno vreme: Pon–Pet 12–20, Sub 11–15, Ned zatvoreno
- SrediMe: https://www.sredime.rs/beograd/salon-gospodjica

### Vračar
- Cara Nikolaja II 79, Beograd
- Tel: [060 014 7800](tel:+381600147800)
- SrediMe: https://www.sredime.rs/beograd/salon-tijana-mrdjen-pmu-esthetics

## Pravne napomene

Footer: **TIJANA MRĐEN PR KOZMETIČKI SALON GOSPOĐICA**, PIB **113748401**.

## Napomena o SrediMe widget-ima

Iframe ugradnje (`/widget/...`) mogu biti blokirane cross-origin politikom SrediMe.  
Dugmad „Zakaži na SrediMe“ uvek rade kao primarni CTA.
