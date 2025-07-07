---
title: Terrain attributes
keywords: documentation, dad6, wilderness
last_updated: Jul 7, 2025
tags: [dad6_wilderness]
summary: "Terrain attributes in DAD6 Wilderness."
sidebar: dad6_sidebar
permalink: dad6w_attributes.html
folder: dad6w
---

To describe creatures mechanically, we use a stat block to give us an at-a-glance view of the major elements of that creature. We can do the same for the wilderness.

## Hazard Dice

Let’s start out with a very simple measure that might, by itself, provide all the utility that might be needed. We’ll call it **Hazard Dice** (_HD_). The more HD an area has, the more formidable it will be against the incursions of Creatures that operate within it.

**When a Character attempts a Wilderness Action in an area, it requires a number of boons equal to its HD to be successful.**

In general, areas that pose no additional difficulty to actions (_normal_) have an HD of 1. Areas that possess a significant challenge to actions (_difficult_) have an HD of 2 and those areas that offer extensive obstacles (_extreme_) to actions have an HD of 3.

| Common Area Type | Difficulty | Hazard Dice |
| ---------------- | ---------- | ----------- |
| Clear            | Normal     | 1           |
| Grasslands       | Normal     | 1           |
| River            | Difficult  | 2           |
| Woodlands        | Difficult  | 2           |
| Hills            | Difficult  | 2 / +1      |
| Barren           | Difficult  | 2           |
| Swampland        | Extreme    | 3           |
| Jungle           | Extreme    | 3           |
| Mountains        | Extreme    | 3 / +2      |
| Desert           | Extreme    | 3           |

Notice that hills and mountains are included on this list because they are often represented in some form on hex maps. They are not, however, true area types in and of themselves but measures of elevation changes that affect an area. A better way to represent hills and mountains is through a modifier: **+1 for hills** and **+2 for mountains**. Thus, for example, an area of hilly jungle would have 4 HD.

## TRAPS

We could stop there but we won’t. There may be times when we want a little less abstraction, to describe an area’s resilience or response to different actions separately instead of relying on a single number. To do that, we first need to categorize the different sorts of actions and activities we’ll be dealing with. We can then match those sorts of actions with area attributes.

| Action Type       | Area Attribute |
| ----------------- | -------------- |
| Navigation/Search | Turbidity      |
| Travel            | Ruggedness     |
| Stealth           | Activity       |
| General danger    | Peril          |
| Supply            | Scarcity       |

Let’s go over what they mean.

### Turbidity

The word itself refers to a cloudiness or opaqueness. In our case, we’re using the term to represent the difficulty of surveying the area clearly and accurately.

### Ruggedness

Ruggedness measures the difficulty of traversing the area. **An area requires one Expedition Turn for each of its Ruggedness points to move through it.**

### Activity

How populated is this area? That’s what Activity measures.

### Peril

How dangerous is this area? That’s its Peril. The higher the value, the more dangerous the place.

### Scarcity

The more difficult it is for a Character to resupply (hunt, fish, forage, find other resources, etc.), the higher its Scarcity value.

## Terrain TRAPS summary table

| Area Type  | HD   | Turbidity | Ruggedness | Activity | Peril | Scarcity |
| ---------- | ---- | --------- | ---------- | -------- | ----- | -------- |
| Clear      | 1    | 1         | 1          | 1        | 1     | 1        |
| Grasslands | 1    | 1         | 1          | 1        | 1     | 1        |
| River      | 2    | 1         | 2          | 2        | 2     | 1        |
| Woodlands  | 2    | 2         | 2          | 2        | 2     | 2        |
| Hills      | 2/+1 | 2/+1      | 2/+1       | 2/+1     | 2/+1  | 2/+1     |
| Barren     | 2    | 3         | 2          | 2        | 2     | 3        |
| Swampland  | 3    | 3         | 3          | 3        | 3     | 3        |
| Jungle     | 3    | 3         | 3          | 3        | 3     | 3        |
| Mountains  | 3/+2 | 3/+2      | 3/+2       | 3/+2     | 3/+2  | 3/+2     |
| Desert     | 3    | 3         | 3          | 3        | 3     | 3        |

A note about the numbers: all the numbers that I’ve posted above are merely provisional, mostly drawn from classic sources with a few of my own tweaks here and there tossed into the mix. As we use these HD and attributes to describe various places, feel free, encouraged even, to tweak or wholly replace these numbers with whatever makes sense to you.

## Expressing HD and TRAPS in Shorthand

In exactly the same way that we can describe a monster’s stats in an abbreviated way, we can reference HD and TRAPS in a quick shorthand. In our notes, we might mark a forest as _Gray Woods (_**_HD_**_2)_.

If there’s an exceptional value, ie. one that isn’t reflected in the generic stats, we can call it out, as in: _Mottled Woods (_**_HD_**_2,_ **_P_**_3)_. This would indicate that these woods have an overall HD 2 but a specific Peril of 3.

If we want to be extremely specific, we can list it out all the values, as in: _Forest of Death (_**_HD_**_4,_ **_T_**_2_ **_R_**_3_ **_A_**_4_ **_P_**_4_ **_S_**_5)_.

{% include links.html %}
