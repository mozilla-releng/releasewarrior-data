# firefox 60.2.0esr

### Date of go-to-build: 2018-05-02

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-08-20 - [bug 1408868](https://bugzil.la/1408868): Change https://hg.mozilla.org/releases/mozilla-esr60/rev/e1c89bf28365823de83262354b17801158d9414f#l1.15 and following lines to let esr-latest aliases point to esr60.
- [ ] 2. due:2018-08-20 (est) - [bug 1464741](https://bugzil.la/1464741): Update changes for ESR60 at 60.2.0esr

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/CIDC-h0YQEm7jiV3ShA0Yw) CIDC-h0YQEm7jiV3ShA0Yw
```
export PROMOTE_TASK_ID=CIDC-h0YQEm7jiV3ShA0Yw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#1-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-signoffs)  - signoff in Balrog
- [ ] 5.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1460752)  - Update ship-it config for ESR52 deprecation

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

