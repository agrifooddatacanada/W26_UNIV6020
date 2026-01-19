---
layout: default  
title: Manika Maharjan
parent: UNIV6026 School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Litter Bag Study  
**Description**: Litter bag field experiment is conducted to understand how fast cover crop biomass gets decomposed and how much of those decomposed biomass contributes to the stable soil organic carbon pool. We used a 50 μm polyester mesh bag and added 10 gram dried chopped cover crop shoot part and then buried them in field at 7.5 cm soil depth and retrieved at least 17 times in a year.  
**Classification**: RDF401  
**Author**: Manika Maharjan  
**Author Email**: mmaharja@uoguelph.ca  
**Schema package SAID**: EDICETOFBG0nRhLCsVJV-IOeS1VBL9fTAOYyVRYrw_qQ

[Download Schema](Maharjan_Litter_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Date |  |  |
| Rep_no |  |  |
| Plot_Number |  |  |
| CC_Name | Cover Crop name | This represents the list of cover crop used in the experiment. |
| Fresh_Wt | Fresh weight | This represents the weight of cover crop biomass after litter bags were retrieved from the field on the designated sampling days. |
| Dry_Wt | Dry weight | This is the weight of oven-dried cover crop biomass after retrieval of the litter bags from the field, dried at 60 °C for 24 h. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Litter Bag Study | Litter bag field experiment is conducted to understand how fast cover crop biomass gets decomposed and how much of those decomposed biomass contributes to the stable soil organic carbon pool. We used a 50 μm polyester mesh bag and added 10 gram dried chopped cover crop shoot part and then buried them in field at 7.5 cm soil depth and retrieved at least 17 times in a year. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Lower Bound | Inclusive | Upper Bound | Inclusive |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Date | false |  | DateTime |  | true |  |
| Rep_no | false |  | Numeric |  | true |  |
| Plot_Number | true |  | Numeric |  | true |  |
| CC_Name | false |  | Text |  | true |  |
| Fresh_Wt | false | gm | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| Dry_Wt | false | gm | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |

### Unit framing 

| Term | Value |
| --- | --- |
| id | UCUM |
| label | Unified Code for Units of Measure |
| location | https://ucum.org/ |
| version |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Date |  |  | Not a list |
| Rep_no |  |  | Not a list |
| Plot_Number |  |  | Not a list |
| CC_Name | Cover Crop name | This represents the list of cover crop used in the experiment. | Not a list |
| Fresh_Wt | Fresh weight | This represents the weight of cover crop biomass after litter bags were retrieved from the field on the designated sampling days. | Not a list |
| Dry_Wt | Dry weight | This is the weight of oven-dried cover crop biomass after retrieval of the litter bags from the field, dried at 60 °C for 24 h. | Not a list |

## Schema SAIDs

**Capture base**: EITsTUH848iXn0XQNH5i93SqyXCVuxcfZv2b-WX52Ys_

**Bundle**: EOTAWgbZXSxAgfwgkwabH6sQl2Yum0YpW0hOykpW1u2y

**Package**: EDICETOFBG0nRhLCsVJV-IOeS1VBL9fTAOYyVRYrw_qQ

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EJ3mmjAfg193Dedy-ZPagFdPZEy5--qRjgeRjqO7xHAn | spec/overlays/conformance/1.1 |
| format | EI3lvVmQDW_lC35iVoOjrX2SReD9dpNw7xsGoYT8Nk6U | spec/overlays/format/1.1 |
| information (eng) | EJ8tTtzHRaePi5aWMKTFYKe85FdG9ze6n3JyhUVAsam7 | spec/overlays/information/1.1 |
| label (eng) | EBEyIY3GgsYdkHiTLeLSz0AtNfsZ-QEXNt69hn73hasP | spec/overlays/label/1.1 |
| meta (eng) | EF6jvc-ijfYps3PAaV8kiq6KH8-EFlgEPBGwt-VI8VyA | spec/overlays/meta/1.1 |
| unit | ELp1ELbhuI_Jzk2UZ8o6tmEYxZvObYwvi3K3u43qKWvB | spec/overlays/unit/1.1 |
| ordering | EHs2S_J1TfCbfoNW_KddFC483zbypLXs8YVTuVcI0pUY | community/overlays/adc/ordering/1.0 |
| range | EK_KW6sRs9REXSB-1qFYJPiCnnWyygsrCT8jTFjkV9zf | community/overlays/adc/range/1.0 |
| sensitive | EOcE_OBqJKenulCi_aIoQPALY2ps6_6nEdWE3_6G8dTD | community/overlays/adc/sensitive/1.0 |
| unit_framing | EPvpznB0YboQg5RCnzPUdwii1RXUdl533BipzZGgTmXB | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-15 11:39:22

