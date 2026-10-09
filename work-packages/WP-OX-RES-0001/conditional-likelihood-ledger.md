# Conditional Likelihood Ledger v0.1

WP-OX-RES-0001 | 2026-10-08
Status: qualitative hypothesis audit, not measured frequencies or numerical Bayes factors.

## Definitions

R = bodily resurrection and subsequent appearances. V = individual visions or revelations. S = socially mediated experiences and interpretation. L = legendary expansion. F = deliberate fabrication. M = mistaken identity/survival (specify submodel before scoring). C = composite naturalistic explanation.

Evidence is the **surviving record** rather than the alleged events themselves. In particular, an early report that 500 saw Jesus is evidence of that report, not 500 independent depositions.

Notation: **P** plausible/expected given a sufficiently specified model; **U** underdetermined without additional assumptions; **T** tension requiring additional explanation; **X** not applicable to a mechanism without auxiliary claims. These are diagnostic judgments, **not** probabilities or an ordinal ranking.

| Observed record | R | V | S | L | F | M | C |
|---|---|---|---|---|---|---|---|
| E1: early Christian testimony that Jesus was crucified, with later Roman corroboration | P | P | P | P | P | T (survival version) / P (misidentification version) | P |
| E2: Paul personally claims an appearance | P | P | U | T (if legend alone) | U | U | P |
| E3: Paul preserves received list of named and grouped appearances | P | U | P | P | P | U | P |
| E4: early proclamation centers on resurrection | P | P | P | P | P | U | P |
| E5: later Gospel empty-tomb and appearance narratives survive | P | U | P | P | P | U | P |
| E6: Paul says he met Cephas and James; James is independently identified by Josephus | P | P | P | P | P | P | P |

**Interpretation:** Many models can accommodate the existence of *reports*. That observation is not evidence of equivalence of the models. Relative likelihoods depend on the mechanisms, expected reporting pathways, and dependencies. The prevalence of P values here must not be used as a tally or converted into Bayes factors.

## Conditional factorization

Let E1...E6 be observed records. For each H:
`P(E1,...,E6 | H) = P(E1 | H) P(E2 | E1,H) P(E3 | E1,E2,H) ... P(E6 | E1,...,E5,H)`.

Order is algebraically arbitrary; the conditional dependencies are not. A practical dependency model should represent shared traditions, authorial aims, textual copying, social transmission, and manuscript survival. A report from Matthew that overlaps Mark is not a new independent observation of the event simply because it occurs in another book.

## Discriminators that matter most

**D1. Early tradition provenance:** Is the 1 Corinthians 15 formula datable to a narrow early window? Which features can be assigned to the formula versus Paul's own framing? Record scholarly arguments and exact citations.

**D2. Appearance phenomenology:** What does Paul's language establish about his own encounter? Can the text distinguish physical, visionary, or other experience? Do not infer the phenomenology of Cephas/James/the Twelve from Paul's testimony alone.

**D3. Group claims:** How should the Twelve and 500 reports be modeled given no separately preserved depositions from each participant? Examine known group-perception mechanisms without presuming they apply.

**D4. Empty tomb:** Determine which elements are source-dependent, which have independent corroboration, and how each hypothesis predicts the *narrative*, separately from an actual empty tomb.

**D5. Paul and James:** Paul's pre-conversion opposition and James's relationship to Jesus are potentially discriminating, but specific psychological histories and motives cannot be invented.

**D6. Counterevidence:** Seek positive evidence of fabrication, mistaken identity, natural survival, and literary development; avoid explaining away evidence by merely naming a mechanism.

## Sensitivity design

Use four background frameworks: metaphysical naturalism, open methodological naturalism, broad theism, and Christian theism. Distinguish *prior odds* from *likelihood ratios*. A strictly zero prior for R cannot be updated and therefore measures a philosophical stipulation rather than a historical inference. No scenario gets invented numerical inputs.

The R hypothesis must specify what 'bodily resurrection' predicts about the surviving testimony, including whether it predicts any particular Gospel narrative detail. C must specify which component mechanisms apply to which strands and must pay a complexity penalty where components are introduced only after seeing the evidence. R also incurs a specification burden when auxiliary divine intentions are introduced after observing the record.

## Provisional assessment

The strongest currently documented historical claims are that Jesus was executed, that Paul claimed an experience of the risen Jesus, that he preserved a list of other reported appearances, and that early Christians proclaimed resurrection. The historical occurrence of an empty tomb, the nature of the appearances, and the causal claim of bodily resurrection require further argument. The matrix does not presently demonstrate that R has a higher likelihood or posterior probability than its rivals.

## Next increment

Verify page-specific primary scholarly arguments for D1–D5; create an explicit source-dependency DAG; test an adversarial pair of well-specified R and C hypotheses; then assess whether a bounded likelihood ratio is justifiable. No unsupported quantitative inference.
