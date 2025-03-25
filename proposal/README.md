Sriram Soundar & Matheo Dwyer

MATH 244 Project Proposal

Source of the Data: The dataset was publicly available on Kaggle and was collected from Lichess.org, a popular online chess platform. The data includes over 20,000 chess games played by users on the platform.

Link to Data: Kaggle Chess Dataset

Collection Method: The data was collected through Lichess API, which provides access to game histories for users. The dataset includes games and moves from users who are part of large teams on Lichess, ensuring a wide range of players and game types. It does not specify any collection techniques such as random sampling, but it implies taking recent historical data.

Cases: Each case represents a single chess game played on Lichess.org.

Variables:
Game ID: Unique identifier for each game.
Rated (T/F): Whether the game was rated (True) or unrated (False).
Start Time: Timestamp of when the game started.
End Time: Timestamp of when the game ended.
Number of Turns: Total number of moves made in the game.
Game Status: The outcome of the game (e.g., "checkmate", "resign", "draw").
Winner: The winner of the game ("white", "black", or "draw").
Time Increment: The time increment (in seconds) added after each move.
White Player ID: Unique identifier for the white player.
White Player Rating: The rating of the white player at the time of the game.
Black Player ID: Unique identifier for the black player.
Black Player Rating: The rating of the black player at the time of the game.
All Moves in Standard Chess Notation: The sequence of moves made in the game, recorded in standard algebraic notation.
Opening Eco: The ECO code (Encyclopedia of Chess Openings) for the opening used in the game.
Opening Name: The name of the opening used in the game.
Opening Ply: The number of moves in the opening phase of the game.






Research Questions

Research Question 1: What factors (e.g., player rating, opening choice, time increment) are most strongly associated with a player's likelihood of winning a chess game? Specifically, how do these factors differ between white and black players?
Hypothesis: We expect that higher-rated players will have a higher likelihood of winning, regardless of whether they are playing as white or black. Additionally, we hypothesize that certain openings may be an advantage to white or black players, and that games with shorter time increments may favor players with faster decision-making skills or a higher-rating.

Research Question 2: How does the choice of opening (as indicated by the ECO code and opening name) influence the outcome of the game? Are certain openings more likely to lead to a win for white or black, and how does the length of the opening phase (opening ply) affect the game's outcome?
Hypothesis: We expect that certain openings will be more advantageous for white or black players, and that longer opening phases may lead to more balanced games, reducing the likelihood of an early decisive outcome.


Second Dataset

Source of the Data: The dataset was publicly available on Kaggle and contains historical match results from tier one men's international rugby teams (England, Wales, Ireland, Scotland, Italy, France, South Africa, New Zealand, Australia, Argentina). The data was collected from Wikipedia pages documenting international rugby matches.

Link to Data: Kaggle Rugby Dataset

Collection Method: The data was scraped from Wikipedia pages listing international rugby match results. The collection method appears to be comprehensive for tier one nations, though it doesn't specify exact date ranges or sampling techniques.
Cases: Each case represents a single international rugby match between tier one nations.
Variables:
date: Date of the match (YYYY-MM-DD)
home_team: Name of the home team
away_team: Name of the away team
home_score: Full-time home team score
away_score: Full-time away team score
competition: Name of the tournament (e.g., Six Nations, Rugby Championship)
stadium: Name of the stadium where match was played
city: City where match was played
country: Country where match was played
neutral: Boolean indicating if match was at a neutral venue (TRUE/FALSE)
world_cup: Boolean indicating if match was during a Rugby World Cup (TRUE/FALSE)

Research Questions 

Research Question 1: How do home-field advantage, competition type, and World Cup participation influence match outcomes in international rugby?
Hypothesis: We expect that home teams will win more frequently than away teams, especially in annual tournaments like the Six Nations. Neutral venues should reduce this home advantage.

Research Question 2: Which teams have the strongest historical performance, and how does this vary by competition?
Hypothesis: Southern Hemisphere teams (particularly New Zealand and South Africa) will dominate overall win rates. Underdog teams (Italy, Argentina) may perform better in World Cups than in annual tournaments due to increased match intensity.

