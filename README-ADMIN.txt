TEXLAB KONVEKSI V8 — WEBSITE + ADMIN CONTENT MANAGER

Website pages:
- index.html: Beranda
- katalog.html: Katalog (data-driven)
- portofolio.html: Portofolio (data-driven with image viewer)
- materials.html and materials-*.html: Materials
- testimoni.html: Testimoni (data-driven)
- admin.html: Admin untuk menambah, mengubah, menghapus katalog, portofolio, testimoni
- data/catalog.json
- data/portfolio.json
- data/testimonials.json

INSTALL:
1. Extract the ZIP.
2. Upload ALL files and folders to the ROOT of the existing GitHub repository, replacing same-named files.
3. Commit changes and wait for the website hosting deploy to finish.
4. Open https://YOUR-WEBSITE-DOMAIN/admin.html (or the GitHub Pages URL + /admin.html).

FIRST ADMIN SETUP:
- Create a Fine-grained personal access token in GitHub.
- Restrict it to only the Texlab repository.
- Grant Repository permissions: Contents = Read and write.
- In admin.html, enter owner/repo (e.g. yulio0507/Texlab_konveksi), branch main, and the token.
- Click "Hubungkan & muat konten".
- The token is kept in page memory only; it is not written into site files. Close the admin tab after use. Do not share the token.
- Add/edit/delete items in Katalog, Portofolio, and Testimoni. Upload an image if desired. Save. GitHub will commit changes and the static host will redeploy.

NOTES:
- GitHub Pages and most static hosts publish admin.html publicly, but editing requires a token with repository write access.
- Anyone who has both access to the admin page and your token can change site content. Keep the token private and revoke it in GitHub if exposed.
- Image files uploaded from admin are stored in assets/admin/.
- Testimonials should be genuine and published with customer permission.
- Product material descriptions and color swatches are general references; confirm availability with suppliers.
