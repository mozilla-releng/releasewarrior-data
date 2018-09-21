# firefox 63.0b8

### Date of go-to-build: 2018-09-20

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/EjriZedLRoeG55XhMZ_enA) EjriZedLRoeG55XhMZ_enA
* [push](https://tools.taskcluster.net/push-inspector/#/CTU6CA-PTGyDBu4IExIgoA) CTU6CA-PTGyDBu4IExIgoA
* [ship](https://tools.taskcluster.net/push-inspector/#/GT-f8ebSRomsoC9k2ZQHUA) GT-f8ebSRomsoC9k2ZQHUA
```
export PROMOTE_TASK_ID=EjriZedLRoeG55XhMZ_enA
export PUSH_TASK_ID=CTU6CA-PTGyDBu4IExIgoA
export SHIP_TASK_ID=GT-f8ebSRomsoC9k2ZQHUA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | prematurely shipped fx 63.0b8. cancelled ship graph; need to run `tc-filter.py --graph-id GT-f8ebSRomsoC9k2ZQHUA --state exception --action rerun` to ship | False | True |
| nthomas  | 2 | [bug 1493056](https://bugzil.la/1493056)        | Partner repackage jobs fail to download upstream artifact, and try to chmod a mar util we don't need. We re-enable partner & EME-free at b8 and determined with RyanVM we wouldn't block shipping on this. To force promote to continue we used 'taskluster task rerun' on release-generate-checksums (ZUNzA7VNQMyGIfb6ujoCgA) | True | False |
| nthomas  | 3 | [bug 1493053](https://bugzil.la/1493053)        | release-snap-push-firefox needs xdelta3 tool | False | True |
| mtabara  | 4 | [bug 1493071](https://bugzil.la/1493071)        | bouncer check mistakenly runs as part of the push graph(s) | False | True |

