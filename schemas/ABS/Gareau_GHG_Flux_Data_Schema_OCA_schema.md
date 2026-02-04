---
layout: default  
title: Michelle Gareau 
parent: School of Envirnomental Sciences Schemas
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: GHG_Flux_Data_Schema  
**Description**: This dataset contains chamber-based measurements of greenhouse gas (GHG) concentrations and derived flux calculations for soil N₂O. Raw concentration data are combined with environmental parameters and chamber geometry to calculate linear and quadratic flux estimates.  
**Classification**: RDF401  
**Author**: Michelle Gareau  
**Author Email**: gareaum@uoguelph.ca  
**Schema package SAID**: ENkZNNH9QYzX3mnk9YQ2s-S2Zx3ONfXTTMG4kofoFpbD  

[Download Schema](Gareau_GHG_Flux_Data_Schema_OCA_package.json)

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| date | date of sampling | date of sampling (mm:dd:yyyy) |
| doy | doy of year | day of year corresponding to the sample date (1 - 366) |
| sample_id | sample identifier | unique sample entry code (doy-sample_id-timestep) |
| sample_location | sample location | Experimental location identifier corresponding to the hexagon (hex) and lysimeter |
| soil_id | soil type | soil classification |
| start_time | sampling start time | time chambers are closed and the first sample is collected. |
| end_time | sampling end time | time the chambers are opened and no more samples are collected |
| time_step_h | time since closure when a sample is collected | Time elapsed since chamber closure (t=0 mins, 7 mins, 14 mins, 21 mins) |
| time_step_h2 | time step sqaured | Squared time step term used for quadratic flux model fitting |
| co2_ppm | CO2 concentration | Measured carbon dioxide concentration inside the chamber. |
| n2o_ppm | N2O concentratoin | Measured nitrous oxide concentration inside the chamber. |
| temperature_c | Air temperature | average air temperature during sampling |
| pressure_atm | atmospheric pressure | Atmospheric pressure measured during sampling |
| molar_volume | molar gas volume | Calculated from temperature and pressure using ideal gas law |
| co2_concentration | CO2 concentraction | COnverted from ppm to mass-based units as carbon equivalents |
| n2o_concentration | N2O concentration | Converted from ppm to mass-based units as nitrogen equivalents |
| n2o_linear_flux | N2O linear flux | Flux from linear regression of concentration vs time |
| n2o_linear_r2 | N2O linear R2 | Coefficient of determination for linear model |
| n2o_quadratic_slope | N2O quadratic slope | Instantaneous slope at time zero from quadratic model |
| n2o_quadratic_r2 | N2O quadratic R2 | Coefficient of determination for quadratic model |
| n2o_quadratic_coefficient | N2O quadratic coefficient | Second derivative indicating curvature of concentration–time relationship |
| n2o_quadratic_flux | N2O quadratic flux | Flux estimated from quadratic model scaled by chamber geometry |
| fit_selection | Flux fit scheme | Which flux scheme was selected based on R2 |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | GHG_Flux_Data_Schema | This dataset contains chamber-based measurements of greenhouse gas (GHG) concentrations and derived flux calculations for soil N₂O. Raw concentration data are combined with environmental parameters and chamber geometry to calculate linear and quadratic flux estimates. |

## Selection lists

### English

#### fit_selection entry codes

| Entry code | Label |
| --- | --- |
| quadratic | quadratic flux scheme |
| linear | linear flux scheme |

#### sample_location entry codes

| Entry code | Label |
| --- | --- |
| H1L1 | hex 1 lysimeter 1 |
| H1L2 | hex 1 lysimeter 2 |
| H1L3 | hex 1 lysimeter 3 |
| H1L4 | hex 1 lysimeter 4 |
| H1L5 | hex 1 lysimeter 5 |
| H1L6 | hex 1 lysimeter 6 |
| H2L1 | hex 2 lysimeter 1 |
| H2L2 | hex 2 lysimeter 2 |
| H2L3 | hex 2 lysimeter 3 |
| H2L4 | hex 2 lysimeter 4 |
| H2L5 | hex 2 lysimeter 5 |
| H2L6 | hex 2 lysimeter 6 |
| H3L1 | hex 3 lysimeter 1 |
| H3L2 | hex 3 lysimeter 2 |
| H3L3 | hex 3 lysimeter 3 |
| H3L4 | hex 3 lysimeter 4 |
| H3L5 | hex 3 lysimeter 5 |
| H3L6 | hex 3 lysimeter 6 |

#### soil_id entry codes

