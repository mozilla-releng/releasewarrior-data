# firefox 63.0b13

### Date of go-to-build: 2018-10-08

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/f6y2sZfiQoW_tvhikLc9bQ) f6y2sZfiQoW_tvhikLc9bQ
* [push](https://tools.taskcluster.net/push-inspector/#/BojoOLA9TF6N9TiCH7vHuQ) BojoOLA9TF6N9TiCH7vHuQ
```
export PROMOTE_TASK_ID=f6y2sZfiQoW_tvhikLc9bQ
export PUSH_TASK_ID=BojoOLA9TF6N9TiCH7vHuQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1318173](https://bugzil.la/1318173)        | eme-free win32 pl repackage, repackage-l10n win64 pt-PT failed hg clone | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | partials es-MX win64 timed out during clamav update | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | UV timeouts (force kill container after 3600 seconds) | True | True |

