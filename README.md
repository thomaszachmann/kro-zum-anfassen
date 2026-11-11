# kro zum Anfassen – Begleitcode

Begleitcode zum Buch **kro zum Anfassen** – eigene Plattform-APIs für Kubernetes mit
kro (Kube Resource Orchestrator): ResourceGraphDefinitions, SimpleSchema, CEL,
Readiness, Collections, externe Referenzen, RGD-Chaining, Rechte und GitOps. Teil der
Reihe IT-Trainingslager von Thomas Zachmann.

Buchseite: https://it-trainingslager.de/buecher/kro

Der Code begleitet das Buch; Erklärungen und Übungen stehen im Buch. Die Dateien
schreibst du im Buch selbst – hier liegen die fertigen Fassungen zum Vergleichen und
die kaputten Dateien für den Wettkampf. Alle Schlüssel und Passwörter sind Laborwerte –
nie in Produktion verwenden.

Getestet mit k3s 1.37.2, Helm 4.3.1, kro 0.10.0 und notes-api 0.5.1.

## Inhalt

- `loesung/tagNN/` – fertige Dateien jedes Trainingstags (RGDs, Instanzen, Rollen,
  Werte für das Chart, Helm-Chart und Kustomize-Variante an Tag 13)
- `loesung/pruefung/` – Lösungen der Abschlussprüfung (Anhang B)
- `wettkampf/rundeN/` – Dateien, mit denen die Runden in Tag 15 beginnen
- `wettkampf/loesung/` – reparierte Fassungen

## Schnellstart

```bash
git clone https://github.com/thomaszachmann/kro-zum-anfassen.git ~/kro-lab/code
diff ~/kro-lab/tag04/notesapp-rgd.yaml ~/kro-lab/code/loesung/tag04/notesapp-rgd.yaml
```

Details stehen im Kapitel „Tag 0“ des Buchs.

## Lizenz

Code: MIT (siehe LICENSE). Buchtexte, Abbildungen und Cover sind nicht Teil dieses Repos
und nicht lizenziert.
