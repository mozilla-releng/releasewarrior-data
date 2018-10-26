# devedition 64.0b4

### Date of go-to-build: 2018-10-25

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Qk6NbeZST-WjcoW6Umc3mQ) Qk6NbeZST-WjcoW6Umc3mQ
```
export PROMOTE_TASK_ID=Qk6NbeZST-WjcoW6Umc3mQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1502234](https://bugzil.la/1502234)        | beta l10n is broken for locale be and lij. needed manual l10n-changesets.json bump due to l10n typo. build2. more context | True | True |
| jlund  | 2 | [bug 1502245](https://bugzil.la/1502245)        | release-early-tagging tasks between devedition and beta may race pushing to m-b | True | True |
| callek  | 3 | [bug none](https://bugzil.la/none)        | Partials failed due to worker not finding some artifacts [ar6QtOrGSn-X0RSDh7rHiw](https://tools.taskcluster.net/groups/R7VfTN0PTUSEPMuVzsM5LQ/tasks/ar6QtOrGSn-X0RSDh7rHiw/runs/0) | True | True |
| jlund  | 4 | [bug none](https://bugzil.la/none)        | getting auth failure in shipit v2 for every write action | True | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/R7VfTN0PTUSEPMuVzsM5LQ) R7VfTN0PTUSEPMuVzsM5LQ
```
export PROMOTE_TASK_ID=R7VfTN0PTUSEPMuVzsM5LQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1502234](https://bugzil.la/1502234)        | beta l10n is broken for locale be and lij. needed manual l10n-changesets.json bump due to l10n typo. build2. more context | False | True |
| jlund  | 2 | [bug 1502245](https://bugzil.la/1502245)        | release-early-tagging tasks between devedition and beta may race pushing to m-b | False | True |
| callek  | 3 | [bug none](https://bugzil.la/none)        | Partials failed due to worker not finding some artifacts [ar6QtOrGSn-X0RSDh7rHiw](https://tools.taskcluster.net/groups/R7VfTN0PTUSEPMuVzsM5LQ/tasks/ar6QtOrGSn-X0RSDh7rHiw/runs/0) | False | True |

