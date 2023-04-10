## 🤝 Code Merge Process

### 🚀 feature to development flow
1. Create a feature branch from development branch.
2. Commit and push the code daily.
3. Keep the PR size to a minimum.
4. Create a PR from feature branch to development using the standard [PR Template](./pr-templates/feature-dev-branches.md).
5. Tag the appropriate peer.
6. Wait for the sonar cloud, snyk, codebuild, gitstream checks to pass.
7. Once approved, Squash and Merge the PR.
8. Delete the branch.

### 🏗 development to testing flow
1. Create a PR from development branch to testing branch using the standard [PR Template](./pr-templates/dev-stage-branches.md).
2. Tag the appropirate Team Lead and Quality Engineer. 
3. Wait for the cypress, postman checks to pass. 
4. Once approved, Merge the PR. 

### 🧪 testing to production flow
1. Create a PR from testing branch to production branch using the standard [PR Template](./pr-templates/stage-production-branches.md).
2. Tag the appropirate Business Analyst, Business Head, Team Leads. 
4. Once approved, Merge the PR. 


### 🔥 hotfix process - scenario 1
In this scenario, the testing and production code are in sync, and there are no changes between them. Validate this by creating a PR from testing branch to production branch.

1. Create hotfix branch from testing.
2. Create a bug branch from hotfix, squash and merge the code to hotfix branch.
3. Create PR from hotfix branch to testing branch.
4. Tag the appropirate Team Lead and Quality Engineer. 
5. Wait for the cypress, postman checks to pass. 
6. Once approved, Merge the PR. 
7. Post the hotfix release, create a PR from hotfix branch to development branch, merge the code. This is done to synchronise the changes across the branches
8. Delete the hotfix branch
9. Create the postmortum report

### 🔥 hotfix process - scenario 2
In this scenario, the testing and production code are out of sync, and there changes between them. Validate this by creating a PR from testing branch to production branch. This occurs when we are close to a release and an issue has been identified in the production. Firstly, validate if hotfix is required to be done before the upcoming release. If yes, then follow `hotfix process - scenario 1`, else follow the process below

1. Create hotfix branch from production.
2. Create a bug branch from  hotfix, squash and merge the code code to hotfix branch.
3. Create PR from hotfix branch to production branch.
4. Tag the appropirate Team Lead. 
6. Once approved, Merge the PR. 
7. Post the hotfix release, create a PR from hotfix branch to testing branch and development branch, merge the code. This is done to synchronise the changes across the branches.
8. Delete the hotfix branch.
9. Create the postmortum report.