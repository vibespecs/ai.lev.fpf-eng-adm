# ADM.8 - Establish and Exercise the Required Permission for an Administrative Action: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ADM.8:5 - Archetypal Grounding {#archetypal-grounding}

### ADM.8:5.1 - A quote and a booking have different prerequisites {#a-quote-and-a-booking-have-different-prerequisites}

A travel handler is permitted by the supplied service policy to request nonbinding prices. The same policy permits booking only after a named budget holder authorizes the expenditure. A traveller supplies a destination and date, but the budget authorization is pending.

The intended first action is a nonbinding price inquiry. The standing permission covers the handler, inquiry and relevant provider; the stipulated other conditions hold. The handler can obtain a quote now. That action does not create the budget holder's approval or commit the organization to the booking.

After the budget holder authorizes a specified booking up to 300 units for the named trip, the handler receives a 280-unit offer within those conditions. The existing booking instruction and grant permit the handler to book it. An otherwise similar 340-unit offer is outside the supplied amount condition and needs its applicable response or a new competent decision.

The budget holder's decision, handler's booking action and traveller's usable travel arrangements remain separately recoverable.

### ADM.8:5.2 - A grant, a temporary restriction and an unresolved variant {#a-grant-a-temporary-restriction-and-an-unresolved-variant}

A researcher has a valid read grant for collection R on 2 October. A security instruction restricts that same read action from 09:00 to 11:00. The supplied policy explicitly gives this temporary security restriction precedence during that interval. At 09:30 the handler applies that rule: the read action is restricted, and no additional discretionary decision is needed.

At noon the temporary restriction no longer covers the requested action. Suppose the grant and all its other conditions still hold and no other applicable restriction is present. The researcher can exercise the read permission. The earlier conflict does not create an all-day ban.

Now change the case: both conclusions apply at 09:30, but no matching precedence rule or adequate resolving decision is available. The handler returns the exact conflict to the authorized security/access decision maker and preserves the unresolved permission question. Naming that person is not the resolving decision.

### ADM.8:5.3 - Permission survives a provider failure within its conditions {#permission-survives-a-provider-failure-within-its-conditions}

For a permitted read at noon, the portal fails to open collection R. The grant is still valid. The provider investigates the failed use under ADM.9, using any permitted existing recovery route.

The provider may not silently give download access when the grant covers reading only. If recovery is delayed beyond the grant's effective day, the permission question reopens for the later use. Repairing software neither broadens the action nor extends its time.

## ADM.8:6 - Bias-Annotation {#bias-annotation}

Organizational status, familiarity and a powerful interface can be mistaken for authority. Examine the actual grant and action instead of the participant's prestige or technical capability.

A permission account can also become needlessly restrictive by carrying every neighboring action's prerequisites into the present one. Keep the bounded action visible, including ordinary permitted inquiry and correction.

## ADM.8:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**The button grants authority** treats technical capability as institutional permission. Recover the rule or grant required for the action.

**Approval everywhere** repeats a standing authorization or blocks inquiry behind an unrelated spending prerequisite. Match the condition to the particular action.

**Permit always wins** invents conflict precedence. Apply the actual matching rule or adequate resolving decision; return only the unresolved question.

**A repair enlarges the grant** supplies an excluded action or later use as a convenient workaround. Recover permission for the changed action before relying on it.

## ADM.8:10 - Architectural Rationale {#architectural-rationale}

A permission is a relation under particular conditions, its exercise is an action, and the provider's usable result may be a further effect. Preserving those distinctions lets the handler reuse a grant, identify a real conflict and repair a failed provision without accidentally changing institutional authority.

## ADM.8:11 - SoTA-Echoing {#sota-echoing}

The working question is how to make an administrative action legitimate and executable without confusing grant, eligibility, enforcement and performance. The selected instruction follows the actual [A.2.8.PER][PER] grant, exercise, non-prohibition and conflict distinctions, especially §4.6. The laboratories supply the administrative cases in which device permission, institutional conditions and usable access diverge.

[OASIS XACML 3.0][XACML], terminology and §7.2, supplies a serious policy-decision/enforcement comparison. Its architecture separates information, decisions and enforcement; it requires defined handling of inapplicable or indeterminate outcomes. Sections 4.2–4.5 retain that separation without prescribing XML or importing an XACML enforcement operation as a general legal obligation.

A direct standing rule is the strongest simpler alternative and is sufficient when its conditions settle the action. A universal approval workflow adds cost and can misclassify independent actions; an allow/deny interface alone can conceal the missing institutional basis. The constructed cases test these distinctions under supplied rules, not the legality of an actual organization.

Reopen the affected permission when its beneficiary, action, scope, rule or effective conditions change. Changes to a technical implementation require reconsidering permission only where they change those conditions or the action being performed.


## ADM.8:End {#end}

[PER]: spec://ai.lev/fpf-spec/contract/A-2-8-PER#root
[XACML]: https://docs.oasis-open.org/xacml/3.0/xacml-3.0-core-spec-os-en.html
