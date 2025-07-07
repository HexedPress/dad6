---
title: Stunts
keywords: documentation, dad6, advanced, core
last_updated: July 3, 2016
tags: [dad6_core, dad6_advanced]
summary: "Running stunts in the DAD6 framework."
sidebar: dad6_sidebar
permalink: dad6_stunts.html
folder: dad6
---

Up until now, we’ve assumed that the prize for completing a challenge was a singular thing. Why is the Character jumping across the pit? To get to the other side.

## What is a stunt?

Sometimes, though, the prize might be a compound of multiple goals. The Character wants to jump across the pit not only to reach the other side but to do it silently. Two goals, movement and stealth, in one action, jumping across the pit. This is a stunt. How do we handle it? Actually, it’s pretty easy.

### Separate the stunt into segements for each goal

1. For each goal, sum up the difficulty as if it were its own challenge.
2. The Character assembles their dice pool as usual and rolls their dice. Here, the stunt kicks in.
3. **The Character must split up their boons between the goals**.
4. Any banes they suffer should use the context of whichever goals they come up short against. Failed to be stealthy? You’ve made a bunch of noise. Failed the jump? You’re falling (let’s hope it’s only a ten foot deep pit!).
5. If they manage to succeed at both goals, then they’ve done it! *Huzzah!*

{% include links.html %}
