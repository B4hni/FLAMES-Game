# FLAMES Game

FLAMES is a popular childhood game used to predict the nature of a relationship between two people based on their names. The acronym "FLAMES" stands for Friends, Love, Affection, Marriage, Enemy, and Siblings. This simple Python script implements the FLAMES game logic.

## How the Game Works

1. **Input Names**: The game takes two names as input.
2. **Remove Common Characters**: All common characters between the two names are removed.
3. **Count Remaining Characters**: The total number of characters left after removing common characters is calculated.
4. **Determine Relationship**: Using the remaining character count, the game determines the relationship between the two names based on the acronym "FLAMES."

### Acronym Breakdown

- **F**: Friends
- **L**: Love
- **A**: Affection
- **M**: Marriage
- **E**: Enemy
- **S**: Siblings

## Example Gameplay

1. **Input**: 
   - Player 1 name: "Alice"
   - Player 2 name: "Bob"
2. **Processing**:
   - Common characters are removed.
   - Remaining characters are counted.
   - Relationship is determined using the FLAMES acronym.
3. **Output**:
   - The game will output the predicted relationship, e.g., "Friends," "Love," etc.

### Example Output

```plaintext
Player 1 name : Alice
Player 2 name : Bob
Relationship status : Marriage
