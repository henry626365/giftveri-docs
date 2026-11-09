# Apple gift card region: a preflight record

Use this record before choosing a regional Apple workflow. Its purpose is to make country evidence explicit and prevent an uncertain card from being relabeled as a confirmed US or UK product.

## Record the four contexts

| Context | Record privately | Evidence required |
| --- | --- | --- |
| Card | Product and purchase country | Original card instructions and purchase information |
| Account | The account relevant to the intended operation | Its own applicable country information |
| Client | Regional entry actually selected | Current interface and documented scope |
| Task | Inquiry, redemption or account-balance inspection | The action you deliberately intend to take |

Do not use device language as a substitute for account country. Do not use a currency symbol as a substitute for purchase country. These shortcuts lose the information needed to explain a mismatch later.

Apple's [gift card problem guidance](https://support.apple.com/en-us/108285) covers redemption-country restrictions. Record that as a rule for the operation it describes, rather than treating every inquiry failure as a regional finding.

## Grade the country evidence

Use a simple evidence label:

- **Confirmed:** the original purchase record establishes the country relevant to this card.
- **Conflicting:** two records appear to describe different countries or products.
- **Unknown:** the available description does not establish the country.

These are organizational labels for your notes, not issuer statuses. Keep the source of the information beside the label. A later reviewer should be able to tell whether you inspected a record or simply inherited a seller's short description.

When evidence conflicts, preserve both descriptions and resolve the purchase details before another request. Changing an application setting does not resolve a conflict in the underlying card record.

## Use an example without live card data

Suppose Card A is described only as “Apple, dollars,” while Card B has a purchase receipt confirming a UK product. Keep Card A unknown and record the confirmed evidence for Card B. Do not assign both to a US batch merely because the same seller supplied them.

Suppose a different-country message appears during redemption for Card C. Record the operation and message. That observation does not supply an amount for an unperformed balance inquiry or explain the history of another card.

These examples are invented. They illustrate record keeping, not actual compatibility or balance outcomes.

## Review the relevant GiftVeri scope

The [US Apple entry](https://www.giftveri.com/en/brands/apple/us) publishes its verification limits. The [UK Apple entry](https://www.giftveri.com/en/brands/apple/gb) has a separate workflow and verification record. Keep regional evidence separate rather than transferring a result from one entry to another.

An initialized session is a readiness result. It does not establish that a card was submitted or that its balance was returned. After any session or regional change, review the current entry and task state before deciding what should happen next.

For client-side context, consult the [GiftVeri Apple region guide](https://www.giftveri.com/en/guides/apple-card-region). Avoid putting an already-sent task with an unclear outcome into a fresh queue without review.

## Treat account-country changes as another task

Apple's [account-country change instructions](https://support.apple.com/en-us/118283) explain prerequisites and steps. If a genuine move requires an account change, review those requirements separately from the card investigation.

A card preflight should not automatically trigger account changes. Document the intended change, why it is needed and whether its prerequisites are satisfied. The card's original purchase-country record remains unchanged by that decision.

This separation also improves troubleshooting: you can still describe the original operation and response instead of trying to reconstruct them after several unrelated settings changed.

## Ready-to-proceed criteria

Proceed only when the intended operation, product and country evidence are understood and the selected entry actually matches the documented scope. If one field remains unknown, retain that limitation instead of implying that preflight passed.

Then follow the [Apple balance checklist](apple-gift-card-balance-checklist.md) or [Apple error triage](apple-gift-card-message-triage.md), depending on the observation. Preflight is preparation; the next operation still needs its own explicit result.
