---
layout: default  
title: Tung Lam Ngo 
parent: Food Science Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Relationships among oral processing behaviour, sensory perception, and bolus properties of embedded almonds in chocolate matrices  
**Description**: This schema describes a tabular dataset used to examine relationships between oral processing behaviour, sensory perception, and bolus properties for chocolate matrices containing embedded almonds. Each record represents one observation per panellist per sample (panellist ID). Variables include sample information (sample mass, sample code, sample name), oral processing metrics (consumption time, number of chews, number of swallows, eating rate, chew rate per min, swallow rate per min), and bolus/particle characteristics (D50, number of particles, particle size, saliva incorporation).  
**Classification**: RDF404  
**Author**: Tung Lam Ngo  
**Author Email**: tngo09@uoguelph.ca  
**Schema package SAID**: EJrRwg_TprbMkLhXYwXiV8RC_uYugJeOzFfHAGBJaDNE  

[Download Schema](Ngo_Relationships_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Panellist_ID | Panellist identifier | Pseudonymized unique ID for each panellist (no direct personal identifiers) |
| Sample_code | Sample code | Code used to blind/identify the product sample |
| Sample_name | Sample name | Name of the sample |
| Sample_mass | Sample mass | Mass of the food sample portion provided |
| Consumption_time | Consumption time | Total time from first bite to swallow for the sample |
| Number_of_swallows | Number of swallows | Total count of swallows observed during consumption of the sample |
| Eating_rate | Eating rate | Rate of consumption calculated from mass and consumption time |
| Number_of_chews | Number of chews | Total count of chewing cycles observed during consumption of the sample |
| Chew_rate_per_min | Chewing rate | Chewing frequency is expressed as chews per minute during consumption |
| Swallow_rate_per_min | Swallowing rate | Swallowing frequency expressed as swallows per minute during consumption |
| D50 | Median particle size | Median particle size of almonds particles |
| Number_of_particles | Number of particles | Count of particles quantified in particle analysis for the sample |
| Particles_size | Particle size | Particle size metric used in analysis |
| Saliva_incorporation | Saliva incorporation | Amount of saliva incorporated into bolus as measured for the sample |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Relationships among oral processing behaviour, sensory perception, and bolus properties of embedded almonds in chocolate matrices | This schema describes a tabular dataset used to examine relationships between oral processing behaviour, sensory perception, and bolus properties for chocolate matrices containing embedded almonds. Each record represents one observation per panellist per sample (panellist ID). Variables include sample information (sample mass, sample code, sample name), oral processing metrics (consumption time, number of chews, number of swallows, eating rate, chew rate per min, swallow rate per min), and bolus/particle characteristics (D50, number of particles, particle size, saliva incorporation). |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| Panellist_ID | true |  | Text |  | true |
| Sample_code | false |  | Numeric |  | true |
| Sample_name | false |  | Text |  | true |
| Sample_mass | false | gram | Numeric |  | false |
| Consumption_time | false | sec | Numeric |  | false |
| Number_of_swallows | false | count | Numeric |  | false |
| Eating_rate | false | g/min | Numeric |  | false |
| Number_of_chews | false | count | Numeric |  | false |
| Chew_rate_per_min | false | chews/min | Numeric |  | false |
| Swallow_rate_per_min | false | swallows/mins | Numeric |  | false |
| D50 | false | mm | Numeric |  | false |
| Number_of_particles | false | count | Numeric |  | false |
| Particles_size | false | mm | Numeric |  | false |
| Saliva_incorporation | false | ml | Numeric |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Panellist_ID | Panellist identifier | Pseudonymized unique ID for each panellist (no direct personal identifiers) | Not a list |
| Sample_code | Sample code | Code used to blind/identify the product sample | Not a list |
| Sample_name | Sample name | Name of the sample | Not a list |
| Sample_mass | Sample mass | Mass of the food sample portion provided | Not a list |
| Consumption_time | Consumption time | Total time from first bite to swallow for the sample | Not a list |
| Number_of_swallows | Number of swallows | Total count of swallows observed during consumption of the sample | Not a list |
| Eating_rate | Eating rate | Rate of consumption calculated from mass and consumption time | Not a list |
| Number_of_chews | Number of chews | Total count of chewing cycles observed during consumption of the sample | Not a list |
| Chew_rate_per_min | Chewing rate | Chewing frequency is expressed as chews per minute during consumption | Not a list |
| Swallow_rate_per_min | Swallowing rate | Swallowing frequency expressed as swallows per minute during consumption | Not a list |
| D50 | Median particle size | Median particle size of almonds particles | Not a list |
| Number_of_particles | Number of particles | Count of particles quantified in particle analysis for the sample | Not a list |
| Particles_size | Particle size | Particle size metric used in analysis | Not a list |
| Saliva_incorporation | Saliva incorporation | Amount of saliva incorporated into bolus as measured for the sample | Not a list |

## Schema SAIDs

**Capture base**: ECK4xCE75Kqqksn-Nq4YbWN-_R8ZHJyAfxX5I1_KxrfM

**Bundle**: ENxTke-KB3DNxRNPDgXiBuTESFhVZeEfwoNIeSd5XlDV

**Package**: EJrRwg_TprbMkLhXYwXiV8RC_uYugJeOzFfHAGBJaDNE

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EF10KuMSHQxShbvee0JGKn7H0NkdyMpQOtXV20E3P-ER | spec/overlays/conformance/1.1 |
| information (eng) | EBHTHq1C7w9dhwIgPy49sTZxwOJypHkj2ww2_3oS54-j | spec/overlays/information/1.1 |
| label (eng) | EI7RYLbcKto4T0qoj27s-q11s8Gkw7RnAHB7mLDfKi0- | spec/overlays/label/1.1 |
| meta (eng) | EPqTUOIetJiYsujCrpyZNEWbVSWFC453We8z-a0LJz0b | spec/overlays/meta/1.1 |
| unit | EK7z9stS364bYS5wpeRHQaa1IOvxO6TFM4CUySU7vfxY | spec/overlays/unit/1.1 |
| ordering | ECcjriotYQX1Yd6zk9pvdMH957uwiGXHiVQ3miemz2tu | community/overlays/adc/ordering/1.0 |
| sensitive | EKffDZwXUFxEJk1aHxIGKVPI-SDFDCso11QiXY21Hu2g | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:43:35

