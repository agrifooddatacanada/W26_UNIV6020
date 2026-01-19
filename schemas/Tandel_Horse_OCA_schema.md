---
layout: default  
title: Horse Experimental Data  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Horse Experimental Data  
**Description**: This dataset contains information on horses used in a research study, including demographic characteristics, treatment group, and performance metrics.  
**Classification**: RDF402  
**Author**: Muskan Tandel  
**Author Email**: tandelm@uoguelph.ca  
**Schema package SAID**: EHR8fj67q3xaP7_1dU2Q6Her5OGzRz6HoGdEiapLf3dk  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| horse_registration_number | Horse Registration Number | Unique alphanumeric code assigned to identify each individual horse within the dataset. |
| horse_age | Horse Age | Age of the horse in whole years at the time of measurement. |
| horse_gender | Horse Gender | Biological sex of the horse, encoded numerically (e.g., 1 = Male, 2 = Female). |
| treatment | Treatment | Assigned treatment category or protocol applied to the horse, labeled as A, B, or C. |
| starting_weight | Starting Weight | Body weight of the horse in kilograms recorded at the beginning of the study or treatment period. |
| feed_type | Feed Type | Category of feed provided to the horse, such as Hay, Pasture, or Silage. |
| feed_supplier | Feed Supplier | Name of the company or farm responsible for supplying the horse’s feed |
| weight_week_1 | Weight Week 1 | Recorded body weight of the horse in kilograms at the end of the first week of observation. |
| feed_consumed_week_1 | Feed Consumed Week 1 | Total amount of feed in kilograms consumed by the horse during the first week. |
| weight_week_2 | Weight Week 2 | Recorded body weight of the horse in kilograms at the end of the second week of observation. |
| feed_consumed_week_2 | Feed Consumed Week 2 | Total amount of feed in kilograms consumed by the horse during the second week. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Horse Experimental Data | This dataset contains information on horses used in a research study, including demographic characteristics, treatment group, and performance metrics. |

## Selection lists

### English

#### horse_gender entry codes

| Entry code | Label |
| --- | --- |
| 1 | male |
| 2 | female |

#### treatment entry codes

| Entry code | Label |
| --- | --- |
| A | Treatment A |
| B | Treatment B |
| C | Treatment C |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Unit Framing |
| --- | --- | --- | --- | --- | --- | --- |
| horse_registration_number | false | N/A | Numeric | utf-8 | true |
| horse_age | false | Years | Numeric | utf-8 | true | a |
| horse_gender | false | 1=male, 2=female | Text | utf-8 | true |
| treatment | false | A/B/C | Text | utf-8 | true |
| starting_weight | false | Kg | Numeric | utf-8 | true | kg |
| feed_type | false | N/A | Text | utf-8 | true |
| feed_supplier | false | N/A | Text | utf-8 | true |
| weight_week_1 | false | Kg | Numeric | utf-8 | true | kg |
| feed_consumed_week_1 | false | Kg | Numeric | utf-8 | true | kg |
| weight_week_2 | false | Kg | Numeric | utf-8 | true | kg |
| feed_consumed_week_2 | false | Kg | Numeric | utf-8 | true | kg |

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
| horse_registration_number | Horse Registration Number | Unique alphanumeric code assigned to identify each individual horse within the dataset. | Not a list |
| horse_age | Horse Age | Age of the horse in whole years at the time of measurement. | Not a list |
| horse_gender | Horse Gender | Biological sex of the horse, encoded numerically (e.g., 1 = Male, 2 = Female). | male, female |
| treatment | Treatment | Assigned treatment category or protocol applied to the horse, labeled as A, B, or C. | Treatment A, Treatment B, Treatment C |
| starting_weight | Starting Weight | Body weight of the horse in kilograms recorded at the beginning of the study or treatment period. | Not a list |
| feed_type | Feed Type | Category of feed provided to the horse, such as Hay, Pasture, or Silage. | Not a list |
| feed_supplier | Feed Supplier | Name of the company or farm responsible for supplying the horse’s feed | Not a list |
| weight_week_1 | Weight Week 1 | Recorded body weight of the horse in kilograms at the end of the first week of observation. | Not a list |
| feed_consumed_week_1 | Feed Consumed Week 1 | Total amount of feed in kilograms consumed by the horse during the first week. | Not a list |
| weight_week_2 | Weight Week 2 | Recorded body weight of the horse in kilograms at the end of the second week of observation. | Not a list |
| feed_consumed_week_2 | Feed Consumed Week 2 | Total amount of feed in kilograms consumed by the horse during the second week. | Not a list |

## Schema SAIDs

**Capture base**: EJFFR_c1QtjXsbI-IqpB-_vbK2biZ-Fq_kbPzawUBnZk

**Bundle**: EJkeEud6pfd95e5T6VKBJpAfVelqtzFoH1LkPo8tSFno

**Package**: EHR8fj67q3xaP7_1dU2Q6Her5OGzRz6HoGdEiapLf3dk

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EK5YdKyRvWTHFU2VeZp_iFkU8xLhTYPJo0HXEqMG0NPA | spec/overlays/character_encoding/1.1 |
| conformance | ENDGBXgBM1MGaCky84bX2CQlbsWnKjFpIVtNlQabnjGd | spec/overlays/conformance/1.1 |
| entry (eng) | EGJyxlspQVACUuhjp1jCv1lYh7_lBmJOzIFm_hKqgZ5f | spec/overlays/entry/1.1 |
| entry_code | EJVk8q2Luo-aZ1YrluGex6fvtYhAPTEuptdEMZoTnH0O | spec/overlays/entry_code/1.1 |
| information (eng) | EKBJpLj9T-0ALu778TyAhPhHqxdgyLzLEFSrkxJ0H4et | spec/overlays/information/1.1 |
| label (eng) | EGIpsSM5cCHIcuHJvZIR5ypq-FQX9kUQEr8tB8JaD8jS | spec/overlays/label/1.1 |
| meta (eng) | EMOyNqYH1iPnofF4WF6mlrJG5u_Y0LtVU0CxrfEsGsQX | spec/overlays/meta/1.1 |
| unit | EA3ErFzp-3isFd5VpSCy_uSa2QWWsHbMNsz0KWrIxAid | spec/overlays/unit/1.1 |
| ordering | EF1SJOqd7FPjcQfB9uFkHLiZHUpyvy5gP6A0NIkAqBz2 | community/overlays/adc/ordering/1.0 |
| unit_framing | ENcrHV-MjlqcL-6FIxe3vWZJl1l-hkYBJYDfagtk7_0H | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-16 09:50:58

