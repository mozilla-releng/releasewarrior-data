# firefox 64.0b10

### Date of go-to-build: 2018-11-15

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/J8lhygB1RjGcnbPldnb75Q) J8lhygB1RjGcnbPldnb75Q
* [push](https://tools.taskcluster.net/push-inspector/#/LJ7QEWPPR_aP2JdI2f-XVw) LJ7QEWPPR_aP2JdI2f-XVw
* [ship](https://tools.taskcluster.net/push-inspector/#/F-EfVxdYQY6WT-n-RIAw5Q) F-EfVxdYQY6WT-n-RIAw5Q
```
export PROMOTE_TASK_ID=J8lhygB1RjGcnbPldnb75Q
export PUSH_TASK_ID=LJ7QEWPPR_aP2JdI2f-XVw
export SHIP_TASK_ID=F-EfVxdYQY6WT-n-RIAw5Q
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1474156](https://bugzil.la/1474156)        | Clamav timeout again on a partial task (TLo5OH8YSNGtf6sM0jPLqA) | True | True |

