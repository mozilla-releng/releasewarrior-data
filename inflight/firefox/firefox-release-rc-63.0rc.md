# firefox 63.0rc

### Date of go-to-build: 2018-10-03

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-10-23 - [bug 1495844](https://bugzil.la/1495844): We will need to update the firefox-election-edition bouncer URLs manually after shipping.

## Build 2  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/SObDu5XHQTGgFHTOz4IuXQ) SObDu5XHQTGgFHTOz4IuXQ
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/K8ZgBTa4QG2dBvLqS4tuww) K8ZgBTa4QG2dBvLqS4tuww
* [push](https://tools.taskcluster.net/push-inspector/#/bgHpPUB2QZ2BcLZd7W5Zlw) bgHpPUB2QZ2BcLZd7W5Zlw
* [ship](https://tools.taskcluster.net/push-inspector/#/ftxWHWbtQEmPMUtr0vlKlw) ftxWHWbtQEmPMUtr0vlKlw
```
export PROMOTE_RC_TASK_ID=SObDu5XHQTGgFHTOz4IuXQ
export SHIP_RC_TASK_ID=K8ZgBTa4QG2dBvLqS4tuww
export PUSH_TASK_ID=bgHpPUB2QZ2BcLZd7W5Zlw
export SHIP_TASK_ID=ftxWHWbtQEmPMUtr0vlKlw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [x] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [x] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | release-mark-as-started bustage; known; fix landing | True | False |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | hg issue for UpSVfWizQsCldgTfs_w-jQ | True | True |
| nthomas  | 3 | [bug 1501141](https://bugzil.la/1501141)        | final verify not actually testing anything, then just testing mac | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/Xei1zndyT_Ov6arEk1doTw) Xei1zndyT_Ov6arEk1doTw
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/H0h2Wk2LQI2KonEHY2HcSg) H0h2Wk2LQI2KonEHY2HcSg
```
export PROMOTE_RC_TASK_ID=Xei1zndyT_Ov6arEk1doTw
export SHIP_RC_TASK_ID=H0h2Wk2LQI2KonEHY2HcSg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | rr3 not running | True | False |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | missing shipit-dev scope; the mark-as-started task should point at production for esr and release | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | cron-check-bouncer is running in the release graph, including devedition | True | True |
| asasaki  | 4 | [bug none](https://bugzil.la/none)        | linux64 l10n lij upload issue? script exited fine, task failed, missing a tarball | True | True |
| asasaki  | 5 | [bug none](https://bugzil.la/none)        | hg clone issue again | True | True |

