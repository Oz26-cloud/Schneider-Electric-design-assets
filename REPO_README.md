# Schneider Electric Design Assets

Brand assets and documentation for the Schneider Electric PowerPoint design system, used by the TAGWW team and the Claude PowerPoint skill.

The repository is public so the skill can fetch files with plain links.

## Folders

| Folder | Contents |
|---|---|
| `01_FOUNDATION_DOCUMENTATION/` | Brand specs (colors, typography, logo, layout, CTA, gradients, ovals, photography, sketches, icons, infographics, illustrations, tagline) and design tokens (`03_Design_Tokens.json`, `04_Design_Tokens.css`) |
| `02_WORKFLOW_LAYER/` | How to build a deck: 8-step process, template choice, slide-by-slide guides, common questions and mistakes, quality checklist |
| `03_BRAND_VISUAL_REFERENCES/` | 12 brand guideline PDFs |
| `04_ASSETS/` | Production assets (see below) |

Files in `04_ASSETS/`:

| Folder | Contents |
|---|---|
| `06_Typography_Fonts/` | 18 Poppins font files (9 weights, upright and italic) |
| `07_Logo/` | 12 logo files (Black, Green, White in 1x to 4x) |
| `08_Layout_Grid/` | 4 grid reference files |
| `09_CTA/` | 1 CTA button file |
| `10_Gradients/` | 33 gradient backgrounds |
| `11_Ovals/` | 12 oval shapes |
| `13_Sketches/` | 11 tech sketch overlays |
| `14_Icons/` | 571 pictograms (series A to U, plus K) |
| `16_Illustrations/` | 196 flat illustrations |
| `17_PowerPoint_Templates/` | 4 master templates (white, dark green, light green, gradient) |
| `18_Tagline/` | Tagline asset |

## Using the files

Every file can be fetched with a plain link. Replace `<folder>` and `<file name>` with the actual names. Spaces in file names become `%20`.

```
https://raw.githubusercontent.com/Oz26-cloud/Schneider-Electric-design-assets/main/04_ASSETS/<folder>/<file name>
```

Example:

```
https://raw.githubusercontent.com/Oz26-cloud/Schneider-Electric-design-assets/main/04_ASSETS/16_Illustrations/IllustrationsArtboard%201.png
```

## Skill

`SKILL.md` is the entry point for the Claude skill. It lists the rules, the workflow, and where each document and asset is. `README.md` in the root is the skill's own package guide.

## Changes

Files are on `main`. Each change is a commit, so earlier versions can be restored from history.
