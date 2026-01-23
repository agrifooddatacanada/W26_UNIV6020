---
layout: default  
title: Bianca Garcia
parent: Animal Biosciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Sow Nutrition and Fetal Development Dataset  
**Description**: This dataset contains laboratory measurements of dry matter and ash content from tissue samples collected from late-gestation sows. Samples include feed, carcass, viscera, uterus, placenta, fetus, and mammary glands.Each sample includes measurements used to calculate dry matter percentage and ash percentage.  
**Classification**: RDF402  
**Author**: Bianca Garcia  
**Author Email**: bgarcia@uoguelph.ca  
**Schema package SAID**: EE_XTnPBijt7Bh3FgxhjNeoNyxg-4nQXg-C7i2QXhq0t  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Sample | Sample ID | Unique identifier assigned to each tissue sample |
| Crucible | Crucible ID | Identification number of the crucible used for drying and ashing the sample |
| CrucibleWeight | Empty crucible weight | Weight of the empty crucible before adding the sample (g) |
| SampleWeight | Wet sample weight | Weight of the fresh tissue sample before drying (g) |
| DriedWeight | Dried sample weight | Weight of the tissue sample after oven drying (g) |
| DM | Dry matter percentage | Percentage of dry matter in the sample calculated from wet and dried weights |
| AvgDM | Mean dry matter percentage | Average dry matter percentage calculated from replicate samples |
| DMCV | Dry matter coefficient of variation | Coefficient of variation of dry matter percentage across replicates |
| AshedWeight | Ash residue weight | Weight of inorganic residue remaining after ashing the dried sample (g) |
| Ash | Ash percentage | Percentage of ash (mineral content) in the sample |
| AvgAsh | Mean ash percentage | Average ash percentage calculated from replicate samples |
| AshCV | Ash coefficient of variation | Coefficient of variation of ash percentage across replicate samples |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Sow Nutrition and Fetal Development Dataset | This dataset contains laboratory measurements of dry matter and ash content from tissue samples collected from late-gestation sows. Samples include feed, carcass, viscera, uterus, placenta, fetus, and mammary glands.Each sample includes measurements used to calculate dry matter percentage and ash percentage. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Unit Framing |
| --- | --- | --- | --- | --- | --- |
| Sample | true |  | Text |  |
| Crucible | true |  | Numeric |  |
| CrucibleWeight | true | g | Numeric |  | g |
| SampleWeight | true | g | Numeric |  | g |
| DriedWeight | true | g | Numeric |  | g |
| DM | true | % | Numeric |  | % |
| AvgDM | true | % | Numeric |  | % |
| DMCV | true | % | Numeric |  | % |
| AshedWeight | true | g | Numeric |  | g |
| Ash | true | % | Numeric |  | % |
| AvgAsh | true | % | Numeric |  | % |
| AshCV | true | % | Numeric |  | % |

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
| Sample | Sample ID | Unique identifier assigned to each tissue sample | Not a list |
| Crucible | Crucible ID | Identification number of the crucible used for drying and ashing the sample | Not a list |
| CrucibleWeight | Empty crucible weight | Weight of the empty crucible before adding the sample (g) | Not a list |
| SampleWeight | Wet sample weight | Weight of the fresh tissue sample before drying (g) | Not a list |
| DriedWeight | Dried sample weight | Weight of the tissue sample after oven drying (g) | Not a list |
| DM | Dry matter percentage | Percentage of dry matter in the sample calculated from wet and dried weights | Not a list |
| AvgDM | Mean dry matter percentage | Average dry matter percentage calculated from replicate samples | Not a list |
| DMCV | Dry matter coefficient of variation | Coefficient of variation of dry matter percentage across replicates | Not a list |
| AshedWeight | Ash residue weight | Weight of inorganic residue remaining after ashing the dried sample (g) | Not a list |
| Ash | Ash percentage | Percentage of ash (mineral content) in the sample | Not a list |
| AvgAsh | Mean ash percentage | Average ash percentage calculated from replicate samples | Not a list |
| AshCV | Ash coefficient of variation | Coefficient of variation of ash percentage across replicate samples | Not a list |

## Schema SAIDs

**Capture base**: EDgzy12IklLxyYT3fyqRdEZRLbCIqmTsgudtIxjBZ7wO

**Bundle**: EE8xBwoJnlv9D4tUOo3HdEHbOmqoICXaCIkxw1QE-Vu8

**Package**: EE_XTnPBijt7Bh3FgxhjNeoNyxg-4nQXg-C7i2QXhq0t

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EMgG18g0sTaez3bisEWWmjn6uoIU3H4p_MGKvyrY2vh7 | spec/overlays/information/1.1 |
| label (eng) | EB99YOcwUxcY-6TTimUXTHW9r00dBoiMCnnTe0RhFhyN | spec/overlays/label/1.1 |
| meta (eng) | ED7kKLsRnZXgq807ZJ1kwRwSI1TTeizTjZy5VGnt7x3B | spec/overlays/meta/1.1 |
| unit | ECHb9eAhN9HC_OUThWXL8PMrU8s7VK0gWInqKLB7X8lL | spec/overlays/unit/1.1 |
| ordering | EI28MY67b-AZo7tgbe-zgiMh-t1Ps_7DBTRrbvC2tB2E | community/overlays/adc/ordering/1.0 |
| sensitive | EDLzKmRnZvYgKzY97z4wbfCK-9hLExStX3rNRMAeEFFq | community/overlays/adc/sensitive/1.0 |
| unit_framing | EFGc4anNixVsTFVtVpjONcHYJ_pgE5UV6rmRWLE3035l | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-23 10:12:08

