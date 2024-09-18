# Shooting_Game
 
demo: https://youtu.be/Ah0aehp0L-0?si=UaHz-ejSifNku37u

Download Unreal Engine

How to Open: Content -> LearningKit_Games -> Maps -> MP2

Design Process:

My level includes the following elements, health packs, purple balls (collectible items), shabby buildings, trees, and three types of enemies: two patrollers, some mortar enemies (the glowing yellow ones), and some tree-type enemies.

The health packs scattered around the enemies for the player to increase health by 30 hp. For the collectible items, the purple balls, sometimes they can only be collected after jumping to the near windowsill in order to increase the game difficulty. The player needs to collect 7 purple balls to win the game.

Next is three kinds of enemies. The enemies are scattered mostly near the purple balls to protect them. The first is the pursuer enemy. There are two such enemy on the level. They follow a patrol path randomly around the starting point. Once they find the player, they will chase it until it is out of sight and then go back to their patrol path. The player will lose 5 hp if it happens to hit the pursuer enemy. The challenging part is, if the player cannot find a way to get rid of the pursuer enemy quickly, they will be constantly hit by the pursuer and lose many hp in a short time. The player can get rid of them by keeping a moderate distance with them or jump to touch their head to destroy them.

The second enemy is mortar enemies (the glowing yellow ones). Once the mortar enemies find the player coming near, they will randomly launch projectiles around itself at a close to middle range affected by gravity. The challenging part is, when the projectiles hit other objects, there will be a small circle that will knock back and damage the player by 10 hp. The player can destroy the mortar enemies by collide with the head (the glowing pink object) of the mortar enemies.

The most interesting part of my level is designing the tree-type enemies. They are scattered around the “real” trees, which is not easy for the player to detect. Once the tree-type enemies find the player coming near, they will constantly launch glowing-green sword-like projectiles at a middle to long range directly towards the player and damage the player by 5 hp. The challenging part is, the tree-type enemies have an “eye” to track the player and launch the projectiles according to the location of the player. It is even more threatening in the left part of the level where many tree-type enemies are gathered with the mortar enemies. Since the knock back effect of the mortar enemies will make it harder for the player to stay away from the sword- like projectiles of the tree-type enemies. The player can destroy the tree-type enemies by collide with its eye (the glowing white object) since the player cannot jump over the top of the “trees”.
