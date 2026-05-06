# Standards & API Reference

> Project: Carbon Credit Management · Generated: 2026-05-03

## Industry Standards & Specifications

### ISO Standards

**ISO 14064-1:2018 — GHG Quantification and Reporting at Organisation Level**
- URL: https://www.iso.org/standard/66453.html
- The primary international standard specifying principles and requirements for quantifying and reporting organisational greenhouse gas (GHG) emissions and removals, including design and management of a GHG inventory. Foundational for any carbon accounting platform. An updated version (ISO/WD 14064-1.2) is under development as of 2025.

**ISO 14064-2:2019 — GHG Quantification and Reporting for Projects**
- URL: https://www.iso.org/standard/66454.html
- Specifies requirements for planning, quantifying, monitoring, and reporting GHG emission reductions or removal enhancements from specific projects, including baseline establishment and performance period tracking. Directly relevant for carbon credit project lifecycle management.

**ISO 14064-3:2019 — Verification and Validation of GHG Statements**
- URL: https://www.iso.org/standard/66455.html
- Specifies principles and requirements for conducting validation and verification of GHG assertions. Critical for CSRD third-party assurance mandated from 2026. Directly relevant when integrating with accredited Validation and Verification Body (VVB) workflows.

**ISO 14083:2023 — GHG Emissions from Transport Chain Operations**
- URL: https://www.iso.org/standard/78864.html
- Establishes a common methodology for quantifying and reporting GHG emissions from freight and passenger transport chains across all modes (road, rail, sea, air). Relevant for Scope 3 Category 4 (upstream transportation) and Category 9 (downstream transportation) emissions calculations.

**ISO/AWI TS 32214 — Data Model for Carbon Credit Markets (In Development)**
- URL: https://www.iso.org/standard/77780.html
- Under development by ISO Technical Committee 322 (Sustainable Finance), Working Group 5. Aims to create a common reference data model for identifying carbon credit projects and units, enabling interoperability across registries, platforms, and financial systems. Based on the G20 Common Carbon Credit Data Model and Carbon Data Open Protocol (CDOP). Expert working draft expected 2026–2027.

### W3C & IETF Standards

**XBRL (eXtensible Business Reporting Language) / ESRS XBRL Taxonomy**
- URL: https://www.xbrl.org/ and https://www.efrag.org/en/sustainability-reporting/esrs-workstreams
- XBRL is the machine-readable digital format mandated by the EU CSRD for sustainability reporting. The European Financial Reporting Advisory Group (EFRAG) is developing the updated ESRS XBRL taxonomy to support CSRD reporting in the European Single Electronic Format. Any platform generating CSRD-compliant reports must output XBRL.

**RFC 7519 — JSON Web Tokens (JWT)**
- URL: https://datatracker.ietf.org/doc/html/rfc7519
- JWT is the standard token format used for API authentication across major carbon platforms. Required for implementing secure API integrations with registry systems, third-party ESG data providers, and enterprise systems.

**RFC 6749 — OAuth 2.0 Authorization Framework**
- URL: https://datatracker.ietf.org/doc/html/rfc6749
- The standard authorization protocol for delegated access. Used by Greenly, Patch.io, Climatiq, and CDP Disclosure API for third-party integrations. Required for enterprise integrations with ERP, accounting, and HRIS systems.

**OpenAPI Specification 3.x**
- URL: https://spec.openapis.org/oas/latest.html
- The de-facto standard for describing REST APIs. Greenly, Climatiq, Patch.io, and CDP publish OpenAPI specifications or use OpenAPI-based documentation tooling. Building with OpenAPI 3.x from the outset enables automatic SDK generation, documentation, and test tooling.

### Data Model & Carbon Market Specifications

**GHG Protocol Corporate Accounting and Reporting Standard (Revised Edition)**
- URL: https://ghgprotocol.org/corporate-standard
- The foundational accounting standard used by 92%+ of Fortune 500 companies for emissions reporting. Defines Scope 1, 2, and 3 classification, organisational and operational boundary setting, and GHG inventory requirements. Compliance is table-stakes for any corporate carbon management tool.

