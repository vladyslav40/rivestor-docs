# Rivestor Docs

Documentation for Rivestor, built on [Mintlify](https://mintlify.com).

## Structure

- `docs.json` — site configuration, theme colors, and navigation
- `style.css` — "dark amethyst" styling refinements
- `index.mdx`, `status.mdx`, `how-it-works.mdx` — overview
- `concepts/` — rTokens, dual-engine model, glossary
- `investors/` — onboarding, trading, income, exits, risks
- `issuers/` — Engine A and Engine B listing, tracks, fees
- `protocol/` — RTCS programs, Token-2022 extensions, Compliance Hook, venue, Embedded SDK
- `legal/` — SPV structure, trustee, title protection, jurisdictions, risk matrix, disclaimer
- `resources/` — comparison, FAQ, support

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run it at the root of the repo, where `docs.json` is located:

```bash
mint dev
```

Open `http://localhost:3000` to preview.

## Publishing changes

Changes pushed to `main` are deployed automatically through the Mintlify GitHub app.

## Troubleshooting

- If the dev server doesn't start, run `mint update`.
- If a page loads as a 404, make sure you run `mint dev` in the folder that contains `docs.json`.
