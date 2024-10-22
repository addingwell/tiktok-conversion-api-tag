# Tiktok Conversion API Tag for Google Tag Manager (server-side)

The Tiktok Conversions API Tag allows advertisers to send web events from their servers directly to the Conversions API.

## Background

The TikTok Conversion API (CAPI) is essential for overcoming the limitations of the TikTok Pixel, which has become less effective due to ad blockers and the decline of third-party cookies (on browsers like Safari and Firefox). While the TikTok Pixel uses client-side tracking with third-party cookies, the TikTok Events API relies on server-side tracking. Using both methods together ensures optimized and reliable data collection across all browsers.
Follow our complete guide on [Tiktok CAPI benefits](https://docs.addingwell.com/tiktok-events-api/benefits).

## How does the Addingwell tag work?

This template is a tag that reads the standard event schema sent from the client running on a tagging server. It then converts events to the appropriate schema and sends them through the Conversions API. The tag also allows sending the unique event ID for each event to Tiktok through you tracking server. TikTok can then eliminate duplicates received from Pixel and CAPI, while still capturing any additional events missed by the TikTok Pixel via server-side tracking, ensuring comprehensive data collection.

The tag supports only GA4 client.

## Implementation

You can follow our [step-by-step instructions](https://docs.addingwell.com/tiktok-events-api/tag-setup).

## How to check received data

Is your tag already live, and you're unsure whether everything is working correctly?
Follow our complete guide on [how to check the received data](https://docs.addingwell.com/tiktok-events-api/data-check).

## Reporting Bugs/Feedback

Please raise any issues on GitHub or contact us directly at support@addingwell.com.

## Open Source

The Tiktok Conversion API Tag for GTM Server-Side is developed and maintained by [Addingwell](https://www.addingwell.com) under the Apache 2.0 license.