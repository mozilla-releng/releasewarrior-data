# fennec 58.0b15

### Date of go-to-build: 2018-01-08

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/RxS2YAQ8RR-n8p8xmSvO_g)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Push-to-Google-Play#what-to-do)  - run pushapk

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| callek  | 1 | [bug none](https://bugzil.la/none)        | All builds of fennec failed -- Theory is that it broke due to a [Taskcluster infra issue](https://github.com/taskcluster/taskcluster-retrospectives/pull/5/files). reran via cli | True | False |
| nthomas  | 2 | [bug none](https://bugzil.la/none)        | bouncer sub job (QuN-e5bIT-Sqzfaon5UQ9Q) ran but the bridge hit 503s updating tc. marked complete with cli | True | True |

