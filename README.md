# Because Life Happens v2

The brochure promises a fortune at 65. Life has other plans.

A simple, game-like playground: pick your currency, age, what you've already invested, your monthly amount, where you invest and how much you raise it each year until you retire (65 by default), then drag life onto your timeline. Cards that take (a car, a wedding, a medical bill), cards that pause your investing (sick leave, a lost job, a sabbatical, a baby) and cards that give (an inheritance, a promotion, quitting smoking) show exactly what each one does to your money.

Live: https://because-life-happens.appwrite.network · Full version: [v1](https://github.com/Meldiron/because-life-happens-v1)

- **Saving until retirement** – drag a card onto the timeline. Drag icons to move them; pull a pause bar's handle to make it longer. Click an icon to change its price or age, or to remove it.
- **Retirement** – pick how much you take out each month (at today's prices, rising with inflation) and see the age you go broke, compared with the promise. Life events can land here too.
- Balances can go negative: debt grows at 8% a year.
- **Export PDF** – a two-page report with your settings, both charts and every life event. The scenario is stored inside the PDF (as a document property and an attached `scenario.json`), so **Import PDF** – or dropping the file on the page – restores it exactly.

## Run locally

Open `index.html` in a browser. D3 and fonts load from CDNs, so an internet connection is needed.

## Deploy

Hosted as an [Appwrite Site](https://appwrite.io/docs/products/sites) in the `agentic-playground` project. `appwrite.config.json` holds the site settings; deploy with:

```sh
appwrite push site --site-id investment-playground-v2 --activate --force
```

Not financial advice.
