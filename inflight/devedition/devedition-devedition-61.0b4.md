# devedition 61.0b4

### Date of go-to-build: 2018-05-10

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/URaNBED0R9myRBIGkVHGLg) URaNBED0R9myRBIGkVHGLg
* [push](https://tools.taskcluster.net/push-inspector/#/cunId6g0SqqaITtWsIzewQ) cunId6g0SqqaITtWsIzewQ
* [ship](https://tools.taskcluster.net/push-inspector/#/KFxb6Q9qRaWDqbbG4LcLmA) KFxb6Q9qRaWDqbbG4LcLmA
```
export PROMOTE_TASK_ID=URaNBED0R9myRBIGkVHGLg
export PUSH_TASK_ID=cunId6g0SqqaITtWsIzewQ
export SHIP_TASK_ID=KFxb6Q9qRaWDqbbG4LcLmA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | bouncer-check, partials needed reruns | True | False |
| sfraser  | 2 | [bug 1460906](https://bugzil.la/1460906)        | Incorrect use of config.params made the balrog schedule task fail | False | True |

