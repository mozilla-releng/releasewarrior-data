# devedition 59.0b11

### Date of go-to-build: 2018-02-19

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[promote](https://tools.taskcluster.net/push-inspector/#/Z1gJPDHMR-yzmiah2JuY1w)
[push](https://tools.taskcluster.net/push-inspector/#/BEq0FzQ4SnuDZlWkEnQgow)
[ship](https://tools.taskcluster.net/push-inspector/#/WleishiaThuHZPkc8IWvJQ)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#publish-the-release)  - publish release tasks
- [ ] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks-TC#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| jlund  | 1 | [bug 1409445](https://bugzil.la/1409445)        | Updates builder can race pushing to tools | True | False |
| jlund  | 2 | [bug 1438906](https://bugzil.la/1438906)        | UV script change broke mac-os UV. backed out | False | True |

