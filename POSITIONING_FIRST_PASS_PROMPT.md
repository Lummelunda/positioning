# Website positioning analysis: extraction and synthesis

## Purpose

Use this prompt in one run to analyse the **positioning communicated by supplied text or a company's public website**. It produces a sourced extraction, a short analyst synthesis and unresolved questions. It does not establish how buyers actually perceive the company, independently verify product claims, judge whether the position is effective, or compare it with Scaleout. The buyer-facing assessment can be done separately.

The dimensions combine April Dunford's competitive alternatives, differentiated capabilities, customer value, target customers and market category with Kellogg's target audience, frame of reference, point of difference and reason to believe. Buyer situation, offer boundary and system role make the extraction useful for complex B2B and defence offers.

## Reusable prompt

> Analyse the positioning communicated by the material I provide below. Treat the material as evidence of the company's **publicly communicated position**, not proof of actual capability, commercial maturity, buyer perception or market success.
>
> **Input:** [Paste text or provide website URL here. Optionally name a particular product or offer to focus on.]
>
> If given a URL, review the homepage and the pages needed to understand the offer: relevant product/platform, application or use-case, deployment/integration, evidence/case-study, and commercial or engagement pages. Record the pages reviewed. Do not assume that a logo, partnership, demonstration, trial, customer quote, or operational deployment means the same thing. If browsing is incomplete or a page is inaccessible, state the limitation. If given pasted text, use only that text and refer to its headings or passages.
>
> **Extraction rules**
>
> - Separate **explicit statements**, **reasonable inferences**, and **not stated / unclear**. Never present an inference as a company claim.
> - Cite a specific page URL or text passage for every substantive finding. Prefer short paraphrases; quote only where exact wording matters.
> - Do not fill gaps from general market knowledge or from what similar companies offer.
> - If the company has several offers or audiences, identify the company-level position and the distinct positions of the relevant offers. Do not collapse them into one artificial statement.
> - Preserve the company's own terminology, then explain it in plain language where needed. Flag terms used inconsistently.
>
> **Extract these positioning dimensions**
>
> 1. **Target customer and buyer collective:** Which organisations, segments, roles, users or partners are named or clearly addressed? Distinguish the buyer, technical evaluator, operator, integrator and route to market where the material does.
> 2. **Buying situation and need:** What event, problem, requirement or desired outcome makes the offer relevant? When should the buyer consider it?
> 3. **Market category and frame of reference:** What does the company call the offer? In what category or stack layer does it ask the buyer to place it? What expectations would that frame create?
> 4. **Alternatives:** Which competing approaches, incumbent systems or status-quo workflows are named or implied? If none are identifiable, say so. Do not invent named competitors.
> 5. **Offer and system role:** What exactly is supplied: software platform, application, hardware, service, integration, or a combination? What does the customer or partner supply? Where does the offer fit into the wider system, and what are its stated boundaries?
> 6. **Distinctive capabilities:** Which capabilities does the company present as different or especially important relative to the stated alternatives? Distinguish a claimed differentiator from a capability that may be common in the market.
> 7. **Buyer value:** What operational, technical, financial or risk-related benefit is claimed, for whom, and through which capability? Capture the causal link rather than listing benefits alone.
> 8. **Reason to believe:** What supports the claims: product detail, technical documentation, measured results, demonstrations, trials, customer accounts, deployments, certifications, or third-party validation? Record the type and limits of each item. Do not equate a claim of maturity with independent verification.
> 9. **Scope and maturity:** Which uses are described as available, deployed, being evaluated, planned or experimental? Note relevant licensing, delivery or procurement information if publicly stated.
>
> **Output**
>
> A. **Source coverage:** Pages or passages reviewed and any material gaps in coverage.
>
> B. **Positioning extraction table:** One row per dimension above, with columns for finding, status (**explicit / inferred / unclear**), source, and ambiguity or qualification. Use multiple rows when offers or audiences differ.
>
> C. **Positioning synthesis:** In 2–4 sentences, describe the position the material appears to communicate. Label this as an analyst synthesis. If several distinct offers exist, provide a brief synthesis for each instead of forcing one statement.
>
> D. **Unresolved questions:** List the few questions that would most change the positioning interpretation. Do not answer them speculatively.
>
> Keep this analysis descriptive. Do not run a buyer-facing quality assessment, recommend website changes or compare the company with another unless I explicitly request it.

## Sources behind the dimensions

- April Dunford, [An Introduction to Positioning](https://www.aprildunford.com/post/an-introduction-to-positioning).
- Kellogg School of Management, [Why Does Your Brand Need to Exist?](https://insight.kellogg.northwestern.edu/article/podcast-insight-unpacked-branding-episode-1).
- See also [What we mean by positioning](POSITIONING_DEFINITION.md).
