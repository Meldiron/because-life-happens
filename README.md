# Investment Playground v2 · Because Life Happens

The brochure promises a fortune at 65. Life has other plans.

A simple, game-like playground: pick your age, monthly amount, where you invest and how much you raise it each year, then drag life onto your timeline. Cards that take (a car, a wedding, a medical bill), cards that pause your investing (sick leave, a lost job, a sabbatical, a baby) and cards that give (an inheritance, a promotion, quitting smoking) show exactly what each one does to your money.

Live: https://investment-playground-v2.surge.sh · Full version: [v1](https://github.com/Meldiron/investment-playground-v1)

- **Saving until 65** – drag a card onto the timeline, or click it to drop it at a random age. Drag icons to move them; pull a pause bar's handle to make it longer. Click an icon to change its price, or to pay for a cost by pausing your investing instead of selling.
- **Retirement** – pick how much you take out each month (in today's money, rising with inflation) and see the age you go broke, compared with the promise. Life events can land here too.
- **Live a random life** deals four setbacks and two lucky breaks.
- Balances can go negative: debt grows at 8% a year.

## Run locally

Open `index.html` in a browser. D3 and fonts load from CDNs, so an internet connection is needed.

## Deploy

Every push to `main` deploys to Surge through GitHub Actions (`SURGE_LOGIN` and `SURGE_TOKEN` repository secrets). To deploy by hand: `surge .`

Not financial advice.
