# Investment Playground v2 · Because Life Happens

The brochure promises a fortune at 65. Life has other plans.

A simple, game-like playground: pick your age, monthly amount and where you invest, then drag life onto your timeline. Cards that take (a car, a wedding, a baby, a lost job, a market crash) and cards that give (an inheritance, a promotion, quitting smoking) show exactly what each one does to your money at 65.

Live: https://investment-playground-v2.surge.sh · Full version: [v1](https://github.com/Meldiron/investment-playground-v1)

- Drag a card onto the timeline, or click it to drop it at a random age.
- Drag icons to move them in time. Pauses (👶, 💼) are ranges: pull the handle to make them longer.
- 🎲 **Live a random life** deals four setbacks and two lucky breaks.
- The row under the chart shows what €1 at each age is worth at 65.

## Run locally

Open `index.html` in a browser. D3 and fonts load from CDNs, so an internet connection is needed.

## Deploy

Every push to `main` deploys to Surge through GitHub Actions (`SURGE_LOGIN` and `SURGE_TOKEN` repository secrets). To deploy by hand: `surge .`

Not financial advice.
