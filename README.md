# Nourish and Thrive Foundation — Website
 
Source code for the Nourish and Thrive Foundation's one-page website. Plain HTML, CSS, and JavaScript — no frameworks, no build step.
 
## What's here
 
```
.
├── index.html        # The entire site — hero, mission, programs, contact
└── assets/
    ├── logo.png       # Foundation logo (PNG, broad browser support)
    └── logo.webp      # Foundation logo (WebP, smaller file size)
```
 
## Viewing it locally
 
No build tools needed — just open `index.html` in a browser. Or serve the folder so relative paths behave exactly like they will in production:
 
```bash
python3 -m http.server 8000
```
 
Then visit `http://localhost:8000`.
 
## Deployment
 
This site is hosted on **GitHub Pages**, with a custom domain pointed here from GoDaddy DNS. Pushing or uploading changes to `main` redeploys the live site automatically — usually within a minute.
 
## Editing content
 
Everything lives in `index.html` — copy, layout, and styling in one file. Brand colors and fonts are set as CSS variables near the top of the `<style>` block, so the whole palette or type system can be updated from one place.
 
## Contact
 
Questions about the Foundation: **nourishthrive.fdn@gmail.com**
 
## License
 
The code in this repository (the HTML, CSS, and JavaScript that make up the site's structure and functionality) is available under the [MIT License](LICENSE) — feel free to reuse the structure or techniques for your own project.
 
**This license covers the code only.** It does not extend to, and no rights are granted to:
 
- The **Nourish and Thrive Foundation** name and any related trade names
- The Foundation's **logo, seal, and visual brand identity** — including its color palette, typography system, and iconography
- The **written content** on this site, including the mission and vision statements, program descriptions, and all other copy
These remain the sole property of the Nourish and Thrive Foundation. They may not be copied, reused, or adapted for another organization or project without the Foundation's prior written permission.
