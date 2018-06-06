# firefox 60.0.2

### Date of go-to-build: 2018-06-04

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/K0R9k4t7SHupumGQLwA7Rw) K0R9k4t7SHupumGQLwA7Rw
* [push](https://tools.taskcluster.net/push-inspector/#/Wvh36N0bSYGNiHm2nEJ-Rw) Wvh36N0bSYGNiHm2nEJ-Rw
* [ship](https://tools.taskcluster.net/push-inspector/#/dMzfJ0CbSMiiQZCKKeOfrQ) dMzfJ0CbSMiiQZCKKeOfrQ
```
export PROMOTE_TASK_ID=K0R9k4t7SHupumGQLwA7Rw
export PUSH_TASK_ID=Wvh36N0bSYGNiHm2nEJ-Rw
export SHIP_TASK_ID=dMzfJ0CbSMiiQZCKKeOfrQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 6.  - as per open snap issue, publishing 60.0.2 to stable snap channel may be manually required

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1467261](https://bugzil.la/1467261)        | snaps are not being published on the stable channel for 60.0.1 and current 60.0.2. catlee manually updated on snapcraft. Ask jlorenzo about current automation state and whether we need to add more human tasks in mean time | False | True |

