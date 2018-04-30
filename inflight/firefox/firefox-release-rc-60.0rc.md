# firefox 60.0rc

### Date of go-to-build: 2018-04-30

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/aB3RQPVESoyWn86O5BHdpg) aB3RQPVESoyWn86O5BHdpg
```
export PROMOTE_RC_TASK_ID=aB3RQPVESoyWn86O5BHdpg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1441353](https://bugzil.la/1441353)        | addonscript failure without automatic rerun | False | True |
| asasaki  | 2 | [bug 1446160](https://bugzil.la/1446160)        | all secondary update verifies fail due to lack of automated diffing | False | True |

