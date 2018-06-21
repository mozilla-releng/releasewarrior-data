# thunderbird 60.0b8

### Date of go-to-build: 2018-06-19

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/cQrInTw0QH-C9i9PmROdzg) cQrInTw0QH-C9i9PmROdzg
* [push](https://tools.taskcluster.net/push-inspector/#/BC3qiHD2QfC2YwnFOO8O6g) BC3qiHD2QfC2YwnFOO8O6g
```
export PROMOTE_TASK_ID=cQrInTw0QH-C9i9PmROdzg
export PUSH_TASK_ID=BC3qiHD2QfC2YwnFOO8O6g
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug none](https://bugzil.la/none)        | treescript doesn't bump the version on a relbranch, if one is being used | True | True |

