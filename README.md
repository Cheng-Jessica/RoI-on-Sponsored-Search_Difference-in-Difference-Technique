## "Difference in Difference" - Bazaar.com

### Technique: R, Difference in Difference
### The ultimate goal is to report an accurate estimate of the Return on Investment associated with Sponsored Search advertising being run by Bazaar.com, based on the natural experiment. You should address the following set of questions as part of your report:

- (a) What is Wrong with Bob’s RoI Calculation? Explain in words what is problematic with Bob’s approach to calculating the RoI associated with sponsored search ads? Hint: think about what visitors might do instead, in the absence of sponsored ads from Bazaar.com when they run a Google search.
- (b) Define the Treatment and Control. What is the unit of observation here? Define the treatment. Which unit(s) are treated and which is / are control?
- (c) Consider a First Difference Estimate. One approach we might take (if we could only observe the treated unit) would be to calculate the first difference (that is, the % change in web traffic arriving from Google; (after – before) / before). This estimate is the pre-post difference in the treated cohort. Estimate this value using a regression (what is the estimated treatment effect from this simple post estimator?). Explain why it would not be a good idea to solely rely on this number as our estimate of the causal effect of the treatment.


Frequently, conducting a randomized experiment is not feasible. This might be because there is no reliable way to “target” units of observation with a treatment, or it may be that an experimental intervention is not legal,ethical or cost effective. In these situations, one must adapt, bringing to bear alternative techniques that can help to establish causality in non-experimental data.

One technique, which is simple, yet powerful, is known as Difference-in-Differences (DD) regression. DD regression is applicable when you are presented with a setting in which multiple units of study are observed
over time, and a subset of units is treated midway through the panel. Given this setup, we can recover a reliable estimate of the causal effect of the treatment, given some assumptions (e.g., that treatment is assigned in a
plausibly exogenous manner, such that treatment is not confounded with other changes experienced by the treated units around the same point in time). Using this method, we might, for example, estimate the causal
effect of an operating policy change within a company if said policy was instituted (or removed) at some office locations, but not at others. This would be achieved by comparing outcomes of interest associated with each
location, before vs. after the change. The “others” ultimately serve as a control group (similar to an experiment); they enable us to recover a plausible counterfactual for what would have happened in the treated location had
treatment never happened.
