# CCS CONCLAVE DOCUMENT CLAMAV BUILDPACK
This is a cloudfoundry buildpack to be used within ccs-conclave-document-check to install the clamav dependancies onto the Govuk Paas environment

### Usage
Specify this buildpack in your main app's manifest file before any final buildpacks. 
For example:
```   
buildpacks:
      - https://github.com/Crown-Commercial-Service/ccs-conclave-document-clamav-buildpack.git
      - https://github.com/cloudfoundry/ruby-buildpack.git
``` 