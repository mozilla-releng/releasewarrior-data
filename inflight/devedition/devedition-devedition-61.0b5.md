# devedition 61.0b5

### Date of go-to-build: 2018-05-14

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/L4FgXyZkSTCOl5wGjOFgLw) L4FgXyZkSTCOl5wGjOFgLw
* [push](https://tools.taskcluster.net/push-inspector/#/XWgqyJTiTFypzkdVFsbeLQ) XWgqyJTiTFypzkdVFsbeLQ
* [ship](https://tools.taskcluster.net/push-inspector/#/X9xdxYvtRLy0gpo5Jk7Qgg) X9xdxYvtRLy0gpo5Jk7Qgg
```
export PROMOTE_TASK_ID=L4FgXyZkSTCOl5wGjOFgLw
export PUSH_TASK_ID=XWgqyJTiTFypzkdVFsbeLQ
export SHIP_TASK_ID=X9xdxYvtRLy0gpo5Jk7Qgg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1461490](https://bugzil.la/1461490)        | UV needs to whitelist certain binary diffs. e.g. ignoring channel-pref when testing rc to a beta. | True | True |

