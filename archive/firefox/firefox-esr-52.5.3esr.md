# firefox 52.5.3esr

### Date of go-to-build: 2017-12-26

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/TqHmA8tDT--yBsQCGippwQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [x] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | YkguRF5hRNy9Cu0Wqff1Xg docker gen tasks failed intermittently (stale state?) because tmp dir couldn't be created: Error calling 'link' for dind : EEXIST: file already exists, mkdir '/tmp/mQtdw8mjQU-TP_PRrpDTcQ' | True | True |
| jlund  | 2 | [bug none](https://bugzil.la/none)        | bump version did not work. I suspect because of relbranch | False | True |
| jlund  | 3 | [bug none](https://bugzil.la/none)        | publish to esr channel failed LUd7dUIURpuMifmbPq3fRQ - retry: attempt #4 caught exception: argument of type 'int' is not iterable | False | True |

