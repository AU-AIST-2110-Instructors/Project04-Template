
# Part 4: Creative Extension

In this final part, you’ll have the opportunity to take everything you've learned and make the escape adventure game your own. Now that you’ve implemented a solid structure with room navigation, key collection, and locked doors, it’s time to get creative and expand the game in any direction you like.

This part is about giving the game more depth by adding new features, improving the narrative, and implementing more complex mechanics. Think of this as your chance to transform the simple escape game into a unique experience.

## Getting Started
- You can either start by copying the solution of part 3 posted in D2L, or continue on your own implementation.

## How to Submit

- Use the VS code Source Control Tab to submit your assignment:
    - Click on the `+` sign next to the files you want to include, in this case `escape.py`
    - Write a commit message, e.g., "Finished with part 4."
    - Select "Commit and Push".
- Alternativally, you can use git to add, commit, and push your changes:
    ```bash
    git add escape.py
    git commit -m "Finished with part 4."
    git push
    ```

## General Tips
- Make sure to frequently save and push your changes to your GitHub repository.
- Test your code after each significant modification.

## Suggestions for Expansion

The following are **just suggestions** and you don't need to implement all of them. You can choose ideas from the list, or come up with your own creative features and additions. These suggestions are provided to inspire you, but feel free to explore your own ideas.


### 1. Add More Rooms and Story Elements
Expand the house by adding more rooms, or even different locations like a basement, attic, or garden. For example, you could implement a locked room that contains important clues, but it requires a special key. Each room could have a unique description that adds depth to the narrative and environment.

- Implement new rooms with hidden passages, or even secret rooms that can only be accessed through a combination of keys or actions.


### 2. Add Puzzles and Challenges
Make the game more interesting by adding puzzles that players must solve to proceed. For instance:
- A **code** could be required to unlock certain rooms.
- Implement a **combination lock** for the basement, where the player has to solve a series of clues to obtain the code.
- Add **riddles** that give hints about where the keys or objects are hidden.

### 3. Enhance Object Interaction
Currently, the player can only find keys automatically. You could expand on this by requiring players to interact with objects more actively. For example:
- Introduce **searching mechanics** where players need to examine furniture, shelves, or drawers to find hidden items.
- Hide keys or other items behind objects that players need to move or unlock first.
  
### 4. Add Timed Challenges
You could introduce a sense of urgency by adding a **timer** that tracks how long the player has before something happens. This could be used to:
- Introduce a time limit before a door locks permanently.
- Implement a countdown where the player has to escape within a certain time, or they fail.

### 5. Implement an Inventory System
Instead of automatically picking up keys, you could introduce an inventory system where players must manage and use their items manually. The player would have to choose which item to use at the right time.

### 6. Introduce NPCs or Enemies
Introduce a mysterious character that gives cryptic clues or warnings.
Add an enemy or monster that the player must avoid. For example, certain rooms could be "unsafe," and the player needs to find hiding spots to avoid being caught.

### 7. Create Branching Endings
Give the player multiple ways to escape or fail, adding replayability to your game. For example:

One ending could be a successful escape through the front door.
A different ending could involve finding a secret tunnel leading out through the basement.
Failure could result from getting caught by an enemy, failing to solve a puzzle, or running out of time.

## Final Notes
By the end of this part, your escape game will be a unique creation, reflecting your personal style and creativity. Have fun, and push the limits of what you can do with the game!