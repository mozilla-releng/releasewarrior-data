# firefox 60.0b15

### Date of go-to-build: 2018-04-23

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/O607MSw1T46go1vCaaIinA) O607MSw1T46go1vCaaIinA
* [push](https://tools.taskcluster.net/push-inspector/#/U-wG0qa_S6mE8VhsTRmt_w) U-wG0qa_S6mE8VhsTRmt_w
* [ship](https://tools.taskcluster.net/push-inspector/#/bVOm2TG0TH-W8sDuHoiDsA) bVOm2TG0TH-W8sDuHoiDsA
```
export PROMOTE_TASK_ID=O607MSw1T46go1vCaaIinA
export PUSH_TASK_ID=U-wG0qa_S6mE8VhsTRmt_w
export SHIP_TASK_ID=bVOm2TG0TH-W8sDuHoiDsA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1450075](https://bugzil.la/1450075)        | repackage tasks flaky - mostly hg? | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | sheriffs reran completed tasks again | True | True |

