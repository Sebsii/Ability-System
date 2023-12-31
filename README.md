# Ability System in Ruins of the Lost
Many games in the action-roguelite genre have some kind of an ability system. From a game designer's perspective I see it as a tool to broaden the amount of build paths on the one hand and on the other hand to make the moment to moment gameplay more diverse and interesting. Naturally, we also wanted to have one. Easier said than done…

## Ruins of the Lost (RotL) in a nutshell
To start, here is a short summary of RotL’s combat: The player is equipped with a bow and arrow. At the start with just a simple bow and in the course of a run with more elaborate bows, think of splitting projectiles, rapid fire or lightning bows. Multiple of those can be carried and swapped through. This represents the “basic attack”. Movement-wise the player is able to dash, where they are unhittable for the duration. The player has to always be on the lookout for enemies' attacks and has to move pretty much constantly while raining down arrows onto their foes.

## Ability systems
We wanted to have a secondary attack, another way of interaction with the world. Like every good game designer, what was the first thing I did? Correct, I looked at what others do. I want to categorize in three classes of systems:
Firstly, the single ability. This is characterized by having this ability in every run, always. Here I immediately think of Hades, where you have your right click, where you throw a projectile, which can be modified and enhanced to suit your build.
Secondly, the character/weapon/equipment based ability. In this case the player can choose, which ability or set of abilities they want to have for a single run. Here, something like Slay the Spire and Risk of Rain 2 come to mind, where you choose the character at the start of the run, which dictates the way you play.
Finally, the swap-at-any-time abilities. Where the player is free to choose during a run. Here, I think of the weapons in Enter the Gungeon. Maybe this category is a little far fetched as in reality this is what Enter the Gungeon and also we did for our basic attack. Maybe it does not fall into an “ability system” per se, but certainly into an attack system.

## The journey
So, what did we decide on? At first, we wanted to have one ability slot, where different abilities can be inserted during one run. At this point I want to mention that the bow and arrow basic attack was not yet there, so both systems were developed in parallel and influenced each other. I prototyped some abilities, which I thought could be interesting including a black hole, a spin attack, a shield, a dropping ranged AoE attack, a AoE knockback, an exploding grenade and a fast, to-the-side pushing, projectile.

|   |   |
|---|---|
![](black_hole.gif)  |  ![](push_aside.gif)
![](dropper.gif)  |  ![](garen.gif)

The feedback was mixed, but more on the positive side. OK, not a great success, but a step in the right direction. I wanted to have more interaction between the abilities, so I implemented a second ability slot. The hope was that the player uses the abilities synergistically. At least with the abilities at hand, this did not work at all, with very few exceptions. Pretty much the only one, which made sense was the black hole, which clumps up the enemies in combination with a ranged AoE attack, naturally. But other combinations did not make much sense, nor did they bring any fun. Somehow to make this thing work, I figured that ideally one given ability would have to synergize with all other abilities. An impossible task. The final nail in this system's coffin was the realization that we could not even create the visuals to our high standards in time. Consequently this system was scrapped (for now) and instead we switched to a much simpler single ability approach, where we chose the grenade as it was the most satisfying and it looked the best at that point in time.

![](Unity_cMdjzqIaLx.gif)

## Conclusion
To some extent, the way it is now, with bow and arrow switching and a single ability it is like we wanted it in the first place. One system, which brings variety by providing different play styles and one which accents it. Reflecting on the approaches we took in the past, does it really make sense to have two variable attack systems in parallel? Most of the time the player settles on one playstyle pretty early in a run depending on the early items one gets and the second system gets adjusted to the first one to fit the best. If this is the case, as a game designer, I think it makes more sense to just let the player decide which playstyle route they want to go in the first place. Maybe that is why so many games do exactly that with a character based ability set. What does this mean for RotL? We can try to let the player choose their ability at the start of a run and see what happens. I don’t think it’s a silver bullet, which erases all the gameplay problems, but a battle-tested approach to achieve variety.
