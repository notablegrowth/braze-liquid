# Notable Growth Liquid Snippets

A collection of helpful Liquid code snippets compiled by Notable Growth. These snippets are intended for use with [Braze](https://braze.com).

As Braze uses a forked version of Liquid, the code in these snippets may not work with other services that also use Liquid.

Notable Growth is a [Braze Alloy partner](https://www.braze.com/partners/solutions-partners/notable-growth). We use data, creativity, and empathy in our strategic planning to connect meaningfully with our customers and deliver Notable results.

## Contents

- [Working with data](#working-with-data) — arrays and delimited strings
- [Conditional logic](#conditional-logic) — branching, defaults, and aborting sends
- [Formatting](#formatting) — dates, numbers, and text
- [External data](#external-data) — Catalogs and Connected Content

## Working with data

- [Create Array](/working-with-data/create-array.liquid) - Create an array from a string. This also has an example of how to count values in a for loop.
- [Create Two Dimensional Array](/working-with-data/create-two-dimensional-array.liquid) - Create a two dimensional array.
- [Loop Parallel Arrays](/working-with-data/loop-parallel-arrays.liquid) - Looping through one array while referencing another array.

## Conditional logic

- [Case When](/conditional-logic/case-when.liquid) - Switch statement based on the values of a variable. Useful for displaying copy based on the language of a user.
- [Unless](/conditional-logic/unless.liquid) - Run a block only when a condition is false.
- [Default Value](/conditional-logic/default-value.liquid) - Fall back to a default value when an attribute is blank or missing.
- [Compare Numeric Strings](/conditional-logic/compare-numeric-strings.liquid) - Casting a string as a number and then comparing it, including handling negative numbers.
- [Abort Message](/conditional-logic/abort-message.liquid) - Abort a campaign based on the value of a variable.

## Formatting

### Dates

- [Format Date](/formatting/dates/format-date.liquid) - Format a date and time for display.
- [Add Days](/formatting/dates/add-days.liquid) - Add a specific amount of days to an existing date. Starting date must be converted to seconds first.
- [Convert Timezone](/formatting/dates/convert-timezone.liquid) - Render a date in the user's local time with the `time_zone` filter.
- [Ordinal Date](/formatting/dates/ordinal-date.liquid) - Get the ordinal number for a date (e.g. 5th, 22nd etc).
- [Days Left In Month](/formatting/dates/days-left-in-month.liquid) - Get the number of days remaining in the current month.
- [Localize Date](/formatting/dates/localize-date.liquid) - Render a date with localized day and month names.

### Numbers

- [Format Currency](/formatting/numbers/format-currency.liquid) - Thousands separators and money formatting.
- [Random Number](/formatting/numbers/random-number.liquid) - Generate a random number.

### Text

- [Format Text](/formatting/text/format-text.liquid) - Capitalize, truncate, strip HTML, and chained find/replace.

## External data

### Catalogs

- [Get Catalog Items](/external-data/catalogs/get-catalog-items.liquid) - Look up items from a Braze Catalog.

### Connected Content basics

- [GET Request](/external-data/connected-content/basics/get-request.liquid) - Connected Content GET request with basic auth.
- [POST Request](/external-data/connected-content/basics/post-request.liquid) - Connected Content POST request with custom header values.
- [Parameter Reference](/external-data/connected-content/basics/parameter-reference.liquid) - Commonly used `connected_content` parameters in one place.

### Connected Content integrations

- [Airtable](/external-data/connected-content/integrations/airtable.liquid) - Connected Content GET request to the [Airtable](https://airtable.com/api) API.
- [Flagsmith](/external-data/connected-content/integrations/flagsmith.liquid) - Connected Content GET request to the [Flagsmith](https://docs.flagsmith.com/deployment/locally-api) API to get feature flags and remote config.
- [Giphy](/external-data/connected-content/integrations/giphy-search.liquid) - Connected Content GET request to [Giphy's](https://developers.giphy.com/docs/api/) search endpoint.
- [NASA](/external-data/connected-content/integrations/nasa.liquid) - Connected Content GET request to [NASA's Astronomy Picture of the Day](https://api.nasa.gov/).
- [Transifex](/external-data/connected-content/integrations/transifex.liquid) - Connected Content GET request to v2.5 of the [Transifex](https://docs.transifex.com/api/introduction) API.

#### Voucherify

Examples using the [Voucherify](https://www.voucherify.io/) promotion engine.

- [Retrieve incentive data](/external-data/connected-content/integrations/voucherify/retrieve-data.liquid) - Retrieve selected incentive data.
- [Publish a promo code](/external-data/connected-content/integrations/voucherify/publish-promo-code.liquid) - Publish a Voucherify incentive to a user in Braze.
- [Resend a promo code](/external-data/connected-content/integrations/voucherify/resend-promo-code.liquid) - Re-send the same incentive when close to expiration (a reminder).
- [Republish a promo code](/external-data/connected-content/integrations/voucherify/republish-promo-code.liquid) - Publish another promo code from the same campaign if the previous one was redeemed.
- [List unredeemed promo codes](/external-data/connected-content/integrations/voucherify/list-unredeemed.liquid) - List all unredeemed promo codes for a user in Braze.
- [List available promotions](/external-data/connected-content/integrations/voucherify/list-promotions.liquid) - List available cart promotions.
- [Add loyalty points](/external-data/connected-content/integrations/voucherify/add-loyalty-points.liquid) - Add loyalty points triggered by a Braze event.
- [Update gift card balance](/external-data/connected-content/integrations/voucherify/update-card-balance.liquid) - Update gift card balance triggered by a Braze event.
- [Create a custom code pattern](/external-data/connected-content/integrations/voucherify/create-custom-code-pattern.liquid) - Create a promo code based on the customer's custom attribute.
