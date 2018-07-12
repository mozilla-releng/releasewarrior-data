# firefox 62.0b7

### Date of go-to-build: 2018-07-09

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/CANUCVZ5RBKFbCooJ3npPw) CANUCVZ5RBKFbCooJ3npPw
* [push](https://tools.taskcluster.net/push-inspector/#/B21weAkDR1eQrkpriM-OFA) B21weAkDR1eQrkpriM-OFA
* [ship](https://tools.taskcluster.net/push-inspector/#/HnaxDhHgRImsBMmHkOjJQQ) HnaxDhHgRImsBMmHkOjJQQ
```
export PROMOTE_TASK_ID=CANUCVZ5RBKFbCooJ3npPw
export PUSH_TASK_ID=B21weAkDR1eQrkpriM-OFA
export SHIP_TASK_ID=HnaxDhHgRImsBMmHkOjJQQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1474630](https://bugzil.la/1474630)        | ship-it migration to mdc1 broke connection used by shipit_scriptworker. I manually marked the release as shipped and forced the email task to run. This unblocks QE from testing updates. | True | False |

