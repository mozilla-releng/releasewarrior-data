# firefox 59.0.2

### Date of go-to-build: 2018-03-23

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/C8N0d-bATh61Ao8qwA-i_Q) C8N0d-bATh61Ao8qwA-i_Q
* [push](https://tools.taskcluster.net/push-inspector/#/ScnkAhV0Tdm8_H5j8Ln9Ng) ScnkAhV0Tdm8_H5j8Ln9Ng
* [ship](https://tools.taskcluster.net/push-inspector/#/Mnes1fBTRKuj0_hmmKz-Yw) Mnes1fBTRKuj0_hmmKz-Yw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | both ryan and i reran the same repackage task, then ryan cancelled his (latest). i had to cancel the repackage-signing task, then rerun both in order. this could have forced us to do a build2 if it wasn't caught in time. we should consider moving off treeherder and into a releaseduty dashboard, and/or going with stricter handoffs | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | release-updates-builder-firefox died trying to use the v4 submitter (buildbot) | True | False |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | snap failed | True | True |
| asasaki  | 4 | [bug none](https://bugzil.la/none)        | repackages and partials continue to be flaky, requiring people to rerun tasks. if these were robust, we wouldn't have hit the double rerun conflict | False | True |

