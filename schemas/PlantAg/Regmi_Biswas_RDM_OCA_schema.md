---
layout: default  
title: Biswas Regmi 
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Biswas_RDM  
**Description**: Georeferenced soil dataset with depth, pH, moisture, and available N, P, and K measurements for spatial and soil fertility analysis.  
**Classification**: RDF401  
**Author**: Biswas Regmi  
**Author Email**: regmib@uoguelph.ca  
**Schema package SAID**: EA1mAUYb_A722CkePqvc194WZPcOjWBaxur8Kn1qEbxQ  

[Download Schema](Regmi_Biswas_RDM_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| sample_id | Soil Sample ID | Unique identifier assigned to each soil sample collected in the field. |
| x_coord_m | X coordinate | Easting coordinate of the sampling location in meters (UTM or local coordinate system). |
| y_coord_m | Y coordinate | Northing coordinate of the sampling location in meters (UTM or local coordinate system). |
| depth_cm | Sampling depth (cm) | Depth at which the soil sample was collected, measured in centimeters from the soil surface. |
| ph | Soil pH | Soil pH measured in the laboratory, indicating acidity or alkalinity of the sample. |
| soil_moisture_pct | Gravimetric soil moisture (%) | Gravimetric soil moisture content, expressed as a percentage of water weight relative to dry soil weight. |
| n_mgkg | Available nitrogen | Concentration of available nitrogen in the soil sample, measured in milligrams per kilogram (mg/kg). |
| p_mgkg | Available phosphorus | Concentration of available phosphorus in the soil sample, measured in milligrams per kilogram (mg/kg) |
| k_mgkg | Exchangeable potassium | Concentration of exchangeable potassium in the soil sample, measured in milligrams per kilogram (mg/kg). |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Biswas_RDM | Georeferenced soil dataset with depth, pH, moisture, and available N, P, and K measurements for spatial and soil fertility analysis. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| sample_id | false | - | Text |  | true | ^\.\{0,50\}$ |
| x_coord_m | true | m | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| y_coord_m | true | m | Numeric |  | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| depth_cm | false | cm | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| ph | false | - | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| soil_moisture_pct | false | % | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n_mgkg | false | mg/kg | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| p_mgkg | false | mg/kg | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| k_mgkg | false | mg/kg | Numeric |  | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| sample_id | Soil Sample ID | Unique identifier assigned to each soil sample collected in the field. | Not a list |
| x_coord_m | X coordinate | Easting coordinate of the sampling location in meters (UTM or local coordinate system). | Not a list |
| y_coord_m | Y coordinate | Northing coordinate of the sampling location in meters (UTM or local coordinate system). | Not a list |
| depth_cm | Sampling depth (cm) | Depth at which the soil sample was collected, measured in centimeters from the soil surface. | Not a list |
| ph | Soil pH | Soil pH measured in the laboratory, indicating acidity or alkalinity of the sample. | Not a list |
| soil_moisture_pct | Gravimetric soil moisture (%) | Gravimetric soil moisture content, expressed as a percentage of water weight relative to dry soil weight. | Not a list |
| n_mgkg | Available nitrogen | Concentration of available nitrogen in the soil sample, measured in milligrams per kilogram (mg/kg). | Not a list |
| p_mgkg | Available phosphorus | Concentration of available phosphorus in the soil sample, measured in milligrams per kilogram (mg/kg) | Not a list |
| k_mgkg | Exchangeable potassium | Concentration of exchangeable potassium in the soil sample, measured in milligrams per kilogram (mg/kg). | Not a list |

## Schema SAIDs

**Capture base**: EMIGj-CjmG2w8teSH2QS3vbrxbgrOgbQ2wmGKCV87cn4

**Bundle**: EAGPl4VGmPNTGpesII7SzuI4Ci_09HdDaZnnDszNdNei

**Package**: EA1mAUYb_A722CkePqvc194WZPcOjWBaxur8Kn1qEbxQ

| Layer | SAID | Type |
| --- | --- | --- |
| conformance | ELE3l46LvaCr2V-bKaD685CF9ltd3OdJq9DMv-NJ9NtQ | spec/overlays/conformance/1.1 |
| format | EOaNmX9_rE-FKUIANv7fWwqA1U-3ZLTEefECF8UnZh_x | spec/overlays/format/1.1 |
| information (eng) | ED-lx5Q0eMZw7Ni7slkddJkqdv3GJniQlvvNzws_pU-O | spec/overlays/information/1.1 |
| label (eng) | EOyXLWZ3rtDv6xJgCe93S0PwlwT_p4tcIqN7L7rsbnn4 | spec/overlays/label/1.1 |
| meta (eng) | ELN0OVZUuFxTQ2ku1r-Gz6NyEJUklcA1FQ62f34Mk3-U | spec/overlays/meta/1.1 |
| unit | EKq6_hRxyKHXq1se7IxY4SJcOAiM_ftpuB8seF53JBk0 | spec/overlays/unit/1.1 |
| ordering | EMonawWacw9qVrOpe8ouO6SD0m6f6EJ8m8lIkbB4rJGf | community/overlays/adc/ordering/1.0 |
| sensitive | ENbS4apVW6omnVgCVnx2kwAjxHqryuEtkBLcdkwQTWOM | community/overlays/adc/sensitive/1.0 |

**Date created**: 2026-01-16 09:47:06

