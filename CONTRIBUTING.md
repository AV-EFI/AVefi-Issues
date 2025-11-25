# CONTRIBUTING — AV-efi User Stories & Issue-Vorlagen

Danke, dass du zur Pflege der Projektanforderungen beiträgst. Dieses Repository sammelt User Stories und Epics als GitHub Issues. Damit alle Beiträge konsistent und nützlich sind, bitte die folgenden Richtlinien beachten.

Kurzüberblick
- User Stories werden als Issues angelegt.
- Verwende die Issue-Vorlage "User Story / Anforderung" (.github/ISSUE_TEMPLATE/user_story.md).
- Titel: Nutze ein Kürzel + laufende Nummer und eine kurze Beschreibung (z. B. RD-01: Rollen- & Rechteverwaltung ...).

Wie du eine neue Story anlegst
1. Klicke auf "New issue" und wähle die Vorlage "User Story / Anforderung".
2. Fülle alle Sektionen aus:
   - Title with Shortcode (z. B. RD-01: ...)
   - User Story (Rolle / Ziel / Nutzen)
   - Kontext (Quelle, Links, offene Fragen)
   - Akzeptanzkriterien (konkret, testbar, im Given/When/Then-Format)
   - Technische Hinweise (optional)
3. Weise passende Labels zu (UserStory, Frontend/Backend, Epic:..., Priorität). Falls du keine Labels setzen kannst, markiere das Issue mit "needs-triage".

Akzeptanzkriterien — Leitfaden
- Formuliere testbare Kriterien (Given/When/Then).
- Vermeide vage Formulierungen wie "besser" oder "schneller" ohne Messgröße.
- Falls ein Kriterium unscharf ist (z. B. Architekturentscheidung offen), kennzeichne mit "UNSCHARF".

Label-Konventionen (Kurzreferenz)
- UserStory — alle Stories
- Epic:<Name> — Gruppierung zu größeren Themen
- Frontend / Backend / Accessibility / Datenqualität / Technical-Blocker
- Priorität: MUSTHAVE / NICE-TO-HAVE / WONTHAVE
- Öffentlichkeitsrelevant: PUBLIC-RELEASE

Workflow & Verlinkungen
- Verlinke Implementierungs-PRs, Commits oder Skripte anhand der Issue-Nummer (#123).
- Verwende Issues als Ausgangspunkt für Sprintplanung / Board-Items.
- Bei größeren Epics: erstelle ein übergeordnetes Issue mit dem Label Epic:<Name> und verlinke Child-Issues.

Review & Pflege
- Maintainer prüfen Issues auf Vollständigkeit und passen Labels / Titel ggf. an.
- Bei inhaltlichen Änderungen: ergänze den Issue-Body mit Datum und Kurznotiz der Änderung.

Support / Fragen
- Für Rückfragen zur Formulierung oder Label-Konvention: erwähne @steffolino oder öffne ein kurzes Meta-Issue.

Vielen Dank für deine Unterstützung — klare, gut strukturierte Issues machen das Team schneller und effektiver.

---

# CONTRIBUTING — AV-efi User Stories & Issue Templates (English)

Thank you for contributing to the project's requirements. This repository collects user stories and epics as GitHub issues. To keep contributions consistent and useful, please follow the guidelines below.

Overview
- User stories are created as issues.
- Use the "User Story / Anforderung" issue template (.github/ISSUE_TEMPLATE/user_story.md).
- Title: Use a shortcode + incremental number and a short description (e.g. RD-01: Roles & permissions ...).

How to create a new story
1. Click "New issue" and choose the "User Story / Anforderung" template.
2. Fill in all sections:
   - Title with Shortcode (e.g. RD-01: ...)
   - User Story (role / goal / benefit)
   - Context (source, links, open questions)
   - Acceptance Criteria (concrete, testable, in Given/When/Then format)
   - Technical notes (optional)
3. Assign appropriate labels (UserStory, Frontend/Backend, Epic:..., priority). If you cannot assign labels, tag the issue with "needs-triage".

Acceptance criteria — guidance
- Write testable criteria using Given/When/Then.
- Avoid vague terms like "better" or "faster" without measurable targets.
- If a criterion is unclear (e.g. architecture decision pending), mark it as "UNSCHARF".

Label conventions (quick reference)
- UserStory — all stories
- Epic:<Name> — group related stories under a common epic
- Frontend / Backend / Accessibility / DataQuality / Technical-Blocker
- Priority: MUSTHAVE / NICE-TO-HAVE / WONTHAVE
- Public release relevance: PUBLIC-RELEASE

Workflow & linking
- Link implementation PRs, commits or scripts to the issue using the issue number (#123).
- Use issues as input for sprint planning and board items.
- For large epics: create a parent issue with the label Epic:<Name> and link child issues.

Review & maintenance
- Maintainers review issues for completeness and may adjust labels/titles.
- When changing story content, add a note with date summarizing the change to the issue body.

Support / questions
- For questions about wording or label conventions: mention @steffolino or open a short meta issue.

Thanks for your contribution — clear, well-structured issues help the team move faster and deliver better results.
