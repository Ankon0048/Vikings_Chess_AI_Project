# Vikings Chess Game - AI-Powered Strategic Gameplay

## Overview
The Vikings Chess Game is an AI-powered strategic game developed using the Python Pygame library. It leverages advanced algorithms such as Minimax, Alpha-Beta Pruning, Genetic Algorithms, and Fuzzy Logic to create a challenging and responsive AI opponent. The project aims to demonstrate game theory principles through an engaging, strategic gameplay experience.

## Key Features
- **Advanced AI Algorithms:** Integration of Minimax, Alpha-Beta Pruning, Genetic Algorithms, and Fuzzy Logic.
- **Strategic Gameplay:** AI capable of optimal decision-making using advanced game theory techniques.
- **User-Friendly Interface:** Intuitive design for smooth interaction.
- **Competitive AI Opponent:** Offers a challenging experience by adapting strategies dynamically.
- **Educational Insight:** Provides a practical understanding of AI and game theory concepts.

---

## Game Rules

1. **Turn-Based Gameplay:** Players alternate turns to make their moves.
2. **Restricted Cells:** The center cell and four corner cells are designated as restricted.
3. **King Piece (Yellow):**
   - Moves only one cell at a time.
   - The goal is to move the king to any of the four corner cells.
4. **Attacker Pieces (Pink):**
   - AI-controlled pieces trying to capture the king.
   - Can move any number of cells horizontally or vertically.
5. **Defender Pieces (Green):**
   - Defend the king from being captured.
6. **Winning Conditions:**
   - **Player Wins:** The king reaches any of the four corners.
   - **AI Wins:** The king is surrounded on all four sides by attackers.
7. **Capturing Mechanics:**
   - A piece is captured when sandwiched between two opposing pieces or restricted cells.
   - Only one piece can be captured at a time.

---

## AI Strategies and Implementation

### **Minimax Algorithm with Alpha-Beta Pruning**
- **Goal:** Optimize AI decision-making through depth-based simulations.
- **Approach:**
  - Simulate all possible moves up to depth 3.
  - Evaluate moves using a heuristic evaluation function.
  - Prune branches that do not affect the final decision.

### **Genetic Algorithm**
- **Goal:** Evolve optimal strategies through selection, crossover, and mutation.
- **Approach:**
  - Generate a population of potential moves.
  - Evaluate them using a heuristic function.
  - Apply selection, crossover, and mutation to refine the strategy.

### **Fuzzy Logic System**
- **Goal:** Assess player performance through a fuzzy logic-based evaluation.
- **Approach:**
  - Assign membership values based on timing, move count, and board state.
  - Use fuzzy rules to determine whether the performance was excellent, good, moderate, bad, or worst.

---

## Class Diagram

The association and encapsulation of each class are represented in the following class diagram:

![Class Diagram](https://github.com/Ankon0048/Vikings_Chess_AI_Project/blob/master/Screenshot_3.jpg)

---

## Figures

- ![Class Diagram](https://github.com/Ankon0048/Vikings_Chess_AI_Project/blob/master/Screenshot_4.jpg)
- ![Class Diagram](https://github.com/Ankon0048/Vikings_Chess_AI_Project/blob/master/Screenshot_5.jpg)
- ![Class Diagram](https://github.com/Ankon0048/Vikings_Chess_AI_Project/blob/master/Screenshot_6.jpg)
---

## Conclusion
The project successfully developed an AI-powered Vikings Chess Game, integrating Minimax, Genetic Algorithms, and Fuzzy Logic for intelligent decision-making. These advanced techniques created a responsive and challenging AI opponent, significantly enhancing the overall gaming experience.
