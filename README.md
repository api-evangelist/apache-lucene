# Apache Lucene (apache-lucene)

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

Apache Lucene is a high-performance, full-featured text search engine library written entirely in Java. It provides indexing and search technology, as well as spellchecking, hit highlighting, faceting, vector similarity search, and advanced analysis and tokenization capabilities. Lucene is the foundation for many popular search applications including Apache Solr.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-lucene/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Full-Text Search, Indexing, Java, Search, Text Analysis, Vector Search

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Lucene
Lucene provides a comprehensive Java API for full-text indexing, searching, faceting, hit highlighting, spatial search, vector nearest-neighbor search, and text analysis with support for custom analyzers, query parsers, and pluggable ranking models including BM25 and Vector Space Model.

**Human URL:** [https://lucene.apache.org/core/](https://lucene.apache.org/core/)

#### Tags:

 - Indexing, Java, Search, Vector Search, Text Analysis

#### Properties

- [Documentation](https://lucene.apache.org/core/)
- [Documentation](https://lucene.apache.org/core/10_4_0/index.html)
- [GettingStarted](https://lucene.apache.org/core/quickstart.html)
- [Maven Central (Java)](https://central.sonatype.com/artifact/org.apache.lucene/lucene-core)
- [GitHubRepository](https://github.com/apache/lucene)

## Common Properties

- [Portal](https://lucene.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/lucene)
- [GitHubRepository](https://github.com/apache/lucenenet)
- [IssueTracker](https://github.com/apache/lucene/issues)
- [Blog](https://lucene.apache.org/news.html)
- [MailingList](https://lists.apache.org/list.html?dev@lucene.apache.org)
- [Slack](https://the-asf.slack.com/messages/CE70MDPMF)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Full-Text Indexing | High-performance full-text indexing with over 800GB/hour throughput on modern hardware with minimal RAM requirements. |
| Vector Nearest-Neighbor Search | Native support for approximate and exact k-nearest-neighbor vector similarity search alongside traditional keyword search. |
| Advanced Query Types | Supports phrase queries, wildcard, proximity, range, fuzzy, and fielded queries with pluggable query parsers. |
| Faceting and Grouping | Built-in faceted search and result grouping capabilities for navigation and aggregation. |
| Hit Highlighting | Highlights search keywords in result snippets using the Highlighter and UnifiedHighlighter modules. |
| Spell Checking and Suggestions | Auto-suggest and spell-checking support via the Suggest module with multiple suggester implementations. |
| Pluggable Analyzers | Extensive analyzer ecosystem supporting dozens of languages including ICU, Kuromoji (Japanese), Nori (Korean), OpenNLP, and more. |
| Pluggable Ranking Models | Supports Vector Space Model, Okapi BM25, and custom pluggable similarity implementations. |
| Spatial Search | Geospatial search capabilities via the Spatial and Spatial3D modules. |
| Replication Support | Index replication support via the Replicator module for leader-follower architectures. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Search | Power full-text search across enterprise documents, emails, databases, and file systems. |
| E-Commerce Product Search | Implement fast, relevant product search with facets, autocomplete, and spell correction. |
| Log and Event Search | Index and search structured and unstructured log data for observability and security analytics. |
| Semantic Search | Combine keyword search with vector embeddings for hybrid semantic and lexical retrieval. |
| Knowledge Base Search | Build searchable knowledge bases and documentation portals with rich query capabilities. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Solr | Apache Solr is built on top of Lucene and adds distributed search, REST API, and enterprise features. |
| Elasticsearch/OpenSearch | Elasticsearch and OpenSearch use Lucene as their underlying search engine. |
| Apache Hadoop | Lucene integrates with Hadoop for large-scale distributed indexing pipelines. |
| Apache Tika | Apache Tika extracts text from thousands of file formats for indexing into Lucene. |
| Apache OpenNLP | OpenNLP provides NLP analysis capabilities integrated through Lucene analyzers. |
| Apache Nutch | Apache Nutch is a web crawler that stores and indexes content via Lucene. |
| Lucene.NET | Official .NET port of Apache Lucene, maintained in the apache/lucenenet repository. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
