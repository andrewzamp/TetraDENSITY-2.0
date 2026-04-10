<div align="center">

# TetraDENSITY 2.0

### A Global Database of Tetrapod Population Density Estimates

[![Explore the Database](https://img.shields.io/badge/🌍%20Explore%20the%20Database-Live%20App-2dd4c8?style=for-the-badge)](https://andrewzamp.github.io/TetraDENSITY/)
[![Paper](https://img.shields.io/badge/📄%20Read%20the%20Paper-GEB%202024-f0913a?style=for-the-badge)](https://doi.org/10.1111/geb.13929)

</div>

---

## 🌍 Explore the Interactive database

> **👉 [andrewzamp.github.io/TetraDENSITY](https://andrewzamp.github.io/TetraDENSITY/)**

Filter, map, and download population density records for over **3,900 tetrapod species** across the globe. No installation required, straight in your browser.

---

## What is TetraDENSITY?

**TetraDENSITY** is an open, continuously updated database of empirical population density estimates for the four tetrapod classes: amphibians, reptiles, birds, and mammals. It compiles density measurements from the primary scientific literature into a single, harmonised resource, enabling researchers to ask large-scale questions about how animal populations vary across species, habitats, and the planet.

<!-- IMAGE PLACEHOLDER — replace with a representative figure from the paper (e.g. global map of sampling locations) -->
<!-- ![Global sampling map](images/fig1_global_map.png) -->
> 📌 *Figure placeholder: global map of TetraDENSITY 2.0 sampling locations — add image here.*

---

## Database at a glance

| | |
|---|---|
| **Total density records** | 54,323 |
| **Species covered** | 3,992 |
| **Taxonomic classes** | 4 |
| **Families** | 343 |
| **Orders** | 65 |
| **Countries / territories** | 260 |
| **Literature sources** | 2,734 |

### Records by class

| Class | Records |
|---|---:|
| 🐦 Aves (birds) | 23,663 |
| 🦣 Mammalia (mammals) | 28,067 |
| 🦎 Reptilia (reptiles) | 1,832 |
| 🐸 Amphibia (amphibians) | 761 |

<!-- IMAGE PLACEHOLDER — replace with a bar/pie chart from the paper showing taxonomic coverage -->
<!-- ![Taxonomic coverage](images/fig2_taxonomic_coverage.png) -->
> 📊 *Figure placeholder: chart of taxonomic coverage by class — add image here.*

---

## Data

The database is available directly in this repository:

| File | Description |
|---|---|
| [`data/TetraDENSITY_2.0_Database.csv`](data/TetraDENSITY_2.0_Database.csv) | Main density records |
| [`data/TetraDENSITY_2.0_References.csv`](data/TetraDENSITY_2.0_References.csv) | Full bibliography |

### Key columns in the main database

| Column | Description |
|---|---|
| `Class`, `Order`, `Family` | Taxonomy |
| `Species_rep` | Accepted species name |
| `Year` | Year of the study |
| `X`, `Y` | Longitude / latitude of the sampling site |
| `Country`, `Site` | Location descriptors |
| `Sampling_area`, `Sampling_area_unit` | Area sampled |
| `Density`, `Density_unit` | Population density estimate and units |
| `SE`, `SD`, `CI90`, `CI95`, `CV` | Uncertainty metrics |
| `Method`, `Method2` | Sampling methodology |
| `Native` | Whether the population is native to the site |
| `Ref_N` | Reference key (links to References file) |

---

## How to Use

### In the browser
Open **[andrewzamp.github.io/TetraDENSITY](https://andrewzamp.github.io/TetraDENSITY/)**, filter by class, order, country or species name, explore the interactive map and charts, then download your filtered subset as a CSV.

## The paper

TetraDENSITY 2.0 is described in full in:

> **Santini, L., Benítez-López, A., Lumbierres, M., Maurenza, D., Pereira, H. M., & others (2024).** TetraDENSITY 2.0: a global database of population density estimates for tetrapods. *Global Ecology and Biogeography*, 33, e13929. [https://doi.org/10.1111/geb.13929](https://doi.org/10.1111/geb.13929)

The paper describes the data collection protocol, the geographic and phylogenetic coverage, and a series of macroecological analyses that illustrate the kinds of research questions the database enables.

<!-- IMAGE PLACEHOLDER — replace with a key results figure from the paper (e.g. density vs. body mass relationship) -->
<!-- ![Density vs body mass](images/fig3_density_bodymass.png) -->
> 📈 *Figure placeholder: key result figure from the paper (e.g. density–body mass scaling) — add image here.*

---

## Citation

If you use TetraDENSITY in your work, please cite the paper above. A BibTeX entry is provided below for convenience:

```bibtex
@article{Santini2024,
  title = {<scp>TetraDENSITY</scp> 2.0—A Database of Population Density Estimates in Tetrapods},
  volume = {33},
  ISSN = {1466-8238},
  url = {http://dx.doi.org/10.1111/geb.13929},
  DOI = {10.1111/geb.13929},
  number = {12},
  journal = {Global Ecology and Biogeography},
  publisher = {Wiley},
  author = {Santini,  L. and Mendez Angarita,  V. Y. and Karoulis,  C. and Fundarò,  D. and Pranzini,  N. and Vivaldi,  C. and Zhang,  T. and Zampetti,  A. and Gargano,  S. J. and Mirante,  D. and Paltrinieri,  L.},
  year = {2024},
  month = oct 
}
```

---

## Contributing

Spotted a missing study or an error in the data? Contributions are welcome! Please open an [issue](https://github.com/andrewzamp/TetraDENSITY/issues) or a pull request.

---

## Licence

The data are made available for academic and non-commercial use. Please refer to the published paper for the full terms of use.

---

<div align="center">
  <sub>Built and maintained by Andrea Zampetti and contributors · Powered by <a href="https://pages.github.com/">GitHub Pages</a></sub>
</div>
