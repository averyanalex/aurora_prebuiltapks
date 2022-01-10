# Aurora Prebuilt APKs
This repository contains APKs of Aurora project:
* AuroraStore
* AuroraDroid
* AuroraServices

Add to manifest file:
```xml
<project name="averyanalex/aurora_prebuiltapks" path="prebuilts/aurora" remote="github" revision="main" />
```
When using [docker-lineage-cicd](https://github.com/lineageos4microg/docker-lineage-cicd) add this to docker arguments:
```shell
-e "CUSTOM_PACKAGES=AuroraStore AuroraDroid AuroraServices "
```
