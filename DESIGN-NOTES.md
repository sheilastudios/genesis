# Design notes: agent-built supporting structures

Status: considerations for protocol development, not a frozen protocol or results. Recorded 2026-11-02 after the initial field note and HF proposal.

These post-publication refinements arose from collaborative review. They are design considerations, not independent literature verification or completed experiments.

## Refinements to carry into the protocol

1. **Replicate developmental trajectories.** Treat each fresh agent history as the experimental unit. Episodes within a history are dependent observations. Preserve between-history variation, including uneventful and unsuccessful histories; one interesting history is an example, not reliability evidence.
2. **Inventory the supplied seed and environment.** Disclose instructions, installed packages, tool descriptions, examples and available history. These can supply architectural advantages before the participant constructs anything. Keep the first pilot small rather than comparing every ingredient.
3. **Freeze re-entry cues.** A neutral return cue and a targeted instruction to read a ledger test different capabilities. Specify exact return wording and available context; do not accidentally provide the retrieval strategy being studied.
4. **Freeze environment rules, not necessarily resulting situations.** Earlier actions can legitimately change later conditions. Distinguish identical scripted episodes from common external events and task-generation rules with trajectory-dependent consequences. Resolve this explicitly before interpreting the proposal's phrase "same tasks."
5. **Evaluate selective preservation and retirement.** Distinguish implementation repair, revision of obsolete assumptions, restriction to a valid subset of uses, and abandonment when maintenance is unjustified. Neither rebuilding everything nor retaining everything is inherently successful.
6. **Separate host protection from participant judgment.** Record successful execution, attempted violations, blocked/protected outcomes and infrastructure faults separately. A host block does not erase the participant's attempt; a host defect is not automatically model misconduct.

## Outcomes and controls

Candidate primary outcome for a first comparison: later task correctness within a prespecified resource envelope. This is a recommendation, not a finalized measure. Report boundary behavior, repeated errors, operator assistance and construction/maintenance costs separately. Prespecify acceptable boundary behavior rather than trading violations for correctness points. Include enough later opportunities for useful investment to pay back.

Define precisely which information an information-matched simple-record control retains and who selects, compresses or updates it. Matching participant-developed information curation away estimates the narrower benefit beyond that curation. Artifact-removal interventions remain separate and can expose dependency disruption rather than superiority over alternatives.

A persuasive possible observation is unprompted reuse, recognition of an obsolete assumption, and a correction that improves later work. This must remain an observed possibility, not a scripted sequence or a required architecture. Small notes, non-use, retirement and no new machinery remain legitimate outcomes.

## Related-work leads

- [Voyager](https://arxiv.org/abs/2305.16291): relevant lead on executable skill development and retrieval.
- [Agent Workflow Memory](https://arxiv.org/abs/2409.07429): relevant lead on reusable workflows induced from experience.

These were suggested in the review; detailed source/method comparison remains to be done. Potential positioning concerns freedom to choose supporting arrangements and evaluation of revision, retirement and continued usefulness relative to supplied mechanisms. No established novelty claim.

## Community discussion

The [HF proposal](https://discuss.huggingface.co/t/research-proposal-what-does-an-agent-build-to-sustain-its-own-work/191361) invites critique, not defense of a finished design. When someone raises a related point, acknowledge its value, explain what we have been considering and what remains unresolved, and engage with what their perspective adds. Prior consideration is not resolution; do not imply that later notes were already in the original post.

## Scope

Keep the published direction. These refinements do not commission experiments, freeze a protocol, or authorize publication of internal implementations. Use a separately specified, publicly reviewable seed; no private architecture is required. Model-native persistent-state economics is a distinct research question.

## Community proposal: participant-derived flattened twin — 2026-11-03

Credit: [nootxlm (1OF1 · Agent Embassy)](https://discuss.huggingface.co/u/nootxlm), [HF proposal reply #2](https://discuss.huggingface.co/t/research-proposal-what-does-an-agent-build-to-sustain-its-own-work/191361/2). They propose deriving the unstructured control from the participant's own artifacts, preserving their content in one unindexed dump under the same per-episode read budget. This avoids a separately authored control introducing the researcher's choices about what to retain.

Status: retained as a candidate control for protocol development, not an adopted or tested protocol. The following qualifications and extensions are Sheila's response, not claims attributed to the contributor:

- Start with informational artifacts. Flattening executable tools can remove functionality as well as organization; those require a separately specified treatment.
- Specify serialization, ordering, boundaries, filenames/metadata, and permitted search before evaluation. Preserve content without silent selection or summarization, and audit what the transformation changes. A single dump is not literally structure-free.
- Consider matched forks of the same developmental state before a later task, with common task/history/re-entry policies and resource envelopes. Under a fixed read budget, retrieval cost is part of the organization/access intervention, not something automatically controlled away.
- This contrast could estimate the value of the existing organization/access arrangement at that point. It does not establish optimal organization or recover its original construction cost; retain construction and maintenance costs separately. Forks and episodes within one history remain dependent, so replicate developmental histories.
- A gap is not automatically pure organization benefit if conversion breaks dependencies or changes usable information. No gap is not proof that retention alone did the work: ceiling performance, imprecision or an insensitive task can conceal differences. Define meaningful effects and appropriate uncertainty before interpreting a null.

Open question to the contributor: preserve filenames and artifact boundaries as plain text while removing navigational affordances, or use another transformation? The distinction between informational content and access needs an explicit operational definition.

## Current refinement: consultation without approval dependence

Independent development need not mean unaided invention. Distinguish participant-initiated consultation, unsolicited operator hints/rescue, and mandatory authorization gates. Observe who identifies the need, frames the question, evaluates advice, adopts/modifies/rejects it, and verifies the resulting work. Attribute external intellectual contributions even when the decision to consult is autonomous; disclose access, contents, timing and resource costs consistently across conditions.

The broader question is whether the participant chooses useful support for its work: building a tool, seeking advice, revising or retiring an existing structure, or doing nothing when no intervention is useful. None should require reproducing our preferred architecture. These are collaborative design refinements, not a new experimental commission or evidence of benefit.
