# Research Question

## Main research question

In professional tennis, how do tactical shot choices - serve placement,
shot direction relative to the incoming ball, court depth, and net approach -
affect the conditional probability of winning a point, and how does this
risk-reward relationship vary with rally phase, surface, gender, and
score pressure?

## Sub-questions

**SQ1 (descriptive).** How are point outcomes distributed across tactical
choices, and are the observed differences statistically significant after
correcting for multiple comparisons?

**SQ2 (predictive).** Can shot outcome class be predicted from pre-shot
tactical context, and by how much does this improve over a majority-class
baseline?

**SQ3 (explanatory).** Which tactical features drive the model's risk
estimates, as measured by Shapley values?

**SQ4 (contextual).** Does the risk-reward relationship change on
high-leverage points (break point, game point)?

**SQ5 (process).** Can a rally be modelled as an absorbing Markov chain,
and what do expected rally length and absorption probabilities reveal
about tactical positions?

## Note on data

The MCP points files contain no ready-made outcome columns. All outcome and
shot-level information is parsed from the notation strings (see notebook 02).
The parser reconstructs the point winner with 97.71% agreement against the
independent PtWinner column, which serves as external validation.
