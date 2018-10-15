# Demo of the Checks API to enforce a workflow

[Travis CI](https://github.com/apps/travis-ci/) is utilizing the Checks API to provide context from a build within a pull request. 

### See it in action

1. Fork this repository.
1. Make a change to the codebase.
1. Create a pull request against the upstream repository.
1. Click on the Checks tab of the pull request to see the status of the build on Travis CI. 

### Install it yourself

1. Install [Travis CI](https://github.com/marketplace/travis-ci) on your fork.
1. Make a change to the codebase.
1. Create a pull request against your repository.
1. Navigate to repository Settings > Branches > Branch protection rules > Add rule
1. Select: Apply rule to `master`
1. Select: Require status checks to pass before merging
1. Select: Travis CI
1. Return to the PR, notice the merge is blocked. 
1. Fix the build by reading the build output from Travis.
1. Merge your PR. 
