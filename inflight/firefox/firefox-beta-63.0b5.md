# firefox 63.0b5

### Date of go-to-build: 2018-09-10

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/DQt-RcMwTFOXUcl9buNZtA) DQt-RcMwTFOXUcl9buNZtA
* [push](https://tools.taskcluster.net/push-inspector/#/f36SGmzCQGG5Y9VLg5vYuA) f36SGmzCQGG5Y9VLg5vYuA
* [ship](https://tools.taskcluster.net/push-inspector/#/V9VxUG_jSguy1L_qRU5v6g) V9VxUG_jSguy1L_qRU5v6g
```
export PROMOTE_TASK_ID=DQt-RcMwTFOXUcl9buNZtA
export PUSH_TASK_ID=f36SGmzCQGG5Y9VLg5vYuA
export SHIP_TASK_ID=V9VxUG_jSguy1L_qRU5v6g
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1488396](https://bugzil.la/1488396)        | Snap push failed. It timed out after uploading the snap. Resolved by manually promoting this snap to the beta channel | True | True |

