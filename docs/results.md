# Gift Card Balance Results: Zero, Unknown and Failed Checks

Treat the amount, currency, operation status and response details as four related fields. A completed task alone does not establish a gift card balance.

## What the amount establishes

Use an amount only when the brand's business response explicitly returns it. An empty field or a dash should remain unconfirmed. An explicit zero is an amount, but does not explain the card's previous activity by itself.

The following are invented teaching examples. They are not real gift card checks and do not define the client's export format.

| Reference | Amount | Status | Interpretation |
| --- | --- | --- | --- |
| Example A | USD 25.00 | Balance returned | The response explicitly reported an amount and currency. |
| Example B | Not returned | Unknown | No balance has been established. Preserve the unknown state. |
| Example C | USD 0.00 | Balance returned | Zero was explicitly returned; do not infer the reason from the amount alone. |
| Example D | Not returned | Session failure | Investigate the session stage; no conclusion about the card's funds follows. |

## Keep specific business messages

A brand may return information about card format, region or redemption state. Retain the specific message and the context shown by the client. Do not replace a precise explanation with a generic label such as “used” merely because no amount was displayed.

Status wording can differ by brand and version. Use the [official result interpretation guide](https://www.giftveri.com/en/guides/query-results) for the maintained explanation.

## Flow errors and pre-activation are different

A failed sign-in, expired session, rate limit or connection error means the current flow did not establish enough business information. It does not, by itself, mean the card is inactive, invalid or empty.

The pre-activation feature described on the product website is a separate brand-response workflow. Check its documented interpretation, plan, client version and current brand scope. Do not use a general connection or unknown-result error as a substitute for that feature's result.

## Uncertain submission state

When a request may have been sent but no clear result is visible:

1. Pause and retain the uncertain state.
2. Inspect the visible progress and feedback.
3. Continue only with tasks that were clearly not sent.
4. Review an uncertain item explicitly before deciding to send it again.

Do not move an uncertain item automatically into a fresh pending list.

## Preserve context, remove secrets

For troubleshooting, keep the client version, brand, region, timestamp, failed stage and a redacted status message. Keep full business results in a controlled location. Public examples should use labels such as “example A” and omit card codes, PINs and account credentials.

Continue with [troubleshooting](troubleshooting.md), or return to [getting started](getting-started.md).
