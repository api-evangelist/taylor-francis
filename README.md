# Taylor & Francis (taylor-francis)

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

Taylor & Francis Group is a British academic publisher offering REST APIs for searching and accessing journal articles, books, metadata, and bibliographic records from over 2,700 Taylor & Francis and Routledge publications. Their API surfaces include content download APIs for books and chapters, KBART holdings automation for library systems, COUNTER 5 SUSHI usage reporting, and text and data mining access for institutional subscribers across humanities, social sciences, science, technology, and medicine.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/taylor-francis/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/taylor-francis/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Academic
- Books
- Journals
- Metadata
- Publishing
- Research
- Text Mining

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Taylor & Francis Content API

The Taylor & Francis Content API provides programmatic access to eBook and chapter downloads from the taylorfrancis.com platform. Using DOI-based identifiers, institutional subscribers can retrieve PDF content for monographs and edited volume chapters, including open-access titles, via the api.taylorfrancis.com domain.

- **Human URL:** [https://www.taylorfrancis.com/](https://www.taylorfrancis.com/)
- **Base URL:** `https://api.taylorfrancis.com`

#### Tags

- Books
- Chapters
- Content
- DOI
- Downloads
- eBooks

#### Properties

- [Documentation](https://www.taylorfrancis.com/how-to-obtain-institutional-token)
- [Authentication](https://librarianresources.taylorandfrancis.com/services-support/authentication-and-remote-access/)

### Taylor & Francis KBART Holdings API

The Taylor & Francis KBART Holdings API enables library management systems to automatically retrieve and synchronise institutional journal and eBook entitlements. Librarians generate a Customer Reference Number (CRN) token from the Librarian Dashboard, which LMS providers use to pull KBART holdings files on an automated schedule.

- **Human URL:** [https://librarianresources.taylorandfrancis.com/insights/library-management/enhanced-kbart-features/](https://librarianresources.taylorandfrancis.com/insights/library-management/enhanced-kbart-features/)

#### Tags

- Automation
- eBooks
- Holdings
- Institutional
- KBART
- Library

#### Properties

- [Documentation](https://librarianresources.taylorandfrancis.com/insights/library-management/enhanced-kbart-features/)
- [Getting Started](https://www.taylorfrancis.com/how-to-obtain-institutional-token)

### Taylor & Francis SUSHI / COUNTER 5 API

Taylor & Francis Online supports automated harvesting of COUNTER Release 5 usage statistics via the SUSHI protocol. Institutional library administrators can retrieve Title, Database, Platform, and Item master reports through a COUNTER-compliant REST API using credentials generated from the T&F librarian portal.

- **Human URL:** [https://www.tandfonline.com/page/librarians/usage](https://www.tandfonline.com/page/librarians/usage)

#### Tags

- COUNTER
- Institutional
- Library
- Reporting
- Statistics
- SUSHI
- Usage

#### Properties

- [Documentation](https://www.tandfonline.com/page/librarians/usage)
- [Support](https://help.tandfonline.com/s/article/Usage-reports)
- [Provider Registry](https://registry.countermetrics.org/platform/b0d81a4b-9023-42ac-a034-703c23124cae)

### Taylor & Francis Text and Data Mining API

Taylor & Francis provides API-based text and data mining access to subscribed and open-access content for non-commercial research purposes. Institutions notify Taylor & Francis in advance of TDM projects and receive technical assistance to access full-text content programmatically across journals and books indexed on tandfonline.com and taylorfrancis.com.

- **Human URL:** [https://taylorandfrancis.com/our-policies/textanddatamining/](https://taylorandfrancis.com/our-policies/textanddatamining/)

#### Tags

- Academic
- Content
- Full Text
- Journals
- Research
- Text Mining

#### Properties

- [Documentation](https://taylorandfrancis.com/our-policies/textanddatamining/)
- [Support](https://www.tandfonline.com/page/librarians/usage)

## Common Properties

- [Website](https://taylorandfrancis.com/)
- [Portal](https://www.tandfonline.com/)
- [Librarian Resources](https://librarianresources.taylorandfrancis.com/)
- [Authentication](https://librarianresources.taylorandfrancis.com/services-support/authentication-and-remote-access/)
- [Getting Started](https://www.taylorfrancis.com/how-to-obtain-institutional-token)
- [Support](https://help.tandfonline.com/s/)
- [Terms of Service](https://taylorandfrancis.com/our-policies/)
- [Privacy Policy](https://taylorandfrancis.com/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/taylor-&-francis-group)
- [Twitter](https://x.com/tandfonline)
- [Contact](https://taylorandfrancis.com/contact/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
