# acr-tasks
Collection of Azure Container Registry tasks.


**Available task**:
- `base-image-update.yaml`: Autopatch task for hmcts base images (e.g. hmcts/base/node/alpine-lts-10:10-alpine). This triggers an 
  image rebuild as soon as its base image is updated by the upstream maintainer, for example with a critical OS security patch. 
  For more details see: [ACR OS patching](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tasks-overview#automate-os-and-framework-patching)
- `tf-utils-build.yaml`: Builds a docker image for the terraform utils application. For details see: [Terraform utils](https://github.com/hmcts/terraform-utils) 
- `acr-sync-build.yaml`: Builds a docker image for the ACR sync check application. For details see: [ACR sync check](https://github.com/hmcts/azure-cftapps-monitoring/tree/master/acr-sync) 
