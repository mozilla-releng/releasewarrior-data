# firefox 62.0b12

### Date of go-to-build: 2018-07-26

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/fOSdPGEjSBCpyp0tAm7zFA) fOSdPGEjSBCpyp0tAm7zFA
* [push](https://tools.taskcluster.net/push-inspector/#/D_S0DF9DSBOZyb2j4_Vh6Q) D_S0DF9DSBOZyb2j4_Vh6Q
* [ship](https://tools.taskcluster.net/push-inspector/#/UW3tcdmvS8ajOfxjRCemZg) UW3tcdmvS8ajOfxjRCemZg
```
export PROMOTE_TASK_ID=fOSdPGEjSBCpyp0tAm7zFA
export PUSH_TASK_ID=D_S0DF9DSBOZyb2j4_Vh6Q
export SHIP_TASK_ID=UW3tcdmvS8ajOfxjRCemZg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlorenzo  | 1 | [bug 1478997](https://bugzil.la/1478997)        | treescript.exceptions.ChangesetMismatchError: Expected 2 changesets to push, found 1 | False | True |

