---
name: "BUG: KURZER BUGTITEL"
description: "Bug Report Template"
about: "Fehlerbericht ausfüllen"
title: "BUG: KURZER BUGTITEL"
labels: ["bug"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        Bitte fülle die folgenden Abschnitte sorgfältig aus. Je genauer die Angaben, desto schneller kann der Fehler reproduziert und behoben werden.

  - type: textarea
    id: beschreibung
    attributes:
      label: Fehlerbeschreibung
      description: Kurze Beschreibung des beobachteten Fehlers
      value: |
        Bitte beschreibe den Fehler möglichst klar und präzise.
    validations:
      required: true

  - type: textarea
    id: schritte
    attributes:
      label: Schritte zur Reproduktion
      description: Schritt-für-Schritt-Anleitung, wie der Fehler ausgelöst werden kann
      value: |
        1.  
        2.  
        3.  
        Erwartet:  
        Tatsächlich:
    validations:
      required: true

  - type: textarea
    id: erwartetes-verhalten
    attributes:
      label: Erwartetes Verhalten
      description: Was sollte passieren?
      value: |
        Bitte beschreibe das erwartete Verhalten.
    validations:
      required: true

  - type: textarea
    id: technischer-kontext
    attributes:
      label: Technischer Kontext
      description: Browser, Gerät, Umgebung (Dev/Staging/Prod), relevante Logs
      value: |
        Browser:  
        System:  
        Umgebung:  
        Relevante Logs:
    validations:
      required: false

  - type: checkboxes
    id: auswirkungen
    attributes:
      label: Auswirkungen / Schweregrad
      options:
        - label: Blocker (System kann nicht genutzt werden)
        - label: Hoch (kritische Funktion beeinträchtigt)
        - label: Mittel (stört Arbeitsabläufe)
        - label: Niedrig (kosmetisch / Edge Case)
    validations:
      required: false

  - type: textarea
    id: test-hinweise
    attributes:
      label: Testfälle / Regression
      description: Hinweise für QA, mögliche betroffene Bereiche
      value: |
        Bitte zusätzliche Testfälle oder Regression-Hinweise ergänzen.

  - type: textarea
    id: links
    attributes:
      label: Referenzen / Links
      description: Relevante Issues, PRs oder Confluence-Seiten
      value: |
        -
projects:
  - AV-EFI/1
---
