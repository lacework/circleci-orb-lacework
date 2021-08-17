<img src="https://techally-content.s3-us-west-1.amazonaws.com/public-content/lacework_logo_full.png" width="600">

# Lacework Orb for CircleCI
[![CircleCI Build Status](https://circleci.com/gh/lacework/circleci-orb-lacework.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/lacework/circleci-orb-lacework) 
![Orb Version Badge](https://badges.circleci.com/orbs/lacework/lacework.svg)
[![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

Use the Lacework Orb to add security into your CI/CD pipeline. You can run vulnerability scans and other operations.

## Usage

Example use-cases are provided on the orb [registry page](https://circleci.com/orbs/registry/orb/lacework/lacework#usage-examples). Source for these examples can be found within the [src/examples](src/examples) directory.

## Resources

[Lacework Orb Registry Page](https://circleci.com/orbs/registry/orb/lacework/lacework) - Official registry page of this orb for all versions, executors, commands, and jobs described.  
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.  

### How To Contribute

We welcome [issues](https://github.com/lacework/circleci-orb-lacework/issues) to and [pull requests](https://github.com/lacework/circleci-orb-lacework/pulls) against this repository!

To publish a new production version:
* Create a PR to the `Alpha` branch with your changes. This will act as a "staging" branch.
* When ready to publish a new production version, create a PR from `Alpha` to `master`. The Git Subject should include `[semver:patch|minor|release|skip]` to indicate the type of release.
* On merge, the release will be published to the orb registry automatically.

For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).
