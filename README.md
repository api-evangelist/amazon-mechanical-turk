# Amazon Mechanical Turk (amazon-mechanical-turk)
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
