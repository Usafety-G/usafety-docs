# Usafety docs

Customer-facing documentation for Usafety — DSE assessments, equipment compliance and workplace safety management for Irish organisations.

Built with [Mintlify](https://mintlify.com). Published at `docs.usafety.ie` (once hosted).

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

From this directory (where `docs.json` lives), run:

```bash
mint dev
```

The preview will open at http://localhost:3000.

## Structure

- `docs.json` — navigation and site config
- `index.mdx` — welcome page
- `getting-started/` — onboarding guides (quickstart, roles, team)
- `dse-assessments/` — sending, reviewing, remediation, reassessments
- `equipment-and-compliance/` — catalogue, recommendations, fulfilment, exports, dashboard
- `bookings-and-scheduling/` — booking links, calendar, rescheduling
- `importing-data/` — CSV imports and troubleshooting
- `for-administrators/` — org setup, SSO, custom fields, billing
- `for-senior-leaders/` — short, exec-focused pages
- `irish-hs-reference/` — regulations, HSA guidance, GDPR, glossary
- `changelog.mdx` — release notes (uses Mintlify `<Update>` component)
- `logo/` — light and dark logos
- `favicon.svg` — site favicon

## Writing conventions

- **British/Irish English** (colour, organisation, catalogue, fulfilment)
- **Short pages over long ones** — if a page is longer than ~600 words, split it
- **Every page ends with a "Related" card group** linking to 1–2 sensible next reads
- **Real screenshots beat words** — drop PNGs into `/images` and reference with `<img>` or Markdown
- **Stubs are OK** — pages that aren't written yet use a `<Note>` telling the reader to email support

## Publishing

Changes pushed to `main` deploy automatically via the Mintlify GitHub app. Install it from the Mintlify dashboard if it's not already connected.

## Help

Something broken? Email [info@usafety.ie](mailto:info@usafety.ie).
