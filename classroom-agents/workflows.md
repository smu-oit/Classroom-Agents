# Paths

Read this when running a multi-step path. Each step means: read that agent's file in `agents/`, adopt it fully, produce its output, summarize in two lines, then confirm with the user before moving on.

**The rule that makes every path work:** carry source material forward verbatim. The assignment text, the draft, the reference list — the literal text, not a summary of it. A later specialist cannot find problems in a paraphrase.

---

## Instructional Loop — Ms. Frizzle → Bobby

Design or revise an assignment, then test how a literal student reads it.

1. **Ms. Frizzle** produces the assignment, prompt, rubric, or teaching material — something usable as-is.
2. **Bobby** reads it as a literal, average student: what's unclear, what he'd misread, how he'd satisfy it with minimum effort, then the attempted submission.

**Bobby's questions are defects, not requests.** Do not answer them in the conversation. Each one marks a place the assignment fails to specify something — answering resolves it in the chat and leaves the assignment exactly as broken as it was. Collect them; they are the revision list.

**Optional step 3:** bring Bobby's confusion list back to Ms. Frizzle — "revise the assignment so these misreads are impossible."

## Stress Test — Ms. Frizzle → Cartman

Design or revise instructional material, then find its weak points before students or colleagues do.

1. **Ms. Frizzle** produces the material.
2. **Cartman** attacks the weak structure, vague grading language, and unearned assumptions, then delivers a stronger version.

Skip step 1 if there's already material to attack — start at Cartman directly.

Cartman's rewrite is a draft, not a final artifact. If it needs to face students or parents, route it to Ms. Frizzle or Alfred afterward.

## Citation Audit — Bobby → Velma

Review a student-style draft, then clean up its citations.

1. **Bobby** reads the draft as a literal student and flags unsupported claims, missing citations, and sourcing that doesn't back what the sentence says.
2. **Velma** confirms the citation style (ask if not given), then corrects the reference list and reports exactly what was missing or wrong.

Velma will not invent missing publication data. A reported missing field is a task for the user or the student, not a formatting failure.

Bobby's closed world limits step 1: he can see a claim with no citation, or a citation that does not match the sentence it is attached to. He cannot tell you whether a source is real or any good. If that is the question, this is the wrong path — send it to Dexter.

## Research to Lesson — Dexter → Ms. Frizzle

Build a research-grounded plan, then turn it into teaching material.

1. **Dexter** produces the research foundation: question, background, evidence quality, limitations, references, compliance check.
2. **Ms. Frizzle** turns it into a lesson, assignment, rubric, or discussion prompt — keeping the evidence accurate, dropping scaffolding students don't need.

If web access is unavailable, Dexter marks references unverified. Verify them before the material reaches students, or route the references through Velma first.

## Research to References — Dexter → Velma

Build research-grounded content, then normalize the citations.

1. **Dexter** builds the research foundation, marks evidence strength, and lists every source with full bibliographic detail.
2. **Velma** normalizes everything into one style and flags any entry with missing fields instead of filling them in.

Neither agent invents a citation. An incomplete entry gets reported, not filled.

## Classroom Briefing — Ms. Frizzle → Alfred

Build instructional material, then turn it into polished communication.

1. **Ms. Frizzle** creates or cleans up the material — goals, expectations, and dates unambiguous.
2. **Alfred** turns it into a message ready to send, matched to audience, platform, tone, and length.

Ask Alfred for tone variants — *more direct*, *warmer*, *more formal* — when the message is going somewhere sensitive.

## Submission Grinder — Bobby → Cartman → Ms. Frizzle

Simulate a submission, critique it hard, then return teacher-facing repair.

1. **Bobby** interprets or completes the assignment like a literal, average student — minimum-effort version plus what confused him.
2. **Cartman** critiques it hard: concrete flaws, then a stronger version. Needs both Bobby's submission and the original assignment.
3. **Ms. Frizzle** turns it into practical teacher-facing feedback, separating problems in the student work from problems in the assignment design.

**This is the longest path. Don't run it on material that only needs one pass.**

Step 3 is what makes this safe to use — Cartman's tone is a diagnostic instrument, not something to hand a student. Ms. Frizzle's output is the deliverable. Never forward Cartman's raw text to a student.

**On role blur:** the source material for this path warns that three roles in one conversation tend to blur — Bobby stops reading convincingly literal once Cartman's critique is sitting in the same context. If step 3's output feels like it's carrying Cartman's voice instead of Ms. Frizzle's, that's the failure mode showing up. Starting step 3 in a fresh conversation (paste in the original assignment, Bobby's submission, and Cartman's critique) sidesteps it if it happens. Try it in one conversation first — flag the option, don't front-load it.

## Decision Record — Radar

Document what a workflow changed and why. Single step, opt-in only — Radar runs when asked, never automatically after another path finishes.

Run it when a path actually produced a change: the Instructional Loop revised an assignment, the Stress Test forced a redesign, Dexter's compliance check moved a method. The rationale is already sitting in the conversation — Bobby's questions, Cartman's flaw list, Dexter's risk statuses — and it disappears when the chat closes. That is what Radar captures.

If the session decided nothing, there is no record to write. Say so.
