# ADM.14 - Connect an Administrative Control to Its Purpose and Competent Decision: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ADM.14:5 - Archetypal Grounding {#archetypal-grounding}

### ADM.14:5.1 - Duplicate expense control checks the wrong identity {#duplicate-expense-control-checks-the-wrong-identity}

Policy P requires eligible expenses to be reimbursed once. The qualified case procedure establishes the actual expense and checks its earlier reimbursement effects. A portal has implemented a shortcut that compares only uploaded image hashes.

A claimant uploads a new photograph of an expense whose reimbursement is already confirmed. The image hash differs, so the shortcut does not identify the earlier payment. The controlling claim is “this expense has already been reimbursed”, not “this file has previously been uploaded”.

The service owner recovers P and the adequate existing expense-correspondence procedure. For the actual case, the handler uses the qualified source and effect evidence to establish the earlier reimbursement and applies P's response. That bounded result can be used immediately; it does not depend on completing a new platform design.

For the reusable repair, the assigned provider implements the supplied correspondence and effect check where the payment decision uses it. The design retains the actual expense identity and evidence needed by the qualified procedure. It does not prescribe an arbitrary universal key or treat equal amounts as one expense.

The exercise includes the same expense with a different photograph, two distinct expenses with equal amounts, and an unavailable prior-payment source. The first must retain the earlier reimbursement result; the second must preserve the distinct expenses; the third must return the missing effect evidence rather than pass the check. These are stated completion conditions for the design and trial, not claims that an implementation has already passed them.

### ADM.14:5.2 - A paper requirement and an existing policy answer {#a-paper-requirement-and-an-existing-policy-answer}

A service form requests an original paper receipt. The operative policy explicitly permits a qualified electronic receipt for the same expense class, and an adequate existing interpretation covers the submitted receipt. The handler can apply that supplied policy result; another policy decision is unnecessary. The service owner sends the inconsistent form or implementation to its authorized maintainer for repair.

Change the situation: the operative policy actually requires the original for this class and its purpose is disputed. The handler cannot remove the condition by editing the form. The competent owner receives the requirement question and the evidence about burden and alternatives. An existing permitted exception may be used within its scope; otherwise the current rule supplies the case response until it is validly changed.

## ADM.14:6 - Bias-Annotation {#bias-annotation}

Control advocates can interpret every delay as the price of protection, while service-improvement advocates can interpret every restriction as waste. Neither view supplies the actual requirement or evidence of effectiveness.

Digital implementations favor conditions that are easy to count. Inspect whether the convenient property is the one the institutional decision needs, and include the participant who bears a mistaken rejection or extra collection task.

## ADM.14:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**The form is the policy** treats a mandatory field as sufficient authority. Recover the operative requirement and its actual scope.

**The proxy is the protected condition** substitutes an image hash or document presence for the decision's claim. Identify and test the actual correspondence.

**Faster means better** removes checking without examining its consequence. Compare the permitted alternatives and retained protection.

## ADM.14:10 - Architectural Rationale {#architectural-rationale}

The institutional requirement, factual check, administrative decision and enforcing mechanism each have their own conditions and responsible participants. Connecting them explicitly lets a repair stay local and prevents a successful result in one place from acquiring the authority or meaning of another.

## ADM.14:11 - SoTA-Echoing {#sota-echoing}

The working question is how a control remains justified and usable as the administrative situation changes. The May and June laboratories supply the purpose, competent-owner and opaque-refusal failures. The selected synthesis uses [SYSE.9][SYSE] for a worthwhile missing specialist contribution and [SYSE.28][SYSE] for meaningful placement, reuse and consequential outcomes.

[OASIS XACML 3.0][XACML]'s decision/enforcement distinction is a bounded technical comparison. It helps keep an unresolved or inapplicable outcome separate from the policy that governs the response; it does not determine a local requirement or turn an enforcement operation into an institutional duty.

An adequate existing rule and qualified check are the strongest simpler alternative and should be applied. Adding another approval or a more elaborate technical block fails when the actual defect is wrong claim correspondence or missing remedy. Sections 4.1–4.5 therefore locate the governed contribution before choosing a repair.

Reopen the affected arrangement when the protected condition, rule, capable source, test applicability, implementation or observed consequences change. The constructed cases demonstrate the distinctions; they do not establish an empirical false-acceptance rate.


## ADM.14:End {#end}

[SYSE]: spec://ai.lev/fpf-eng-syse/pub/TOC#root
[XACML]: https://docs.oasis-open.org/xacml/3.0/xacml-3.0-core-spec-os-en.html
