# Mancala-using-alphabeta-pruning.
This program has two player classes. Each player class is supplied with calculate_utility
and alphabeta_parameters where utility function returns the likeness of the current state
based on Piece count and score count and returns their sum which is either positive or
negative. The alphabeta function gives the game state information on how much the game
needs to check in terms of depth. Higher, the time higher the depth will be. Among these
players each player has same utility function but different alphabeta function in order
to test which strategies might be better.
