# Classroom Agents

These are seven academic specialists for Claude Cowork and Claude Code.
You can install the plugin once, then just ask for what you need. Claude figures out which one to use.

| Ask for | You get |
| --- | --- |
| **Ms. Frizzle** | Assignments, rubrics, lessons, grading language, feedback |
| **Bobby** | A literal student who reads your assignment exactly as written and flags where it's confusing |
| **Cartman** | Harsh critique. He'll insult your draft, then fix it. |
| **Velma** | Citation cleanup: APA, MLA, Chicago, IEEE |
| **Dexter** | Research plans, evidence quality, compliance review |
| **Alfred** | Emails, announcements, memos |
| **Radar** | A written record of what changed and why, for your course file |

**BUT** you don't *have to* name one. Describe the task and Claude routes it. Naming a specialist directly also works.

## Install

Requires a Claude Pro, Max, Team, or Enterprise account, in Cowork or Claude Code.

### Cowork

1. Open Customize in the sidebar, then Plugins.
2. Click Add marketplace, enter `smu-oit/Classroom-Agents`.
3. Find Classroom Agents in the list and click Install.

### Claude Code

In a terminal session, run:

```
/plugin marketplace add smu-oit/Classroom-Agents
/plugin install classroom-agents@smu-oit
```

### Not supported

Plain claude.ai Chat doesn't run plugins. Cowork and Claude Code only.

## Check it worked

Ask:

> Design a 10th-grade discussion prompt on Macbeth.

The reply should open with "Seatbelts everyone!" That's Ms. Frizzle, and confirmation the plugin loaded.

## Multi-step paths

Ask for these by name when a task needs more than one specialist in sequence:

- **Instructional Loop**: write the assignment, then see how a student misreads it
- **Stress Test**: write it, then have Cartman attack it
- **Citation Audit**: student-style draft, then citation cleanup
- **Research to Lesson**: research plan, then teaching material
- **Research to References**: research content, then normalized citations
- **Classroom Briefing**: instructional material, then a polished message
- **Submission Grinder**: simulated submission, hard critique, then assignment repair. Longest path, save it for material that needs all three passes.
- **Decision Record**: write up what a workflow changed and why

Claude pauses between steps so you can see each one before continuing.

## A few honest notes

- **Cartman is rude on purpose.** Want kind feedback instead? Ask Ms. Frizzle.
- **Bobby doesn't research anything, even when he could.** A student who looks things up would quietly resolve your assignment's ambiguities before you ever see them. Whatever confuses Bobby is confusing because of what you wrote.
- **Bobby won't do students' homework.** He writes minimum-effort submissions so you can see what your assignment invites, and declines a request that's just "complete this for me."
- **Velma won't guess.** A missing citation field gets flagged, not invented.
- **Dexter's compliance check is a first pass, not an approval.** Anything flagged still goes to your IRB or research compliance office.
- **Radar documents from actual session reasoning, never invents a rationale.** Ask for one after you revise something. Save the write-up wherever you keep course files, since nothing here retains it for you.
- **Don't paste student records into a chat.** Strip names and ID numbers first, always.

## Updating

Cowork: reopen Customize, then Plugins, and click Update on the marketplace.
Claude Code: run `/plugin marketplace update smu-oit`, then reinstall if a new version is listed.

## Questions

Levi Sterling, OIT / SMU Guildhall. levi@smu.edu

## License

MIT. See [LICENSE](LICENSE).
