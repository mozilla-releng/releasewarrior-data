# firefox 60.0esr

### Date of go-to-build: 2018-03-19

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-04-24 - [bug 1445666](https://bugzil.la/1445666): remove esr-latest* aliases from esr52
- [x] 2. due:2018-04-26 - [bug 1457090](https://bugzil.la/1457090): land+graft post-merge patches

## Build 6  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/InENFaK4Roa4s61cAHZYdQ) InENFaK4Roa4s61cAHZYdQ
* [push](https://tools.taskcluster.net/push-inspector/#/dqhcS8eKS0OIF2udsb292A) dqhcS8eKS0OIF2udsb292A
```
export PROMOTE_TASK_ID=InENFaK4Roa4s61cAHZYdQ
export PUSH_TASK_ID=dqhcS8eKS0OIF2udsb292A
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship. NB: There's a rule but ESR60 requests will not reach it. | False | True |
| jlorenzo  | 2 | [bug none](https://bugzil.la/none)        | release-balrog-submit-toplevel-firefox failed (ZB6V2TlUS7CvgyLxw8001Q) because rule "firefox-esr60-cdntest" didn't exist. I renamed existing alias "esr60-cdntest" to what the worker expects | True | False |
| jlorenzo  | 3 | [bug 1459145](https://bugzil.la/1459145)        | release-notify-promote-firefox didn't send an email to release-signoff. I sent it manually. If we keep build6 running, we must also send emails manually after push and ship | False | True |
| asasaki  | 4 | [bug none](https://bugzil.la/none)        | missing snap+notify scopes! | True | False |
| asasaki  | 5 | [bug none](https://bugzil.la/none)        | esr60 snap failed -- kill? | False | True |
| asasaki  | 6 | [bug none](https://bugzil.la/none)        | bouncer check failed | False | True |

## Build 5  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/HOffha7JS8eISza1qm5sYA) HOffha7JS8eISza1qm5sYA
```
export PROMOTE_TASK_ID=HOffha7JS8eISza1qm5sYA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship. NB: There's a rule but ESR60 requests will not reach it. | False | True |
| jlorenzo  | 2 | [bug none](https://bugzil.la/none)        | release-balrog-submit-toplevel-firefox failed (ZB6V2TlUS7CvgyLxw8001Q) because rule "firefox-esr60-cdntest" didn't exist. I renamed existing alias "esr60-cdntest" to what the worker expects | False | True |
| mtabara  | 3 | [bug 1457090](https://bugzil.la/1457090)        | add missing esr60 config in release-generate-checksums. Fixed in https://hg.mozilla.org/releases/mozilla-esr60/rev/1185905f50087bae5d1000de0abde4fed8d899eb | True | False |
| jlorenzo  | 4 | [bug 1408868](https://bugzil.la/1408868)        | Set bouncer alias in taskgraph and removed duplicated configs | True | False |

## Build 4  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship. NB: There's a rule but ESR60 requests will not reach it. | False | True |
| nthomas  | 2 | [bug 1458744](https://bugzil.la/1458744)        | Missing scopes for promote action | True | False |
| jlorenzo  | 3 | [bug 1458819](https://bugzil.la/1458819)        | platform.ini had no esr60 configuration | True | False |
| jlorenzo  | 4 | [bug 1458809](https://bugzil.la/1458809)        | release-bouncer-sub has the wrong scopes for esr60 | True | False |
| jlorenzo  | 5 | [bug 1458810](https://bugzil.la/1458810)        | L10n repackage missing esr60 single_locale config | True | False |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/VtwRzO8vQSmsbpFgJXGpqQ) VtwRzO8vQSmsbpFgJXGpqQ
```
export PROMOTE_TASK_ID=VtwRzO8vQSmsbpFgJXGpqQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship. NB: There's a rule but ESR60 requests will not reach it. | False | True |
| nthomas  | 2 | [bug 1458744](https://bugzil.la/1458744)        | Missing scopes for promote action | False | True |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Zu6HtaOuR7-31HeB3EuLoA) Zu6HtaOuR7-31HeB3EuLoA
```
export PROMOTE_TASK_ID=Zu6HtaOuR7-31HeB3EuLoA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship | False | True |
| nthomas  | 2 | [bug 1432737](https://bugzil.la/1432737)        | Release runner objects to display version of 60.0esr, backed out 34474b4c614b | True | False |
| nthomas  | 3 | [bug 1458744](https://bugzil.la/1458744)        | Missing scopes for releaserunner | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#4-publish-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/historic_relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | add watershed to prevent esr52 from updating to esr60 before ship | False | True |
| nthomas  | 2 | [bug 1434889](https://bugzil.la/1434889)        | m-esr60 not included in RELEASE_PROJECTS, so release actions left out by decision task. Resolved by d9e849d8f10f | True | False |

