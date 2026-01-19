---
layout: default  
title: Chloe El Hani 
parent: School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Sweep Sampling for Arthropods in Solanaceous Crops  
**Description**: Count data of orders of arthropods caught in sweep sampling efforts conducted in solanaceous crops of southern Ontario during the field season.  
**Classification**: RDF105  
**Author**: Chloe El Hani  
**Author Email**: celhani@uoguelph.ca  
**Schema package SAID**: EA0b3tdu1DGv5ldhcD_sycAmywFu7w9dhBGctTYifeOt  

[Download Schema](Hani_Sweep_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Date | Date | Date of sampling identification |
| Name | Name | Name of person conducting sample identification |
| DateCollected | Date collected | Date the sweep sampling was conducted |
| Location | Location | Location of field site in which the sweep sampling was conducted |
| Section | Section | One of 2 transects in field site, A or B |
| SweepNo | Sweep Number | Number of the sweep conducted. Each transect had 2 sweeps conducted each week. |
| Order | Order of Insect or Class Arachnida | Order of insect identified, or class Arachnida |
| LifeStage | Life Stage | Life stage of insect/arachnid identified |
| NoOfIndividuals | Number of Individuals | Number of individuals of that specific Order and life stage identified |
| Comments | Comments | Space for person conducting the sample identification to add additional comments about data entry |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Sweep Sampling for Arthropods in Solanaceous Crops | Count data of orders of arthropods caught in sweep sampling efforts conducted in solanaceous crops of southern Ontario during the field season. |

## Selection lists

### English

#### LifeStage entry codes

| Entry code | Label |
| --- | --- |
| Adult | Adult lifestage |
| Egg | Egg lifestage |
| Nymph | Nymph lifestage |
| Larvae | Larvae lifestage |
| Pupae | Pupae lifestage |

#### Location entry codes

| Entry code | Label |
| --- | --- |
| Elora | Site A, Location Elora |
| Alliston | Site B, Location Alliston |

#### Order entry codes

| Entry code | Label |
| --- | --- |
| Arachnida | Class Arachnida |
| Coleoptera | Order Coleoptera, the beetles |
| Collembola | Order Collembola, the springtails |
| Dermaptera | Order Dermaptera, the earwigs |
| Diptera | Order Diptera, the flies |
| Hemiptera | Order Hemiptera, the true bugs |
| Hymenoptera | Order Hymenoptera, the bees, wasps and ants |
| Lepidoptera | Order Lepidoptera, the moths and butterflies |
| Neuroptera | Order Neuroptera, the lacewings |
| Odonata | Order Odonata, the dragonflies and damselfies |
| Orthoptera | Order Orthoptera, the grasshoppers, locusts and crickets |
| Thysanoptera | Order Thysanoptera, the thrips |

#### Section entry codes

| Entry code | Label |
| --- | --- |
| A | Transect A |
| B | Transect B |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| Date | false |  | DateTime |  | true |
| Name | true |  | Text |  | true |
| DateCollected | false |  | DateTime |  | true |
| Location | true |  | Text |  | true |
| Section | false |  | Text |  | true |
| SweepNo | false |  | Numeric |  | true |
| Order | false |  | Text |  | true |
| LifeStage | false |  | Text |  | true |
| NoOfIndividuals | false |  | Numeric |  | true |
| Comments | false |  | Text |  | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Date | Date | Date of sampling identification | Not a list |
| Name | Name | Name of person conducting sample identification | Not a list |
| DateCollected | Date collected | Date the sweep sampling was conducted | Not a list |
| Location | Location | Location of field site in which the sweep sampling was conducted | Site A, Location Elora, Site B, Location Alliston |
| Section | Section | One of 2 transects in field site, A or B | Transect A, Transect B |
| SweepNo | Sweep Number | Number of the sweep conducted. Each transect had 2 sweeps conducted each week. | Not a list |
| Order | Order of Insect or Class Arachnida | Order of insect identified, or class Arachnida | Class Arachnida, Order Coleoptera, the beetles, Order Collembola, the springtails, Order Dermaptera, the earwigs, Order Diptera, the flies, Order Hemiptera, the true bugs, Order Hymenoptera, the bees, wasps and ants, Order Lepidoptera, the moths and butterflies, Order Neuroptera, the lacewings, Order Odonata, the dragonflies and damselfies, Order Orthoptera, the grasshoppers, locusts and crickets, Order Thysanoptera, the thrips |
| LifeStage | Life Stage | Life stage of insect/arachnid identified | Adult lifestage, Egg lifestage, Nymph lifestage, Larvae lifestage, Pupae lifestage |
| NoOfIndividuals | Number of Individuals | Number of individuals of that specific Order and life stage identified | Not a list |
| Comments | Comments | Space for person conducting the sample identification to add additional comments about data entry | Not a list |

## Schema SAIDs

**Capture base**: EEtboi4SVX-Oj43A-rtGuBZWN87tm929n2TpCUQbrLBR

**Bundle**: EO0-55D3reJWQa5gIvj8pzZRgiiesCKGwlG_gg63L22L

**Package**: EA0b3tdu1DGv5ldhcD_sycAmywFu7w9dhBGctTYifeOt

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EM0tKbd7rDfb72wJHnMb6bdsJJhgHPxvyxHfxbQHLskB | spec/overlays/conformance/1.1 |
| entry (eng) | EAqobpvbyw884ghXmYGsCeC32ZSzmFKu8a0TITzH_F0y | spec/overlays/entry/1.1 |
| entry_code | EMw3jm-cDPrzCoRmRCmwGYhy_rNzkgPtuaM4ceQvpTwa | spec/overlays/entry_code/1.1 |
| information (eng) | EEywmy8rU1T3sT4A6xILzGwMr50iF-SNU-a0kCICQysX | spec/overlays/information/1.1 |
| label (eng) | EBA4cfBTspWW1WuVabyxplA2LDjeBCaSrAS0EW16r7ZF | spec/overlays/label/1.1 |
| meta (eng) | EHOPdvRNH5YxHqShqvEqPeBcJT6zGzj2qOlmpXXtCS5B | spec/overlays/meta/1.1 |
| ordering | EJO6RHPUYjxQQHRxIH78JlxKLipeqgNzwG3Pnr1Pageh | community/overlays/adc/ordering/1.0 |
| sensitive | EAb8-TlVJMfBDEVysbNeuJSmdJPbY8MpImupWlr9EG8U | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-15 11:35:24

