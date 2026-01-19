---
layout: default  
title: Tianrui Zhang  
parent: UNIV6026 School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: CO2 Enriched Irrigation  
**Description**: Enriching the concentration of CO2 dissolved in nutrient solution used to grow lettuce in both vertical and NFT systems. CO2 enrichment levels were no enrichment, 50mg/L and 100mg/L. Growth parameters during and after harvest were measured.  
**Classification**: RDF401  
**Author**: Tianrui Zhang  
**Author Email**: tianrui@uoguelph.ca  
**Schema package SAID**: EGM9kFNdMuFoyxIcDzpughTQMLqg51AL_n9vIpbCCWUS 

[Download Schema](Zhang_CO2_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Obv_Date | Obv_Date | Date of observation |
| Treatment | Treatment | Treatment applied to the nutrient solution in the compartment |
| G_Method | G_Method | Growing method of the lettuce in the compartment |
| Compartment | Compartment | Compartment number |
| Row-Column | Row-Column | Row (if NFT) or column (if vertical) in each compartment |
| Location | Location | Location of plant in the row or column |
| Plant_ID | Plant_ID | ID of the lettuce plant |
| Irrig_Volume | Irrig_Volume | Volume of nutrient solution left in the irrigation tank. Measured daily |
| Irrig_pH | Irrig_pH | pH of nutrient solution left in the irrigation tank. Measured daily |
| Irrig_EC | Irrig_EC | Electrical conductivity of nutrient solution left in the irrigation tank. Measured daily |
| Irrig_CO2 | Irrig_CO2 | Concentration of dissolved CO2 in the nutrient solution. Measured daily |
| Post_Irrig_CO2 | Post_Irrig_CO2 | Concentration of dissolved CO2 in the nutrient solution immediately after it has interacted with plant roots. Measured weekly |
| Atmos_CO2 | Atmos_CO2 | Concentration of atmospheric CO2. Measured daily |
| Light_Intensity | Light_Intensity | Light intensity observed by the plants at the canopy level. Measured after transplating and before harvest. |
| Height | Height | Height of lettuce plants. Measured twice a week |
| Width | Width | Width of lettuce plants. Measured twice a week |
| Leaf_Number | Leaf_Number | Number of leaves on each lettuce plant. Measured twice a week |
| Stomata_Conduct | Stomata_Conduct | Stomata conductance of the largest leaf on each plant. Measured twice a week |
| LFresh_Weight | LFresh_Weight | Fresh weight of the leaves after harvest |
| LDry_Weight | LDry_Weight | Dry weight of the leaves |
| RFresh_Weight | RFresh_Weight | Fresh weight of the roots after harvest |
| RDry_Weight | RDry_Weight | Dry weight of the roots |
| Root_Length | Root_Length | Length of the roots after harvest |
| Leaf_Area | Leaf_Area | Leaf area of the largest leaf after harvest |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | CO2 Enriched Irrigation | Enriching the concentration of CO2 dissolved in nutrient solution used to grow lettuce in both vertical and NFT systems. CO2 enrichment levels were no enrichment, 50mg/L and 100mg/L. Growth parameters during and after harvest were measured. |

## Selection lists

### English

#### Compartment entry codes

| Entry code | Label |
| --- | --- |
| 1 | 1 |
| 2 | 2 |
| 3 | 3 |
| 4 | 4 |
| 5 | 5 |
| 6 | 6 |

#### G_Method entry codes

| Entry code | Label |
| --- | --- |
| NFT | NFT |
| Vertical | Vertical |

#### Location entry codes

| Entry code | Label |
| --- | --- |
| A | A |
| V | B |
| C | C |
| D | D |
| E | E |
| F | F |
| G | G |
| H | H |

#### Row-Column entry codes

| Entry code | Label |
| --- | --- |
| 1 | 1 |
| 2 | 2 |
| 3 | 3 |
| 4 | 4 |
| 5 | 5 |
| 6 | 6 |
| 7 | 7 |
| 8 | 8 |
| 9 | 9 |
| 10 | 10 |
| 11 | 11 |
| 12 | 12 |
| 13 | 13 |
| 14 | 14 |
| 15 | 15 |
| 16 | 16 |

#### Treatment entry codes

| Entry code | Label |
| --- | --- |
| No_Enrichment | No_Enrichment |
| 50mg/L | 50mg/L |
| 100mg/L | 100mg/L |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Obv_Date | false |  | DateTime |  |
| Treatment | false |  | Text |  |
| G_Method | false |  | Text |  |
| Compartment | false |  | Numeric |  |
| Row-Column | false |  | Numeric |  |
| Location | false |  | Text |  |
| Plant_ID | false |  | Text |  |
| Irrig_Volume | false | Liters (L) | Numeric |  |
| Irrig_pH | false |  | Numeric |  |
| Irrig_EC | false | µS/cm | Numeric |  |
| Irrig_CO2 | false | mg/L | Numeric |  |
| Post_Irrig_CO2 | false | mg/L | Numeric |  |
| Atmos_CO2 | false | PPM µmol/mol | Numeric |  |
| Light_Intensity | false | μmol/m2/s | Numeric |  |
| Height | false | Centimeters (cm) | Numeric |  |
| Width | false | cm | Numeric |  |
| Leaf_Number | false |  | Numeric |  |
| Stomata_Conduct | false | mmol/m2/s | Numeric |  |
| LFresh_Weight | false | Grams (g) | Numeric |  |
| LDry_Weight | false | g | Numeric |  |
| RFresh_Weight | false | g | Numeric |  |
| RDry_Weight | false | g | Numeric |  |
| Root_Length | false | cm | Numeric |  |
| Leaf_Area | false | cm2 | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Obv_Date | Obv_Date | Date of observation | Not a list |
| Treatment | Treatment | Treatment applied to the nutrient solution in the compartment | No_Enrichment, 50mg/L, 100mg/L |
| G_Method | G_Method | Growing method of the lettuce in the compartment | NFT, Vertical |
| Compartment | Compartment | Compartment number | 1, 2, 3, 4, 5, 6 |
| Row-Column | Row-Column | Row (if NFT) or column (if vertical) in each compartment | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16 |
| Location | Location | Location of plant in the row or column | A, B, C, D, E, F, G, H |
| Plant_ID | Plant_ID | ID of the lettuce plant | Not a list |
| Irrig_Volume | Irrig_Volume | Volume of nutrient solution left in the irrigation tank. Measured daily | Not a list |
| Irrig_pH | Irrig_pH | pH of nutrient solution left in the irrigation tank. Measured daily | Not a list |
| Irrig_EC | Irrig_EC | Electrical conductivity of nutrient solution left in the irrigation tank. Measured daily | Not a list |
| Irrig_CO2 | Irrig_CO2 | Concentration of dissolved CO2 in the nutrient solution. Measured daily | Not a list |
| Post_Irrig_CO2 | Post_Irrig_CO2 | Concentration of dissolved CO2 in the nutrient solution immediately after it has interacted with plant roots. Measured weekly | Not a list |
| Atmos_CO2 | Atmos_CO2 | Concentration of atmospheric CO2. Measured daily | Not a list |
| Light_Intensity | Light_Intensity | Light intensity observed by the plants at the canopy level. Measured after transplating and before harvest. | Not a list |
| Height | Height | Height of lettuce plants. Measured twice a week | Not a list |
| Width | Width | Width of lettuce plants. Measured twice a week | Not a list |
| Leaf_Number | Leaf_Number | Number of leaves on each lettuce plant. Measured twice a week | Not a list |
| Stomata_Conduct | Stomata_Conduct | Stomata conductance of the largest leaf on each plant. Measured twice a week | Not a list |
| LFresh_Weight | LFresh_Weight | Fresh weight of the leaves after harvest | Not a list |
| LDry_Weight | LDry_Weight | Dry weight of the leaves | Not a list |
| RFresh_Weight | RFresh_Weight | Fresh weight of the roots after harvest | Not a list |
| RDry_Weight | RDry_Weight | Dry weight of the roots | Not a list |
| Root_Length | Root_Length | Length of the roots after harvest | Not a list |
| Leaf_Area | Leaf_Area | Leaf area of the largest leaf after harvest | Not a list |

## Schema SAIDs

**Capture base**: EEBp6D-czQvX9xsHe_5c_Tgny-LFs_IN1-DzqOAerjhX

**Bundle**: ELpXuaBowXn7FzJgT2WSJZlgc7vje7GizXnzvyuzwiML

**Package**: EGM9kFNdMuFoyxIcDzpughTQMLqg51AL_n9vIpbCCWUS

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | EIAvFU5yIykqKElWM3GX5Be7waiVOz_ydVbjl2VInHWJ | spec/overlays/entry/1.1 |
| entry_code | EFcLs_Hkn9hqRjSdwgdkSsvAVE0AHuC3OvnzkhtpiPwE | spec/overlays/entry_code/1.1 |
| information (eng) | EH6q0MZRY6raDu_2vNvbVr15QTyCh4RNZpOtkJ9Ct7uH | spec/overlays/information/1.1 |
| label (eng) | EMrFNKk-J8BnJADG70b5H3fiKuMIgAjXuXWawBTtdZIr | spec/overlays/label/1.1 |
| meta (eng) | EAvrcUDB3hufxxT5l0VDfAhwUXXR7m-On3kEiJurTXQB | spec/overlays/meta/1.1 |
| unit | ENt_o7Al45PpER9X8ZAkEq_X_kvLYdhTyVVQXQFiXRLn | spec/overlays/unit/1.1 |
| ordering | EJFJhUibWWQbRx3r0n19X2DhlGqehvUFXkoRmr2hjtBX | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:53:01

