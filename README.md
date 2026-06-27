# RateHawk (ratehawk)

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
