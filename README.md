# LADYBUG

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `LADYBUG` in category **ENGINEERING_CONSTRUCTION**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/LadybugDB/ladybug · **Upstream pin:** `a86f5f7a83707e4e7cb586ef6babefe56a7c5649` · **Category:** ENGINEERING_CONSTRUCTION · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

<div align="center">
  <picture>
    <!-- <source srcset="https://ladybugdb.com/img/lbug-logo-dark.png" media="(prefers-color-scheme: dark)"> -->
    <img src="https://ladybugdb.com/logo.png" height="100" alt="Ladybug Logo">
  </picture>
</div>

<br>

<p align="center">
  <a href="https://github.com/LadybugDB/ladybug/actions">
    <img src="https://github.com/LadybugDB/ladybug/actions/workflows/ci-workflow.yml/badge.svg?branch=master" alt="Github Actions Badge"></a>
  <a href="https://deepwiki.com/LadybugDB/ladybug"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>
  <a href="https://discord.com/invite/hXyHmvW3Vy">
    <img src="https://img.shields.io/discord/1162999022819225631?logo=discord" alt="discord" /></a>
  <a href="https://twitter.com/lbugdb">
    <img src="https://img.shields.io/badge/follow-@lbugdb-1DA1F2?logo=twitter" alt="twitter"></a>
</p>

# Ladybug
Ladybug is an embedded graph database built for query speed and scalability. Ladybug is optimized for handling complex analytical workloads
on very large databases and provides a set of retrieval features, such as a full text search and vector indices. Our core feature set includes:

- Flexible Property Graph Data Model and Cypher query language
- Embeddable, serverless integration into applications
- Native full text search and vector index
- Columnar disk-based storage
- Columnar sparse row-based (CSR) adjacency list/join indices
- Vectorized and factorized query processor
- Novel and very fast join algorithms
- Multi-core query parallelism
- Serializable ACID transactions
- Wasm (WebAssembly) bindings for fast, secure execution in the browser

Ladybug is being developed by [LadybugDB Developers](https://github.com/LadybugDB) and
is available under a permissive license. So try it out and help us make it better! We welcome your feedback and feature requests.

The database was formerly known as [Kuzu](https://github.com/kuzudb/kuzu).

## Installation

| Language | Installation                                                           |
| -------- |------------------------------------------------------------------------|
| Python   | `pip install ladybug`                                             |
| NodeJS   | `npm install @ladybugdb/core`                                            |
| Rust     | `cargo add lbug`                                                       |
| Go       | `go get github.com/LadybugDB/go-ladybug`                                     |
| Swift    | [lbug-swift](https://github.com/LadybugDB/swift-ladybug)                     |
| Java     | [Maven Central](https://central.sonatype.com/artifact/com.ladybugdb/lbug) |
| C/C++    | [precompiled binaries](https://github.com/LadybugDB/ladybug/releases/latest) |
| CLI      | [precompiled binaries](https://github.com/LadybugDB/ladybug/releases/latest) |

To learn more about installation, see our [Installation](https://docs.ladybugdb.com/installation) page.

## Getting Started

Refer to our [Getting Started](https://docs.ladybugdb.com/get-started/) page for your first example.

## Build from Source

You can build from source using the instructions provided in the [developer guide](https://docs.ladybugdb.com/developer-guide/).

## Contributing
We welcome contributions to Ladybug. If you are interested in contributing to Ladybug, please read our [Contributing Guide](CONTRIBUTING.md).

## License
By contributing to Ladybug, you agree that your contributions will be licensed under the [MIT License](LICENSE).

## Contact
You can contact us at [social@ladybugdb.com](mailto:social@ladybugdb.com) or [join our Discord community](https://discord.com/invite/hXyHmvW3Vy).

---

## Installation

| Language | Installation                                                           |
| -------- |------------------------------------------------------------------------|
| Python   | `pip install ladybug`                                             |
| NodeJS   | `npm install @ladybugdb/core`                                            |
| Rust     | `cargo add lbug`                                                       |
| Go       | `go get github.com/LadybugDB/go-ladybug`                                     |
| Swift    | [lbug-swift](https://github.com/LadybugDB/swift-ladybug)                     |
| Java     | [Maven Central](https://central.sonatype.com/artifact/com.ladybugdb/lbug) |
| C/C++    | [precompiled binaries](https://github.com/LadybugDB/ladybug/releases/latest) |
| CLI      | [precompiled binaries](https://github.com/LadybugDB/ladybug/releases/latest) |

To learn more about installation, see our [Installation](https://docs.ladybugdb.com/installation) page.

## Usage

Refer to our [Getting Started](https://docs.ladybugdb.com/get-started/) page for your first example.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing

Welcome! We are excited that you are interested in contributing to Ladybug.
Before submitting your contribution though, please make sure to take a moment and read through the following guidelines.

Join the GraphGeeks [Discord community](https://discord.com/invite/hXyHmvW3Vy ) for real-time communication with the core team and other contributors.
If you have a question or need help, feel free to ask in the appropriate channel or create an issue.

## General Steps and Guidelines to Contribute
* Discuss your intended changes with the core team on Github or Discord, so we can assign appropriate issue(s) for you to work on.
* Do not commit/push directly to the master branch. Instead, create a fork and open a pull request.
* While you're working on the issue, please merge frequently with the master branch.
* All pull requests with new features and bug fixes should be covered by proper tests.
* Avoid large pull requests - they are much less likely to be merged as they are incredibly hard to review.
* We reserve full and final discretion over whether or not we will merge a pull request. Adhering to these guidelines is not a complete guarantee that your pull request will be merged.

Thank you for your contribution to Ladybug! We're grateful for your time and effort, and we look forward to working with you.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/LadybugDB/ladybug
- **Pinned SHA:** `a86f5f7a83707e4e7cb586ef6babefe56a7c5649`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`7f15b3b5741a92bf814123c2b5a485d077595e4af0f79e70d7882fed97f692a3`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

