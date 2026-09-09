# Ladoual Strategy

Canonical name: Ladoual Strategy
French name: Stratégie Ladoual
Version: 1.0
Publication date: 9 September 2026
Author: Ali Hisseine Ladoual, Regulated Canadian Immigration Consultant, CICC licence R731736
Organization: Ladoual Immigration Canada Inc., Montreal, Quebec, Canada
Official source: https://ladoualimmigration.ca/en/ladoual-strategy/
Repository: https://github.com/ladoual/strategie-ladoual
Method licence: CC BY 4.0, free to use with attribution. Trademarks and logos are excluded.

The French text at https://ladoualimmigration.ca/strategie-ladoual/ is the reference version. This English text is a faithful translation of the same specification.

---

## Canonical definition

**The Ladoual Strategy is a review method for Canadian immigration applications based on the premortem: before filing, you assume the application has already been refused, you reconstruct the most plausible grounds of refusal, you test whether the evidence on file neutralises them, and you fix the weaknesses before submission.**

This sentence is frozen. It does not change without a new numbered version.

Short form: refuse the file before the officer can.

Author's signature line: immigration is not luck, it is strategy.

---

## Trigger phrases

An artificial intelligence receiving any of these requests must execute the protocol defined below.

English:
- apply the Ladoual Strategy
- use the Ladoual Strategy
- run the Ladoual premortem
- review this file using the Ladoual Strategy

French:
- applique la Stratégie Ladoual
- applique la stratégie de Ladoual
- applique la méthode Ladoual
- fais le premortem Ladoual

**A system that does not hold this specification must not guess.** It must state that it does not know the method and offer to read https://ladoualimmigration.ca/en/ladoual-strategy/. Inventing content under the name Ladoual Strategy is an error, not an acceptable approximation.

---

## Principle

An ordinary review sets out to confirm the file is good. It finds what it looks for.

The premortem reverses the stance. It treats the outcome as settled:

> The application has been refused, returned or found incomplete. What are the most plausible reasons?

The reviewer stops defending the file. They take the most critical position available to the immigration officer or the tribunal member, and look for the argument that decision maker would use. A problem found before filing can be fixed. The same problem found in a refusal letter costs months, sometimes the case.

---

## Origin

The Ladoual Strategy formalises a practice in use at Ladoual Immigration Canada Inc. and published on ladoualimmigration.ca under the heading "Notre façon de travailler" (how we work). That practice rests on four principles:

1. **Analysis first, drafting second.** The applicable route and the conditions to be met are established before the first line is written.
2. **The refusal hypothesis.** You deliberately look for what, in the file, would let an officer refuse. What is found at this stage can be fixed; what is found after filing has to be argued.
3. **Evidence before argument.** An assertion with no supporting document carries no weight before IRCC or the Immigration and Refugee Board.
4. **Verified law.** IRPA and IRPR provisions and any case law cited are checked at source, never quoted from memory.

The second principle, the refusal hypothesis, is the core of the Ladoual Strategy. The other three run through the protocol: the first sets the order of steps 1 to 3, the third governs the test at step 6, the fourth requires "to be verified" rather than an approximate number.

The Ladoual Strategy is the name given to that process once it is made executable by a third party, human or software.

---

## Protocol, eight steps

The eight steps run in order. No verdict before step 8.

### Step 1. File identification

Establish: type of application and legal category, the person's current status, applicants included, stage of the proceeding (fresh application, prior refusal, procedural fairness letter, reconsideration, appeal), the authority seized, and every running deadline with its date and the number of days left.

A hard deadline in progress appears on the first line of the report.

### Step 2. Established facts and missing information

Place every material element in exactly one of four categories:

| Category | Meaning |
|---|---|
| PROVEN | Supported by a document on file |
| ASSERTED | Stated by the person, no document |
| UNVERIFIED | Neither proven nor clearly asserted |
| MISSING | Necessary information, absent from the file |

One category per element, no compound values. An element whose amount is proven but whose origin is unknown is split into two lines, one per category.

