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

## Static GPT routing canary

This is a separate benign test of whether a public repository can act as a user-mediated routing layer between link-shared GPTs. It uses ordinary links only; there is no automatic navigation, tracking, cross-GPT state, or transfer of conversation content.

- Source node: [Rewrite Canary 5 (safe test)](https://chatgpt.com/g/g-6a7ea3d599508191906c39bf7c6989d1-riraitokanaria5-an-quan-jian-zheng-yong)
- Existing destination node: [Creative Writing Coach](https://chatgpt.com/g/g-lN1gKFnvL-creative-writing-coach), created by ChatGPT.

Test route:

`Repository → Rewrite Canary 5 → this repository on completed output 5 → Creative Writing Coach`

Every transition requires a voluntary user click. This routing test is separate from the age-gate storage-location comparison above.
