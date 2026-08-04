# RateHawk (ratehawk)

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

RateHawk is the B2B hotel and travel booking brand of Emerging Travel Group (ETG). Its Partner API (pAPI v3, served from api.worldota.net) gives OTAs, travel platforms, and agencies programmatic access to 2.5M+ properties with net rates, covering hotel search, prebook, the asynchronous order booking flow, static hotel content, and cancellation over a JSON REST interface secured with HTTP Basic auth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ratehawk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ratehawk/refs/heads/main/apis.yml)

## Tags

- Travel
- Hotels
- Booking
- B2B
- Reservations

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### RateHawk Hotel Search API

Search Engine Results Page (SERP) endpoints returning available hotels and rates by region, by hotel IDs (max 300), or by geo radius for the given dates, occupancy, currency, and residency.

- **Human URL:** [https://docs.emergingtravel.com/docs/b2b-api/hotel-search/](https://docs.emergingtravel.com/docs/b2b-api/hotel-search/)
- **Base URL:** `https://api.worldota.net/api/b2b/v3`

#### Tags

- Hotel Search
- SERP
- Availability

#### Properties

- [Documentation](https://docs.emergingtravel.com/docs/b2b-api/hotel-search/)
- [API Reference](https://docs.emergingtravel.com/docs/b2b-api/endpoints/)
- [OpenAPI](openapi/ratehawk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ratehawk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ratehawk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RateHawk Hotel Page / Prebook API

Retrieve Hotelpage actualizes bookable rates and book_hash values for a single chosen hotel, and Prebook revalidates availability and price for the selected rate (with an optional price_increase_percent bound) before booking.

- **Human URL:** [https://docs.emergingtravel.com/docs/b2b-api/hotel-search/retrieve-hotelpage/](https://docs.emergingtravel.com/docs/b2b-api/hotel-search/retrieve-hotelpage/)
- **Base URL:** `https://api.worldota.net/api/b2b/v3`

#### Tags

- Hotel Page
- Prebook
- Rate Confirmation

#### Properties

- [Documentation](https://docs.emergingtravel.com/docs/b2b-api/hotel-search/retrieve-hotelpage/)
- [API Reference](https://docs.emergingtravel.com/docs/b2b-api/hotel-search/prebook-rate-from-hotelpage-step/)
- [OpenAPI](openapi/ratehawk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ratehawk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ratehawk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RateHawk Order Booking API

The asynchronous order booking flow - booking form, booking finish, and booking finish status polling - plus order information retrieval and order cancellation by the partner's booking identifier.

- **Human URL:** [https://docs.emergingtravel.com/docs/b2b-api/booking/](https://docs.emergingtravel.com/docs/b2b-api/booking/)
- **Base URL:** `https://api.worldota.net/api/b2b/v3`

#### Tags

- Booking
- Orders
- Reservations

#### Properties

- [Documentation](https://docs.emergingtravel.com/docs/b2b-api/booking/create-booking-process/)
- [API Reference](https://docs.emergingtravel.com/docs/b2b-api/booking/check-booking-process/)
- [OpenAPI](openapi/ratehawk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ratehawk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ratehawk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RateHawk Hotel Content / Static API

Static hotel content - address, amenities, descriptions, images, metapolicy, room groups, and star rating - via per-hotel lookup plus full and incremental hotel data dump archives used to build a local catalog.

- **Human URL:** [https://docs.emergingtravel.com/docs/b2b-api/static-content/](https://docs.emergingtravel.com/docs/b2b-api/static-content/)
- **Base URL:** `https://api.worldota.net/api/b2b/v3`

#### Tags

- Static Content
- Hotel Data
- Dump

#### Properties

- [Documentation](https://docs.emergingtravel.com/docs/b2b-api/static-content/b2b-v3-hotel-info/)
- [API Reference](https://docs.emergingtravel.com/docs/b2b-api/static-content/retrieve-hotel-incremental-dump/)
- [OpenAPI](openapi/ratehawk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ratehawk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ratehawk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RateHawk Webhooks

Asynchronous order status notifications delivered to a partner-registered callback URL, used as an alternative to polling the booking finish status endpoint for booking completion.

- **Human URL:** [https://docs.emergingtravel.com/docs/integration-guide/](https://docs.emergingtravel.com/docs/integration-guide/)
- **Base URL:** `https://api.worldota.net/api/b2b/v3`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.emergingtravel.com/docs/integration-guide/)
- [OpenAPI](openapi/ratehawk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/EmergingTravel)
- [LinkedIn](https://www.linkedin.com/company/ratehawk-com)
- [Website](https://www.ratehawk.com)
- [Documentation](https://docs.emergingtravel.com/)
- [Plans](plans/ratehawk-plans-pricing.yml)
- [Rate Limits](rate-limits/ratehawk-rate-limits.yml)
- [Fin Ops](finops/ratehawk-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
