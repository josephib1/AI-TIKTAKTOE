# TIKTAKTOE GAME

## Abstract:
This scientific report presents a project that implements a TIC TAC TOE game with an artificial intelligence (AI) opponent. The project utilizes the pygame library in Python to provide a graphical user interface and incorporates a simple AI algorithm based on the minimax algorithm. The report provides an overview of the project's objectives, the implemented methods and algorithms, and the experimental results.

## Introduction:
The objective of this project is to create an interactive and challenging gaming experience by implementing an AI opponent for the game of Tic Tac Toe. The project combines game development, artificial intelligence, and user interface design to provide an engaging gameplay environment.
Getting Started:
To get started with the TIC TAC TOE AI project, you need to have Python and the pygame library installed on your system. Once the dependencies are set up, you can run the project and start playing Tic-Tac-Toe against either a human opponent or the AI.

## Methods:
### 2.1 Game Logic:
The game logic component handles the rules and mechanics of the Tic Tac Toe game. It tracks the game board, determines the final state of the game, and checks for winning conditions. The game logic ensures fair and accurate execution of the game.

### 2.2 Artificial Intelligence:
The AI component implements a simple AI algorithm based on the minimax algorithm. This decision-making algorithm evaluates different game states, enabling the AI opponent to make strategic moves and provide a challenging gameplay experience. The AI component offers multiple difficulty levels, from random moves to intelligent moves based on the minimax and Alpha-Beta algorithm.
To change between them what you need to do is to comment what you want to use and uncomment the other:
            # minimax algo choice line 221
            #Alpha-Beta algorithm choice line 222
            #---to use alphabeta uncomment line 222 and comment line 221---
            
            eval, move = self.minimax(main_board,False)  
            #eval, move = self.alphabeta(main_board, float('-inf'), float('inf'),             False)
            
You can find the minimax function In the code line 163 and the alpha beta function in code line 113.

### 2.3 User Interface:
The graphical user interface (GUI) is developed using the pygame library in Python. It provides a visually appealing game board and interactive elements for players to mark their moves and observe the AI's moves. The GUI enhances the user experience by offering real-time feedback and visual indications of player moves.

Results and Discussion:
The project was evaluated by testing its gameplay functionalities and observing the AI opponent's performance. It successfully created an interactive gameplay environment with an AI opponent. Players can choose between PvP mode or challenging the AI opponent by changing this line of code number 239:
        self.gamemode = 'ai' # pvp for 2 players or ai for AI

The experimental results showed that the implemented minimax algorithm provided a competent AI opponent capable of making strategic moves based on the current game state. The difficulty levels effectively influenced the AI's decision-making process, providing a range of gameplay experiences for players. The user interface elements enhanced the gameplay experience by offering clear visual feedback and intuitive controls.
NOTE: Every crucial function and line of code is accompanied by descriptive comments.

## Conclusion:
The TIC TAC TOE AI project successfully combines game development, artificial intelligence, and user interface design to create an engaging and challenging gaming experience. By implementing the minimax algorithm, the AI opponent offers intelligent moves, providing players with a challenging gameplay experience. The pygame library facilitates the creation of an intuitive graphical user interface, enhancing the overall user experience. The project demonstrates the effective integration of AI techniques in traditional game development.

## Some pictures:

![1](https://github.com/josephib1/AI-TIKTAKTOE/assets/105210115/c9303680-21b8-4711-81e8-0a136e970d84)

![2](https://github.com/josephib1/AI-TIKTAKTOE/assets/105210115/6de77a8a-a205-4c3e-b756-4189a7a4fdd9)
