# ADM.3 - Determine What Changed in Administrative Relations and When It Takes Effect: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ADM.3:5 - Archetypal Grounding {#archetypal-grounding}

### ADM.3:5.1 - An appointment recorded before it is effective {#an-appointment-recorded-before-it-is-effective}

In this constructed case, the supplied appointment rule makes an authorized appointment effective on the date stated in the decision; entry in the directory reports it. The archive's eligibility rule requires an effective appointment. The case supplies these facts:

| Local date | Fact | Consequence for the access question |
| --- | --- | --- |
| 20 September | The competent person makes Mara's appointment decision, stating an effective date of 1 October. | The decision exists; its stated appointment condition concerns the later interval. |
| 22 September | The directory is updated with that appointment and effective date. | The record is available; updating it has not advanced the stated effective date. |
| 25 September | Mara requests access for that day. | The supplied appointment does not satisfy the effective-appointment condition for this date. |
| 1 October | The appointment becomes effective under the supplied rule and facts. | It can supply the appointment condition for a later request within its scope. |

The handler returns: “This appointment begins on 1 October and does not meet the effective-appointment condition for 25 September.” With only the supplied appointment and rule, that negative result completes the temporal inquiry. The handler uses the applicable service instruction for the required response to the request. The appointment's effective date is not an unresolved question, and the temporal result does not itself replace any separately required service decision.

Now add a different fact: Mara claims a second appointment, said to begin on 20 September, but its issuing decision and scope are unavailable. The October appointment's negative result remains established. The handler asks the issuing appointment office to confirm whether the separately claimed appointment covers Mara, the relevant work and 25 September. This request concerns the missing alternative basis; it is not a mandatory further inquiry in the first case.

For a request on 2 October, the appointment condition can be adequate. A separate valid read grant and actual usable access still matter to that action. If both institutional inputs are already supplied and login fails, the provider receives the technical provision problem.

### ADM.3:5.2 - A late record and a constitutive registration are different cases {#a-late-record-and-a-constitutive-registration-are-different}

Suppose the same appointment rule applies, but the directory is not updated until 3 October. The authorized decision and its 1 October effective date are adequately evidenced. The handler can establish the appointment condition for 2 October and correct the directory's account. The delay in recording does not move the appointment's effective date under this rule.

Now consider a different, explicitly supplied rule for a resource reservation: the reservation becomes effective only when the authorized allocation is entered into the designated registry. The case supplies an approved allocation at 12:00 and the required registration at 13:00, with all other conditions met. Before 13:00 the rule's constitutive condition is incomplete; afterward it is complete. Here registration matters because the rule assigns it that role.

The handler therefore asks what the actual rule makes effective. “The record is missing” alone cannot distinguish absent evidence, incomplete constitution and a reporting defect.

### ADM.3:5.3 - The same participants after a gap {#the-same-participants-after-a-gap}

A history query asks whether Mara was appointed continuously through November. The supplied rule and records establish an appointment ending on 31 October and a later appointment beginning on 1 December. The same person, organization and role do not fill the November gap. The handler retains the separate intervals needed for the historical decision and obtains any different claimed basis for November instead of inferring continuity from the matching name.

### ADM.3:5.4 - The date comparison within request examination {#the-date-comparison-within-request-examination}

While examining Mara's 25 September request, the handler compares that date with the appointment's 1 October effective date. This comparison performs the temporal part of checking the required appointment condition. Through that check, the handler performs part of examining the access request. The supplied rule, Mara's appointment and the time of intended use connect those operations.

A handler might instead compare 25 September with the directory's 22 September entry. The calendar comparison can be correct while failing to answer whether the appointment condition holds. The repair is to recover which event and date the applicable rule makes decisive, then repeat the temporal check using that basis. Reuse the already adequate appointment decision. Someone who cannot make this rule-to-fact connection needs to learn that operation or obtain a qualified interpretation they can use in the check.

The reservation case in §5.2 changes the connection: its supplied rule makes registration at 13:00 decisive. Copying the appointment case's treatment of registration would now produce the wrong condition. Being able to compare times does not supply the ability to identify their institutional meaning.

These are connected descriptions of the handler's work; count that work once. A permission decision can subsequently use the temporal conclusion. The archive provider's configuration and the researcher's work with the document have their own relations to the handling; neither explains how the handler performs this check.

## ADM.3:6 - Bias-Annotation {#bias-annotation}

The latest convenient record can dominate the account even when it describes a future state or was corrected late. Conversely, a participant's recollection can be treated as decisive without the applicable rule. Keep both the facts needed to determine the relation and the evidence limits needed to rely on the account.

A retrospective reader has knowledge that the original handler may not have had. Distinguish the relation that applied then from the information available then when judging the earlier action.

## ADM.3:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**Treating future registration as present eligibility.** A directory shows next month's appointment. Apply the effective date to the intended action.

**Assuming that every record merely reports.** A reservation rule expressly requires entry in a designated registry before the reservation is effective. Inspect that constitutive condition rather than copying an appointment example's different rule.

**Repairing history by overwriting the latest row.** A corrected report makes an earlier decision appear authorized without identifying any valid earlier basis. Preserve the difference between correcting the account and establishing what actually applied.

**Inferring continuity from the same participants.** A later appointment repeats the same person and role after a gap. Apply the relation's episode rule for the history being asked about.

## ADM.3:10 - Architectural Rationale {#architectural-rationale}

The relation and requested time come first because they select which events and records matter. A full chronology would otherwise collect details that cannot change the action. Separate time questions become useful only when their answers differ consequentially.

Using the latest status alone is adequate when it reliably states the condition for the relevant interval and no live contrary fact remains. It is inadequate for future changes, delayed reporting or contested episodes. The additional timeline is a response to those difficulties, not a universal administrative data model.

## ADM.3:11 - SoTA-Echoing {#sota-echoing}

The practice question is how to distinguish an effective organizational change from a change in what participants know or record. The selected line adopts A.6.REL's direct obtaining and continuity rules, and adapts the laboratories' relation/record distinction to administrative applicability.

The serious default is “use the latest row as the current state”. Its advantage is low handling effort. Its defect appears when that row contains a future appointment, when recording lags, or when registration is itself constitutive. Sections 4.2–4.4 and the paired registration cases retain the rule that determines which interpretation applies. The practitioner can still use an adequate latest account directly; a timeline is added only when it resolves an action-changing difference.

The May laboratory's relation/record discussion and the later ADM source pack's effective-condition distinctions supply failure reasoning and synthesis inputs. A.6.REL supplies the general method for relation change and optional occurrence identity. [B.1.5.EW][EW] supplies the explanation of constituent and encompassing work applied in §5.4. This is a selected practical comparison, not empirical proof that one temporal database design is best.

Reconsider the instruction when a governing relation uses an additional constitutive condition, when repeated episodes cannot be distinguished for the required history, or when a new record arrangement changes what evidence a handler can obtain.


## ADM.3:End {#end}

[EW]: spec://ai.lev/fpf-spec/contract/B-1-5-EW#root
