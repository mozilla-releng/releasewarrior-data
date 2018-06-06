# firefox 60.0.2esr

### Date of go-to-build: 2018-06-05

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/U06V9maQTPC6S6fwNjCAUA) U06V9maQTPC6S6fwNjCAUA
* [push](https://tools.taskcluster.net/push-inspector/#/ewjZyCU-TnKpFy_HvCzRzA) ewjZyCU-TnKpFy_HvCzRzA
* [ship](https://tools.taskcluster.net/push-inspector/#/WwojF4BMQO-sYA8eE-QuoQ) WwojF4BMQO-sYA8eE-QuoQ
```
export PROMOTE_TASK_ID=U06V9maQTPC6S6fwNjCAUA
export PUSH_TASK_ID=ewjZyCU-TnKpFy_HvCzRzA
export SHIP_TASK_ID=WwojF4BMQO-sYA8eE-QuoQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| mtabara  | 1 | [bug none](https://bugzil.la/none)        | missing UV patch uplift from esr60 relbranch. canceling build1, uplift, triggering build2 | True | True |
| jlund  | 2 | [bug none](https://bugzil.la/none)        | bouncer check failing as it expects sha1 artifacts to exist even though it shouldn't. We are ignoring the reported sha1 failures. leaving as future threat for 60esr until we file ticket and fix bouncer-check configuration. IJaOKI8vQ8SrsrKqIjWbVg | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/EXIaI_l4TMWeHm7_c8AhEg) EXIaI_l4TMWeHm7_c8AhEg
```
export PROMOTE_TASK_ID=EXIaI_l4TMWeHm7_c8AhEg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

