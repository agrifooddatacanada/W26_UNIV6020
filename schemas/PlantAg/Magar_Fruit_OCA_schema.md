---
layout: default  
title: Sabina Roka Magar - Fruit and Vegetable Crop Yield in Canada  
parent: UNIV6026 Plant Agriculture Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Fruit and Vegetable Crop Yield in Canada  
**Description**: This data schema describes a dataset containing information on fruits and vegetables grown in Canada. The dataset includes crop name, crop category (fruit or vegetable), yield measured in tonnes per hectare, and total production measured in tonnes.  
**Classification**: RDF401  
**Author**: Sabina Roka Magar  
**Author Email**: srokamag@uoguelph.ca  
**Schema package SAID**: ECgVVFH499VpBin2LARMv7z5_srYTux3RH4MPovzxi2K 

[Download Schema](Magar_Fruit_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| crop_name |  | Name of the fruit or vegetable grown in Canada |
| crop_category | Fruits or Vegetables | Category of the crop |
| yield |  | Crop yield per hectare |
| total_production |  | Total weight of crop produced |
| year |  | Year of crop production |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Fruit and Vegetable Crop Yield in Canada | This data schema describes a dataset containing information on fruits and vegetables grown in Canada. The dataset includes crop name, crop category (fruit or vegetable), yield measured in tonnes per hectare, and total production measured in tonnes. |

## Selection lists

### English

#### crop_category entry codes

| Entry code | Label |
| --- | --- |
| Fruit | Fruit |
| Vegetable | Vegetable |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule | Lower Bound | Inclusive | Upper Bound | Inclusive |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| crop_name | false |  | Text |  | true | ^\.\{0,50\}$ |
| crop_category | false |  | Text |  | true | ^\.\{0,50\}$ |
| yield | false | t/ha | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true | 100000 | true |
| total_production | false | t | Numeric |  | true | ^\-?\[0\-9\]\+$ | 0 | true | 10000000 | true |
| year | false |  | Numeric |  | true | ^\-?\[0\-9\]\+$ | 1900 | true | 2025 | true |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| crop_name |  | Name of the fruit or vegetable grown in Canada | Not a list |
| crop_category | Fruits or Vegetables | Category of the crop | Fruit, Vegetable |
| yield |  | Crop yield per hectare | Not a list |
| total_production |  | Total weight of crop produced | Not a list |
| year |  | Year of crop production | Not a list |

## Schema SAIDs

**Capture base**: EJW3J6uXfzHlOWnNm4v9CIPgx4y5gMON8rZ9NGVzVK6x

**Bundle**: ELPipYTaPfCDmby3uZZcrPq-hRxGfMSj7DOlIphSV9pH

**Package**: ECgVVFH499VpBin2LARMv7z5_srYTux3RH4MPovzxi2K

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EPIns6fGGngFxF7WwUAcwHkbARS7GxdodPh9xhbssGHn | spec/overlays/conformance/1.1 |
| entry (eng) | EI5QflWwS7qtMTGaed1ylcmUajbJL9u2iKYAQ4oTDU2y | spec/overlays/entry/1.1 |
| entry_code | EKLYfHwuwHeEPhdrgCzwN_C5GQUNDRkQreJcrERaIj42 | spec/overlays/entry_code/1.1 |
| format | EOjBHPnvFDs4kBIvhwoAviKfBwk9pyDB0IUy7xqDhsvk | spec/overlays/format/1.1 |
| information (eng) | EIzkUJACNNUZfl8wlx6caYq-ugknkyw8lAyjdWkJdPfR | spec/overlays/information/1.1 |
| label (eng) | EJkmv8MMeBKBm9dxft2j96GxErOm8eXHqzI-rS4Kq50Z | spec/overlays/label/1.1 |
| meta (eng) | EGAM8pORftg7T41Y8foHixc7TKHoDE85FhV0yLj2Xs87 | spec/overlays/meta/1.1 |
| unit | EPY1wFdqO3H-lPgC4GSapWA5qBVrXKITh7B6AAxJeQ47 | spec/overlays/unit/1.1 |
| ordering | ENrWszN3FIEna5l6ETF0uwtcRJmMmoB6jg6a6F1XjwgU | community/overlays/adc/ordering/1.0 |
| range | EFJ7wdQlBJrtSKlogApvYi6P-m2zgDuaheX9L0jAr2nP | community/overlays/adc/range/1.0 |

**Date created**: 2026-01-16 09:44:13

