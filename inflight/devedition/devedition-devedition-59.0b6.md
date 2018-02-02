# devedition 59.0b6

### Date of go-to-build: 2018-01-31

## Preflight tasks (pre go-to-build)
- [ ] 1. due:2018-01-30 - [bug 1431764](https://bugzil.la/1431764): [jlorenzo] 'release-mark-as-shipped' task is now running on scriptworker. I don't expect breakage, but there might be issues either related to scopes or to https credentials. In case of a failure, you can just manually mark the release as shipped on the ship-it webUI. This task doesn't do more. In any case, please reach out to me if any issue comes up

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/MMG3YkvkQ5K4bGOiUYuhWA)
[task group](https://tools.taskcluster.net/push-inspector/#/GZZ4TaSCQEySs6ZmKbV_8A)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#publish-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| none | | | | | |

