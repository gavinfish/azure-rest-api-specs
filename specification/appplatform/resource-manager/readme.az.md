## AZ

These settings apply only when `--az` is specified on the command line.

``` yaml $(az) && $(target-mode) != 'core'
az:
  extensions: spring-cloud
  namespace: azure.mgmt.spring-cloud
  package-name: azure-mgmt-spring-cloud
az-output-folder: $(azure-cli-extension-folder)/src/spring-cloud
python-sdk-output-folder: "$(az-output-folder)/azext_spring-cloud/vendored_sdks/spring-cloud"