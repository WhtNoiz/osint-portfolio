# [Investigation Title]

> **Investigation type:** [Technical OSINT / GEOINT / SOCMINT / CTI / Corporate Intelligence / etc.]
> **Date:** YYYY-MM-DD
> **Status:** Completed
> **Confidence:** [High / Moderate / Low]
> **Training context:** [Independent investigation / Bellingcat Challenge / OSINT Exercise / CTF / etc.]

---

## Executive Summary

Provide a concise summary of the investigation.

Explain:

* what was investigated;
* why it was investigated;
* the most important findings;
* the final assessment.

This section should allow a reader to understand the main result without reading the entire report.

---

## Intelligence Question

State the exact question the investigation attempts to answer.

> **Example:**
> What infrastructure can be associated with `example.com`, and is there evidence linking it to other domains?

### Sub-questions

Where useful:

1. What infrastructure currently hosts the domain?
2. What historical infrastructure can be identified?
3. Are other domains associated with the same infrastructure?
4. How strong are the identified relationships?

---

## Scope

### Included

Describe what the investigation covers.

* Publicly available information
* Relevant time period
* Infrastructure associated with the target
* Historical records where available

### Excluded

Describe what is intentionally outside the investigation.

* Non-public information
* Active interaction with the target
* Attempts to bypass authentication or access controls
* Claims that cannot be independently supported

### Investigation period

**From:** YYYY-MM-DD
**To:** YYYY-MM-DD

---

## Key Findings

1. **Finding 1:** Concise description of the most important finding.
2. **Finding 2:** Concise description.
3. **Finding 3:** Concise description.
4. **Finding 4:** Concise description, if necessary.

Key findings should describe what the investigation actually established and should not overstate the available evidence.

---

## Methodology

Describe the investigative approach.

### Collection

Explain how information was collected.

Examples:

* search-engine research;
* RDAP queries;
* DNS enumeration;
* Certificate Transparency searches;
* archived web pages;
* reverse image searches;
* satellite imagery;
* public company registries.

### Verification

Explain how important information was independently checked or corroborated.

### Correlation

Explain how relationships between different pieces of information were evaluated.

### Preservation

Where relevant, document how volatile sources were preserved or archived.

---

## Investigation

### 1. Initial Information

Describe the starting information.

Do not analyse it yet. State what was known when the investigation began.

---

### 2. [First Investigative Step]

Describe the information discovered.

Clearly distinguish evidence from interpretation.

**Evidence**

[Describe the observed information.]

**Source:** [S1]

If relevant:

![Description](assets/fig-01.png)

*Figure 1 — Description of what the image demonstrates.*

**Analysis**

Explain why the evidence matters and what can reasonably be inferred from it.

---

### 3. [Second Investigative Step]

**Evidence**

[Observed information.]

**Source:** [S2]

**Analysis**

[Interpretation.]

---

### 4. [Third Investigative Step]

Continue as required by the investigation.

---

## Timeline

Include this section when chronology matters.

| Date / Time | Event             | Source |
| ----------- | ----------------- | ------ |
| YYYY-MM-DD  | Event description | [S1]   |
| YYYY-MM-DD  | Event description | [S2]   |
| YYYY-MM-DD  | Event description | [S3]   |

---

## Analysis

Bring the separate findings together.

Explain:

* which pieces of evidence corroborate each other;
* which relationships are strong;
* which relationships are circumstantial;
* whether alternative explanations exist;
* what remains uncertain.

Avoid introducing important new evidence in this section. Evidence should already have been documented in the investigation.

---

## Assessment

### Primary assessment

State the final analytical judgment.

> The available evidence indicates that [...]

### Confidence

**Confidence level:** [High / Moderate / Low]

**Rationale:**
Explain why this confidence level was assigned.

For example:

* multiple independent sources corroborate the finding;
* only indirect evidence is available;
* historical records are incomplete;
* an important relationship could not be independently verified.

---

## Alternative Hypotheses

Where appropriate, describe plausible alternative explanations.

### Hypothesis A

[...]

### Hypothesis B

[...]

Explain what evidence supports or weakens each hypothesis.

---

## Limitations and Intelligence Gaps

Document what the investigation could **not** determine.

Examples:

* historical records were unavailable;
* ownership could not be independently verified;
* some sources require paid access;
* deleted material could not be recovered;
* available evidence establishes infrastructure correlation but not common ownership.

### Intelligence gaps

* [Gap 1]
* [Gap 2]
* [Gap 3]

### Further collection

Explain what additional publicly available information could help resolve those gaps.

---

## Tools Used

| Tool      | Purpose              |
| --------- | -------------------- |
| Tool name | What it was used for |
| Tool name | What it was used for |
| Tool name | What it was used for |

Tools should be listed because they were actually used, not simply because they are relevant to OSINT.

---

## Sources

### [S1] Source name

* **URL:** `https://...`
* **Type:** Primary / Secondary
* **Accessed:** YYYY-MM-DD
* **Archived:** [archive URL if applicable]
* **Used for:** Brief explanation

### [S2] Source name

* **URL:** `https://...`
* **Type:** Primary / Secondary
* **Accessed:** YYYY-MM-DD
* **Archived:** [archive URL if applicable]
* **Used for:** Brief explanation

### [S3] Source name

[...]

---

## Conclusion

Briefly answer the original intelligence question.

State:

1. what was established;
2. what is probable but not established;
3. what remains unknown.

Do not introduce new evidence here.

---

## Disclaimer

This investigation was conducted using publicly available information for educational and portfolio purposes.

Findings reflect the information available at the time of the investigation. Analytical assessments represent interpretations of the documented evidence and should not be treated as established facts beyond what the underlying sources support.
