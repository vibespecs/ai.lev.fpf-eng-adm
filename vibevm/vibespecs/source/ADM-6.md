# ADM.6 - Resolve an Administrative Exception: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Organization Administration Principles Framework* (2026-09-29), `Engineering DPF Suite/ORGANIZATION-ADMINISTRATION-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ADM.6:5 - Archetypal Grounding {#archetypal-grounding}

### ADM.6:5.1 - A valid read grant and a failed identity route {#a-valid-read-grant-and-a-failed-identity-route}

A visiting researcher has an effective appointment and a valid archive read grant for 2 October. The supplied access policy additionally requires an accepted identity result for the person using the service. The portal's device credential succeeds, but its identity service cannot complete the required person check.

The handler establishes three facts: the grant is valid, the requested use is within it, and the person-check result is unavailable. The device result cannot answer the missing person question. The handler has no authority to remove that requirement.

The supplied support instruction permits the identity support officer to perform a qualified attended check through a protected channel. The handler sends that officer the specific failed attempt and needed identity question. This is a resolution request; the researcher does not yet have usable archive access.

The officer performs the prescribed check and returns an accepted result for this person and attempt. The archive provider then completes the authorized access setup. The researcher successfully opens the permitted archive material, supplying evidence of usable provision through ADM.9. These are three distinct results: the check, its use in handling, and access that actually works.

If the attended route is unavailable too, the handler reports the unavailable check and the existing support or challenge route. The valid grant is preserved; it does not supply missing identity evidence. A different service that does not depend on that check may proceed under its own conditions.

### ADM.6:5.2 - A settled negative and a genuine alternative basis {#a-settled-negative-and-a-genuine-alternative-basis}

A request for 25 September cites only an appointment effective on 1 October. The service rule requires an effective appointment at use and prescribes a response explaining the failed condition. ADM.3 supplies the negative temporal result; the handler issues that response. No further eligibility decision is needed for the supplied appointment.

The requester then identifies a different appointment said to begin on 1 September, but the relevant decision and scope are unavailable. The new question goes to its issuing office: does that appointment cover this person, work and requested date? If an adequate existing decision is recovered, use it. If it is not recovered, preserve the gap. The later descriptive record of a valid September appointment would not itself make that appointment begin later.

## ADM.6:6 - Bias-Annotation {#bias-annotation}

Handlers often classify an unusual participant as an invalid request or assume that every exception deserves special permission. First distinguish a valid unsupported case, a settled negative condition and a genuine uncertainty.

A digital route can conceal barriers experienced by people who cannot use that channel. The pattern requires an actual permitted support or redress arrangement when one is supplied; it does not presume universal availability or let the handler invent it.

## ADM.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**Escalation by forwarding** moves the case but supplies no question or capable recipient. Identify the smallest missing contribution and who can return it.

**A negative answer treated as uncertainty** repeats a decision already supplied by the rule. Apply its ordinary response; investigate only a separately live alternative or challenge.

**An exception that rewrites the facts** describes absent evidence as a passed check. Keep the authorized variation and the unresolved or negative fact distinct.

## ADM.6:10 - Architectural Rationale {#architectural-rationale}

The unit of resolution is the action-changing question. That unit connects the case to the source or participant able to answer it without making the handler a universal authority. Separating the answer from its later execution preserves accountability when several people contribute to one administrative result.

## ADM.6:11 - SoTA-Echoing {#sota-echoing}

The working question is how to restore legitimate continuation when ordinary administrative handling cannot supply its result. The May and June laboratories expose opaque refusal, specialist judgment and execution gaps. The selected method joins those domain distinctions to the actual direct-rule, recognition and continuation instructions in [OPS.6][OPS].

[NIST SP 800-63-4][NIST]'s redress treatment supplies a bounded comparison for digital-identity failures: accessible issue handling, review, correction and human support. It does not determine a local appointment or entitlement. That limit shapes §§4.2 and 5.1: a qualified identity result is requested from its proper source and then used by the service.

[CMMN 1.1][CMMN] provides a serious alternative for adaptive case planning. Its information and discretionary-work constructs can carry the handling arrangement, but do not by themselves settle institutional authority. An adequate ordinary instruction is the cheaper alternative and remains sufficient when it already resolves the condition.

Reopen the affected instruction when repeated exceptions reveal a missing ordinary branch, an unavailable competent provider or a changed governing rule. Repetition alone does not justify waiving the condition.


## ADM.6:End {#end}

[OPS]: spec://ai.lev/fpf-eng-ops/pub/TOC#root
[NIST]: https://pages.nist.gov/800-63-4/sp800-63.html
[CMMN]: https://www.omg.org/spec/CMMN/1.1/PDF
