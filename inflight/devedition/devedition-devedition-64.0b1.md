# devedition 64.0b1

### Date of go-to-build: 2018-10-15

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/H6yyeskzSGGB4z-X-ixneQ) H6yyeskzSGGB4z-X-ixneQ
```
export PROMOTE_TASK_ID=H6yyeskzSGGB4z-X-ixneQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1499217](https://bugzil.la/1499217)        | no ssh key on bm01; had to push l10n bump manually | True | False |
| asasaki  | 2 | [bug 1499204](https://bugzil.la/1499204)        | hg push to beta timed out | True | True |
| asasaki  | 3 | [bug none](https://bugzil.la/none)        | shipit v2 doesn't have user friendly docs for relman | True | True |
| nthomas  | 4 | [bug none](https://bugzil.la/none)        | UV timeouts (force kill container after 3600 seconds) | True | True |

