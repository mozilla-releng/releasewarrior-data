# devedition 64.0b2

### Date of go-to-build: 2018-10-18

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/QSXPcjUcTHugp6nLq0-1WQ) QSXPcjUcTHugp6nLq0-1WQ
```
export PROMOTE_TASK_ID=QSXPcjUcTHugp6nLq0-1WQ
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | ryanvm got auth failures on shipit v2 but was successful creating the release/graph | True | True |
| asasaki  | 2 | [bug 1499265](https://bugzil.la/1499265)        | linux UV timeouts NAuNEH3ERSW0kA_ShsbW9Q DeHS-aDITYq2MIHEZ_VLOw EeMZ1uCwQ8WWK_yP2gbrJw PKOYOyGIRq6TN4LqyhFh8w BXJIHI8MTZKvvLE0UUsx1Q VDaLz8H-QEmJRnZQt1pT6w dGmUWi4eSqmO54RWVu_iww blWalH9TRXexwoH6ZuS6_w PjTONsESQEGQgWZH6s2K8g es33tvBdRe68hrf9Uakbsg | True | True |
| asasaki  | 3 | [bug 1486554](https://bugzil.la/1486554)        | static analysis on windows builds caused windows build timeouts; had to bump ec2 instance types to c5 | False | True |

