# Bowling_Score_Calculator
App to allow for quick calculation of potential bowling scores based on current bowling score.

Bowling is a sport that bases player scores on a combination of different factors.  This can be a 'Raw' score and a 'Combined Handicap' score. Typically bowlers attempt to knock down 10 pins at the end of the alley each frame. For each pin knocked down the bowler scores a point.  Each frame allows for the bowler to bowl twice to attempt to knock down all 10 pins.

Some special conditions to consider.
Strikes: A bowler scores 10 points, plus the score for the next two throws.  10pins(strike) + 2pins (throw 1) + 7pins (throw 2) = 19pins
Spares: A bowler scores 10 points, pluse the score for the next throw. 10pins(spare) + 2pins = 12

The 10th frame (Last frame) potentially allows for a bowler to bowl 3 times instead of just 2.  This means that a bowler could technically bowl 3 (first throw is strike the bowler gets 2 more throws to complete the strike in the 10th frame) strikes in the 10th frame. 10 + 10 + 10, 30 points (pins).
If a bowler bowls strikes on every frame and 3 in the final 10th frame, then the bowler gets a "Perfect Score" totaling 300 pins.

-Frame 1: 10+10+10 = 30 pins
-Frame 2: 10+10+10 = 30 pins
-Frame 3: 10+10+10 = 30 pins
-Frame 4: 10+10+10 = 30 pins
-Frame 5: 10+10+10 = 30 pins
-Frame 6: 10+10+10 = 30 pins
-Frame 7: 10+10+10 = 30 pins
-Frame 8: 10+10+10 = 30 pins
-Frame 9: 10+10+10 = 30 pins
-Frame 10: 10+10+10 = 30 pins

Additionally bowlers in some situations (typically leagues) will have what is known as a handicap which is usually based on the bowlers bowling 'average'.  This can vary depending on how and when the average is calculated and how the individual league creates handicap score.

Ex. Bowler average is 100.  The handicap in the leage is avg/2+(0.1*avg) then the bowler would have a handicap score of 100/2 = 50; 50 + (100 * 0.1); 50+10 = 60

This means that the bowler starts the game with a score of 60 pins.

##This calculator should do the following:

-Allow a user to input their handicap (if applicable) and then input their score for each frame (displayed as a graphical interface of 10 frames).  Using this the user shoulb be able to add new scores to determine what they would potentially be able to get in total based on their current actual (raw score + handicap).

-Users should also be able to add in a total desired score and then be shown what they would need to get in each frame in order to obtain this.

-Users should also be able to input a score and be told if (based on their current score + handicap) the score is obtainable or not.

