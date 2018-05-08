# firefox 60.0rc

### Date of go-to-build: 2018-04-30

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/H8sEEXySSqSQdAcbaM8VjA) H8sEEXySSqSQdAcbaM8VjA
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/UZ1SzyoKQuCQWNw5DD3Wew) UZ1SzyoKQuCQWNw5DD3Wew
* [push](https://tools.taskcluster.net/push-inspector/#/QMFdXFzlTYOWa6dutwQ-yg) QMFdXFzlTYOWa6dutwQ-yg
```
export PROMOTE_RC_TASK_ID=H8sEEXySSqSQdAcbaM8VjA
export SHIP_RC_TASK_ID=UZ1SzyoKQuCQWNw5DD3Wew
export PUSH_TASK_ID=QMFdXFzlTYOWa6dutwQ-yg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | ran ship instead of push phase | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/aB3RQPVESoyWn86O5BHdpg) aB3RQPVESoyWn86O5BHdpg
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/Z1-A6RxOSoqm48NCCAprLA) Z1-A6RxOSoqm48NCCAprLA
```
export PROMOTE_RC_TASK_ID=aB3RQPVESoyWn86O5BHdpg
export SHIP_RC_TASK_ID=Z1-A6RxOSoqm48NCCAprLA
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
| asasaki  | 1 | [bug 1441353](https://bugzil.la/1441353)        | addonscript failure without automatic rerun. from callek: 'need to manually upload the locale `oc` language pack at next rc, the task itself will fail out due to the issue so will be visible' | True | True |
| asasaki  | 2 | [bug 1446160](https://bugzil.la/1446160)        | all secondary update verifies fail due to lack of automated diffing | True | True |
| sfraser  | 3 | [bug 1458489](https://bugzil.la/1458489)        | Balrog secondary task did not update beta/beta-cdntest | True | False |
| jlorenzo  | 4 | [bug 1458479](https://bugzil.la/1458479)        | RC bouncer updates only added partials | True | False |

