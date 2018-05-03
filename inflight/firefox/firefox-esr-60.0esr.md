# firefox 60.0esr

### Date of go-to-build: 2018-03-19

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-04-24 - [bug 1445666](https://bugzil.la/1445666): remove esr-latest* aliases from esr52
- [ ] 2. due:2018-04-26 - [bug 1457090](https://bugzil.la/1457090): land+graft post-merge patches

## Build 2  

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
| nthomas  | 3 | [bug 1458744](https://bugzil.la/1458744)        | Missing scopes | False | True |

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

