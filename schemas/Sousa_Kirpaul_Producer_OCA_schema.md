---
layout: default  
title: Producer Ridgling Data  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Producer Ridgling Data  
**Description**: Measurements of hormone concentrations at specific slaughter weights for ridgling boars of different producers  
**Classification**: RDF402  
**Author**: Sean Sousa-Kirpaul  
**Author Email**: ssousaki@uoguelph.ca  
**Schema package SAID**: ENlB6LFS2nxDk3pY71G0KXaSXuf81rYoVP61wSP5fkhi  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Sample_num | Sample number | Sequential sample number for fat samples taken from ridglings in chronological order |
| ID | Identification number | The producer/sample-unique ID number for each animal |
| Date_Collected | Date collected | Date of sample collection at slaughter for each animal in the format DDMMYY |
| Weight_kg | Weight | The weight at slaughter for each animal in kilograms |
| Fat3one_ugg | Fat androstenone | The measured androstenone concentration in fat samples in micrograms per gram |
| FatSkatole_ngmL | Fat skatole | The measured skatole concentration in fat samples in nanograms per millilitre |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Producer Ridgling Data | Measurements of hormone concentrations at specific slaughter weights for ridgling boars of different producers |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Lower Bound | Inclusive | Upper Bound | Inclusive | Unit Framing |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Sample_num | false |  | Numeric |  | false |  |
| ID | true |  | Numeric |  | true | ^\-?\[0\-9\]\+$ | 1 | true | 9999999 | true |
| Date_Collected | false |  | DateTime |  | true | ^\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)/\(0\[1\-9\]\|1\[0\-2\]\)/\\d\{2\}$ | 01/01/23 | true | 01/01/27 | true |
| Weight_kg | false | kg | Numeric |  | true | ^\-?\[0\-9\]\+$ | 1 | true | 200 | true | kg |
| Fat3one_ugg | false | ug/g | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true | 500 | true | ug/g |
| FatSkatole_ngmL | false | ng/mL | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true | 1000 | true | ng/mL |

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
| Sample_num | Sample number | Sequential sample number for fat samples taken from ridglings in chronological order | Not a list |
| ID | Identification number | The producer/sample-unique ID number for each animal | Not a list |
| Date_Collected | Date collected | Date of sample collection at slaughter for each animal in the format DDMMYY | Not a list |
| Weight_kg | Weight | The weight at slaughter for each animal in kilograms | Not a list |
| Fat3one_ugg | Fat androstenone | The measured androstenone concentration in fat samples in micrograms per gram | Not a list |
| FatSkatole_ngmL | Fat skatole | The measured skatole concentration in fat samples in nanograms per millilitre | Not a list |

## Schema SAIDs

**Capture base**: EFhyvEGCWy34uHUh4j7pz1jj-2QaDY3xwl6Qd4Iycve9

**Bundle**: EJRVHTsJaOJ1yMsvrMyyrsp4Z1LCDxB0tMQ1aNoc1DxG

**Package**: ENlB6LFS2nxDk3pY71G0KXaSXuf81rYoVP61wSP5fkhi

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EKGNoIPSgiZTJj_-kTtCKeWuaeRTMNqBJKcYEdz_A2ss | spec/overlays/conformance/1.1 |
| format | EJb_Sm3uwi_-wEOkmszLC2Y27c3b4s5mWyL_aMWOVj0B | spec/overlays/format/1.1 |
| information (eng) | EI2ZfYw36KZux7LMD7tRg81QYOdrJvjeZpuprzt6Mdj8 | spec/overlays/information/1.1 |
| label (eng) | EJE5-VWwAqhHd5A12zMVCo7reNiNdcCvQIwOqMTbS97G | spec/overlays/label/1.1 |
| meta (eng) | EKXiNFs24S7tr2ELHX7k7vRyW0-udKzmFrViNgX4N2pR | spec/overlays/meta/1.1 |
| unit | EFH52WHaRZLegl_nE2tphfWlALxGjP_3HR7J_6op4YCg | spec/overlays/unit/1.1 |
| ordering | EAyFXJrYnqDns5Hl-ORtrQfIi3KQoxddVLr_9E07T5SP | community/overlays/adc/ordering/1.0 |
| range | ENZC9CWZB82GSaWuIFl48FreuYJQg5rrOpBmSThlGEXu | community/overlays/adc/range/1.0 |
| sensitive | ECOteBoJtS5GbZnqLnT4XVNb4rVU1thOzrCfIjZ7w6ZO | community/overlays/adc/sensitive/1.0 |
| unit_framing | EBwZBhkyjWbbmlErCVXczvujQIOPp_agX_L8J1nscZFI | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-15 11:49:41

