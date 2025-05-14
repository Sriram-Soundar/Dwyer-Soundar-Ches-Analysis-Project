Source of the Data: The dataset was publicly available on Kaggle and was collected from Lichess.org, a popular online chess platform. The data includes over 20,000 chess games played by users on the platform.

Link to Data: https://www.kaggle.com/datasets/datasnaek/chess

Collection Method: The data was collected through Lichess API, which provides access to game histories for users. The dataset includes games and moves from users who are part of large teams on Lichess, ensuring a wide range of players and game types. It does not specify any collection techniques such as random sampling, but it implies taking recent historical data.

Cases: Each case represents a single chess game played on Lichess.org.

Variables: Game ID: Unique identifier for each game. Rated (T/F): Whether the game was rated (True) or unrated (False). Start Time: Timestamp of when the game started. End Time: Timestamp of when the game ended. Number of Turns: Total number of moves made in the game. Game Status: The outcome of the game (e.g., "checkmate", "resign", "draw"). Winner: The winner of the game ("white", "black", or "draw"). Time Increment: The time increment (in seconds) added after each move. White Player ID: Unique identifier for the white player. White Player Rating: The rating of the white player at the time of the game. Black Player ID: Unique identifier for the black player. Black Player Rating: The rating of the black player at the time of the game. All Moves in Standard Chess Notation: The sequence of moves made in the game, recorded in standard algebraic notation. Opening Eco: The ECO code (Encyclopedia of Chess Openings) for the opening used in the game. Opening Name: The name of the opening used in the game. Opening Ply: The number of moves in the opening phase of the game.
