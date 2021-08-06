# Release notes for appveen data.stack 1.1

# Table of contents

- [Release notes for appveen data.stack 1.1](#release-notes-for-appveen-datastack-11)
- [Table of contents](#table-of-contents)
- [Releases](#releases)
	- [1.1.5 - August 4th, 2021](#115---august-4th-2021)
	- [1.1.4 - July 20, 2021](#114---july-20-2021)
	- [1.1.3 - July 14, 2021](#113---july-14-2021)
	- [1.1.2 - July 9, 2021](#112---july-9-2021)
	- [1.1.1 - June 29, 2021](#111---june-29-2021)
	- [1.1.0 - June 26, 2021](#110---june-26-2021)
- [Images](#images)
- [Support](#support)

# Releases

## 1.1.5 - August 4th, 2021

| ID | Description | 
|-|-|
| STORY1091 | \[TXN\] As a user i should be able to CUD data on multiple data-services using transactions with pre-hooks |
| STORY1090 | \[TXN\] As a user i should be able to CUD data on multiple data-services using transactions |
| STORY1089 | \[TXN\] As a user i should NOT be allowed to do CUD data on data-services using transactions if workflow has been enabled and i don't have Skip-Review permissions |
| STORY1088 | \[TXN\] As a user i should be able to CUD data on data-services using transactions if workflow has been enabled and i have Skip-Review permissions |
| STORY1086 | \[TXN\] As a user i should be able to CUD data on a data-service using transactions with pre-hooks |
| STORY1085 | \[TXN\] As a user i should be able to CUD data on a single data-service using transactions |

Detailed changelog: [1.1.5 Changelog](./1.1.5-Changelog.md)

## 1.1.4 - July 20, 2021

| ID | Description |
|-|-|
| DEF1395 | \[Appcenter\] Unable to export records after applying filter. |
| DEF1396 | Multiple posthooks not working |

Detailed changelog: [1.1.4 Changelog](./1.1.4-Changelog.md)

## 1.1.3 - July 14, 2021

| ID | Description |
|-|-|
| DEF1388 | \[Author\] User with manage permission for Data services is not able to save & deploy the DS. |
| DEF1330 | \[Appcenter\]\[WF\] Unable to approve or reject work items which has deleted record relation. |
| DEF1380 | \[Cloud\] data.stack > Stories is not loading more records. |
| DEF1379 | \[File Type Restriction\] If user have a  .exe file and rename the extension to any acceptable file type, it allows the upload. |
| DEF1378 | \[Appcenter\] File Attachment, Validation not working. |
| DEF1360 | \[Author\]\[Groups\] user who has view permission for basic settings and members tab under groups is unable to view members of group. |
| DEF1377 | \[Author\]\[FAAS\] Last invoked data is not coming up for functions. |
| DEF1291 | \[Author\]\[Role\]\[Conditions\] Unable to change dataservice in select and traverse  |
| DEF1290 | \[Author\]\[Role\]\[Conditions\] Filetype conditions is not working as expected  |
| DEF1284 | \[Author\]\[Data Service\] "Delete All" in Design tab breaks UI |
| DEF1279 | \[Author\]\[Data service\] Attribute value in condition is not displayed in view screen |
| DEF1384 | \[Author\]\[Data Service\]:The file extension should be removed from the settings tab. |
| DEF1373 | AppCenter UI stuck when trying to logout again |
| DEF1367 | \[Author\] Relationships -> Search on field is not visible on view screen |
| DEF1358 | \[Author\]\[Groups\]:User permission are not working as expected. |
| DEF1347 | \[Appcenter\]\[History\] In WF enabled DS, the record history shows the approver as creator. |
| DEF1335 | \[Appcenter\] Inline filter for date in collection of group of date isn't working. |
| DEF1359 | \[Author\]\[Groups\]:User with bots end session permission does not have an option to end session of the bot, the end session button is not available in UI |

Detailed changelog: [1.1.3 Changelog](./1.1.3-Changelog.md)

## 1.1.2 - July 9, 2021

| ID | Description |
|-|-|
| DEF1390 |	Math API not working for complex structures |

Detailed changelog: [1.1.2 Changelog](./1.1.2-Changelog.md)

## 1.1.1 - June 29, 2021

| ID | Description |
|-|-|
| DEF1374 |	FaaS is only working for superadmins |

Detailed changelog: [1.1.1 Changelog](./1.1.1-Changelog.md)

## 1.1.0 - June 26, 2021

| ID | Description |
|-|-|
| STO1054 | [Author][UI][FAAS] As a user, I must be able to write and deploy hooks/nanoservices from data.stack UI |
| STO1067 | [Author][UI] As a user, I must be able to purge logs from Insights |
| STO1072 | [Appcenter][UI] Link for relation attributes in the Edit/Save page to be able to navigate to related entity |
| STO1057 | [Author][UI] As a user I must be able to select the functions from function page in hooks |

Detailed changelog: [1.1.0 Changelog](./1.1.0-Changelog.md)

# Images

| Component | Short code | Image |
|--|--|--|
| Service manager | sm | data.stack:sm.1.1.3 |
| Base | base | data.stack:base.1.1.3 |
| Gateway | gw | data.stack:gw.1.1.3 |
| Common | common | data.stack:common.1.1.0 |
| Proxy | proxy | data.stack:proxy.1.1.2 |
| User | user | data.stack:user.1.1.1 |
| Deployment manager | dm | data.stack:dm.1.1.2 |
| Notification engine | ne | data.stack:ne.1.1.1 |
| Security | sec | data.stack:sec.1.1.2 |
| Monitoring | mon | data.stack:mon.1.1.1 |
| Partner manager | pm | data.stack:pm.1.1.1 |
| FaaS base image | faas-base | data.stack:faas.base.1.1.1 |
| B2B Gateway | b2bgw | data.stack:b2bgw.1.1.2 |
| B2B base image| b2b-base | data.stack:b2b.base.1.1.2 |

# Support

For any incidents, queries or feedback, please reach out to support@appveen.com
