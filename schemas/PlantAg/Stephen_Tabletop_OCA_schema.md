---
layout: default  
title: Anna Stephen - Tabletop Strawberry Project  
parent: UNIV6026 Plant Agriculture Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Tabletop Strawberry Project  
**Description**: Tabletop strawberry cultivation utilizes soilless media on raised beds in a controlled environment such as a high tunnel. This project will include trials on cultivar, plant type (plug vs bare root), fertility/irrigation, soil substrate, as well as cropping length/timing to provide Ontario growers with recommendations to succeed with this advanced method to strawberry production.  
**Classification**: RDF401  
**Author**: Anna Stephen  
**Author Email**: asteph08@uoguelph.ca  
**Schema package SAID**: EKiYF-5xIMezPLGs_MIq3AKR0AMsrHwgKMbCj2_FZ80L  

[Download Schema](Stephen_Tabletop_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Collection_Date | Collection_Date | Date that strawberries were harvested and data was collected |
| Plot_ID | Plot_ID | Unique plot identification |
| LMN | LMN | Total number of large marketable fruit |
| LMW | LMW | Weight of large marketable fruit |
| SMN | SMN | Total number of small marketable fruit |
| SMW | SMW | Weight of small marketable fruit |
| UMN | UMN | Total number of unmarketable fruit |
| UMW | UMW | Weight of unmarketable fruit |
| RFN | RFN | Total number of rotted fruit |
| RFW | RFW | Weight of rotted fruit |
| Crown_size | Crown_size | Crown size at planting |
| Plant_type | Plant_type | Bare-root or plug plant |
| Cultivar | Cultivar | Variety of strawberry |
| Planting_date | Planting_Date | Planting date |
| Blossom_removal | Blossom_removal | No blossom removal or blossom removal from plants |
| Media_type | Media_type | Type of soilless media |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Tabletop Strawberry Project | Tabletop strawberry cultivation utilizes soilless media on raised beds in a controlled environment such as a high tunnel. This project will include trials on cultivar, plant type (plug vs bare root), fertility/irrigation, soil substrate, as well as cropping length/timing to provide Ontario growers with recommendations to succeed with this advanced method to strawberry production. |

## Selection lists

### English

#### Blossom_removal entry codes

| Entry code | Label |
| --- | --- |
| NR | No blossom removal |
| BR | Blossom removal for 3 weeks |

#### Crown_size entry codes

| Entry code | Label |
| --- | --- |
| Lg | Large crown size |
| Sm | Small crown size |

#### Cultivar entry codes

| Entry code | Label |
| --- | --- |
| Alb | Albion |
| San | San Andreas |

#### Media_type entry codes

| Entry code | Label |
| --- | --- |
| BVB | BVB Coir |
| Lambert | Lambert Peat |

#### Plant_type entry codes

| Entry code | Label |
| --- | --- |
| PP | Plug plant |
| BRP | Bare-root plant |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Collection_Date | false |  | DateTime |  |
| Plot_ID | false |  | Numeric |  |
| LMN | false |  | Numeric |  |
| LMW | false | kg | Numeric |  |
| SMN | false |  | Numeric |  |
| SMW | false | kg | Numeric |  |
| UMN | false |  | Numeric |  |
| UMW | false | kg | Numeric |  |
| RFN | false |  | Numeric |  |
| RFW | false | kg | Numeric |  |
| Crown_size | false |  | Text |  |
| Plant_type | false |  | Text |  |
| Cultivar | false |  | Text |  |
| Planting_date | false |  | DateTime |  |
| Blossom_removal | false |  | Text |  |
| Media_type | false |  | Text |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Collection_Date | Collection_Date | Date that strawberries were harvested and data was collected | Not a list |
| Plot_ID | Plot_ID | Unique plot identification | Not a list |
| LMN | LMN | Total number of large marketable fruit | Not a list |
| LMW | LMW | Weight of large marketable fruit | Not a list |
| SMN | SMN | Total number of small marketable fruit | Not a list |
| SMW | SMW | Weight of small marketable fruit | Not a list |
| UMN | UMN | Total number of unmarketable fruit | Not a list |
| UMW | UMW | Weight of unmarketable fruit | Not a list |
| RFN | RFN | Total number of rotted fruit | Not a list |
| RFW | RFW | Weight of rotted fruit | Not a list |
| Crown_size | Crown_size | Crown size at planting | Large crown size, Small crown size |
| Plant_type | Plant_type | Bare-root or plug plant | Plug plant, Bare-root plant |
| Cultivar | Cultivar | Variety of strawberry | Albion, San Andreas |
| Planting_date | Planting_Date | Planting date | Not a list |
| Blossom_removal | Blossom_removal | No blossom removal or blossom removal from plants | No blossom removal, Blossom removal for 3 weeks |
| Media_type | Media_type | Type of soilless media | BVB Coir, Lambert Peat |

## Schema SAIDs

**Capture base**: EASBmD7bgMlvJuIYsNSFTP39B_4yd16mHP_7OwEFcX8L

**Bundle**: EMQZ2K11l_iSyeH7nwB1gbxwD183Uxy1CXInYOSxMnQt

**Package**: EKiYF-5xIMezPLGs_MIq3AKR0AMsrHwgKMbCj2_FZ80L

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | ELAk3uAEJomh-VLUYnnxP7f8dcpXS44EnF_39OQYpT3u | spec/overlays/entry/1.1 |
| entry_code | EJ7cDLUhtLl_sqbMVlae0TV6wqtMtz-kAbCwuc77Sv6C | spec/overlays/entry_code/1.1 |
| information (eng) | ELQnC_1oAE7JnPZUsI13ojZr4ZbsntzMEOWPhHrGYemy | spec/overlays/information/1.1 |
| label (eng) | EMz1DiTPFqZDPjFbbEAWkEYh_mnYhDEB8Txt-euPEgwi | spec/overlays/label/1.1 |
| meta (eng) | EMUhZOzk986qs2XKByse1O2zUo_zt-SR5_HwsQSl3Lbb | spec/overlays/meta/1.1 |
| unit | EHQrxOHYnvu4b0CDkDCAu4UfQeQXgNP3Vz868gQkmQE- | spec/overlays/unit/1.1 |
| ordering | EN961E6ZU7yY2vQe9--dhdfo8eefu2Z-lV55UNIwyyJ0 | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-16 09:49:47

