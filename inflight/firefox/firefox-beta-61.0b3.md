# firefox 61.0b3

### Date of go-to-build: 2018-05-07

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/bpgJFUOIReqo1AFZY2Vc4w) bpgJFUOIReqo1AFZY2Vc4w
* [push](https://tools.taskcluster.net/push-inspector/#/c6uqUd5MSkauX9P_CglMR) c6uqUd5MSkauX9P_CglMR
```
export PROMOTE_TASK_ID=bpgJFUOIReqo1AFZY2Vc4w
export PUSH_TASK_ID=c6uqUd5MSkauX9P_CglMR
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | beetmover-repackage-linux64-asan-reporter-nightly/opt shouldn't be part of the promote graph | False | True |

