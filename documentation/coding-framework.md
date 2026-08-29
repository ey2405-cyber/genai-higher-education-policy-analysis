# Coding Framework

## Overview

Each GenAI policy document in the dataset was coded across six dimensions:

1. Stance
2. Disclosure
3. Discretion
4. Primary Focus
5. Enforcement
6. Coverage

The framework was designed to convert qualitative characteristics of GenAI policies into structured variables that could be compared across regions, institutions, and governance tiers.

**Stance** is the primary ordinal variable. The remaining dimensions are treated as nominal categorical variables.

---

## 1. Stance

**Guiding question:**  
What is the document's overall position on the use of Generative AI?

| Category | Numeric Code | Definition |
|---|---:|---|
| Prohibitive | 0 | GenAI use is viewed as a threat and is explicitly prohibited |
| Cautious | 1 | GenAI use is treated as a risk and is permitted only under specific conditions, permission, or strict rules |
| Functional | 2 | GenAI is accepted or recognized as a tool; the policy focuses primarily on how it may be used |
| Encouraging | 3 | GenAI use is actively promoted as beneficial to learning, teaching, or related activities |

**Scale:** Ordinal, 0–3

Stance was converted to a numeric variable for statistical analysis while preserving the order from most restrictive to most encouraging.

---

## 2. Disclosure

**Guiding question:**  
Does the document require users to acknowledge or declare their use of GenAI?

| Category | Description |
|---|---|
| Required | GenAI use must be cited, acknowledged, or declared |
| Recommended | Disclosure is encouraged but not universally required |
| Conditional | Disclosure requirements depend on the task, assignment, or specific circumstances |
| Not specified | The document contains no disclosure requirement |

**Scale:** Nominal

---

## 3. Discretion

**Guiding question:**  
Who holds the authority to establish rules around GenAI use?

| Category | Definition |
|---|---|
| Gov-mandated | Rules are issued by a government body external to the university |
| Institution-mandated | Rules are established by a university-wide authority such as a provost, senate, or registry |
| Faculty/Department decides | Rules are established by a school, faculty, department, or other academic sub-unit |
| Instructor decides | Individual instructors determine GenAI rules for their courses |
| Hybrid | An institution establishes baseline rules while explicitly allowing faculty or instructors to establish additional requirements |
| Not specified | The document provides guidance without clearly identifying rule-making authority |

**Scale:** Nominal

---

## 4. Primary Focus

**Guiding question:**  
What is the primary concern or goal driving the document's GenAI guidance?

| Category | Primary Concern |
|---|---|
| Academic Integrity | Authorship, originality, cheating, plagiarism, or appropriate attribution |
| AI Literacy | Understanding AI capabilities, limitations, bias, hallucinations, and responsible use |
| Pedagogy/Learning | Using GenAI to support teaching, learning, feedback, brainstorming, or other learning processes |
| Privacy/Data/Ethics | Privacy, data security, bias, ethical use, safety, or responsible technology use |
| Professional Readiness | Preparing students for AI use in professional or workplace contexts |
| Equity | Access, fairness, accessibility, or disparities in access to AI tools |

**Scale:** Nominal

---

## 5. Enforcement

**Guiding question:**  
Does the document specify what happens when GenAI rules are violated?

| Category | Definition |
|---|---|
| Explicit penalties | A specific consequence for violating the policy is directly stated |
| Referenced to integrity code | The document refers users to another academic integrity policy or institutional regulation where consequences are defined |
| Guidance only | The document provides recommendations or best practices without connecting them to formal penalties |
| None stated | The document discusses GenAI but provides no information about enforcement, penalties, or compliance |

**Scale:** Nominal

---

## 6. Coverage

**Guiding question:**  
Who is the policy written for, and whose behavior does it govern?

| Category | Definition |
|---|---|
| Students only | The policy directly governs student behavior or obligations |
| Faculty only | The policy directly governs instructor or faculty behavior and decision-making |
| Students and Faculty | Both instructors and students are explicitly governed audiences |
| Researchers only | The policy focuses specifically on research practice |
| Whole community | The policy applies broadly across the institution or community, including groups beyond instructors and students |

**Scale:** Nominal

---

## Governance Tier

In addition to the six policy dimensions, every document was assigned to one level of the governance hierarchy.

| Tier | Level |
|---:|---|
| 1 | National/Federal |
| 2 | State/Territory |
| 3 | Institutional |
| 4 | Faculty/Department |
| 5 | Course-wide |

Governance tier was treated as an ordered variable when analyzing how policy characteristics changed as governance moved from broad external policy toward classroom-level implementation.

---

## Analytical Variables

The primary variables used in the quantitative analysis were:

| Variable | Type |
|---|---|
| Region | Nominal |
| Institution | Nominal |
| Governance Tier | Ordinal |
| Stance | Ordinal |
| Disclosure | Nominal |
| Discretion | Nominal |
| Primary Focus | Nominal |
| Enforcement | Nominal |
| Coverage | Nominal |
