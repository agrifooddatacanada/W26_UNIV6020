---
layout: default  
title: Cheng Qian 
parent: UNIV6026 Plant Agriculture Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Sticky Card Insect Monitoring  
**Description**: This schema is for greenhouse IPM scouting datasets. It includes identifiers (block/treatment/card/date), sticky card insect counts, and weekly mean climate variables (temperature and relative humidity).  
**Classification**: RDF404  
**Author**: Cheng Qian  
**Author Email**: cqian04@uoguelph.ca  
**Schema package SAID**: EJBiRinTXOV2f58d8ZUAfQ7eZzygB4PuquDZVLq45UCM  

[Download Schema](Qian_Sticky_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Treatment | Treatment group | Treatment assigned to each plot (biocontrol vs. control). |
| Block | Block ID | RCBD block based on greenhouse location. |
| Card_ID | Sticky card ID | Unique ID for each sticky card/position (e.g., B1-C1 = Block 1, Card 1). |
| Date | Sampling date | Date when the sticky card was checked (weekly). |
| Total_Insect_Counts | Total insect count | Total number of insects counted on the sticky card (count ≥ 0). |
| Temperature | Mean temperature | Weekly mean greenhouse air temperature. |
| RH | Mean relative humidity | Weekly mean relative humidity (0–100%). |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Sticky Card Insect Monitoring | This schema is for greenhouse IPM scouting datasets. It includes identifiers (block/treatment/card/date), sticky card insect counts, and weekly mean climate variables (temperature and relative humidity). |

## Selection lists

### English

#### Block entry codes

| Entry code | Label |
| --- | --- |
| B1 | Block 1 |
| B2 | Block 2 |
| B3 | Block 3 |
| B4 | Block 4 |

#### Treatment entry codes

| Entry code | Label |
| --- | --- |
| Control | Control (no biocontrol release) |
| Biocontrol | Biocontrol release |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Treatment | false |  | Text |  |
| Block | false |  | Text |  |
| Card_ID | false |  | Text |  |
| Date | false |  | DateTime |  |
| Total_Insect_Counts | false |  | Numeric |  |
| Temperature | false | ℃ | Numeric |  |
| RH | false | % | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Treatment | Treatment group | Treatment assigned to each plot (biocontrol vs. control). | Control (no biocontrol release), Biocontrol release |
| Block | Block ID | RCBD block based on greenhouse location. | Block 1, Block 2, Block 3, Block 4 |
| Card_ID | Sticky card ID | Unique ID for each sticky card/position (e.g., B1-C1 = Block 1, Card 1). | Not a list |
| Date | Sampling date | Date when the sticky card was checked (weekly). | Not a list |
| Total_Insect_Counts | Total insect count | Total number of insects counted on the sticky card (count ≥ 0). | Not a list |
| Temperature | Mean temperature | Weekly mean greenhouse air temperature. | Not a list |
| RH | Mean relative humidity | Weekly mean relative humidity (0–100%). | Not a list |

## Schema SAIDs

**Capture base**: EPm7RjsThtI5c6SIbuZKNXhGoEKO8QQERLkf4urVe31O

**Bundle**: EP2XCdwxDtlH_7_m9SBht5fv_FAewpflSZpRQTKebd0e

**Package**: EJBiRinTXOV2f58d8ZUAfQ7eZzygB4PuquDZVLq45UCM

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EFyGscz8GRhEh2-xTA-TyscH777QGCAcH8wYndKrmmtR | spec/overlays/entry/1.1 |
| entry_code | EJYtJaw-sT0FiPnIrmOSlKL9F_zrU7hT5hWtaH0g8gBM | spec/overlays/entry_code/1.1 |
| information (eng) | EMzVnQ-rRpjudidnunCu8ICisGcsiexUHVtiejI63Z8V | spec/overlays/information/1.1 |
| label (eng) | EMKVcgWcoAcFMRxdfOfXvYzsnrkF5cAub2z4xGBc0DMl | spec/overlays/label/1.1 |
| meta (eng) | EOLZhVrz28zGa4Jv_cEdWCophWd3xRE8F9x6wNtgCRYM | spec/overlays/meta/1.1 |
| unit | EHKk_doXdYEZGdLSdm4oUYixdKHt0MgwlhrMeltLlRrk | spec/overlays/unit/1.1 |
| ordering | EGZ-H9sUz8MkAMj6QBvygeLuj_nCu9PLEAB6SbLTmhjG | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:44:43

