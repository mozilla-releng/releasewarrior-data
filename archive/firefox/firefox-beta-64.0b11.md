# firefox 64.0b11

### Date of go-to-build: 2018-11-19

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/X8-rAlI6QBq1QQF_czPilA) X8-rAlI6QBq1QQF_czPilA
* [push](https://tools.taskcluster.net/push-inspector/#/XPU1IElLTCiLRb5Kxc41HA) XPU1IElLTCiLRb5Kxc41HA
* [ship](https://tools.taskcluster.net/push-inspector/#/WXj1LiTTQQ26w_C_lY8YEg) WXj1LiTTQQ26w_C_lY8YEg
```
export PROMOTE_TASK_ID=X8-rAlI6QBq1QQF_czPilA
export PUSH_TASK_ID=XPU1IElLTCiLRb5Kxc41HA
export SHIP_TASK_ID=WXj1LiTTQQ26w_C_lY8YEg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | softonic tasks failing missing artifacts, e.g. http://taskcluster/queue/v1/task/N8wl3298RNeNmpGRX_3RQw/artifacts/releng/partner/softonic/softonic/tr/setup.exe https://taskcluster-artifacts.net/VprFpyieTvWUKWZJGQepUA/0/public/logs/live_backing.log | True | True |

