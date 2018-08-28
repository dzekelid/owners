---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Owners
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - List Registered Owners
  x-api-slug: devicesidregisteredowners-get
  description: List registeredOwners Retrieve a list of users that are registered
    owners of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-get-openapi.md
- name: Microsoft Graph API - List Owners
  x-api-slug: groupsidowners-get
  description: List owners Retrieve a list of the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidowners-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidowners-get-openapi.md
- name: Microsoft Graph API - List Owned Devices
  x-api-slug: usersid--userprincipalnameowneddevices-get
  description: List ownedDevices Get the list of devices that are owned by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-openapi.md
- name: Microsoft Graph API - List Owned Objects
  x-api-slug: usersid--userprincipalnameownedobjects-get
  description: List ownedObjects Get the list of directory objects that are owned
    by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-openapi.md
- name: Microsoft Graph API - Create Registered Owner
  x-api-slug: devicesidregisteredowners-post
  description: Create registeredOwner Add a user as a registered owner of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-openapi.md
- name: Microsoft Graph API - Remove Owner
  x-api-slug: groupsidownersidref-delete
  description: Remove owner Use this API to remove an owner from an Office 365 group,
    a security group or a mail-enabled security group through the owners navigation
    property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-openapi.md
- name: Microsoft Graph API - Add Group Owner
  x-api-slug: groupsidownersref-post
  description: Add group owner Add a user to the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-openapi.md
- name: Microsoft Graph API - List Owned Devices
  x-api-slug: usersid--userprincipalnameowneddevices-get
  description: List ownedDevices Get the list of devices that are owned by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-openapi.md
- name: Microsoft Graph API - List Owned Objects
  x-api-slug: usersid--userprincipalnameownedobjects-get
  description: List ownedObjects Get the list of directory objects that are owned
    by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-openapi.md
- name: Microsoft Graph API - Create Registered Owner
  x-api-slug: devicesidregisteredowners-post
  description: Create registeredOwner Add a user as a registered owner of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-openapi.md
- name: Microsoft Graph API - Remove Owner
  x-api-slug: groupsidownersidref-delete
  description: Remove owner Use this API to remove an owner from an Office 365 group,
    a security group or a mail-enabled security group through the owners navigation
    property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-openapi.md
- name: Microsoft Graph API - Add Group Owner
  x-api-slug: groupsidownersref-post
  description: Add group owner Add a user to the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-openapi.md
- name: Microsoft Graph API - List Owned Objects
  x-api-slug: usersid--userprincipalnameownedobjects-get
  description: List ownedObjects Get the list of directory objects that are owned
    by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameownedobjects-get-openapi.md
- name: Microsoft Graph API - List Owned Devices
  x-api-slug: usersid--userprincipalnameowneddevices-get
  description: List ownedDevices Get the list of devices that are owned by the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/usersid--userprincipalnameowneddevices-get-openapi.md
- name: Microsoft Graph API - Add Group Owner
  x-api-slug: groupsidownersref-post
  description: Add group owner Add a user to the group's owners. The owners are a
    set of non-admin users who are allowed to modify the group object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersref-post-openapi.md
- name: Microsoft Graph API - Remove Owner
  x-api-slug: groupsidownersidref-delete
  description: Remove owner Use this API to remove an owner from an Office 365 group,
    a security group or a mail-enabled security group through the owners navigation
    property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/groupsidownersidref-delete-openapi.md
- name: Microsoft Graph API - Create Registered Owner
  x-api-slug: devicesidregisteredowners-post
  description: Create registeredOwner Add a user as a registered owner of the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/owners/master/_listings/microsoft-graph/devicesidregisteredowners-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---