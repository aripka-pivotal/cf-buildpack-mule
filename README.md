cf-buildpack-mule
=================

Deploy mule apps to Cloud Foundry

```
git clone https://github.com/danielkennedy/cf-buildpack-mule
cd cf-buildpack-mule
zip -r cf-buildpack-mule.zip bin/
cf create-buildpack mule cf-buildpack-mule.zip 1 --enable
```
