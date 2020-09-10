﻿# Carnalitas v1.1

## Slavery System (WIP)

* Added new traits: Chattel Slave (`slave`), Freedman/Freedwoman (`former_slave`)
* New overwrites prevent Chattel Slaves from being granted titles, or from leaving court.

## Stress From Arousal

* Added a game rule for characters to passively gain stress over time. Stress gain is increased if Lustful or Rakish and absent if Chaste.

## Dominant/Submissive Relation

* Added two new scripted_relations, `dominant` and `submissive`. Every dominant has a submissive and vice versa. These presently do nothing and are meant for modders to hook into.

## Sex Scene Flag Triggers

* Sex scene flags are now re-asserted in the immediate block of sex scene events and persistent through the carn_on_sex on_action, allowing modders to reference them in followup events. The syntax is `carn_sex_scene_was_vaginal = yes`, where `vaginal` can be replaced with any of the supported flags. This means that you can, for example, add an event to carn_on_sex that only triggers when the player has `bdsm` sex.
* `carn_on_vaginal_sex`, `carn_on_anal_sex`, and `carn_on_oral_sex` are now depreciated and no longer function.

## New Sex Scene Tags

`bestiality`
`petplay`

## Bug Fixes

* Fixed every single child inheriting small dicks and tits, regardless of genetics.
* Fixed male characters being generated with the futa trait when futa inheritance is off.
* Fixed some errors in French localization.