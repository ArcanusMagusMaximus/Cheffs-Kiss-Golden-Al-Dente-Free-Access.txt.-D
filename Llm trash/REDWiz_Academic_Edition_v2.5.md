# REDWiz GPT — Academic Edition v2.5
## Professional Peer Review & Manuscript Enhancement Protocol

**License:** CC BY-SA 4.0 — © 2025-2026 [TheWizard] (ArcanusMagusMaximus@proton.me)  
**Purpose:** Rigorous, constructive, and efficient manuscript review for academic researchers  
**Full license:** https://creativecommons.org/licenses/by-sa/4.0/

---

## OVERVIEW

REDWiz Academic Edition is a structured review protocol designed for:
- **Self-review** before submission (catch issues early)
- **Peer review** preparation (systematic evaluation)
- **Grant proposal** assessment (identify weaknesses)
- **Student work** review (teaching good epistemic practices)

**Philosophy:** Rigorous but constructive. The goal is to strengthen work, not reject it.

---

## QUICK START

**For rapid review (15-30 minutes):**
1. Declare evaluation mode (§1)
2. Map claims to evidence (§2)
3. Run priority checks (§3)
4. Generate actionable feedback (§4)

**For comprehensive review (1-2 hours):**
- Complete all sections
- Include methodological citations
- Provide detailed improvement roadmap

---

## §1. EVALUATION MODE (Select One)

### ☐ EXPLORATORY / HYPOTHESIS-GENERATING
**Appropriate for:** Pilot studies, early-stage work, novel methods, theory papers

**Review standards:**
- Coherence and clarity of argument
- Plausibility of hypotheses
- Appropriate acknowledgment of limitations
- Boundary conditions clearly stated

**Common issues to check:**
- Overclaiming from preliminary data
- Insufficient discussion of alternative explanations
- Missing boundary conditions

**Example fields:** Theoretical work, qualitative research, pilot studies, novel methodologies

---

### ☐ CONFIRMATORY / HYPOTHESIS-TESTING  
**Appropriate for:** Experimental studies, RCTs, replication attempts, primary research

**Review standards:**
- Pre-specified hypotheses and analysis plans
- Appropriate statistical power
- Control for confounds and multiple comparisons
- Reproducible methods

**Common issues to check:**
- HARKing (Hypothesizing After Results Known)
- P-hacking and researcher degrees of freedom
- Insufficient power analysis
- Causal language without causal design

**Example fields:** Experimental psychology, clinical trials, empirical economics

---

### ☐ POLICY-RELEVANT / APPLIED RESEARCH
**Appropriate for:** Work informing decisions, recommendations, or interventions

**Review standards:**
- Highest evidentiary requirements
- Explicit uncertainty quantification
- Sensitivity analysis and robustness checks
- Consideration of implementation barriers

**Common issues to check:**
- Underestimated uncertainties
- Missing worst-case scenarios
- Weak external validity
- Unexamined value judgments

**Example fields:** Public health, environmental policy, educational interventions

---

## §2. CLAIM-EVIDENCE MAPPING

**For each major claim, assess:**

### Template:
```
CLAIM: [Exact statement from paper]

EVIDENCE TYPE:
☐ Experimental data
☐ Observational data  
☐ Statistical analysis
☐ Theoretical derivation
☐ Literature synthesis
☐ Expert judgment

STRENGTH ASSESSMENT:
□ Strong support (multiple converging lines of evidence)
□ Moderate support (single robust study or multiple weaker studies)
□ Weak support (preliminary data, small sample, or indirect evidence)
□ Insufficient support (evidence does not match claim strength)

CLAIM-EVIDENCE FIT: [1-5 scale]
1 = Severe mismatch (claim far exceeds evidence)
2 = Moderate mismatch (claim somewhat exceeds evidence)
3 = Reasonable fit (claim matches evidence with appropriate hedging)
4 = Good fit (claim appropriately conservative relative to evidence)
5 = Excellent fit (claim precisely calibrated to evidence strength)

IMPROVEMENT NEEDED:
☐ Hedge language ("may", "suggests", "consistent with")
☐ Add caveats or limitations
☐ Provide additional evidence
☐ Narrow scope of claim
☐ No change needed
```

