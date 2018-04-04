# devedition 60.0b9

### Date of go-to-build: 2018-04-02

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/Uq2I-M9NRueaH59JUWI0og) Uq2I-M9NRueaH59JUWI0og
* [push](https://tools.taskcluster.net/push-inspector/#/AyKuEmbvRo6ZNknHs_zuzA) AyKuEmbvRo6ZNknHs_zuzA
* [ship](https://tools.taskcluster.net/push-inspector/#/FzjRbO7vR5if3Suz_WDWYA) FzjRbO7vR5if3Suz_WDWYA
* [push2](https://tools.taskcluster.net/push-inspector/#/Gkw7fgghRo23heUEz89HIA) Gkw7fgghRo23heUEz89HIA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1304942](https://bugzil.la/1304942)        | hg clone bustage | True | True |
| asasaki  | 2 | [bug 1450075](https://bugzil.la/1450075)        | partials flaky | True | True |
| asasaki  | 3 | [bug 1451531](https://bugzil.la/1451531)        | missing checksums | False | True |

