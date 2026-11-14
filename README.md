# BALANS.PL — landing page (PL/UA)

Statyczna, dwujęzyczna (PL/UA) strona dla biura rachunkowego. Jeden plik: `index.html`.

## Publikacja na GitHub Pages
1. Wgraj pliki do repozytorium (`index.html` w katalogu głównym).
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**.
3. Strona będzie pod `https://<login>.github.io/<repo>/`.

## Przed publikacją zmień
- `canonical`, `og:url`, `robots.txt`, `sitemap.xml` — zamień `https://balanspl.netlify.app/` na swój adres.
- Formularz: w `index.html` wpisz `FORM_ENDPOINT` (np. Formspree). Bez tego na GitHub Pages formularz otworzy klienta poczty (mailto).
- Dane firmowe w JSON-LD (adres, telefon, ocena) — wstaw prawdziwe.

## Pliki
- `index.html` — strona
- `robots.txt`, `sitemap.xml` — SEO
- `netlify.toml` — tylko dla hostingu Netlify (na GitHub Pages ignorowany)
- `.nojekyll` — wyłącza Jekyll na GitHub Pages
