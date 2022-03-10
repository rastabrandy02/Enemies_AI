# Introduction to the Artificial Inteligence
In videogames, the artificial intelligence is used to generate responsive behaviours against certain situations in non playable characters. It is mainly used to improve the game-player experience rather than machine-learning (but it can also be used).
The AI in videogames was popularized during the arcade golden age of arcade games, making different difficulty levels, alternate movement patterns and in-game events driven by the player actions. 
Modern games use AI to implement pathfinding, decision trees, data-mining and procedural content generation.
For the artificial intelligence of the enemies is very common to use some type of state machine, this way it's easier to manage the behaviour of these entities depending on the current state of the game.
# Combat archetypes
In this section we will review the different archetypes of RPG enemies that you can find and their main characteristics. 
## Agressive
This archetype of enemy is the most common one. They usually have low life pool and low damage because their main function is to fill the battle. They will attack without any special priority and they don't usually cast special abilities or magic skills.
## Anti-Tank
Those enemies are designed to melt the characters with more health or defenses, they usually have a large life pool and strong single-target attacks. They usually priorize attacking the tanks of the party but they are not restringed to these targets.
The anti-tanks are usually enemies with some crowd control or altered state weakness because the player is intended to leave these enemies out of combat for some turns while they focus in higher priority targets.
## Tank
The tanks are enemies with high life pools, resistances or defensive skills. Some of them have also the ability to drive the attention of the party to them, leaving the high priority enemy targets alive.
## Assasin
This archetype of character is characterized by their high damage output, usually targeting characters with low hp/defenses with single target attacks. If the player doesn't focus on these enemies soon enough they might become a serious threat, specially for the mages and healers.
## Caster
The casters have low life pools and high damage attacks. They use multi-target skills often so they can drain the life and mana of the whole party in a couple of turns. 
Also, if they are combined with other archetypes, can become a serious threat as they weaken the characters while others finish them.
## Support
The supports are identified by their healing and buffing abilities, making the rest of the enemies more difficult to beat. They have low life pools and almost never attack directly but they are designed to be a high priority target for the player because leaving untouched might transform an easy encounter into a really hard battle.
## Spawner
The spawners have the ability of calling more monsters into battle and they will make that for the most part, attacking once in a while or when the battle is full of monsters. They usually have low life pools so the player can burst the spawners to stop the reinforcements.
## Merger
They usually have low life pools and damage. Their main characteristic is that they will attack or call more monsters of the same type into battle at a similar rate. If the number of monsters reaches a certain amount, they can merge into a more powerful enemy. The player is expected to kill the little mergers faster than they appear and use multi target skills to contain the reinforcement rate to prevent the strong enemy from appearing.
## Reward
These enemies have high life pools/defenses and their probability to flee is very high. The main characteristic of this archetype is the reward they give when slain (gold, xp, items...). Those characteristics make the reward enemies a high priority target because the player wants to beat them before they flee, increasing intrisically the difficulty of the battle just because the party is not focusing the rest of enemies.
# Other uses of artificial intelligence
## Aggro
The aggro is a range around the enemies in which, if the player goes trhough it, the enemies will start chasing them to begin the battle encounter.
In case that the player is underleveled for the current zone, the enemies will have increased aggro range and chase the party faster.
This is a natural way of communicating the player that the enemies are stronger than them because they see the player as a prey.
## Flee
If the player is overleveled for the current zone, the enemies will try to run away instead of chasing the party.
Also, if the player starts a battle with underleveled monster, they might try to flee out of combat.
This is a natural way of telling the player that they are stronger than the enemies because those are trying to scape from the party.
## Block escape
If the party tries to flee out of combat and fails, the enemies will have an extra turn so the option to flee because the enemies are too strong is a risk itsefl. The players are forced to plan when they are entering some zones or fighting against certain enemies, also they are encouraged to use high-cost skills or consumable items before trying to flee, because if they don't manage to scape, the death of a party member will be more punishing than the use of these tools.
## Item usage
If an enemy is able to drop a specific item and certain conditions are met during battle, the enemy will use this item to help themselves or other enemies in combat.
## Charming/Taming
The charm is an altered state that makes an enemy help your party for a specific number of turns. Charmed enemies are not controlled by the player so they will beahave as usual but against the other enemies.
If the player uses certain abilities and/or items onto an enemy it might want to join your party when slain. These enemies act as complete characters so you can continue the game using the tamed enemies equiping, leveling and controlling them.
# Example bosses
Now I will use some bosses from the Dragon Quest saga to make some examples of their specific behaviour and what strategies encourage to the player.
## Malicious grey gordon
This boss acts as a spawner and a support so it will call more monsters into battle and buff/heal them. The spawned enemies are casters and supports. The attacks of this boss and those of the spawned enemies are almost all altered state skills, making the battle incredibly difficult if the player doesn't have a plan and lets the enemies buff themselves. 
This boss encourages the player to use altered states onto the boss to manage the spawned enemies first and then trying to burst the boss itself as fast as possible before it spawns more enemies.
## Mortamor
The first phase of Mortamor is a caster archetype, the second phase is an anti-tank archetype and the third phase is one caster and two supports.
This changes of the boss behaviour exist to make the player change their strategies depending on the current state of the battle, using some skills more often than others, reserving the mana of specific characters for some phase or defending at certain moments of the battle with the most vulnerable characters.
## Psaro 
Psaro is a very interesting boss beacuse it has 7 phases, through wich it will be loosing partso of its body and then regenearating them in a stronger way, changing its behaviour accordingly to its appearence. For example, when it has two arms it is capable of doing multi-target physical attacks, when it looses one it will only make single target attacks and when loosing both it will only cast spells. 
When the battle continues it will change its appearence drastically and start casting more powerful spells, it will grow arms and legs, regaining the ability to do physical attacks and finally growing a second head, gaining the ability to make 2 actions each turn.
This boss encourages the player to burst the most dangerous phases and healing/buffing the party in the less difficult phases while maintaining a correct mana economy to be able to burst the final phase, which is the most difficult.
## Calasmos
This boss is very difficult, it has a lot of resistances and dangerous spells but, if the player uses a specific item from a secondary quest, it will become more manageable.
The use of this item is transmitted to the player through the storyline, there's not a specific message telling the player to use it, there's only the knowdledge that the player has achieved playing and talking to the party and other NPC's.
This makes the player more engaged with the storyline and gives the sensation that they have discovered the weakness of the final boss by themself, making it specially rewarding just because the stories and legends of the world feel real.
