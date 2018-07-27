# devedition 62.0b12

### Date of go-to-build: 2018-07-26

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/ZHpT744-RjmMtaM0QRH0TA) ZHpT744-RjmMtaM0QRH0TA
* [push](https://tools.taskcluster.net/push-inspector/#/UteHAL46RJKKjkGZk5VxiA) UteHAL46RJKKjkGZk5VxiA
* [ship](https://tools.taskcluster.net/push-inspector/#/UteHAL46RJKKjkGZk5VxiA) UteHAL46RJKKjkGZk5VxiA
```
export PROMOTE_TASK_ID=ZHpT744-RjmMtaM0QRH0TA
export PUSH_TASK_ID=UteHAL46RJKKjkGZk5VxiA
export SHIP_TASK_ID=UteHAL46RJKKjkGZk5VxiA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1478935](https://bugzil.la/1478935)        | Instead of kicking off the push graph for devedition 62.0b12, the ship one was started https://treeherder.mozilla.org/#/jobs?repo=mozilla-beta&revision=23bc64507f53b0cba44c72f72539716adcf02d68&selectedJob=190452585. This leaves devedition in a state where we let new users install b12, but updates are still on hold for existing users - until QE greenlights the build. :jcristau from relman was okay to let devedition in this state and just sign off balrog when the build is done | False | True |