**GHG Protocol Corporate Value Chain (Scope 3) Standard**
- URL: https://ghgprotocol.org/sites/default/files/standards/Corporate-Value-Chain-Accounting-Reporing-Standard_041613_2.pdf
- Defines the 15 Scope 3 categories (upstream and downstream) and methodology for measuring supply chain emissions. Required for complete Scope 3 accounting features.

**Carbon Data Open Protocol (CDOP) v1.0**
- URL: https://press.spglobal.com/2025-09-23-Carbon-Data-Open-Protocol-CDOP-Coalition-Unveils-Open-Source-Data-Model-at-Climate-Week-NYC-to-Facilitate-and-Scale-Carbon-Markets
- Launched September 2025 at Climate Week NYC by S&P Global–led coalition. Open-source data model providing standardised definitions for five foundational data categories: location, project details, project approach, disclosures, and issuances/retirements. Harmonises 15+ existing data schemas with 1,600+ identified unique data fields. Directly relevant for carbon credit portfolio data models.

**RMI Carbon Crediting Data Framework (CCDF)**
- URL: https://rmi.org/our-work/climate-intelligence/carbon-markets-initiative/the-carbon-crediting-data-framework/
- Open-source toolkit and community designed to address carbon data interoperability challenges. Provides reference data schemas and tooling for connecting registries, platforms, and buyers. Complements CDOP and ISO/AWI TS 32214.

**Verified Carbon Standard (VCS) — Verra Programme Documents**
- URL: https://verra.org/programs/verified-carbon-standard/
- The VCS Programme rules, methodologies, and registration/issuance process documents are publicly available. Implementing credit lifecycle management (issuance, transfer, retirement) requires alignment with VCS serialisation and account structure. Represents ~63% of voluntary carbon market retirements.

**ICVCM Core Carbon Principles (CCP) v2**
- URL: https://icvcm.org/core-carbon-principles/ and https://icvcm.org/wp-content/uploads/2024/02/CCP-Book-V1.1-FINAL-LowRes-15May24.pdf
- Ten science-based principles defining high-quality carbon credits, established by the Integrity Council for the Voluntary Carbon Market (ICVCM). CCP-eligibility is an emerging quality signal covering ~98% of market volume by programme. CCP-labelled credits command premium pricing and are increasingly required by institutional buyers. Platforms must surface CCP status for each credit.

**Paris Agreement Article 6.2 — ITMO Framework**
- URL: https://unfccc.int/process-and-meetings/the-paris-agreement/article-6/article-62
- Provides the international framework for bilaterally traded Internationally Transferred Mitigation Outcomes (ITMOs). Confirmed at COP29 with three authorisation types established. The Centralised Accounting and Reporting Platform (CARP) is being established for Article 6.2 reporting. Relevant for platforms managing government or compliance-market credit transfers.

### Disclosure & Regulatory Frameworks

**IFRS S2 Climate-related Disclosures**
- URL: https://www.ifrs.org/issued-standards/ifrs-sustainability-standards-navigator/ifrs-s2-climate-related-disclosures/
- ISSB standard published June 2023, replacing TCFD recommendations (TCFD disbanded October 2023). Structured on four pillars: Governance, Strategy, Risk Management, Metrics & Targets. Amended December 2025 for GHG emissions disclosure. Mandatory in 40+ jurisdictions. Directly drives demand for structured emissions data with platform-level disclosure report generation.

**EU CSRD / ESRS — European Sustainability Reporting Standards**
- URL: https://finance.ec.europa.eu/financial-markets/company-reporting-and-auditing/company-reporting/corporate-sustainability-reporting_en
- CSRD Omnibus I simplification approved December 2025; applies to companies with 1,000+ employees and €450M+ turnover. Updated ESRS expected Q1/Q2 2026, taking effect for FY2027 reporting. Mandates XBRL machine-readable output. Requires third-party assurance aligned with ISO 14064-3. Key driver for carbon accounting platform demand in Europe.

