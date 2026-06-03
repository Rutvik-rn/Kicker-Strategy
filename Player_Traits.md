"""This file contains the player traits (for all 6 players) we noted down during our EDA tests and Player Analysis phase, which was used further for our hypothesis"""


Diana -- 22 wins / 25
- lost 2 games against Simon, 1 against Magnus
- less seconds held before scoring a goal ( 1.80 seconds median; low compared to other players) -> quick shooter
- low possession length compared to others but a greater possession length to Hans. max =18 > 10 Hans
- 9.6 points average (lowest points: 5)
- has a clear preference for the left side (towards her) 
- most successful with the attack bar on the left side (39.2% of successful shots taken from there); plays a lot from the middle bar too but is not that successful from there
- her shots are not very effective and her most common moves have very low success rates. (Middle shots only succeed 11% of the time and direct defense shots succeed only 8% of the time)
- her best results come from multi‑pass plays and her most effective move( Middle-> Middle) scores nearly 69% of the time.
- dangerous when she passes backward (Attack‑>Middle) play results in a 56.5% success rate. 
- full back to front passing sequence (Defense → Middle → Attack) leads to a goal 60% of the time. 

Simon -- 17 wins / 25 
-best against Hans (5/5), bad against Diana (2/5)
-Shoots mostly from defense bar
- has the highest number of shots (1368) among all players.
- conversion rate is 16.2% very low compared to his high shot count.
- high shooting frequency but low efficiency.
- avg possession length 2.63 - moderate control
- Long-Range: Simon shoots from the Defence bar 298 times, more than Magnus (212), Tanja (231), or Olga (106).
- Defensive play?: He regularly passes backward from the Middle to the Defence bar (135 times), rather than developing forward.
- Inefficient play? (lowest-success-rate): His most common two-step path (Middle --> Defence) only converts at an 8.89% rate, indicating that he frequently resets even while in a stronger offensive position.
- Deep Play Making: He uses Goal --> Defence makes 100 passes, over twice the frequency of any other player.

Olga -- 15 wins / 25
- highest shot conversion rate (25%)
- mostly uses the attack bar to shoot, rarely uses the defense bar to shoot
- seconds held before a successful goal is always almost the same (2-3 seconds)
- longest possession of the ball (consecutive events, mean = 3.4 events, for unsuccessful shots: 4.0, for successful goals: 4.2) -> likes passing the ball
- Optimal Shot Selection: She has found the game's most successful sequence: Attack --> Middle --> Attack has a 60% success rate.
- Shot Faking / Fooling the Opponent: The "Golden Path" entails dragging the ball back to the middle bar to fool the opponent before passing forward to shoot.
- Dominant Bar?: She fires directly from the Attack bar 236 times, indicating a preference for close-range shooting over long-range sniping.
- Variety for path selection: Despite her "Golden Path" success, she only utilises it 25 times, which means she tried using different paths almost equally too.

Magnus --10 wins / 25
- bad against everyone but good against Hans (5/5)
- avg possession length is 2.49, showing balanced control of ball.
- total goals (186), total shots (1002) show consistent but not outstanding performance.
-  shot conversion rate is moderate (18.7%) compared to other players. 
- his most (and very!!!!) successful strategy is Middle -> Middle and then shooting (10/11 tries successful)
- tries Middle -> Defense very often (89 times) but has only a success rate of 6% with that
- has a 20% success rate when shooting directly from the Attack bar


Tanja -- 8 wins / 25
- her successful shots also mostly come from the attack bar( similar to Diana) however Tanja prefers middle or right ( away from her)
- her unsuccessful shots mostly come from the middle and defense bar
- highest success passing strategy: Middle-> Middle and then shooting (64% success) and Attack -> Middle -> Attack (64%) 
- has a 24% success rate when shooting directly from the attack bar

Hans -- 3 wins / 25
- lowest shot conversion rate (13%)
- shoots fairly often from the goal bar -> reason for low conversion rate?
-Took more time compared to other players before a goal -> 3.25 s median, high max (11.82 seconds)
- shortest possession of the ball (consecutive events, mean = 2.1 events), his maximum possession length is only 10 events (compared to 15-24 for the other players)
- passing rate: least passing rate for successful goals.
-Hans had a balanced number of attempts for the successful shots -> Eg: with the attack bar shoots from his side, middle, and away from him -> explains his poor performance.
- takes a massive amount of direct shots from the far back of the table. He shoots directly from the Defense bar 257 times (only 7.8% successful) and directly from the Goal bar 191 times (only 4.2% successful)
- frequently passes backwards into his own defensive zone to shoot (Middle -> Defense occurs 70 times) and (Middle -> Goal occurs 39 times) 
- his most successful path is a build up (Attack -> Middle -> Attack), which has a  60% success rate. However, he almost never uses it (only 10 times out of over 1200 shots) 
- Overall, he shoots the most, scores the least and holds the ball the longest.

All players
- more or less a linear relationship between round duration and number of shots but with outliers
- no own goals
- longer ball possession before shots
