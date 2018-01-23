---
#
# Page Layout (Leave As Is)
layout: guide_post
#
# Duty Metadata ================================================================
#
# Guide Title
title: "Neverreap"
#
# Guide Description (Shows Up in Google Search)
description: "Read our Guide on the dungeon Neverreap (Normal) where you'll face off against Nunyenunc, Canu Vanu, and Waukkeon."
#
# Primary Image (1500px Wide) & Thumbnail (500px Wide)
image:
    - url: "/assets/img/dungeons/neverreap.jpg"
    - urlSmall: "/assets/img/dungeons/small/neverreap.jpg"
#
# Search Terms (Include Nicknames, Name, Bosses, Difficulty)
terms:
    - term: "Heavensward"
    - term: "Neverreap"
    - term: "Nunyenunc"
    - term: "Canu Vanu"
    - term: "Waukkeon"
    - term: "Normal"
#
# Patch Information (Number & Name)
patchNumber: 3.0
patchName: "Heavensward"
#
# Difficulty (Normal, Hard, Extreme, Savage, Ultimate)
difficulty: "Normal"
#
# Player Level
plvl: 60
#
# Item Level
ilvl: 145
#
# Order (Combine plvl & ilvl - 70310)
order: 60145
#
# Orchestrion Roll
orchestrion: "TBD"
#
# Instance Type
instanceType: "dungeon"
#
# MTQ Capture Video Link
mtqvid: "YouTube URL"
#
# Dungeon Mechanics ============================================================
mechanics:
  - title: ""
    steps:
      - step: 01
        notes:
          - note: ""
#
# Multiple Bosses ==============================================================
bosses:
  # Boss Name ==================================================================
  - title: ""
    # Boss ID (Used in Sidebar Menu)
    id: "boss01"
    # Fight Sequence
    sequence:
      # Fight Phase
      - phase: 01
        # Attack Script
        attacks:
          - attack: ""
            # Duty Action (Include When Necessary)
            dutyActions:
        # Alerts
        alerts:
          - alert: ""
        # Phase Mechanics (Include Duty Gauges)
        mechanics:
          - title: ""
            notes:
              - note: ""
    #
    # Boss Attacks
    #
    # Paired Attack Tags: Marker
    # AoE Attack Tags: Cone AoE, Circular AoE, Puddle AoE, Donut AoE, Column AoE, Area AoE, Point Blank AoE, Raid Wide AoE, Proximity AoE, Cross AoE, Figure 8 AoE
    # Other Attack Tags: Knockback, Cleave, Buff, Debuff, Tankbuster, Stack, Spread, Tether, Stun
    # Unique Attack Tags: Mechanic, Animation, Spawn, Ultimate, Active Time Maneuver
    #
    # Use "attk-reg", "attk-combo", "attk-vari" to insert Attack Snippets.
    attacks:
      # Regular Attack *********************************************************
      - title: "Attack Name"
        phases:
          - phase: 01
        roles:
          - role: ""
        # Duty Action (Include When Necessary)
        dutyActions:
          - action: ""
        tags:
          - tag: ""
        notes:
          - note: ""
        images:
          - url: "/assets/img/image-path.png"
            alt: "Image Description"
#
# Single Boss ==================================================================
#
# Boss Name
#
bossName: ""
# Fight Sequence
sequence:
  # Fight Phase
  - phase: 01
    # Attack Script
    attacks:
      - attack: ""
        # Duty Action (Include When Necessary)
        dutyActions:
    # Alerts
    alerts:
      - alert: ""
    # Phase Mechanics (Include Duty Gauges)
    mechanics:
      - title: ""
        notes:
          - note: ""
#
# Boss Attacks
#
# Paired Attack Tags: Marker
# AoE Attack Tags: Cone AoE, Circular AoE, Puddle AoE, Donut AoE, Column AoE, Area AoE, Point Blank AoE, Raid Wide AoE, Proximity AoE, Cross AoE, Figure 8 AoE
# Other Attack Tags: Knockback, Cleave, Buff, Debuff, Tankbuster, Stack, Spread, Tether, Stun
# Unique Attack Tags: Mechanic, Animation, Spawn, Ultimate, Active Time Maneuver
#
# Use "attk-reg", "attk-combo", "attk-vari" to insert Attack Snippets.
attacks:
  # Regular Attack *************************************************************
  - title: "Attack Name"
    phases:
      - phase: 01
    roles:
      - role: ""
    # Duty Action (Include When Necessary)
    dutyActions:
      - action: ""
    tags:
      - tag: ""
    notes:
      - note: ""
    images:
      - url: "/assets/img/image-path.png"
        alt: "Image Description"
---