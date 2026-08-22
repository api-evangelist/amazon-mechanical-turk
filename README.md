# Amazon Mechanical Turk (amazon-mechanical-turk)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Mechanical Turk (MTurk) is a crowdsourcing marketplace that makes it easier for individuals and businesses to coordinate the use of human intelligence to perform tasks that computers are currently unable to do well. It enables access to a global, on-demand, 24x7 workforce for data labeling, content moderation, surveys, transcription, and machine learning training data collection.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Crowdsourcing, Human Intelligence, Labor, Machine Learning, Tasks

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Mechanical Turk API
The Amazon Mechanical Turk API provides programmatic access to create and manage HITs, qualifications, workers, assignments, and bonuses for coordinating crowdsourced human intelligence tasks. Covers 39 operations for the complete HIT lifecycle from creation through assignment review, worker management, and payment processing.

**Human URL:** [https://www.mturk.com/](https://www.mturk.com/)

#### Tags:

 - Crowdsourcing, Human Intelligence, Machine Learning, Tasks

#### Properties

- [Documentation](https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/Welcome.html)
- [OpenAPI](openapi/amazon-mechanical-turk-openapi-original.yaml)
- [GettingStarted](https://www.mturk.com/get-started)
- [Pricing](https://www.mturk.com/pricing)
- [FAQ](https://www.mturk.com/faqs)

## Common Properties

- [Portal](https://www.mturk.com/)
- [Documentation](https://docs.aws.amazon.com/mturk/)
- [TermsOfService](https://www.mturk.com/participation-agreement)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://www.mturk.com/contact)
- [Blog](https://blog.mturk.com/)
- [GitHubOrganization](https://github.com/aws)
- [SignUp](https://www.mturk.com/get-started)
- [Login](https://requester.mturk.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://www.mturk.com/contact)
- [SpectralRules](rules/amazon-mechanical-turk-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-mechanical-turk-vocabulary.yaml)
- [NaftikoCapability](capabilities/crowdsourcing-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| Human Intelligence Tasks (HITs) | Create and manage discrete units of work distributed to the global MTurk worker population. |
| Qualification Types | Define custom qualification tests and requirements to target the right worker pool for each task type. |
| Assignment Review and Approval | Review submitted assignments and approve or reject work with feedback to workers. |
| Worker Bonuses | Award bonus payments to workers for exceptional task completion beyond the base HIT reward. |
| Worker Notifications | Send targeted messages to specific workers to communicate task updates or instructions. |
| Worker Blocks | Prevent specific workers from accessing your HITs when quality does not meet requirements. |
| Sandbox Environment | Test HIT templates and requester workflows using the MTurk sandbox before going to production. |

## Use Cases

| Name | Description |
|------|-------------|
| Machine Learning Data Labeling | Label images, text, audio, and video to create training datasets for machine learning models. |
| Content Moderation | Review and moderate user-generated content for inappropriate material at scale. |
| Transcription Services | Transcribe audio and video recordings using human workers for high accuracy. |
| Survey and Research Data Collection | Conduct surveys and collect research data from a diverse global workforce. |
| Data Validation and Quality Assurance | Validate and verify structured data for accuracy using human review. |
| Sentiment Analysis Training Data | Generate labeled sentiment data for training NLP and sentiment analysis models. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon SageMaker Ground Truth | Use MTurk workers directly within SageMaker Ground Truth for ML data labeling jobs. |
| AWS Lambda | Trigger Lambda functions on HIT completion events for automated downstream processing. |
| Amazon S3 | Store HIT input data and collect worker output files in S3 buckets. |
| Amazon CloudWatch | Monitor MTurk task completion rates and worker performance metrics. |
| AWS IAM | Control requester access to the MTurk API through IAM policies and roles. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Mechanical Turk OpenAPI](openapi/amazon-mechanical-turk-openapi-original.yaml)

### JSON Schema

144 schema files available in the [json-schema/](json-schema/) directory.

### JSON Structure

144 structure files available in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Amazon Mechanical Turk Context](json-ld/amazon-mechanical-turk-context.jsonld)

### Examples

144 example files available in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Mechanical Turk Requester API](capabilities/shared/mturk-requester.yaml) — 16 operations for HIT management, assignment review, qualifications, and worker payments

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Crowdsourcing Workflow](capabilities/crowdsourcing-workflow.yaml) | Amazon Mechanical Turk | 10 | Data Scientist, Researcher |

## Vocabulary

- [Amazon Mechanical Turk Vocabulary](vocabulary/amazon-mechanical-turk-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 10 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Mechanical Turk Spectral Rules](rules/amazon-mechanical-turk-spectral-rules.yml) — Rules enforcing Amazon Mechanical Turk API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
