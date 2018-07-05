# firefox 61.0.1

### Date of go-to-build: 2018-07-04

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/DgylP9ewT_2-SLCclTex0A) DgylP9ewT_2-SLCclTex0A
* [push](https://tools.taskcluster.net/push-inspector/#/c2ZFX1fVRXK2Yb4dIEn97w) c2ZFX1fVRXK2Yb4dIEn97w
```
export PROMOTE_TASK_ID=DgylP9ewT_2-SLCclTex0A
export PUSH_TASK_ID=c2ZFX1fVRXK2Yb4dIEn97w
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1473286](https://bugzil.la/1473286)        | Action task couldn't start: git@github.com:mozilla-partners/playanext doesn't exist | True | False |
| jlorenzo  | 2 | [bug 1473288](https://bugzil.la/1473288)        | release-runner3 couldn't kick release off: Can't download actions.json | True | True |

