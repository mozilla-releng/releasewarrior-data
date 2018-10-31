# firefox 63.0.1

### Date of go-to-build: 2018-10-30

## Preflight tasks (pre go-to-build)
- none

## Build 4  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/eAQCnoHFQtKgrtaNXSZTYA) eAQCnoHFQtKgrtaNXSZTYA
* [push](https://tools.taskcluster.net/push-inspector/#/aOb4yk0fTiC3insIp7LaGA) aOb4yk0fTiC3insIp7LaGA
* [ship](https://tools.taskcluster.net/push-inspector/#/Ks9Gohi0TrG-K18VG0eqNg) Ks9Gohi0TrG-K18VG0eqNg
```
export PROMOTE_TASK_ID=eAQCnoHFQtKgrtaNXSZTYA
export PUSH_TASK_ID=aOb4yk0fTiC3insIp7LaGA
export SHIP_TASK_ID=Ks9Gohi0TrG-K18VG0eqNg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog
- [x] 6.  - bump the firefox-election-edition bouncer entries when 63.0.1 ships

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1503430](https://bugzil.la/1503430)        | promotion action task timed out. may have submitted graph anyway. second run, run1 also hung. cancelled graph and triggered build1-4. see bug for resolution | True | True |
| callek  | 2 | [bug none](https://bugzil.la/none)        | hg clone issue getting clonebundle from s3 (N4FUF0XYSD6NF88NetNxug) | True | True |
| callek  | 3 | [bug none](https://bugzil.la/none)        | using 'release wnp_blob' for 63.0.1 build 4 was finding build 3 and erroring because of lack of locale lists | True | True |
| callek  | 4 | [bug 1495714](https://bugzil.la/1495714)        | Release Blob gets corrupted when manually updated | True | True |
| callek  | 5 | [bug 1495464](https://bugzil.la/1495464)        | Treescript worker hard codes hgrc which meant todays hgfingerprint swap broke it, rectified with a swap in hardcoded file and deploy. Long term solution pending someone working on [Issue 12](https://github.com/mozilla-releng/treescript/issues/12) | True | True |

## Build 3  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
```
```
task graph url: unknown


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | promotion action task timed out. may have submitted graph anyway. second run, run1 also hung. cancelled graph and triggered build2 | False | True |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/E0yoL16jTu-PenRG_2Dsgg) E0yoL16jTu-PenRG_2Dsgg
```
export PROMOTE_TASK_ID=E0yoL16jTu-PenRG_2Dsgg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | promotion action task timed out. may have submitted graph anyway. second run, run1 also hung. cancelled graph and triggered build2 | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/bKu596bqSRC1Lmd67jJj_A) bKu596bqSRC1Lmd67jJj_A
```
export PROMOTE_TASK_ID=bKu596bqSRC1Lmd67jJj_A
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | promotion action task timed out. may have submitted graph anyway. second run, run1 also hung. cancelled graph and triggered build2 | False | True |

