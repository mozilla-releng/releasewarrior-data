# firefox 60.0b14

### Date of go-to-build: 2018-04-19

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/KXC_f9OTRN6DHa_IYiatWQ) KXC_f9OTRN6DHa_IYiatWQ
* [push](https://tools.taskcluster.net/push-inspector/#/ew3RJY_CRZu9PYPU3GFtcA) ew3RJY_CRZu9PYPU3GFtcA
```
export PROMOTE_TASK_ID=KXC_f9OTRN6DHa_IYiatWQ
export PUSH_TASK_ID=ew3RJY_CRZu9PYPU3GFtcA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1442545](https://bugzil.la/1442545)        | partner beetmover busted, now fixed | True | False |
| sfraser  | 2 | [bug none](https://bugzil.la/none)        | release-snap-push-firefox (CDraGnh_TEGGiut9YL6cGg) failed because it's build2 and the sha matched build1.  | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/b2jFhrCVSNOdaEolYZbyvg) b2jFhrCVSNOdaEolYZbyvg
```
export PROMOTE_TASK_ID=b2jFhrCVSNOdaEolYZbyvg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | partner scopes issue | True | False |

