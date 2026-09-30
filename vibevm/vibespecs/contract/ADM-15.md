# ADM.15 - Judge Administrative Consequences {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Architectural

**Status:** Stable

## ADM.15:0 - Use this when {#use-this-when}

Use this pattern when a decision about an administrative service depends on its actual consequences: whether to retain a promise, repair a control, change a provider arrangement or investigate a reported burden. A high closure rate or shorter provider handling time may conceal unusable results, mistaken refusals or work shifted to applicants.

Start with the decision and the consequence that could change it. The first useful result is a bounded account of provision, correctness, restrictions, recovery and participant effort relevant to that decision, or the exact missing observation.

Use adequate current evidence directly. A known protection breach or supported case defect can justify its applicable response without waiting for a new dashboard. This pattern does not make one speed, cost or satisfaction measure the universal objective of administration.

## ADM.15:1 - Problem frame {#problem-frame}

The practitioner is assessing a service or proposed change for an identified population, arrangement and period. Relevant participants include recipients, handlers, specialist providers, people who recover failures and others whose work is displaced.

The service's result is institutionally defined. A legitimate refusal can be a correct disposition while the requested condition remains unprovided. A technically successful action can still be unauthorized or unusable. The enabled business work has its own outcome, as ADM.1 establishes.

The receiving decision determines the evidence needed. Describing this week's observed cases, forecasting a future service level and claiming that a redesign caused improvement are different questions.

## ADM.15:2 - Problem {#problem}

Service reports often count completed tickets and average their duration. Requests abandoned before registration, unresolved cases and participants who supplied unrecorded effort disappear from the account. A local gain is then presented as a whole-service improvement.

Financial and time claims can drift too. Freed staff minutes are reported as cash savings even when no payment changes, or a faster administrative service is credited with the success of the business activity it enabled. These claims can lead the decision maker to retain the wrong arrangement.

## ADM.15:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Decision relevance | Evidence should change a real choice without becoming a permanent collection burden. |
| Population | Completed cases are easy to observe, while excluded, abandoned and unfinished needs may reveal the decisive loss. |
| Several consequences | Speed, correctness, protection, effort and money can move in different directions. |
| Claim strength | A descriptive contrast can be useful while causal and population-wide claims need stronger support. |
| Authority | An observer can reveal a trade-off without having authority to relax a protected condition or change the service. |

## ADM.15:4 - Solution {#solution}

### ADM.15:4.1 - Fix the decision, service result and affected population {#fix-the-decision-service-result-and-affected-population}

Name who needs to decide what and when the answer can still change action. Recover the applicable service promise, eligibility and permission conditions, protected interests and actual condition the recipient needs.

Define the cases or attempts relevant to that use. Include unfinished and abandoned cases, repeated attempts and pre-entry failures where omitting them changes the conclusion. Distinguish these subjects rather than adding every log row to one denominator.

Ask affected participants what the visible service record omits. An account of repeated form failure may identify a missing population even before its size is established. Preserve that limited observation while deciding which further evidence matters.

### ADM.15:4.2 - Choose the observations that can alter the decision {#choose-the-observations-that-can-alter-the-decision}

Use existing [OPS.12–15][OPS] and [OCE.13][OCE] results when they match the administrative question. Select only the relevant consequences; the following are discovery questions rather than compulsory metrics.

| Question | Necessary distinction |
| --- | --- |
| Was the condition supplied? | Promised usable effect versus approval, instruction or local closure. |
| Was the handling correct? | Legitimate refusal, mistaken refusal, unsupported approval and unresolved condition. |
| Was a restriction preserved? | Authorized use versus a successful action outside its permission or required protection. |
| What happened after failure? | Recovery, repeated work, unknown effect, abandonment and work shifted to another participant. |
| What time and effort changed? | Elapsed delay, each participant's work, interruptions and displaced work. |
| What financial consequence matters? | Actual or conditional payment, released capacity and the receiving use of that capacity. |

Use the qualified domain result for a substantive correctness or protection claim. A satisfaction answer can report the participant's experience; it cannot alone establish that the decision followed the governing rule.

### ADM.15:4.3 - Make timing, counts and comparisons interpretable {#make-timing-counts-and-comparisons-interpretable}

For each chosen quantity, recover the subject, unit or category, observation period, inclusion rule and source. Ratios need a numerator and denominator; durations need a start, end and treatment of unfinished cases. OPS.15 supplies this observation discipline.

For the laboratory shorthand `T+N`, choose the start T for the receiving question. A recipient's need-to-result delay begins at that person's observed or reported onset of need; registered handling begins when the identified request enters the service's register. Name the selected event, its source and its supported time or interval. Keep the time of a report separate from the onset it reports. If the question instead concerns delay after a request became eligible or an action became permitted, identify the applicable rule, relevant facts and event that met its condition. A reported need alone does not establish that condition.

Define the usable ending condition and the evidence for its time. State the time unit and calendar; retain a missing time as unknown or as a supported bound. For an unprovided result, report elapsed time to a stated observation cutoff with its unfinished status. N measures elapsed time, not the sum of provider and recipient labor.

