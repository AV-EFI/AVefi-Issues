---
name: "User Story / Anforderung"
about: "Vorlage für neue User Stories / Projektanforderungen (inkl. Kontext und Akzeptanzkriterien)"
title: ""
labels: ["UserStory", "needs-triage"]
assignees: []
---

<!--
Bitte dieses Template verwenden, wenn Sie eine neue User Story / ein neues Feature für AV-efi anlegen.
Füllen Sie die Bereiche so vollständig wie möglich aus. Verwenden Sie für den Title das Projekt-Kürzel:
Beispiel: DQ-09: Harmonisierung von Genre „Dokumentation“ / „Documentary“
-->

# Title with Shortcode
DQ-09: Harmonisierung von Genre „Dokumentation“ / „Documentary“

---

## User Story
Als <Rolle>  
möchte ich, dass <Ziel / Funktionalität>  
damit <Nutzen / Grund>.

Beispiel:
Als Datenpflegender oder Metadaten-Qualitätsverantwortlicher  
möchte ich, dass die Gattungs- und Genre-Bezeichnungen wie „Dokumentation“ und „Documentary“ harmonisiert werden,  
damit die Suchfacetten, Statistiken und Darstellungen konsistent und fachlich korrekt sind.

---

## Kontext / Hintergrund
- Quelle / Reporter: <Name / Gruppe>
- Relevante Diskussion / Link: <Link zu Konversation, Dokumenten, Tickets>
- Kurzbeschreibung der Situation und bisheriger Befund:
  - z. B. Unterschiedliche Schreibweisen / Sprachen führen zu falscher Facettenaggregation, doppelten Filtern, inkonsistenter Anzeige
- Unklarheiten / offene Fragen (markieren Sie ggf. mit "UNSCHARF"):
  - z. B. Unklar, ob Normalisierung im Frontend oder Backend erfolgen soll → **UNSCHARF**

---

## Akzeptanzkriterien (gegeben / wenn / dann)
- Given <Vorbedingung>
  When <Aktion>
  Then <erwartetes Ergebnis>

Beispiele (kopieren / anpassen):
- Given ein Werk oder eine Manifestation enthält Genre- oder Gattungsangaben  
  When die Werte in der Oberfläche angezeigt werden  
  Then werden international äquivalente Werte („Dokumentation" / „Documentary") einheitlich und harmonisiert dargestellt.

- Given ein Nutzer filtert nach Genre/Gattung  
  When „Dokumentation" oder „Documentary" gewählt wird  
  Then erhält er denselben aggregierten Filtereffekt (keine Doppelwerte).

- Given bestehende Daten weisen gemischte Varianten auf  
  When die Liste der Genres im Filter erzeugt wird  
  Then erscheint nur ein vereinheitlichter Wert.

- Given die Metadatenfachgruppe bestimmt zukünftige Schreibweisen  
  When neue Daten importiert oder synchronisiert werden  
  Then wird dieselbe Normalisierung automatisch angewendet.

---

## Technische / Implementationshinweise (optional)
- Betroffene Bereiche: Frontend / Backend / Datenbank / Import-Process / Indexing
- Vorschlag: <z. B. Mapping-Tabelle, Normalisierungs-Service, Index-time-normalization>
- Performance- oder Migrationskonsequenzen: <abschätzen oder verlinken>
- Security / Privacy Hinweise: <wenn relevant>

---

## Test & Verifikation
- Testfälle / Schritte zum Überprüfen der Akzeptanzkriterien:
  - [ ] Beispiel-Datensatz mit "Documentary" anzeigen → Darstellung: "Dokumentation"
  - [ ] Filteraggregation → keine Doppelwerte
  - [ ] Import neuer Daten → Normalisierung greift automatisch
- Verantwortlicher QA / Reviewer: <Person / Team>

---

## Labels / Priorisierung (zur Verwendung durch Maintainer)
- Empfohlene Labels: Epic:<Name>, Frontend / Backend, MUSTHAVE / WONTHAVE / NICE-TO-HAVE, PUBLIC-RELEASE (falls zutreffend)
- Story-Prefix: z. B. RD-, NC-, BR-, RECS-, DQ-, LIC-, EXPORT- (verwenden Sie vorhandene Konventionen)

---

## Sonstiges / Links
- Relevante Issues / PRs: #<nummer>, <link>
- Verwandte Dokumente: <link>
