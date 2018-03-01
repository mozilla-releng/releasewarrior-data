# devedition 59.0b12

### Date of go-to-build: 2018-02-22

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[promote](https://tools.taskcluster.net/push-inspector/#/RxpwQLikS22S-VNoZcgzng)
[push](https://tools.taskcluster.net/push-inspector/#/Wn10U6j5Qf6QrlylAzzhxQ)
[ship](https://tools.taskcluster.net/push-inspector/#/KhvsulMXT8O19_stq2aHYA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - publish release tasks
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1438906](https://bugzil.la/1438906)        | UV osx failed again with new patch from bug. Backed out | True | False |
| jlund  | 2 | [bug none](https://bugzil.la/none)        | bouncer check failing | True | True |
| mihaitabara  | 3 | [bug none](https://bugzil.la/none)        | Failed version bump. Seems like we always need to rerun this because of race condition with the firefox counterpart." | True | True |

