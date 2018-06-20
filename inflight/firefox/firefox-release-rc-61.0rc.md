# firefox 61.0rc

### Date of go-to-build: 2018-05-10

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-05-09 - [bug 1441353](https://bugzil.la/1441353): from callek: 'need to manually upload the locale oc language pack at next rc, the task itself will fail out due to the issue so will be visible'

## Build 2  

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/fyTjQfaPQKaHGJPtTs8o2w) fyTjQfaPQKaHGJPtTs8o2w
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/e8zM6iu6QlGP08rWTQWyxw) e8zM6iu6QlGP08rWTQWyxw
```
export PROMOTE_RC_TASK_ID=fyTjQfaPQKaHGJPtTs8o2w
export SHIP_RC_TASK_ID=e8zM6iu6QlGP08rWTQWyxw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#wnp)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - ship in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#remove-wnp)  - remove previous version's What's New Page
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - schedule the release for shipping
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1469450](https://bugzil.la/1469450)        | release-update-verify-config tasks failing for 61.0rc. e.g. NvDsOfpFSuOR2fy4Ggfw1w nthomas fixed outside offical graph so we didn't need a build2. we can ignore all failed and unscheduled UV tasks. those can be sound here: https://tools.taskcluster.net/groups/HolVnqBSST-lzsRazKn_Ow | True | True |
| jlund  | 2 | [bug 1469456](https://bugzil.la/1469456)        | macos signing servers cause exceptions when overloaded | True | True |
| mtabara  | 3 | [bug 1469607](https://bugzil.la/1469607)        | Partner repacks run into fail / exception for various reason. Are these tasks supposed to exist in this graph altogether? | True | True |

