# National Center for Biotechnology Information (NCBI)

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

National Center for Biotechnology Information with REST APIs for GenBank sequences, gene data, BLAST homology search, literature references, and taxonomy databases.

- **Human URL:** https://www.ncbi.nlm.nih.gov/home/develop/api/
- **Base URL:** https://eutils.ncbi.nlm.nih.gov/entrez/eutils/

## Description

The National Center for Biotechnology Information (NCBI) provides a suite of free, publicly accessible REST APIs for querying and retrieving biological and biomedical data. Offerings include the Entrez Programming Utilities (E-utilities) for searching and fetching records across 38 databases including PubMed, GenBank, Gene, and Taxonomy; the BLAST URL API for homology sequence searching; the NCBI Datasets API for downloading genomic, gene, and taxonomy data; and PubChem APIs for chemical compound data. PMC developer tools provide Open Access article retrieval, metadata harvesting, identifier conversion, and citation export.

## APIs

- **NCBI Entrez E-utilities API** — Access to 38 Entrez databases (PubMed, GenBank, Gene, Taxonomy, Protein) via nine server-side programs for search, retrieval, linking, and batch operations.
- **NCBI BLAST URL API** — Submit nucleotide and protein sequence homology searches, poll for status, and retrieve results asynchronously.
- **NCBI Datasets API** — Download gene, genome, taxonomy, virus, and ortholog data packages defined by an OpenAPI 3.0 specification.
- **PubChem PUG REST API** — Programmatic access to chemical compound, substance, and bioassay data by name, structure, or identifier.
- **PMC Open Access API** — Retrieve citation data, licensing, and file locations for Open Access articles in the PMC archive.
- **PMC ID Converter API** — Batch conversion between PMCID, PMID, Manuscript ID, and DOI.
- **PMC OAI-PMH Service** — Bulk metadata and full-text harvesting of the PMC archive using the OAI-PMH 2.0 protocol.

## Links

- **Developer Portal:** https://www.ncbi.nlm.nih.gov/home/develop/
- **E-utilities Documentation:** https://www.ncbi.nlm.nih.gov/books/NBK25497/
- **BLAST API Documentation:** https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html
- **Datasets API Documentation:** https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/rest-api/
- **PubChem PUG REST Documentation:** https://pubchem.ncbi.nlm.nih.gov/docs/pug-rest
- **PMC Developer Tools:** https://pmc.ncbi.nlm.nih.gov/tools/developers/
- **Terms of Service:** https://www.ncbi.nlm.nih.gov/home/about/policies/
- **Support:** https://support.nlm.nih.gov/support/create-case/
- **Blog / News:** https://ncbiinsights.ncbi.nlm.nih.gov/
