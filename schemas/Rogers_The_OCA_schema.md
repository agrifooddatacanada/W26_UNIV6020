---
layout: default  
title: The Effect of Puberty on Fear Behaviour in Laying Pullets  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: The Effect of Puberty on Fear Behaviour in Laying Pullets  
**Description**: Puberty is a critical period characterized by a multitude of physiological and behavioural changes. In humans and rats, the changes in fear behaviour are well documented. In poultry, however, this topic remains largely under-researched. At 4 different developmental ages (pre-puberty, early puberty, late puberty, and post-puberty), brown-feathered layers will undergo a combined emergence/novel arena/novel object fear test to assess changes in fearfulness and threat processing throughout puberty.  
**Classification**: RDF402  
**Author**: Meg Rogers  
**Author Email**: mroger13@uoguelph.ca  
**Schema package SAID**: EB00EAHqWzEGohxo830UtCOcpyq0di37XMoUiYhXkCWl  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| room_pen | Room and pen number | The home location of the test bird, formatted as R2P1, for example. |
| diet | Diet type | The type of diet fed to the test bird, either ad libitum or restricted (to 10% body weight). |
| date | Date of testing | The date that the fear test was performed, formatted as DDMMYYYY. |
| time | Time of testing | The time of day that the fear test was performed, formatting using the 24 hour clock. |
| age_wk | Age of birds at testing, in weeks | The age of the birds at the time of testing, formatted as 15 weeks of age (woa), for example. |
| bird_ID | Unique bird identification number | The identification/tag number assigned to the test bird. |
| emergence_time_sec | Latency to emerge from the start box, in seconds | The length of time taken for the bird to emerge from a start box into the novel arena, in seconds. A maximum of 300 s is permitted without intervention. Exiting the start box is defined as box feet in the arena. |
| reaction_NO | Reaction to the novel object | The initial reaction to the novel object, categorized as high or low fearfulness. Bird may flee, freeze, or exhibit no noticeable change in behaviour (indifference). |
| latency_approach_NO_sec | Latency to approach to novel object, in seconds | The length of time taken for the bird to approach the novel object, in seconds. Some birds may not approach the novel object, thus denoted by \"DNA\" - did not approach. |
| total_time_arena_sec | Total time spent in the novel arena, in seconds | The total amount of time the bird spends in the novel arena, in seconds. This includes emergence from the start box to the conclusion of the test. An absolute maximum total time of 900 s may be obtained. |
| time_wall_sec | Time spent against the wall of the arena, in seconds | The amount of time spent around the perimeters of the fear test, in seconds. Against the wall is defined as less than a body length away. |
| time_centre_sec | Time spent in the centre of the arena, in seconds | The amount of time spent in the centre of the fear test, in seconds. In the centre is defined as at least a body length away from the wall. |
| percent_wall | Percentage of time in the arena spent against the wall | The proportion of time (%) spent less than a body length away from the wall of the test arena. |
| percent_centre | Percentage of time in the arena spent in the centre | The proportion of time (%) spent at least a body length away from the wall of the test arena. |
| alert_stand_ag_sec | Time spent exhibiting alert standing (agitated behaviour), in seconds | The amount of time spent upright and stationary with neck extended, in seconds. |
| alert_walk_ag_sec | Time spent exhibiting alert walking (agitated behaviour), in seconds | The amount of time spent upright and exhibit bipedal movement with neck extended, in seconds. |
| vocalization_ag_sec | Time spent vocalizing (agitated behaviour), in seconds | The amount of time spent making audible calls, in seconds. |
| escape_ag_sec | Time spent attempting to escape (agitated behaviour), in seconds | The amount of time spent walking, running, or jumping at the walls of the arena, in seconds. Wing flapping may be attempted. |
| total_ag_sec | Total time spent exhibiting agitated behaviour during the test, in seconds | The total amount of time spent exhibited agitated behaviours, in seconds. Agitated behaviour includes alert standing, alert walking, vocalization, and attempting escape. |
| explore_nag_sec | Time spent exhibiting exploration (not agitated behaviour), in seconds | The amount of time spent moving with head below the back and attention focussed downward, in seconds. |
| sit_nag_sec | Time spent sitting (not agitated behaviour), in seconds | The amount of time spent on the ground, stationary, with legs tucked under, in seconds. |
| preen_nag_sec | Time spent preening (not agitated behaviour), in seconds | The amount of time spent stationary with beak manipulating her feathers, in seconds. |
| ground_peck_nag_sec | Time spent pecking at the ground (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the floor, in seconds. |
| wall_peck_nag_sec | Time spent pecking at the wall (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the wall, in seconds. |
| NO_peck_nag_sec | Time spent pecking at the novel object (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the novel object, in seconds. |
| relax_stand_nag_sec | Time spent exhibiting relaxed standing (not agitated behaviour), in seconds | The amount of time spent stationary and upright with both legs on the ground, in seconds. |
| dustbath_nag_sec | Time spent dustbathing (not agitated behaviour), in seconds | The amount of time spent stationary and on her side, raking substrate with her wings, beak, or feet, in seconds. She may roll over exhibit kicking motions. |
| total_nag_sec | Total time spent exhibiting not agitated behaviour during the test, in seconds | The total amount of time spent exhibiting not agitated behaviours, in seconds. Not agitated behaviours includes exploring, sitting, preening, ground pecking, wall pecking, novel object pecking, relaxed standing, and dustbathing. |
| percent_ag | Percentage of time during the test spent agitated | The percentage of time spent agitated. This is calculated as \"total_ag_sec\" divided by \"total_time_arena_sec\", then multiplied by 100. |
| percent_nag | Percentage of time during the test spent not agitated | The percentage of time spent not agitated. This is calculated as \"total_nag_sec\" divided by \"total_time_arena_sec\", then multiplied by 100. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | The Effect of Puberty on Fear Behaviour in Laying Pullets | Puberty is a critical period characterized by a multitude of physiological and behavioural changes. In humans and rats, the changes in fear behaviour are well documented. In poultry, however, this topic remains largely under-researched. At 4 different developmental ages (pre-puberty, early puberty, late puberty, and post-puberty), brown-feathered layers will undergo a combined emergence/novel arena/novel object fear test to assess changes in fearfulness and threat processing throughout puberty. |

## Selection lists

### English

#### diet entry codes

| Entry code | Label |
| --- | --- |
| AL | ad libitum feeding |
| R | restricted feeding |

#### reaction_NO entry codes

| Entry code | Label |
| --- | --- |
| H_FL | high fearfulness in reaction to the novel object, flees. |
| H_FR | high fearfulness in reaction to the novel object, freezes. |
| L_IN | low fearfulness in reaction to the novel object, is indifferent. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| room_pen | false |  | Text |  |
| diet | false |  | Text |  |
| date | false |  | DateTime |  |
| time | false |  | DateTime |  |
| age_wk | false | weeks | Numeric |  |
| bird_ID | false |  | Numeric |  |
| emergence_time_sec | false | seconds | Numeric |  |
| reaction_NO | false |  | Text |  |
| latency_approach_NO_sec | false | seconds | Numeric |  |
| total_time_arena_sec | false | seconds | Numeric |  |
| time_wall_sec | false | seconds | Numeric |  |
| time_centre_sec | false | seconds | Numeric |  |
| percent_wall | false | percentage | Numeric |  |
| percent_centre | false | percentage | Numeric |  |
| alert_stand_ag_sec | false | seconds | Numeric |  |
| alert_walk_ag_sec | false | seconds | Numeric |  |
| vocalization_ag_sec | false | seconds | Numeric |  |
| escape_ag_sec | false | seconds | Numeric |  |
| total_ag_sec | false | seconds | Numeric |  |
| explore_nag_sec | false | seconds | Numeric |  |
| sit_nag_sec | false | seconds | Numeric |  |
| preen_nag_sec | false | seconds | Numeric |  |
| ground_peck_nag_sec | false | seconds | Numeric |  |
| wall_peck_nag_sec | false | seconds | Numeric |  |
| NO_peck_nag_sec | false | seconds | Numeric |  |
| relax_stand_nag_sec | false | seconds | Numeric |  |
| dustbath_nag_sec | false | seconds | Numeric |  |
| total_nag_sec | false | seconds | Numeric |  |
| percent_ag | false | percentage | Numeric |  |
| percent_nag | false | percentage | Numeric |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| room_pen | Room and pen number | The home location of the test bird, formatted as R2P1, for example. | Not a list |
| diet | Diet type | The type of diet fed to the test bird, either ad libitum or restricted (to 10% body weight). | ad libitum feeding, restricted feeding |
| date | Date of testing | The date that the fear test was performed, formatted as DDMMYYYY. | Not a list |
| time | Time of testing | The time of day that the fear test was performed, formatting using the 24 hour clock. | Not a list |
| age_wk | Age of birds at testing, in weeks | The age of the birds at the time of testing, formatted as 15 weeks of age (woa), for example. | Not a list |
| bird_ID | Unique bird identification number | The identification/tag number assigned to the test bird. | Not a list |
| emergence_time_sec | Latency to emerge from the start box, in seconds | The length of time taken for the bird to emerge from a start box into the novel arena, in seconds. A maximum of 300 s is permitted without intervention. Exiting the start box is defined as box feet in the arena. | Not a list |
| reaction_NO | Reaction to the novel object | The initial reaction to the novel object, categorized as high or low fearfulness. Bird may flee, freeze, or exhibit no noticeable change in behaviour (indifference). | high fearfulness in reaction to the novel object, flees., high fearfulness in reaction to the novel object, freezes., low fearfulness in reaction to the novel object, is indifferent. |
| latency_approach_NO_sec | Latency to approach to novel object, in seconds | The length of time taken for the bird to approach the novel object, in seconds. Some birds may not approach the novel object, thus denoted by \"DNA\" - did not approach. | Not a list |
| total_time_arena_sec | Total time spent in the novel arena, in seconds | The total amount of time the bird spends in the novel arena, in seconds. This includes emergence from the start box to the conclusion of the test. An absolute maximum total time of 900 s may be obtained. | Not a list |
| time_wall_sec | Time spent against the wall of the arena, in seconds | The amount of time spent around the perimeters of the fear test, in seconds. Against the wall is defined as less than a body length away. | Not a list |
| time_centre_sec | Time spent in the centre of the arena, in seconds | The amount of time spent in the centre of the fear test, in seconds. In the centre is defined as at least a body length away from the wall. | Not a list |
| percent_wall | Percentage of time in the arena spent against the wall | The proportion of time (%) spent less than a body length away from the wall of the test arena. | Not a list |
| percent_centre | Percentage of time in the arena spent in the centre | The proportion of time (%) spent at least a body length away from the wall of the test arena. | Not a list |
| alert_stand_ag_sec | Time spent exhibiting alert standing (agitated behaviour), in seconds | The amount of time spent upright and stationary with neck extended, in seconds. | Not a list |
| alert_walk_ag_sec | Time spent exhibiting alert walking (agitated behaviour), in seconds | The amount of time spent upright and exhibit bipedal movement with neck extended, in seconds. | Not a list |
| vocalization_ag_sec | Time spent vocalizing (agitated behaviour), in seconds | The amount of time spent making audible calls, in seconds. | Not a list |
| escape_ag_sec | Time spent attempting to escape (agitated behaviour), in seconds | The amount of time spent walking, running, or jumping at the walls of the arena, in seconds. Wing flapping may be attempted. | Not a list |
| total_ag_sec | Total time spent exhibiting agitated behaviour during the test, in seconds | The total amount of time spent exhibited agitated behaviours, in seconds. Agitated behaviour includes alert standing, alert walking, vocalization, and attempting escape. | Not a list |
| explore_nag_sec | Time spent exhibiting exploration (not agitated behaviour), in seconds | The amount of time spent moving with head below the back and attention focussed downward, in seconds. | Not a list |
| sit_nag_sec | Time spent sitting (not agitated behaviour), in seconds | The amount of time spent on the ground, stationary, with legs tucked under, in seconds. | Not a list |
| preen_nag_sec | Time spent preening (not agitated behaviour), in seconds | The amount of time spent stationary with beak manipulating her feathers, in seconds. | Not a list |
| ground_peck_nag_sec | Time spent pecking at the ground (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the floor, in seconds. | Not a list |
| wall_peck_nag_sec | Time spent pecking at the wall (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the wall, in seconds. | Not a list |
| NO_peck_nag_sec | Time spent pecking at the novel object (not agitated behaviour), in seconds | The amount of time spent with her beak repeatedly touching the novel object, in seconds. | Not a list |
| relax_stand_nag_sec | Time spent exhibiting relaxed standing (not agitated behaviour), in seconds | The amount of time spent stationary and upright with both legs on the ground, in seconds. | Not a list |
| dustbath_nag_sec | Time spent dustbathing (not agitated behaviour), in seconds | The amount of time spent stationary and on her side, raking substrate with her wings, beak, or feet, in seconds. She may roll over exhibit kicking motions. | Not a list |
| total_nag_sec | Total time spent exhibiting not agitated behaviour during the test, in seconds | The total amount of time spent exhibiting not agitated behaviours, in seconds. Not agitated behaviours includes exploring, sitting, preening, ground pecking, wall pecking, novel object pecking, relaxed standing, and dustbathing. | Not a list |
| percent_ag | Percentage of time during the test spent agitated | The percentage of time spent agitated. This is calculated as \"total_ag_sec\" divided by \"total_time_arena_sec\", then multiplied by 100. | Not a list |
| percent_nag | Percentage of time during the test spent not agitated | The percentage of time spent not agitated. This is calculated as \"total_nag_sec\" divided by \"total_time_arena_sec\", then multiplied by 100. | Not a list |

## Schema SAIDs

**Capture base**: EDtPq8I4ZmmVsALcaHBMpVxkTt8_H4QEdmuDcbH7UvqP

**Bundle**: EGv_C8aQySN0_ExyZcioOXdHWhrMiiJBtE7IoLkH-xin

**Package**: EB00EAHqWzEGohxo830UtCOcpyq0di37XMoUiYhXkCWl

| Layer | SAID | Type |
| --- | --- | --- |
| entry (eng) | ENgg5nmJjMKsdVugbgB06TvlwkS_m18rZcAmw2QV_dIX | spec/overlays/entry/1.1 |
| entry_code | EM1Th_uae8tOrhacjXvtKCteqzabYkpuUhAUns49e-VI | spec/overlays/entry_code/1.1 |
| information (eng) | EIWkdl0bowmME6wHSCVSui-Ffip96-xKc2IJfaO79pfZ | spec/overlays/information/1.1 |
| label (eng) | EC5HPOAqqyWSDqTBOuZpCDp-lp4nNfpbgTTWtq1ikzDS | spec/overlays/label/1.1 |
| meta (eng) | EHvvGSn0kKCgAjH2Mwgu0_J-uuINTVvhmZ_sxNL-TaBW | spec/overlays/meta/1.1 |
| unit | EIy_tD9elMoFwkWCZsrepFvMcAsptvkYHRAxfYPw9TfL | spec/overlays/unit/1.1 |
| ordering | EML-KyhzoWCac66GgQhqCmxe4Hk1yZCnnlZKEIMAtERz | community/overlays/adc/ordering/1.0 |

**Date created**: 2026-01-15 11:45:41

