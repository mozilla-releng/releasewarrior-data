# firefox 63.0rc

### Date of go-to-build: 2018-10-03

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-10-23 - [bug 1495844](https://bugzil.la/1495844): We will need to update the firefox-election-edition bouncer URLs manually after shipping.

## Build 1  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/Xei1zndyT_Ov6arEk1doTw) Xei1zndyT_Ov6arEk1doTw
```
export PROMOTE_RC_TASK_ID=Xei1zndyT_Ov6arEk1doTw
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
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | rr3 not running | True | False |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | missing shipit-dev scope; the mark-as-started task should point at production for esr and release | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | cron-check-bouncer is running in the release graph, including devedition | True | True |
| asasaki  | 4 | [bug none](https://bugzil.la/none)        | linux64 l10n lij upload issue? script exited fine, task failed, missing a tarball | True | True |
| asasaki  | 5 | [bug none](https://bugzil.la/none)        | hg clone issue again | False | True |

