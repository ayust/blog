+++
draft = false
date = "2009-09-07T02:55:37-07:00"
title = "Preventing Cheating in Online Games"
tags = "up-past-midnight"
+++
If I were forced to guess, I'd probably be safe with the assumption that cheating has been an issue for nearly as long as online multiplayer games have existed. As more and more games move into the realm of internet play, the question of how to deal with those who choose not to play by the "rules" of game mechanics has become a very important one in the realm of game design.

{{< figure src="img/drhax.jpg" caption="If you don't know the origin of this image then you are definitely missing out." >}}

Initially, it was enough to just have the powers that be dealing with miscreants - back in the days of MUDs, typically a few admins/arches or whatever the game masters of the particular server in question happened to call themselves.

As online games became more popular and evolved, so did methods to cheat in them. It became far harder to tell what was actually cheating, and what was just someone with really good aim. Thus, other solutions to the cheating problem were invented: "cheater detection" programs like Punk Buster came into vogue as a way of deterring attempted cheaters. Unfortunately, as anyone with experience will tell you, such programs are playing a cat-and-mouse game with the developers of cheats, and the game is one that they tend to be losing - after all, the cheat developers have the advantage of initiative: they force the anti-cheat programs to react to their new inventions.

<!--more-->One of the issues with cheat-prevention programs is that they're forced to make a trade-off between intrusiveness and effectiveness - the less intrusive they are, generally, the easier they are for a cheat developer to bypass or work around in such a manner as to make their cheat undetectable by the program. While some companies like Valve have been moderately successful in balancing both factors with technologies like VAC, other anti-cheater solutions seem to have had less success - GameGuard is an (in)famous example of an anti-cheating solution that is often considered both overly intrusive and disappointingly ineffective, thus leading to many complaints about its usage in various games.

From my experience, though, the best solution avoids these problems entirely. Instead of trying to play the cat and mouse game, it takes the approach of a military general and wins the war before the battle is even fought. This is done through both smart client-server design decisions and intelligently-designed game mechanics. By making sure the client is only trusted with information that *should* be available to the player, and double-checking that what the client says the player is doing is really something they're allowed to do, the potential for cheating is greatly diminished.

Likewise, avoiding mechanics that are well-suited to automation (which also tend to be those that players don't find fun a lot of the time, imagine that!) can greatly reduce the desire for many players to cheat in the first place. One good example would be a comparison of the "aura twisting" mechanic from EQ, DAOC, WAR, and certain other games compared to always-on auras such as those of Aion's Chanter class. It's not really hard to understand why many players of the former set of games might resort to automation via an external program or keyboard macro to twist auras; the mechanic as a whole is rather mindless and boring. There's no real good reason to have it as part of a game's design, so why include it? Instead, simply allowing a player to select a set number of auras to have active (as Aion's chant mechanic does) achieves the same overall effect as far as buffing other players goes, but without the finger-tiring mashing of keys that doesn't actually contribute to interesting play.

Hopefully as time goes on, developers will put more and more effort into "designing out" cheating instead of simply trying to block it out after the fact via inherently limited means.
