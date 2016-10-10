+++
draft = false
date = "2009-09-14T03:35:36-07:00"
title = "Making PvP Scale"
tags = "up-past-midnight"
+++
{{< figure src="img/zerg_rush.png" >}}

When PvP in computer games was first introduced, I'd have to assume that participant scaling wasn't even on the radar. After all, it's a bit hard to envision a "zerg" in Pong. As games have grown in both complexity and scale, however, the problem of how to make PvP fun regardless of how many people are involved in it is a real and complicated one.

As it currently stands, most player combat systems in multiplayer games consist of two elements, which I'll refer to as technique and strategy:
<ul>
  <li><span style="background-color: #ffffff;">"Technique" refers to technical skill: generally a quality of individual players or small groups, this category would include things like twitch aiming, bunny jumping, interrupting enemy actions, coordinating spikes on a target, and so on. FPS games tend to be heavy on technique.</span></li>
       <li><span style="background-color: #ffffff;">"Strategy" (in the context which I'm using for this article) refers to a wider view of the battle: where resources are relative to one another on the battlefield, elements of surprise, class compositions, and reinforcements are examples. Many MMORPGs currently focus on this aspect in battlefield-style PvP.</span></li>
</ul>
<!--more-->How does this play into PvP scaling? Each of these elements heavily favors its own particular scale of combat, if existing games are anything to judge by. Technique tends to lend itself to solo and small-group combat by its very nature - individual skill shines most when the number of individuals involved is low. As the number of participants involved in a battle grows, the strategic elements of the fight become more and more important until eventually they dominate the fight (the classic example being "victory through superior numbers," also known as "zerging").

The crux of the problem arises in this transition of combat elements along the scale spectrum: it's hard to design a game that integrates both categories of combat elements in a cohesive and scalable manner. It's even harder to make that game appeal to fans of both types.

Some games don't even bother to try making encounters scale fluidly, and instead take the route of partitioning PvP into different areas, with each area having a set scale - MMOs such as WoW and WAR are examples of this strategy. WAR's RvR and WoW's Wintergrasp/AV aim heavily towards the strategic element, while the other instanced combat focuses on small-group PvP. This approach has the advantage of simplifying combat design for each of the areas, but it comes at the cost of a balancing nightmare - player abilities have to be considered in all of the possible contexts within which they might be employed.

Another even more popular approach is to simply not scale at all - most games simply pick a target scale and stick to it. This is the case with almost all non-MMO games currently on the market. While simple, this approach is rather limiting - you'd run into trouble if you wanted to play an L4D game with your entire 50-member EVE corp.

Thus we arrive at the real challenge: making games which allow battles to scale in size dynamically, while still maintaining as close to the same balance between technique and strategy with any number of participants. *(Stay tuned, I'll be continuing this discussion in a later article.)*
