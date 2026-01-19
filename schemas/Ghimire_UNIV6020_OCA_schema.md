---
layout: default  
title: UNIV6020 Assignment  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: UNIV6020 Assignment  
**Description**: This project aims at exploring the impact of varying amounts of vermicompost and urea fertilizer on the vegetative development of corn (Zea mays L.). The research design is a two-factor factorial experiment design where the application of vermicompost is at five levels and urea fertilizer is at four levels in three replications giving 60 units of the experiment. The parameters of growth such as stem height, stem diameter, length of leaves, width of leaves, and the number of leaves were measured at 64-65 days after planting. All the data would be stored in one, structured dataset at the level of experimental-units to facilitate transparent data management, statistical analysis, and reproducibility with the help of Excel, R, or SPSS.  
**Classification**: RDF401  
**Author**: Bibek Ghimire  
**Author Email**: bibek@uoguelph.ca  
**Schema package SAID**: EAL-qhreRPgRfEfSFhPb3Fa6q9t47NlnIFM8tF5fBfC7  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Experiment_id | Experiment_id | Each experimental unit number |
| replication | replication | The replicate number indicating repeated experimental units under the same treatment combination. |
| vermicompost_level | vermicompost_level | Categorical code indicating the level of vermicompost treatment applied (K0–K4) |
| vermicompost_amount | vermicompost_amount | The amount of vermicompost applied per square meter of land for each experimental unit, expressed in kilograms. |
| urea_level | urea_level | Categorical code indicating the level of urea fertilizer treatment applied (U0–U3). |
| urea_amount | urea_amount | The quantity of urea fertilizer applied per plant for each experimental unit, expressed in grams. |
| days_after_planting | days_after_planting | The number of days after planting when vegetative growth measurements were collected. |
| stem_height | stem_height | The vertical height of the corn stem measured from the soil surface to the highest vegetative point, expressed in centimeters |
| stem_diameter | stem_diameter | The diameter of the corn stem measured at a standard position above the soil surface, expressed in millimeters. |
| leaf_length | leaf_length | The length of a fully expanded corn leaf measured from the base to the tip, expressed in centimeters. |
| leaf_width | leaf_width | The maximum width of a fully expanded corn leaf measured at its widest point, expressed in millimeters. |
| leaves_number | leaves_number | The total number of fully developed leaves counted on each corn plant at the time of measurement. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | UNIV6020 Assignment | This project aims at exploring the impact of varying amounts of vermicompost and urea fertilizer on the vegetative development of corn (Zea mays L.). The research design is a two-factor factorial experiment design where the application of vermicompost is at five levels and urea fertilizer is at four levels in three replications giving 60 units of the experiment. The parameters of growth such as stem height, stem diameter, length of leaves, width of leaves, and the number of leaves were measured at 64-65 days after planting. All the data would be stored in one, structured dataset at the level of experimental-units to facilitate transparent data management, statistical analysis, and reproducibility with the help of Excel, R, or SPSS. |

## Selection lists

### English

#### urea_level entry codes

| Entry code | Label |
| --- | --- |
| U0 | 0 g plant⁻¹ |
| U1 | 0.6 g plant⁻¹ |
| U2 | 1.2 g plant⁻¹ |
| U3 | 1.8 g plant⁻¹ |

#### vermicompost_level entry codes

| Entry code | Label |
| --- | --- |
| K0 | 0 kg m⁻² |
| K1 | 0.5 kg m⁻² |
| K2 | 1 kg m⁻² |
| K3 | 1.5 kg m⁻² |
| K4 | 2 kg m⁻² |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Experiment_id | false | unitless | Numeric |  |
| replication | false | unitless | Numeric |  |
| vermicompost_level | false | categorical | Text |  |
| vermicompost_amount | false | kg m⁻² | Numeric |  |
| urea_level | false | categorial | Text |  |
| urea_amount | false | g plant⁻¹ | Numeric |  |
| days_after_planting | false | days | Numeric |  |
| stem_height | false | cm | Numeric |  |
| stem_diameter | false | mm | Numeric |  |
| leaf_length | false | cm | Numeric |  |
| leaf_width | false | mm | Numeric |  |
| leaves_number | false | count | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Experiment_id | Experiment_id | Each experimental unit number | Not a list |
| replication | replication | The replicate number indicating repeated experimental units under the same treatment combination. | Not a list |
| vermicompost_level | vermicompost_level | Categorical code indicating the level of vermicompost treatment applied (K0–K4) | 0 kg m⁻², 0.5 kg m⁻², 1 kg m⁻², 1.5 kg m⁻², 2 kg m⁻² |
| vermicompost_amount | vermicompost_amount | The amount of vermicompost applied per square meter of land for each experimental unit, expressed in kilograms. | Not a list |
| urea_level | urea_level | Categorical code indicating the level of urea fertilizer treatment applied (U0–U3). | 0 g plant⁻¹, 0.6 g plant⁻¹, 1.2 g plant⁻¹, 1.8 g plant⁻¹ |
| urea_amount | urea_amount | The quantity of urea fertilizer applied per plant for each experimental unit, expressed in grams. | Not a list |
| days_after_planting | days_after_planting | The number of days after planting when vegetative growth measurements were collected. | Not a list |
| stem_height | stem_height | The vertical height of the corn stem measured from the soil surface to the highest vegetative point, expressed in centimeters | Not a list |
| stem_diameter | stem_diameter | The diameter of the corn stem measured at a standard position above the soil surface, expressed in millimeters. | Not a list |
| leaf_length | leaf_length | The length of a fully expanded corn leaf measured from the base to the tip, expressed in centimeters. | Not a list |
| leaf_width | leaf_width | The maximum width of a fully expanded corn leaf measured at its widest point, expressed in millimeters. | Not a list |
| leaves_number | leaves_number | The total number of fully developed leaves counted on each corn plant at the time of measurement. | Not a list |

## Schema SAIDs

**Capture base**: EG8daeUX_8w2kxA_15cSUIL4DIFpfsFPdRWMt9ZGdR1f

**Bundle**: EEJGXs0qHRGiGxUp-Dh6_gcVoguSExmq1ujDxKbDTZpq

**Package**: EAL-qhreRPgRfEfSFhPb3Fa6q9t47NlnIFM8tF5fBfC7

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EDdiP_sCqZGXRqFv3dcDHa7PtqLNcv3mfSNC0b3Y1YNt | spec/overlays/entry/1.1 |
| entry_code | EBReOqljoKR8R1qkY4twM4POFp8UElR8FuoT-PFu9Yi9 | spec/overlays/entry_code/1.1 |
| information (eng) | EDBzc5nuWBwVCNwGERagL4yyEs4p_Um6XHgQSN74uLqa | spec/overlays/information/1.1 |
| label (eng) | EIPmsvE5EbOUmVwf-wHZ-4KEwHVNj2ASZ2szzz79t4ag | spec/overlays/label/1.1 |
| meta (eng) | ED459ryqaG2J25teS9e9fg9q7rYROcpqiYZ1GBfDyB4t | spec/overlays/meta/1.1 |
| unit | ED4QfxN_A5FpaCMQCkUk5QlD2x-kouOMMdodCjguBbBB | spec/overlays/unit/1.1 |
| ordering | ECLU7xg64qXGmKRczNE7tWOktirBEUWuITvfWVpP1TfQ | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:32:24

