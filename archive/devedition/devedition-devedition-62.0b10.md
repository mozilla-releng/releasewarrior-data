# devedition 62.0b10

### Date of go-to-build: 2018-07-19

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/JZ3EEfOLQ2KlDPO2a3RqJw) JZ3EEfOLQ2KlDPO2a3RqJw
* [push](https://tools.taskcluster.net/push-inspector/#/D7t83SW6Sby7penpGRS5Dg) D7t83SW6Sby7penpGRS5Dg
* [ship](https://tools.taskcluster.net/push-inspector/#/ai0djtfvTbOgUeGaa8cM1w) ai0djtfvTbOgUeGaa8cM1w
```
export PROMOTE_TASK_ID=JZ3EEfOLQ2KlDPO2a3RqJw
export PUSH_TASK_ID=D7t83SW6Sby7penpGRS5Dg
export SHIP_TASK_ID=ai0djtfvTbOgUeGaa8cM1w
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1477097](https://bugzil.la/1477097)        | task stuck as unscheduled even with all deps resolved, possible issue with queue dependency resolver ZWRKPgonRayyySrhHfnp7w | True | True |

