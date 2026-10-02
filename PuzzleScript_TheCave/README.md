[The Cave.html](https://github.com/user-attachments/files/32956641/The.Cave.html)
The Cave is a game created on PuzzleScript. This puzzle game has 12 levels where players must navigate through different maps to piece together the story of main character and what really happened in The Cave. 

The main rules for the game are:
  1) Stepping on a hole will cause the level to restart.
  2) Players must push boulders to fill holes in order to walk over them safely to collect items.
  3) Each item collected will either give the player an advantage in the game or insight into the storyline. 
Walkthrough for how to play each level:
  1) The first level starts with introductory story lines, as well as instructions to "roll right". Right arrow key in order to complete the level by picking up an "eye" for your character to gain sight.
  2) Because the character only has one eye, the game play will be through a small "flashlight" view until the player picks up another eye to gain the full sight ability. In order to complete level two, push the boulder up to fill the hole. Collect the "leg" on the right side.
  3) Level three: The player will spawn back where the leg they had picked up was. Position the character to the left of the boulder, and "push" it to the right using the right arrow key in order to fill another hole and access "Journal Entry 1".
  4) Level four: The player will spawn back where they collected the journal entry. Move to the left, back over the filled hole two spaces. Then move down the map until you can no longer move. Move right until you see three more boulders. Move downwards and position the character to the left of the bottom most boulder. Push it once to the right. Position the character beneath the boulder and push it up to fill the holes above. Now, with two boulders left, position the character to the left of the new bottom most boulder. Push it to the right once. Position the character beneath the boulder. Push it up all the way to fill the next hole above the previously filled hole. The player may now access the second leg piece.
  5) Level five: The player will spawn back where they collected the second leg. Move to the right over the filled holes until no longer able to move right. Move down until you reach three more boulders. Push the left most boulder down to fill the hole. Continue to move down to collect the next journal entries.
  6) Level six: The player will spawn back where they collected the journal entries. Move up over the filled holes. Move to the right until no longer able to. Move up until no longer able to. There will be one boulder. Push this boulder to the right once. Go around the boulder and position the character beneath it. Push the boulder all the way up to fill the hole and access an "arm".
  7) Level seven: The player will spawn back where they collected the arm. Move down over the filled hole until no longer able to. Move to the right until you encounter two more boulders. Push both boulders to the right to fill the holes and access the "eye". Now that the player has collected two eyes, full vision has been restored.
  8) Level eight: The player will stay where the eye was collected. Move upwards to collect the second arm.
  9) Level nine: The player will spawn back where they collected the second arm. Move back through the map to the ladder located at the bottom of the map.
  10) Level ten: The player will spawn on a different map as if they had fallen into the hole that was next to the ladder. Move to collect the "Brain" at the top right of the map.
  11) Level eleven: The player will spawn in a memory. This memory is located in a log cabin. Move the player towards the doors on the left wall of the map.
  12) Level twelve: The player will spawn back at The Cave. Walk left towards the red explosive in order to light it.
  13) There will be ending dialogue as well as a Thank You message after a black screen.

Walkthrough on the story for each level:
  1) The player starts off with a black screen, not realizing who their character is, or what to do. By "rolling" right, the player obtains an eye and gains sight.
  2) By collecting the "leg", the player is able to gain some knowledge that their character is probably not a normal human, through the dialogue as well as the changing of the character to add a leg.
  3) By collecting the first journal entry, the player is able to understand that there is something else living where they are playing. This build suspense as the player tries to escape where they are.
  4) By collecting the second leg and seeing that it is a different color and shape, the player can start to wonder what is wrong with their character and start believing that the character is an unreliable narrator. The character's dialogue is also to build suspense as it seems more of something a monster building itself again would say.
  5) By collecting journal entries 12 and 20, the player now knows for sure that there is something living within The Cave. The dialogue also builds suspense and a sense of urgency to quickly complete the puzzles and escape The Cave.
  6) Collecting the first arm provides another mysterious dialogue from the character.
  7) By collecting the second eye and gaining back all vision, the player is able to see a bloody arm on the screen. This is to create urgency, suspicion, and curiosity as the player must collect the second arm in order to progress.
  8) By collecting the second arm, the player receives a false sense of hope with the dialogue that says they may now escape using the ladder that the player may have seen in earlier levels as they played through the map.
  9) The ladder's collapse provides the dialogue "I can finally return home", to provide the player with false hope, as well as slightly suggest that when the character falls, they are actually falling into the hole, which is deeper into The Cave that is there home.
  10) By collecting the brain, the player now is certain that their character was not human and was building pieces of themselves the entire game.
  11) The memory shows the backstory of the game and where the journal entries came from. As well as confirms that the "monster" was collecting pieces to build itself.
  12) The ending shows the true main character falling to their death after "killing" the monster that had been tormenting their town. The dialogue "At least now I can return home..." references dialogue from earlier in the game. While the true main character is able to go "home" (reunite with their family after death), the "monster" also returns home to its cave.

Walkthrough on the code:
  1) Each level had the win condition: NO Collectible
         Most of the level's collectables are body parts or journal entries. Level 1's collectable is a transparent item placed to the right of the player. Level 9's collectable is the ladder. Level 11's collectable is either door that you exit the cabin from. Level 12's collectable is the explosive.
         The win conditions were that the player must be standing on one of the collectables.
  2) Each level had a different player sprite. This was so that all the collectables could be present on the map at the same time, but players could only collect those collectables in a certain order depending on which sprite they were playing as. Different player sprites also carried different fields of visions.
