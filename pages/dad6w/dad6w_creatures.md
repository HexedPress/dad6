---
title: Wandering creature encounters
keywords: documentation, dad6, wilderness
last_updated: Jul 7, 2025
tags: [dad6_wilderness]
summary: "Wandering creature encounters in DAD6 Wilderness."
sidebar: dad6_sidebar
permalink: dad6w_creatures.html
folder: dad6w
---

The higher an area’s **Activity**, the more likely the party is to encounter creatures while there.

## Activity sets encounter frequency

Start with a default value of one wandering creature check every four Expedition Turns. Subtract one Turn for each **Activity** Level above one. We can express this in a simple formula: **check for encounters once every (5 – Activity) Expedition Turns**. If the final number is less than zero, roll an additional die for each negative number and choose the highest result of the dice rolled. **A six indicates an encounter**.

| Area Type  | Peril | Encounter Frequency  |
| ---------- | ----- | -------------------- |
| Clear      | 1     | 1/4 Turns            |
| Grasslands | 1     | 1/4 Turns            |
| River      | 2     | 1/3 Turns            |
| Woodlands  | 2     | 1/3 Turns            |
| Hills      | 2/+1  | 1/3 Turns / -1 Turn  |
| Barren     | 2     | 1/2 Turns            |
| Swampland  | 3     | 1/2 Turns            |
| Jungle     | 3     | 1/2 Turns            |
| Mountains  | 3/+2  | 1/2 Turns / -2 Turns |
| Desert     | 3     | 1/2 Turns            |

### Alternate approach: less frequent rolls, higher encounter chance

Another way to leverage **Activity** is, instead of rolling more frequently, increase the probability of an encounter instead. To do this, at every encounter check, roll a number of dice equal to the **Activity** value and choose the highest result. **A six indicates an encounter**.

| Area Type  | Peril | Encounter Check Dice |
| ---------- | ----- | -------------------- |
| Clear      | 1     | 1 die                |
| Grasslands | 1     | 1 die                |
| River      | 2     | 2 dice               |
| Woodlands  | 2     | 2 dice               |
| Hills      | 2/+1  | 2 dice / +1 die      |
| Barren     | 2     | 2 dice               |
| Swampland  | 3     | 3 dice               |
| Jungle     | 3     | 3 dice               |
| Mountains  | 3/+2  | 3 dice / +2 dice     |
| Desert     | 3     | 3 dice               |

### Increasing danger with extra successes

If you end up in a situation in which you roll multiple dice to indicate an encounter and you score more than one success (ie a result of six), you can add those extra successes to your encounter roll. If you organize your encounter table in order from least to most dangerous creatures, this modifier will push results towards the more dangerous encounters.

### Example

The party is in the desert and I am using the alternate encounter roll approach. I roll 3d6 and score two successes: the first success indicates an encounter and I add the second success as a modifier on my encounter roll. Instead of rolling 1d6 on my desert encounter table, I roll 1d6+1.

## Turbidity and Encounters

The higher an area’s **Turbidity**, the more the terrain and environment conceal features and creatures. When rolling encounter distance, start with 4d6 then subtract one die for every level of **Turbidity** above one. Roll the remaining number of dice and multiply the result by tens of yards for distance.

If the result is less than 1, take the remaining dice and subtract them from 4d6 but, this time, roll the remaining dice and multiply the result by tens of feet.

{% include links.html %}

## Surprise

Surprise can be adjudicated by a contested challenge (see DAD6, “[Running Races, Chases, and Contested Challenges](dad6_multi_stage.html#running-races-chases-and-contested-challenges)”). In the wilderness, an area’s **Turbidity** will make it harder to spot Creatures at distance. If a Creature is surprised, add or subtract the margin of defeat from the encounter distance, at the discretion of the surprising Creature.

## Pursuit

DAD6 contains a mechanic for adjudicating chases (see “[Running Races, Chases, and Contested Challenges](dad6_multi_stage.html#running-races-chases-and-contested-challenges)”). In the wilderness, an area’s **Turbidity** will make it harder to track, follow, and pursue a target. For every level of **Turbidity** above one, add one die to the pursued target’s dice pool.
