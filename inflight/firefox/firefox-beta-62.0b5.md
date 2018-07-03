# firefox 62.0b5

### Date of go-to-build: 2018-07-02

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/fOyFWZPXQP6E2hktOPH-RA) fOyFWZPXQP6E2hktOPH-RA
* [push](https://tools.taskcluster.net/push-inspector/#/b2bFGIoKSDONa0XohSVqRw) b2bFGIoKSDONa0XohSVqRw
```
export PROMOTE_TASK_ID=fOyFWZPXQP6E2hktOPH-RA
export PUSH_TASK_ID=b2bFGIoKSDONa0XohSVqRw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | repackage-l10n-mai-win32-nightly bUByc-Y_TiCsGG7HYf6M6w - failed to checkout. rerunning | True | True |
| jlorenzo  | 2 | [bug 1472929](https://bugzil.la/1472929)        | Intermittent: Update verify, cannot download mar: Error 500 from cloudfront | True | True |
| jlorenzo  | 3 | [bug 1472930](https://bugzil.la/1472930)        | Update verify, Task timeout after 7200 seconds. Force killing container. | False | True |

