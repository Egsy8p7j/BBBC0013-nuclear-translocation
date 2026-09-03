# BBBC0013-nuclear-translocation
Image analysis of BBBC0013 Human U2OS cells cytoplasm–nucleus translocation

# Automated Quantification of Nuclear Translocation

## Background
This 96-well plate has images of cytoplasm to nucleus translocation of the Forkhead (FKHR-EGFP) fusion protein in stably transfected human osteosarcoma cells, U2OS. In proliferating cells, FKHR is localized in the cytoplasm. Even without stimulation, Forkhead is constantly moving into the nucleus, but is transported out again by export proteins. Upon inhibition of nuclear export, FKHR accumulates in the nucleus. In this assay, export is inhibited by blocking PI3 kinase / PKB signaling by incubating cells for 1 h with Wortmannin or with the compound LY294002. Both drugs are considered positive controls in the assay. Nuclei are stained with DRAQ, a DNA stain.

## Research question

Can fluorescence microscopy images be used to automatically quantify treatment-induced nuclear translocation at the single-cell level?

## Dataset

The project uses the BBBC013 dataset from the Broad Bioimage Benchmark Collection.

## Analysis plan

1. Explore fluorescence microscopy images
2. Segment cell nuclei
3. Extract nuclear and cytoplasmic fluorescence intensity
4. Calculate nuclear-to-cytoplasmic fluorescence ratios
5. Compare treatment conditions
6. Analyse dose-response relationships

## Project structure

- `notebooks/` – exploratory analysis and image processing
- `src/` – reusable Python functions
- `figures/` – figures generated during analysis
- `report/` – final project report
- `data/` – local raw data directory
