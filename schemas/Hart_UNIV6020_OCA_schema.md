---
layout: default  
title: UNIV6020 Sample Hart  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: UNIV6020 Sample Hart  
**Description**: Working data schema for the NSERC Alliance Project (Lyons Trial) at the Ontario Beef Research Station in Elora, ON, Pasture One. Effects of pasture management strategies during the cow-calf phase of beef production, considering soil health, environmental microbiology and carbon sequestration.  
**Classification**: RDF105  
**Author**: Emilie Hart  
**Author Email**: ehart05@uoguelph.ca  
**Schema package SAID**: EOUKzVGtoWPLlGBtCsGHzljBQMi5KyIVAEvd9GOYpLco  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| sample_id | Soil sample identification | Unique sample ID that corresponds to a bulk 0-15 cm soil sample. Field#-Paddock#-Transec(A/B) |
| treatment | Grazing management strategy | Grazing management strategies included: strip grazing, a daily rotation, rotational grazing, a 3-day rotation between paddocks, and continuous grazing (unrestricted field access). |
| field | Field | Corresponds to the on-farm field map. Field 1-15 inclusive. Treatment is applied at the field level (i.e. grazing strategy) |
| paddock | Paddock | Corresponds to the on-farm field map. 1,3,7 were selected as representative sub-samples of a field. Each paddock was one acre of an eight-acre field. Paddocks were labelled in ascending order in a U-shape from the left side of the gate. |
| transect | Transect | Two 50-meter transects were used to subsample a one-acre paddock. 16 cores were taken along each transect. Transect A was always positioned closest to the main road. |
| pmn | Potentially mineralizable nitrogen | A soil health metric quantifying the amount of organic nitrogen that can be converted by microbes to inorganic forms. |
| resp | Microbial respiration | A soil health metric quantifying microbial mediated CO2 released (respiration). |
| moisture | Gravemetric moisture content | Moisture content taken within 1-2 days of sampling via mass/mass wet and oven-dry ratio. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | UNIV6020 Sample Hart | Working data schema for the NSERC Alliance Project (Lyons Trial) at the Ontario Beef Research Station in Elora, ON, Pasture One. Effects of pasture management strategies during the cow-calf phase of beef production, considering soil health, environmental microbiology and carbon sequestration. |

## Selection lists

### English

#### paddock entry codes

| Entry code | Label |
| --- | --- |
| 1 | Paddock 1 |
| 3 | Paddock 3 |
| 7 | Paddock 7 |

#### transect entry codes

| Entry code | Label |
| --- | --- |
| A | Transect A |
| B | Transect B |

#### treatment entry codes

| Entry code | Label |
| --- | --- |
| STRIP | Strip grazing |
| RG3 | Rotational grazing, three-day move |
| CG | Continuous grazing |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| sample_id | true |  | Text |  | false |
| treatment | false |  | Text |  | true |
| field | false |  | Text |  | false |
| paddock | false |  | Text |  | false |
| transect | false |  | Text |  | false |
| pmn | false | ug/g dry/week | Numeric |  | true |
| resp | false | mg CO2/20g soil | Numeric |  | true |
| moisture | false |  | Numeric |  | true |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| sample_id | Soil sample identification | Unique sample ID that corresponds to a bulk 0-15 cm soil sample. Field#-Paddock#-Transec(A/B) | Not a list |
| treatment | Grazing management strategy | Grazing management strategies included: strip grazing, a daily rotation, rotational grazing, a 3-day rotation between paddocks, and continuous grazing (unrestricted field access). | Strip grazing, Rotational grazing, three-day move, Continuous grazing |
| field | Field | Corresponds to the on-farm field map. Field 1-15 inclusive. Treatment is applied at the field level (i.e. grazing strategy) | Not a list |
| paddock | Paddock | Corresponds to the on-farm field map. 1,3,7 were selected as representative sub-samples of a field. Each paddock was one acre of an eight-acre field. Paddocks were labelled in ascending order in a U-shape from the left side of the gate. | Paddock 1, Paddock 3, Paddock 7 |
| transect | Transect | Two 50-meter transects were used to subsample a one-acre paddock. 16 cores were taken along each transect. Transect A was always positioned closest to the main road. | Transect A, Transect B |
| pmn | Potentially mineralizable nitrogen | A soil health metric quantifying the amount of organic nitrogen that can be converted by microbes to inorganic forms. | Not a list |
| resp | Microbial respiration | A soil health metric quantifying microbial mediated CO2 released (respiration). | Not a list |
| moisture | Gravemetric moisture content | Moisture content taken within 1-2 days of sampling via mass/mass wet and oven-dry ratio. | Not a list |

## Schema SAIDs

**Capture base**: ENK5t-rfL06wfyi9S6lkawf3nBjsPNYAQXrhRVNBnGiP

**Bundle**: EApEorAFYWBMy-MvaqyWoO61BfjOmwaFHrmOiLUEUFp2

**Package**: EOUKzVGtoWPLlGBtCsGHzljBQMi5KyIVAEvd9GOYpLco

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EP20FEzCPzloSwo8i9j0D7b9IagtUWc99nwyt1Qs9f6q | spec/overlays/conformance/1.1 |
| entry (eng) | EMFmj-EG7vVjFmEeEasX7MaTN-qeRLcAEwiWBeSUcYFk | spec/overlays/entry/1.1 |
| entry_code | ECDmiSgIi0r7c9Pbwsrfw_ZBUdjpW2tnqfdI04f6iJ4R | spec/overlays/entry_code/1.1 |
| information (eng) | EMdHHe4URZBNRKU9KwS_wBwUtitJjrvbRjVFFZf00xu1 | spec/overlays/information/1.1 |
| label (eng) | ENV5TSflhQI3fRQYIYjKDUmdC1xG30n5sKNiDEboAjGs | spec/overlays/label/1.1 |
| meta (eng) | EEs8U3KCV1q2BINSFR1mGW1-22-kEpXtxiboRyBRyU7- | spec/overlays/meta/1.1 |
| unit | ELHZ9IW05wwRvgSQFjHWyab0-_MVlr-9QdJJHKfXPk1u | spec/overlays/unit/1.1 |
| ordering | EAuYrP6F4S7r6sMLfjyw_2kBv2Xvs72GzjyVDW9l_XNu | community/overlays/adc/ordering/1.0 |
| sensitive | EH-pwZ2U5MP6sJOIKADvjBkCLMI0l7BltyxMYm1-6Gsg | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:36:38

