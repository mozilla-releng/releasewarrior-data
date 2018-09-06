# fennec 62.0rc

### Date of go-to-build: 2018-08-28

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/RbjdmL1NTuqrY9_0HpC7Qw) RbjdmL1NTuqrY9_0HpC7Qw
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/W16eDSJWQmKKEI9aAfWWPg) W16eDSJWQmKKEI9aAfWWPg
```
export PROMOTE_TASK_ID=RbjdmL1NTuqrY9_0HpC7Qw
export SHIP_RC_TASK_ID=W16eDSJWQmKKEI9aAfWWPg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/YJ1M0j2qRMGX5z5IuwJ_KA) YJ1M0j2qRMGX5z5IuwJ_KA
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/FxZuebE9SYasNRyuGvvfvg) FxZuebE9SYasNRyuGvvfvg
```
export PROMOTE_TASK_ID=YJ1M0j2qRMGX5z5IuwJ_KA
export SHIP_RC_TASK_ID=FxZuebE9SYasNRyuGvvfvg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1487114](https://bugzil.la/1487114)        | Fennec RC: Ship-rc email should be more nuanced than "fennec 62.0 build1 [...] has shipped!". Fixed by manually sending a follow up email | True | True |

