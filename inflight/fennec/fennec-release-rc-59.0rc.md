# fennec 59.0rc

### Date of go-to-build: 2018-03-01

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-03-05 - [bug none](https://bugzil.la/none): [jlorenzo] Workaround in case the fennec_rc taskgraph isn't ready yet: when the promote action graph is submitted, cancel the "google-play-strings" task (for instance https://tools.taskcluster.net/groups/BFxmYjjZQRynxfeInleESg/tasks/MN0K1JIDTbWqfe7TmIJ2pw/details). Then, push-apk will detect no strings and will skip the part where they get updated. This ensures we don't promote Firefox 59 publicly on Google Play, on the release product.

## Build 3  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Jp2wmtf8R8K1c_BAAL-vkw) Jp2wmtf8R8K1c_BAAL-vkw
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/TfKFXCykQTuPkyAarmpNTw) TfKFXCykQTuPkyAarmpNTw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/VoVEu8-ZTKGdQMUqDYXhcA) VoVEu8-ZTKGdQMUqDYXhcA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/clifvnJKS6i8xMexCIAiIQ) clifvnJKS6i8xMexCIAiIQ
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/AeKtuisDRPqNCL2npr5FwA) AeKtuisDRPqNCL2npr5FwA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug none](https://bugzil.la/none)        | had to local patch trigger_action.py to support ship_fennec_rc flavour | True | False |
| bhearsum  | 2 | [bug none](https://bugzil.la/none)        | ship fennec rc action task failed with scope issues on project:releng:googleplay:release | True | False |
| bhearsum  | 3 | [bug 1444391](https://bugzil.la/1444391)        | accidentally changed org.mozilla.firefox description to "Firefox for Android Beta" | True | True |