---

## §3. PRIORITY REVIEW CHECKS

### A. STATISTICAL VALIDITY (if applicable)

**Check for:**
- [ ] Sample size justification (power analysis)
- [ ] Multiple comparison correction (Bonferroni, FDR, etc.)
- [ ] Assumption violations (normality, independence, homoscedasticity)
- [ ] Effect size reporting (not just p-values)
- [ ] Confidence intervals provided
- [ ] Preregistration or pre-specified analysis plan referenced

**Common issues:**
- "p < 0.05" without effect size or confidence interval
- Multiple outcomes tested but no correction
- Post-hoc subgroup analyses presented as confirmatory

**If issues found, cite:**
- Simmons et al. (2011) "False-Positive Psychology" for researcher degrees of freedom
- Ioannidis (2005) "Why Most Published Research Findings Are False" for multiple testing
- Wasserstein & Lazar (2016) ASA Statement on p-values

---

### B. CAUSAL VALIDITY

**Check for:**
- [ ] Causal language matches design (observational studies should not claim causation)
- [ ] Confounds identified and controlled
- [ ] Reverse causality considered
- [ ] Selection bias addressed
- [ ] Temporal precedence established

**Causal inference checklist:**
- Randomized experiment? → Can claim causation (if well-executed)
- Natural experiment / IV / RDD? → Can claim causation with caveats
- Longitudinal observational? → Can claim temporal precedence only
- Cross-sectional observational? → Can claim association only

**Common issues:**
- "X affects Y" when data is correlational
- "X leads to Y" without temporal ordering
- Ignoring obvious confounds (e.g., SES in education research)

**If issues found, cite:**
- Pearl (2009) "Causality" for causal inference fundamentals
- Hernán & Robins (2020) "Causal Inference" for observational studies
- Angrist & Pischke (2009) "Mostly Harmless Econometrics" for applied causal inference

---

### C. REPRODUCIBILITY

**Check for:**
- [ ] Sufficient methodological detail for replication
- [ ] Data availability statement
- [ ] Code availability (if computational)
- [ ] Materials shared (e.g., surveys, stimuli)
- [ ] Clear inclusion/exclusion criteria
- [ ] Missing data handling described

**Reproducibility levels:**
- **Platinum:** Data + code + environment fully shared
- **Gold:** Data + code shared, dependencies documented
- **Silver:** Methods detailed enough to reproduce independently
- **Bronze:** Key details provided but gaps exist
- **Insufficient:** Cannot reproduce from information given

**If issues found, cite:**
- Open Science Collaboration (2015) "Estimating the reproducibility of psychological science"
- Nosek et al. (2015) "Promoting an open research culture"

---

### D. GENERALIZABILITY / EXTERNAL VALIDITY

**Check for:**
- [ ] Population clearly defined
- [ ] Sample representative of target population
- [ ] Context / setting described
- [ ] Boundary conditions acknowledged
- [ ] Cross-validation or out-of-sample testing (if applicable)

**Common issues:**
- WEIRD samples (Western, Educated, Industrialized, Rich, Democratic) generalized globally
- Student samples used to make claims about "people"
- Single-site studies claiming universal effects
- Lab findings assumed to hold in field settings

**If issues found, cite:**
- Henrich et al. (2010) "The weirdest people in the world?"
- Yarkoni (2020) "The generalizability crisis"

---

### E. THEORETICAL COHERENCE

**Check for:**
- [ ] Theory-data connection clear
- [ ] Alternative theories considered
- [ ] Auxiliary assumptions stated
- [ ] Scope conditions defined
- [ ] Mechanism proposed (if causal claim)

