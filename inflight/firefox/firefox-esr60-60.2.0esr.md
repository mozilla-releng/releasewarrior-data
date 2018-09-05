# firefox 60.2.0esr

### Date of go-to-build: 2018-05-02

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-08-20 - [bug 1408868](https://bugzil.la/1408868): Change https://hg.mozilla.org/releases/mozilla-esr60/rev/e1c89bf28365823de83262354b17801158d9414f#l1.15 and following lines to let esr-latest aliases point to esr60.
- [ ] 2. due:2018-08-20 (est) - [bug 1464741](https://bugzil.la/1464741): Update changes for ESR60 at 60.2.0esr

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/TXUf-jr1Q1ej8rcOdp6GtA) TXUf-jr1Q1ej8rcOdp6GtA
* [push](https://tools.taskcluster.net/push-inspector/#/SkDMIM1HQMiDIPfzsl7qvA) SkDMIM1HQMiDIPfzsl7qvA
* [ship](https://tools.taskcluster.net/push-inspector/#/PevpN8F9RE607B6KLjw0oA) PevpN8F9RE607B6KLjw0oA
```
export PROMOTE_TASK_ID=TXUf-jr1Q1ej8rcOdp6GtA
export PUSH_TASK_ID=SkDMIM1HQMiDIPfzsl7qvA
export SHIP_TASK_ID=PevpN8F9RE607B6KLjw0oA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#1-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-publish-release)  - schedule the release for shipping
- [x] 4.  - Update bouncer entries firefox-esr-latest-ssl and firefox-esr-latest to point to ESR60. This has to be done manually if we ship 60.2.0esr-build2. Otherwise this is done automatically thanks to https://hg.mozilla.org/releases/mozilla-esr60/rev/8b9c2d5d09bf
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-signoffs)  - signoff in Balrog
- [ ] 6.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1460752)  - Update ship-it config for ESR52 deprecation

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1488511](https://bugzil.la/1488511)        | Final verify failed  due to matching HTTP headers case-sensitively | True | True |
| tomprince  | 2 | [bug 1488518](https://bugzil.la/1488518)        | Bouncer entries for completes point at bz2 paths. | True | True |
| jlorenzo  | 3 | [bug 1488686](https://bugzil.la/1488686)        | 52.9.0esr -> 60.2.0esr: wrong bouncer entries found by final-verify => "firefox-60.2.0esr-complete-bz2" doesn't exist. Fixed manually. | True | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

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

