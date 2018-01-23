# firefox 52.6.0esr

### Date of go-to-build: 2018-01-15

## Preflight tasks (pre go-to-build)
- none

## Build 2  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/EP95aXu5SCqdudWWKY50EQ)
[task group](https://tools.taskcluster.net/push-inspector/#/LBFICYvGT5KNV2X7hGHCvw)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug none](https://bugzil.la/none)        | linux64 repack 7/10 (JYZIwWyHS1mMaBEs0yv8Gw) failed upload on a single locale, a rather strange ssh warning. The corresponding artifacts task (TK2DGUBMRn6h08dfVJC8qw) also failed. Initial fix was running the repack in buildbot, rather than tc, witbhout touching the artifacts task so - so the repack failed. Reran both tasks using taskcluster cli | True | False |
| callek  | 2 | [bug 1407174](https://bugzil.la/1407174)        | Balrog failure when publishing (task shows as SUCCESSFUL!) Cannot submit scheduled change to alias "esr52": Invalid input for rule_id. Not an integer. rule_id: u'esr52' is not a 'rule_id' - Previously hit 52.4.1 (and others) | True | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/LtXuHitNSJOsEL3d1AILFQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#2-push-to-releases-dir-mirrors)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#4-publish-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/old-how-tos/relpro.md#3-signoffs)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug 1412967](https://bugzil.la/1412967)        | Releaserunner was not configured to track esr, after in-tree-relpro changes. | True | False |

