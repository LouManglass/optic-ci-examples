# optic-ci-examples

Example of a project with OpenAPI files representing an API.

Branches are used for works in progress, to compare to the main branch.

The `main` branch `openapi.yaml` is the baseline OpenAPI file (found in `resources/baseline.openapi.yaml`). The `main` branch is always our baseline - where we start our journey. We do work in branches, and compare those changes against what's in `main`. Each branch is part of a PR that contains changes to the OpenAPI file, and the corresponding check output.