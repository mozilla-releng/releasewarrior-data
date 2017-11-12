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
- [ ] 2.  [how-to](https://bugzilla.mozilla.org/show_bug.cgi?id=1413645#c4)  - after artifacts complete, create wnp and win64 migration blobs
- [x] 3.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish in Balrog on beta channel
- [x] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog
- [x] 5.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [ ] 6.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 7.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 8.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Descripiton                | Blocking Release        | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](http://bugzilla/none)        | win32 EME repacks (LH5h1BHURBuFZuQ87yt4kg) had a '3600 seconds without output' hang, rerun | False | True |
| nthomas  | 2 | [bug none](http://bugzilla/none)        | release update verify 4,5,6,7,8/12 failed due to expecting 56.0 to be offered 57.0 instead of 56.0.2. We need to set up release-localtest | False | True |
| callek  | 3 | [bug 1415276](http://bugzilla/1415276)        | Unable to publish to beta channel: KeyError: 'bz2_blob_suffix' | False | True |
| bhearsum  | 4 | [bug 1415172](http://bugzilla/1415172)        | need to back out because chunked update verify doesn't support multiple 'to' versions in the same config | False | True |
| bhearsum  | 5 | [bug 1415557](http://bugzilla/1415557)        | fix up OS and SYSTEM_CAPABILITIES for update verify | False | True |

