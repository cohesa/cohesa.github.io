# Scott A. Cohen Conference Poster Site

GitHub Pages source for `https://cohesa.github.io/`.

## Repository structure

```text
cohesa.github.io/
├── index.html
├── styles.css
└── posters/
    ├── Antifungal_COM26.pdf
    ├── Antifungal_FLACP26.pdf
    ├── Candida_IDWeek25.pdf
    ├── MRSA_EPI23.pdf
    ├── MRSA_FLACP23.pdf
    ├── MRSA_PHHP23.pdf
    ├── OldMRSA_EPI19.pdf
    ├── OutbreakDetection_EPI25.pdf
    ├── OutbreakDetection_FLACP26.pdf
    ├── OutbreakDetection_IDWeek25.pdf
    ├── PM25_COM20.pdf
    ├── PM25_PHHP20.pdf
    ├── PM25_SAEM20.pdf
    ├── PredictAMR_IDWeek24.pdf
    ├── SAE_COM19.pdf
    ├── SAE_SAEM19.pdf
    ├── SpatialOHCA_ACEP18.pdf
    ├── SpatialOHCA_PHHP19.pdf
    ├── Target_AMIA24.pdf
    ├── Target_JM24.pdf
    ├── Target_PHHP24.pdf
    └── Troponin_ESC21.pdf
```

## Publish

1. Create a public GitHub repository named `cohesa.github.io`.
2. Upload `index.html` and `styles.css` to the repository root.
3. Create a folder named `posters` and upload all 22 PDFs with filenames unchanged.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select `main` and `/(root)`, then save.
7. Verify the site and every PDF link in a private browser window.

## ERAS links

Use the direct PDF URL in each Poster URL field:

```text
https://cohesa.github.io/posters/FILENAME.pdf
```

Example:

```text
https://cohesa.github.io/posters/Candida_IDWeek25.pdf
```

## Metadata verification

Titles, meetings, author lists, and awards were populated from the August 2026 CV. Before publishing, compare each card against the corresponding PDF. In particular, verify the complete author list for `OldMRSA_EPI19.pdf` because the CV lists the presentation without authors.
