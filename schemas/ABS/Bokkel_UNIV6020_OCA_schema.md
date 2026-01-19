---
layout: default  
title: Emmeline te Bokkel
parent: UNIV6026 Animal Biosciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: UNIV6020  
**Description**: This schema represents data collected from 99 dairy farms across Ontario, and indicates settings used in robotic milking systems to reduce robot and feed access as cows are nearing the end of their lactation  
**Classification**: RDF402  
**Author**: Emmeline te Bokkel  
**Author Email**: etebokke@uoguelph.ca  
**Schema package SAID**: EJNElGQ1iYssx-MZzUsNKXuOigPcAvR_8YDGSKv_iNJF 

[Download Schema](Bokkel_UNIV6020_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| farmID | Farm identification number | number used to identify the farm corresponding to the settings recorded |
| dbdryoff | days before dryoff | number of days before dry off that milking robot access is reduced |
| maxmilkings | maximum number of milkings | maximum number of times that a cow is permitted to visit the robot per day |
| yield | milk yield | based off the predicted average yield of a cow per milking, this setting will let a cow through the robot if she is expected to produce more than a certain quantity of milk |
| minmilkings | minimum number of milkings | minimum permitted number of times that a cow can visit a robot per day |
| DIM | days in milk | days in milk when the feed allocation is based on milk yield |
| feedmin | minimm feed allocation | minimum feed allocation based on milk yield |
| feedmax | maximum feed allocation | maximum feed allocation based on milk yield |
| feeddbdryoff1 | days before dry off of first feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the second time |
| feeddbdryoff2 | days before dry off of second feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the second time |
| feed1 | quantity of feed after reduction | quantity of feed the cow will receive during the period before dry off |
| feeddbdryoff3 | days before dry off of third feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the final time |
| feed2 | final quantity of feed permitted | final quantity of feed the cow is permitted to consume right before going dry |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | UNIV6020 | This schema represents data collected from 99 dairy farms across Ontario, and indicates settings used in robotic milking systems to reduce robot and feed access as cows are nearing the end of their lactation |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| farmID | false |  | Numeric |  | true |
| dbdryoff | false | Days Before Dryoff | Numeric |  | true |
| maxmilkings | false |  | Numeric |  | true |
| yield | false | kg | Numeric |  | true |
| minmilkings | false |  | Numeric |  | true |
| DIM | false | Days | Numeric |  | true |
| feedmin | false | kg | Numeric |  | true |
| feedmax | false | kg | Numeric |  | true |
| feeddbdryoff1 | false | Days | Numeric |  | true |
| feeddbdryoff2 | false | Days Before Dryoff | Numeric |  | true |
| feed1 | false | kg | Numeric |  | true |
| feeddbdryoff3 | false | Days Before Dryoff | Numeric |  | true |
| feed2 | false | kg | Numeric |  | true |

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
| farmID | Farm identification number | number used to identify the farm corresponding to the settings recorded | Not a list |
| dbdryoff | days before dryoff | number of days before dry off that milking robot access is reduced | Not a list |
| maxmilkings | maximum number of milkings | maximum number of times that a cow is permitted to visit the robot per day | Not a list |
| yield | milk yield | based off the predicted average yield of a cow per milking, this setting will let a cow through the robot if she is expected to produce more than a certain quantity of milk | Not a list |
| minmilkings | minimum number of milkings | minimum permitted number of times that a cow can visit a robot per day | Not a list |
| DIM | days in milk | days in milk when the feed allocation is based on milk yield | Not a list |
| feedmin | minimm feed allocation | minimum feed allocation based on milk yield | Not a list |
| feedmax | maximum feed allocation | maximum feed allocation based on milk yield | Not a list |
| feeddbdryoff1 | days before dry off of first feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the second time | Not a list |
| feeddbdryoff2 | days before dry off of second feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the second time | Not a list |
| feed1 | quantity of feed after reduction | quantity of feed the cow will receive during the period before dry off | Not a list |
| feeddbdryoff3 | days before dry off of third feed reduction | number of days before the cow goes dry that the quantity of feed is dropped for the final time | Not a list |
| feed2 | final quantity of feed permitted | final quantity of feed the cow is permitted to consume right before going dry | Not a list |

## Schema SAIDs

**Capture base**: ED8AUtq_pcbYVf2tkOJ4LTvz57w_9OxZs1aem6hfzmHM

**Bundle**: EBad67Sxls67glv14PyHikVaZHGxCLCgv1zDOQ1YlLsV

**Package**: EJNElGQ1iYssx-MZzUsNKXuOigPcAvR_8YDGSKv_iNJF

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | EFJEcKKRciAJ6g43-m8u6yZbS_REEe5zuYUWJCr_GnlS | spec/overlays/conformance/1.1 |
| information (eng) | EHqMl05ZTxo7EJzQZJz6nnZRDmn5d8aYxib754Wob1ZE | spec/overlays/information/1.1 |
| label (eng) | EEQ4-zFC3hsk-lBVdok3qO8iHB4o4aZLkxiCCIJFi93A | spec/overlays/label/1.1 |
| meta (eng) | EDdiwrmkKjj0vSVOaI_4qlAZAo3k5hOX9bOU6kAaBSDr | spec/overlays/meta/1.1 |
| unit | ECdOA4c6a9xdpR70hMiyQNAvTbT4s3Hz1wqEjul10PRF | spec/overlays/unit/1.1 |
| ordering | EMmzPcJJ-NOqAM_MOJP_ACOjz9er05W_jOWtSFQ6YBy3 | community/overlays/adc/ordering/1.0 |
| unit_framing | EN_gmCaCEyOGn-xrHwoIUouI8bvJqKqhtC0AHK34l4qx | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-01-15 10:38:05