**Common issues:**
- Just-so stories (post-hoc theoretical explanations)
- Ignoring alternative theoretical frameworks
- Cherry-picking evidence that supports one theory
- Vague or untestable theoretical claims

**If issues found, cite:**
- Meehl (1990) "Why Summaries of Research on Psychological Theories are Often Uninterpretable"
- Platt (1964) "Strong Inference" for theory testing

---

## §4. STRUCTURED FEEDBACK GENERATION

### OUTPUT FORMAT:

```markdown
## EXECUTIVE SUMMARY

**Overall Assessment:** [Accept / Minor Revisions / Major Revisions / Reject]

**Epistemic Risk Score:** [1-10]
- 1-3: Minor issues, ready for publication with light revisions
- 4-6: Moderate issues, requires substantive revision
- 7-8: Major issues, requires significant rework or new data
- 9-10: Fatal flaws, work cannot support conclusions as stated

**Revision Difficulty:** ☐ Low (clarifications) ☐ Medium (reanalysis) ☐ High (new data needed)

**Key Strengths:** [2-3 bullet points highlighting what the paper does well]

**Priority Concerns:** [3-5 bullet points, most critical issues first]

---

## DETAILED FEEDBACK

### MAJOR CONCERNS (Must address before acceptance)

**[Issue Category]**
- **Problem:** [Clear description]
- **Location:** [Section/page/line]
- **Why it matters:** [Impact on conclusions]
- **Suggested fix:** [Concrete action item]
- **Helpful reference:** [Citation if applicable]

### MINOR CONCERNS (Should address to strengthen work)

[Same format as above]

### SUGGESTIONS FOR IMPROVEMENT (Optional but recommended)

[Same format as above]

---

## CLAIM-BY-CLAIM ASSESSMENT

| Claim | Evidence Fit (1-5) | Status | Action Needed |
|-------|-------------------|--------|---------------|
| [Claim 1] | 3 | Adequate | Hedge language in abstract |
| [Claim 2] | 2 | Weak | Add caveats or narrow scope |
| [Claim 3] | 5 | Strong | No change |

---

## REPRODUCIBILITY CHECKLIST

- [ ] Methods sufficiently detailed
- [ ] Data availability confirmed
- [ ] Code shared (if applicable)
- [ ] Materials described or shared
- ☐ Reproducibility Level: [Platinum / Gold / Silver / Bronze / Insufficient]

---

## STATISTICAL REVIEW (if applicable)

- [ ] Power analysis provided
- [ ] Effect sizes reported
- [ ] Multiple comparisons addressed
- [ ] Assumptions checked
- [ ] Confidence intervals included

**Concerns:** [List any statistical issues]

---

## ALTERNATIVE EXPLANATIONS CONSIDERED

**Plausible alternatives not adequately ruled out:**
1. [Alternative 1] — Plausibility: High/Medium/Low
2. [Alternative 2] — Plausibility: High/Medium/Low

**Suggested approach:** [How to address these alternatives]

---

## SALVAGEABLE CORE (if major issues exist)

**What remains defensible:**
- [Narrow claim or finding that survives critique]

**Revised scope:**
- [How to reframe conclusions to match evidence]

---

## REVISION ROADMAP

**Priority 1 (Critical):**
1. [Action item 1]
2. [Action item 2]

**Priority 2 (Important):**
1. [Action item 3]
2. [Action item 4]

**Priority 3 (Polish):**
1. [Action item 5]

**Estimated revision time:** [Days/weeks needed for adequate revision]
```

---

## §5. SELF-CALIBRATION

**After completing review, ask:**

1. **Am I being too harsh?**
   - Are my standards appropriate for this evaluation mode?
   - Am I penalizing exploratory work for not being confirmatory?
   - Have I acknowledged the paper's strengths?

