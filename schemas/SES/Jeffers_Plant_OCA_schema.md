---
layout: default  
title: Ella Jeffers
parent: UNIV6026 School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Plant Destructive Harvest Data Collection  
**Description**: Series of destructive measurements performed on tomato plants in order to gain valuable harvest data.  
**Classification**: RDF401  
**Author**: Ella Jeffers  
**Author Email**: jefferse@uoguelph.ca  
**Schema package SAID**: EPzbvJO7pkDg656OE3t0XNTSNsov_PEHuopVL2DlMhsc 

[Download Schema](Jeffers_Plant_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| plant_ID | Plant Identification Tag | Individual plant identification tag, unique to each plant. |
| pot_size | Plant Pot Size | Size of the pot each plant was grown in. |
| node_count | Node Count | Total number of nodes with either a leaf longer than 5cm or inflorescence longer than 3cm present on plant at time of harvest. |
| leaf_count | Leaf Count | Total number of true leaves longer than 5cm present on plant at time of harvest. |
| inflorescence_count | Inflorescence Count | Total number of inflorescences longer than 3cm present on plant at time of harvest. |
| leaf_area | Leaf Area | Total leaf area of plant at time of harvest. |
| SPAD | SPAD | Average SPAD value of 5 measured leaves at time of harvest. |
| leaf_FW | Leaf Fresh Weight | Total weight of true leaves on plant at time of harvest. |
| stem_FW | Stem Fresh Weight | Total weight of stem cut at the base of the plant just above soil with the leaves removed at time of harvest. |
| leaf_DW | Leaf Dry Weight | Total weight of completely dried true leaves at time of harvest. |
| stem_DW | Stem Dry Weight | Total weight of completely dried stem tissue cut at the base of the plant just above soil with leaves removed at time of harvest. |
| root_DW | Root Dry Weight | Total weight of completely dried root tissue initially collected at time of harvest. |
| height | Plant Height | Height of plant from the base of the plant just above soil to the tip of the growing point at time of harvest. |
| cultivar | Cultivar | Cultivar each plant harvested belongs to. |
| flower_count | Flower Count | Number of flowers present on all inflorescences longer than 3cm at time of harvest. |
| openflower_count | Open Flower Count | Number of open flowers present on all inflorescences longer than 3cm at time of harvest. |
| closedflower_count | Closed Flower Count | Number of closed flowers present on all inflorescences longer than 3cm at time of harvest. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Plant Destructive Harvest Data Collection | Series of destructive measurements performed on tomato plants in order to gain valuable harvest data. |

## Selection lists

### English

#### cultivar entry codes

| Entry code | Label |
| --- | --- |
| Endeavour | RZH - Endeavour cultivar |
| Trovanzo | RZH - Trovanzo cultivar |

#### pot_size entry codes

| Entry code | Label |
| --- | --- |
| Small | Small pot size |
| Medium | Medium pot size |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| plant_ID | true |  | Text |  |
| pot_size | false |  | Text |  |
| node_count | false |  | Numeric |  |
| leaf_count | false |  | Numeric |  |
| inflorescence_count | false |  | Numeric |  |
| leaf_area | false | cm^2 | Numeric |  |
| SPAD | false |  | Numeric |  |
| leaf_FW | false | g | Numeric |  |
| stem_FW | false | g | Numeric |  |
| leaf_DW | false | g | Numeric |  |
| stem_DW | false | g | Numeric |  |
| root_DW | false | g | Numeric |  |
| height | false | cm | Numeric |  |
| cultivar | false |  | Text |  |
| flower_count | false |  | Numeric |  |
| openflower_count | false |  | Numeric |  |
| closedflower_count | false |  | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| plant_ID | Plant Identification Tag | Individual plant identification tag, unique to each plant. | Not a list |
| pot_size | Plant Pot Size | Size of the pot each plant was grown in. | Small pot size, Medium pot size |
| node_count | Node Count | Total number of nodes with either a leaf longer than 5cm or inflorescence longer than 3cm present on plant at time of harvest. | Not a list |
| leaf_count | Leaf Count | Total number of true leaves longer than 5cm present on plant at time of harvest. | Not a list |
| inflorescence_count | Inflorescence Count | Total number of inflorescences longer than 3cm present on plant at time of harvest. | Not a list |
| leaf_area | Leaf Area | Total leaf area of plant at time of harvest. | Not a list |
| SPAD | SPAD | Average SPAD value of 5 measured leaves at time of harvest. | Not a list |
| leaf_FW | Leaf Fresh Weight | Total weight of true leaves on plant at time of harvest. | Not a list |
| stem_FW | Stem Fresh Weight | Total weight of stem cut at the base of the plant just above soil with the leaves removed at time of harvest. | Not a list |
| leaf_DW | Leaf Dry Weight | Total weight of completely dried true leaves at time of harvest. | Not a list |
| stem_DW | Stem Dry Weight | Total weight of completely dried stem tissue cut at the base of the plant just above soil with leaves removed at time of harvest. | Not a list |
| root_DW | Root Dry Weight | Total weight of completely dried root tissue initially collected at time of harvest. | Not a list |
| height | Plant Height | Height of plant from the base of the plant just above soil to the tip of the growing point at time of harvest. | Not a list |
| cultivar | Cultivar | Cultivar each plant harvested belongs to. | RZH - Endeavour cultivar, RZH - Trovanzo cultivar |
| flower_count | Flower Count | Number of flowers present on all inflorescences longer than 3cm at time of harvest. | Not a list |
| openflower_count | Open Flower Count | Number of open flowers present on all inflorescences longer than 3cm at time of harvest. | Not a list |
| closedflower_count | Closed Flower Count | Number of closed flowers present on all inflorescences longer than 3cm at time of harvest. | Not a list |

## Schema SAIDs

**Capture base**: EKs0vExFpbRTYe04bidAJynFbMSPNtdqs3npZfbNWc35

**Bundle**: EBQkbIAmisZMYvejTZtvPIWH_Xzrdq8WdFyEfr9v8seV

**Package**: EPzbvJO7pkDg656OE3t0XNTSNsov_PEHuopVL2DlMhsc

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | ENv5PBLm3yWugY91CHLzOeBb1ZSSKsXvuYpYu9Rqg67F | spec/overlays/entry/1.1 |
| entry_code | EFOJZgr8VPcSF7hCZuyARM0enfh7TPg2hMzHfsRIAQx7 | spec/overlays/entry_code/1.1 |
| information (eng) | EMt2yzp5GWUcJGHbfyl_Ty9tbm-zKOh6cRoGidrVAxjj | spec/overlays/information/1.1 |
| label (eng) | EOPMFXPdnS-NhIIDcQcxSiyjZjmqGxI1xhShA3V2o0rE | spec/overlays/label/1.1 |
| meta (eng) | EBrbzfB89z1QRKy06TMgDRN6gvaw9cavl1sXInJWjz6T | spec/overlays/meta/1.1 |
| unit | EJ78dAGLwbG9MLarzKhigc0QP_YDqFJjSIanDvJFAqY9 | spec/overlays/unit/1.1 |
| ordering | ENUiJzhtMJWxLh7lt6IJwm2f4TFsr1I_gXEUyuTFoBCV | community/overlays/adc/ordering/1.0 |
| sensitive | EKsIVr-uXaqYCsHUnl48Raw4w_UafBLH20u9diAF1VwY | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-19 10:30:20

