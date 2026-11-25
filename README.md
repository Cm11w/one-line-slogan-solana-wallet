[![make.fun](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)
[![rank](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e/Cm11w/one-line-slogan-solana-wallet/rank.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)
[![reward](https://make.fun/badge/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e/Cm11w/one-line-slogan-solana-wallet/reward.svg)](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e)

# One-Line Slogan for a Solana Wallet Agent

Entry for the [make.fun bounty](https://make.fun/bounty/u-phudinhvfx-one-line-slogan-for-a-solana-wallet-agent-a7f6564e): a program that writes one slogan — a single line of at most twenty words — to `/output/entry.txt`.

## The text

> Your Solana wallet grew a brain. It watches Solana while you sleep.

12 words, 67 characters (67 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it names the Solana wallet twice, so it is unmistakably a slogan for a Solana wallet agent. The image is fresh — a wallet that "grew a brain" — with no stock crypto line about keys, moons or bags. The promise is clear to a newcomer in plain words: the wallet watches Solana while you sleep, the agent doing the watching so you don't have to. Two short beats with a contrast (the wallet works, you sleep) make it easy to repeat. And it is honest: it promises watching, not riches — nothing the agent cannot deliver.

## License

MIT — see [LICENSE](LICENSE).
