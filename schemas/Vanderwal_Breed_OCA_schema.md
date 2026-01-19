---
layout: default  
title: Carmen Vanderwal - Breed Comparison Gut Permeability Data  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Breed Comparison Gut Permeability Data  
**Description**: Gut permeability was assessed in purebred Holstein and Angus–Holstein crossbred bull calves at 24 hours of life and on day 35 of life. Calves were randomly assigned to receive either a low or high colostrum allowance at birth, differing in IgG intake per kilogram of body weight. Gut permeability was evaluated using an oral chromium-EDTA marker administered prior to a milk meal. Serial blood samples were collected over 12 hours post-dosing to quantify plasma chromium concentrations as an indicator of intestinal permeability.  
**Classification**: RDF402  
**Author**: Carmen Vanderwal  
**Author Email**: cvande10@uoguelph.ca  
**Schema package SAID**: EBzyEbYEf8Q1WZ-5YT-gaQLcsR1CX0u7WtGhB9585gnE

[Download Schema](Vanderwal_Breed_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Feedlot_ID | Feedlot_ID | Number on the ear tag of each calf for identification |
| Colostrum | Colostrum | Calves were either fed a high volume of colostrum (5 g IgG/kg body weight per feeding) or a low volume (2.5 g IgG/kg body weight per feeding) |
| Breed | Breed | Purebred Holstein bull calf, or crossbred Angus-Holstein bull calf |
| Birth_Date | Birth_Date | Date of birth for each calf |
| Birth_BW | Birth_BW | Body weight of each calf, measured on the day of birth |
| Day | Day | Days of life when major sampling timepoints occur |
| Hour | Hour | Hours prior to, or after dosing with the chromium-EDTA marker for gut permeability |
| Cr_ppb | Cr_ppb | Concentration of chromium in parts per billion (ppb) measured in blood plasma |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Breed Comparison Gut Permeability Data | Gut permeability was assessed in purebred Holstein and Angus–Holstein crossbred bull calves at 24 hours of life and on day 35 of life. Calves were randomly assigned to receive either a low or high colostrum allowance at birth, differing in IgG intake per kilogram of body weight. Gut permeability was evaluated using an oral chromium-EDTA marker administered prior to a milk meal. Serial blood samples were collected over 12 hours post-dosing to quantify plasma chromium concentrations as an indicator of intestinal permeability. |

## Selection lists

### English

#### Breed entry codes

| Entry code | Label |
| --- | --- |
| Hol | Holstein calf |
| Beef | Angus-Holstein crossbred calf |

#### Colostrum entry codes

| Entry code | Label |
| --- | --- |
| High | Indicates a high level of colostrum fed (10L/day) |
| Low | Indicates a low level of colostrum fed (5L/day) |

#### Day entry codes

| Entry code | Label |
| --- | --- |
| 1 | Day of life when blood sampling and the first Cr-EDTA dosing occur |
| 35 | Day of life when post-prandial blood sampling for glucose, insulin, and abomasal emptying rate occur |
| 84 | Day of life when final body weight, health assessments, and fecal sampling are recorded |

#### Hour entry codes

| Entry code | Label |
| --- | --- |
| 0 | Baseline blood sample collected before Cr-EDTA administration |
| 2 | Blood sample collected 2 hours post-dosing with Cr-EDTA |
| 4 | Blood sample collected 4 hours post-dosing with Cr-EDTA |
| 6 | Blood sample collected 6 hours post-dosing with Cr-EDTA |
| 8 | Blood sample collected 8 hours post-dosing with Cr-EDTA |
| 10 | Blood sample collected 10 hours post-dosing with Cr-EDTA |
| 12 | Blood sample collected 12 hours post-dosing with Cr-EDTA |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Feedlot_ID | false |  | Numeric |  |
| Colostrum | false |  | Text |  |
| Breed | false |  | Text |  |
| Birth_Date | false |  | DateTime |  |
| Birth_BW | false | kg | Numeric |  |
| Day | false |  | Numeric |  |
| Hour | false |  | Numeric |  |
| Cr_ppb | false | parts per billion (ppb) | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Feedlot_ID | Feedlot_ID | Number on the ear tag of each calf for identification | Not a list |
| Colostrum | Colostrum | Calves were either fed a high volume of colostrum (5 g IgG/kg body weight per feeding) or a low volume (2.5 g IgG/kg body weight per feeding) | Indicates a high level of colostrum fed (10L/day), Indicates a low level of colostrum fed (5L/day) |
| Breed | Breed | Purebred Holstein bull calf, or crossbred Angus-Holstein bull calf | Holstein calf, Angus-Holstein crossbred calf |
| Birth_Date | Birth_Date | Date of birth for each calf | Not a list |
| Birth_BW | Birth_BW | Body weight of each calf, measured on the day of birth | Not a list |
| Day | Day | Days of life when major sampling timepoints occur | Day of life when blood sampling and the first Cr-EDTA dosing occur, Day of life when post-prandial blood sampling for glucose, insulin, and abomasal emptying rate occur, Day of life when final body weight, health assessments, and fecal sampling are recorded |
| Hour | Hour | Hours prior to, or after dosing with the chromium-EDTA marker for gut permeability | Baseline blood sample collected before Cr-EDTA administration, Blood sample collected 2 hours post-dosing with Cr-EDTA, Blood sample collected 4 hours post-dosing with Cr-EDTA, Blood sample collected 6 hours post-dosing with Cr-EDTA, Blood sample collected 8 hours post-dosing with Cr-EDTA, Blood sample collected 10 hours post-dosing with Cr-EDTA, Blood sample collected 12 hours post-dosing with Cr-EDTA |
| Cr_ppb | Cr_ppb | Concentration of chromium in parts per billion (ppb) measured in blood plasma | Not a list |

## Schema SAIDs

**Capture base**: EGlGTzJrDZfIHYpnTduU0iyStN3Ybdeu3gXY2t364run

**Bundle**: EBYCKdI_w_flXrHI2mJ7e1GmjDX0eP23UIJnM9lbONC6

**Package**: EBzyEbYEf8Q1WZ-5YT-gaQLcsR1CX0u7WtGhB9585gnE

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EAgZ1oHKayNyCiQ7nKfqmaDQGpLed3F_pCgRC6zPPZLh | spec/overlays/entry/1.1 |
| entry_code | EB1Oe6lFZHsnxRZpXRO1h3jx5TpVXRMSehUrtbsMky8G | spec/overlays/entry_code/1.1 |
| information (eng) | EEJxAem26SoSHQ8KHDsIDxfWwIGNCXHWxR5aEVJmAk4V | spec/overlays/information/1.1 |
| label (eng) | EKvV8NwvUZE9MGzPSigCV-19qy5B_5oebhAOg5G7szrC | spec/overlays/label/1.1 |
| meta (eng) | ECtDvXBeSKOzqIrZJ3OibRQ_s4lu3l9PqR8mxK4ymfpU | spec/overlays/meta/1.1 |
| unit | EHuTOV2Qlhjf-kWwFMxiFonKNxyYzV5la12fpLN1N7cI | spec/overlays/unit/1.1 |
| ordering | ED-LYe14DaBHe9e7qOKKlRJIvWkz4TaESElPRNj9yoec | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:51:46

