# United States National Library of Medicine

The United States National Library of Medicine (NLM) is the world's largest biomedical library. It serves as a vital resource for researchers, healthcare professionals, and the general public by providing access to a vast collection of biomedical literature and resources. The NLM offers databases, digital archives, and research tools supporting medical research, education, and patient care.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml)

**Website:** https://www.nlm.nih.gov  
**Developer Portal:** https://www.ncbi.nlm.nih.gov/home/develop/api/

## Scope

- **Type:** Contract
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
- **Modified:** 2026-05-03

---

## APIs

### NCBI E-Utilities API

The NCBI Entrez Programming Utilities provide access to all 41 Entrez databases including PubMed, PMC, Gene, Nuccore, and Protein. Supports search, retrieval, linking, and database info operations.

**Human URL:** https://www.ncbi.nlm.nih.gov/books/NBK25497/

#### Tags

- Biomedical, PubMed, Literature, Genomics, Federal Government

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25497/)
- [Portal](https://www.ncbi.nlm.nih.gov/home/develop/api/)
- [OpenAPI](openapi/ncbi-e-utilities-openapi.yml)
- [SpectralRules](rules/ncbi-e-utilities-rules.yml)
- [NaftikoCapability](capabilities/biomedical-literature-research.yaml)

---

### NCBI Datasets REST API

REST API v2 for accessing genome assemblies, gene records, and protein sequences. Full OpenAPI spec available at github.com/ncbi/datasets.

**Human URL:** https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/

#### Tags

- Genomics, Biological Sequences, Gene Data, Federal Government

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/)
- [SwaggerUI](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/rest-api/)
- [OpenAPI](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/openapi3/openapi3.docs.yaml)
- [OpenAPI](openapi/ncbi-datasets-openapi.yml)
- [Repository](https://github.com/ncbi/datasets)
- [NaftikoCapability](capabilities/biomedical-literature-research.yaml)

---

### NCBI BLAST URL API

Submit BLAST sequence searches and retrieve alignment results in multiple formats via HTTPS.

**Human URL:** https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html

#### Tags

- Genomics, Sequence Alignment, Bioinformatics, Federal Government

#### Properties

- [Documentation](https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html)
- [OpenAPI](openapi/ncbi-blast-openapi.yml)

---

### ClinicalTrials.gov API

Programmatic access to clinical trial data for hundreds of thousands of registered trials including protocols, eligibility, locations, and results. No API key required.

**Human URL:** https://clinicaltrials.gov/data-api/api

#### Tags

- Clinical Trials, Healthcare, Research, Federal Government

#### Properties

- [Documentation](https://clinicaltrials.gov/data-api/api)
- [Portal](https://clinicaltrials.gov/data-api/api#introduction)
- [OpenAPI](openapi/nlm-clinicaltrials-openapi.yml)
- [NaftikoCapability](capabilities/biomedical-literature-research.yaml)

---

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [ncbi-e-utilities-openapi.yml](openapi/ncbi-e-utilities-openapi.yml) | NCBI E-Utilities Entrez API (esearch, efetch, esummary, elink) |
| [ncbi-datasets-openapi.yml](openapi/ncbi-datasets-openapi.yml) | NCBI Datasets REST API v2 (genomes, genes, taxonomy) |
| [ncbi-blast-openapi.yml](openapi/ncbi-blast-openapi.yml) | NCBI BLAST URL API (submit, status, retrieve) |
| [nlm-clinicaltrials-openapi.yml](openapi/nlm-clinicaltrials-openapi.yml) | ClinicalTrials.gov REST API v2 |

### Spectral Rules

| File | Description |
|------|-------------|
| [ncbi-e-utilities-rules.yml](rules/ncbi-e-utilities-rules.yml) | Spectral lint rules for NCBI API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | APIs |
|------|------|
| [shared/ncbi-e-utilities.yaml](capabilities/shared/ncbi-e-utilities.yaml) | NCBI E-Utilities (4 operations) |
| [shared/nlm-clinicaltrials.yaml](capabilities/shared/nlm-clinicaltrials.yaml) | ClinicalTrials.gov API (3 operations) |

#### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [biomedical-literature-research.yaml](capabilities/biomedical-literature-research.yaml) | Biomedical literature and clinical research workflows | 7 tools |

### JSON Schemas

| File | Description |
|------|-------------|
| [ncbi-pubmed-article-schema.json](json-schema/ncbi-pubmed-article-schema.json) | Schema for PubMed article records |
| [nlm-clinical-trial-schema.json](json-schema/nlm-clinical-trial-schema.json) | Schema for ClinicalTrials.gov study records |

### JSON Structures

| File | Description |
|------|-------------|
| [ncbi-pubmed-article-structure.json](json-structure/ncbi-pubmed-article-structure.json) | Field structure for PubMed article records |

### JSON-LD Context

| File | Description |
|------|-------------|
| [united-states-national-library-of-medicine-context.jsonld](json-ld/united-states-national-library-of-medicine-context.jsonld) | Linked data context aligning NLM vocabulary with schema.org and BioSchemas |

### Examples

| File | Operation |
|------|-----------|
| [ncbi-esearch-pubmed-example.json](examples/ncbi-esearch-pubmed-example.json) | Search PubMed (E-Utilities esearch) |
| [ncbi-datasets-get-genome-example.json](examples/ncbi-datasets-get-genome-example.json) | Get Genome Dataset Report (NCBI Datasets) |
| [nlm-clinicaltrials-search-example.json](examples/nlm-clinicaltrials-search-example.json) | Search Clinical Trials |

### Vocabulary

| File | Description |
|------|-------------|
| [united-states-national-library-of-medicine-vocabulary.yml](vocabulary/united-states-national-library-of-medicine-vocabulary.yml) | NLM biomedical vocabulary (PubMed, BLAST, MeSH, E-Utilities, NCT IDs, etc.) |

---

## Common Properties

- [Portal](https://www.ncbi.nlm.nih.gov/home/develop/api/)

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
