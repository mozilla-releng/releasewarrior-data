# thunderbird 60.0b11

### Date of go-to-build: 2018-08-24

## Preflight tasks (pre go-to-build)
- none

## Build 5  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/bPsFpJRZR4m-TlnLISq6Iw) bPsFpJRZR4m-TlnLISq6Iw
* [push](https://tools.taskcluster.net/push-inspector/#/ezksyp7MSuCY0TAohe-jAA) ezksyp7MSuCY0TAohe-jAA
* [ship](https://tools.taskcluster.net/push-inspector/#/EKtAMJMzR0aqoMRF7aj5sA) EKtAMJMzR0aqoMRF7aj5sA
```
export PROMOTE_TASK_ID=bPsFpJRZR4m-TlnLISq6Iw
export PUSH_TASK_ID=ezksyp7MSuCY0TAohe-jAA
export SHIP_TASK_ID=EKtAMJMzR0aqoMRF7aj5sA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1486475](https://bugzil.la/1486475)        | releaserunner failed to mark build as started in shipit-v1, causing a second promote action to be created. This led to duplicate complete.mar entries in the balrog blob (as per Bug 1389312). | False | True |

## Build 4  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Ey3NP1CQS0WBpQ-YIL3bdw) Ey3NP1CQS0WBpQ-YIL3bdw
```
export PROMOTE_TASK_ID=Ey3NP1CQS0WBpQ-YIL3bdw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1486475](https://bugzil.la/1486475)        | releaserunner failed to mark build as started in shipit-v1, causing a second promote action to be created. This led to duplicate complete.mar entries in the balrog blob (as per Bug 1389312). | False | True |
| nthomas  | 2 | [bug 1439860](https://bugzil.la/1439860)        | update verify failures on Windows due to malformed complete mar files, bug 1439860 needs backout on esr60 verbranch | True | False |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1486475](https://bugzil.la/1486475)        | releaserunner failed to mark build as started in shipit-v1, causing a second promote action to be created. This led to duplicate complete.mar entries in the balrog blob (as per Bug 1389312). | False | True |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/FsmUIQLmSaGO1J6IRxS5Tg) FsmUIQLmSaGO1J6IRxS5Tg
```
export PROMOTE_TASK_ID=FsmUIQLmSaGO1J6IRxS5Tg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1486475](https://bugzil.la/1486475)        | releaserunner failed to mark build as started in shipit-v1, causing a second promote action to be created. This led to duplicate complete.mar entries in the balrog blob (as per Bug 1389312). | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/XSe_872TTNCMyzPtXsL-ig) XSe_872TTNCMyzPtXsL-ig
```
export PROMOTE_TASK_ID=XSe_872TTNCMyzPtXsL-ig
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| tomprince  | 1 | [bug 1466222](https://bugzil.la/1466222)        | Misisng backports | True | False |

