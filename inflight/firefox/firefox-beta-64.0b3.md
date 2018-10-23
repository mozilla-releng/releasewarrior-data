# firefox 64.0b3

### Date of go-to-build: 2018-10-22

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/LiXhFfXbTbuA5ZFSQA0tEw) LiXhFfXbTbuA5ZFSQA0tEw
* [push](https://tools.taskcluster.net/push-inspector/#/LHajgRahR5mDVuAoRtg10A) LHajgRahR5mDVuAoRtg10A
```
export PROMOTE_TASK_ID=LiXhFfXbTbuA5ZFSQA0tEw
export PUSH_TASK_ID=LHajgRahR5mDVuAoRtg10A
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | rerun EtMs1b3vT1i7hhZ6kbtsgA, YETuIdBuQpuvb1lXUCbHxg x2, also https://bugzilla.mozilla.org/attachment.cgi?id=9019197 | False | True |
| asasaki  | 2 | [bug 1501113](https://bugzil.la/1501113)        | concurrent partial generation has race conditions due to shared cache. had to purge caches in bug 1501131 | False | True |

