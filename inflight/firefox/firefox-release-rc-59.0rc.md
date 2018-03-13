# firefox 59.0rc

### Date of go-to-build: 2018-03-05

## Preflight tasks (pre go-to-build)
- none

## Build 5  

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/X-UA6oNqSfCCX25A-LDr-A) X-UA6oNqSfCCX25A-LDr-A
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/WXtFK0QoSO-qnHY2vcE0Fg) WXtFK0QoSO-qnHY2vcE0Fg
* [push](https://tools.taskcluster.net/push-inspector/#/QK0wvF5lROqwGPeTI-_KAw) QK0wvF5lROqwGPeTI-_KAw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  - Set up WNP on release-localtest so QE can early test blobs and rules. Context: https://bugzilla.mozilla.org/show_bug.cgi?id=1438653#c7 
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - publish in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug issue](https://bugzil.la/issue)        | snap failed with KeyError: '"status"' | False | True |
| mihaitabara  | 2 | [bug none](https://bugzil.la/none)        | snap failed with KeyError: '\"status\"' | False | True |
| nthomas  | 3 | [bug none](https://bugzil.la/none)        | 58.0 WNP rules where still on release-cdntest (699 and 732). Removed them to unblock QA. We'll need to remove 677 and 733 to push to release. | False | True |

## Build 4  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/N8hCeDl0Qty2PM3ukpcmmw) N8hCeDl0Qty2PM3ukpcmmw
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/d6LwEWeNSHKIp5sT5HbMVA) d6LwEWeNSHKIp5sT5HbMVA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  - Set up WNP on release-localtest so QE can early test blobs and rules. Context: https://bugzilla.mozilla.org/show_bug.cgi?id=1438653#c7 
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - publish in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug issue](https://bugzil.la/issue)        | snap failed with KeyError: '"status"' | False | True |
| bhearsum  | 2 | [bug none](https://bugzil.la/none)        | lots of confusion around the locale list for WNP. can we ask relman or whomever owns it to give us the list upfront? | True | True |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/SjeNNvPdStWuuvjJp4PUBA) SjeNNvPdStWuuvjJp4PUBA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - publish in Balrog on beta channel
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug none](https://bugzil.la/none)        | same scope issues as build2 - it looks like it didn't actually get added between build2 and build3 | True | False |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/Y82yfN7lTuKFwhRb6_WX8g) Y82yfN7lTuKFwhRb6_WX8g


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - publish in Balrog on beta channel
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug 1443432](https://bugzil.la/1443432)        | IF WE ARE SHIPPING 59.0build1, talk to jlorenzo and mkaply about manual steps needed for snap. not needed for build2 | True | False |
| bhearsum  | 2 | [bug none](https://bugzil.la/none)        | missing secrets:get:project/releng/snapcraft/firefox/candidate scope | True | False |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote_rc](https://tools.taskcluster.net/push-inspector/#/S3Ygsrn8QfuFvBXK5nAXlw) S3Ygsrn8QfuFvBXK5nAXlw
* [ship_rc](https://tools.taskcluster.net/push-inspector/#/F15arWGbTqCE_90xxLOkdw) F15arWGbTqCE_90xxLOkdw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship-rc)  - publish in Balrog on beta channel
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#push)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md#ship)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug 1443335](https://bugzil.la/1443335)        | release-snap builder failed because it couldn't find credentials | True | False |
| bhearsum  | 2 | [bug 1443432](https://bugzil.la/1443432)        | IF WE ARE SHIPPING 59.0build1, talk to jlorenzo and mkaply about manual steps needed for snap. not needed for build2 | False | True |

