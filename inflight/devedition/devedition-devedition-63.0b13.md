# devedition 63.0b13

### Date of go-to-build: 2018-10-08

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/HbAIAmQXQaSQsngxfbV7Tw) HbAIAmQXQaSQsngxfbV7Tw
* [push](https://tools.taskcluster.net/push-inspector/#/Fh19ooV4RRS58YG0_8orJQ) Fh19ooV4RRS58YG0_8orJQ
```
export PROMOTE_TASK_ID=HbAIAmQXQaSQsngxfbV7Tw
export PUSH_TASK_ID=Fh19ooV4RRS58YG0_8orJQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1371378](https://bugzil.la/1371378)        | hg clone failed grabbing bundle for l10n e8T1mdOkQQm45DJ3pSNQyw | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | UV timeouts (force kill container after 3600 seconds) | True | True |

