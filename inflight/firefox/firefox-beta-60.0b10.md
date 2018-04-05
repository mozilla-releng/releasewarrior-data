# firefox 60.0b10

### Date of go-to-build: 2018-04-04

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/HKNBTwAMT22-Tk9WQyZEVw) HKNBTwAMT22-Tk9WQyZEVw
* [push](https://tools.taskcluster.net/push-inspector/#/GYT_nZNyQzGn7wjcwBTajw) GYT_nZNyQzGn7wjcwBTajw
* [ship](https://tools.taskcluster.net/push-inspector/#/eyoq1WXeQYqOqRinpGprFg) eyoq1WXeQYqOqRinpGprFg


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| sfraser  | 1 | [bug 1451667](https://bugzil.la/1451667)        | release-snap-push-firefox task failed, but pushed the snap anyway | False | True |

