# age-gate-safety-test

A benign, self-contained age-acknowledgement page for controlled Custom GPT publishing-moderation research.

## Safety boundary

This repository and its published page contain:

- no sexual or explicit content;
- no adult products or services;
- no regulated goods;
- no commerce, advertising, or subscriptions;
- no authentication or identity verification;
- no personal-data collection;
- no cookies, analytics, tracking, or storage;
- no externally hosted scripts, images, fonts, APIs, or redirects.

The 18+ button loads one repository-local cosplay image only after it is selected. The under-18 path does not load the image. No button transmits or retains information.

## Test purpose

The fixture supports a controlled comparison in which materially identical benign age-gate text and the same URL are placed either:

1. directly in Custom GPT Instructions; or
2. in a Custom GPT Knowledge file referenced by Instructions.

The test is about publishing-review consistency across storage locations. It is not intended to test prohibited content or to bypass policy.

## Public page

Once GitHub Pages is enabled from the `main` branch root:

`https://lucidity3k.github.io/age-gate-safety-test/`

For reproducibility, record the exact commit SHA used for every submission.
