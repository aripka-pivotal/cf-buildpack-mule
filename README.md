cf-buildpack-mule
=================

Deploy mule apps to Cloud Foundry

Deploys a Mule App Zip file.

Currently expects the artifact to only file in push directory (does not support direct artifact reference)

Example usage 
```
cf push mule-books -b https://github.com/aripka-pivotal/cf-buildpack-mule
```
or
```
cf push mule-books -b https://github.com/aripka-pivotal/cf-buildpack-mule -p <<path_to_artifact_directory>>
```
