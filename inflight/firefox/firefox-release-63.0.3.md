# firefox 63.0.3

### Date of go-to-build: 2018-11-14

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/T_T6tbxBSYGIuZUu4dsc7A) T_T6tbxBSYGIuZUu4dsc7A
* [push](https://tools.taskcluster.net/push-inspector/#/NZF0P14CRziO4gby6xrhRQ) NZF0P14CRziO4gby6xrhRQ
* [ship](https://tools.taskcluster.net/push-inspector/#/ChrbdLIZSuiiaN4ddrOIbA) ChrbdLIZSuiiaN4ddrOIbA
```
export PROMOTE_TASK_ID=T_T6tbxBSYGIuZUu4dsc7A
export PUSH_TASK_ID=NZF0P14CRziO4gby6xrhRQ
export SHIP_TASK_ID=ChrbdLIZSuiiaN4ddrOIbA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto-rc.md)  - setup whatsnew page
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#bump-the-election-edition-bouncer-entries)  - bump the firefox-election-edition bouncer locations
- [x] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](https://bugzil.la/none)        | hg clone error in NlTnz9hfRm-0nw6nXH2uNw (mac EME-free repackage) and A0fiwGiqRzCRAyOOwUE4Ng (mac yandex repackage) | True | True |

