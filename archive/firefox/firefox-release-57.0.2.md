# firefox 57.0.2

### Date of go-to-build: 2017-12-01

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/DrBVs1VKQ8eeIwZsPUr0sQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [x] 3.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c6)  - after candidates are complete, create wnp blobs for the four rules in both localtest and cdntest. Patch Patcher configs for update verify to pass, rerun any failed update verify tasks that missed this fix in mean time.
- [x] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [x] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | repack bbb task YvH9LOYBSam7sKOWPiA3Bg spot instance killed while running desktop_l10n.py reran | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/dXW9QkLrQ_i3FW0m1L4COA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [ ] 3.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c5)  - after candidates are complete, create wnp blobs for the four rules in both localtest and cdntest. Patch Patcher configs for update verify to pass, rerun any failed update verify tasks that missed this fix in mean time.
- [ ] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1423663](https://bugzil.la/1423663)        | Docker generation for ubuntu:vivid distro failing due to EOL of vivid. Affected funsize and beetmover. Pushed a fix to repos. | True | False |

