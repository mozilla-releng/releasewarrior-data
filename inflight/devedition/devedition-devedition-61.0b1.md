# devedition 61.0b1

### Date of go-to-build: 2018-04-28

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/UiZl2TE_QgOObsX265SPtg) UiZl2TE_QgOObsX265SPtg
* [push](https://tools.taskcluster.net/push-inspector/#/LKKnPp1QQOG3KFd89G1IPw) LKKnPp1QQOG3KFd89G1IPw
```
export PROMOTE_TASK_ID=UiZl2TE_QgOObsX265SPtg
export PUSH_TASK_ID=LKKnPp1QQOG3KFd89G1IPw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| sfraser  | 1 | [bug 1458555](https://bugzil.la/1458555)        | Beetmover had the wrong S3 bucket configured for devedition | False | True |

