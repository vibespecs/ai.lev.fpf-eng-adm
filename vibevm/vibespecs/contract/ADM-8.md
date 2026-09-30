# ADM.8 - Establish and Exercise the Required Permission for an Administrative Action {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Architectural

**Status:** Stable

## ADM.8:0 - Use this when {#use-this-when}

Use this pattern when an intended administrative action needs a permission and the performer must establish the applicable grant, its conditions or a material conflict before acting. Examples include approving expenditure, booking a journey, reading an archive or instructing a payment.

Start with the actual performer and intended action, including the resource, extent and time that matter. The first useful result is the applicable permission and its conditions, an established lack of the required permission, or the precise unresolved authority question. When the current work includes performance, the performer then acts within the established bounds.

Use an adequate standing grant directly. The pattern does not require a fresh approval for every exercise. Technical ability, an appointment or an absence of known prohibition can be relevant inputs; each supplies only the condition it actually establishes.

## ADM.8:1 - Problem frame {#problem-frame}

A person or organization proposes an action for which the applicable institutional arrangement requires authority. The beneficiary of a grant may perform the action or may act through another participant whose own authority must be established. Approval of expenditure, delegation to an agent, access to a technical system and actual performance can therefore concern different actions.

The permission question is bounded. Permission to ask for a quote may already exist while permission to incur expenditure is still missing. Permission to read a collection does not necessarily cover downloading or disclosing it.

The local policy, agreement or competent decision supplies the substantive grant and conflict rules. This pattern establishes and uses their application to the case; it does not invent the institution's authority structure.

## ADM.8:2 - Problem {#problem}

Administrative handling often treats all successful preparatory steps as “approval”. A directory entry, supervisor endorsement or enabled button is then used as if it granted the exact action. Conversely, staff repeatedly seek approval already supplied by a standing grant.

Conflicts create a further error. A handler may assume that a permit overrides a prohibition, or ask another decider despite an applicable precedence rule already settling the case. Both responses lose the actual authority and scope of the decision.

## ADM.8:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Usable authority | A performer needs an actionable answer, while broad labels conceal resource, purpose, amount and time limits. |
| Reuse | Standing grants reduce repeated decisions, but cannot cover changed actions or expired conditions. |
| Conflict | An applicable rule can settle incompatible conclusions; unresolved cases require a competent result. |
| Technical enforcement | A mechanism can block or enable an action without constituting institutional permission. |
| Performance | Permission supports an action but does not establish that the action occurred or its promised result was supplied. |

## ADM.8:4 - Solution {#solution}

### ADM.8:4.1 - Name the action and actual participants {#name-the-action-and-actual-participants}

Specify who intends to do what, to which resource or recipient, for what relevant purpose, extent and time. Identify whose grant is being used and whether the performer acts for another participant. Add a delegation question only when the action depends on one.

Separate neighboring actions when their permission conditions differ. A manager's authorization to approve a travel expense does not automatically authorize the travel handler to approve it; the handler may instead be authorized to prepare the claim or issue a booking after that approval.

Use ADM.2 for an unclear participant or relation and ADM.3 for uncertain effectivity. Use already adequate results without rebuilding the organizational account.

### ADM.8:4.2 - Recover the required positive basis and conditions {#recover-the-required-positive-basis-and-conditions}

Obtain the applicable grant or rule-derived permission and the source that establishes it. Match the beneficiary, action, resource, extent and effective conditions to the proposed exercise. Check a relevant revocation, suspension or unmet prerequisite when it can alter this use.

Establish separately any eligibility condition required by the grant. A valid appointment can meet an appointment condition while leaving the required read grant absent. A technical credential can support authentication without supplying spending authority.

If the governing arrangement requires a positive grant, a non-prohibition finding alone is insufficient. If the rule itself permits the action under specified conditions, apply that rule; do not manufacture a separate approval requirement.

### ADM.8:4.3 - Resolve only the conflict that actually applies {#resolve-only-the-conflict-that-actually-applies}

