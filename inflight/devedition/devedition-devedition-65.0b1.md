# devedition 65.0b1

### Date of go-to-build: 2018-10-18

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-12-03 - [bug 1499440](https://bugzil.la/1499440): Check Ship-it v2 rollout to release branches for the sanity of mark-as-started task. Read bug 1499440 comment 11

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/S9sR5G94TvOPLCMH7BjFxw) S9sR5G94TvOPLCMH7BjFxw
* [push](https://tools.taskcluster.net/push-inspector/#/FTfKrreNQkm_PsJG4IrcdA) FTfKrreNQkm_PsJG4IrcdA
* [ship](https://tools.taskcluster.net/push-inspector/#/EyF-h6_eQnmEt2EKwoDDYA) EyF-h6_eQnmEt2EKwoDDYA
```
export PROMOTE_TASK_ID=S9sR5G94TvOPLCMH7BjFxw
export PUSH_TASK_ID=FTfKrreNQkm_PsJG4IrcdA
export SHIP_TASK_ID=EyF-h6_eQnmEt2EKwoDDYA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1511924](https://bugzil.la/1511924)        | BouncerCheck failed due to MSI configuration issue (bouncer pointing at wrong location) | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/VD8UomoUQe6NtGib8JETUg) VD8UomoUQe6NtGib8JETUg
* [ship](https://tools.taskcluster.net/push-inspector/#/bQfG0zxLQOqXZoOUbdTXqw) bQfG0zxLQOqXZoOUbdTXqw
```
export PROMOTE_TASK_ID=VD8UomoUQe6NtGib8JETUg
export SHIP_TASK_ID=bQfG0zxLQOqXZoOUbdTXqw
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

