# devedition 63.0b8

### Date of go-to-build: 2018-09-20

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/b9gZhMMGTzmSEPI-mXuwbA) b9gZhMMGTzmSEPI-mXuwbA
* [push](https://tools.taskcluster.net/push-inspector/#/ZbedeifrQim2SbiVy1ynnw) ZbedeifrQim2SbiVy1ynnw
* [ship](https://tools.taskcluster.net/push-inspector/#/EI2zrQJ7T1OyrCoOn870Vg) EI2zrQJ7T1OyrCoOn870Vg
```
export PROMOTE_TASK_ID=b9gZhMMGTzmSEPI-mXuwbA
export PUSH_TASK_ID=ZbedeifrQim2SbiVy1ynnw
export SHIP_TASK_ID=EI2zrQJ7T1OyrCoOn870Vg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| mtabara  | 1 | [bug 1493071](https://bugzil.la/1493071)        | bouncer check mistakenly runs as part of the push graph(s) | True | True |

