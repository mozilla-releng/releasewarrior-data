# thunderbird 60.0

### Date of go-to-build: 2018-07-24

## Preflight tasks (pre go-to-build)
- none

## Build 4  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/RCniTnXJSnuBMHzqwx5DzA) RCniTnXJSnuBMHzqwx5DzA
* [push](https://tools.taskcluster.net/push-inspector/#/D7-u7xOMSYO1kqfH3g5PQw) D7-u7xOMSYO1kqfH3g5PQw
* [ship](https://tools.taskcluster.net/push-inspector/#/B5SChkanQf2ahu0Kr1POgQ) B5SChkanQf2ahu0Kr1POgQ
```
export PROMOTE_TASK_ID=RCniTnXJSnuBMHzqwx5DzA
export PUSH_TASK_ID=D7-u7xOMSYO1kqfH3g5PQw
export SHIP_TASK_ID=B5SChkanQf2ahu0Kr1POgQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1481095](https://bugzil.la/1481095)        | update verify config gen: FATAL - Didn't find any update paths, cannot continue. Expected with no updates configured for older than 60.0 | False | True |
| jlorenzo  | 2 | [bug 1481198](https://bugzil.la/1481198)        | Wrong bouncer entries are updated by automation. I manually changed the bouncer alias and cancelled+rerun the next task (a16X_sdwSxKSnErZgCb6oQ) | True | True |
| jlorenzo  | 3 | [bug 1481203](https://bugzil.la/1481203)        | Cannot mark Thunderbird 60.0 as shipped: No valid scope found. I manually marked it as shipped on ship-it and cancelled+rerun the next task (B8nQn2dOQkONPDXep7hUpg)  | True | True |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/HktsjY2jSJuOnmZdryoEQw) HktsjY2jSJuOnmZdryoEQw
```
export PROMOTE_TASK_ID=HktsjY2jSJuOnmZdryoEQw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug ?](https://bugzil.la/?)        | update verify config gen: FATAL - Didn't find any update paths, cannot continue | False | True |
| nthomas  | 2 | [bug 1472860](https://bugzil.la/1472860)        | Signing issues with newly enabled mdc1 servers. Aki disabled them. | True | False |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/ewkdWZ_URzSPILVA4mXh_Q) ewkdWZ_URzSPILVA4mXh_Q
```
export PROMOTE_TASK_ID=ewkdWZ_URzSPILVA4mXh_Q
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug ?](https://bugzil.la/?)        | update verify config gen: FATAL - Didn't find any update paths, cannot continue | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/HpgK00tcSJyzqk4H7pGvRw) HpgK00tcSJyzqk4H7pGvRw
```
export PROMOTE_TASK_ID=HpgK00tcSJyzqk4H7pGvRw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug ?](https://bugzil.la/?)        | update verify config gen: FATAL - Didn't find any update paths, cannot continue | False | True |

