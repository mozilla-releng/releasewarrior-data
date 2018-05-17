# firefox 61.0b4

### Date of go-to-build: 2018-05-10

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Sn7Q1UvTRuil7edbA62Elg) Sn7Q1UvTRuil7edbA62Elg
* [push](https://tools.taskcluster.net/push-inspector/#/dvb58Z_nSEGyFYHc8-ObPw) dvb58Z_nSEGyFYHc8-ObPw
* [ship](https://tools.taskcluster.net/push-inspector/#/AroZVdVWSx2kubqlwVHQTQ) AroZVdVWSx2kubqlwVHQTQ
```
export PROMOTE_TASK_ID=Sn7Q1UvTRuil7edbA62Elg
export PUSH_TASK_ID=dvb58Z_nSEGyFYHc8-ObPw
export SHIP_TASK_ID=AroZVdVWSx2kubqlwVHQTQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| sfraser  | 1 | [bug 1460906](https://bugzil.la/1460906)        | Incorrect use of config.params made the balrog schedule task fail | True | False |

