# ADR for decision on CI/CD Platform
---
## Context
- As a group we need to select a tool for our CI/CD pipelines

## Decision
- We have agreed that we will use GitHub Actions to create our build and deploy pipelines

## Rationale
- We were already using GitHub as our source control manager, so it made sense to use Actions for our pipelines

## Implementation 
- We will create skeleton pipelines in GitHub Actions
- We will create GitHub Actions to provide checks on the Pull Requests

## Anticpated Outcomes
- Simplified workflows as the pipelines and the code will be in the same place
- Better code quality since we can easily integrate code and workflows, and leverage the build-in GitHub tools

## Conclusion
- A combined repository and CI/CD platform will enable us to create a integrated workflow from source code pull requests to build and deploy to our staging and production environments

  
