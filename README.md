# 🌌 Nebula Quotes

- A free and open-source collection of motivational quotes curated for [Nebula](https://github.com/delta6626/365-days-of-code/tree/main/day9-dayx/nebula).

- No dependencies. No setup. Just pure JSON you can fetch or import into any app.

## 📥 Usage

Fetch directly from the raw GitHub URL:

```js
const QUOTE_REPOSITORY =
  "https://raw.githubusercontent.com/delta6626/nebula-quotes/main/quotes.json";

fetch(QUOTE_REPOSITORY)
  .then(res => res.json())
  .then(quotes => {
    const randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
    console.log(randomQuote);
  });
```
