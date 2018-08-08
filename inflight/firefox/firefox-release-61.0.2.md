# firefox 61.0.2

### Date of go-to-build: 2018-08-02

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/bLKZsxWsSqO71PLziWAUTg) bLKZsxWsSqO71PLziWAUTg
* [push](https://tools.taskcluster.net/push-inspector/#/faHC2a7tRU23Z09Fpy35Iw) faHC2a7tRU23Z09Fpy35Iw
```
export PROMOTE_TASK_ID=bLKZsxWsSqO71PLziWAUTg
export PUSH_TASK_ID=faHC2a7tRU23Z09Fpy35Iw
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
| jlorenzo  | 1 | [bug none](https://bugzil.la/none)        | snap push failed. It timed out after uploading the snap. Resolved by manually promoting this snap to the candidate channel | True | False |

