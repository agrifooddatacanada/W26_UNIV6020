---
layout: default  
title: Gestating Gilt Tissue Compositions  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Gestating Gilt Tissue Compositions  
**Description**: This data schema describes quantitative laboratory data generated from chemical composition analyses of biological tissue samples collected from pregnant gilts during late gestation. The dataset captures measurements related to dry matter and ash content, which are used to characterize tissue composition and support calculations of nutrient and protein pools within maternal and pregnancy-associated tissues. Each record in the dataset represents a single analyzed sample and includes identifiers linking the sample to an individual animal, tissue type, experimental group, and sampling time point. Variables include both raw laboratory measurements (e.g., sample weights before and after drying or ashing) and derived values (e.g., dry matter percentage, ash percentage), calculated using standardized laboratory procedures. Units of measurement are consistent across records to allow comparison among tissues, animals, and dietary treatments.  
**Classification**: RDF401  
**Author**: Vikki Ernest  
**Author Email**: vernest@uoguelph.ca  
**Schema package SAID**: EB--srzAd0RYfwXKM8yhvzDfuw-vX0WH1whauoE1pBpe  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Sample_ID | Sample_ID | Unique identifier assigned to each biological sample. This ID links laboratory measurements to the originating animal, tissue type, experimental treatment, and sampling time point used elsewhere in the project. |
| Crucible | Crucible | Identifier for the crucible used during drying and ashing procedures. |
| Crucible_wt | Crucible_wt | Mass of the empty crucible measured prior to sample addition, recorded in grams. This value is used to calculate sample dry matter and ash content. |
| Sample_wt | Sample_wt | Mass of the freeze-dried tissue sample placed into the crucible prior to drying, recorded in grams. This measurement represents the initial sample weight for dry matter determination. |
| Dried_wt | Dried_wt | Mass of the crucible and sample after oven drying to constant weight, recorded in grams. This value is used to calculate dry matter content. |
| DM | DM | Calculated dry matter percentage of the sample, expressed as a percentage of the original wet sample weight. This variable represents the proportion of solid material remaining after moisture removal. |
| Avg_DM | Avg_DM | Average dry matter percentage calculated from replicate measurements of the same sample or treatment group, used to improve accuracy and reduce analytical variability. |
| DM_CV | DM_CV | Coefficient of variation for dry matter measurements, expressed as a percentage. This variable is used as a quality control metric to assess analytical precision across replicates. |
| Ashed_wt | Ashed_wt | Mass of the crucible and sample after ashing in a muffle furnace, recorded in grams. This measurement represents the inorganic residue remaining after combustion of organic material. |
| Ash | Ash | Calculated ash percentage of the sample, expressed as a percentage of dry matter. This variable represents the mineral (inorganic) fraction of the tissue. |
| Avg_Ash | Avg_Ash | Average ash percentage calculated from replicate measurements of the same sample or treatment group, used to reduce analytical variability. |
| Ash_CV | Ash_CV | Coefficient of variation for ash measurements, expressed as a percentage. This variable is used to assess the precision and reliability of ash determination across replicates. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Gestating Gilt Tissue Compositions | This data schema describes quantitative laboratory data generated from chemical composition analyses of biological tissue samples collected from pregnant gilts during late gestation. The dataset captures measurements related to dry matter and ash content, which are used to characterize tissue composition and support calculations of nutrient and protein pools within maternal and pregnancy-associated tissues. Each record in the dataset represents a single analyzed sample and includes identifiers linking the sample to an individual animal, tissue type, experimental group, and sampling time point. Variables include both raw laboratory measurements (e.g., sample weights before and after drying or ashing) and derived values (e.g., dry matter percentage, ash percentage), calculated using standardized laboratory procedures. Units of measurement are consistent across records to allow comparison among tissues, animals, and dietary treatments. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Sample_ID | false |  | Text |  |
| Crucible | false |  | Text |  |
| Crucible_wt | false | g | Numeric |  |
| Sample_wt | false | g | Numeric |  |
| Dried_wt | false | g | Numeric |  |
| DM | false | % | Numeric |  |
| Avg_DM | false | % | Numeric |  |
| DM_CV | false | % | Numeric |  |
| Ashed_wt | false | g | Numeric |  |
| Ash | false | % | Numeric |  |
| Avg_Ash | false | % | Numeric |  |
| Ash_CV | false | % | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Sample_ID | Sample_ID | Unique identifier assigned to each biological sample. This ID links laboratory measurements to the originating animal, tissue type, experimental treatment, and sampling time point used elsewhere in the project. | Not a list |
| Crucible | Crucible | Identifier for the crucible used during drying and ashing procedures. | Not a list |
| Crucible_wt | Crucible_wt | Mass of the empty crucible measured prior to sample addition, recorded in grams. This value is used to calculate sample dry matter and ash content. | Not a list |
| Sample_wt | Sample_wt | Mass of the freeze-dried tissue sample placed into the crucible prior to drying, recorded in grams. This measurement represents the initial sample weight for dry matter determination. | Not a list |
| Dried_wt | Dried_wt | Mass of the crucible and sample after oven drying to constant weight, recorded in grams. This value is used to calculate dry matter content. | Not a list |
| DM | DM | Calculated dry matter percentage of the sample, expressed as a percentage of the original wet sample weight. This variable represents the proportion of solid material remaining after moisture removal. | Not a list |
| Avg_DM | Avg_DM | Average dry matter percentage calculated from replicate measurements of the same sample or treatment group, used to improve accuracy and reduce analytical variability. | Not a list |
| DM_CV | DM_CV | Coefficient of variation for dry matter measurements, expressed as a percentage. This variable is used as a quality control metric to assess analytical precision across replicates. | Not a list |
| Ashed_wt | Ashed_wt | Mass of the crucible and sample after ashing in a muffle furnace, recorded in grams. This measurement represents the inorganic residue remaining after combustion of organic material. | Not a list |
| Ash | Ash | Calculated ash percentage of the sample, expressed as a percentage of dry matter. This variable represents the mineral (inorganic) fraction of the tissue. | Not a list |
| Avg_Ash | Avg_Ash | Average ash percentage calculated from replicate measurements of the same sample or treatment group, used to reduce analytical variability. | Not a list |
| Ash_CV | Ash_CV | Coefficient of variation for ash measurements, expressed as a percentage. This variable is used to assess the precision and reliability of ash determination across replicates. | Not a list |

## Schema SAIDs

**Capture base**: EPgEI2bgBEuDPa0X8vKHIS9QvJsI5pdcVIwvwdKwU2lX

**Bundle**: EJN6-jZi-0ec5SXJOrHhhPzqIzXIyAM0fn6Nayc7gvRc

**Package**: EB--srzAd0RYfwXKM8yhvzDfuw-vX0WH1whauoE1pBpe

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EMS3rZrt1fLYUAdqrs3g_3mvWGHFHxbP2r7XRepCjnoc | spec/overlays/information/1.1 |
| label (eng) | EGWrDFhMWcs8FUoh4-hv-wlC4BKL5zycP2Ykp57GNK-q | spec/overlays/label/1.1 |
| meta (eng) | EAxpiwVzy-jtYC3zYWC_VLbi_D8BM3uZMm631ygXu3OQ | spec/overlays/meta/1.1 |
| unit | EJSgkAMOUVdujEnbyHlj-EJkeA9ran3VLNawrZkaXjFO | spec/overlays/unit/1.1 |
| ordering | EPIvEgKxW3AKtQdsYE5BPBuV7_FinjLkeWiNaAmfPF0W | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-16 09:41:16

