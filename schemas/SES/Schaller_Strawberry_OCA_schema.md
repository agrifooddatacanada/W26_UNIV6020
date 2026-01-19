---
layout: default  
title: Jonah Schaller 
parent: UNIV6026 School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Strawberry Tipburn Under Blue LED Light  
**Description**: This study looks at the efficacy of nighttime blue LED lighting in preventing strawberry tipburn - a physiological disorder that results from localized calcium deficiency in the shoot tissue. In addition to tipburn incidence (no. affected leaves/flowers), this study looks at additional effects pure blue light may have on strawberry development. All plants were grown in a controlled growth chamber within the University of Guelph.  
**Classification**: RDF401  
**Author**: Jonah Schaller  
**Author Email**: schaller@uoguelph.ca  
**Schema package SAID**: EDGllXsRtME1EuMnjF9HfywSEe9LC3DeFAy_pH5EXNAy  

[Download Schema](Schaller_Strawberry_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Phase | Plant growth stage or phase. | Two phases in this trial: (1) vegetative phase in which runners and flowers (reproductive parts) are pruned to encourage leaf growth; and (2) reproductive phase, in which runners are pruned, but flowers are allowed to develop into fruit. |
| Block | Experimental block (RCBD) in growth chamber. | There are six compartments (experimental units) within the growth chamber that are divided into three blocks, e.g., 1 blue light compartment and 1 control compartment per block. |
| Treatment | Lighting treatment. | Treatment plants are subject to nighttime blue LED lighting while control plants are not. That said, there are two lighting treatments - blue or dark (control). |
| Compartment | Individual compartment (experimental unit) within growth chamber. | Six compartments, or experimental units (n), within the growth chamber, divided by lighting blocking curtains. Apart from their nighttime lighting environments, all other environmental variables are uniform among compartments. |
| Plant_ID | Unique number code given to individual strawberry plants. | Unique number code given to individual strawberry plant subsamples within their respective compartments. There are 12 plant subsamples per compartment, and are therefore a total of 72 unique plant IDs. |
| Week | Weeks that have elapsed since trial start. | Number of weeks (uniform time points) that have elapsed since the beginning of the trial. As a growth trial, repeated measures were necessary to track the development of outcome variables over time as plants grew larger and bared fruit. |
| TB_Leaves | Number of leaves with tipburn. | Absolute number of leaves with tipburn symptoms observed on a given plant for that week (measurement time point). |
| Green_Buds | Number of green flower buds. | Absolute number of healthy, green flower buds (no tipburn symptoms) observed on a given plant for that week. |
| TB_Buds | Number of flower buds with tipburn. | Absolute number of flower buds with tipburn symptoms observed on a given plant for that week. |
| Runners | Number of runners. | Absolute number of runners observed and pruned from a given plant for that week. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Strawberry Tipburn Under Blue LED Light | This study looks at the efficacy of nighttime blue LED lighting in preventing strawberry tipburn - a physiological disorder that results from localized calcium deficiency in the shoot tissue. In addition to tipburn incidence (no. affected leaves/flowers), this study looks at additional effects pure blue light may have on strawberry development. All plants were grown in a controlled growth chamber within the University of Guelph. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Format rule |
| --- | --- | --- | --- | --- | --- |
| Phase | false |  | Text |  | ^\.\{0,50\}$ |
| Block | false |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| Treatment | false |  | Text |  |  |
| Compartment | false |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| Plant_ID | false |  | Numeric |  | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| Week | false |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| TB_Leaves | true |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| Green_Buds | true |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| TB_Buds | true |  | Numeric |  | ^\-?\[0\-9\]\+$ |
| Runners | true |  | Numeric |  | ^\-?\[0\-9\]\+$ |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Phase | Plant growth stage or phase. | Two phases in this trial: (1) vegetative phase in which runners and flowers (reproductive parts) are pruned to encourage leaf growth; and (2) reproductive phase, in which runners are pruned, but flowers are allowed to develop into fruit. | Not a list |
| Block | Experimental block (RCBD) in growth chamber. | There are six compartments (experimental units) within the growth chamber that are divided into three blocks, e.g., 1 blue light compartment and 1 control compartment per block. | Not a list |
| Treatment | Lighting treatment. | Treatment plants are subject to nighttime blue LED lighting while control plants are not. That said, there are two lighting treatments - blue or dark (control). | Not a list |
| Compartment | Individual compartment (experimental unit) within growth chamber. | Six compartments, or experimental units (n), within the growth chamber, divided by lighting blocking curtains. Apart from their nighttime lighting environments, all other environmental variables are uniform among compartments. | Not a list |
| Plant_ID | Unique number code given to individual strawberry plants. | Unique number code given to individual strawberry plant subsamples within their respective compartments. There are 12 plant subsamples per compartment, and are therefore a total of 72 unique plant IDs. | Not a list |
| Week | Weeks that have elapsed since trial start. | Number of weeks (uniform time points) that have elapsed since the beginning of the trial. As a growth trial, repeated measures were necessary to track the development of outcome variables over time as plants grew larger and bared fruit. | Not a list |
| TB_Leaves | Number of leaves with tipburn. | Absolute number of leaves with tipburn symptoms observed on a given plant for that week (measurement time point). | Not a list |
| Green_Buds | Number of green flower buds. | Absolute number of healthy, green flower buds (no tipburn symptoms) observed on a given plant for that week. | Not a list |
| TB_Buds | Number of flower buds with tipburn. | Absolute number of flower buds with tipburn symptoms observed on a given plant for that week. | Not a list |
| Runners | Number of runners. | Absolute number of runners observed and pruned from a given plant for that week. | Not a list |

## Schema SAIDs

**Capture base**: EH9dXdZ9tlJ0G27Fe2wgI9taV8dW54sNoOcNsTsRfyQ4

**Bundle**: EOrPqwd0Z7UPkAYidQ79ADh-y0ACFWUnk-JHgCZxBpCo

**Package**: EDGllXsRtME1EuMnjF9HfywSEe9LC3DeFAy_pH5EXNAy

| Layer | SAID | Type |
| --- | --- | --- |
| format | EH975s9_r6Djg-1R1F-RQfvliGs9Uw0W7BkQcHfmOnlL | spec/overlays/format/1.1 |
| information (eng) | EOZE8jk8a61x9HatVgAeQDcRbMBJL0GUhnWU4mLRQwe8 | spec/overlays/information/1.1 |
| label (eng) | EAU0YKrXDrgRrjpzfyTxrbdYuJwBqvF2FMYbGODkjuQM | spec/overlays/label/1.1 |
| meta (eng) | EAy_1_oC2uRin7KyQAaoKdxnz4j1zRJRPf44-Smdve10 | spec/overlays/meta/1.1 |
| ordering | EDh-6qwjbCxrxtvbX8_WSn6wQsh2zSWLdDeEKvQTbNX8 | community/overlays/adc/ordering/1.0 |
| sensitive | ECM9cuREYivIy9aLO1NOY1GmUsqBCih2GTt7aJ1Fx6dR | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:48:37

