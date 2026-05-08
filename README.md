# CUR_Res_FRDR_Presentation

This repository contains the Quarto presentation materials for the introduction to the Federated Research Data Repository (FRDR) / Dépôt fédéré de données de recherche (DFDR) for the ACFAS 2026 congress. 

The presentation has been adapted to Quarto format from an original PowerPoint slide deck, focusing on a clean, bilingual-capable design (primary language: French) using the `revealjs` format.

## 📺 Live Presentation
**[Click here to view the live presentation](https://Alliance-RDM-GDR.github.io/CUR_Res_FRDR_Presentation/Acfas_FRDR_2026.html)**

## Contents
- **FRDR_Acfas/**: Contains the main presentation file (`Acfas_FRDR_2026.qmd`), custom CSS styles, and institutional logos.
- **Sample/**: Contains the original RDM presentation Quarto template used as a format base.
- **extract_pptx.py**: A python script used to extract raw text content from the original `.pptx` presentation.
- **2026-05-08_FRDR_Acfas.pptx**: Original PowerPoint deck containing the source content.

## How to view
You can render the presentation by opening the `.qmd` file in RStudio or VS Code and using the **Render** button, or by running the following command in the terminal inside the presentation folder:

```bash
quarto render Acfas_FRDR_2026.qmd
```
