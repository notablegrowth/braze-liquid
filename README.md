# Notable Growth Liquid Snippets

A collection of helpful Liquid code snippets compiled by Notable Growth. These snippets are intended for use with [Braze](https://braze.com). 

As Braze uses a forked version of Liquid, the code in these snippets may not work with other services that also use Liquid.

Notable Growth is a [Braze Alloy partner](https://www.braze.com/partners/solutions-partners/notable-growth), we use data, creativity, and empathy in our strategic planning to connect meaningfully with our customers and deliver Notable results.

## Arrays
- [Create Array](./create-array.html) - Create an array from a string. This also has an example of how to count values in a for loop.
- [Create Two Dimensional Array](./create-two-dimensonial-array.html) - Create a two dimensional array.
- [For Loop Multiple Arrays](./forloop-multiple-arrays.html) - Looping through one array while referencing another array.

## Connected Content
- [Connected Content Get](./connected-content-get.html) - Connected Content GET request with basic auth.
- [Connected Content Post](./connected-content-post.html) - Connected Content POST request with custom header values.
- [Connected Content Airtable](./connected-content-airtable.html) - Connected Content GET request to the [Airtable](https://airtable.com/api) API.
- [Connected Content Flagsmith](./connected-content-flagsmith.html) - Connected Content GET request to the [Flagsmith](https://docs.flagsmith.com/deployment/locally-api) API to get feature flags and remote config.
- [Connected Content Transifex](./connected-content-transifex.html) - Connected Content GET request to v2.5 of the [Transifex](https://docs.transifex.com/api/introduction) API. This API will be deprecated 11/30/2022.

### Voucherify Loyalty
- [Publish a Voucherify incentive to a user in Braze](/voucherify/loyalty/connected-content-publish-promo-code.html)
- [Retrieve selected incentive data](/voucherify/loyalty/connected-content-retrieve-data.html)
- [Re-send the same incentive when close to expiration (a reminder)](/voucherify/loyalty/connected-content-resend-promo-code.html)
- [Publish another promo code from the same campaign if the previous one was redeemed](/voucherify/loyalty/connected-content-republish-promo-code.html)
- [List all unredeemed promo codes for a user in Braze](/voucherify/loyalty/connected-content-list-unredeemed.html)
- [List available cart promotions](/voucherify/loyalty/connected-content-list-promotions.html)
- [Add loyalty points triggered by Braze event](/voucherify/loyalty/connected-content-add-loyalty-points.html)
- [Update gift card balance triggered by Braze event](/voucherify/loyalty/connected-content-update-card-balance.html)
- [Create a promo code based on the customer’s custom attribute](/voucherify/loyalty/connected-content-create-custom-code-pattern.html)

## Dates
- [Add Days](./add-days.html) - Add a specific amount of days to an existing date. Starting date must be converted to seconds first.
- [Format Date](./format-date.html) - Format a date into ISO 8601.
- [Ordinal Date](./ordinal-date.html) - Get the ordinal number for a date (e.g 5th, 22nd etc).

## Logic
- [Abort](./abort.html) - Abort a campaign based on the value of a variable.
- [Case When](./case-when.html) - Switch statement based on the values of a variable. Useful for displaying copy based on the language of a user.

## Math
- [Compare Negative Numbers](./compare-negative-numbers.html) - Simple example showing how to handle comparing a negative number in Liquid. This also has an example of casting a string as a number.