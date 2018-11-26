# devedition 64.0b12

### Date of go-to-build: 2018-11-22

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/USzychG6QQCdkzutn7Ws_w) USzychG6QQCdkzutn7Ws_w
* [push](https://tools.taskcluster.net/push-inspector/#/BBC-NmKdR9mpyXd3XjCMsg) BBC-NmKdR9mpyXd3XjCMsg
* [ship](https://tools.taskcluster.net/push-inspector/#/DIVx4DIpQF-2bY4c9HiPTg) DIVx4DIpQF-2bY4c9HiPTg
```
export PROMOTE_TASK_ID=USzychG6QQCdkzutn7Ws_w
export PUSH_TASK_ID=BBC-NmKdR9mpyXd3XjCMsg
export SHIP_TASK_ID=DIVx4DIpQF-2bY4c9HiPTg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1502269](https://bugzil.la/1502269)        | nightly l10n docker-worker task exceeded run time. assuming it never downloaded and started the docker image. cancelled+rerun | False | True |