For a constructed access example, the owner wants to see how much delay a registered-handling report leaves outside its scope. Use elapsed hours on a 24-hour calendar; all dates are in October 2026 and all times are UTC+03:00. In an interview at 16:00 on 5 October, Noor reports that the need for document D began between 09:00 and 10:00 that day. The portal log records registration at 09:00 on 6 October. The selected usable end is the first confirmed successful read under Noor's valid grant: a test with Noor and the archive log establish it at 12:00 on 7 October.

| Duration question | Selected start and source | Elapsed time to that usable end |
| --- | --- | --- |
| Need-to-result | Noor's reported onset, 5 October 09:00–10:00, retained separately from the interview's 16:00 timestamp. | 50–51 hours, conditional on that reported onset interval. |
| Registered handling | Portal registration, 6 October 09:00, from the request log. | 27 hours; the 23–24 hours from reported need to registration are outside this clock. |

If this request's earlier need time were unavailable, the account would retain 27 registered hours and an unknown need-to-result duration; it would not turn unobserved earlier time into zero. If the access test instead established that provision was still unfinished at the 7 October 12:00 cutoff, the account would show 50–51 hours since the reported need and 27 hours since registration, both to that cutoff. Neither would be reported as a completed-result duration.

A shorter N is useful only alongside the relevant correctness, protection, recovery and effort conditions. Moving waiting outside the portal's clock is not evidence of shorter whole-service delay. The aspiration of immediate provision does not establish that zero delay is feasible or preferable for every service.

Align definitions and conditions before comparing arrangements or periods. Preserve material differences in case mix, eligibility, staffing, concurrent changes and missing observations. Recalculate on a common basis when the source permits; otherwise state the narrower comparison.

### ADM.15:4.4 - Obtain or reuse proportionate evidence {#obtain-or-reuse-proportionate-evidence}

Begin with existing case records, provider effects, qualified checks and participant observations. Match their scope and time to the current question. A recent report can contain old data; two records can repeat the same omission.

Obtain a missing observation only when its attainable answer can change the decision or a required claim enough to warrant collection and participant burden. Use permitted sources and avoid exposing identities unnecessarily.

Keep a walkthrough estimate, observed count, participant report, forecast and causal explanation distinct. [OCE.13][OCE] supplies the corresponding consequence comparison. A causal claim requires its actual causal method and domain evidence; a before/after display or plausible story does not supply that result.

### ADM.15:4.5 - Compare the consequences and return an actionable conclusion {#compare-the-consequences-and-return-an-actionable-conclusion}

State what improved, worsened, stayed unchanged or remains unknown for the affected participants. Preserve valid restrictions and obligations before comparing optional gains. A shorter queue does not compensate for a protected condition by arithmetic.

For a financial choice, use [OPS.14][OPS] with the actual alternatives and horizon. Freed capacity has a financial consequence only through the relevant avoided payment, supported additional use or other qualified receiving account. A revised forecast does not grant spending authority.

Return the supported comparison and its limits to the authorized decision maker. A precise defect may justify a bounded repair while a broader effectiveness claim remains unresolved. Use ADM.14 for a control question, ADM.11 for a provider join or ADM.16 for a warranted transition.

Stop collection when unresolved detail cannot change this use and no other actual decision, assurance or recovery use requires it. Reopen only the affected claim when the population, rule, promise, evidence or arrangement changes.

## ADM.15:7 - Conformance Checklist {#conformance-checklist}

**Recognition.** The account names the decision, institutionally defined result, observed population and material consequences for affected participants. It distinguishes usable provision, correct refusal, uncertainty, elapsed time, labor and financial effect.

**Assurance for reliance.** Trace a decision-bearing count or duration to its actual population and source, including a consequential omitted or unfinished case. Check comparability and the qualified basis of correctness claims. Obtain stronger domain, forecasting or causal evidence only for the stronger claim actually being made.

## ADM.15:9 - Consequences {#consequences}

The decision maker can retain an observed benefit, correct a specific loss and limit an unsupported claim without treating the whole service as one success or failure. Participant effort and unresolved outcomes become visible where they affect the choice.

The cost is reconstructing a sufficient observation boundary and, sometimes, obtaining qualified correctness evidence. The result can remain partial. A truthful bounded comparison is more useful than a precise aggregate that answers another question.

## ADM.15:12 - Relations {#relations}

ADM.1 distinguishes the enabled work and administrative condition. ADM.7–10 supply relevant correctness, permission, effect and reconciliation results, while ADM.13 keeps needed grounds recoverable.

[OPS.12–15][OPS] and [OCE.13][OCE] supply the actual consequence and measurement instructions. The authorized owner uses the resulting evidence to repair a control through ADM.14, a provider join through ADM.11 or a selected arrangement through ADM.16.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-adm/contract/ADM-1#root and spec://ai.lev/fpf-eng-adm/contract/ADM-7#root–10; [spec://ai.lev/fpf-eng-ops/contract/OPS-12#root–15][OPS] and [spec://ai.lev/fpf-eng-oce/contract/OCE-13#root][OCE] for the relevant consequence question. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-adm/contract/ADM-14#root @status:spec/done

#source spec://ai.lev/fpf-eng-adm/source/ADM-15

[OPS]: spec://ai.lev/fpf-eng-ops/pub/TOC#root
[OCE]: spec://ai.lev/fpf-eng-oce/pub/TOC#root
