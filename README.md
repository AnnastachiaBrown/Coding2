# Game3Start

An Unreal 5.4.2 project that includes lessons from Game Design 2, as a starting point for Game Design 3.



GamePlay - https://youtu.be/16ymjHdV-9Q



The Game is to get the two dinosaurs locked behind the last door and get them to the front door so the player can leave. ‘I chose to add some art as my extra addition. I did art for some of the menus and then added in a couple models like for the dinosaurs and then the security  camera turrets. I also imported in some sky boxes so there is something interesting to look at in the grey box museum.

For sound I have background music and glass shattering when the player drops the glass dinosaur.

For the enemy AI, they can hear the player and go into an investigative state, attack the player when seeing them and when they get attacked. The enemies also have perception and will guess where the player goes.

For Saving and Loading I have it so the doors, coins and the regular dino’s location when dropped are saved. The health mana and stamina are saved as well and update every .1 second

My three items are the breakable dino, the regular dino and a key that has to be held to use at the door that locks the door that is holding the dinos. I also added in that the player can not melee when they are holding an item.

The bug I fixed was so the enemies can’t hear or perceive you when dead by destroying the actor after death. I put a delay on that way the player would most likely move away from the dead enemy as the disappear. I also fixed the UI not updating on begin play

For the reachable additions \& stretch, my enemies are the guards that hit and then a security camera turret. My melee cooldown is down to one second so the player can’t spam and then there is the previously mentioned addition to not being able to hit with an item in hand. The player can also Die when the AI turret is firing at the player but doesn’t take damage from the other AI Yet.

