# Gift Card Checker Not Working: Troubleshoot GiftVeri

Find the stage that failed before changing settings or sending another request. This guide helps collect useful context without turning a flow failure into a conclusion about a card.

## The client does not open

Check the official source, current Windows platform requirements and complete extraction. Verify that `_internal` is still next to `Giftveri.exe` and that files from multiple versions have not been mixed.

Compare package information with the [official download record](https://www.giftveri.com/en/download). If a file's size or SHA-256 differs, stop and verify the source. A system warning is a reason to inspect the file and source, not to disable protection.

## An expected account or update entry is missing

Confirm the version shown by the client. Website updates do not change a previously downloaded program. An older client may have a different account or update interface.

Use the current installation instructions before assuming the account itself is faulty. Save the results and progress you need before replacing or updating program files.

## The selected brand or region does not fit

Return to the card's product name, purchase details and terms. Check whether it is a retailer gift card or a network prepaid product. Confirm that the fields the workflow asks for actually exist on the card.

Use the [brand and region selection guide](https://www.giftveri.com/en/guides/choose-brand-card-region). Keep an unsupported or unclear scope unconfirmed rather than trying a similar-looking entry.

## Sign-in, session or connection fails

Record which stage failed and which session the interface requires. A GiftVeri account and a brand session are different. Check the selected scope and the current account entry before deciding what to initialize again.

An expired session, network error or rate limit does not determine the card's balance or activation state.

## A task has no clear result

Pause first. Determine whether it was clearly unsent, completed, or uncertain. Keep uncertain rows separate and review them individually before repeating a check.

[Reading results](results.md) explains the distinction between a missing amount, an explicit business message and a flow error.

## Batch processing or export is unavailable

Check the installed version and current plan. Use the input and export formats supported by that workflow. Test with a small matching sample, and confirm the result's status before treating exported values as balances.

## Prepare a useful report

Include:

- Client version and Windows platform.
- Brand and selected country or region.
- Approximate time and the stage that failed.
- Redacted status or error text.
- Whether any tasks are clearly unsent or uncertain.

Remove full card numbers, PINs, passwords, verification codes, tokens and private account details. Do not attach an unredacted CSV or raw session file to a public issue.

The [official features and help page](https://www.giftveri.com/en/help) is the starting point for maintained product guidance.
