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
GITHUB_SHA=624b70b2b92b35237116d4b830b59d43b591670c
GITHUB_BASE_REF=
GITHUB_HEAD_REF=
GITHUB_REF=refs/heads/adding-readme
GITHUB_REF_NAME=adding-readme
GITHUB_RUN_ID=2307890761
```
#### PR - Open new Pull Request 
```shell
GITHUB_SHA=790d083d6b48db60fecbf22746e63c42eb8db19a
GITHUB_BASE_REF=main
GITHUB_HEAD_REF=adding-readme
GITHUB_REF=refs/pull/3/merge
GITHUB_REF_NAME=3/merge
GITHUB_RUN_ID=2307891645
```
#### Merged - PR Merged to Master
```shell
GITHUB_SHA=8bee4210db8d738064c1ef22e19dbeda49267d56
GITHUB_BASE_REF=
GITHUB_HEAD_REF=
GITHUB_REF=refs/heads/main
GITHUB_REF_NAME=main
GITHUB_RUN_ID=2307892193
```
#### Workflow Dispatch
```shell
GITHUB_SHA=8bee4210db8d738064c1ef22e19dbeda49267d56
GITHUB_BASE_REF=
GITHUB_HEAD_REF=
GITHUB_REF=refs/heads/main
GITHUB_REF_NAME=main
GITHUB_RUN_ID=2307929881
```