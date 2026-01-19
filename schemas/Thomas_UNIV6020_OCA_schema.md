---
layout: default  
title: UNIV6020 RDM - Precision Feeding in AMS: Blood Samples  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: UNIV6020 RDM - Precision Feeding in AMS: Blood Samples  
**Description**: This schema describes the information in the spreadsheet containing the blood sample data for the AMS precision feeding project.  
**Classification**: RDF402  
**Author**: Jayden Thomas  
**Author Email**: jthoma26@uoguelph.ca  
**Schema package SAID**: EI-7TetKQfTupFIuSU3kDIwopyhBVR-V6w9nq1uKWULY  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| cow_id | Cow ID | The ID number associated with the cow |
| trmt | Treatment Number | The treatment assigned to the cow; 1 = flat rate of concentrate, 2 = concentrate based on milk production, 3 = concentrate based on milk production and feed intake |
| date | Date | Date the blood sample was taken |
| sample | Sample Number | The sample number for that particular cow |
| actual_dim | Actual DIM | The number of days after calving the blood sample was taken |
| bhb | BHB | BHB (ketone) level in the blood sample |
| glucose | Glucose | Glucose level in the blood sample |
| notes | Notes | Any details about that particular blood sample (ex: issues with collection, strange blood appearance, etc.) |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | UNIV6020 RDM - Precision Feeding in AMS: Blood Samples | This schema describes the information in the spreadsheet containing the blood sample data for the AMS precision feeding project. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| cow_id | true |  | Numeric |  |
| trmt | false |  | Numeric |  |
| date | false |  | DateTime |  |
| sample | false |  | Numeric |  |
| actual_dim | false |  | Numeric |  |
| bhb | false | mmol/L | Numeric |  |
| glucose | false | mmol/L | Numeric |  |
| notes | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| cow_id | Cow ID | The ID number associated with the cow | Not a list |
| trmt | Treatment Number | The treatment assigned to the cow; 1 = flat rate of concentrate, 2 = concentrate based on milk production, 3 = concentrate based on milk production and feed intake | Not a list |
| date | Date | Date the blood sample was taken | Not a list |
| sample | Sample Number | The sample number for that particular cow | Not a list |
| actual_dim | Actual DIM | The number of days after calving the blood sample was taken | Not a list |
| bhb | BHB | BHB (ketone) level in the blood sample | Not a list |
| glucose | Glucose | Glucose level in the blood sample | Not a list |
| notes | Notes | Any details about that particular blood sample (ex: issues with collection, strange blood appearance, etc.) | Not a list |

## Schema SAIDs

**Capture base**: EKouIGLwkcLzHOxIk2Qez9jQnrWKkkOOujz7lY8EsBiu

**Bundle**: EK7GmZTC_jijQQsyH_u_D9OE_49F_PN1bOC5x732wlj8

**Package**: EI-7TetKQfTupFIuSU3kDIwopyhBVR-V6w9nq1uKWULY

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EPyzPbDOEO3Ncl7TKNJuWEQYsL10PK4KZ4-rEVnM9-5v | spec/overlays/information/1.1 |
| label (eng) | ECwhftFRfOLGOKZP5yRxmSpptqYD-OPV1UJIn_LnJYJD | spec/overlays/label/1.1 |
| meta (eng) | EHBGR6cJCLaChEbVDD4pBfI_UAEg12E90jgr9llpHb0Q | spec/overlays/meta/1.1 |
| unit | EH-RxBtj1XSpRa5QXab0KD0rh225S43pv9a5bsKGvdJ3 | spec/overlays/unit/1.1 |
| ordering | EE0_jq7vhLXrgHOE3NluHKq8DwfyJGiBFtyJp318GLR5 | community/overlays/adc/ordering/1.0 |
| sensitive | EM1mhr_KjQiTyvJiD4T2O742VRh6oLfR4VNWPc33KWq- | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:50:47

