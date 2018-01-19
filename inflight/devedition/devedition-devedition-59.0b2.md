# devedition 59.0b2

### Date of go-to-build: 2018-01-18

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/EdcS4iZ_Sr29dYSC59JkzQ)
[task group](https://tools.taskcluster.net/push-inspector/#/eqTuHQPvRT-Gz1-dlZWiRA)
[task group](https://tools.taskcluster.net/push-inspector/#/biOJaam7Q3aLnBzzSmcfGA)
[task group](https://tools.taskcluster.net/push-inspector/#/e5G50QyjQ7uV1PrEqfrdmA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#publish-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  - Manually version bump, and mark as shipped (due to Bug 1431152)

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | mirroring aurora watersheds were added to aurora-localtest: rules 728 and 726. This broke UV as UV wasn't prepared for them. I moved them to low priority so they won't get hit in Balrog. Fix is to fix up patcher configs so UV expects them. We should also discuss if those watersheds are needed at all anymore | False | True |

