# firefox 57.0.4

### Date of go-to-build: 2018-01-03

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/IR_N2kt6QzG67I9Wx_twcw)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - patch patcher configs after we gtb to support JAWS. Similar tools patch needed is linked in how-to
- [x] 3.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - more specifically for wnp, two blobs (official and bz2) and 4 rules (2 official, 2 bz2) are needed to be updated for localtest, cdntest. This can be done after the first update verify task starts. After this and patcher patch is applied, rerun any failed update verify tasks.
- [x] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [x] 5.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c9)  - run bensScript against cdntest (run again after we publish on release and sign off)
- [x] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 8.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - similar to wnp setup for local/cdntest, the 4 release rules should be scheduled to be updated. The two none wnp rules that automation knows about, will be scheduled for sign off automatically
- [ ] 9.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1428026](https://bugzil.la/1428026)        | Repacks on bbb failed to robustcheckout repos: timeout after 1800 seconds | True | True |
| jlorenzo  | 2 | [bug none](https://bugzil.la/none)        | linux UV 12/12 (NC-DCUeyR1Slu6ULaHwZoQ) failed because of linux config off by 3 https://hg.mozilla.org/build/tools/rev/569ed0bb722a#l1.8 (https://hg.mozilla.org/build/tools/rev/352777d48a39#l1.11)  | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - patch patcher configs after we gtb to support JAWS. Similar tools patch needed is linked in how-to
- [ ] 3.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - more specifically for wnp, two blobs (official and bz2) and 4 rules (2 official, 2 bz2) are needed to be updated for localtest, cdntest. This can be done after the first update verify task starts. After this and patcher patch is applied, rerun any failed update verify tasks.
- [ ] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [ ] 5.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c9)  - run bensScript against cdntest (run again after we publish on release and sign off)
- [ ] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 8.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8)  - similar to wnp setup for local/cdntest, the 4 release rules should be scheduled to be updated. The two none wnp rules that automation knows about, will be scheduled for sign off automatically
- [ ] 9.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

