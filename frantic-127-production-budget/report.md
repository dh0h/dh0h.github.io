# Frantic #127 redelivery: From AI Demo to Production Budget

- Public article: https://dev.to/dhooooooh/from-ai-demo-to-production-budget-2cd9
- Platform and byline: DEV Community, dhooooooh.
- Published at: 2026-10-06T15:38:50Z, October 6 at 23:38:50 Asia/Shanghai. This is the new published article, not the deleted earlier URL or a preview.
- Topic 5: checking a startup offer against canonical vendor sources before applying, with worked examples.
- Length: 736 words of prose excluding title, headings and budget table, above the 500-word minimum.
- Three dated Sourcey facts: Google observed August 4, Baseten August 1, and AWS August 4, 2026. All three live pages and their JSON records were fetched again on delivery day, October 6.
- Each observation in evidence.json includes fact, sourcey_url, the actual offer_id from the live record, quoted_value, checked_at and the original observation date.
- Account evidence: joined September 17, 2026; three earlier public posts are listed with exact UTC publication timestamps in evidence.json. They predate this article by about 19 days, but the account is not 90 days old. This report does not represent reviewer acceptance of that history.
- Publication check: anonymous HTML returns 200; the article is listed on the public profile. DEV's public article API reports id 4807474, the expected byline and publication timestamp, and body_markdown exactly matching the local final body.
- Known unresolved blocker: the current published HTML includes robots noindex and nofollow. This redelivery is requested with that limitation disclosed; it does not claim full acceptance compliance.
- Text checks: three Sourcey links, explicit dates, no em dashes or en dashes, no bounty mention or ending disclaimer in the published article.
- Original analysis: an explicitly hypothetical $10,000 eligible cloud bill plus $2,000 external API bill yields cash payments of $2,000 in year one, $10,000 in year two and $12,000 after credits. No real usage or credit approval is claimed.

## Source verification

The Google offer is off_01kz5x2kqemq0cjk00sy3tzjd1; its live figures match the cited first-year maximum, second-year percentage and second-year maximum. The current Google benefits page supplies the directly billed third-party-model exclusion.

The Baseten offer is off_01kyyjpn04x1cdycrwbq4t7r08; the live record separates Dedicated Inference or Training credits from Model APIs credits. The article does not combine them into a fungible $27,500 allowance.

The AWS offer is off_01kyh8fpe12z6fgn1ywg2ykth8; the live record lists a $200,000 Portfolio ceiling. A note in that record reviewed August 5 reports an older discrepancy with the application guide. The current official guide and credits page both state $200,000, so the article describes the note as older evidence rather than repeating it as a current conflict.

Observation dates identify when Sourcey read the evidence; checked_at identifies this redelivery's live recheck. They are not interchangeable. Approved amount, billing coverage and expiration must still be confirmed by an actual applicant.

## Indexability and follow-up

Page-level noindex/nofollow remain. The 14-day and, if needed, 28-day search-discoverability checks have not occurred. No acceptance, search indexing, or removal of platform restrictions is claimed. This evidence packet preserves the precise new publication and account history for review, without overwriting the prior delivery files.

## Text as published

# From AI Demo to Production Budget

An agent keeps spending when a task goes wrong. A failed tool call can trigger another model call; a retry adds to the bill even if the user eventually gives up. Startup credits can cover some of that expense, but relying on them requires checking what the company would actually receive and when it would have to start paying.

Before applying, I would trace the offer to the vendor's program page and read the eligibility and billing terms. I used Sourcey to find dated records and their original sources for the three examples below, then checked the vendor pages on 6 October 2026. The question is whether the published offer supports the budget being proposed.

## The year-two bill

Google's [AI startup offer](https://sourcey.com/c/google-cloud/offers/google-for-startups-cloud-program-ai) lists up to $250,000 in first-year credits, followed by 20% coverage up to another $100,000 in year two (observed 4 August 2026). Google's [benefits page](https://cloud.google.com/startup/benefits?hl=en) confirms the amounts and specifies 100% coverage in year one. Its footnotes also say acceptance is discretionary. Google's models, including Gemini and Gemma, are covered; directly billed third-party models are excluded.

Suppose an application incurs $10,000 a month in eligible Google Cloud charges and $2,000 in model API charges billed directly by a separate provider. This is a hypothetical budget, with taxes excluded. Assume approval for the relevant benefits, enough credit remaining, and no cap reached.

| Monthly budget at the same workload | Gross charges | Credit offset | Cash payment |
| --- | ---: | ---: | ---: |
| Year one, with 100% eligible coverage | $12,000 | $10,000 | $2,000 |
| Year two, with 20% eligible coverage | $12,000 | $2,000 | $10,000 |
| After the applicable credits end | $12,000 | $0 | $12,000 |

The second-year offset is $10,000 multiplied by 20%. That leaves an $8,000 cloud payment plus the $2,000 external API bill. Monthly cash spending rises fivefold at exactly the same workload. A forecast built around the first-year payment would understate the second-year cash requirement by $8,000 a month.

During the pilot, I would divide total gross charges, including failed attempts, by successfully completed tasks. That gives the team a cost measure it can compare across changes to the agent. Keep the credit offset separate: a larger award can lower the cash payment while the cost of completing a task stays unchanged.

Baseten's [AI Startup Program](https://sourcey.com/c/baseten/offers/ai-startup-program) separates up to $25,000 for Dedicated Inference or Training from up to $2,500 for Model APIs (observed 1 August 2026). The [program page](https://www.baseten.co/startup-program/) confirms those categories. Eligible companies must have AI at the core of the product, be at Seed through Series A, be less than five years old, and have received no previous Baseten credits.

For an application using Model APIs, $2,500 is the relevant published ceiling. The page gives no basis for budgeting a transferable $27,500 pool. Moving to dedicated inference to pursue the larger amount would change the deployment plan: the team would need to test performance and utilization, then compare the unsubsidized cost. I would resolve that choice before applying, so the requested credit category matches the service the product will use.

## When the application guide changes

[AWS Activate Portfolio](https://sourcey.com/c/aws/offers/aws-activate-portfolio-credits) lists up to $200,000 for pre-Series B startups with an Activate Provider Org ID (observed 4 August 2026). An application note in the linked record, reviewed on 5 August, reports different ceilings on two AWS pages: $200,000 on the credits page and $100,000 in the application guide.

On 6 October, the [credits page](https://aws.amazon.com/startups/credits/) and [application guide](https://aws.amazon.com/aws-startups/learn/applying-for-aws-activate-credits-a-step-by-step-guide/) both advertised a Portfolio ceiling of $200,000. The guide still uses $100,000 in examples of specific packages and incremental awards, rather than as the overall ceiling. The older note pointed to a possible problem; checking the original pages showed that its warning was no longer current.

There is still a package to confirm. I would get the Org ID from the affiliated provider, ask which award it makes available, and use the application linked from AWS's own program page. The $200,000 ceiling alone does not establish what a particular applicant will receive.

The [credit terms](https://aws.amazon.com/awscredits/), updated on 24 September 2026, restrict coverage to designated eligible services, exclude taxes, and leave excess usage payable. Once an award arrives, its expiration date belongs in the forecast alongside its balance. The forecast should stop applying the offset when the award's coverage period ends, even if some balance remains.

Before committing to a production launch, I would attach the approved amount, covered services, coverage rate, and expiry to the corresponding budget lines. Unapproved credits would appear only in a separate scenario. The launch review would use the pilot's gross cost per completed task and the cash required after the promotion ends, including the full $12,000 monthly bill in the hypothetical Google example.

