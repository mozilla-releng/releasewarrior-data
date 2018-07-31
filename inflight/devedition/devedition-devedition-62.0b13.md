# devedition 62.0b13

### Date of go-to-build: 2018-07-30

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Kd064_lNTcqZFlZCwO4l5A) Kd064_lNTcqZFlZCwO4l5A
* [push](https://tools.taskcluster.net/push-inspector/#/FQYFwGvESvmvfLmRk9Wjaw) FQYFwGvESvmvfLmRk9Wjaw
* [ship](https://tools.taskcluster.net/push-inspector/#/ZzPRQZmzRAeZqdXwDekjWw) ZzPRQZmzRAeZqdXwDekjWw
```
export PROMOTE_TASK_ID=Kd064_lNTcqZFlZCwO4l5A
export PUSH_TASK_ID=FQYFwGvESvmvfLmRk9Wjaw
export SHIP_TASK_ID=ZzPRQZmzRAeZqdXwDekjWw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1341116](https://bugzil.la/1341116)        | Rotated beetmover credenetials didn't have devedition permissions | True | False |

