## Description

Include a few sentences describing the overall goals for this PR (pull request).

## Checklist

> Reviewing is a process done by project maintainers, mostly on a volunteer basis. We try to keep the overhead as small as possible and appreciate if you help us to do so by completing the following items. Feel free to ask in a comment if you have troubles with any of them.

For all pull requests:

- [ ] Confirm you have read the [contribution guidelines](https://github.com/geoserver/geoserver/blob/master/CONTRIBUTING.md) 
- [ ] You have sent a Contribution Licence Agreement (CLA) as necessary (not required for small changes, e.g., fixing typos in documentation)

The following are required only for core and extension modules, while they are welcomed, but not required, for community modules:
- [ ] There is a ticket in Jira describing the issue/improvement/feature (a notable exemptions is, changes not visible to end users)
- [ ] PR for bug fixes and small new features are presented as a single commit
- [ ] Commit message must be in the form "[GEOS-XYZW] Title of the Jira ticket" (export to XML in Jira generates the message in this exact form)
- [ ] New unit tests have been added covering the changes
- [ ] This PR passes all existing unit tests (test results will be reported by travis-ci after opening this PR)
- [ ] This PR passes the [QA checks](https://docs.geoserver.org/latest/en/developer/qa-guide/index.html) (QA checks results will be reported by travis-ci after opening this PR)
- [ ] Commits changing the UI, existing user workflows, or adding new functionality, need to include documentation updates

Submitting the PR does not require you to check all items, but by the time it gets merged, they should be either satisfied or inapplicable.
