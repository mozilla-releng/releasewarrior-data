# firefox 57.0rc

### Date of go-to-build: 2017-11-12

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2017-11-05 - [bug 1397721](http://bugzilla/1397721): Verify that the release patch has landed and reconfigured
- [ ] 2. due:2017-11-05 - [bug 1397721](http://bugzilla/1397721): sanity check change: Cross-Channel L10n new in this release, should use l10n-central repo
- [ ] 3. due:2017-11-06 - [bug 1402411](http://bugzilla/1402411): Block updates for users with old JAWS software using the 'JAWS Screen Reader Compatibility' boolean on Balrog rules

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/C4u-oWlDRqSU3QIYaIFv6Q)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish in Balrog on beta channel
- [x] 3.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog
- [x] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [ ] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Descripiton                | Blocking Release        | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](http://bugzilla/none)        | win32 EME repacks (LH5h1BHURBuFZuQ87yt4kg) had a '3600 seconds without output' hang, rerun | False | True |

