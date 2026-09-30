# ADM.6 - Resolve an Administrative Exception {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Architectural

**Status:** Stable

## ADM.6:0 - Use this when {#use-this-when}

Use this pattern when a real obstacle prevents the applicable administrative instruction from producing its ordinary result: a needed fact is disputed, the rule does not cover the case, requirements conflict, authority is unresolved or provision has failed in a way the ordinary recovery cannot resolve.

The first useful move is to state the exact condition preventing the next action and identify the person or source able to resolve it. The result is a resolved condition and usable continuation, or a reasoned disposition with the applicable correction or challenge route. A request for resolution is an intermediate result when the answer is still unavailable.

Apply a sufficient existing rule or recovery instruction directly. An ordinary missing-field correction or a negative condition already settled by policy is not automatically an exception. This pattern grants no authority to waive a requirement, invent evidence or extend a permission.

## ADM.6:1 - Problem frame {#problem-frame}

A handler is working on a particular request for an administrative condition. The relevant action, participant and intended time are known well enough to locate what is blocked. The handler may have a service instruction, prior decisions and evidence from the provider.

The obstacle belongs to a particular question. A missing identity result, an unresolved eligibility rule, an unavailable authorized decider and an unknown payment effect call for different work. They can occur in one case without becoming interchangeable reasons to “escalate”.

Resolution also has several possible stopping points. Finding the competent source creates an actionable request; receiving its answer may settle the condition; an authorized provider must still perform any resulting provision. The handler states which result is actually available.

## ADM.6:2 - Problem {#problem}

An opaque refusal leaves the participant unable to correct the case. Repeated transfers between departments can move the request without moving the unresolved question. A handler may compensate by improvising a waiver, treating technical access as permission, or repeating a payment whose earlier effect remains unknown.

At the other extreme, every negative answer is sent to a discretionary decision maker. This delays cases whose governing rule already supplies the response and obscures the genuinely unresolved alternatives that do need judgment.

## ADM.6:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Continuity | The participant needs a next move, while some missing results require qualified work that the handler cannot perform. |
| Competence | A reachable person is useful only if they can supply the needed fact, interpretation, decision or provision. |
| Direct resolution | A matching rule or prior result may settle the question without a new choice. |
| Legitimate alternatives | A permitted alternative can restore use; convenience cannot create permission to bypass a restriction. |
| Accurate progress | A sent request, received decision and usable effect must remain distinguishable. |

## ADM.6:4 - Solution {#solution}

### ADM.6:4.1 - Recover the blocked action and the actual obstacle {#recover-the-blocked-action-and-the-actual-obstacle}

State the intended action, its participant, applicable time and the condition that is not established. Use the existing case facts; reopen ADM.1–3 only when the requested result, relevant relation or effective time is itself unclear.

Separate what is known from what is missing. “No appointment is effective on this date under the supplied decision” is an established result. “An earlier appointment is claimed but its decision cannot be recovered” is a separate unresolved basis. A provider's failure message may establish that a login attempt failed while leaving institutional permission intact.

If the applicable rule already determines the response, apply it. A policy-defined refusal can finish that bounded inquiry and still expose the available correction or challenge route. The existence of that route does not make a challenge mandatory.

### ADM.6:4.2 - Identify the smallest resolution task {#identify-the-smallest-resolution-task}

Locate the missing contribution before choosing a recipient.

| Actual obstacle | Needed contribution |
| --- | --- |
| A material claim is unsupported or disputed | Evidence or a competent check of that exact claim; ADM.7 helps specify it. |
| The rule's application or scope is unresolved | Interpretation from the source or person authorized to settle that question. |
| Requirements yield incompatible conclusions | A matching precedence rule or adequate resolving decision; ADM.8 keeps the permission question bounded. |
| A required authority is absent or unclear | A decision or assignment by the person permitted to provide it, if the governing arrangement allows one. |
| Authorized provision failed or its effect is unknown | Investigation and recovery by the provider able to establish or change that effect; ADM.9 applies. |

A named department is not yet a resolution mechanism. Identify an actual receiving function or person and the result they can supply. If no such assignment exists, return that gap to the person authorized to arrange it. Do not fabricate a specialist answer to keep the case moving.

