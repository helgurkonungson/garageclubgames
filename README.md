# garageclubgames.ru

Static site of GarageClub Games. Plain HTML and CSS, no build step, no JavaScript, fonts self-hosted.

Deploy: Cloudflare Pages, connect this repo, branch `main`, build command empty, output directory `/`.

- `index.html`, `arrowcats/`, `chompbook/`: home and game pages
- `legal/`, `privacy/`, `credits/`, `arrowcats/{privacy,terms,delete-data,ads}/`: documents
- `app-ads.txt`: add the AdMob publisher line here
- `img/`: pixel art (AI generated, processed; keep the generation log in the game repo)
- `style.css`, `fonts/`: Press Start 2P and Space Grotesk (SIL OFL)