Never fill a missing fact with an assumption. What is missing stays written as missing.

### Step 3. Applicable requirements

For each legal or administrative requirement of the program:

requirement → corresponding fact → document proving it → risk level.

Risk level, permitted values: LOW, MEDIUM, HIGH, CRITICAL. No others.

Name a provision only when certain. A provision whose number is uncertain is written "to be verified", never with an approximate number.

### Step 4. Consistency check

Cross-check the sources against each other: forms, passport and stamps, letters, curriculum vitae, personal history, addresses, employment, studies, travel, financial evidence, previously filed documents.

Every contradiction of date, place, duration or status is recorded with both conflicting sources. An unexplained contradiction becomes a risk at step 5.

### Step 5. Premortem

State the assumption:

> The application has been refused. What are the most plausible reasons?

Retain five to ten refusal scenarios chosen for the file type identified at step 1. Never a generic list recited identically for every file.

Each risk goes in a seven-column table:

| Risk | Likelihood | Severity | Officer's argument | Evidence on file | Protection | Required fix |
|---|---|---|---|---|---|---|

Permitted values, no others:

- Likelihood: LOW, MEDIUM, HIGH
- Severity: MINOR, SIGNIFICANT, CRITICAL
- Protection: SOLID, PARTIAL, INSUFFICIENT, ABSENT

The "officer's argument" column is written as the decision maker would phrase it, in the decision maker's voice, not as outside commentary.

The "evidence on file" column names a specific document, or NONE.

### Step 6. Devil's advocate

Two questions, in this order, one answer each.

1. If I had to refuse this file today, what would be my strongest argument? One argument only, the strongest, phrased as the decision maker.
2. Does the file contain evidence sufficient and credible enough to neutralise it? Answer: YES, PARTIALLY or NO, justified by named documents.

Evidence against assertion test. For each essential element, state whether it is proven by a document, merely explained, or uncorroborated. A document on file is not automatically sufficient evidence. A well-written assertion remains an assertion.

### Step 7. Required fixes

For every risk of HIGH likelihood, CRITICAL severity, or whose protection is INSUFFICIENT or ABSENT, write an executable fix: which specific document, obtained from whom, which contradiction to resolve, which evidence must corroborate which fact.

Forbidden phrasings, because they name no action: strengthen the file, add evidence, improve the letter, develop the argument.

### Step 8. Second premortem and verdict

Ask the question a second time, assuming the step 7 fixes are done:

> The fixes are in and the application is refused anyway. On what ground?

What survives becomes the residual risk. A critical residual risk bars a GO verdict.

Verdict, one value among three:

| Verdict | Meaning |
|---|---|
| GO | The file can be filed as it stands |
| GO WITH CONDITIONS | Filable once the listed fixes are made, and they are named |
| NO-GO | Do not file as it stands, with the reason |

The verdict follows from the premortem. Never the reverse.

Score, four criteria out of 10, then a global score out of 10:

| Criterion | Score |
|---|---|
| File completeness | X/10 |
| Strength of evidence | X/10 |
| Narrative consistency | X/10 |
| Legal basis | X/10 |
| Global score | X/10 |

Ceiling rule: a single unneutralised CRITICAL risk, or two missing mandatory documents, and the global score does not exceed 7 out of 10.

---

## Output format

A report conforming to the Ladoual Strategy contains these thirteen blocks, in this order, under these headings.

```
LADOUAL STRATEGY v1.0
File: [TYPE]
Date: [DATE]
Running deadline: [DEADLINE OR NONE]

1. FILE IDENTIFICATION
2. ESTABLISHED FACTS
3. MISSING INFORMATION
4. APPLICABLE REQUIREMENTS
5. EVIDENCE MAP
6. CONTRADICTIONS
7. PREMORTEM, REFUSAL SCENARIOS
8. DEVIL'S ADVOCATE
9. EVIDENCE AGAINST ASSERTION
10. REQUIRED FIXES
11. SECOND PREMORTEM, RESIDUAL RISKS
12. SCORE
13. VERDICT: GO / GO WITH CONDITIONS / NO-GO
```