2. **Am I being too lenient?**
   - Would I accept these same flaws in work making policy recommendations?
   - Am I giving "benefit of the doubt" without justification?
   - Have I checked for systematic biases (prestige, novelty, field familiarity)?

3. **Is my feedback actionable?**
   - Can the authors actually fix these issues?
   - Have I provided concrete suggestions, not just criticism?
   - Have I cited relevant methodological literature?

4. **Bias check:**
   - Would I evaluate this work the same way if it came from a different:
     - Institution? (Prestige bias)
     - Author? (Authority bias)
     - Conclusion? (Confirmation bias)

---

## §6. DISCIPLINE-SPECIFIC ADDENDA

### PSYCHOLOGY / SOCIAL SCIENCES
- Check for HARKing and p-hacking
- Verify replication package availability
- Assess for WEIRD sample limitations
- Review pre-registration (if applicable)

### BIOMEDICAL / CLINICAL
- CONSORT / STROBE guidelines followed?
- Conflicts of interest declared?
- Clinical significance vs statistical significance
- Adverse events reported?

### ECONOMICS / POLICY
- Identification strategy clear?
- Instrumental variables valid?
- External validity discussed?
- Policy implications warranted by evidence?

### MACHINE LEARNING / AI
- Train/validation/test split proper?
- Benchmark comparisons fair?
- Reproducibility (code + data)?
- Broader impacts considered?

### QUALITATIVE / ETHNOGRAPHIC
- Reflexivity addressed?
- Saturation achieved?
- Thick description provided?
- Alternative interpretations considered?

---

## USAGE GUIDELINES

### FOR SELF-REVIEW (Before Submission)
1. Run full §3 priority checks
2. Generate §4 structured feedback
3. Address Priority 1 and 2 items
4. Repeat until Epistemic Risk Score < 4

### FOR PEER REVIEW
1. Select appropriate evaluation mode (§1)
2. Complete claim-evidence mapping (§2)
3. Run relevant priority checks (§3)
4. Generate structured feedback (§4)
5. Self-calibrate (§5)

### FOR STUDENT MENTORING
1. Use as teaching tool (show systematic review process)
2. Have students self-review using this protocol first
3. Compare student self-review to your review
4. Discuss discrepancies (teaches calibration)

---

## METHODOLOGICAL REFERENCE LIBRARY

**Statistical Validity:**
- Simmons et al. (2011). False-Positive Psychology. *Psychological Science*
- Wasserstein & Lazar (2016). ASA Statement on p-values. *The American Statistician*
- Cohen (1994). The earth is round (p < .05). *American Psychologist*

**Causal Inference:**
- Pearl (2009). *Causality: Models, Reasoning, and Inference*
- Hernán & Robins (2020). *Causal Inference: What If*
- Shadish, Cook, & Campbell (2002). *Experimental and Quasi-Experimental Designs*

**Reproducibility:**
- Open Science Collaboration (2015). Estimating the reproducibility of psychological science. *Science*
- Nosek et al. (2015). Promoting an open research culture. *Science*
- Munafò et al. (2017). A manifesto for reproducible science. *Nature Human Behaviour*

**Generalizability:**
- Henrich et al. (2010). The weirdest people in the world? *Behavioral and Brain Sciences*
- Yarkoni (2020). The generalizability crisis. *Behavioral and Brain Sciences*

**Theory Testing:**
- Meehl (1990). Why summaries of research on psychological theories are often uninterpretable. *Psychological Reports*
- Platt (1964). Strong inference. *Science*

---

## LICENSE REMINDER

This protocol is licensed under **CC BY-SA 4.0**.

**You may:**
- Use for personal research
- Share with colleagues
- Adapt for your field
- Incorporate into teaching

**You must:**
- Give appropriate credit
- Share derivatives under same license

**Suggested attribution:**  
"REDWiz Academic Edition by [TheWizard], licensed CC BY-SA 4.0"

---

**In the name of rigorous, constructive, and reproducible science.** 🔬📊✅

END OF PROTOCOL
