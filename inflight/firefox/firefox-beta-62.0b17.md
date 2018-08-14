# firefox 62.0b17

### Date of go-to-build: 2018-08-13

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/PJrZEHImSmOhZAznyA3dZQ) PJrZEHImSmOhZAznyA3dZQ
* [push](https://tools.taskcluster.net/push-inspector/#/MDS5wC0rRFqstxwJU4n3Gw) MDS5wC0rRFqstxwJU4n3Gw
```
export PROMOTE_TASK_ID=PJrZEHImSmOhZAznyA3dZQ
export PUSH_TASK_ID=MDS5wC0rRFqstxwJU4n3Gw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug none](https://bugzil.la/none)        | shipit release email never went through. graphs started. shipit frontend looked good. nthomas is investigating with nli | False | True |

