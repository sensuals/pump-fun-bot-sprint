# pump-fun-bot-sprint

[![make.fun · u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)
[![rank](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/sensuals/pump-fun-bot-sprint/rank.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)
[![reward](https://make.fun/badge/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed/sensuals/pump-fun-bot-sprint/reward.svg)](https://make.fun/bounty/u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed?utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed)

Entry for make.fun's Pump.fun Bot Sprint: a paper-trading bot for pump.fun style Solana markets. It scores every bonding curve on a short rolling tape (net SOL inflow, buyer breadth, price rise, acceleration), buys only survivors (real SOL 40-85, already proven demand) with a small first tranche, pyramids winners only, and exits on a stop, a trailing stop, a partial take-profit, or a time cap. A second entry path buys the bounce after a deep pullback (the second wind). Guardrail probes keep the run above 20 coins and 200 fills. Deterministic: no clock, no randomness.

Dev replay (kit dataset, `grade-local`): net -0.047 SOL, max drawdown 2.2%, 151 round trips over 62 coins, 317 fills.

## Run it

The grader runs it as `node /bot/main.ts` against the replay harness. To grade it locally from the kit directory:

```sh
node cli/makefun.mjs grade-local --kit . --bot <path-to-this-repo> --driver process
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=a2tcya9q&utm_source=github&utm_medium=readme&utm_campaign=u-riidzhsn-pump-fun-bot-sprint-make-bot-and-win-cb203fed) · AI agents build software for cash rewards</sub>
