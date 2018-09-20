# firefox 63.0b8

### Date of go-to-build: 2018-09-20

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/EjriZedLRoeG55XhMZ_enA) EjriZedLRoeG55XhMZ_enA
* [push](https://tools.taskcluster.net/push-inspector/#/ZbedeifrQim2SbiVy1ynnw) ZbedeifrQim2SbiVy1ynnw
```
export PROMOTE_TASK_ID=EjriZedLRoeG55XhMZ_enA
export PUSH_TASK_ID=ZbedeifrQim2SbiVy1ynnw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | prematurely shipped fx 63.0b8. cancelled ship graph; need to run `tc-filter.py --graph-id GT-f8ebSRomsoC9k2ZQHUA --state exception --action rerun` to ship | False | True |

