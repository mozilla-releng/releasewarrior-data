# firefox 62.0b4

### Date of go-to-build: 2018-06-28

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/aLiIaUbaSMq1v6eHCXWjOw) aLiIaUbaSMq1v6eHCXWjOw
* [push](https://tools.taskcluster.net/push-inspector/#/Za7glbBUR9msnKp_Xc470A) Za7glbBUR9msnKp_Xc470A
* [ship](https://tools.taskcluster.net/push-inspector/#/JKLW8GTvSz6TFI6nhxLlpQ) JKLW8GTvSz6TFI6nhxLlpQ
```
export PROMOTE_TASK_ID=aLiIaUbaSMq1v6eHCXWjOw
export PUSH_TASK_ID=Za7glbBUR9msnKp_Xc470A
export SHIP_TASK_ID=JKLW8GTvSz6TFI6nhxLlpQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1466627](https://bugzil.la/1466627)        | https://hg.mozilla.org/releases/mozilla-beta/rev/5ba0247433fe didn't make the beta builds. Mark as ship will fail. We just need to use the ship-it web UI (the old one) to mark the release as shipped. Kudos to Mihai for warning us. | False | True |

