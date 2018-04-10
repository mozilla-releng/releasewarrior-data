# firefox 60.0b11

### Date of go-to-build: 2018-04-09

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/XP_KLzLiSSq8ApFDzZrtFA) XP_KLzLiSSq8ApFDzZrtFA
* [push](https://tools.taskcluster.net/push-inspector/#/BH0QdNzbQ8iLXlM28cQ4jw) BH0QdNzbQ8iLXlM28cQ4jw
* [ship](https://tools.taskcluster.net/push-inspector/#/XEouISD6RvaNz3cDTJwJVw) XEouISD6RvaNz3cDTJwJVw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1452759](https://bugzil.la/1452759)        | bad cot signature for >20k char tasks. partner configs slipped in, but we need a docker-worker fix for the underlying issue | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | cancelling a -notify task will send email (e.g., "fx 60.0b11 in candidates dir" on cancelling the graph) | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | 404 for bouncer-check; should we retry more intelligently? | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/FQ2qRYLCQPGpwT4Nz1fjIg) FQ2qRYLCQPGpwT4Nz1fjIg


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1452759](https://bugzil.la/1452759)        | bad cot signature for >20k char tasks. partner configs slipped in, but we need a docker-worker fix for the underlying issue | False | True |