**EU Carbon Border Adjustment Mechanism (CBAM)**
- URL: https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en
- Entered into force 1 January 2026. Requires importers of CBAM-scope goods (steel, cement, aluminium, fertilisers, electricity, hydrogen) to report embedded emissions and surrender CBAM certificates. The EU CBAM Registry is integrated with national customs systems. Directly relevant for supply chain emissions tracking platforms targeting manufacturers and traders.

**Science Based Targets initiative (SBTi) Corporate Net-Zero Standard**
- URL: https://sciencebasedtargets.org/net-zero and https://files.sciencebasedtargets.org/production/files/SBTi-criteria.pdf
- The SBTi Corporate Near-Term Criteria v5.3.1 (April 2026) governs emissions reduction target validation for 10,000+ companies. Targets must be validated via the SBTi Services Validation Portal. Platforms managing decarbonisation planning must align with SBTi methodology requirements.

**CDP Disclosure Framework**
- URL: https://www.cdp.net/en
- Global voluntary disclosure platform used by 23,000+ companies. CDP Gold software provider status (held by Watershed) signals alignment. CDP Disclosure API enables programmatic questionnaire submission. Key integration target for carbon management platforms.

### Security & Authentication Standards

**OAuth 2.0 (RFC 6749) and OpenID Connect**
- URL: https://datatracker.ietf.org/doc/html/rfc6749 and https://openid.net/connect/
- Standard authorisation and authentication protocols for enterprise API integrations. Required for SSO integrations with enterprise identity providers (Azure AD, Okta) used by target enterprise customers.

**ISO/IEC 27001 — Information Security Management**
- URL: https://www.iso.org/standard/27001
- The information security management standard expected by enterprise carbon accounting customers, particularly financial institutions. Relevant for data residency, access control, and audit logging features.

**SOC 2 Type II**
- URL: https://www.aicpa.org/resources/article/soc-2-guide
- Enterprise compliance requirement for SaaS platforms handling sensitive emissions and financial data. Persefoni and Watershed both carry SOC 2 Type II certification. Required for enterprise procurement qualification.

---

## Similar Products — Developer Documentation & APIs

### Climatiq

- **Description:** Automated carbon emission calculation API providing programmatic access to 944k+ scientifically-validated emission factors across energy, travel, freight, and industrial activities.
- **API Documentation:** https://www.climatiq.io/docs
- **API Reference:** https://www.climatiq.io/docs/api-reference
- **Quickstart Guide:** https://www.climatiq.io/docs/guides/tutorials/quickstart
- **SDKs/Libraries:** Available via Climatiq API Toolkit at https://www.climatiq.io/api-toolkit
- **Standards:** REST/JSON; predictable resource-oriented URLs; standard HTTP response codes; authentication via API key
- **Authentication:** API Key

### Greenly

- **Description:** Carbon footprint tracking SaaS for SMBs with a RESTful Carbon Analytics API enabling programmatic access to emissions calculations and an Open Carbon API for supplier carbon scoring.
- **API Documentation:** https://greenly.redoc.ly/
- **API Endpoints:** Sandbox: https://apisandbox.greenly.earth/v1.5 · Production: https://api.greenly.earth/v1.5
- **Open Carbon API:** Announced May 2023 — assigns companies a carbon transparency score for procurement use cases
- **Developer Access:** Via https://greenly.earth — API keys requested by contacting contact@greenly.earth
- **Standards:** REST/JSON; ReDoc documentation format
- **Authentication:** API Key

### Patch.io

- **Description:** API-first carbon offset procurement and retirement platform enabling developer integration of carbon offsetting directly into applications, with unified access to multiple offset suppliers.
- **API Documentation:** https://www.patch.io/ (developer docs available via platform)
- **JavaScript SDK:** https://github.com/patch-technology/patch-node
- **Standards:** REST/JSON; OpenAPI specification published for third-party integration
- **Authentication:** API Key (per TechCrunch coverage and GitHub SDK)

### CDP Disclosure API

