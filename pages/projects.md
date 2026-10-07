---
title: Projects
description: Geospatial, remote sensing, and data projects by Sokeang Hoeun.
keywords:
  - Projects
  - Remote Sensing
  - Dashboards
  - Agriculture
  - Health
---

# Projects

Selected projects in agriculture, public health, and environmental monitoring.

---

## Agriculture & Food Security

::::{grid} 1 2 3 3

:::{card} Digital Rice Monitoring Platform
**FAO Cambodia, 2025--present**
+++
Tools that combine geospatial, remote sensing, and statistical data to monitor rice cultivation and estimate yields, with dashboards for policy makers.
:::

:::{card} Coffee Suitability Mapping
**Kofi Co., Ltd, 2024**
+++
Remote sensing and land-use analysis in Mondulkiri to identify and estimate areas suitable for coffee plantation.
:::

:::{card} Precision Agriculture Mapping
**SMWaypoint Co., Ltd, 2017--2019**
+++
Satellite and drone image analysis to quantify crop health and greenness, with plantation inventory surveys.
:::

::::

---

## Health & Environment

::::{grid} 1 2 3 3

:::{card} Dengue Surveillance Dashboard
**IRD, Phnom Penh**
+++
Interactive dashboard to monitor and visualise dengue case trends for surveillance and response.
:::

:::{card} Mosquito Habitat Suitability
:link: #featured-map-mosquito-sdm
**IRD Espace-Dev, 2024--2025**
+++
Random forest ensemble models predicting the probability of presence of *Aedes aegypti*, *Aedes albopictus* and *Culex quinquefasciatus* across Cambodia.
:::

:::{card} Land Cover for Dengue Vector Ecology
:link: #featured-map-phnom-penh
**IRD, Phnom Penh**
+++
Land use and land cover map of Phnom Penh from SPOT-7 imagery using object-based image analysis, to study the environmental preferences of the dengue vectors *Aedes aegypti* and *Aedes albopictus*.
:::

:::{card} Land Cover for Melioidosis and Leptospirosis
:link: #featured-map-koh-thum
**IRD Espace-Dev, Koh Thum District, 2019**
+++
Nine-class land use and land cover map from Pléiades imagery using object-based image analysis, to study the ecology of melioidosis (*Burkholderia pseudomallei*) and leptospirosis (*Leptospira*).
:::

:::{card} Land Cover for Malaria Elimination
:link: #featured-map-kayin
**EASIMES project, Kayin State, Myanmar**
+++
Ten-class land use and land cover map from Sentinel-2 imagery (2019--2020) using object-based image analysis, to characterise malaria transmission landscapes.
:::

::::

## Featured Maps

(featured-map-mosquito-sdm)=
### Mosquito Habitat Suitability in Cambodia

Results of Sokeang's M.Sc. (M2) internship at IRD Espace-Dev (2024--2025). Each map shows the average probability of presence predicted by a random forest ensemble model, from blue (0, low) to red (1, high).

::::{tab-set}

:::{tab-item} Aedes aegypti
```{image} images/sdm_aedes_aegypti.jpg
:alt: Map of Cambodia showing the average predicted probability of presence of Aedes aegypti
:width: 100%
```
:::

:::{tab-item} Aedes albopictus
```{image} images/sdm_aedes_albopictus.jpg
:alt: Map of Cambodia showing the average predicted probability of presence of Aedes albopictus
:width: 100%
```
:::

:::{tab-item} Culex quinquefasciatus
```{image} images/sdm_culex_quinquefasciatus.jpg
:alt: Map of Cambodia showing the average predicted probability of presence of Culex quinquefasciatus
:width: 100%
```
:::

::::

(featured-map-koh-thum)=
### Land Cover of Koh Thum District

:::{figure} images/lulc_kohthum_pleiades.jpg
:alt: Land cover map of Koh Thum District, Cambodia, 27 January 2019, showing villages along the river, rice fields, orchards, flooded fields, wetlands and water
:width: 75%

Nine-class land use and land cover map of Koh Thum District, Cambodia (27 January 2019): village, village vegetation, orchard, dense rice field, sparse rice field, flooded field, bare field, wetland and water. Classified from Pléiades imagery (© CNES 2019, distribution Airbus DS, provided through DINAMIS GEOSUD) using object-based image analysis in eCognition, to study the ecology of melioidosis (*Burkholderia pseudomallei*) and leptospirosis (*Leptospira*). Produced by Sokeang Hoeun, IRD Espace-Dev.
:::

(featured-map-phnom-penh)=
### Land Cover of Phnom Penh

:::{figure} images/lulc_phnompenh_spot7.jpg
:alt: Land use and land cover map of Phnom Penh in nine classes, with pie charts of Aedes aegypti and Aedes albopictus counts at 40 pagodas
:width: 100%

Nine-class land use and land cover map of Phnom Penh, classified from a SPOT-7 image (11 December 2019; 1.5 m panchromatic, 6 m multispectral) using object-based image analysis (overall accuracy 90%, Kappa 0.88). Pie charts show *Aedes aegypti* and *Aedes albopictus* trapped at 40 pagodas. Published in Herbreteau, Maquart, **Hoeun**, et al. (2025), *PLOS Neglected Tropical Diseases* 19(10): e0013667, [doi:10.1371/journal.pntd.0013667](https://doi.org/10.1371/journal.pntd.0013667) (Fig 6, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
:::

(featured-map-kayin)=
### Malaria Transmission Landscapes in Kayin State, Myanmar

:::{figure} images/landscapes_kayin_sentinel2.jpg
:alt: Map of landscape types across the METF region of Kayin State, Myanmar, from dense forest to cropland, wetland and built-up areas
:width: 60%

Landscape types across the Malaria Elimination Task Force (METF) region of Kayin State, Myanmar, mapped on a 2-km hexagonal grid. They were derived from a ten-class land use and land cover map (dense forest, sparse forest, plantation, cropland, grass/shrubland, bare soil, wetland, road, water, built-up), classified from Sentinel-2 images (2019--2020) using object-based image analysis in eCognition and validated with 600 field and photo-interpreted points (Cohen's Kappa 0.73). Published in Legendre, Girond, Herbreteau, **Hoeun**, et al. (2023), *Parasites & Vectors* 16: 324, [doi:10.1186/s13071-023-05915-w](https://doi.org/10.1186/s13071-023-05915-w) (Fig 3B, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); cropped from the original figure).
:::
