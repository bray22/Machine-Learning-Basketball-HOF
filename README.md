# 51-ray-mlproj-nba
Predict current NBA player's chance to be in the NBA Hall of Fame based on current inductees' career stats.

## Description of Metrics
The primary metric used in this project are is prediction accuracy. About 11000 players will used as data points. Therefore about 11000 predictions will be made by the system on whether or not a player has been inducted into the Pro Basketball Hall of Fame. The data used will be points scored, rebounds, blocks, steals, assists as well as awards and championships. Figure 1 below shows a confusion matrix based on the predictions.

A very small percentage of players make it to the HOF. The total number of players is around 400. So the negatives will be big and the positives will be very small.

I estimate that the system will predict 350 players that are in the HOF that are indeed in the HOF (True Positive). 

I estimate that the system will predict 60 players to be inducted in the HOF that are not in the HOF (False Positive).

I estimate 35 players will be predicted to not be in the HOF that are actually in the HOF (False Negatives).

I estimate that about 10000 players will guessed to be not in the HOF that are actually not in the HOF (True Negative).

![Screen Shot 2022-05-20 at 5 01 29 PM](https://user-images.githubusercontent.com/16246855/169610073-d8b16161-a765-446a-aac1-76128f6df5bb.png)
Fig. 1

![Screen Shot 2022-05-20 at 4 15 02 PM](https://user-images.githubusercontent.com/16246855/169604320-003fd92b-f087-49ff-9c13-9f633b343161.png)
Fig. 2

---
### README Comments
1. I looked around in the vanderbilt-ml organization at other repos. It kind of seems like everyone's got their own take on what we're doing this week.  To me, your README looks fine.  It's clear and concise with well-stated intentions and a good grasp of the metrics you want to look at.
2. In mine, I tried to tie some actual dollar amounts into the valuation, but that doesn't really fit with your goals.  Unless you took the business angle of the league trying to plan for induction ceremonies.  I'm not certain that's necessary, though.
