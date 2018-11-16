# devedition 64.0b10

### Date of go-to-build: 2018-11-15

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/cY8lFcYuSYeLd5hmHxEqxQ) cY8lFcYuSYeLd5hmHxEqxQ
* [push](https://tools.taskcluster.net/push-inspector/#/H4c_VFD_SLmF68qOjndiaA) H4c_VFD_SLmF68qOjndiaA
* [ship](https://tools.taskcluster.net/push-inspector/#/QcC6q8QGQZKXT3rZrljhhw) QcC6q8QGQZKXT3rZrljhhw
```
export PROMOTE_TASK_ID=cY8lFcYuSYeLd5hmHxEqxQ
export PUSH_TASK_ID=H4c_VFD_SLmF68qOjndiaA
export SHIP_TASK_ID=QcC6q8QGQZKXT3rZrljhhw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1504353](https://bugzil.la/1504353)        | Repackage-l10n failed with task exit code 137 (cnplLDL4S3C9RZmrgnc7yg) | False | True |
| callek  | 2 | [bug 1502245](https://bugzil.la/1502245)        | Devedition Early Tagging failed, racing to push (dk37EunxQRK3BGNoMcgn6g) | False | True |

