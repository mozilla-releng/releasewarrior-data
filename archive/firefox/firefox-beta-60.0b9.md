# firefox 60.0b9

### Date of go-to-build: 2018-04-02

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/NXi31S58R6OEAtWdahm9LQ) NXi31S58R6OEAtWdahm9LQ
* [push](https://tools.taskcluster.net/push-inspector/#/CR3CKCvFRPCCt5U2X538Pg) CR3CKCvFRPCCt5U2X538Pg
* [ship](https://tools.taskcluster.net/push-inspector/#/L3icgE9-QlebaWhBDuTbzQ) L3icgE9-QlebaWhBDuTbzQ
* [push2](https://tools.taskcluster.net/push-inspector/#/c5EiS45XRAa3_Kd7k64yFw) c5EiS45XRAa3_Kd7k64yFw


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1371378](https://bugzil.la/1371378)        | hg bundle issue | True | True |
| asasaki  | 2 | [bug 1451531](https://bugzil.la/1451531)        | beetmover-cdns didn't push checksums | True | True |

