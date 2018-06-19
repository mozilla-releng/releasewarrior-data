# devedition 62.0b1

### Date of go-to-build: 2018-06-18

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/LFS0mhasQsG3cmg4WwLqPQ) LFS0mhasQsG3cmg4WwLqPQ
* [push](https://tools.taskcluster.net/push-inspector/#/T2A-SvWjRrayaqPZExEVFQ) T2A-SvWjRrayaqPZExEVFQ
* [ship](https://tools.taskcluster.net/push-inspector/#/L1Bussj9Re2C8dbEiHDcqw) L1Bussj9Re2C8dbEiHDcqw
```
export PROMOTE_TASK_ID=LFS0mhasQsG3cmg4WwLqPQ
export PUSH_TASK_ID=T2A-SvWjRrayaqPZExEVFQ
export SHIP_TASK_ID=L1Bussj9Re2C8dbEiHDcqw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | had to patch rr3 to get graph to start -- we probably want to switch to action hooks sooner | False | True |

