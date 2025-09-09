---
title: "Starborne: Frontiers"
description: "A free-to-play tactical autobattler with hundreds of unique ships."
categories: [Projects, Game]
permalink: /projects/starborne-frontiers/
image:
  path: /assets/img/projects/frontiers-logo.png
  alt: "Starborne: Frontiers Logo"
order: 2
---

![Starborne: Frontiers Logo](/assets/img/projects/frontiers-logo.png)
_Starborne: Frontiers_

Starborne: Frontiers is a free-to-play tactical autobattler with hundreds of unique ships. Form your fleet, customize it with a variety of equipment, and use strategy to create the perfect battlefield formation. Take on bounties, engage in the PvP arena, and bring order to the Frontier.

- **Genre:** auto-battler strategy
- **Platform:** Android, Apple, Steam, PC
- **Release date:** 2022 (beta), 2024 (1.0)
- **Duration:** 3,5 years
- **Website:** [Starborne: Frontiers](https://starborne.com/frontiers)

{% include embed/youtube.html id='gUfEq3QFRqo' %}

## Notable Contributions
In March 2022, a few months before the beta release, I started working on Starborne: Frontiers as part of the all-hands-on-deck efforts to get the game in the best shape possible.

### Upgrade Equipment
My first task was a complete redesign of the equipment panel, in order to better convey how the equipment stats work. In collaboration with the UX/UI designers, we worked on several iterations, especially regarding the animations and the various resolutions supported.

{% include embed/youtube.html id='LuljMHu42vs' %}

### VIP Rewards System
In April 2024, the 1.0 update introduced the VIP rewards, a level that increases with purchases from the store, and granting permanent account-wide bonuses.

Aside from the UI implementation, I’ve also designed and implemented the server-side system. It meant rewriting the whole currency storage system to accommodate for the addition of temporary or permanent bonuses. We eventually migrated all currency bonuses to that new bonus system.

![The VIP Rewards](/assets/img/projects/frontiers/frontiers-vip-rewards.png)
_The UI for the VIP rewards_

### Overall redesign of the Arena
The Arena that had been mostly untouched since the beta release in 2022, and I tackled its complete redesign in early 2025, which I tackled. This needed a complete refactoring of the client-side code for the Arena, as we had kept adding things without ever looking at the big picture, but also adapting the server-side systems to send the required information.

The new interface is now displaying more information to the players and putting more emphasis on the player versus player experience.

{% include embed/youtube.html id='9_SQClFfuUM' %}
