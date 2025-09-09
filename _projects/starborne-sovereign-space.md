---
title: "Starborne: Sovereign Space"
description: "A free PC Space MMORTS game set in a rich Sci-Fi world."
categories: [Projects, Game]
permalink: /projects/starborne-sovereign-space/
image:
  path: /assets/img/projects/sovereign-space-logo.png
  alt: "Starborne: Sovereign Space Logo"
order: 1
---

![Starborne: Sovereign Space Logo](/assets/img/projects/sovereign-space-logo.png)
_Starborne: Sovereign Space_

Starborne: Sovereign Space is a free PC Space MMORTS game set in a rich Sci-Fi world. Build and expand your empire, fight and forge alliances on a huge seamless strategic map.

- **Genre:** MMORTS, 4X
- **Platform:** PC
- **Release date:** 2020 (beta)
- **Duration:** 1,5 years

{% include embed/youtube.html id='_k-Jxhk5WrM' %}

## Notable Contributions
My involvement with the project officially started in August 2020 when, after significant contributions to the community, I was recruited as a part-time community manager for the game.

Then I was hired as a full-time developer in September 2021, mostly for support and maintenance, as the rest of the tech team had moved on working on the new title Starborne: Frontiers. In collaboration with the game designer, we worked on fixing major bugs and design oversight, as well as introducing new mechanics and new maps. At the end of my first month, we were already releasing a first small patch that was solving some of the most pressing issues.

### Optimizations
My most notable contribution was some serious optimizations of the game, specifically on two panels: Movements and Fleets. Both had acquired a terrible reputation as they constantly caused the game to stop responding and crash, so much so that the players made countless memes about it.

![Not Responding Meme](/assets/img/projects/sovereign-space/meme.gif){: .left } 	
![Not Responding More Meme](/assets/img/projects/sovereign-space/meme.png){: .right }

Mostly the Fleet panel was a massive problem, as it contained a lot of game objects, and would entirely refresh every time the player took an action in-game. Reducing the refreshes to only the elements that needed to be, and only when necessary, helped tremendously. Then it was a matter of simplifying the design.

![The Fleet Panel](/assets/img/projects/sovereign-space/fleet-panel.png)
_The fleet panel_