### ADM.6:4.3 - Reuse what already resolves the question {#reuse-what-already-resolves-the-question}

First apply a matching rule, adequate evidence or existing authorized decision within its conditions. Confirm the relevant subject, scope and time; a nearby case's answer may concern a different person or action.

When more than one legitimate continuation remains, use the applicable decision method to select among them. [OPS.6][OPS] supplies the situated continuation: direct rule or recognition first, a real choice only when alternatives remain, and a bounded probe only if its answer can change the action.

An authorized exception can permit a bounded action under its actual conditions. It does not make a failed factual claim true. Record or communicate the condition that was waived or varied separately from the evidence that remains absent or negative.

### ADM.6:4.4 - Send an answerable question and preserve permitted work {#send-an-answerable-question-and-preserve-permitted-work}

Give the resolver the question, relevant facts, actual conflict or gap, intended use of the answer, and any time condition that changes its usefulness. Use existing evidence references and protect information according to the applicable rules. Avoid forwarding an entire personal file when a narrower account suffices.

State who will consume the result and perform the next action. Obtain a usable return arrangement through the existing service channel; do not assume that sending a message appointed the recipient or established a response commitment.

Continue independent permitted work when its own prerequisites hold. A spending-approval question can block booking while a permitted price inquiry proceeds. An unresolved earlier payment effect blocks a potentially duplicate payment, but may leave an evidence inquiry fully permitted.

### ADM.6:4.5 - Apply the actual answer or issue the reasoned disposition {#apply-the-actual-answer-or-issue-the-reasoned-disposition}

On return, check that the answer concerns this subject, action, scope and time. Apply a settled condition under the service instruction. A new authorization supplies a permission result; the provider still needs to perform the authorized provision.

For a refusal, explain the action-changing reason and the correction, alternative or challenge route that the applicable arrangement actually provides. A competent refusal may be the correct case disposition while the requested condition remains unprovided. Do not report the beneficiary's service as supplied merely because the administrative inquiry ended.

If the answer or effect is still unavailable, preserve the specific uncertainty, the responsible next action and any applicable time or stop condition. The useful completed result may be an actionable resolution request, with the dependent provision still unfinished.

## ADM.6:7 - Conformance Checklist {#conformance-checklist}

**Recognition.** The handler can name the blocked action, exact obstacle, needed contribution and competent destination. A settled result is applied; an unresolved question remains explicit.

**Assurance for reliance.** Trace the actual response back to its authority or evidence and forward to the next action. Verify that an alternative preserves the relevant conditions, that independent permitted work is not blocked by association, and that a request for resolution has not been reported as the received answer or completed provision.

## ADM.6:9 - Consequences {#consequences}

Participants receive an intelligible next action instead of an unexplained transfer. Handlers can use existing rules and answers more quickly while reserving specialist attention for unresolved questions.

Some cases remain blocked because the competent contribution is unavailable. Making that condition explicit is useful, but it does not provide the requested service. Evidence from actual handling is needed to establish whether resolution reduces delay or displaced effort.

## ADM.6:12 - Relations {#relations}

ADM.1–3 establish the needed condition and relevant effective relations when those are unclear. ADM.7 specifies the needed factual check; ADM.8 resolves permission within the applicable rule. The handler uses the returned result in continuing the case, while the authorized provider performs provision under ADM.9. ADM.10 supplies reconciliation when an obligation or recorded effect remains disputed.

ADM.5 is used when the recurring instruction itself needs repair. [OPS.6][OPS] supplies a current continuation decision without requiring redesign of that instruction for every exception.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-adm/contract/ADM-7#root–9 for the missing claim, permission or provision; [spec://ai.lev/fpf-eng-ops/contract/OPS-6#root][OPS] for situated continuation. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-adm/contract/ADM-14#root, spec://ai.lev/fpf-eng-adm/contract/ADM-5#root @status:spec/done

#source spec://ai.lev/fpf-eng-adm/source/ADM-6

[OPS]: spec://ai.lev/fpf-eng-ops/pub/TOC#root
