# firefox 63.0b3

### Date of go-to-build: 2018-09-04

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/UbyN8WZqS7OpFbICG-HcUg) UbyN8WZqS7OpFbICG-HcUg
* [push](https://tools.taskcluster.net/push-inspector/#/Et2Kn47nS5WefXfzw3S3kw) Et2Kn47nS5WefXfzw3S3kw
* [ship](https://tools.taskcluster.net/push-inspector/#/ZV6BvJDnQG-E1YTSudKj1g) ZV6BvJDnQG-E1YTSudKj1g
```
export PROMOTE_TASK_ID=UbyN8WZqS7OpFbICG-HcUg
export PUSH_TASK_ID=Et2Kn47nS5WefXfzw3S3kw
export SHIP_TASK_ID=ZV6BvJDnQG-E1YTSudKj1g
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1488396](https://bugzil.la/1488396)        | Snap push failed. It timed out after uploading the snap. Resolved by manually promoting this snap to the beta channel  | True | True |

