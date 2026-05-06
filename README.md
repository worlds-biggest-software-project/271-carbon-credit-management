# Carbon Credit Management

> Part of the [worlds-biggest-software-project](https://github.com/worlds-biggest-software-project) initiative.
>
> An AI-native, open-source platform for emissions tracking, offset management, and registry integration — bringing investor-grade carbon accounting within reach of organisations beyond the enterprise tier.

Carbon Credit Management is a candidate project to build a carbon accounting and offset workflow platform aligned with the GHG Protocol, ISO 14064, and the major voluntary registries (Verra, Gold Standard, ACR). It is aimed at sustainability teams, ESG analysts, procurement and compliance officers who need defensible Scope 1, 2, and 3 data, credible offset procurement, and disclosure-ready reporting without six-figure software contracts.

---

## Why Carbon Credit Management?

- Enterprise incumbents Persefoni and Watershed charge roughly USD 50,000–250,000 per year, restricting comprehensive carbon accounting to large corporates.
- Mid-market tools such as Greenly and KEY ESG are more accessible but offer shallower Scope 3 depth, smaller emission factor libraries, and limited decarbonisation strategy support.
- Registry platforms (Verra, Gold Standard, ACR) track issuance and retirement but provide no financial workflows, no buyer-side portfolio management, and no Scope 1/2/3 accounting — buyers must stitch tools together.
- Salesforce Net Zero Cloud requires the Salesforce ecosystem; Patch.io is API-first for procurement only, with no corporate accounting; CarbonChain serves only commodity-heavy supply chains.
- Regulatory pressure (SEC climate rules, CSRD, CBAM, EUDR, SB 253) and voluntary market integrity concerns are driving demand for registry-integrated, verifiable offset tooling that today's stack does not deliver in one place.

---

## Key Features

### Emissions Accounting

- Scope 1, 2, and 3 emissions accounting aligned with the GHG Protocol Corporate Standard
- Emissions calculation engine with configurable emission factors and custom factor creation
- Multi-entity and multi-site consolidation
- Audit trail documenting all data changes and calculations
- User role management and access control

### Offset Procurement and Portfolio Management

- Integration with major carbon offset registries (Verra, Gold Standard, ACR) for credit verification and retirement tracking
- Multi-supplier offset procurement and portfolio aggregation with contract-terms tracking
- Retirement verification and serialised credit lifecycle visibility
- Dashboard showing offset portfolio status, retirement progress, and compliance deadlines

### Disclosure and Compliance Reporting

- Report generation for standard frameworks (TCFD, GRI, with planned CSRD, SEC climate rules, ISSB S2, SFDR support)
- Regulatory roadmap surfacing upcoming carbon policy deadlines (SB 253, CSRD, CBAM, EUDR)
- Export pathways for regulatory submission

### Scope 3 and Supplier Engagement

- Integrated supplier questionnaire workflow for Scope 3 data collection
- Spend-based to activity-based emissions progression as data quality improves
- Automated reminders and supplier data tracking

### AI Assistance

- AI-powered anomaly detection flagging suspicious offset projects and data-quality issues
- Conversational assistant guiding users through carbon accounting and reporting decisions
- Enhanced credit-quality scoring combining registry data with supply-chain visibility

---

## AI-Native Advantage

Carbon Credit Management uses LLMs to parse supplier invoices, shipping records, and procurement documents to auto-populate Scope 3 categories — eliminating a manual bottleneck that incumbent platforms still require supplier questionnaires to fill. AI-driven credit-quality scoring cross-references registry data, satellite imagery, and third-party audit reports to flag low-integrity offsets before purchase, while a continuous reconciliation engine detects double-counting across Verra, Gold Standard, and ACR. A conversational disclosure assistant generates TCFD, ISSB S2, and CSRD narrative sections from structured emissions data with citation traceability back to the underlying records.

---

## Tech Stack & Deployment

The project is expected to ship as a SaaS-deployable platform with self-hosting as a first-class option, reflecting the ~70% SaaS share of new contracts in this market. Integrations target ERP and accounting systems (SAP, Oracle, NetSuite, QuickBooks), travel and procurement systems, and the public APIs exposed by Verra, Gold Standard, and ACR. Methodologies follow the GHG Protocol, ISO 14064, VCS, Gold Standard, SBTi, and TCFD / ISSB IFRS S2; CORSIA and EU ETS support is in scope for aviation and European compliance use cases.

---

## Market Context

The carbon management software market was valued at approximately USD 4.69 billion in 2026 and is projected to reach USD 42.70 billion by 2035 (CAGR ~27.82%); a broader carbon accounting software view places the 2026 market at ~USD 27.78 billion growing at 22.9% CAGR (Global Growth Insights 2025; The Business Research Company 2026). Enterprise incumbents charge USD 50,000–250,000+ per year while mid-market tools start near USD 299/month. Primary buyers are Chief Sustainability Officers, ESG teams at financial institutions, scope-3-focused procurement and supply-chain managers, and compliance officers at entities regulated under EU ETS or CSRD.

---

## Project Status

> This project is in the **research and specification phase**.  
> Contributions, feedback, and domain expertise are welcome.

---

## Contributing

We welcome contributions from developers, domain experts, and potential users.
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Important:** All contributions must be your own original work or clearly attributed
open-source material with a compatible licence. Copyright infringement and licence
violations will not be tolerated and will result in immediate removal of the offending
contribution. If you are unsure whether a piece of code, text, or other material is
safe to contribute, open an issue and ask before submitting.

---

## Licence

Licence to be determined. See [discussion](#) for context.
