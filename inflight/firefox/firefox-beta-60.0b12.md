# firefox 60.0b12

### Date of go-to-build: 2018-04-12

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/YAM42iDzQl2jduhU7Obbng) YAM42iDzQl2jduhU7Obbng
* [push](https://tools.taskcluster.net/push-inspector/#/OA0voFjlR5KxcVlkIG0kSA) OA0voFjlR5KxcVlkIG0kSA
* [ship](https://tools.taskcluster.net/push-inspector/#/N3r2C4MBQ9GT3B9sQouFbQ) N3r2C4MBQ9GT3B9sQouFbQ


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1453240](https://bugzil.la/1453240)        | langpack beetmover changes broke beetmover | False | True |
| sfraser  | 2 | [bug none](https://bugzil.la/none)        | release-bouncer-check-firefox failed (U4D65-moRjCWcknswXAUjg) due to a partial not being available. rerun->fixed | False | True |

