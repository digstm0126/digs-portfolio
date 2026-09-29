+++
date = '2026-09-24T12:24:15+12:00'
draft = false
title = 'Patchwork:Ōtautahi'
+++

![Patchwork Ōtautahi banner](baner.jpeg)

## Trailer

{{< vimeo-vertical 1228566704 "Patchwork Ōtautahi trailer" >}}

## What is Patchwork Ōtautahi?


Patchwork Ōtautahi is an interactive mural spread across three screens at Tūranga, Christchurch's central library. It shows an isometric town modelled on Ōtautahi, full of little NPCs going about their day. Every so often one of them needs help deciding something, and anyone walking past can text them through a web app on their phone. There's nothing to download. When you help an NPC, they send you a selfie, and your choice stays visible in the town for everyone to see.

## My role

I was **lead designer and a programmer** on a team of 11. I built the NPC and task systems:

- **NPC AI:** navigation, zones, NPC sub-classes, schedules, and goal weighting.
- **Gameplay glue:** the SequenceHandler system, hooking up VFX and sound, animations, the selfie feature, character customisation, and NPC reactions.
- **Game design:** coming up with the design and adapting it as problems came up.

**Team:** Caleb (web app and server), Sam K (content programming, UI), Danni (producer), Sam P (textures), Jams (3D models), Harold (level design), Kiven (NPC models, rigging and art lead), Max (animation), Shannon (VFX), Shanan (sound).

## Key takeaways

### 1. Use an interaction people already know

The main question behind the project was whether a familiar interaction like texting could make a public game easier to join. It did. We never saw anyone struggle to work out how to join or what to do.

### 2. Test ideas you don't like

I didn't want character customisation at first. I thought it was copying Tomodachi Life for the sake of it. We tested it anyway, and it turned out to be one of the best entry points. Making your character is the first thing you do, and seeing them walk around the town ties you to it. People who made one were more likely to keep playing.

### 3. Impact needs a bit of imbalance

At first players' marks lasted all day, and the town quickly became cluttered. When every mark is loud, none of them stand out. We switched to marks that get overwritten, and did the same on the phone by showing fewer messages and highlighting one at a time.

### 4. Build rough and fast first

My biggest lesson: we took far too long to reach something we could test. I spent early time predicting problems and solving them in advance. Most of those problems did show up, but solving them early wasn't worth it. Next time I'll build rough and fast, write down the problems, and fix them when we actually hit them: quick then slow, not slow then quick.

### Latest update

The installation is in its final polish and exhibition prep, and I'm writing up the project as my honours exegesis at the University of Canterbury.
