# thunderbird 60.0b7

### Date of go-to-build: 2018-06-07

## Preflight tasks (pre go-to-build)
- none

## Build 3  

### Graphs
* [decision](https://tools.taskcluster.net/push-inspector/#/RhWly9JYTNS7YV66iHN-YQ) RhWly9JYTNS7YV66iHN-YQ
* [promote](https://tools.taskcluster.net/push-inspector/#/RTCkxBCKTYeozYKGn5ZYSg) RTCkxBCKTYeozYKGn5ZYSg
* [push](https://tools.taskcluster.net/push-inspector/#/VW-fjNJoRyaZkFLsMgPd7Q) VW-fjNJoRyaZkFLsMgPd7Q
* [ship](https://tools.taskcluster.net/push-inspector/#/J3sl3SArSRaFx7yWBz0OeQ) J3sl3SArSRaFx7yWBz0OeQ
```
export DECISION_TASK_ID=RhWly9JYTNS7YV66iHN-YQ
export PROMOTE_TASK_ID=RTCkxBCKTYeozYKGn5ZYSg
export PUSH_TASK_ID=VW-fjNJoRyaZkFLsMgPd7Q
export SHIP_TASK_ID=J3sl3SArSRaFx7yWBz0OeQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug none](https://bugzil.la/none)        | Official branding not enabled in L10n config; caused macOS L10n builds to fail | True | False |
| tomprince  | 2 | [bug none](https://bugzil.la/none)        | Balrog submission was missing file path configuration for localtest channel, due to misspelling of project name in taskgraph config | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug none](https://bugzil.la/none)        | Sanity check failed as version wasn't updated on relbranch | True | False |
| tomprince  | 2 | [bug none](https://bugzil.la/none)        | mozharness config for L10n on config-beta hadn't been created | True | False |

