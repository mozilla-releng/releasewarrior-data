# firefox 60.2.2esr

### Date of go-to-build: 2018-10-01

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Q2y1faFfQZyubvTZJNw3Qw) Q2y1faFfQZyubvTZJNw3Qw
* [push](https://tools.taskcluster.net/push-inspector/#/LWx29n8ySd6tO5Ne6Lyl4A) LWx29n8ySd6tO5Ne6Lyl4A
* [ship](https://tools.taskcluster.net/push-inspector/#/DXtCRrpTQACkCm1Br7gPjg) DXtCRrpTQACkCm1Br7gPjg
```
export PROMOTE_TASK_ID=Q2y1faFfQZyubvTZJNw3Qw
export PUSH_TASK_ID=LWx29n8ySd6tO5Ne6Lyl4A
export SHIP_TASK_ID=DXtCRrpTQACkCm1Br7gPjg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | snap failed to push | True | True |

