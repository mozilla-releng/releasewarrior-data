# firefox 60.0b6

### Date of go-to-build: 2018-03-22

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Ar8c5e3_T_iHbJlzBP56FA) Ar8c5e3_T_iHbJlzBP56FA
* [push](https://tools.taskcluster.net/push-inspector/#/Ikhsz6f0SMqBXsnmNZJDog) Ikhsz6f0SMqBXsnmNZJDog
* [ship](https://tools.taskcluster.net/push-inspector/#/d6Ua9OQ1RzyalfBdwYCQxg) d6Ua9OQ1RzyalfBdwYCQxg


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1448239](https://bugzil.la/1448239)        | Snap build failed: 404 when downloading libtiff5-dev_4.0.6-1ubuntu0.3_amd64.deb. Temporarilly resolved by submitting https://tools.taskcluster.net/groups/Ar8c5e3_T_iHbJlzBP56FA/tasks/az361OxlRqCRJsRkveXfmg | True | True |
| jlorenzo  | 2 | [bug 1448377 ](https://bugzil.la/1448377 )        | Bug 1448377 - Balrog doesn't enact scheduled changes anymore | False | True |

