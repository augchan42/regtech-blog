# Multi-Jurisdictional Compliance

*When US law and EU law disagree, and other fun regulatory conflicts*

---

Operating in multiple jurisdictions means navigating a maze of overlapping, conflicting, and sometimes contradictory rules. A practice that's required in Singapore might be prohibited in the UK. A disclosure that's mandatory in the US might violate GDPR in the EU.

This post explains how multi-jurisdictional compliance works, where conflicts arise, and how companies manage them.

---

## The Major Regulatory Frameworks

### United States: A Patchwork

The US has no single federal regulator for crypto. Instead, authority is fragmented:

| Agency | Jurisdiction |
|--------|-------------|
| SEC | Securities (including some crypto tokens) |
| CFTC | Commodities (including Bitcoin, Ethereum as commodities) |
| FinCEN | Money services businesses, AML |
| OFAC | Sanctions |
| FDIC / OCC / Federal Reserve | Banks involved in crypto |
| State regulators | Money transmitter licenses, securities registration |

The March 2026 SEC/CFTC joint interpretive release attempted to clarify these boundaries — designating categories of crypto assets as non-securities — but the US framework remains more fragmented than most jurisdictions.[^1]

*Source: SEC/CFTC Joint Release, March 2026[^1]*

### European Union: The MiCA Framework

The EU's Markets in Crypto-Assets Regulation (MiCA) created a single, passportable framework across all 27 member states.

Key features:
- **Single license** grants access to the entire EU market
- **ESMA** (European Securities and Markets Authority) provides supervisory convergence
- **National competent authorities** (NCAs) handle day-to-day supervision[^2]

The July 1, 2026 deadline for full MiCA compliance is approaching — all crypto-asset service providers (CASPs) must be authorized or exit the EU market.[^2]

*Source: Sumsub, "MiCA Regulation and EU Crypto Rules" (2026)[^2]*

### United Kingdom: Phased FCA Regime

The UK is building its own framework under the Financial Services and Markets Act (FSMA), with the FCA as regulator.

Key features:
- **Authorization gateway opens September 2026**
- **Full implementation: October 2027**
- **Separate from EU MiCA** — no passporting between UK and EU[^3]

*Source: Morgan Lewis, "UK and EU Crypto Regimes: The Road Ahead in 2026" (2026)[^3]*

### Singapore: PSA Framework

Singapore's Payment Services Act (PSA) requires licenses for digital payment token (DPT) services.

Key features:
- **Major Payment Institution (MPI)** license for larger operators
- **Standard Payment Institution (SPI)** for smaller operators
- **DTSP regime extended globally** — Singapore-incorporated firms serving overseas customers must also be licensed[^4]

*Source: Cryptonewsbytes, "Singapore Crypto Regulation 2026" (2026)[^4]*

---

## Where Conflicts Arise

### 1. Definition Conflicts

What counts as a security? A commodity? A utility token?

- **US (SEC, 2026):** Most tokens are NOT securities. Only tokens with profit-sharing, governance rights, or investment contract characteristics are securities.[^1]
- **EU (MiCA):** Different classification framework for asset-referenced tokens, e-money tokens, and utility tokens
- **UK (FCA):** Closely follows EU approach, but with UK-specific definitions

A token that clears the US securities test might still be regulated as a security in the EU or UK.

### 2. Stablecoin Conflicts

The most acute conflict area.

**US (GENIUS Act):**
- 100% reserve backing required
- Monthly attestations from accounting firms
- No algorithmic stablecoins[^5]

**EU (MiCA):**
- Strict reserve requirements
- Redemption rights within 5 business days
- Restrictions on stablecoin marketing and use[^2]

**UK (FCA):**
- Stablecoins under payment and systemic frameworks
- Different reserve requirements under development[^3]

### 3. AML Conflicts

**EU (AMLA):**

The new Anti-Money Laundering Authority (AMLA) begins direct supervision in 2028, collecting data from March 2026 onward. CASPs are in scope.[^6]

**US (FinCEN):**

Current AML requirements, with the Corporate Transparency Act (CTA) in flux due to ongoing legal challenges.[^7]

**Conflict:** The EU requires detailed beneficial ownership reporting; the US CTA requires similar reporting, but enforcement has been inconsistent and legally contested.

*Source: KYC-Chain, "The Great Compliance Divergence: Surviving the US-EU Regulatory Split in 2026" (2026)[^7]*

### 4. Data Privacy Conflicts

**GDPR (EU) vs. US Requirements:**

The EU's General Data Protection Regulation requires:
- Right to erasure (data deletion on request)
- Data minimization
- Purpose limitation

Blockchain/crypto systems often:
- Store data permanently on-chain
- Cannot modify or delete transaction records
- Make data publicly accessible

The European Data Protection Board (EDPB) issued guidance in April 2025 recommending off-chain storage of personal data — creating technical and operational challenges for crypto companies.[^8]

*Source: Chainlink, "Blockchain GDPR Compliance and Institutional Standards" (2026)[^8]*

---

