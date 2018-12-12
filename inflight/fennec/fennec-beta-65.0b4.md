# fennec 65.0b4

### Date of go-to-build: 2018-12-11

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/PdRoXaUNRcO6MgPH4P7fww) PdRoXaUNRcO6MgPH4P7fww
* [ship](https://tools.taskcluster.net/push-inspector/#/fZ3gWHNWSruj_SCbNAqfEg) fZ3gWHNWSruj_SCbNAqfEg
```
export PROMOTE_TASK_ID=PdRoXaUNRcO6MgPH4P7fww
export SHIP_TASK_ID=fZ3gWHNWSruj_SCbNAqfEg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/mobile/howto.md)  - run pushapk

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| mtabara  | 1 | [bug 1513564](https://bugzil.la/1513564)        | Google API rejects apk as being invalid. Most likely due to Autograph signing changes that have rolled-out recently. | False | True |

