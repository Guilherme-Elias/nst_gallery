# NST Gallery

**Generation, Visualisation and Structured Qualitative Evaluation of Neural Style Transfer**

**Module:** CM3070 Computer Science Final Project  
**Programme:** BSc Computer Science  
**Institution:** Goldsmiths, University of London  
**Student:** Guilherme Elias Marinho  
**Student Number:** 220522652  
**Project Template:** CM3015 Machine Learning and Neural Networks — 3.1 Project Idea 1: Neural Style Transfer  
**Date:** September 2026

---

## Project Overview

This repository contains the datasets, generated artifacts, evaluation results, and report figures for the **NST Gallery** final project.

The project investigates Neural Style Transfer through three connected activities:

1. generation of stylised images;
2. systematic presentation through a digital gallery;
3. structured qualitative curation and analysis.

The final Gallery contains every combination of **10 content images** and **9 style images**, producing **90 stylised outputs**.

## Main Artifacts

- [`nst_gallery.pdf`](./nst_gallery.pdf) — 90-page digital Gallery.
- [`gallery.zip`](./gallery.zip) — archive containing the 90 generated stylised images.
- [`nst_gallery_curation.pdf`](./nst_gallery_curation.pdf) — visual record of the structured curation.
- [`nst_gallery_curation.csv`](./nst_gallery_curation.csv) — machine-readable curation results.
- [`images/`](./images/) — source content and style images.
- [`figures/`](./figures/) — figures used in the final project report.
- [`structured-boolean-evaluation-rubric.pdf`](./structured-boolean-evaluation-rubric.pdf) — complete evaluation instrument containing the 11 Boolean criteria used during Gallery curation.

## Workflow

`nst_gallery.ipynb` generates the complete set of 90 content-style combinations and produces:

- `nst_gallery.pdf`
- `gallery.zip`

`nst_gallery_curation.ipynb` consumes `gallery.zip`, presents the generated images for structured evaluation, and produces:

- `nst_gallery_curation.pdf`
- `nst_gallery_curation.csv`

The resulting CSV can subsequently be analysed using `nst_curation_analysis.ipynb`.

## Image Sources

| File | Source |
|---|---|
| `beige-building.jpg` | [Unsplash](https://unsplash.com/photos/beige-concrete-building-iVmUXothgGY) |
| `balloon-contest.jpg` | [Unsplash](https://unsplash.com/photos/hot-air-balloon-contest-t7YycgAoVSw) |
| `white-houses.jpg` | [Unsplash](https://unsplash.com/photos/aerial-photography-of-white-houses-ovgRb5WLWMQ) |
| `elephant.jpg` | [Unsplash](https://unsplash.com/photos/a-large-elephant-walking-across-a-lush-green-field-U17K57Kwi0U) |
| `windows.jpg` | [Unsplash](https://unsplash.com/photos/a-very-tall-building-with-lots-of-windows-rx5j7gNQebo) |
| `taj-mahal.jpg` | [Unsplash](https://unsplash.com/photos/taj-mahal-india-iWMfiInivp4) |
| `big-ben.jpg` | [Unsplash](https://unsplash.com/photos/big-ben-london-iXqTqC-f6jI) |
| `river-near-mountains.jpg` | [Unsplash](https://unsplash.com/photos/river-near-mountains-KiRlN3jjVNU) |
| `green-mountains.jpg` | [Unsplash](https://unsplash.com/photos/birds-eye-view-photograph-of-green-mountains-01_igFr7hd4) |
| `seashore.jpg` | [Unsplash](https://unsplash.com/photos/landscape-photography-of-seashore-under-cumulus-clouds-U6t80TWJ1DM) |
| `stoke-by-nayland.jpg` | [Art Institute of Chicago](https://www.artic.edu/artworks/4758/stoke-by-nayland) |
| `painting-with-green-center.jpg` | [Art Institute of Chicago](https://www.artic.edu/artworks/8987/painting-with-green-center) |
| `cliff-walk-at-pourville.jpg` | [Art Institute of Chicago](https://www.artic.edu/artworks/14620/cliff-walk-at-pourville) |
| `valley-of-aosta.jpg` | [Art Institute of Chicago](https://www.artic.edu/artworks/109938/valley-of-aosta-snowstorm-avalanche-and-thunderstorm) |
| `boogie-woogie.jpg` | [WikiArt](https://www.wikiart.org/en/piet-mondrian/broadway-boogie-woogie-1943) |
| `mont-sainte-victoire.jpg` | [WikiArt](https://www.wikiart.org/en/paul-cezanne/mont-sainte-victoire-3) |
| `the-wanderer.jpg` | [WikiArt](https://www.wikiart.org/en/caspar-david-friedrich/the-wanderer-above-the-sea-of-fog) |
| `trees-by-the-water.jpg` | [WikiArt](https://www.wikiart.org/en/paul-cezanne/trees-by-the-water-1900) |
| `view-of-segovia.jpg` | [WikiArt](https://www.wikiart.org/en/joaqu-n-sorolla/view-of-segovia-1906) |
