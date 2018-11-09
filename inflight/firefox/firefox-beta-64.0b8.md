# firefox 64.0b8

### Date of go-to-build: 2018-11-08

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/ewtfeGF9Rp2pEaxZLd_Ang) ewtfeGF9Rp2pEaxZLd_Ang
* [push](https://tools.taskcluster.net/push-inspector/#/ZJrGmBA1TYOqNJk5z2K2ow) ZJrGmBA1TYOqNJk5z2K2ow
* [ship](https://tools.taskcluster.net/push-inspector/#/R9ILdjCPSbi_wiZF0jZ-Vw) R9ILdjCPSbi_wiZF0jZ-Vw
```
export PROMOTE_TASK_ID=ewtfeGF9Rp2pEaxZLd_Ang
export PUSH_TASK_ID=ZJrGmBA1TYOqNJk5z2K2ow
export SHIP_TASK_ID=R9ILdjCPSbi_wiZF0jZ-Vw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1474156](https://bugzil.la/1474156)        | clamav timed out in a partials task (HEAdG8AJSGqASz8_GMTZcA) | False | True |

