# LedgerBase

**Traceable financial fundamentals for developers and AI systems.**

LedgerBase provides normalized company financial data derived from SEC filings, with source lineage attached to every reported metric.

Instead of returning unexplained numbers, LedgerBase helps developers understand:

* What the metric represents
* Which SEC filing it came from
* Which XBRL concept was used
* What reporting period it covers
* Whether the value is available, missing, or ambiguous

## What LedgerBase provides

LedgerBase turns public SEC filing data into consistent, developer-friendly financial fundamentals.

Current capabilities include:

* Company financial metrics
* Income statement, balance sheet, and cash-flow data
* Historical metric values
* Filing and reporting-period metadata
* XBRL fact normalization
* Metric-to-source lineage
* Explicit missing and ambiguous data states
* API documentation and integration examples

## Why LedgerBase exists

Public financial data is available, but using it reliably is difficult.

The same financial concept may be reported under different XBRL tags, periods, units, and filing contexts. Many financial APIs return a normalized number without explaining how that number was produced.

LedgerBase is being built around a different principle:

> A financial metric should not be trusted unless its origin can be inspected.

Every supported value should be traceable back to its underlying filing and source fact.

## Built for

LedgerBase is intended for developers building:

* Financial analysis tools
* Company research applications
* Fundamental-data dashboards
* Screening and comparison products
* AI agents working with financial statements
* Internal financial-data pipelines
* Educational and experimental finance projects

## Core principles

* **Traceability** — every metric should retain its source lineage
* **Correctness** — ambiguous data should not be silently guessed
* **Consistency** — financial concepts should have stable application-level definitions
* **Transparency** — missing, derived, and normalized values should be distinguishable
* **Developer experience** — APIs and documentation should be straightforward to use

## Repositories

The LedgerBase organization contains the components used to build and operate the platform:

* Backend API services
* SEC filing and XBRL ingestion pipelines
* Product documentation
* Landing page and developer resources
* Infrastructure and deployment configuration
* Examples and future SDK integrations

Repository availability may vary while the platform is under active development.

## Project status

LedgerBase is currently under active development and validation.

The API contract, supported companies, financial metrics, ingestion pipeline, and developer experience are being expanded incrementally. Interfaces may evolve as data-quality assumptions are tested against additional filings and issuers.

## Contributing and feedback

Feedback from developers, financial-data users, and open-source contributors is welcome.

You can:

1. Review the available repositories and documentation
2. Report incorrect or unclear financial data
3. Request companies, metrics, or API capabilities
4. Open an issue before proposing substantial changes
5. Submit focused pull requests with appropriate tests and documentation

## Resources

* Explore the repositories below
* Read each repository’s README for setup instructions
* Review the API documentation and examples
* Use GitHub Issues for bugs and feature requests
* Use GitHub Discussions for questions and product feedback

---

**LedgerBase — financial data you can trace back to the source.**
