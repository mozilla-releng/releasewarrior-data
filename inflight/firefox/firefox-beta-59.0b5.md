# firefox 59.0b5

### Date of go-to-build: 2018-01-29

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/WBr4quElQW2_grYrFH14HA)
[task group](https://tools.taskcluster.net/push-inspector/#/fIWaEYYEQCizNALRH-9Igg)
[task group](https://tools.taskcluster.net/push-inspector/#/a70JcAtcSNuxoxEWxat8wQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1433809](https://bugzil.la/1433809)        | Missing SHA*SUMS files | True | True |
| jlund  | 2 | [bug 1433809](https://bugzil.la/1433809)        | push graph was generated before promote graph finished and dependencies ignore checksums artifacts. We need to first make sure if KEY, SHA512SUMS made it to releases dir. If it did not, we need to do something like https://bugzilla.mozilla.org/show_bug.cgi?id=1433809#c1 but for devedition 59.0 | True | False |

