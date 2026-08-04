# United States National Library of Medicine (united-states-national-library-of-medicine)

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

The United States National Library of Medicine (NLM) is the world's largest biomedical library. It serves as a vital resource for researchers, healthcare professionals, and the general public by providing access to a vast collection of biomedical literature and resources. The NLM offers a wide range of services and resources including online databases, digital archives, and research tools that support medical research, education, and patient care. Key APIs include the NCBI E-Utilities (PubMed, Entrez), NCBI Datasets (genomes, genes), BLAST sequence alignment, and the ClinicalTrials.gov API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Biomedical Research
- Healthcare
- Genomics
- Literature

## Timestamps

- **Created:** 2024/01/01
- **Modified:** 2026-05-19

## APIs

### NCBI E-Utilities API

The NCBI E-Utilities (Entrez Programming Utilities) are the public API to the NCBI Entrez system providing access to all Entrez databases including PubMed (biomedical literature), PMC (full-text articles), Gene, Nuccore (nucleotide sequences), Protein, and 39 other databases. Supports search, retrieval, linking, and posting operations. API keys from ncbi.nlm.nih.gov/account/ increase the rate limit from 3 to 10 requests/second.

- **Human URL:** [https://www.ncbi.nlm.nih.gov/books/NBK25497/](https://www.ncbi.nlm.nih.gov/books/NBK25497/)
- **Base URL:** `https://eutils.ncbi.nlm.nih.gov/entrez/eutils`

#### Tags

- Biomedical
- PubMed
- Literature
- Genomics
- Federal Government

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25497/)
- [Portal](https://www.ncbi.nlm.nih.gov/home/develop/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-e-utilities-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/rules/ncbi-e-utilities-rules.yml)
- [Postman Collection](collections/ncbi-blast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-blast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-datasets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-datasets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-e-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-e-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nlm-clinicaltrials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nlm-clinicaltrials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NCBI Datasets REST API

The NCBI Datasets REST API v2 provides programmatic access to biological data including genome assemblies, gene records, and protein sequences across organisms. Returns data packages containing sequences, annotations, metadata, and related data. An OpenAPI 3.0 specification is available on GitHub at github.com/ncbi/datasets. API keys are optional but increase rate limits.

- **Human URL:** [https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/)
- **Base URL:** `https://api.ncbi.nlm.nih.gov/datasets/v2`

#### Tags

- Genomics
- Biological Sequences
- Gene Data
- Federal Government

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/)
- [Swagger U I](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/rest-api/)
- [OpenAPI](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/openapi3/openapi3.docs.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-datasets-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Repository](https://github.com/ncbi/datasets)
- [Postman Collection](collections/ncbi-blast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-blast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-datasets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-datasets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-e-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-e-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nlm-clinicaltrials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nlm-clinicaltrials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NCBI BLAST URL API

The NCBI BLAST URL API allows developers to submit BLAST (Basic Local Alignment Search Tool) sequence searches for processing at NCBI using HTTPS. Supports nucleotide and protein sequence searches against NCBI databases. The API can check the status of submitted searches and retrieve results in multiple formats including XML, JSON, text, and ASN.1.

- **Human URL:** [https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html](https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html)
- **Base URL:** `https://blast.ncbi.nlm.nih.gov/blast/Blast.cgi`

#### Tags

- Genomics
- Sequence Alignment
- Bioinformatics
- Federal Government

#### Properties

- [Documentation](https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-blast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ncbi-blast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-blast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-datasets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-datasets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-e-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-e-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nlm-clinicaltrials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nlm-clinicaltrials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClinicalTrials.gov API

The ClinicalTrials.gov API provides programmatic access to clinical trial data registered with ClinicalTrials.gov, operated by the National Library of Medicine. Returns study information, eligibility criteria, outcomes, locations, sponsor/collaborator data, and results for hundreds of thousands of trials. No API key required.

- **Human URL:** [https://clinicaltrials.gov/data-api/api](https://clinicaltrials.gov/data-api/api)
- **Base URL:** `https://clinicaltrials.gov/api/v2`

#### Tags

- Clinical Trials
- Healthcare
- Research
- Federal Government

#### Properties

- [Documentation](https://clinicaltrials.gov/data-api/api)
- [Portal](https://clinicaltrials.gov/data-api/api#introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/nlm-clinicaltrials-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ncbi-blast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-blast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-datasets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-datasets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ncbi-e-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncbi-e-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nlm-clinicaltrials.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nlm-clinicaltrials.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/national-library-of-medicine-nlm)
- [Portal](https://www.ncbi.nlm.nih.gov/home/develop/api/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
