---
layout: default  
title: Bayan Abu Hamdia - Turkey Heat Balance Study Parameters  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Turkey Heat Balance Study Parameters  
**Description**: This schema describes the variables in a dataset collected from several studies on growing turkeys. The data include information on the housing environment, bird characteristics, body temperature, and heat production and heat loss. Measurements are taken from individual birds over time under normal temperature conditions and during chronic heat stress. The goal of this schema is to clearly explain each variable so the data can be understood, compared across studies, and reused in future research.  
**Classification**: RDF402  
**Author**: Bayan Abu Hamdia  
**Author Email**: habuhamd@uoguelph.ca  
**Schema package SAID**: EL9ifVzbjFAZa4fxckLFs-2Yt_7PKroQevWLuNdh8-In

[Download Schema](Hamdia_Turkey_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| bird_obs | Bird observation ID | Unique identifier for one observation record in the dataset. |
| study_id | Study ID | Identifier for the source study or paper from which the record was extracted. |
| paper_title | Paper title | Title of the source paper associated with the record. |
| species | Species | Species category standardized across studies (turkey, chicken, domestic fowl, or duck). |
| breed | Breed or strain | Breed or strain reported in the source study, if available. |
| sex | Sex | Sex of the bird as reported in the source study. |
| age | Age in weeks | Age of the bird at the time of measurement, reported in weeks. |
| live_weight | Live weight | Live body weight of the bird at the time of measurement. |
| treatment_id | Treatment ID | Identifier for the experimental treatment group in the source study. |
| replicate_group | Replicate group | Replicate or experimental unit grouping reported in the source study. |
| housing_type | Housing type | Housing system used in the study (for example, room, chamber, pen), if reported. |
| Ta | Air temperature | Ambient air temperature measured in the housing environment during sampling. |
| RH | Relative humidity | Relative humidity measured in the housing environment during sampling. |
| THI | Temperature humidity index | Temperature humidity index value reported or calculated for the sampling condition. |
| heat_stress_level | Heat stress level | Categorical heat stress classification for the condition (thermoneutral to severe heat stress). |
| duration | Duration under treatment | Time spent under the treatment condition before the measurement. |
| light | Light exposure | Light duration or light condition reported for the sampling period. |
| wind_speed | Wind speed | Air movement or wind speed measured in the housing environment during sampling. |
| core_rectal_temp | Core rectal temperature | Core body temperature measured rectally, reported in degrees Celsius. |
| skin_temp | Skin temperature | Skin or surface temperature measured during sampling, reported in degrees Celsius. |
| resp_rate | Respiration rate | Respiration rate during sampling, reported in breaths per minute. |
| feed_intake | Feed intake | Feed intake reported for the bird or group, usually per day. |
| water_intake | Water intake | Water intake reported for the bird or group, usually per day. |
| heat_prod | Heat production | Heat produced by the bird from metabolism, reported or estimated for the sampling condition. |
| heat_loss | Total heat loss | Total heat loss from the bird, reported or estimated for the sampling condition. |
| convection | Convective heat loss | Heat lost by convection, reported or estimated for the sampling condition. |
| radiation | Radiative heat loss | Heat lost by radiation, reported or estimated for the sampling condition. |
| evaporative_heat_loss | Evaporative heat loss | Heat lost by evaporation (latent heat loss), reported or estimated for the sampling condition. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Turkey Heat Balance Study Parameters | This schema describes the variables in a dataset collected from several studies on growing turkeys. The data include information on the housing environment, bird characteristics, body temperature, and heat production and heat loss. Measurements are taken from individual birds over time under normal temperature conditions and during chronic heat stress. The goal of this schema is to clearly explain each variable so the data can be understood, compared across studies, and reused in future research. |

## Selection lists

### English

#### heat_stress_level entry codes

| Entry code | Label |
| --- | --- |
| thermoneutral | Thermoneutral |
| mild_heat_stress | Mild heat stress |
| moderate_heat_stress | Moderate heat stress |
| severe_heat_stress | Severe heat stress |

#### sex entry codes

| Entry code | Label |
| --- | --- |
| male | Male |
| female | Female |
| mixed | Mixed |
| unknown | Unknown |

#### species entry codes

| Entry code | Label |
| --- | --- |
| Meleagris gallopavo | Turkey |
| Gallus gallus domesticus | Chicken |
| Gallus domesticus | Domestic fowl |
| Muscovy duck | duck |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| bird_obs | false |  | Text | utf-8 |
| study_id | false |  | Text | utf-8 |
| paper_title | false |  | Text |  |
| species | false |  | Text | utf-8 |
| breed | false |  | Text |  |
| sex | false |  | Text |  |
| age | false | weeks | Numeric |  |
| live_weight | false | grams | Numeric |  |
| treatment_id | false |  | Text | utf-8 |
| replicate_group | false |  | Text |  |
| housing_type | false |  | Text |  |
| Ta | false | degrees Celsius | Numeric | utf-8 |
| RH | false | percent | Numeric | utf-8 |
| THI | false |  | Numeric |  |
| heat_stress_level | false |  | Text | utf-8 |
| duration | false | days | Numeric |  |
| light | false | hours | Numeric |  |
| wind_speed | false | meters per second | Numeric |  |
| core_rectal_temp | false | degrees Celsius | Numeric | utf-8 |
| skin_temp | false | degrees Celsius | Numeric |  |
| resp_rate | false | breaths per minute | Numeric |  |
| feed_intake | false | grams per day | Numeric |  |
| water_intake | false | milliliters per day | Numeric |  |
| heat_prod | false | watts | Numeric |  |
| heat_loss | false | watts | Numeric |  |
| convection | false | watts | Numeric |  |
| radiation | false | watts | Numeric |  |
| evaporative_heat_loss | false | watts | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| bird_obs | Bird observation ID | Unique identifier for one observation record in the dataset. | Not a list |
| study_id | Study ID | Identifier for the source study or paper from which the record was extracted. | Not a list |
| paper_title | Paper title | Title of the source paper associated with the record. | Not a list |
| species | Species | Species category standardized across studies (turkey, chicken, domestic fowl, or duck). | Turkey, Chicken, Domestic fowl, duck |
| breed | Breed or strain | Breed or strain reported in the source study, if available. | Not a list |
| sex | Sex | Sex of the bird as reported in the source study. | Male, Female, Mixed, Unknown |
| age | Age in weeks | Age of the bird at the time of measurement, reported in weeks. | Not a list |
| live_weight | Live weight | Live body weight of the bird at the time of measurement. | Not a list |
| treatment_id | Treatment ID | Identifier for the experimental treatment group in the source study. | Not a list |
| replicate_group | Replicate group | Replicate or experimental unit grouping reported in the source study. | Not a list |
| housing_type | Housing type | Housing system used in the study (for example, room, chamber, pen), if reported. | Not a list |
| Ta | Air temperature | Ambient air temperature measured in the housing environment during sampling. | Not a list |
| RH | Relative humidity | Relative humidity measured in the housing environment during sampling. | Not a list |
| THI | Temperature humidity index | Temperature humidity index value reported or calculated for the sampling condition. | Not a list |
| heat_stress_level | Heat stress level | Categorical heat stress classification for the condition (thermoneutral to severe heat stress). | Thermoneutral, Mild heat stress, Moderate heat stress, Severe heat stress |
| duration | Duration under treatment | Time spent under the treatment condition before the measurement. | Not a list |
| light | Light exposure | Light duration or light condition reported for the sampling period. | Not a list |
| wind_speed | Wind speed | Air movement or wind speed measured in the housing environment during sampling. | Not a list |
| core_rectal_temp | Core rectal temperature | Core body temperature measured rectally, reported in degrees Celsius. | Not a list |
| skin_temp | Skin temperature | Skin or surface temperature measured during sampling, reported in degrees Celsius. | Not a list |
| resp_rate | Respiration rate | Respiration rate during sampling, reported in breaths per minute. | Not a list |
| feed_intake | Feed intake | Feed intake reported for the bird or group, usually per day. | Not a list |
| water_intake | Water intake | Water intake reported for the bird or group, usually per day. | Not a list |
| heat_prod | Heat production | Heat produced by the bird from metabolism, reported or estimated for the sampling condition. | Not a list |
| heat_loss | Total heat loss | Total heat loss from the bird, reported or estimated for the sampling condition. | Not a list |
| convection | Convective heat loss | Heat lost by convection, reported or estimated for the sampling condition. | Not a list |
| radiation | Radiative heat loss | Heat lost by radiation, reported or estimated for the sampling condition. | Not a list |
| evaporative_heat_loss | Evaporative heat loss | Heat lost by evaporation (latent heat loss), reported or estimated for the sampling condition. | Not a list |

## Schema SAIDs

**Capture base**: EA6NQH9sq5HBqxWLOCvUXcs9DryBDZpN40pUILCv1HOp

**Bundle**: EPYh-7_5aWW8wb-xQHHCI6nlZfEYx6CfscrRV7Kps_Uy

**Package**: EL9ifVzbjFAZa4fxckLFs-2Yt_7PKroQevWLuNdh8-In

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EEzZFA64WOobMNlOxw10FSTVV3ddSxpBmDPP62YXIpWz | spec/overlays/character_encoding/1.1 |
| entry (eng) | EMWS7cL1i9JdutFm46Kw2YqJR_fJEuE-xSKh8NnEgfNW | spec/overlays/entry/1.1 |
| entry_code | EHH92REvr8xM4wBtzutLxiiH6-IloUzDUrKW6FQJOpf- | spec/overlays/entry_code/1.1 |
| information (eng) | EAlRKr4Si0N8xHoi7_bFx-m3k7S50BeJ9jv8-PuqR-GT | spec/overlays/information/1.1 |
| label (eng) | ENSeAdwrvoMBTKadAIN-SUqUtrovL64g2Xa7bhUMTDn8 | spec/overlays/label/1.1 |
| meta (eng) | EOOwGLwOPtm4t5OxPIMEHME0Q_P79PvtXG4fH6Hcqfkt | spec/overlays/meta/1.1 |
| unit | EDHn71GLjVi8WHYL6kOhZ4fvcB1Kdcu5HKtlmY3X1Veo | spec/overlays/unit/1.1 |
| ordering | EI47rMiHMdMpCqN_DQsRGCYDwa_PuU0lGFEcJpHcmg26 | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:34:00

