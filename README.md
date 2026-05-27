# Alter-Me

**Know Thyself.**

An open-source tool for self-knowledge and personal data ownership.
The dash is the cortex.

---

## What this is

Alter-Me (also called Me-Alter) is a decision-making protocol that runs in your browser, on top of any AI you choose to bring. It helps you make clearer decisions by surfacing what you already know but cannot easily access. Over time, your decisions become a personal cognitive portrait that belongs entirely to you.

Your data never leaves your device unless you choose to export it. The project does not collect, track, or store anything about you. There are no cookies, no analytics, no accounts on our side, no third-party sign-ins.

You bring the AI. You bring the storage. We provide the protocol.

**Live demo:** [https://alter-me.ai](https://alter-me.ai) · [https://me-alter.ai](https://me-alter.ai)

---

## How it works

You answer two questions on the landing page: when you were born, and what age you feel today. The site renders itself in the visual language of that cohort. Same protocol underneath, different door.

You choose an AI to power the session (Claude, GPT, or any other LLM you have API access to). You choose where your data lives (browser storage or a downloaded file you control). You set a password that encrypts everything locally — or you skip it and use the session once without saving.

Then you enter the six-phase decision protocol:

1. **The gate** — Are you figuring something out, or confirming what you've already decided?
2. **Surface the binary** — What's the actual choice, in plain language?
3. **Outcome pass** — What does each future look like, concretely?
4. **Pressure reading** — Under each option, now and later — expansion or compression?
5. **The refusal question** — What haven't you let yourself say yet?
6. **The enough signal** — When you're done, you say so. The protocol stops.

Then the AI reflects back the pattern you've revealed. Not a recommendation — a mirror.

---

## What this is NOT

**Not therapy.** Not medical advice. Not diagnostic. Not a substitute for professional mental health care. If you are in crisis, please contact a qualified professional or emergency service. See [DISCLAIMER.md](./DISCLAIMER.md) for the full statement.

**Not engagement-optimized.** No notifications, no streaks, no badges, no "come back tomorrow." When you're done, the app tells you to close it.

**Not ad-supported.** No advertising will ever appear. Your attention is not for sale.

**Not data-extractive.** We do not collect your data. We cannot sell what we do not have.

**Not subscription-locked.** Free forever. Always.

**Not closed-source.** The code is public. Fork it, audit it, modify it, redistribute it.

---

## Ethical gates

Every feature must pass these checks before shipping:

1. Does it serve the user, or the product's growth narrative?
2. Does it cost the user spoons, or generate them?
3. Is the user the customer, or the product?
4. Will the app tell the user to close it when they need to?
5. Does the user own everything by default?
6. Is it open-source?
7. Does it optimize for the state in which the user cannot stop?
8. Does it match the user's native channel?

If a proposed feature fails any of these, it does not ship.

---

## Run it yourself

This is a single HTML file. To run it locally:

1. Download `index.html` from this repo.
2. Open it in any modern browser.
3. Provide your own API key for the AI of your choice.

To host your own copy: drop `index.html` on any static host (GitHub Pages, Cloudflare Pages, Vercel, Netlify, a server you own). No build step. No dependencies. No backend.

---

## Contributing

This project is part of a commons. Contributions of code, language, translations, design variants, and accessibility improvements are all welcome.

- **Bugs and ideas:** Open an issue.
- **Code:** Open a pull request.
- **Lineages we missed:** Add to [NOTICE](./NOTICE). Credit is additive, never substitutive.
- **New language registers or cohort designs:** Open a PR with a working variant.

The project is maintained as a gift to the commons. Contributors are credited in NOTICE. There are no contributor license agreements; everything released to this repo is released under the repo's license.

---

## License and attribution

This work is dedicated to the public domain under [CC0 1.0 Universal](./LICENSE). You may copy, modify, distribute, and use it — including for commercial purposes — without asking permission.

This does not mean the work has no lineage. It has a long one. See [NOTICE](./NOTICE) for the credit roll, which is incomplete by design and grows by addition.

---

## A note from the project

Alter-Me is one rendering of a framework that argues for digital self-sovereignty as a structural intervention. The framework is in this repo and elsewhere. The product is the test of whether the framework is correct.

The dash is the cortex. The cortex mediates. The user owns themselves.

*Alter-Me. Me-Alter. Know Thyself.*
