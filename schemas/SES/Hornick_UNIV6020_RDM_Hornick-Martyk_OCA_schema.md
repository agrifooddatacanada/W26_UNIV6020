---
layout: default  
title: Hayden Hornick-Martyk
parent: School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: UNIV6020_RDM_Hornick-Martyk  
**Description**: This research is examining the effects of long-term cover cropping on soil microbial communities and sweet corn microbial recruitment during short-term drought. This will be used to determine if either the management practice and/or potential microbial changes offer the sweet corn any type of yield protection.  
**Classification**: RDF401  
**Author**: Hayden Hornick-Martyk  
**Author Email**: hhornick@uoguelph.ca  
**Schema package SAID**: EKgAVme7Y0IVONvwzvCahA88ztl1AWzoqLfPSrPaOd7F  

[Download Schema](Hornick_UNIV6020_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| block | Field block | Field is split into blocks to minimize the effects of spatial variability. Block number represents which block this replicate/plot is contained in. |
| plot | Plot number | Describes the plot that a replicate was grown in. |
| mositure_treatment | Moisture treatment | Describes whether a plot was in the drought or ambient conditions treatment |
| cc_treatment | Cover crop treatment | Describes which cover crop treatment is used on the plot prior to the main crops |
| soil_ww | Soil wet weight (g) | Soil weight (grams) of unaltered soil for the field site |
| tin_w | Tin/container weight (g) | Weight of the container (grams) that wet soil is being dried in. Subtracted from dry soil measurement. |
| soil_dw | Soil dry weight (g) | Soil weight (grams) of dried soil minus the container weight. |
| soil_grav_moist | Soil gravimetric mositure | Gravimetric moisture content of the soil expressed as a percentage. |
| cob_num | Number of sweet corn cobs | Number of sweet corn cobs harvested from two 4 m rows of sweet corn. |
| yield | Sweet corn yield (Mt/Ha) | Sweet corn yield (Mt/Ha). The weight of sweet corn harvested from two 4 m rows was extrapolated. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | UNIV6020_RDM_Hornick-Martyk | This research is examining the effects of long-term cover cropping on soil microbial communities and sweet corn microbial recruitment during short-term drought. This will be used to determine if either the management practice and/or potential microbial changes offer the sweet corn any type of yield protection. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| block | true |  | Numeric |  |
| plot | true |  | Numeric |  |
| mositure_treatment | true |  | Text |  |
| cc_treatment | true |  | Text |  |
| soil_ww | true |  | Numeric |  |
| tin_w | true |  | Numeric |  |
| soil_dw | true |  | Numeric |  |
| soil_grav_moist | true |  | Numeric |  |
| cob_num | true |  | Numeric |  |
| yield | true |  | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| block | Field block | Field is split into blocks to minimize the effects of spatial variability. Block number represents which block this replicate/plot is contained in. | Not a list |
| plot | Plot number | Describes the plot that a replicate was grown in. | Not a list |
| mositure_treatment | Moisture treatment | Describes whether a plot was in the drought or ambient conditions treatment | Not a list |
| cc_treatment | Cover crop treatment | Describes which cover crop treatment is used on the plot prior to the main crops | Not a list |
| soil_ww | Soil wet weight (g) | Soil weight (grams) of unaltered soil for the field site | Not a list |
| tin_w | Tin/container weight (g) | Weight of the container (grams) that wet soil is being dried in. Subtracted from dry soil measurement. | Not a list |
| soil_dw | Soil dry weight (g) | Soil weight (grams) of dried soil minus the container weight. | Not a list |
| soil_grav_moist | Soil gravimetric mositure | Gravimetric moisture content of the soil expressed as a percentage. | Not a list |
| cob_num | Number of sweet corn cobs | Number of sweet corn cobs harvested from two 4 m rows of sweet corn. | Not a list |
| yield | Sweet corn yield (Mt/Ha) | Sweet corn yield (Mt/Ha). The weight of sweet corn harvested from two 4 m rows was extrapolated. | Not a list |

## Schema SAIDs

**Capture base**: EB-JwWb_iaUaXc8AZMpvtaeGMyTZ9Qn7QGfeAQ7hCBPx

**Bundle**: EJIUt_BgMrJkeUrTrRDv_t324AG7UkNWMhpVZzHuhAVG

**Package**: EKgAVme7Y0IVONvwzvCahA88ztl1AWzoqLfPSrPaOd7F

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EHQbpHcK8pZQQX8oec3Hrw3ws7ew9b3yTU4nnUN1-SCB | spec/overlays/information/1.1 |
| label (eng) | EEMMlgTfWW6DSSwej9AyKOgWM741o2T7k_xEfheasJoO | spec/overlays/label/1.1 |
| meta (eng) | EHzIkkQHxvRa5PuvfRhQRGxP7m8Sc1y3FiFMqr5OKYEh | spec/overlays/meta/1.1 |
| ordering | EB-eCpJTMKVqnMGYwewwMOET_OmI8BXlDlCEqZRh3L2x | community/overlays/adc/ordering/1.0 |
| sensitive | EKISQP9SIyG3mdqByGP40foroG-Q3GYnaumBB9ILma2T | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:38:01