- **Description:** Enables CDP reporting software partners to programmatically submit corporate climate disclosures on behalf of clients, covering corporate, SME, cities, and states/regions questionnaires.
- **API Documentation:** https://help.cdp.net/en-us/knowledgebase/article/KA-01133
- **Introduction Guide:** https://help.cdp.net/en-us/knowledgebase/article/KA-01132
- **Endpoints:** Sandbox: https://api.pre.cdpgreenstar.net/asp/response/ · Production: https://api.cdp.net/response/
- **Open Data Portal:** https://data.cdp.net/
- **Standards:** REST/JSON; ISO 8601 for date-time fields; partner access model
- **Authentication:** Partner credential scheme; requires CDP Gold software provider approval for production access

### AlliedOffsets API

- **Description:** Voluntary carbon market data API providing access to carbon offset project data, credit issuance and retirement records, historical pricing, project documents, and corporate offset buyer data.
- **API Documentation:** https://alliedoffsets.com/api/
- **API Overview:** https://alliedoffsets.com/wp-content/uploads/2023/01/AlliedOffsets-Voluntary-Carbon-Market-Data-API.pdf
- **SDKs/Libraries:** Not publicly listed; REST-based API with JSON responses
- **Standards:** REST/JSON
- **Authentication:** API Key (contact via alliedoffsets.com)

### Sylvera Carbon Credit Analytics API

- **Description:** Independent carbon credit ratings, pricing data, and geospatial analysis for voluntary carbon market credits. API provides programmatic access to ratings, vintage-level pricing, and risk signals.
- **API Documentation:** https://www.sylvera.com/blog/the-carbon-credit-analytics-api (overview); full docs via enterprise account
- **Standards:** REST/JSON; enterprise access model
- **Authentication:** API Key; enterprise contract required

### Persefoni

- **Description:** Enterprise carbon accounting and climate disclosure SaaS providing Scope 1/2/3 emissions calculation, regulatory reporting, and an AI copilot. Integration Hub connects with ERP, accounting, and HR systems.
- **API Overview:** https://apitracker.io/a/persefoni (base REST and GraphQL endpoints)
- **Integration Hub:** https://www.persefoni.com/product/integration-hub
- **Standards:** REST and GraphQL; enterprise access model
- **Authentication:** API Key; enterprise contract required

### EU ETS Data — European Environment Agency (EEA)

- **Description:** Publicly accessible EU Emissions Trading System data from the European Union Transaction Log (EUTL), including emissions, allowances, and firm-level data by country, sector, and year.
- **Data Viewer:** https://www.eea.europa.eu/en/analysis/maps-and-charts/emissions-trading-viewer-1-dashboards
- **Data Hub:** https://www.eea.europa.eu/en/datahub/datahubitem-view/98f04097-26de-4fca-86c4-63834818c0c0
- **Stable URL Data Access:** https://www.euets.info/ (stable r-links for scripts and APIs)
- **Open Dataset:** https://datahub.io/core/eu-emissions-trading-system
- **Standards:** Open data; CSV and API formats; EEA data portal
- **Authentication:** Public access

---

## Notes

**Emerging carbon data standards landscape:** The carbon credit data standards space is rapidly consolidating in 2025–2026. Three parallel initiatives — ISO/AWI TS 32214, Carbon Data Open Protocol (CDOP) v1.0, and RMI's Carbon Crediting Data Framework — are all targeting the same interoperability problem from different angles (financial standards body, industry coalition, and think tank respectively). Implementations should monitor CDOP v1.0 as the fastest-moving initiative and align data models with it while ISO/AWI TS 32214 matures.

**Registry API maturity gap:** Major registries (Verra, Gold Standard, ACR) offer limited programmatic API access compared to commercial platforms. Verra's API is primarily for retirement verification; Gold Standard's Impact Registry has some API functionality but limited documentation. AlliedOffsets provides the most comprehensive VCM data API as a third-party aggregator and may be the most practical integration point for registry data.

**CBAM compliance gap:** The CBAM Registry entered force January 2026 and no commercial carbon management platform yet provides end-to-end CBAM certificate management alongside carbon accounting. This represents a significant near-term opportunity for a platform combining supply chain emissions tracking with CBAM certificate procurement and retirement workflows.

**Article 6 / ITMO systems:** The Centralized Accounting and Reporting Platform (CARP) for Article 6.2 reporting is in early-stage development. Government and compliance market buyers will require integration with this system as Article 6 cooperative approaches scale post-COP29.
