[![Pump.fun Replay Sprint](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![Rank](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/Ahmadmukafi/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122-r1/rank.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)
[![Reward](https://make.fun/badge/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122/Ahmadmukafi/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122-r1/reward.svg)](https://make.fun/bounty/u-jackxyz72-pump-fun-replay-sprint-paper-bot-0b809122)

# Pump.fun Replay Sprint — proven-mint swing bot

A paper-trading bot for the pump.fun replay (10 SOL, 24h window). It only buys
a mint once it has proven itself — real reserves of at least 3 SOL — and only
while it is still cheap, at most 2x its creation price. Positions are held
with a loose -35% trailing stop and a 90-trade age exit, and no hard
stop-loss: the winners are the mints that survive 90 trades without a deep
pullback. Dev result (grade-local, real harness): +0.1273 SOL net PnL over
24 round trips on 24 distinct mints, 45.8% win rate, 0.9% max drawdown.
