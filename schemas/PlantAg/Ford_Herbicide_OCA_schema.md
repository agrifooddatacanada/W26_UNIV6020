---
layout: default  
title: Cassandra Ford - Herbicide and Tillage Efficacy - Fall 2025 Winter Wheat  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Herbicide and Tillage Efficacy - Fall 2025 Winter Wheat  
**Description**: Data collection detailing the efficacy of alternative tillage and herbicide treatments to control volunteer winter wheat post-harvest in the absence of glyphosate use.  
**Classification**: RDF401  
**Author**: Cassandra Ford  
**Author Email**: cford04@uoguelph.ca  
**Schema package SAID**: EHZlwCcMK8arnwGd9LjSxmFVYfUne31r526ZjrtAr6J2 

[Download Schema](Ford_Herbicide_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| plot | Plot | Plots in Trial |
| treatment | Treatment | Treatment used in each plot |
| weed_density_0.5_m2 | Weed Density 0.5m2 | Amount of weeds counted in 0.5m2 quadrant in each plot. Quadrant is randomly placed in each plot, and then a white flag is placed in the middle for future evaluations. |
| weed_density_1_m2 | Weed Density 1m2 | Amount of weeds counted in 0.5m2 quadrant in each plot. Quadrant is randomly placed in each plot, and then a white flag is placed in the middle for future evaluations. |
| species_in_quadrant | Species in Quadrant | List of species found in 0.5m2 quadrant and 1m2 quadrant and is listed in common name and latin name. |
| efficacy | Efficacy | Percentage efficacy of weed control found in each plot. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Herbicide and Tillage Efficacy - Fall 2025 Winter Wheat | Data collection detailing the efficacy of alternative tillage and herbicide treatments to control volunteer winter wheat post-harvest in the absence of glyphosate use. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| plot | false | 1-6 | Numeric |  |
| treatment | false |  | Text |  |
| weed_density_0.5_m2 | false |  | Numeric |  |
| weed_density_1_m2 | false |  | Text |  |
| species_in_quadrant | false |  | Text |  |
| efficacy | false | % | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| plot | Plot | Plots in Trial | Not a list |
| treatment | Treatment | Treatment used in each plot | Not a list |
| weed_density_0.5_m2 | Weed Density 0.5m2 | Amount of weeds counted in 0.5m2 quadrant in each plot. Quadrant is randomly placed in each plot, and then a white flag is placed in the middle for future evaluations. | Not a list |
| weed_density_1_m2 | Weed Density 1m2 | Amount of weeds counted in 0.5m2 quadrant in each plot. Quadrant is randomly placed in each plot, and then a white flag is placed in the middle for future evaluations. | Not a list |
| species_in_quadrant | Species in Quadrant | List of species found in 0.5m2 quadrant and 1m2 quadrant and is listed in common name and latin name. | Not a list |
| efficacy | Efficacy | Percentage efficacy of weed control found in each plot. | Not a list |

## Schema SAIDs

**Capture base**: ELWl8SjJiLZvWeNPon4JsDg0M4XhO1rBsl4pU6-dX2ED

**Bundle**: EEndkSxMJel2sZZazPMsNfM9xNHLvWZ0kKsHuo_MQ4qI

**Package**: EHZlwCcMK8arnwGd9LjSxmFVYfUne31r526ZjrtAr6J2

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EPqDH5NFZXVJs9TjrgjeHBq8wxj79wMOvhN0Okh8q0kc | spec/overlays/information/1.1 |
| label (eng) | ELyVNAxLfJou5BEEG2zuqeYAK7VyBofAMUyfw59SVSJv | spec/overlays/label/1.1 |
| meta (eng) | EIGP27oAckrpi6ebQJbCSlejyo44XFldJA6bzZfQE-e2 | spec/overlays/meta/1.1 |
| unit | EGdXfWkiOGVODdI1650yRQ9zSVFC3Bimcj84umzFM-kO | spec/overlays/unit/1.1 |
| ordering | EO0yVCtu4CkO6jekNXi4X4W7LsJ5eGmCoK6gye0KOcWk | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-19 10:28:48

