# Lingmin Zhan — Personal Academic Homepage

Personal academic homepage for Lingmin Zhan, Algorithm Engineer at the Hangzhou Institute of Medicine, Chinese Academy of Sciences.

## Structure

```
├── index.html            # Main homepage
├── ensemblevar.html      # EnsembleVar sub-project page
├── vcf2peptides.html     # VCF2PEPTIDES sub-project page
└── element/
    ├── info.md           # Content reference
    ├── About.jpg         # Profile photo
    ├── Neovar.png        # NeoVariant project image
    ├── EnsembleVar.png   # EnsembleVar sub-project image
    ├── NeoVaxFinder.png  # NeoVaxFinder project image
    ├── VCF2PEPTIDES.png  # VCF2PEPTIDES sub-project image
    └── TranscriptionNet.png  # TranscriptionNet project image
```

## Pages

### Main Page (`index.html`)

Four sections with smooth-scroll navigation:

| Section | Content |
|---------|---------|
| **About** | Profile photo, name, degree, bio, animated research-interest tags (Deep Learning, Multi-Omics, Drug Discovery) |
| **Projects** | NeoVariant, NeoVaxFinder, TranscriptionNet — each with full-width images and descriptions |
| **Publication** | Three publications with journal names and author roles |
| **Contact** | Email link card |

**Navigation:** Fixed top bar with Projects dropdown menu linking directly to each project card.

### Sub-Project Pages

- **EnsembleVar** (`ensemblevar.html`) — Consensus-based silver standard variant calling pipeline. Back link returns to NeoVariant on main page.
- **VCF2PEPTIDES** (`vcf2peptides.html`) — VCF-to-peptide bioinformatics pipeline. Back link returns to NeoVaxFinder on main page.

## Design

- **Fonts:** Archivo (headings) + Space Grotesk (body)
- **Palette:** Monochrome gray scale + blue accent (`#2563EB`)
- **Style:** Minimal single-column layout, card-based content
- **Background:** Canvas-based particle animation with scientific motifs (DNA helix, molecular structures, hexagons, neural networks)

## Features

- Responsive layout (375px–1440px)
- `prefers-reduced-motion` support (disables animations)
- Keyboard-accessible navigation
- Lazy-loaded images
- CSS custom properties for consistent theming