Determine whether the apparently competing conclusions concern the same beneficiary and action with overlapping scope and time. A download restriction may leave a permitted read untouched. A restriction from 09:00 to 11:00 does not by itself govern an action at noon.

For an actual conflict, follow [A.2.8.PER][PER]'s distinction. First apply a matching current precedence rule when it selects the applicable conclusion. Otherwise reuse an adequate authorized resolving decision for this scope and time. Only a remaining unresolved conflict calls for the competent person to decide the exact question.

The title of an office, the presence of two records or the handler's preferred outcome supplies no precedence. Preserve the unresolved condition if the authorized answer is unavailable. An authorized variation does not retroactively make a failed factual prerequisite true.

### ADM.8:4.4 - Return the bounded permission result {#return-the-bounded-permission-result}

State which action by which performer is permitted, under what action-changing conditions, or why the required basis is absent or unresolved. Include the relevant source or decision reference where the recipient needs it to rely on the result.

Apply the ordinary service response to an established negative condition. If a distinct alternative basis is actually claimed, investigate that question. A missing grant, conflicting evidence and a settled prohibition need not receive the same response.

Keep a request for permission separate from the received grant. Use ADM.6 to obtain a missing competent answer or resolve an unavailable authority arrangement. The handler does not acquire the authority by documenting the gap.

### ADM.8:4.5 - Exercise within the established bounds {#exercise-within-the-established-bounds}

If the present task is only to answer the permission question, stop with that answer and its conditions. When the task includes the action, the authorized performer carries it out under those conditions and obtains the evidence of actual performance needed by its consumer.

Before a delayed exercise, revisit only facts that can change the permission: expiration, revocation, changed amount, resource, purpose or performer. A permission for one date does not extend because provision was late. A different permitted action may proceed while a separate grant remains pending.

Technical enforcement implements its specified rule. A successful operation supplies evidence about the operation and effect it actually achieved. Use ADM.9 when the beneficiary's promised condition still needs to be provided or established; use ADM.10 when performance and records disagree.

## ADM.8:7 - Conformance Checklist {#conformance-checklist}

**Recognition.** The result identifies the action, performer, positive basis where required, material conditions and any applicable conflict. It distinguishes the grant, its exercise and a non-prohibition finding.

**Assurance for reliance.** Compare the actual grant and rule to a changed amount, action or time that could alter the answer. For a conflict, establish the scope overlap and the rule or authorized result that settles it. For performance, obtain evidence of what the performer actually did; a permission record alone cannot supply that evidence.

## ADM.8:9 - Consequences {#consequences}

The performer can use established authority without needless reapproval, while material limits remain explicit. Handlers can give a precise response to absent permission and keep technical repair separate from institutional decision.

This requires access to the operative grant and conflict rules. Some actions remain unresolved when those sources or decisions are unavailable. An intelligible permission account improves the basis for action; it does not prove that the later provision succeeded.

## ADM.8:12 - Relations {#relations}

ADM.2–3 establish the relevant participants and effective relations; ADM.7 checks a needed claim without granting permission. ADM.6 supplies a competent return for a genuine unresolved question. The authorized performer uses the applicable permission in acting, and ADM.9 establishes the promised usable condition when provision is the next task.

[A.2.8.PER][PER] governs the grant/exercise/non-prohibition distinction. [OPS.6][OPS] supplies situated continuation when a legitimate next action still needs to be selected.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): [spec://ai.lev/fpf-spec/contract/A-2-8-PER#root][PER]; spec://ai.lev/fpf-eng-adm/contract/ADM-2#root–3 for participant or effective-time questions. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-adm/contract/ADM-11#root, spec://ai.lev/fpf-eng-adm/contract/ADM-9#root @status:spec/done

#source spec://ai.lev/fpf-eng-adm/source/ADM-8

[PER]: spec://ai.lev/fpf-spec/contract/A-2-8-PER#root
[OPS]: spec://ai.lev/fpf-eng-ops/pub/TOC#root
