# firefox 60.0.1

### Date of go-to-build: 2018-05-15

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/F2dVX6m6QPCsy5EnhFUfSg) F2dVX6m6QPCsy5EnhFUfSg
* [push](https://tools.taskcluster.net/push-inspector/#/OilHLYU4Q4eSq95i4L2caA) OilHLYU4Q4eSq95i4L2caA
```
export PROMOTE_TASK_ID=F2dVX6m6QPCsy5EnhFUfSg
export PUSH_TASK_ID=OilHLYU4Q4eSq95i4L2caA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 6.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1452807#c25)  - bump bouncer aliases for funnelcake 133, 134, 135 once 60.0.1 ships

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1461857](https://bugzil.la/1461857)        | langpack signing broken, could be from amo side | True | True |
| jlund  | 2 | [bug 1461895](https://bugzil.la/1461895)        | l10n repacks intermittently end early | False | True |
| mtabara  | 3 | [bug 1461919](https://bugzil.la/1461919)        | reruns are flaky. all over the place. we need to bump its priority and address it sooner | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/TBNtdEMkRliaYV9KwuD5iA) TBNtdEMkRliaYV9KwuD5iA
```
export PROMOTE_TASK_ID=TBNtdEMkRliaYV9KwuD5iA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 6.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1452807#c25)  - bump bouncer aliases for funnelcake 133, 134, 135 once 60.0.1 ships

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1461857](https://bugzil.la/1461857)        | langpack signing broken, could be from amo side | False | True |

