# RED ROLL website

Static site (HTML + GSAP). No build step.

## Struktura
- `index.html` – faqja
- `assets/` – fotot dhe logoja

## Lidhjet sociale / Wolt
Hape `index.html`, gjej `var SOCIAL={...}` dhe vendos URL-të reale, p.sh.
`instagram:"https://www.instagram.com/EMRI/"`. Butonat shfaqen vetë.

## Publikimi me GitHub + Vercel
1. Krijo repo në github.com (New repository, p.sh. `redroll-website`).
2. Ngarko skedarët (Add file > Upload files) ose me terminal:
   ```
   git init
   git add .
   git commit -m "RED ROLL website"
   git branch -M main
   git remote add origin https://github.com/EMRI/redroll-website.git
   git push -u origin main
   ```
3. Hap vercel.com > Add New > Project > Import repo-n.
4. Framework Preset: **Other**. Build command dhe Output Directory lëri bosh. Deploy.
5. Çdo `git push` e ri publikon automatikisht. Domain: Project > Settings > Domains.
