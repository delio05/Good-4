# logic about the game skeleton
  # Starting up phase:
  
  player will be convey the basic story background, which will imply their identity in the game as the God of sea, and their goal is to filp over the whole island.

  # map set up

  the island is made with multiple triangles, and back side up, the player can see no more than what type of the individual tile is and the power cost to filp them

  # playing phase

  the player can choose which tile to flip over as long as they have enough power, with each tile they flip:
    if tile == new type of tile:
      introduction of basic ecological environment
    if tile == story tile:
      reveal the story
    if special effect in tile：
      apply the effect accordingly
  power points--;
  while points > 0:
    ables player to flip, cultivate, apply strength, or end turn
    point-- accordingly
  current turn ended
  points+=points addup

  # ending phase
  unflipped tile==0:
    reveal the whole story
    Congradulation!
    
