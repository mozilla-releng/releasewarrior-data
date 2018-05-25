# devedition 61.0b8

### Date of go-to-build: 2018-05-24

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/BnhX5IHuQ8OrpkcNmFqARg) BnhX5IHuQ8OrpkcNmFqARg
* [push](https://tools.taskcluster.net/push-inspector/#/QueqhBtAR56DtWSsLBu7AA) QueqhBtAR56DtWSsLBu7AA
```
export PROMOTE_TASK_ID=BnhX5IHuQ8OrpkcNmFqARg
export PUSH_TASK_ID=QueqhBtAR56DtWSsLBu7AA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | flaky network, many failed UV jobs. rerunning. no known cause with taskcluster or moc. many intermittent oranges: https://treeherder.mozilla.org/#/jobs?repo=mozilla-beta&revision=0f95c023462e4de617ebdd77cbe90ec523efad10&filter-searchStr=release-update-verify&filter-resultStatus=testfailed&filter-resultStatus=busted&filter-resultStatus=exception&filter-resultStatus=retry&filter-resultStatus=usercancel&filter-resultStatus=runnable&selectedJob=180114241 | True | True |

