# devedition 60.0b1

### Date of go-to-build: 2018-03-02

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-03-01 - [bug none](https://bugzil.la/none): [jlorenzo] I just chatted with jcristau. He would like to kick off a devedition build with what's currently on beta (i.e.: no extra patch since mergeday). Julien doesn't want more patches in the product (but doesn't care too much about the TC changes). Therefore, I uplifted the bouncer and version bump to beta.

## Build 3  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/SdybP-zoSbaWp1x6FdHW1A) SdybP-zoSbaWp1x6FdHW1A
* [push](https://tools.taskcluster.net/push-inspector/#/EOlNVHbfS76aswxZlsjuwQ) EOlNVHbfS76aswxZlsjuwQ


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| mihaitabara  | 1 | [bug 1398796](https://bugzil.la/1398796)        | bouncer check (formerly known 'uptake monitoring') fails for en-US builds during 60.0b1 | False | True |
| mihaitabara  | 2 | [bug 1443104](https://bugzil.la/1443104)        | Update verification fails as well. Most likely related to bouncer check errors." | False | True |

## Build 2  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/ZNS-m-xcRAWJ3FWzL4byMQ) ZNS-m-xcRAWJ3FWzL4byMQ


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug 1432219](https://bugzil.la/1432219)        | generate-checksums-beetmover failed with a cot error | True | False |
| bhearsum  | 2 | [bug ](https://bugzil.la/)        | numerous update verify failures caused by repeated failed downloads - reruns greened things up | True | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/RKcena0UR0-zuryWgN3B2w) RKcena0UR0-zuryWgN3B2w


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| bhearsum  | 1 | [bug none](https://bugzil.la/none)        | in-tree code tried to use beetmoverworker-dev instead of production beetmoverworker | True | False |

