# .github
Organization-wide GitHub workflow templates and default community files for calan-co.

## Workflow Templates

This repository hosts GitHub Actions workflow templates that should appear in the
organization workflow template picker.

Current template:

- `.github/workflow-templates/node-package-release.yml`

The template is a thin caller. The reusable implementation and setup action live
in `calan-co/cicd-shared-pipeline` and are referenced by versioned `uses:` refs.
