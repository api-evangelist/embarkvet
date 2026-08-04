# Embark Veterinary (embarkvet)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Embark Veterinary is a canine genomics and biotechnology company (founded 2015; headquartered in Boston, Massachusetts) that sells at-home dog DNA test kits for breed identification, ancestry, and genetic health screening. A cheek-swab sample is analyzed on Embark's proprietary genotyping platform of 200,000+ genetic markers, and results — 400+ breeds, 270+ genetic health conditions, allergy risk, coat/trait predictions, a relative finder, and (for breeders) a Pair Predictor and eCOI dashboard — are delivered through Embark's website and mobile apps.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/embarkvet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/embarkvet/refs/heads/main/apis.yml)

## API Access Model — No Public Developer API

As of this review (2026-07-03), Embark does **not** publish a documented public or partner developer API. This entry is an honest stub. Findings:

- **Consumer / DTC delivery.** Embark is a direct-to-consumer genetics service. Results are consumed through Embark's own web dashboard and its iOS/Android apps, not through a programmatic API for third-party developers.
- **No developer portal or API docs.** There is no `developers` page, API reference, OpenAPI document, published base URL, SDK, or authentication scheme for an Embark data API. (`embarkvet.com/developers` returns 404.)
- **Raw data download, not an API.** Embark's differentiator is data ownership: every customer can freely **download their dog's raw genetic data file** and share it with a breed club, a health database, or a researcher. This is a per-account file export, not a queryable API.
- **Breeder tools are a dashboard.** The breeder offering (Pair Predictor, eCOI, base coat color predictions, litter planning) is a web dashboard feature set, not a documented programmatic interface.
- **Research is partnership-gated.** Embark collaborates with research partners (Cornell University College of Veterinary Medicine, NIH, Morris Animal Foundation, breed clubs) and publishes research code under the `ProjectAussie` GitHub organization. Data access for research runs through direct partnership (research@ / breeders@ / partner program), not a self-serve API.

Because no API surface is documented, no `apis` are listed in `apis.yml`, and no `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` artifacts were created (nothing to model without fabrication). If Embark publishes a developer or partner API in the future, this entry should be upgraded with real, sourced endpoints.

## Products & Pricing (DNA kits, not API plans)

Consumer product prices as listed on shop.embarkvet.com / retail partners (USD, subject to promotions):

- **Breed + Health Dog DNA Test** — regular ~$199 (frequently on sale ~$118); 400+ breeds and 270+ health conditions, allergy risk, relatives, traits.
- **Breed Identification Dog DNA Test** — regular ~$129 (sale ~$109); ancestry/breed mix without the health screening.
- **Embark for Breeders Dog DNA Test** — breeder-tier kit with the breeder dashboard and Pair Predictor tools.
- Also sells probiotics and health supplements.

Kits ship a cheek swab; results are typically available online in ~2–4 weeks.

## Tags

- Canine Genomics
- Dog DNA Test
- Breed Identification
- Genetic Health
- Direct to Consumer
- Pet Tech
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Common Properties

- [Website](https://embarkvet.com/)
- [LinkedIn](https://www.linkedin.com/company/embark-vet)
- [Store](https://shop.embarkvet.com/)
- [Support](https://help.embarkvet.com/hc/en-us)
- [Partnerships](https://help.embarkvet.com/hc/en-us/sections/10867850136731-Partner-With-Us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