## How Companies Manage Multi-Jurisdictional Compliance

### 1. Legal Entity Structuring

Companies often create separate legal entities for different jurisdictions:
- US entity for US operations
- EU entity for EU operations (often incorporated in a single EU jurisdiction for passporting)
- Singapore entity for MAS-regulated activities

This limits regulatory exposure — problems in one jurisdiction don't automatically flow to others.

### 2. Jurisdictional Risk Assessment

Compliance teams conduct jurisdiction-specific risk assessments to identify:
- Which rules apply to which activities
- Where conflicts exist
- What compliance gaps need to be filled

### 3. Technology Architecture

Many companies build **modular compliance systems** that can be configured for different jurisdictions:
- Transaction monitoring rules that adjust based on jurisdiction
- KYC requirements that meet the highest standard
- Data storage that satisfies GDPR while supporting other requirements

### 4. Regulatory Dialogue

Large companies maintain active relationships with regulators in key jurisdictions:
- Pre-application meetings with FCA before authorization
- Ongoing dialogue with FinCEN and SEC on novel questions
- Industry associations that aggregate and represent views

---

## The UK-US Divergence Case Study

In March 2026, Reuters reported that UK and US regulators are **split** on how to test blockchain-based tokenized securities:

> "The split shows how financial regulators globally have to contend with a pro-crypto U.S. under President Donald Trump. The U.S. has eased crypto regulation and encouraged cryptocurrency adoption. Britain also wants to expand its digital assets industry, but some UK regulators, such as the Bank of England, are cautious about moving too quickly."[^9]

**Key disagreement:** The UK wants a more cautious approach to testing joint work on tokenized securities, while the US has moved more aggressively toward allowing experimentation.

*Source: Reuters, "US and Britain split over crypto collaboration" (March 2026)[^9]*

---

## Practical Tips

### 1. Start with the Highest Standard

If you're building compliance for multiple jurisdictions, start with the most demanding framework and work down. It's easier to relax requirements than add them.

### 2. Build Modular Systems

Design compliance systems that can be configured for different jurisdictions. The rules will change — your systems need to adapt.

### 3. Monitor Regulatory Developments

Subscribe to:
- Agency enforcement announcements
- Industry association newsletters
- Legal alerts from firms covering your jurisdictions

### 4. Budget for Regulatory Counsel

Multi-jurisdictional compliance requires local expertise in each jurisdiction. This isn't optional — it's a cost of doing business globally.

---

## Key Takeaways

1. **No global standard exists** — each jurisdiction has its own framework
2. **Conflicts are common** — especially between US and EU approaches
3. **Entity structuring limits exposure** — separate entities for separate jurisdictions
4. **Technology must be flexible** — static compliance systems won't survive regulatory change
5. **Dialogue with regulators matters** — especially in new or ambiguous areas
6. **Monitor the UK's approach** — the FCA framework will be influential post-Brexit

---

## Sources

[^1]: SEC/CFTC, "Application of the Federal Securities Laws to Certain Types of Crypto Assets," Release No. 33-11412, March 17, 2026. https://www.sec.gov/rules-regulations/2026/03/s7-2026-09

[^2]: Sumsub, "MiCA Regulation and EU Crypto Rules: What Changes in 2026," January 13, 2026. https://sumsub.com/blog/crypto-regulations-in-the-european-union-markets-in-crypto-assets-mica/

[^3]: Morgan Lewis, "UK and EU Crypto Regimes: The Road Ahead in 2026," February 1, 2026. https://www.morganlewis.com/pubs/2026/02/uk-and-eu-crypto-regimes-the-road-ahead-in-2026

[^4]: Cryptonewsbytes, "Singapore Crypto Regulation 2026: MAS Licensing and PSA Framework," March 16, 2026. https://cryptonewsbytes.com/singapore-crypto-regulation-mas-payment-services-act-2026/

[^5]: Latham & Watkins, "The GENIUS Act of 2025 Stablecoin Legislation Adopted in the US," July 24, 2025. https://www.lw.com/en/insights/the-genius-act-of-2025-stablecoin-legislation-adopted-in-the-us

[^6]: PwC Legal, "From action to acceleration — AMLA's Single Programming Document for 2026-2028," March 3, 2026. https://www.lexology.com/library/detail.aspx?g=1c5fc446-04db-4536-8a2c-5501f9303e03

[^7]: KYC-Chain, "The Great Compliance Divergence: Surviving the US-EU Regulatory Split in 2026," January 19, 2026. https://kyc-chain.com/us-eu-compliance-split-2026/

[^8]: Chainlink, "Blockchain GDPR Compliance and Institutional Standards," February 5, 2026. https://chain.link/article/blockchain-gdpr-compliance-guide

[^9]: Reuters, "US and Britain split over crypto collaboration," March 4, 2026. https://www.reuters.com/sustainability/boards-policy-regulation/us-britain-split-over-crypto-collaboration-sources-say-2026-03-04/

---

*Next in this series: "What 'Substantially Implemented' Means"*
