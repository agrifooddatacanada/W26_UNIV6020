---
layout: default  
title: Alvaro Llamosas Ibanez - Canabis meristem tissue culture  
parent: UNIV6026 Plant Agriculture Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Canabis meristem tissue culture  
**Description**: Schema contains information concerning cannabis meristem and nodal tissue samples and the different types of sterilization and treatment protocols used on each one, survival and presence of plant pathogens.  
**Classification**: RDF405  
**Author**: Alvaro Llamosas Ibanez  
**Author Email**: llamosaa@uoguelph.ca  
**Schema package SAID**: EPCp61nYsC7LuHGdca7bRDSusJZtmay6xUrgIkS-oDQd 

[Download Schema](Ibanez_Canabis_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| cultivar_id | cultivar id |  |
| date_created | date created |  |
| sample_type | sample type |  |
| num_samples | number of samples | number of samples created of specified cultivar |
| container_type | type of container |  |
| medium_type | medium_type | describes standard tissue culture media preparation (DMV, MKS) |
| sterilization_procedure | sterilization_procedure |  |
| survival_count | survival_count | number of samples that have survived after a period of 4 weeks |
| survival_rate | survival_rate | survival percentage |
| treatment | treatment | different treatments used to obtain viroid free tissue samples |
| hlvd | hlvd | Hop Latent Viroid disease |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Canabis meristem tissue culture | Schema contains information concerning cannabis meristem and nodal tissue samples and the different types of sterilization and treatment protocols used on each one, survival and presence of plant pathogens. |

## Selection lists

### English

#### container_type entry codes

| Entry code | Label |
| --- | --- |
| petri_plate | petri plate |
| test_tube | test tube |
| magenta_box | magenta box |

#### sample_type entry codes

| Entry code | Label |
| --- | --- |
| meristem | sample is a meristem |
| nodal | sample is a nodal cutting with at least two nodes |

#### sterilization_procedure entry codes

| Entry code | Label |
| --- | --- |
| sterile_1 | Standard sterilization concentrations and exposure times (70% EtOH - 1 min, 10% Bleach - 15 mins) |
| sterile_2 | Lower sterilization concentrations and exposure times (70% EtOH - 1 min, 7% Bleach - 10 mins) |
| sterile_3 | Lower sterilization concentrations and exposure times (70% EtOH - 1 min, 7% Bleach - 10 mins), with growth regulators (TDZ, NAA) |

#### treatment entry codes

| Entry code | Label |
| --- | --- |
| heat_trmt | exposing tissues to high temperature to inhibit virus replication |
| chem_trmt | use of plant hormones to slow viroid infection of meristems |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| cultivar_id | false |  | Text |  | true |  |
| date_created | false |  | Array[DateTime] |  | true | ^\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)/\(0\[1\-9\]\|1\[0\-2\]\)/\\d\{4\}$ |
| sample_type | false |  | Text |  | false |  |
| num_samples | false |  | Numeric |  | true |  |
| container_type | false |  | Text |  | false |  |
| medium_type | false |  | Text |  | false |  |
| sterilization_procedure | false |  | Text |  | true |  |
| survival_count | false |  | Numeric |  | false |  |
| survival_rate | false |  | Numeric |  | false |  |
| treatment | false |  | Text |  | true |  |
| hlvd | false |  | Array[Boolean] |  | true |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| cultivar_id | cultivar id |  | Not a list |
| date_created | date created |  | Not a list |
| sample_type | sample type |  | sample is a meristem, sample is a nodal cutting with at least two nodes |
| num_samples | number of samples | number of samples created of specified cultivar | Not a list |
| container_type | type of container |  | petri plate, test tube, magenta box |
| medium_type | medium_type | describes standard tissue culture media preparation (DMV, MKS) | Not a list |
| sterilization_procedure | sterilization_procedure |  | Standard sterilization concentrations and exposure times (70% EtOH - 1 min, 10% Bleach - 15 mins), Lower sterilization concentrations and exposure times (70% EtOH - 1 min, 7% Bleach - 10 mins), Lower sterilization concentrations and exposure times (70% EtOH - 1 min, 7% Bleach - 10 mins), with growth regulators (TDZ, NAA) |
| survival_count | survival_count | number of samples that have survived after a period of 4 weeks | Not a list |
| survival_rate | survival_rate | survival percentage | Not a list |
| treatment | treatment | different treatments used to obtain viroid free tissue samples | exposing tissues to high temperature to inhibit virus replication, use of plant hormones to slow viroid infection of meristems |
| hlvd | hlvd | Hop Latent Viroid disease | Not a list |

## Schema SAIDs

**Capture base**: ECLdzoTRdt-2nsMUJBJNsn83Hjf2Ib6JjcdFokP-BmFD

**Bundle**: EJrkthF-KJKAttDKwig1I6K8WBTyCKzc4huzp1gU5n9i

**Package**: EPCp61nYsC7LuHGdca7bRDSusJZtmay6xUrgIkS-oDQd

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EGbCFDak5y7mc7uV7M3QRBc8apmQ2Vl6ZTZpby4UTONL | spec/overlays/conformance/1.1 |
| entry (eng) | EE8U5-TgXu0KtpacsdtLvh6D4U8t663OTtB1kfzTmGn0 | spec/overlays/entry/1.1 |
| entry_code | EPq5SRMXVnsiCgd35H4qj9SJUgbycPU7gO4_QkPOvelc | spec/overlays/entry_code/1.1 |
| format | EKYp7dMFBjg_4O5m14seZ9WDOR11jcIW4pT8s7hQCDww | spec/overlays/format/1.1 |
| information (eng) | EGFBc7zniFEtBZc-zoiNG0WvHUIle5bTgbGp-6FegoxI | spec/overlays/information/1.1 |
| label (eng) | EANSiTKwcAFeogCMljH7Fut_pbXbEJxQwhaXL82QuA6W | spec/overlays/label/1.1 |
| meta (eng) | ELFwIIFgRVaAhRSvZMAB-HB1CdoA_0WcGNRGFIpjIWrE | spec/overlays/meta/1.1 |
| ordering | ELHmC1-Wfz5CSn4gN7T84oIYgmJT4CkcYYFqeWJpz0qz | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-16 09:42:52

