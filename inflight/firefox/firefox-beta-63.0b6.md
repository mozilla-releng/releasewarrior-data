# firefox 63.0b6

### Date of go-to-build: 2018-09-13

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/VDJY49MCTrOn8bi6uFASAA) VDJY49MCTrOn8bi6uFASAA
* [push](https://tools.taskcluster.net/push-inspector/#/U2ZUXzf2Rsyx95EJpLGvzQ) U2ZUXzf2Rsyx95EJpLGvzQ
* [ship](https://tools.taskcluster.net/push-inspector/#/SBrZFJtYQ0-xevu5-jdn0Q) SBrZFJtYQ0-xevu5-jdn0Q
```
export PROMOTE_TASK_ID=VDJY49MCTrOn8bi6uFASAA
export PUSH_TASK_ID=U2ZUXzf2Rsyx95EJpLGvzQ
export SHIP_TASK_ID=SBrZFJtYQ0-xevu5-jdn0Q
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| rail  | 1 | [bug 1491262](https://bugzil.la/1491262)        |  Make snap store push idempotent | True | True |

