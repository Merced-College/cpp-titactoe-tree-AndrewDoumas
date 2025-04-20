[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19250048)
# cpp_tictactoe_tree



The purpose of the minimax function is to deterine what the best and worst plays for the AI are.

The GameState class is like a tree, because when it creates a child state it is similar to creating a new node in a tree structure.

The recursion stops for the minimax algorithm after it explores all the possible plays that could be made and selects the best move from that.



I learned that trees and recursion can be confusing to navigate sometimes, but they are very useful data structures. I would consider the AI to be smart for the tic-tac-toe game, but this version of the algorithm would struggle at other games. The AI is limited by the depth at which it can look to make moves. Tic-Tac-Toe is good for a low depth algorithm, but in a game like chess the AI would benefit from having an increased search depth for possible moves. If I had more time, I would look into improving the depth at which the algorithm searches for the best move.