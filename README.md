# SharepointTestUtility
Creates sharepoint test content.

SP test utility will be run via command line


```

  -d, --Domain               Required. Domain of sharepoint user

  -u, --Username             Required. Sharepoint Username. Include 
                             domain\username if you are on prem

  -p, --Password             Required. Sharepoint Password

  -w, --WebApplicationUrl    Required. Sharepoint Web Application Url

  -a, --ActionFile           Required. Json file describing what to do

  --help                     Display this help screen.

  --version                  Display version information.
```


## Action file format

### Create site

* `Type` = `createSite`
* `Description` = string
* `Title` = string
* `Url` = string - url of the site to create
* `ParentSiteUrl` = string - url of the parent site.
* `UseSamePermissionsAsParentSite` = boolean
