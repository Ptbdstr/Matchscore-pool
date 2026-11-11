# Matchscore-pool
The Score Predictor Pool is a football prediction game on Arc Testnet where you win by guessing the exact final score.

How it works

Pick a match from the list, such as a Premier League, La Liga, Serie A, Bundesliga, Ligue 1, MLS or Saudi Pro League game.
Enter a score for each team and press "Lock Prediction & Enter Pool". This locks 2 testnet USDC in the contract and records your prediction. You get one prediction per match.
Entries close at kickoff.
After the match, the admin enters the official final score. The contract finds every wallet that predicted that exact score and splits the whole pool equally between them. Payouts are automatic.
If nobody guesses right: the admin can refund everyone their 2 USDC, or roll the pool into a new match so the prize grows. If the admin never acts, anyone can trigger refunds after 14 days.

Good to know

It uses testnet USDC only, so there is no real money.
Each match has its own pool, player count and leaderboard of recent predictions.
The admin supplies the final score. The contract enforces the split, but it can't check the result itself.
