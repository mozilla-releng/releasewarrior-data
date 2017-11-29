# firefox 57.0.1

### Date of go-to-build: 2017-11-28

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/OS7RbckhT5Stq0veDue6-A)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Descripiton                | Release Unblocked       | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1421535](http://bugzilla/1421535)        | UV tasks failing. localtest/cdntest pointed to old 57.0 wnp blobs rather than 57.0.1. Updated 4 wnp rules in both local and cdntest. Still failing. Need the special hack to query balrog properly, rerunning with that | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/JdNt2YXDQza7VIFbXTu2-A)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Descripiton                | Release Unblocked       | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1421535](http://bugzilla/1421535)        | UV tasks failing. localtest/cdntest pointed to old 57.0 wnp blobs rather than 57.0.1. Updated 4 wnp rules in both local and cdntest. Still failing. Need the special hack to query balrog properly, rerunning with that | False | True |

