# firefox 64.0b9

### Date of go-to-build: 2018-11-12

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/PhC2feEUTM-Pe6D0dn1HDw) PhC2feEUTM-Pe6D0dn1HDw
* [push](https://tools.taskcluster.net/push-inspector/#/Y3ICGsBURYmlZhhuyAGIbw) Y3ICGsBURYmlZhhuyAGIbw
* [ship](https://tools.taskcluster.net/push-inspector/#/Nxj8MihoTGafWIzs0t_VPA) Nxj8MihoTGafWIzs0t_VPA
```
export PROMOTE_TASK_ID=PhC2feEUTM-Pe6D0dn1HDw
export PUSH_TASK_ID=Y3ICGsBURYmlZhhuyAGIbw
export SHIP_TASK_ID=Nxj8MihoTGafWIzs0t_VPA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug none](https://bugzil.la/none)        | Timeout while cloning hg in l10n repackage task (WVcooLJGTZuVlw951ozaMQ) Clone's ETA peaked around 9hr and task timed out. | True | True |

