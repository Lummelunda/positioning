# Positioning method

This folder contains a reusable method for reading the position communicated by a company website, assessing how useful that communication may be to buyers, and comparing offers in a defined buying situation. The method files below are **instructions and definitions**. Company analyses, quality assessments, comparisons and working offer notes elsewhere in the folder are **outputs**, not parts of the method. Find them in the [worked examples index](INDEX.md).

## Method files

| File | Use it for |
|---|---|
| [POSITIONING_DEFINITION.md](POSITIONING_DEFINITION.md) | The working definition of positioning, the inputs to a positioning statement, and a buyer-facing quality check. Read this first. |
| [POSITIONING_FIRST_PASS_PROMPT.md](POSITIONING_FIRST_PASS_PROMPT.md) | A descriptive first pass on a website or supplied text: sources, nine positioning dimensions, synthesis and open questions. |
| [POSITIONING_QUALITY_ASSESSMENT_PROMPT.md](POSITIONING_QUALITY_ASSESSMENT_PROMPT.md) | A separate qualitative assessment of how clearly and credibly that position helps relevant buyers recognise, understand, compare and trust the offer. |
| [BUYER_SITUATION_COMPARISON_PROMPT.md](BUYER_SITUATION_COMPARISON_PROMPT.md) | A comparison of two or more offers against the **same buyer decision**, including overlap, delivery boundaries, evidence and unresolved questions. |

## Recommended sequence

1. **Define the object of analysis.** Specify the company, website or supplied text, date, and any product or offer to focus on. Decide whether you are analysing the company-level position, a particular offer, or both.
2. **Run the first-pass prompt.** Give it the URL or text. For a website, review relevant platform/product, application, integration, evidence and engagement pages as well as the homepage. Save the output with direct source links. Keep explicit claims, analyst inferences and unknowns distinct.
3. **Run the quality-assessment prompt.** Use the completed first pass and its sources. Add known buyer roles and requirements if available. Assess the seven criteria qualitatively; do not turn the labels into an overall numerical score. Save this separately from the descriptive analysis.
4. **Compare only for a defined decision.** If comparing companies, use the comparison prompt with a real buyer requirement if possible. Otherwise label the buying situation illustrative. Compare the particular offers a buyer might shortlist, not entire companies or their assessment ratings. Recheck the source pages and maturity of each relevant offer.
5. **Validate before using findings as strategy.** Buyer interviews can test whether the assumed situation, alternatives and category match how buyers actually decide. Product teams can confirm delivery boundaries. Evaluation results can substantiate performance and outcome claims. Revise the positioning only after those questions are addressed sufficiently for the intended use.

## What each output can and cannot tell you

| Output | It can tell you | It cannot establish on its own |
|---|---|---|
| **First-pass analysis** | What the supplied material says and the position an analyst can reasonably infer. | Actual capability, commercial maturity, buyer perception or market success. |
| **Quality assessment** | Where the *communicated* position appears clear, weak or unsupported for relevant visitors. | A measured buyer response, product score or competitive win probability. |
| **Buyer-situation comparison** | Where specific offers overlap, differ and need further validation under one requirement. | An overall winner without weighted criteria and comparable evidence. |

A positioning statement is a **result of positioning decisions**, not a substitute for them. The [definition](POSITIONING_DEFINITION.md) lists the necessary inputs: buyer and situation, frame and alternatives, offer and role, distinctive value, and reason to believe.

## Reuse and file naming

Copy the reusable prompt text into a new analysis request, replace its bracketed input, and give the output a company-specific filename such as `COMPANY_POSITIONING_ANALYSIS.md`. Keep its quality assessment in a separate `COMPANY_POSITIONING_QUALITY_ASSESSMENT.md`. Name comparisons for both companies and the buyer situation where practical. Record the date and source coverage in every output, since websites change.

A working offer hypothesis, such as [Scaleout's two buyer entry points](SCALEOUT_OFFER_FRAMING_WORKING_NOTE.md), should stay visibly labelled as a hypothesis until its product and buyer assumptions are checked. It is an output of the discussion, not a reusable instruction.