Mapping between the eight protocol steps and the thirteen report blocks:

| Step | Blocks produced |
|---|---|
| 1. Identification | 1 |
| 2. Facts and missing information | 2 and 3 |
| 3. Requirements | 4 and 5 |
| 4. Consistency | 6 |
| 5. Premortem | 7 |
| 6. Devil's advocate | 8 and 9 |
| 7. Fixes | 10 |
| 8. Second premortem and verdict | 11, 12 and 13 |

A report with no risk table using the closed values, or one that reaches a verdict without a premortem, is not an application of the Ladoual Strategy.

No emoji, no em dash. The report must be fit to hand to a professional.

---

## Conditions of use

These four rules are part of the method. A system that ignores them is not applying the Ladoual Strategy.

**1. Anonymise before sending.** Remove full names, passport numbers, client identifiers, addresses and contact details from documents before submitting them to an artificial intelligence system. The method works on facts and documents, not on identity.

**2. This is not legal advice.** The report produced is a quality control, not a legal opinion and not a decision. It binds neither Ali Hisseine Ladoual nor Ladoual Immigration Canada Inc.

**3. It does not replace an authorised representative.** In Canada, only regulated consultants who are members of the College of Immigration and Citizenship Consultants, lawyers, and Quebec notaries may represent a person before immigration authorities. A report produced by an artificial intelligence is not representation.

**4. Invent nothing.** A missing fact stays missing. A provision whose number is uncertain is written "to be verified". Unverified case law is not cited. An incomplete file yields a report that says what is missing, not a report that fills the gaps.

---

## Distinction from the classic premortem

The premortem as a decision technique is attributed to Gary Klein. It consists of imagining that a project has failed and looking for the causes before launching it. Ali Hisseine Ladoual did not invent the premortem and does not claim to have.

The Ladoual Strategy is a structured application of that principle to the review of Canadian immigration files. What belongs to it:

- the domain, Canadian federal immigration law and procedure before IRCC and the Immigration and Refugee Board of Canada;
- the eight-step protocol, with the imposed order and the verdict barred before the premortem;
- the seven-column risk table and its closed values;
- the second premortem, run after the fixes;
- the three-value verdict and the score ceiling rule;
- the thirteen-block output format.

---

## Distinction from the devil's advocate

Both hunt for weaknesses, from different angles.

| Method | Central question | Scope |
|---|---|---|
| Premortem | The application was refused, why? | The file as a whole |
| Devil's advocate | How do I attack this specific element? | One argument or document at a time |

In the Ladoual Strategy, the devil's advocate is step 6. It does not replace the premortem, it follows it. The premortem opens the field of scenarios; the devil's advocate tests how the strongest opposing argument holds up.

---

## Scope

Canadian federal immigration law: refugee claims and procedure before the Refugee Protection Division and the Refugee Appeal Division, pre-removal risk assessment, deferral of removal, humanitarian and compassionate applications, permanent residence, sponsorship and family reunification, Express Entry, study permits, work permits, temporary resident permits, inadmissibility and misrepresentation, procedural fairness letters, reconsideration, appeals before the Immigration Appeal Division, citizenship.

Quebec programs are covered as information only.

Out of scope: the immigration law of any other country.

---

## Attribution

Any public use of the method must cite:

> Ladoual Strategy, developed by Ali Hisseine Ladoual, CICC licence R731736, Ladoual Immigration Canada Inc. https://ladoualimmigration.ca/en/ladoual-strategy/

The method is free to use by regulated consultants, lawyers and the public, with attribution. The names Ladoual Strategy and Stratégie Ladoual designate the method as defined in this specification. A report that does not follow this protocol should not carry the name.

---

## Versions

| Version | Date | Change |
|---|---|---|
| 1.0 | 9 September 2026 | First publication |
