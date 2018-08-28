# firefox 62.0rc

### Date of go-to-build: 2018-06-04

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-08-21 - [bug none](https://bugzil.la/none): We need to properly publish en-CA for this release. More information in bug 1465064

## Build 1  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/clacPCDwRYWZJHdZzRP0cA) clacPCDwRYWZJHdZzRP0cA
```
export PROMOTE_RC_TASK_ID=clacPCDwRYWZJHdZzRP0cA
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
| jlorenzo  | 1 | [bug https://github.com/mozilla-releng/bouncerscript/pull/39](https://bugzil.la/https://github.com/mozilla-releng/bouncerscript/pull/39)        | scriptworker.exceptions.ScriptWorkerTaskException: Corrupt submission entry for product Firefox-62.0build1-Partial-61.0build3 platform linux path /firefox/candidates/62.0-candidates/build1/update/linux-i686/:lang/firefox-61.0-62.0.partial.mar | False | True |

