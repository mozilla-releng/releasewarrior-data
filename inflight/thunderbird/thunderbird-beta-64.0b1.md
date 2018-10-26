# thunderbird 64.0b1

### Date of go-to-build: 2018-10-26

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [push](https://tools.taskcluster.net/push-inspector/#/PREQbFt1SBy-4OPbHFYlkg) PREQbFt1SBy-4OPbHFYlkg
* [promote](https://tools.taskcluster.net/push-inspector/#/eTrXoVR4Q9-332CNuO6tFA) eTrXoVR4Q9-332CNuO6tFA
```
export PUSH_TASK_ID=PREQbFt1SBy-4OPbHFYlkg
export PROMOTE_TASK_ID=eTrXoVR4Q9-332CNuO6tFA
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| sfraser  | 1 | [bug none](https://bugzil.la/none)        | Downloading parameters file failed on initial push script run. Timeouts to cloud mirrors. 2018-10-26 09:30:53,713 - WARNING - Retrying (Retry(total=4, connect=5, read=4, redirect=None, status=None)) after connection broken by 'ReadTimeoutError("HTTPSConnectionPool(host='cloud-mirror.taskcluster.net', port=443): Read timed out. (read timeout=5)",)': /v1/redirect/s3/us-east-1/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Ftaskcluster-public-artifacts%2FeTrXoVR4Q9-332CNuO6tFA%2F0%2Fpublic%2Fparameters.yml | True | True |
| jlund  | 2 | [bug 1481203](https://bugzil.la/1481203)        | shipit mark as shipped task failes due to scopes | False | True |

