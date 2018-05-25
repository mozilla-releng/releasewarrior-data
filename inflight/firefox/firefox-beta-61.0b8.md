# firefox 61.0b8

### Date of go-to-build: 2018-05-24

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/OBmC-5-qRmecFUMlxyOTUQ) OBmC-5-qRmecFUMlxyOTUQ
* [push](https://tools.taskcluster.net/push-inspector/#/QueqhBtAR56DtWSsLBu7AA) QueqhBtAR56DtWSsLBu7AA
* [ship](https://tools.taskcluster.net/push-inspector/#/T9BOaTgtRiusbXpnLARS-g) T9BOaTgtRiusbXpnLARS-g
```
export PROMOTE_TASK_ID=OBmC-5-qRmecFUMlxyOTUQ
export PUSH_TASK_ID=QueqhBtAR56DtWSsLBu7AA
export SHIP_TASK_ID=T9BOaTgtRiusbXpnLARS-g
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1462120](https://bugzil.la/1462120)        | Bug 1462120 - Firefox 60.0esr should be in firefox.json. needs backout caused UVC failures | True | False |

