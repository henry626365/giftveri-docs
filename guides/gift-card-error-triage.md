# Gift card not working: activation, invalid codes and balance errors

Classify the operation before diagnosing an error. “Not working” can describe an unread balance, failed session, declined payment or redemption message.

## Record the operation and exact message

Keep the client version, brand, region, timestamp and a redacted message. A public report can refer to “example card A”; it should not carry the card's number or access codes.

| State | Safe interpretation |
| --- | --- |
| No amount and a session failure | The balance remains unconfirmed. |
| Explicit returned zero | The returned amount is zero; the cause is not established by that number alone. |
| Issuer activation message | Follow that product's activation support instructions. |
| Wrong-region message | Check the product's purchase country and the operation's region. |
| Declined payment | Investigate the payment through the issuer; it is separate from an inquiry. |

## Follow product-specific guidance

Apple's [gift card redemption help](https://support.apple.com/en-au/108285) distinguishes invalid, redeemed, activation and region messages for redemption. Apply those instructions to that operation rather than using redemption to test an uncertain balance inquiry.

For a Visa card with an unexplained decline, use the issuer instructions linked by [Visa's gift card guidance](https://www.visa.com/en-us/personal/cards/gift/gift-card-balance). A general network error is not an activation result.

## Keep request uncertainty separate

When a request may have been sent, pause and inspect it. In a batch, keep completed, clearly unsent and uncertain tasks distinct. Resume clearly unsent tasks; review uncertain items before sending them again.

GiftVeri's [result interpretation guide](https://www.giftveri.com/en/guides/query-results) explains the distinction. The repository's [troubleshooting guide](../docs/troubleshooting.md) helps locate the failure stage.

## What a status checker does not establish

A status-check feature is not a promise to activate a card, reverse a payment or recover value. Follow the issuer's supported process for those questions and keep complete card and account details out of public reports.
