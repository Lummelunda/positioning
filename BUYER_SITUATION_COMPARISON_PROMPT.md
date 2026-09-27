# Buyer-situation positioning comparison prompt

## Purpose

Use this after separate website positioning analyses and quality assessments. Compare two or more offers as a buyer might encounter them in **one defined decision**, rather than comparing company-level scores. The result is a sourced map of overlap, difference, evidence and unknowns. It is not a procurement recommendation or proof of technical performance.

## Reusable prompt

> Compare [company/offer A] and [company/offer B] for this buyer situation: [specific operational or enabling need, environment, buyer collective, and known constraints]. If the actual buyer situation is unknown, state a plausible illustrative scenario, label it as an analyst assumption, and do not imply it is a live requirement.
>
> **Inputs:** [links to positioning analyses and quality assessments]; [current public websites or supplied text]; [optional actual requirement, buyer interviews, evaluation results and criteria].
>
> 1. **Define the decision.** State the task, operating context, outcome sought, constraints, buyer roles and the part of the stack being bought. Say whether the suppliers are likely substitutes, complements, or both depending on scope. If there are two distinct decisions, analyse them separately.
> 2. **Set the comparable offers.** Identify the exact product, application, service and hardware included for each supplier. Do not transfer a claim or maturity level from one product to another. Explain any material difference in delivery boundary.
> 3. **Compare against the same questions.** Cover mission or technical function; model/data operations; operation through connection changes; integration and hardware; delivery and responsibility; maturity/availability; and evidence relevant to the decision. Add requirements specific to the scenario. For each row, say what A states, what B states, the practical buyer implication, and what is unknown. Cite direct source pages.
> 4. **Handle evidence consistently.** Label marketing claims, demonstrations, customer testimonials, field trials, operational deployments, measured outcomes and independent validation separately. Do not infer one from another. Record when public evidence is not comparable.
> 5. **Synthesize the positioning.** Explain where both would enter the same shortlist, where one addresses a different layer or buying route, and what each company's website makes easiest or hardest for the buyer to understand. Distinguish communicated position from actual superiority.
> 6. **Close with validation questions.** List the smallest set of buyer, technical and commercial questions needed for a fair evaluation. Do not declare a winner unless a real requirement, weighted criteria and comparable evidence are provided.
>
> **Output:** Scope and source coverage; short decision statement; one table per distinct decision; evidence and maturity note; short positioning synthesis; validation questions. Use explicit / inferred / unknown where a distinction matters. A quality-assessment rating may inform the analysis but is never a numerical company score. Avoid recommending claims the sources cannot support.

## How to use it

The comparison should answer **“Which offer would a buyer think to consider for this job, and what would they need to verify?”** It does not answer **“Which company is better?”** without an actual requirement and evaluation evidence.

See the worked example: [Scaleout and Vizgard buyer-situation comparison](SCALEOUT_VIZGARD_BUYER_SITUATION_COMPARISON.md).
