# Welcome to Sunken!

We're excited to invite you to play this game presented by the Good-4!

## Game Logic Overview:

### Starting Phase:

The player will set the stage by narrating the basic story background, establishing their role as the God of the sea. Their ultimate goal is to flip over the entire island.

### Map Setup:

The island consists of multiple triangles, initially facing downward. The player can only see the type of each tile and the power cost required to flip them.

### Playing Phase:

The player can choose a tile to flip, provided they have enough power. Each flipped tile triggers different outcomes:

```python
if tile == new type of tile:
    # Introduction of basic ecological environment
elif tile == story tile:
    # Reveal the story
elif special effect in tile:
    # Apply the effect accordingly
```

Power points decrease with each action. As long as points are positive, the player can continue flipping, cultivating, applying strength, or ending their turn.

```python
while points > 0:
    # Player actions: flip, cultivate, apply strength, or end turn
    # Adjust points accordingly
```

The current turn ends, and points accumulate.

### Ending Phase:

If all tiles are flipped:

```python
if unflipped tile == 0:
    # Reveal the whole story
    # Congratulations!
```
