# devedition 63.0b6

### Date of go-to-build: 2018-09-13

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/NodILVtpQHGJ05B6-4nvfQ) NodILVtpQHGJ05B6-4nvfQ
* [push](https://tools.taskcluster.net/push-inspector/#/UtbRw8RHS8iz_NPg29X8ow) UtbRw8RHS8iz_NPg29X8ow
* [ship](https://tools.taskcluster.net/push-inspector/#/HfQILiUtQomwoUzDiIdniA) HfQILiUtQomwoUzDiIdniA
```
export PROMOTE_TASK_ID=NodILVtpQHGJ05B6-4nvfQ
export PUSH_TASK_ID=UtbRw8RHS8iz_NPg29X8ow
export SHIP_TASK_ID=HfQILiUtQomwoUzDiIdniA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| rail  | 1 | [bug none](https://bugzil.la/none)        | Pushing to aurora failed, because b5 was never published and balrog rejected to accept a conflicting change. Had to delete the pending change and rerun the task. | False | True |

