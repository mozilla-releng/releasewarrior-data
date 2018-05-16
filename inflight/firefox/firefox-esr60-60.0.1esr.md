# firefox 60.0.1esr

### Date of go-to-build: 2018-05-15

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [push](https://tools.taskcluster.net/push-inspector/#/Cw3cWLIlSI-7hMKijuTf6w) Cw3cWLIlSI-7hMKijuTf6w
* [promote](https://tools.taskcluster.net/push-inspector/#/atmH6Cq5TpygtR_ttVdyUw) atmH6Cq5TpygtR_ttVdyUw
```
export PUSH_TASK_ID=Cw3cWLIlSI-7hMKijuTf6w
export PROMOTE_TASK_ID=atmH6Cq5TpygtR_ttVdyUw
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1461859](https://bugzil.la/1461859)        | esr 60.0.1 is failing to pass kickoff sanity check | True | False |
| mtabara  | 2 | [bug 1461919](https://bugzil.la/1461919)        | reruns are flaky. all over the place. we need to bump its priority and address it sooner | False | True |
| mtabara  | 3 | [bug 1461919](https://bugzil.la/1461919)        | Kind of worrying to see jamun tasks referenced in Cot for esr balrogworkers tasks. | False | True |
| mtabara  | 4 | [bug none](https://bugzil.la/none)        | bouncer check failed | True | False |
| mtabara  | 5 | [bug none](https://bugzil.la/none)        | esr60 snap failed -- kill? | False | True |
| mtabara  | 6 | [bug 1462064](https://bugzil.la/1462064)        | sha1 is esr52 only so release bouncer check on esr60 should stop checking it | False | True |
| mtabara  | 7 | [bug 1462066](https://bugzil.la/1462066)        | esr60 snap is failing | False | True |

