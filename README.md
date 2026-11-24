# Dealer growth platform (preview)

Two versions of the same offer for used car dealers, published together so they can be compared.

| Page | URL | Leads with |
|---|---|---|
| DSC-led | https://dealersales.github.io/dealer-growth-platform/ | Digital Sales Consultants, Carki's finance inside |
| Carki-led | https://dealersales.github.io/dealer-growth-platform/carki/ | Carki's finance and branding, DSC's website and stock inside |

- Not indexed (`noindex`, `robots.txt` disallow) and not the launch build.
- Do not point a client domain at this repo. The production version belongs on
  sales-consultants.com, served outside the theme.
- The small "Compare" chip is added by the build to these copies only; the standalone
  HTML files sent to clients do not carry it.

Built from `~/Projects/dsc-dealer-growth-platform` (`python3 build.py`). Do not edit
`index.html` here by hand: change `src/index.html` or `src/carki.html` and rebuild.
