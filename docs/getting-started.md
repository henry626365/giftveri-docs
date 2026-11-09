# Install GiftVeri for Windows Gift Card Balance Checks

This guide follows the current Windows download workflow. Start with one card and review its result before preparing a larger task list.

## 1. Confirm the package and platform

Open the [official Windows download page](https://www.giftveri.com/en/download). Check the listed version, platform, package format and release details there.

As checked on November 8, 2026, the page lists v0.4.10 for Windows 64-bit as a RAR archive. The current page is the reference if those details change. Its file information provides the package size and SHA-256 for verification; a matching name by itself is insufficient to verify a file.

## 2. Extract the complete archive

Extract the package to a writable local directory. The application file is `Giftveri.exe`; its `_internal` directory must stay beside it. Launch from the extracted directory, rather than from inside the archive.

Keep files from different versions in separate directories. The distributed client does not require a separate Python or Docker installation. For the current release and updater instructions, read the [installation and update guide](https://www.giftveri.com/en/guides/download-install-update).

## 3. Check the account and workflow

Use the account entry provided by the installed version. GiftVeri account access and a gift card brand's own account or session are separate parts of the workflow.

Confirm the card's full product name, purchase country or region and currency. A card bought at a store is not necessarily that store's own gift card. Match the actual product and the fields it provides to the chosen workflow.

The [brand, card type and region guide](https://www.giftveri.com/en/guides/choose-brand-card-region) explains how to resolve a mismatch. Coverage labels and verification progress need to be checked independently of the client's version number.

## 4. Make a single-card check

1. Use a card you own or are clearly authorized to check.
2. Select its matching brand and region.
3. Enter the requested fields exactly as supplied with the card.
4. Read the returned amount, currency, status and details together.
5. If the outcome is unclear, keep it unconfirmed and inspect the task before another attempt.

Do not pad or rewrite card fields to fit a different workflow. [Reading results](results.md) explains why a missing amount is different from an explicit zero balance.

## 5. Prepare for batch work or updates

Check that the installed plan and version offer the batch or export operation you need. Follow the current interface for input and export formats; this guide does not define a universal CSV import schema.

Start with a small matching sample. Keep completed, clearly unsent and uncertain tasks distinguishable. Save any needed results and stop active tasks before an update. Keep an old program directory until the new client starts and the files you need are separately retained.

[Troubleshooting](troubleshooting.md) provides a stage-by-stage checklist if you cannot complete the first check.
