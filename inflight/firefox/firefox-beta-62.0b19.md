# firefox 62.0b19

### Date of go-to-build: 2018-08-20

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/A0nXB_grTCqOfv6_z5gBcA) A0nXB_grTCqOfv6_z5gBcA
* [push](https://tools.taskcluster.net/push-inspector/#/BCJdwikxReyXt06A3O7rBw) BCJdwikxReyXt06A3O7rBw
* [ship](https://tools.taskcluster.net/push-inspector/#/NeiLnQbYSiCP2_ZgQNMKBA) NeiLnQbYSiCP2_ZgQNMKBA
```
export PROMOTE_TASK_ID=A0nXB_grTCqOfv6_z5gBcA
export PUSH_TASK_ID=BCJdwikxReyXt06A3O7rBw
export SHIP_TASK_ID=NeiLnQbYSiCP2_ZgQNMKBA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug none](https://bugzil.la/none)        | Signing failed because signing_scriptworker timed out fetching signed build https://tools.taskcluster.net/groups/A0nXB_grTCqOfv6_z5gBcA/tasks/AUpCwWOmQjyfdgdmSKX-Sg/runs/0/logs/public%2Flogs%2Flive_backing.log#L57. I reran it | True | True |
| jlorenzo  | 2 | [bug 1484924](https://bugzil.la/1484924)        | Intermittent: Could not start taskcluster proxy: fork/exec C:\generic-worker\taskcluster-proxy.exe: Access is denied. => "invalid memory address or nil pointer dereference" | True | True |

