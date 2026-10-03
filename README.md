# Quarto Research Site v0.3.1

Final homepage refinements: valid Quarto title metadata, homepage TOC disabled, standard title block hidden only on the homepage, wider hero layout, and retained professional headshot.

# Quarto Research Site v0.3

This is an update package for the `HL_Blog` Quarto project.

## Important

Keep your existing `HL_Blog.Rproj`, `.Rproj.user`, `Branch_DS`, `LinkedIn Archive`, and any other private/source folders in place.

## Install v0.3

1. Close the running Quarto preview (press `Ctrl+C` in the RStudio Terminal if needed).
2. Extract this ZIP.
3. Copy the contents of the `quarto-site-v0.3` folder into your existing `HL_Blog` folder.
4. When Windows asks, choose **Replace the files in the destination** for the website files.
5. Do **not** delete your existing `HL_Blog.Rproj`.
6. Open `HL_Blog.Rproj` and run:

```r
system("quarto preview")
```

## v0.3 changes

- Redesigned homepage with a research-oriented hero section.
- Research-area cards instead of simple bullet lists.
- Prominent Models & Software section.
- Featured DS-01 article with a research figure preview.
- Removed public development/site-status text.
- Redesigned DSteele landing page around the DSteele article series.
- Technical Articles listing changed to a grid layout.
- Improved typography, spacing, responsive layout, cards, and dark-mode behavior.
- Light web-specific polish added to DS-01 without changing the approved article body.

## Current article status

- DS-01: final content; integrated into the site.
- DS-02: next planned article, focused on the detailed mathematical formulation of DSteele.


## v0.3 changes

- Added Hyungsuk S. Lee headshot to the homepage hero.
- Removed the duplicate Quarto page title above the homepage hero.
- Converted the hero to a responsive two-column layout with portrait.
- Preserved the v0.2 research cards, model cards, DSteele series page, and DS-01 article.


## v0.4.2 — DS-02 integration

- Adds finalized DS-02 as `posts/dsteele-mathematical-formulation/index.qmd`.
- Preserves the finalized v2.1 manuscript text and equation sequence; the Quarto work is presentation/integration rather than a rewrite.
- Converts legacy Word equation graphics (WMF/EMF) to browser-safe PNG files.
- Adds the handwritten derivation photographs to the web article.
- Links DS-02 from the DSteele article-series page.
- Promotes DS-02 to the homepage Latest Technical Article.
- The Technical Articles listing discovers DS-02 automatically from its article metadata.


## v0.4.2 changes
- Traffic Speed Deflectometer (TSD) terminology standardized in site navigation/research labels.
- Latest Technical Article moved above Featured Research on the homepage.
- TSD research page now includes DS-01 and DS-02.
- DS-02 equation graphics tightly cropped and styled for readable web display while retaining manuscript numbering.

### v0.4.2 DS-02 refinement
- Standardized the visual scale of the compact Equation (5) relative to neighboring equations.
- Centered standalone DS-02 figures and captions.
- Kept equation numbers locked to their equation rows.

## GitHub Pages deployment note

This working project intentionally keeps private/local research materials alongside the public Quarto source. The `.gitignore` file excludes `LinkedIn Archive/`, `Branch_DS/`, RStudio/Quarto working state, rendered `_site/` output, and internal planning documents from Git tracking. These folders can remain on the local machine while the public repository contains only the website source and public assets.

Before the first GitHub Pages deployment, set `website.site-url` in `_quarto.yml` to the final GitHub Pages URL after the repository name is chosen.
