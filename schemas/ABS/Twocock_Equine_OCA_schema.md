---
layout: default  
title: Caitlyn Twocock - Equine Digestibility Schema 
parent: UNIV6026 Animal Biosciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Equine Digestibility Schema  
**Description**: This schema stores equine nutrient digestibility data compiled from published research literature. It contains methodology used, nutrient compositions within the feeds and digestibility coefficients.  
**Classification**: RDF402  
**Author**: Caitlyn Twocock  
**Author Email**: ctwocock@uoguelph.ca  
**Schema package SAID**: EKwbMhwGZr783T1yKm48ZuriFc9dAn8GFnjpgNca2jmZ 

[Download Schema](Twocock_Equine_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Obs | Obs | This is the number of observations within that the database contains. |
| Exp | Exp | This describes the certain article with a number to show it as one experiment within the database. |
| Ref | Ref | This is the reference/citation for the article being used. |
| Ing | Ing | This is the ingredient within the experiments used. |
| Hay_cut | Hay_cut | This shares what cut of hay was used within experiments. |
| yeastSupp | yeastSupp | This acknowledges whether a yeast supplement was used in the study. |
| digMarker | digMarker | Shares if a digestibility marker was used by saying what one it was. |
| Forage_class | Forage_class | Explains what classification of forage is in the row. For example, alfalfa hay, timothy grass or etc. |
| Forage_type | Forage_type | Shows the type of hay it is such as legume, grass, or mixed. |
| Forage_pDiet | Forage_pDiet | Lets us know the percentage of the diet is forage. |
| Diet_desc | Diet_desc | Gives a description of the diet. |
| Ing_class | Ing_class | Classifies the experiment/diet as forage, concentrate, or mixed diets. |
| n | n | Number of horses used in the study. |
| Breed | Breed | Breed of horses within the study. |
| Exercise | Exercise | What type of exercise might have been used (maintenance, moderate, or intense). |
| BW_kg | BW_kg | Body weight in kilograms. |
| BW_kg_SEM | BW_kg_SEM | Standard error of the mean for body weight in kilograms. |
| Age | Age | Age of the animal. |
| Sex | Sex | Sex of the animal (stud, mare, gelding, or mixed) |
| Meal_Type | Meal_Type | How many times the horses got feed within a day. |
| DMI_kgd | DMI_kgd | Dry matter intake in kilograms per day. |
| DMI_kgd_SEM | DMI_kgd_SEM | Standard error of the mean for dry matter intake in kilograms per day. |
| DM_p | DM_p | Percent of dry matter in the diet composition. |
| DM_p_SEM | DM_p_SEM | Standard error of the mean for percent of dry matter. |
| OM_p | OM_p | Percent of organic matter in the diet composition. |
| OM_p_SEM | OM_p_SEM | Standard error of the mean for percent of organic matter. |
| CP_p | CP_p | Percent of crude protein in the diet composition. |
| CP_p_SEM | CP_p_SEM | Standard error of the mean for percent of crude protein. |
| EE_p | EE_p | Percent of fat in the diet composition. |
| EE_p_SEM | EE_p_SEM | Standard error of the mean for percent of fat. |
| CF_p | CF_p | Percent of crude fiber in the diet composition. |
| CF_p_SEM | CF_p_SEM | Standard error of the mean for percent of crude fiber. |
| NDF_p | NDF_p_SEM | Percent of neutral detergent fiber in the diet composition. |
| NDF_p_SEM | NDF_p_SEM | Standard error of the mean for percent of neutral detergent fiber. |
| ADF_p | ADF_p | Percent of acid detergent fiber in the diet composition. |
| ADF_p_SEM | ADF_p_SEM | Standard error of the mean for percent of acid detergent fiber. |
| Lignin_p | Lignin_p | Percent of lignin in the diet composition. |
| Lignin_p_SEM | Lignin_p_SEM | Standard error of the mean for percent of Lignin. |
| NFC_p | NFC_p | Percent of non-fibrous carbohydrates in the diet composition. |
| NFC_p_SEM | NFC_p_SEM | Standard error of the mean for percent of non-fibrous carbohydrates. |
| NSC_p | NSC_p | Percent of non-structural carbohydrates in the diet composition. |
| NSC_p_SEM | NSC_p_SEM | Standard error of the mean for percent of non-structural carbohydrates. |
| WSC_p | WSC_p | Percent of water soluble carbohydrates in the diet composition. |
| WSC_p_SEM | WSC_p_SEM | Standard error of the mean for percent of water soluble carbohydrates. |
| ESC_p | ESC_p | Percent of ethanol soluble carbohydrates in the diet composition. |
| ESC_p_SEM | ESC_p_SEM | Standard error of the mean for percent of ethanol soluble carbohydrates. |
| ST_p | ST_p | Percent of starch in the diet composition. |
| ST_p_SEM | ST_p_SEM | Standard error of the mean for percent of starch. |
| SU_p | SU_p | Percent of sugar in the diet composition. |
| ASH_p | ASH_p | Percent of ash in the diet composition |
| ASH_p_SEM | ASH_p_SEM | Standard error of the mean for percent of ash. |
| AIA_p | AIA_p | Percent of acid insoluble ash in the diet composition. |
| GE_Mcalkg | GE_Mcalkg | Gross energy by megacalories per kilogram in the diet composition. |
| GE_Mcalkg_SEM | GE_Mcalkg_SEM | Standard error of the mean for gross energy by megacalories per kilogram. |
| DE_Mcalkg | DE_Mcalkg | Digestible energy by megacalories per kilogram in the diet composition. |
| DE_Mcalkg_SEM | DE_Mcalkg_SEM | Standard error of the mean for digestible energy by megacalories per kilogram. |
| Digest_compartment | Digest_compartment | Where in the digestive tract nutrients were digested or if it was total tract. |
| adDM_p | adDM_p | Percent of apparent digestibility of dry matter. |
| adDM_p_SEM | adDM_p_SEM | Standard error of the mean for percent of apparent digestibility of dry matter. |
| adDM_p_RMSE | adDM_p_RMSE | Root mean square error for percent of apparent digestibility of dry matter. |
| adOM_p | adOM_p | Percent of apparent digestibility of organic matter. |
| adOM_p_SEM | adOM_p_SEM | Standard error of the mean for percent of apparent digestibility of organic matter. |
| adOM_p_RMSE | adOM_p_RMSE | Root mean square error for percent of apparent digestibility of organic matter. |
| adCP_p | adCP_p | Percent of apparent digestibility of crude protein. |
| adCP_p_SEM | adCP_p_SEM | Standard error of the mean for percent of apparent digestibility of crude protein. |
| adCP_p_RMSE | adCP_p_RMSE | Root mean square error for percent of apparent digestibility of crude protein. |
| adN_p | adN_p | Percent of apparent digestibility of nitrogen. |
| adN_p_SEM | adN_p_SEM | Standard error of the mean for percent of apparent digestibility of nitrogen. |
| adDCP_p | adDCP_p | Percent of apparent digestibility of daily crude protein. |
| adDCP_p_SEM | adDCP_p_SEM | Standard error of the mean for percent of apparent digestibility of daily crude protein. |
| adEE_p | adEE_p | Percent of apparent digestibility of fat. |
| adEE_p_SEM | adEE_p_SEM | Standard error of the mean for percent of apparent digestibility of fat. |
| adNFE_p | adNFE_p | Percent of apparent digestibility of nitrogen free extract. |
| adNFE_p_SEM | adNFE_p_SEM | Standard error of the mean for percent of apparent digestibility of nitrogen free extract. |
| adCF_p | adCF_p | Percent of apparent digestibility of crude fiber. |
| adCF_p_SEM | adCF_p | Standard error of the mean for percent of apparent digestibility of crude fiber. |
| adCF_p_RMSE | adCF_p_RMSE | Root mean square error for percent of apparent digestibility of crude fiber. |
| adNDF_p | adNDF_p | Percent of apparent digestibility of neutral detergent fiber. |
| adNDF_p_SEM | adNDF_p_SEM | Standard error of the mean for percent of apparent digestibility of neutral detergent fiber. |
| adNDF_p_RMSE | adNDF_p_RMSE | Root mean square error for percent of apparent digestibility of neutral detergent fiber. |
| adADF_p | adADF_p | Percent of apparent digestibility of acid detergent fiber. |
| adADF_p_SEM | adADF_p_SEM | Standard error of the mean for percent of apparent digestibility of acid detergent fiber. |
| adADF_p_RMSE | adADF_p_RMSE | Root mean square error for percent of apparent digestibility of acid detergent fiber. |
| adLignin_p | adLignin_p | Percent of apparent digestibility of lignin. |
| adLignin_p_SEM | adLignin_p_SEM | Standard error of the mean for percent of apparent digestibility of lignin. |
| adST_p | adST_p | Percent of apparent digestibility of starch. |
| adST_p_SEM | adST_p_SEM | Standard error of the mean for percent of apparent digestibility of starch. |
| adST_p_RMSE | adST_p_RMSE | Root mean square error for percent of apparent digestibility of starch. |
| adWSCp | adWSCp | Percent of apparent digestibility of water soluble carbohydrates. |
| adWSCp_SEM | adWSCp_SEM | Standard error of the mean for percent of apparent digestibility of water soluble carbohydrates. |
| adESCp | adESCp | Percent of apparent digestibility of ethanol soluble carbohydrates. |
| adESCp_SEM | adESCp_SEM | Standard error of the mean for percent of apparent digestibility of ethanol soluble carbohydrates. |
| adSU_p | adSU_p | Percent of apparent digestibility of sugar. |
| adSU_p_SEM | adSU_p_SEM | Standard error of the mean for percent of apparent digestibility of sugar. |
| adNSC_p | adNSC_p | Percent of apparent digestibility of non-structural carbohydrates. |
| adNSC_p_SEM | adNSC_p_SEM | Standard error of the mean for percent of apparent digestibility of non-structural carbohydrates. |
| adTDNDM | adTDNDM | Apparent digestibility of total digestible nutrients based on dry matter. |
| adTDNDM_SEM | adTDNDM_SEM | Standard error of the mean for apparent digestibility of total digestible nutrients based on dry matter. |
| adGE_p | adGE_p | Percent of apparent digestibility of gross energy. |
| adGE_p_SEM | adGE_p_SEM | Standard error of the mean for percent of apparent digestibility of gross energy. |
| adEnergy_p | adEnergy_p | Percent of apparent digestibility of energy. |
| adEnergy_p_SEM | adEnergy_p_SEM | Standard error of the mean for percent of apparent digestibility of energy. |
| adEnergy_p_RMSE | adEnergy_p_RMSE | Root mean square error for percent of apparent digestibility of energy. |
| adGEMJkgDM | adGEMJkgDM | Apparent digestibility of gross energy in megajoules per kilogram based on dry matter. |
| adGEMJkgDM_SEM | adGEMJkgDM_SEM | Standard error of the mean for apparent digestibility of gross energy in megajoules per kilogram based on dry matter. |
| adDE_p | adDE_p | Percent of apparent digestibility of digestible energy. |
| adDE_p_SEM | adDE_p_SEM | Standard error of the mean for percent of apparent digestibility of digestible energy. |
| adDE_Mcalkg | adDE_Mcalkg | Apparent digestibility of digestible energy in megacalories per kilogram. |
| adDE_Mcalkg_SEM | adDE_Mcalkg_SEM | Standard error of the mean for apparent digestibility of digestible energy in megacalories per kilogram. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Equine Digestibility Schema | This schema stores equine nutrient digestibility data compiled from published research literature. It contains methodology used, nutrient compositions within the feeds and digestibility coefficients. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Obs | false |  | Numeric |  |
| Exp | false |  | Numeric |  |
| Ref | false |  | Text |  |
| Ing | false |  | Text |  |
| Hay_cut | false |  | Text |  |
| yeastSupp | false |  | Boolean |  |
| digMarker | false |  | Text |  |
| Forage_class | false |  | Text |  |
| Forage_type | false |  | Text |  |
| Forage_pDiet | false | % | Numeric |  |
| Diet_desc | false |  | Text |  |
| Ing_class | false |  | Text |  |
| n | false |  | Numeric |  |
| Breed | false |  | Text |  |
| Exercise | false |  | Text |  |
| BW_kg | false | kg | Numeric |  |
| BW_kg_SEM | false | kg | Numeric |  |
| Age | false |  | Numeric |  |
| Sex | false |  | Text |  |
| Meal_Type | false |  | Text |  |
| DMI_kgd | false | kg/d | Numeric |  |
| DMI_kgd_SEM | false | kg/d | Numeric |  |
| DM_p | false | % | Numeric |  |
| DM_p_SEM | false | % | Numeric |  |
| OM_p | false | % | Numeric |  |
| OM_p_SEM | false | % | Numeric |  |
| CP_p | false | % | Numeric |  |
| CP_p_SEM | false | % | Numeric |  |
| EE_p | false | % | Numeric |  |
| EE_p_SEM | false | % | Numeric |  |
| CF_p | false | % | Numeric |  |
| CF_p_SEM | false | % | Numeric |  |
| NDF_p | false | % | Numeric |  |
| NDF_p_SEM | false | % | Numeric |  |
| ADF_p | false | % | Numeric |  |
| ADF_p_SEM | false | % | Numeric |  |
| Lignin_p | false | % | Numeric |  |
| Lignin_p_SEM | false | % | Numeric |  |
| NFC_p | false | % | Numeric |  |
| NFC_p_SEM | false | % | Numeric |  |
| NSC_p | false | % | Numeric |  |
| NSC_p_SEM | false | % | Numeric |  |
| WSC_p | false | % | Numeric |  |
| WSC_p_SEM | false | % | Numeric |  |
| ESC_p | false | % | Numeric |  |
| ESC_p_SEM | false | % | Numeric |  |
| ST_p | false | % | Numeric |  |
| ST_p_SEM | false | % | Numeric |  |
| SU_p | false | % | Numeric |  |
| ASH_p | false | % | Numeric |  |
| ASH_p_SEM | false | % | Numeric |  |
| AIA_p | false | % | Numeric |  |
| GE_Mcalkg | false | Mcal/kg | Numeric |  |
| GE_Mcalkg_SEM | false | Mcal/kg | Numeric |  |
| DE_Mcalkg | false | Mcal/kg | Numeric |  |
| DE_Mcalkg_SEM | false | Mcal/kg | Numeric |  |
| Digest_compartment | false |  | Text |  |
| adDM_p | false | % | Numeric |  |
| adDM_p_SEM | false | % | Numeric |  |
| adDM_p_RMSE | false | % | Numeric |  |
| adOM_p | false | % | Numeric |  |
| adOM_p_SEM | false | % | Numeric |  |
| adOM_p_RMSE | false | % | Numeric |  |
| adCP_p | false | % | Numeric |  |
| adCP_p_SEM | false | % | Numeric |  |
| adCP_p_RMSE | false | % | Numeric |  |
| adN_p | false | % | Numeric |  |
| adN_p_SEM | false | % | Numeric |  |
| adDCP_p | false | % | Numeric |  |
| adDCP_p_SEM | false | % | Numeric |  |
| adEE_p | false | % | Numeric |  |
| adEE_p_SEM | false | % | Numeric |  |
| adNFE_p | false | % | Numeric |  |
| adNFE_p_SEM | false | % | Numeric |  |
| adCF_p | false | % | Numeric |  |
| adCF_p_SEM | false | % | Numeric |  |
| adCF_p_RMSE | false | % | Numeric |  |
| adNDF_p | false | % | Numeric |  |
| adNDF_p_SEM | false | % | Numeric |  |
| adNDF_p_RMSE | false | % | Numeric |  |
| adADF_p | false | % | Numeric |  |
| adADF_p_SEM | false | % | Numeric |  |
| adADF_p_RMSE | false | % | Numeric |  |
| adLignin_p | false | % | Numeric |  |
| adLignin_p_SEM | false | % | Numeric |  |
| adST_p | false | % | Numeric |  |
| adST_p_SEM | false | % | Numeric |  |
| adST_p_RMSE | false | % | Numeric |  |
| adWSCp | false | % | Numeric |  |
| adWSCp_SEM | false | % | Numeric |  |
| adESCp | false | % | Numeric |  |
| adESCp_SEM | false | % | Numeric |  |
| adSU_p | false | % | Numeric |  |
| adSU_p_SEM | false | % | Numeric |  |
| adNSC_p | false | % | Numeric |  |
| adNSC_p_SEM | false | % | Numeric |  |
| adTDNDM | false | % | Numeric |  |
| adTDNDM_SEM | false | % | Numeric |  |
| adGE_p | false | % | Numeric |  |
| adGE_p_SEM | false | % | Numeric |  |
| adEnergy_p | false | % | Numeric |  |
| adEnergy_p_SEM | false | % | Numeric |  |
| adEnergy_p_RMSE | false | % | Numeric |  |
| adGEMJkgDM | false | MJ/kg DM | Numeric |  |
| adGEMJkgDM_SEM | false | MJ/kg DM | Numeric |  |
| adDE_p | false | % | Numeric |  |
| adDE_p_SEM | false | % | Numeric |  |
| adDE_Mcalkg | false | Mcal/kg | Numeric |  |
| adDE_Mcalkg_SEM | false | Mcal/kg | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Obs | Obs | This is the number of observations within that the database contains. | Not a list |
| Exp | Exp | This describes the certain article with a number to show it as one experiment within the database. | Not a list |
| Ref | Ref | This is the reference/citation for the article being used. | Not a list |
| Ing | Ing | This is the ingredient within the experiments used. | Not a list |
| Hay_cut | Hay_cut | This shares what cut of hay was used within experiments. | Not a list |
| yeastSupp | yeastSupp | This acknowledges whether a yeast supplement was used in the study. | Not a list |
| digMarker | digMarker | Shares if a digestibility marker was used by saying what one it was. | Not a list |
| Forage_class | Forage_class | Explains what classification of forage is in the row. For example, alfalfa hay, timothy grass or etc. | Not a list |
| Forage_type | Forage_type | Shows the type of hay it is such as legume, grass, or mixed. | Not a list |
| Forage_pDiet | Forage_pDiet | Lets us know the percentage of the diet is forage. | Not a list |
| Diet_desc | Diet_desc | Gives a description of the diet. | Not a list |
| Ing_class | Ing_class | Classifies the experiment/diet as forage, concentrate, or mixed diets. | Not a list |
| n | n | Number of horses used in the study. | Not a list |
| Breed | Breed | Breed of horses within the study. | Not a list |
| Exercise | Exercise | What type of exercise might have been used (maintenance, moderate, or intense). | Not a list |
| BW_kg | BW_kg | Body weight in kilograms. | Not a list |
| BW_kg_SEM | BW_kg_SEM | Standard error of the mean for body weight in kilograms. | Not a list |
| Age | Age | Age of the animal. | Not a list |
| Sex | Sex | Sex of the animal (stud, mare, gelding, or mixed) | Not a list |
| Meal_Type | Meal_Type | How many times the horses got feed within a day. | Not a list |
| DMI_kgd | DMI_kgd | Dry matter intake in kilograms per day. | Not a list |
| DMI_kgd_SEM | DMI_kgd_SEM | Standard error of the mean for dry matter intake in kilograms per day. | Not a list |
| DM_p | DM_p | Percent of dry matter in the diet composition. | Not a list |
| DM_p_SEM | DM_p_SEM | Standard error of the mean for percent of dry matter. | Not a list |
| OM_p | OM_p | Percent of organic matter in the diet composition. | Not a list |
| OM_p_SEM | OM_p_SEM | Standard error of the mean for percent of organic matter. | Not a list |
| CP_p | CP_p | Percent of crude protein in the diet composition. | Not a list |
| CP_p_SEM | CP_p_SEM | Standard error of the mean for percent of crude protein. | Not a list |
| EE_p | EE_p | Percent of fat in the diet composition. | Not a list |
| EE_p_SEM | EE_p_SEM | Standard error of the mean for percent of fat. | Not a list |
| CF_p | CF_p | Percent of crude fiber in the diet composition. | Not a list |
| CF_p_SEM | CF_p_SEM | Standard error of the mean for percent of crude fiber. | Not a list |
| NDF_p | NDF_p_SEM | Percent of neutral detergent fiber in the diet composition. | Not a list |
| NDF_p_SEM | NDF_p_SEM | Standard error of the mean for percent of neutral detergent fiber. | Not a list |
| ADF_p | ADF_p | Percent of acid detergent fiber in the diet composition. | Not a list |
| ADF_p_SEM | ADF_p_SEM | Standard error of the mean for percent of acid detergent fiber. | Not a list |
| Lignin_p | Lignin_p | Percent of lignin in the diet composition. | Not a list |
| Lignin_p_SEM | Lignin_p_SEM | Standard error of the mean for percent of Lignin. | Not a list |
| NFC_p | NFC_p | Percent of non-fibrous carbohydrates in the diet composition. | Not a list |
| NFC_p_SEM | NFC_p_SEM | Standard error of the mean for percent of non-fibrous carbohydrates. | Not a list |
| NSC_p | NSC_p | Percent of non-structural carbohydrates in the diet composition. | Not a list |
| NSC_p_SEM | NSC_p_SEM | Standard error of the mean for percent of non-structural carbohydrates. | Not a list |
| WSC_p | WSC_p | Percent of water soluble carbohydrates in the diet composition. | Not a list |
| WSC_p_SEM | WSC_p_SEM | Standard error of the mean for percent of water soluble carbohydrates. | Not a list |
| ESC_p | ESC_p | Percent of ethanol soluble carbohydrates in the diet composition. | Not a list |
| ESC_p_SEM | ESC_p_SEM | Standard error of the mean for percent of ethanol soluble carbohydrates. | Not a list |
| ST_p | ST_p | Percent of starch in the diet composition. | Not a list |
| ST_p_SEM | ST_p_SEM | Standard error of the mean for percent of starch. | Not a list |
| SU_p | SU_p | Percent of sugar in the diet composition. | Not a list |
| ASH_p | ASH_p | Percent of ash in the diet composition | Not a list |
| ASH_p_SEM | ASH_p_SEM | Standard error of the mean for percent of ash. | Not a list |
| AIA_p | AIA_p | Percent of acid insoluble ash in the diet composition. | Not a list |
| GE_Mcalkg | GE_Mcalkg | Gross energy by megacalories per kilogram in the diet composition. | Not a list |
| GE_Mcalkg_SEM | GE_Mcalkg_SEM | Standard error of the mean for gross energy by megacalories per kilogram. | Not a list |
| DE_Mcalkg | DE_Mcalkg | Digestible energy by megacalories per kilogram in the diet composition. | Not a list |
| DE_Mcalkg_SEM | DE_Mcalkg_SEM | Standard error of the mean for digestible energy by megacalories per kilogram. | Not a list |
| Digest_compartment | Digest_compartment | Where in the digestive tract nutrients were digested or if it was total tract. | Not a list |
| adDM_p | adDM_p | Percent of apparent digestibility of dry matter. | Not a list |
| adDM_p_SEM | adDM_p_SEM | Standard error of the mean for percent of apparent digestibility of dry matter. | Not a list |
| adDM_p_RMSE | adDM_p_RMSE | Root mean square error for percent of apparent digestibility of dry matter. | Not a list |
| adOM_p | adOM_p | Percent of apparent digestibility of organic matter. | Not a list |
| adOM_p_SEM | adOM_p_SEM | Standard error of the mean for percent of apparent digestibility of organic matter. | Not a list |
| adOM_p_RMSE | adOM_p_RMSE | Root mean square error for percent of apparent digestibility of organic matter. | Not a list |
| adCP_p | adCP_p | Percent of apparent digestibility of crude protein. | Not a list |
| adCP_p_SEM | adCP_p_SEM | Standard error of the mean for percent of apparent digestibility of crude protein. | Not a list |
| adCP_p_RMSE | adCP_p_RMSE | Root mean square error for percent of apparent digestibility of crude protein. | Not a list |
| adN_p | adN_p | Percent of apparent digestibility of nitrogen. | Not a list |
| adN_p_SEM | adN_p_SEM | Standard error of the mean for percent of apparent digestibility of nitrogen. | Not a list |
| adDCP_p | adDCP_p | Percent of apparent digestibility of daily crude protein. | Not a list |
| adDCP_p_SEM | adDCP_p_SEM | Standard error of the mean for percent of apparent digestibility of daily crude protein. | Not a list |
| adEE_p | adEE_p | Percent of apparent digestibility of fat. | Not a list |
| adEE_p_SEM | adEE_p_SEM | Standard error of the mean for percent of apparent digestibility of fat. | Not a list |
| adNFE_p | adNFE_p | Percent of apparent digestibility of nitrogen free extract. | Not a list |
| adNFE_p_SEM | adNFE_p_SEM | Standard error of the mean for percent of apparent digestibility of nitrogen free extract. | Not a list |
| adCF_p | adCF_p | Percent of apparent digestibility of crude fiber. | Not a list |
| adCF_p_SEM | adCF_p | Standard error of the mean for percent of apparent digestibility of crude fiber. | Not a list |
| adCF_p_RMSE | adCF_p_RMSE | Root mean square error for percent of apparent digestibility of crude fiber. | Not a list |
| adNDF_p | adNDF_p | Percent of apparent digestibility of neutral detergent fiber. | Not a list |
| adNDF_p_SEM | adNDF_p_SEM | Standard error of the mean for percent of apparent digestibility of neutral detergent fiber. | Not a list |
| adNDF_p_RMSE | adNDF_p_RMSE | Root mean square error for percent of apparent digestibility of neutral detergent fiber. | Not a list |
| adADF_p | adADF_p | Percent of apparent digestibility of acid detergent fiber. | Not a list |
| adADF_p_SEM | adADF_p_SEM | Standard error of the mean for percent of apparent digestibility of acid detergent fiber. | Not a list |
| adADF_p_RMSE | adADF_p_RMSE | Root mean square error for percent of apparent digestibility of acid detergent fiber. | Not a list |
| adLignin_p | adLignin_p | Percent of apparent digestibility of lignin. | Not a list |
| adLignin_p_SEM | adLignin_p_SEM | Standard error of the mean for percent of apparent digestibility of lignin. | Not a list |
| adST_p | adST_p | Percent of apparent digestibility of starch. | Not a list |
| adST_p_SEM | adST_p_SEM | Standard error of the mean for percent of apparent digestibility of starch. | Not a list |
| adST_p_RMSE | adST_p_RMSE | Root mean square error for percent of apparent digestibility of starch. | Not a list |
| adWSCp | adWSCp | Percent of apparent digestibility of water soluble carbohydrates. | Not a list |
| adWSCp_SEM | adWSCp_SEM | Standard error of the mean for percent of apparent digestibility of water soluble carbohydrates. | Not a list |
| adESCp | adESCp | Percent of apparent digestibility of ethanol soluble carbohydrates. | Not a list |
| adESCp_SEM | adESCp_SEM | Standard error of the mean for percent of apparent digestibility of ethanol soluble carbohydrates. | Not a list |
| adSU_p | adSU_p | Percent of apparent digestibility of sugar. | Not a list |
| adSU_p_SEM | adSU_p_SEM | Standard error of the mean for percent of apparent digestibility of sugar. | Not a list |
| adNSC_p | adNSC_p | Percent of apparent digestibility of non-structural carbohydrates. | Not a list |
| adNSC_p_SEM | adNSC_p_SEM | Standard error of the mean for percent of apparent digestibility of non-structural carbohydrates. | Not a list |
| adTDNDM | adTDNDM | Apparent digestibility of total digestible nutrients based on dry matter. | Not a list |
| adTDNDM_SEM | adTDNDM_SEM | Standard error of the mean for apparent digestibility of total digestible nutrients based on dry matter. | Not a list |
| adGE_p | adGE_p | Percent of apparent digestibility of gross energy. | Not a list |
| adGE_p_SEM | adGE_p_SEM | Standard error of the mean for percent of apparent digestibility of gross energy. | Not a list |
| adEnergy_p | adEnergy_p | Percent of apparent digestibility of energy. | Not a list |
| adEnergy_p_SEM | adEnergy_p_SEM | Standard error of the mean for percent of apparent digestibility of energy. | Not a list |
| adEnergy_p_RMSE | adEnergy_p_RMSE | Root mean square error for percent of apparent digestibility of energy. | Not a list |
| adGEMJkgDM | adGEMJkgDM | Apparent digestibility of gross energy in megajoules per kilogram based on dry matter. | Not a list |
| adGEMJkgDM_SEM | adGEMJkgDM_SEM | Standard error of the mean for apparent digestibility of gross energy in megajoules per kilogram based on dry matter. | Not a list |
| adDE_p | adDE_p | Percent of apparent digestibility of digestible energy. | Not a list |
| adDE_p_SEM | adDE_p_SEM | Standard error of the mean for percent of apparent digestibility of digestible energy. | Not a list |
| adDE_Mcalkg | adDE_Mcalkg | Apparent digestibility of digestible energy in megacalories per kilogram. | Not a list |
| adDE_Mcalkg_SEM | adDE_Mcalkg_SEM | Standard error of the mean for apparent digestibility of digestible energy in megacalories per kilogram. | Not a list |

## Schema SAIDs

**Capture base**: EJT9-nAHr6_50gnaavjAEuEGmV09uMimiERd4fjqMez_

**Bundle**: EHjlOYQdg2-wlAsjOzN09KkAL_HCoNGX40D_T-61XNMH

**Package**: EKwbMhwGZr783T1yKm48ZuriFc9dAn8GFnjpgNca2jmZ

| Layer | SAID | Type |
| --- | --- | --- |
| information (eng) | EO_Y39hCBLgWLqjEeGgSGhn4NSxlhocLpqCcZagfPdiL | spec/overlays/information/1.1 |
| label (eng) | EPJ65EBI9lg5h375I9owfOzWhpERZRb1JqcmQGn3gSLp | spec/overlays/label/1.1 |
| meta (eng) | EEyWc3ih-3NxtVu5_VZygE_Pa-k5XRND20WKYDkaj_l5 | spec/overlays/meta/1.1 |
| unit | EPgSo6EVk4hQR9p7EtQYf9rgF1VrmULx8w-jWz8B5OZk | spec/overlays/unit/1.1 |
| ordering | EI2Gn8Rq0I-TV_Ux7_hPLIwx6At5apfvQygVVBK13f3h | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-19 10:34:55

