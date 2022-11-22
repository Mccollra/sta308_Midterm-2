# sta308_Midterm-2
As coach, you get to decide: does your team go for a two point field goal or a three point field goal? 
SCENARIO
Your wildest dreams have been fulfilled and you are the head coach for the Michigan State Spartans!. You are in the winner-take-all championship game and are trailing by a single point with 2 seconds to play! You just called time out and have possession of the ball on the offensive side of the court. You have the opportunity for one more shot. What will you do? Go for a three point field goal or a two point field goal?

STATED PROBLEM
As coach, you get to decide: does your team go for a two point field goal or a three point field goal? Your code must consider both scenarios.

GOING FOR TWO
When you go for a two point field goal, there is a 60% chance your team completes the inbound pass (so 40% chance it is stolen and you lose the game). The player who receives the ball has a 55% chance of making the shot (you are awarded 2 points, and win the game). There is a 10% chance that player is fouled on the play. If fouled, they are awarded two foul shots and have a 60.5% chance of making each shot (each worth one point, so you may miss both, make one and tie or make 2 and win the game)). So by using this strategy it is possible your teams scores 0, 1 or 2 points, but the outcome is randomly determined by probabilities.

GOING FOR 3
When you go for a three point field goal, there is an 80% chance your team completes the inbound pass. The player who receives the ball has a 39.95% chance of making the three point shot (you are awarded 3 points, and win the game). There is only a 5% chance they are fouled on the play. However if fouled, they are awarded three foul shots and because this person is a good shooter, they have an 90% chance of making each of the foul shots (so they may make 0, 1, 2 or all 3 shots). The possible point outcomes from this strategy are 0, 1, 2, or 3 points but again random. You will win the game if your team scores 2 or 3 points.

PROGRAM
Runs multiple functions to simulate each scenario enough times to get a good enough understanding of potential outcomes and which play is the best play to call in regulation, as well as which play is the best to call when considering overtime as well. 
