# devedition 59.0b5

### Date of go-to-build: 2018-01-29

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/ZTnivi7NRJKaCRCLX31JaA)
[task group](https://tools.taskcluster.net/push-inspector/#/eA7lRewxSwqB8IR05_G37A)
[task group](https://tools.taskcluster.net/push-inspector/#/dgTb_k4kRhapv2Mu4OfLDw)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#publish-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1433809](https://bugzil.la/1433809)        | Missing SHA*SUMS files | True | True |
| nthomas  | 2 | [bug none](https://bugzil.la/none)        | cot failure in win32 signing job (f400phKcTOewjOZ7qXxI8g) due to 500 from queue.taskcluster.net | True | False |
| jlund  | 3 | [bug 1433809](https://bugzil.la/1433809)        | push graph was generated before promote graph finished and dependencies ignore checksums artifacts. We need to first make sure if KEY, SHA512SUMS made it to releases dir. If it did not, we need to do something like https://bugzilla.mozilla.org/show_bug.cgi?id=1433809#c1 but for devedition 59.0b5 | True | False |

