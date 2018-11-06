# devedition 64.0b7

### Date of go-to-build: 2018-11-05

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/LcA-Z4FgQJSTcqDPvJ0m1Q) LcA-Z4FgQJSTcqDPvJ0m1Q
* [push](https://tools.taskcluster.net/push-inspector/#/ccqR_E0jQrSu7FXfeOGRRg) ccqR_E0jQrSu7FXfeOGRRg
* [ship](https://tools.taskcluster.net/push-inspector/#/PdRYGgV2RsGgH8ZoSxNoYw) PdRYGgV2RsGgH8ZoSxNoYw
```
export PROMOTE_TASK_ID=LcA-Z4FgQJSTcqDPvJ0m1Q
export PUSH_TASK_ID=ccqR_E0jQrSu7FXfeOGRRg
export SHIP_TASK_ID=PdRYGgV2RsGgH8ZoSxNoYw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug none](https://bugzil.la/none)        | Repackage-Signing (OP871SnEQ-6bOvd4cTJ9IQ) failed, due to CoT issues locating a target.complete.mar from task (BLHIEu4VSgik4pGHwDfClA) which despite being green did not have it. Reran both tasks to success. | True | True |

