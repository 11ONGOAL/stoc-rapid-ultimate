# StocRapid / Alexa Imports — versiune GitHub

Site static pregătit pentru încărcare într-un repository GitHub.

## Conținut
- `index.html` la rădăcina repository-ului;
- paginile produselor în `products/`;
- CSS și JavaScript în `assets/`;
- imaginile în `assets/images/`;
- logo-ul și imaginile produselor similare folosesc fișiere locale validate;
- `404.html` inclus;
- `.nojekyll` inclus pentru compatibilitate cu GitHub Pages.

## Publicare în GitHub
Încarcă **conținutul acestui folder** în rădăcina repository-ului, apoi fă commit/push.

Dacă repository-ul este folosit ca sursă pentru Vercel, Vercel poate importa direct repository-ul, fără altă structură specială.

Dacă folosești GitHub Pages, în `Settings > Pages` publică branch-ul care conține aceste fișiere și folderul `/ (root)`.