| Entry code | Label |
| --- | --- |
| C | cambridge loamy sand |
| E | Elora silty loam |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| date | false |  | DateTime | utf-8 | true | ^\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)/\(0\[1\-9\]\|1\[0\-2\]\)/\\d\{4\}$ |
| doy | false | day | Numeric | utf-8 | true | ^\-?\[0\-9\]\+$ |
| sample_id | false |  | Text | utf-8 | true | ^\[A\-Za\-z\]\{1,50\}$ |
| sample_location | false |  | Text | utf-8 | true | ^\[A\-Za\-z\]\{1,50\}$ |
| soil_id | false |  | Text | utf-8 | false | ^\[A\-Za\-z\]\{0,50\}$ |
| start_time | false | hours | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| end_time | false | hours | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| time_step_h | false | hours | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| time_step_h2 | false | hours^2 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| co2_ppm | false | ppm | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_ppm | false | ppm | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| temperature_c | false | celcius | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| pressure_atm | false | atm | Numeric | utf-8 | true | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| molar_volume | false | m^3 mol^-1 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| co2_concentration | false | ug CO2-C m^-3 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_concentration | false | ug N2O-N m^-3 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_linear_flux | false | ug N m^-3 h^-1 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_linear_r2 | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_quadratic_slope | false | ug N m^-3 h^-2 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_quadratic_r2 | false |  | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_quadratic_coefficient | false | ug N m^-3 h^-2 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| n2o_quadratic_flux | false | ug N m^-3 h^-1 | Numeric | utf-8 | false | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| fit_selection | false |  | Text | utf-8 | false | ^\[A\-Za\-z\]\{0,50\}$ |

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
| date | date of sampling | date of sampling (mm:dd:yyyy) | Not a list |
| doy | doy of year | day of year corresponding to the sample date (1 - 366) | Not a list |
| sample_id | sample identifier | unique sample entry code (doy-sample_id-timestep) | Not a list |
| sample_location | sample location | Experimental location identifier corresponding to the hexagon (hex) and lysimeter | hex 1 lysimeter 1, hex 1 lysimeter 2, hex 1 lysimeter 3, hex 1 lysimeter 4, hex 1 lysimeter 5, hex 1 lysimeter 6, hex 2 lysimeter 1, hex 2 lysimeter 2, hex 2 lysimeter 3, hex 2 lysimeter 4, hex 2 lysimeter 5, hex 2 lysimeter 6, hex 3 lysimeter 1, hex 3 lysimeter 2, hex 3 lysimeter 3, hex 3 lysimeter 4, hex 3 lysimeter 5, hex 3 lysimeter 6 |
| soil_id | soil type | soil classification | cambridge loamy sand, Elora silty loam |
| start_time | sampling start time | time chambers are closed and the first sample is collected. | Not a list |
| end_time | sampling end time | time the chambers are opened and no more samples are collected | Not a list |
| time_step_h | time since closure when a sample is collected | Time elapsed since chamber closure (t=0 mins, 7 mins, 14 mins, 21 mins) | Not a list |
| time_step_h2 | time step sqaured | Squared time step term used for quadratic flux model fitting | Not a list |
| co2_ppm | CO2 concentration | Measured carbon dioxide concentration inside the chamber. | Not a list |
| n2o_ppm | N2O concentratoin | Measured nitrous oxide concentration inside the chamber. | Not a list |
| temperature_c | Air temperature | average air temperature during sampling | Not a list |
| pressure_atm | atmospheric pressure | Atmospheric pressure measured during sampling | Not a list |
| molar_volume | molar gas volume | Calculated from temperature and pressure using ideal gas law | Not a list |
| co2_concentration | CO2 concentraction | COnverted from ppm to mass-based units as carbon equivalents | Not a list |
| n2o_concentration | N2O concentration | Converted from ppm to mass-based units as nitrogen equivalents | Not a list |
| n2o_linear_flux | N2O linear flux | Flux from linear regression of concentration vs time | Not a list |
| n2o_linear_r2 | N2O linear R2 | Coefficient of determination for linear model | Not a list |
| n2o_quadratic_slope | N2O quadratic slope | Instantaneous slope at time zero from quadratic model | Not a list |
| n2o_quadratic_r2 | N2O quadratic R2 | Coefficient of determination for quadratic model | Not a list |
| n2o_quadratic_coefficient | N2O quadratic coefficient | Second derivative indicating curvature of concentration–time relationship | Not a list |
| n2o_quadratic_flux | N2O quadratic flux | Flux estimated from quadratic model scaled by chamber geometry | Not a list |
| fit_selection | Flux fit scheme | Which flux scheme was selected based on R2 | quadratic flux scheme, linear flux scheme |

## Schema SAIDs

**Capture base**: EJi4Y2K5g202vZTbMlLxycMfoZSXvuRurAWeKBJL6ZCS

**Bundle**: ECo5uFixUxjrww9I65Kmm6O1AE3zahjHZqBoZBCCxVYr

**Package**: ENkZNNH9QYzX3mnk9YQ2s-S2Zx3ONfXTTMG4kofoFpbD

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EPLjavPckEhln3_bhmeDjVR-KR9VlOhkkdq0KMLzj6M_ | spec/overlays/character_encoding/1.1 |
| conformance | EIz_QN6bucMuKgKUE-G6J8c5ITM2A0TEYH_juD48NZpr | spec/overlays/conformance/1.1 |
| entry (eng) | EOTdMGLOMj8rkhsvOJ7ZQYbDxRdQXe7DZWvKfLiotCQl | spec/overlays/entry/1.1 |
| entry_code | EH_yYXq5mDqzPOiOLrN53Y1tEN3qvfC1p_BCLg2v7v-q | spec/overlays/entry_code/1.1 |
| format | EP72AusTFErouDUsTf6nNqdmtyJw-CF7Be7iau2Jvl4f | spec/overlays/format/1.1 |
| information (eng) | EOFCIVxmY_aInA5jrlQe8tv78cCsFfSdOb-NZ-Br1lTz | spec/overlays/information/1.1 |
| label (eng) | EIY-J7MkN9KI5zH5wTldVtM23Jdi_8_di5kP7qdFDMyr | spec/overlays/label/1.1 |
| meta (eng) | EFxoTP5CSy86FbPH_uxfT9g6uSPguhkCWLUkiL6pfFol | spec/overlays/meta/1.1 |
| unit | EC9fV69LkWKKNnejdSItlANvjiTT1-85MedoGR9h3gj2 | spec/overlays/unit/1.1 |
| ordering | EPdQYfVoXwdpwEyxyESWyfiS8ibyPpV71iw0gAOcdap6 | community/overlays/adc/ordering/1.0 |
| unit_framing | EPyVTX2P6J0zIPrZvI8b3ULH-_v7u6HKbI6waHjDm3Y2 | community/overlays/adc/unit_framing/1.0 |

**Date created**: 2026-02-04 11:58:25

