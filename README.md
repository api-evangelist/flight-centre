# Flight Centre Travel Group (flight-centre)

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

Flight Centre Travel Group (ASX: FLT) is a Brisbane-headquartered travel retailer and corporate travel manager, one of the largest agency groups in the world and by far the largest in its home market of Australia. It operates more than thirty brands across leisure retail (Flight Centre, Travel Associates, Cruiseabout, Aunt Betty, BYOjet, Envoyage, Scott Dunn, StudentUniverse), corporate travel management (FCM, Corporate Traveller, Stage and Screen, FCM Consulting) and wholesale supply (Discova, Infinity Holidays, Topdeck, Backroads Touring, TPConnects), with company-owned operations in twenty-four countries and licensed operations in roughly ninety more. Structurally it sits on the demand side of the travel distribution chain — an aggregator-reseller that buys airline, hotel, cruise and land content through the GDSs (Sabre and Amadeus), through NDC aggregators, and through direct supplier agreements, and resells it to consumers and corporate travel programmes.

Its API posture is honestly assessed as **none published**. Flight Centre Travel Group operates no developer portal, publishes no API reference, no OpenAPI, and no partner API documentation on any of its brand domains. The group's genuine machine-readable distribution asset is TPConnects, the Dubai NDC aggregator it holds a majority stake in, whose Iris and Astra APIs are described on public product pages but whose reference documentation sits behind a ReadMe login.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flight-centre/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flight-centre/refs/heads/main/apis.yml)

## Tags

- Travel
- Australia
- Corporate Travel
- Travel Agency
- Distribution
- NDC
- Aviation
- Booking
- Hotels
- Aggregator

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

None. `apis[]` is deliberately empty.

Every developer-shaped subdomain probed on `fctgl.com`, `fcmtravel.com`, `flightcentre.com.au`, `corporatetraveler.us`, `discova.com`, `studentuniverse.com` and `envoyage.com` fails to resolve in DNS. Every conventional discovery path on `fctgl.com` — `/developers`, `/api`, `/docs`, `/openapi.json`, `/swagger.json`, `/api-docs`, `/.well-known/security.txt` — returns 404. No GitHub organisation exists for `flightcentre`, `fctg`, `fcmtravel` or `FlightCentreTravelGroup`; the one that does exist, `github.com/Discova`, has zero public repositories.

See [review.yml](review.yml) for the full probe log and the switching-cost analysis.

## Artifacts

| Artifact | File | What it records |
| --- | --- | --- |
| Conformance | [conformance/flight-centre-conformance.yml](conformance/flight-centre-conformance.yml) | IATA NDC Level 4 (claimed), NDC Schema 18.2/21.3 via TPConnects, OAuth 2.0 / OIDC on tpconnects.com, and the standards that are genuinely not applicable. No compliance programme is published — no SOC 2, ISO 27001, PCI DSS, HIPAA or FedRAMP claim exists on any group domain. |
| Well-known | [well-known/flight-centre-well-known.yml](well-known/flight-centre-well-known.yml) | Every `/.well-known/` path probed across nine group hosts. Flight Centre serves none; the only live documents belong to 70%-owned TPConnects and are archived alongside. |
| Domain security | [security/flight-centre-domain-security.yml](security/flight-centre-domain-security.yml) | TLS, HSTS, DNSSEC, CAA, SPF and DMARC across nine hosts and eight domains. All HTTPS; six of nine serve HSTS; two domains are DNSSEC-signed; only `envoyage.com` publishes CAA. |
| MCP posture | [mcp/flight-centre-mcp.yml](mcp/flight-centre-mcp.yml) | TPConnects announced MCP layers over Astra (March 2026) and Iris (April 2026). Announcements only — no server URL, no tool list, every discovery probe fails. No `MCPServer` pointer is claimed. |
| Packages | [packages/flight-centre-packages.yml](packages/flight-centre-packages.yml) | npm, PyPI and GitHub sweep. Zero first-party SDKs. Both group GitHub organisations have zero public repositories. |
| llms.txt | [llms/flight-centre-llms.txt](llms/flight-centre-llms.txt) | Generated. The group publishes no `llms.txt` of its own, but FCM and Corporate Traveler both publish human-readable `/llm-info` pages written for AI assistants, and [tpconnects.com/llms.txt](llms/flight-centre-tpconnects-llms.txt) is archived verbatim. |

### What changed in the 2026-07-28 round

The "no published API" finding is unchanged for every Flight Centre brand. Three new machine-readable facts turned up one level down at 70%-owned TPConnects: a real `llms.txt`, live OIDC/RFC 8414 discovery documents on the web property, and two 2026 press releases announcing MCP layers over the Iris and Astra platforms. A genuine API host was also identified — `api.iris.tpconnects.com` resolves and returns `401` for every path, including `/openapi.json` and `/swagger/v1/swagger.json`, so the contract-discovery pass still ends with no machine-readable contract in public.

## Switching Cost

| Dimension | Finding |
| --- | --- |
| Interface shape | `none-published` — nothing to conform to a standard, nothing to swap |
| Second source | `alternatives-with-migration` — GBT, BCD, CWT, CTM, Navan, TravelPerk, Webjet |
| Exit path | `export-on-request` — GDPR-style subject access request via a live OneTrust web form; no bulk export for corporate booking data |
| Identifier portability | IATA airline/airport codes and PNR record locators are portable; the IATA/ARC agency accreditation number that negotiated fares attach to is not |
| Contractual lock-in | Nothing published — no developer terms, no API licence, no MSA; `/terms`, `/terms-of-use`, `/legal` all 404 |
| Distribution model | `aggregator-reseller`, GDS-intermediated upstream (Sabre global technology partner since 2018) |
| NDC posture | IATA NDC Level 4 certified (first global TMC, full offer and order management) — but no public NDC endpoint and no published NDC API |
| Access gate | `none-published` — there is no developer programme to apply to |

## Common Properties

- [Website](https://www.fctgl.com/)
- [Brands](https://www.fctgl.com/brands)
- [Investor Relations](https://www.fctgl.com/investors)
- [News](https://www.fctgl.com/news)
- [Global Locations](https://www.fctgl.com/global-locations)
- [Privacy Policy](https://www.fctgl.com/privacy-policy)
- [Cookies Policy](https://www.fctgl.com/cookies-policy)
- [Data Portability — Subject Access Request](https://privacyportal-de.onetrust.com/webform/01c95262-28d1-4b76-89f7-6b0b650d1af2/d036c47c-47be-4cb7-be63-5a65a9cc5f0d)
- [LinkedIn](https://www.linkedin.com/company/flight-centre)
- [FCM NDC Hub](https://www.fcmtravel.com/en/travel-insights/our-approach-ndc)
- [IATA NDC Level 4 Certification Announcement](https://www.fcmtravel.com/en/resources/news-hub/fcm-is-first-global-tmc-to-achieve-iata-ndc-level-4-certification)
- [FCM Travel — LLM Info](https://www.fcmtravel.com/en-us/llm-info)
- [Corporate Traveler — LLM Info](https://www.corporatetraveler.us/en-us/llm-info)

## Maintainers

- Kin Lane — kin@apievangelist.com
