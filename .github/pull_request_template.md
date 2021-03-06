<!--
Thank you for working on PD! Please read PD's [CONTRIBUTING](https://github.com/pingcap/pd/blob/master/CONTRIBUTING.md) document **BEFORE** filing this PR.
PR Title Format:
1. pkg [, pkg2, pkg3]: what's changed
2. *: what's changed
-->

### What problem does this PR solve? <!--add the issue link with summary if it exists-->


### What is changed and how it works?


### Check List <!--REMOVE the items that are not applicable-->

Tests <!-- At least one of them must be included. -->

 - Unit test
 - Integration test
 - Manual test (add detailed scripts or steps below)
 - No code

Code changes

 - Has configuration change
 - Has HTTP API interfaces change (Don't forget to [add the declarative for API](https://github.com/pingcap/pd/blob/master/docs/development.md#updating-api-documentation))
 - Has persistent data change

Side effects

 - Possible performance regression
 - Increased code complexity
 - Breaking backward compatibility

Related changes

- PR to update `pingcap/docs`/`pingcap/docs-cn`:
- PR to update `pingcap/tidb-ansible`:
- Need to cherry-pick to the release branch

### Release note <!-- bugfixes or new feature need a release note -->
