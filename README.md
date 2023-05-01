# IncidentCAD - Kubernetes Manifests

This repo should be the main source of truth for the IncidentCAD Kubernetes Configuration. 

## Sections

- Helmsman


## Helmsman

Helm Charts are deployed using Helmsman. The helmsman folder contains a root helmsman.yaml file that contains the Desired State File or DSF and subfolders for each Helm Chart containing a values.yaml file.
A values.yaml file should be created regardless if there are any overrides.

### Applying changes to Helmsman

```bash
helmsman --apply -f path/to/helmsman.yaml
```
