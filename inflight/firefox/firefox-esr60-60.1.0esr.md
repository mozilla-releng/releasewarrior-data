# firefox 60.1.0esr

### Date of go-to-build: 2018-06-19

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/ZvCvJWyITQSP_XuEET7uwA) ZvCvJWyITQSP_XuEET7uwA
* [push](https://tools.taskcluster.net/push-inspector/#/O_5B0rvSTZWU50Ry0qNSeQ) O_5B0rvSTZWU50Ry0qNSeQ
* [ship](https://tools.taskcluster.net/push-inspector/#/eb0G-2YkQAKmkbmTDlJosg) eb0G-2YkQAKmkbmTDlJosg
```
export PROMOTE_TASK_ID=ZvCvJWyITQSP_XuEET7uwA
export PUSH_TASK_ID=O_5B0rvSTZWU50Ry0qNSeQ
export SHIP_TASK_ID=eb0G-2YkQAKmkbmTDlJosg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| mtabara  | 1 | [bug 1362480](https://bugzil.la/1362480)        | Verison bump failed. Could be related to version bumping failing off on relbranches in bug 1362480. | True | False |
| mtabara  | 2 | [bug 1471208](https://bugzil.la/1471208)        | version bump failed in esr60 complaining about 60.1.0esr as being invalid | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/a96k3WI4TwmMWf8H8_H7mg) a96k3WI4TwmMWf8H8_H7mg
```
export PROMOTE_TASK_ID=a96k3WI4TwmMWf8H8_H7mg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

