---
layout: default  
title: Josephin Nivetha Victor 
parent: UNIV6026 Plant Agriculture Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Horse Feed Consumption and Weight Change Dataset  
**Description**: This dataset contains information on horse demographics, feeding treatments, feed consumption, and body weight changes over a two-week experimental feeding trial.  
**Classification**: RDF402  
**Author**: Josephin Nivetha Victor  
**Author Email**: victorj@uoguelph.ca  
**Schema package SAID**: EHCS_PHYMmQTky-7jEGRgvQPTD1O_DKvop9gU0OX4fMx  

[Download Schema](Victor_Horse_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Horse_Registration_Number | Horse Registration Number | A unique identification number assigned to each registered horse |
| Horse_Age | Horse Age | The age of the horse in years |
| Horse_Gender | Horse Gender | The biological sex of the horse, either male or female |
| Treatment | Treatment | Experimental treatment assigned to each horse during the study. Treatments were coded to distinguish between different dietary or management interventions applied. |
| Starting_Weight | Starting Weight | Initial body weight of the horse measured at the beginning of the study, before any experimental treatment was applied. The weight was recorded in kilograms (kg). |
| Feed_Type | Feed Type | Type of feed provided to the horse during the study period. This variable describes the diet category or feed formulation assigned to each horse. |
| Feed_Supplier | Feed Supplier | Name of the company or source that supplied the feed used in the study. This information helps track feed origin and ensure consistency and traceability across treatments. |
| Weight_Week_1 | Weight Week 1 | Body weight of the horse measured at the end of the first week of the study following the start of the experimental treatments. The weight was recorded in kilograms (kg). |
| Feed_Consumed_Week_1 | Feed Consumed Week 1 | Amount of feed consumed by the horse during the first week of the study. This value represents the total feed intake over week 1 and was recorded in kilograms (kg). |
| Weight_Week_2 | Weight Week 2 | Body weight of the horse measured at the end of the second week of the study following the start of the experimental treatments. The weight was recorded in kilograms (kg). |
| Feed_Consumed_Week_2 | Feed Consumed Week 2 | Amount of feed consumed by the horse during the second week of the study. This value represents the total feed intake over week 2 and was recorded in kilograms (kg). |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Horse Feed Consumption and Weight Change Dataset | This dataset contains information on horse demographics, feeding treatments, feed consumption, and body weight changes over a two-week experimental feeding trial. |

## Selection lists

### English

#### Horse_Gender entry codes

| Entry code | Label |
| --- | --- |
| 1 | Male |
| 2 | Female |

#### Treatment entry codes

| Entry code | Label |
| --- | --- |
| A | Treatment A |
| B | Treatment B |
| C | Treatment C |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Unit Framing |
| --- | --- | --- | --- | --- | --- | --- |
| Horse_Registration_Number | false | N/A | Numeric | utf-8 | true |
| Horse_Age | false | Years | Numeric | utf-8 | true | a |
| Horse_Gender | false | 1 = Male, 2 = Female | Text | utf-8 | true |
| Treatment | false | A/B/C | Text | utf-8 | true |
| Starting_Weight | false | Kg | Numeric | utf-8 | true | kg |
| Feed_Type | false | N/A | Text | utf-8 | true |
| Feed_Supplier | false | N/A | Text | utf-8 | true |
| Weight_Week_1 | false | Kg | Numeric | utf-8 | true | kg |
| Feed_Consumed_Week_1 | false | Kg | Numeric | utf-8 | true | kg |
| Weight_Week_2 | false | Kg | Numeric | utf-8 | true | kg |
| Feed_Consumed_Week_2 | false | Kg | Numeric | utf-8 | true | kg |

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
| Horse_Registration_Number | Horse Registration Number | A unique identification number assigned to each registered horse | Not a list |
| Horse_Age | Horse Age | The age of the horse in years | Not a list |
| Horse_Gender | Horse Gender | The biological sex of the horse, either male or female | Male, Female |
| Treatment | Treatment | Experimental treatment assigned to each horse during the study. Treatments were coded to distinguish between different dietary or management interventions applied. | Treatment A, Treatment B, Treatment C |
| Starting_Weight | Starting Weight | Initial body weight of the horse measured at the beginning of the study, before any experimental treatment was applied. The weight was recorded in kilograms (kg). | Not a list |
| Feed_Type | Feed Type | Type of feed provided to the horse during the study period. This variable describes the diet category or feed formulation assigned to each horse. | Not a list |
| Feed_Supplier | Feed Supplier | Name of the company or source that supplied the feed used in the study. This information helps track feed origin and ensure consistency and traceability across treatments. | Not a list |
| Weight_Week_1 | Weight Week 1 | Body weight of the horse measured at the end of the first week of the study following the start of the experimental treatments. The weight was recorded in kilograms (kg). | Not a list |
| Feed_Consumed_Week_1 | Feed Consumed Week 1 | Amount of feed consumed by the horse during the first week of the study. This value represents the total feed intake over week 1 and was recorded in kilograms (kg). | Not a list |
| Weight_Week_2 | Weight Week 2 | Body weight of the horse measured at the end of the second week of the study following the start of the experimental treatments. The weight was recorded in kilograms (kg). | Not a list |
| Feed_Consumed_Week_2 | Feed Consumed Week 2 | Amount of feed consumed by the horse during the second week of the study. This value represents the total feed intake over week 2 and was recorded in kilograms (kg). | Not a list |

## Schema SAIDs

**Capture base**: EMS56xA_SgX5n5pY7L3hVNDOgYN3Xpm7cKvFZ2BhDDmg

**Bundle**: ELQNfM0qvMbGsiRXPDZbqlfOLka3_ar50jkuxNMsXBUd

**Package**: EHCS_PHYMmQTky-7jEGRgvQPTD1O_DKvop9gU0OX4fMx

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EMsIYmV-rLOIyzX6LFGqZwVlghp5OLu6fR_RxH--mlRa | spec/overlays/character_encoding/1.1 |
| conformance | EKP4IDR6d8k3qZm7-7lpSyFY2UpfW3r4u-E8PVhar6Ku | spec/overlays/conformance/1.1 |
| entry (eng) | EMGoQGP4EyxzJ1Itcs-UWjuxsT9tLgso1dkM0iVLfObf | spec/overlays/entry/1.1 |
| entry_code | EEHN7anebMqXVfep1vt8CgvEvR3FEEK10lBNCFe4Te_C | spec/overlays/entry_code/1.1 |
| information (eng) | EDiAkFJ1wXtamSdHlUWdr6ILv8zUNBlx7_3UZmo5SMNA | spec/overlays/information/1.1 |
| label (eng) | ENWROTws0stWslWUu51Z9nekilWGmFLdhRwVXy9jA-l- | spec/overlays/label/1.1 |
| meta (eng) | EN2dIy5WnoBpZpUwOnsLUjmXPHefkhtLITf9t0msiSgU | spec/overlays/meta/1.1 |
| unit | ELhhb_OC2RfYsN39shUneWx64tCYFzZmLvy_Dm_EKAHx | spec/overlays/unit/1.1 |
| ordering | ENtN_6v-7JAbXwlI1Goyp5JJSYhaaE4-eM-1a6KkAxmi | community/overlays/adc/ordering/1.0 |
| unit_framing | ED-Dla7W92emXYWL-cIf9sErXuEwCxZuZ44mdDd24aLS | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-16 09:45:38

