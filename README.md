# kro hands-on – Companion Code

Companion code for the book **kro hands-on** (German edition: *kro zum Anfassen*) – your own
platform APIs for Kubernetes with kro (Kube Resource Orchestrator): ResourceGraphDefinitions,
SimpleSchema, CEL, readiness, collections, external references, RGD chaining, permissions and
GitOps. Part of Thomas Zachmann's IT Drills series.

Book page: https://itdrills.com/books/kro · German edition: https://it-trainingslager.de/buecher/kro

The code accompanies the book; explanations and exercises are in the book. You write the files
yourself as you work through the book – this repo holds the finished versions for comparison and
the broken files for the competition. All keys and passwords are lab values – never use them in
production.

Tested with k3s 1.37.2, Helm 4.3.1, kro 0.10.0 and notes-api 0.5.1.

## Contents

- `loesung/tagNN/` – finished files of each training day (RGDs, instances, roles,
  chart values, Helm chart and Kustomize variant on Day 13)
- `loesung/pruefung/` – solutions to the final exam (Appendix B)
- `wettkampf/rundeN/` – files the rounds of Day 15 start with
- `wettkampf/loesung/` – repaired versions

## Quick start

```bash
git clone https://github.com/thomaszachmann/kro-zum-anfassen.git ~/kro-lab/code
diff ~/kro-lab/tag04/notesapp-rgd.yaml ~/kro-lab/code/loesung/tag04/notesapp-rgd.yaml
```

Details are in the book's "Day 0" chapter.

## License

Code: MIT (see LICENSE). Book text, figures and cover are not part of this repo and are not licensed.
