# Working Notes

## User preferences (carried over from the Isaiah study, 2026-08-01)
- Mission: personal depth, not teaching prep or apologetics mastery. Matthew runs as a companion track alongside the ongoing Isaiah study.
- Method foundations already taught in Isaiah 0001-0051: assume observation/interpretation/application, refresh briefly, define Gospel-specific terms (Synoptic, discourse, kingdom of heaven) on first use. Glossary adherence matters.
- 20-30 min daily. Keep lessons small: one passage unit, one win.
- ESV quotations throughout. Owned: MacArthur Study Bible + Olive Tree.
- Theological frame: Reformed. Postmil (Durbin) is the home lens; MacArthur (premil/futurist) and White (amil) alternatives flagged honestly at the big passages. Fork checkpoints: Matt 5:17-20 (law), ch. 13 (kingdom parables), 16:18-19 (church and keys), ch. 23-25 (Olivet Discourse, the big one: postmil partial-preterist home reading vs MSB's consistently futurist reading, argued from the text), 28:18-20 (Great Commission).
- Workflow: user reads passage in ESV FIRST, jots observations, then opens lesson. Lessons open by asking what they observed, then check.
- Retention: memory verses (~10, one per unit, listed in reference/memory-verses.html) + spaced recall quiz at the top of each lesson.
- Community prompts: yes, tied to church life.
- Build each lesson fully (no stubs). Course generated in batches as the learner progresses (zone of proximal development requires seeing learning records first); curriculum map in reference/matthew-book-map.html covers all 28 chapters up front.
- No em dashes in any written content (user global rule). MacArthur quoted text kept verbatim, including its own punctuation.

## Course conventions
- Lesson files: lessons/NNNN-slug.html, numbered sequentially.
- Every lesson links assets/course.css and assets/quiz.js, opens with a recall quiz, ends with: application, memory verse work (when active), primary source recommendation, "ask your teacher" reminder, and links to reference docs.
- Quiz answer options: keep all options the same word count so formatting gives no clue.
- Reference docs are the durable artifacts; lessons point into them.
- reference/macarthur-notes.html = user's personal copy of their owned MacArthur Study Bible Matthew notes (pasted by user 2026-08-01), per-chapter anchors ch01-ch28. PRIVATE USE ONLY: never publish as an Artifact or share beyond this workspace; it is copyrighted material the user owns. Lessons may deep-link (#chNN) and should engage its futurist readings critically per the course's postmil home lens (caveat card is in the file header). Quoted text kept verbatim, including its own punctuation.
- Shared left sidebar: assets/nav.js (manifest-driven) + styles in course.css. EVERY page includes `<script src="../assets/nav.js" defer></script>` after the course.css link. When adding a lesson: add one entry to the LESSONS array in nav.js, nothing else. Mark-complete progress persists in localStorage key `matthew-study-progress` (per browser).
- Theme color #2e3a7a (royal blue, the King motif); Isaiah course uses #7a2e2e. Icons generated locally (letter M).

## Pacing ledger
- Lesson 0001 built: The Big Picture of Matthew (orientation; activates memory verse 1, Matt 1:21; assigns Matt 1:1-17 reading).
- Memory verse 1 (1:21) active. Next verse: 2 (4:4), activates in Unit 1 at the temptation passage.
- Eschatology fork checkpoints ahead: 5:17-20, ch. 13, 16:18-19, ch. 23-25 (main), 28:18-20.
- Next lesson: 0002, Matthew 1:1-17 (the genealogy: son of David, son of Abraham; the five women; 3x14 structure).
- Estimated full course: ~70 lessons over ~4-6 months at daily cadence (long chapters split; discourses get multiple lessons).
