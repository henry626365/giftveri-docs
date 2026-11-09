# Gift Card Balance Checker FAQ

## Where should I download GiftVeri?

Use the [official Windows download page](https://www.giftveri.com/en/download). It carries the current package, version and file-verification details. Use its current record rather than an old link in a post or screenshot.

## Which operating system does this guide cover?

The current public download is for Windows 64-bit. Check the download page for changes to supported platforms. The package is distributed with its runtime files; a separate Python or Docker installation is not part of the documented setup.

## Is the Free workflow the same as PRO?

Free starts with single-card checks. Batch processing, export and other PRO features depend on the current plan and version. Refer to the [official plan comparison](https://www.giftveri.com/en/pricing) for the maintained feature list and pricing.

## Does a brand or region in the directory mean every operation is verified?

No. A listed entry, an implemented workflow, a stable release and a real balance result describe different evidence. Read the current brand and region page's scope and verification progress before use.

## Can an empty amount be treated as zero?

No. Keep an empty or unknown amount unconfirmed. A zero balance needs an explicit returned amount. [Reading results](results.md) includes teaching examples.

## Does a connection error mean a card is inactive?

No. A sign-in or connection failure alone does not establish a card's activation state or balance. The pre-activation feature has a separate documented interpretation; it should not be inferred from a generic flow error.

## Can I repeat a check when I cannot see its result?

Inspect the submission state first. If a request might have been sent, keep that uncertainty visible and review it before trying again. In a batch, resume tasks that were clearly not sent rather than automatically restarting the whole list.

## What should I share when asking for help?

Share a version, brand, region, failed stage and a redacted message. Keep card codes, PINs, credentials and session data private. The [troubleshooting guide](troubleshooting.md) provides a report checklist.

## Does this repository contain the GiftVeri application source?

This repository contains documentation and illustrations. Use the official product website for software distribution and product terms.
