# firefox 60.2.1esr

### Date of go-to-build: 2018-09-04

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/D-fWrJ75Rxy61bEHnVyajA) D-fWrJ75Rxy61bEHnVyajA
* [push](https://tools.taskcluster.net/push-inspector/#/YndHp56KRGiPUmmt0tNd0Q) YndHp56KRGiPUmmt0tNd0Q
```
export PROMOTE_TASK_ID=D-fWrJ75Rxy61bEHnVyajA
export PUSH_TASK_ID=YndHp56KRGiPUmmt0tNd0Q
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1493028](https://bugzil.la/1493028)        | Signing backlog, and 'low' priority for esr60, means graph is not progressing. Priority fix landed for future builds, and email disucssion about mac signing capacity opened. | True | True |

