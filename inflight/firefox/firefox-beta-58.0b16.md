# firefox 58.0b16

### Date of go-to-build: 2018-01-11

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/SS1je0y2Sy2-t35x5sYZOA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://tools.taskcluster.net/groups/SS1je0y2Sy2-t35x5sYZOA/tasks/INyW0CckTYGxOlcqT0e5Lg/details)  - Because we migrated m-c->m-b in between gtb and publish, callek cancelled version bump task. We should manually sanity check the version string in tree is good for next beta. This I suppose should be 59.0b1. Should also add FIREFOX_58_0b16_{RELEASE,BUILD1} tags on 8bb8f895a740ba60d587337e920f30ec3000c4ca

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](https://bugzil.la/none)        | 2 dummy tasks (A41szYoPTUK9wLRxWtJvrg &f2joGZpPQJG5rEnTzJu2cA) ended up as exception/claimExpired. TC or worker issue ? Reran them to unblock an update verify job each | True | True |

