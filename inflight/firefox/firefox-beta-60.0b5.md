# firefox 60.0b5

### Date of go-to-build: 2018-03-19

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-03-18 - [bug 1445593](https://bugzil.la/1445593): All scriptworker instances had their *script bumped, for refactoring. Changes happened at the beginning of scripts, hence if a failure is a fallout, it must be at the beginning of the run. No behavior is expected to change [jlorenzo]

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Xdukuwf8SLygzvCcJ5layA) Xdukuwf8SLygzvCcJ5layA
* [push](https://tools.taskcluster.net/push-inspector/#/EKDdG097Q1uJUeAF-VfLsw) EKDdG097Q1uJUeAF-VfLsw
* [ship](https://tools.taskcluster.net/push-inspector/#/BwzFhcODT629rHOjMn9V4w) BwzFhcODT629rHOjMn9V4w


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1431789](https://bugzil.la/1431789)        | 502: bad gateway for balrog submit-locale tasks | True | False |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | partials-pt-PT-win64-nightly/opt failed; rerun fixed | True | False |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | snap image failed | False | True |
| asasaki  | 4 | [bug none](https://bugzil.la/none)        | bouncer check failed; rerun fixed | True | False |

