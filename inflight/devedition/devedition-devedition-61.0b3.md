# devedition 61.0b3

### Date of go-to-build: 2018-05-07

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/PkP0V_OsQROhhlBkZXM8mA) PkP0V_OsQROhhlBkZXM8mA
* [push](https://tools.taskcluster.net/push-inspector/#/Xm1Yg0vJTheXPo1bSFv1Mg) Xm1Yg0vJTheXPo1bSFv1Mg
* [ship](https://tools.taskcluster.net/push-inspector/#/Qf26jrDERGSmocn6oJuZCQ) Qf26jrDERGSmocn6oJuZCQ
```
export PROMOTE_TASK_ID=PkP0V_OsQROhhlBkZXM8mA
export PUSH_TASK_ID=Xm1Yg0vJTheXPo1bSFv1Mg
export SHIP_TASK_ID=Qf26jrDERGSmocn6oJuZCQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1408868](https://bugzil.la/1408868)        | we removed too many bouncer config files | False | True |

