# firefox 58.0rc

### Date of go-to-build: 2018-01-15

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-01-15 - [bug 1415557](https://bugzil.la/1415557): this is actually a post gtb human task but we are limited in rw and can't create ad-hoc tasks until after gtb. We should merge, fix conflicts of the patcher patch we have needed since 57.0. Context: https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c9 and recent example tools patch with required retagging can be found here: https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8 *Note*: we still need proper docs on how to do this I believe.

## Build 6  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/NTzcMXyoTdaaAXvCqJKPtQ)
[task group](https://tools.taskcluster.net/push-inspector/#/AtQ39aLrRPae7xT5-RjPPA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c16)  - A tools patch that truncates UV tests for <57.0.4 for linux/mac and <56.0 for win. This reflects our watershed state and release-localtest. The tools repo will need to be retagged with the patcher config changes. Context in the bug. Note, we don't need the OS_VERSION patches previously.
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [x] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://hg.mozilla.org/users/bhearsum_mozilla.com/tools/file/update-status/scripts/updates/)  - Create BenScript config for 58.0 WNP, and run against release-cdntest
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 9.  - Create POA for Firefox Balrog rules, to make 'release' match 'release-cdntest'
- [ ] 10.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 11.  - Run BenScript 58.0 WNP config against 'release' channel.

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

## Build 5  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/bYGCZwkjSQOBrPtTU9BuCg)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c16)  - A tools patch that truncates UV tests for <57.0.4 for linux/mac and <56.0 for win. This reflects our watershed state and release-localtest. The tools repo will need to be retagged with the patcher config changes. Context in the bug. Note, we don't need the OS_VERSION patches previously.
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1431381](https://bugzil.la/1431381)        | Partials generation broken with construct exception (due to missing package pins) -- Release only due to funsize balrog docker being seperate | True | True |

## Build 4  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/ZQ5x4-6dR7W5DBGSIryEYg)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c16)  - A tools patch that truncates UV tests for <57.0.4 for linux/mac and <56.0 for win. This reflects our watershed state and release-localtest. The tools repo will need to be retagged with the patcher config changes. Context in the bug. Note, we don't need the OS_VERSION patches previously.
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1431381](https://bugzil.la/1431381)        | Partials generation broken with construct exception (due to missing package pins) | True | True |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/ELmfX3koT0GN-In8__rgXA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c16)  - A tools patch that truncates UV tests for <57.0.4 for linux/mac and <56.0 for win. This reflects our watershed state and release-localtest. The tools repo will need to be retagged with the patcher config changes. Context in the bug. Note, we don't need the OS_VERSION patches previously.
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1430535](https://bugzil.la/1430535)        | Despite backout of bug 1418425 and CDN purge in bug 1430597, we got CRC errors for partials | True | False |
| nthomas  | 2 | [bug 1415557](https://bugzil.la/1415557)        | Update verify failures from testing updates from behind the watersheds at 57.0.4 (linux & mac) and 56.0 (win) | True | True |
| jlund  | 3 | [bug 1430670](https://bugzil.la/1430670)        | AWS network issues causing lot's of failures over the network. Tasks need to be rerun. Something like: https://irccloud.mozilla.com/pastebin/LulhGcoq/ | True | False |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/cynEWCkRSZyGzr5qg_6fTA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c16)  - A tools patch that truncates UV tests for <57.0.4 for linux/mac and <56.0 for win. This reflects our watershed state and release-localtest. The tools repo will need to be retagged with the patcher config changes. Context in the bug. Note, we don't need the OS_VERSION patches previously.
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1430535](https://bugzil.la/1430535)        | Despite backout of bug 1418425 and CDN purge in bug 1430597, we got CRC errors for partials | False | True |
| nthomas  | 2 | [bug 1415557](https://bugzil.la/1415557)        | Update verify failures from testing updates from behind the watersheds at 57.0.4 (linux & mac) and 56.0 (win) | False | True |
| jlund  | 3 | [bug 1430670](https://bugzil.la/1430670)        | AWS network issues causing lot's of failures over the network. Tasks need to be rerun. Something like: https://irccloud.mozilla.com/pastebin/LulhGcoq/ | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/HQFXrJxVQbi-Rqcpv41Thw)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1430535](https://bugzil.la/1430535)        | Despite backout of bug 1418425 and CDN purge in bug 1430597, we got CRC errors for partials | False | True |
| nthomas  | 2 | [bug 1415557](https://bugzil.la/1415557)        | Update verify failures from testing updates from behind the watersheds at 57.0.4 (linux & mac) and 56.0 (win) | False | True |

