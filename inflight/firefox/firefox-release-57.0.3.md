# firefox 57.0.3

### Date of go-to-build: 2017-12-26

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/WQ_XrryTTPyBrGV4fvLErQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://docs.google.com/spreadsheets/d/1Nua344Mque8NTpTOZdAesEv1cXYkscV4z9rn09r0cVc/edit#gid=0)  - localtest/cdntest update path setup. after all artifact gen tasks complete, remove 57.0.1 freeze for linux/mac. point to wnp
- [x] 3.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page
- [x] 4.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [x] 5.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#4-publish-release)  - publish release tasks
- [x] 6.  [how-to](https://docs.google.com/spreadsheets/d/1Nua344Mque8NTpTOZdAesEv1cXYkscV4z9rn09r0cVc/edit#gid=0)  - release channel update path setup: after go from relman to publish to release, remove 57.0.1 freeze for linux/mac. point to wnp for rules outside of automation
- [x] 7.  [how-to](https://github.com/mozilla/releasewarrior/blob/master/how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1421535](https://bugzil.la/1421535)        | update verify failures. needed to: https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8 | True | True |

