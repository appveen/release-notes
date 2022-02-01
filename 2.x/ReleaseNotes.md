# Release notes for appveen data.stack 2.0

# Table of contents

- [Release notes for appveen data.stack 2.0](#release-notes-for-appveen-datastack-20)
- [Table of contents](#table-of-contents)
- [Releases](#releases)
	- [2.1.0 - January 28th, 2022](#210---january-28th-2022)
		- [Defects](#defects)
		- [Detailed changelog](#detailed-changelog)
	- [2.0.0 - January 12th, 2022](#200---january-12th-2022)
		- [Stories and Defects](#stories-and-defects)
		- [Detailed changelog](#detailed-changelog-1)
		- [Known issues](#known-issues)
- [Images](#images)
- [Support](#support)

# Releases

## 2.1.0 - January 28th, 2022

* Removed Security deployment and simplified the security architecture.

### Defects

| ID | Description |
|-|-|
| DEF1740 | \[AppCenter\]: Exact value is not showing for 'Secure Text' while checking the history |
| DEF1737 | \[AppCenter\]: Unable to save the record with 'Secure Text' type |
| DEF1742 | \[AppCenter\]: Relation issue with 'Secure Text' type |
| DEF1739 | \[AppCenter\]: 'Secure Text' value not showing in exported doc |
| DEF1749 | \[Appcenter\] Bulk export is not working when secure text field does not have value |
| DEF1748 | \[AppCenter\] secure text value is not showing for bulk import. |
| DEF1735 | JWT token is not getting expired. |
| DEF1733 | \[Pods\]Deployment version to be removed from the ds and faas pod |
| DEF1734 | \[DS 2.0.0 Installation\] Installation failing on a fresh machine with no data |
| DEF1728 | data.satck 2.0 new install fails because USR is not able to create default users |
| DEF1729 | Remove info level mogodb, nats and redis logs |

### Detailed changelog

[2.1.0 Changelog](2.1.0-Changelog.md)

---

## 2.0.0 - January 12th, 2022

* data.stack SDK is now at 2.0
* All Author side APIs (`/api/a`) must have an additional query parameter `?app=<appName>`

### Stories and Defects

| ID | Description | 
|-|-|
| STO1013 | \[UI\]  Multilevel Workflow & Field Level access control |
| STO1064 | \[BE\]  Multilevel Workflow & Field Level access control |
| STORY1088 | \[TXN\] As a user i should be able to CUD data on data-services using transactions if workflow has been enabled and i have Skip-Review permissions |
| STORY1089 | \[TXN\] As a user i should NOT be allowed to do CUD data on data-services using transactions if workflow has been enabled and i don't have Skip-Review permissions |
| STORY1110 | As a user I should be able to add super admins to groups. |
| DEF1539 | \[Author\] Not able to create steps for maker checker in an already present DS |
| DEF1548 | \[Groups\] \[Maker Checker\] When maker checker is enabled in groups it gets stuck in processing. |
| DEF1551 | \[Users\] Password format for reset password is different from create user password. |
| DEF1580 | \[User\] Unable to create users from app panel.  |
| DEF1581 | \[Author\]\[Groups\] Unable to edit group and save the group. |
| DEF1583 | Unable to add records, creation screen is empty. |
| DEF1590 | \[Appcenter\] Failing to import bulk data |
| DEF1593 | \[Maker Checker\]\[State Model\] Unable to save records with state model. |
| DEF1600 | \[Maker Checker\] Records approved by a user it still available for the same user to respond and the approval is not added to responded by column when the DS has state model. |
| DEF1627 | \[Appcenter\]Records Are Not Getting Exported . |
| DEF1630 | \[Author\]\[Groups\]User is not Able To Create Any Group. |
| DEF1636 | \[Maker Checker\] When a DS has duplicate step names in maker checker user is not able to approve records |
| DEF1643 | \[Bots\] Unable to add properties to bots. |
| DEF1652 | \[Secure Text\] Value of secure text changes after approval. |
| DEF1678 | \[Maker  Checker\] Unable to approve record in last step. |

### Detailed changelog

[2.0.0 Changelog](2.0.0-Changelog.md)

### Known issues

* DEF1724	[Insights] Disable insights is not working as expected.
* DEF1715	[Insights] User with permission to insights is not able to view user logs.
* DEF1714	[Bots] User needs to have permissions to users in group to add a bot to a group.
* DEF1707	[Bots] Login from bot calls n number of API's.
* DEF1693	[Maker Checker] Unable to respond to old records if the checker step name is renamed.
* DEF1508	[Author] User with view permission for insights is not able to see users list.

---

# Images

| Component | Short code | Image |
|--|--|--|
| Base | base | data.stack:base.2.1.0 |
| Common | common | data.stack:common.2.1.0 |
| Deployment manager | dm | data.stack:dm.2.0.0 |
| FaaS base image | faas-base | data.stack:faas.base.2.1.0 |
| Gateway | gw | data.stack:gw.2.1.0 |
| Monitoring | mon | data.stack:mon.2.0.0 |
| Notification engine | ne | data.stack:ne.2.0.0 |
| Partner manager | pm | data.stack:pm.2.1.0 |
| Proxy | proxy | data.stack:proxy.2.1.0 |
| Service manager | sm | data.stack:sm.2.1.0 |
| User | user | data.stack:user.2.1.0 |

---

# Support

For any incidents, queries or feedback, please reach out to support@appveen.com