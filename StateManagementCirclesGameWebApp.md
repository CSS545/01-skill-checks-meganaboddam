[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8842962&assignment_repo_type=AssignmentRepo)

For this circle's game, there are three states the user can be in. I only consider these three states (playing, exiting but intending to return, and completely exiting) because I am creating a very simple webapp game to practice state management. 
- The user can be playing the game. This is stimulated by entering the score page.
  - While the user is playing the game, they can artificially create game sessions
  - This mimicks how the user can leave and return as desired
  - In each game session, they can add thier "score". 
    - [I have not actually created a circles game for the purposes of this exercise] 
  - The number of sessions is tallied up and displayed; including the score in each session. 
- The user can exit the score page. This represents them exiting the game but intending to return. When they return to the game page, the sessions they inputted will remain stored.
- They can completely exit the game. THis is signified by canceling "http-server" package required to run the game locally. This resets the game.