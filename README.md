# Github Actions Variables

### The purpose of this repository 
Testing the Github Actions (GHA) variables values as progressing through the "gitops" pipeline.
1. On feature branch creation
2. Pull Request creation
3. Pull Request merged to master
4. Manual Workflow dispatch

### Background 
As a Gitlab CI/CD user and developer that start to use GHA, I wanted to learn the mechanics of the default environment variables in GHA. 
Using the power of the default environment variables can assist the building of a robust CI/CD.

### Outputs
#### Feature - push to branch
```shell
GITHUB_SHA=9891f4dcaa6a1bf792d29e53b53f83766d79e314
GITHUB_BASE_REF=
GITHUB_HEAD_REF=
GITHUB_REF=refs/heads/adding-readme
GITHUB_REF_NAME=adding-readme
GITHUB_RUN_ID=2307860296
```
#### PR - Open new Pull Request 
```shell
GITHUB_SHA=2e71b2975677ffaae34a5736d5cb901e5d707594
GITHUB_BASE_REF=main
GITHUB_HEAD_REF=adding-readme
GITHUB_REF=refs/pull/1/merge
GITHUB_REF_NAME=1/merge
GITHUB_RUN_ID=2307861256
```
#### Merged - PR Merged to Master
```shell


```
#### Workflow Dispatch