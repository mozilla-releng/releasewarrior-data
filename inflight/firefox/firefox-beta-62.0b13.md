# firefox 62.0b13

### Date of go-to-build: 2018-07-30

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/OJpUEhpzT3efefk9onqDtA) OJpUEhpzT3efefk9onqDtA
* [push](https://tools.taskcluster.net/push-inspector/#/cU_pxtbcTYi4au7ZeNqsfA) cU_pxtbcTYi4au7ZeNqsfA
* [ship](https://tools.taskcluster.net/push-inspector/#/LAuuaRwERmKkDfT374xiyg) LAuuaRwERmKkDfT374xiyg
```
export PROMOTE_TASK_ID=OJpUEhpzT3efefk9onqDtA
export PUSH_TASK_ID=cU_pxtbcTYi4au7ZeNqsfA
export SHIP_TASK_ID=LAuuaRwERmKkDfT374xiyg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1470232](https://bugzil.la/1470232)        | Firefox failed to tag release, due to verification and devedition already having bumped version. | True | True |

