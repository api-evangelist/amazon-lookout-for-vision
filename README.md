# Amazon Lookout for Vision (amazon-lookout-for-vision)

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

Amazon Lookout for Vision is a machine learning service that spots defects and anomalies in visual representations using computer vision. With just a small sample of images, it builds a custom computer vision model to enable you to identify damaged products or issues before production issues arise. It supports projects, datasets, model training, and real-time anomaly detection.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Computer Vision, Machine Learning, Manufacturing, Quality Inspection, Anomaly Detection

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Lookout for Vision API
The Amazon Lookout for Vision API provides programmatic access to create and manage projects, datasets, models, and anomaly detection jobs for visual quality inspection using computer vision. Supports 22 operations covering the full model lifecycle from dataset management through real-time anomaly detection.

**Human URL:** [https://aws.amazon.com/lookout-for-vision/](https://aws.amazon.com/lookout-for-vision/)

#### Tags:

 - Computer Vision, Machine Learning, Quality Inspection, Anomaly Detection

#### Properties

- [Documentation](https://docs.aws.amazon.com/lookout-for-vision/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-lookout-for-vision-openapi-original.yaml)
- [GettingStarted](https://aws.amazon.com/lookout-for-vision/getting-started/)
- [Pricing](https://aws.amazon.com/lookout-for-vision/pricing/)
- [FAQ](https://aws.amazon.com/lookout-for-vision/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/lookout-for-vision/)
- [Documentation](https://docs.aws.amazon.com/lookout-for-vision/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-vision/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/lookoutvision/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-lookout-for-vision-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-lookout-for-vision-vocabulary.yaml)
- [NaftikoCapability](capabilities/visual-inspection-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| Custom Computer Vision Models | Build custom visual inspection models with just a small sample of images, no ML expertise required. |
| Real-Time Defect Detection | Run inference on images in real time to detect defects and anomalies on the production line. |
| Edge Deployment | Package and deploy models to edge devices for local inference without cloud connectivity. |
| Dataset Management | Manage labeled training and test datasets directly through the API. |
| Model Packaging Jobs | Package trained models for deployment to AWS IoT Greengrass edge devices. |

## Use Cases

| Name | Description |
|------|-------------|
| Manufacturing Quality Control | Automate visual inspection of manufactured products to detect surface defects, assembly errors, and damaged items. |
| Electronics Assembly Inspection | Detect solder defects, missing components, and board damage in electronics manufacturing. |
| Food and Beverage Quality | Identify contaminated, damaged, or improperly packaged food products on production lines. |
| Pharmaceutical Packaging | Verify correct labeling, packaging integrity, and tablet quality in pharmaceutical manufacturing. |
| Automotive Parts Inspection | Detect cracks, scratches, and dimensional defects in automotive components. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store training images and dataset manifests in S3 buckets. |
| AWS IoT Greengrass | Deploy packaged models to IoT Greengrass edge devices for local inference. |
| Amazon CloudWatch | Monitor model performance metrics and detection results in CloudWatch. |
| AWS KMS | Encrypt model artifacts using AWS Key Management Service. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Lookout for Vision OpenAPI](openapi/amazon-lookout-for-vision-openapi-original.yaml)

### JSON Schema

131 schema files available in the [json-schema/](json-schema/) directory.

### JSON Structure

131 structure files available in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Amazon Lookout for Vision Context](json-ld/amazon-lookout-for-vision-context.jsonld)

### Examples

131 example files available in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Lookout for Vision](capabilities/shared/lookout-for-vision.yaml) — 9 operations for project management, model training, and anomaly detection

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Visual Inspection Workflow](capabilities/visual-inspection-workflow.yaml) | Amazon Lookout for Vision | 8 | Manufacturing Engineer, Quality Inspector |

## Vocabulary

- [Amazon Lookout for Vision Vocabulary](vocabulary/amazon-lookout-for-vision-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Lookout for Vision Spectral Rules](rules/amazon-lookout-for-vision-spectral-rules.yml) — 18 rules across 7 categories enforcing Amazon Lookout for Vision API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
