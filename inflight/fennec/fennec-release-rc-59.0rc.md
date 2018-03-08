# fennec 59.0rc

### Date of go-to-build: 2018-03-01

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-03-05 - [bug none](https://bugzil.la/none): [jlorenzo] Workaround in case the fennec_rc taskgraph isn't ready yet: when the promote action graph is submitted, cancel the "google-play-strings" task (for instance https://tools.taskcluster.net/groups/BFxmYjjZQRynxfeInleESg/tasks/MN0K1JIDTbWqfe7TmIJ2pw/details). Then, push-apk will detect no strings and will skip the part where they get updated. This ensures we don't promote Firefox 59 publicly on Google Play, on the release product.

## Build 1  

### Graphs
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship-rc)  - run ship-rc
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto-rc.md#ship)  - mark the release as shipped

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

