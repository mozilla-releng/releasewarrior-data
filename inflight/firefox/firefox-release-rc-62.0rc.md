# firefox 62.0rc

### Date of go-to-build: 2018-06-04

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-08-21 - [bug none](https://bugzil.la/none): We need to properly publish en-CA for this release. More information in bug 1465064

## Build 2  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/An7X0OORTaC-NUrp-7AG6g) An7X0OORTaC-NUrp-7AG6g
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/JB3ZYdXXRMW_DC6u02HQpQ) JB3ZYdXXRMW_DC6u02HQpQ
* [push](https://tools.taskcluster.net/push-inspector/#/UQd6GS1uRxqTZDpbG8e43Q) UQd6GS1uRxqTZDpbG8e43Q
* [ship](https://tools.taskcluster.net/push-inspector/#/BdgTRHu1SxeOfQhbD2ZLXg) BdgTRHu1SxeOfQhbD2ZLXg
```
export PROMOTE_RC_TASK_ID=An7X0OORTaC-NUrp-7AG6g
export SHIP_RC_TASK_ID=JB3ZYdXXRMW_DC6u02HQpQ
export PUSH_TASK_ID=UQd6GS1uRxqTZDpbG8e43Q
export SHIP_TASK_ID=BdgTRHu1SxeOfQhbD2ZLXg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [x] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1488396](https://bugzil.la/1488396)        | Snap push failed. It timed out after uploading the snap. Resolved by manually promoting this snap to the candidate channel | True | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/clacPCDwRYWZJHdZzRP0cA) clacPCDwRYWZJHdZzRP0cA
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/INov5AXESsKrxpUscPS5Gg) INov5AXESsKrxpUscPS5Gg
```
export PROMOTE_RC_TASK_ID=clacPCDwRYWZJHdZzRP0cA
export SHIP_RC_TASK_ID=INov5AXESsKrxpUscPS5Gg
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
| jlorenzo  | 1 | [bug https://github.com/mozilla-releng/bouncerscript/pull/39](https://bugzil.la/https://github.com/mozilla-releng/bouncerscript/pull/39)        | scriptworker.exceptions.ScriptWorkerTaskException: Corrupt submission entry for product Firefox-62.0build1-Partial-61.0build3 platform linux path /firefox/candidates/62.0-candidates/build1/update/linux-i686/:lang/firefox-61.0-62.0.partial.mar | True | False |
| jlorenzo  | 2 | [bug 1486745](https://bugzil.la/1486745)        | release-secondary-final-verify-firefox failed to download some TC artifacts. The root cause is bug 1486582: it often returns a 500, which comes from the Queue not being able to resolve some DNS. The taskcluster team is on it. On our end, we could probably retry on the downloads. I don't see any retry on the logs. For instance: https://taskcluster-artifacts.net/Gaayh57cTlqURXqDvUwQRw/26/public/logs/live_backing.log  | True | True |
| jlorenzo  | 3 | [bug 1486747](https://bugzil.la/1486747)        | "Firefox-62.0build1-Complete" in bouncer didn't have any location set. Bouncerscript should add them even when the product already exists. | True | True |

