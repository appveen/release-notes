# Release notes for appveen data.stack 1.0

# Table of contents

- [Release notes for appveen data.stack 1.0](#release-notes-for-appveen-datastack-10)
- [Table of contents](#table-of-contents)
- [Preface](#preface)
- [1.0 - Mar 8, 2021](#10---mar-8-2021)
	- [Features](#features)
	- [Issues fixed](#issues-fixed)
	- [Builds](#builds)
	- [Changelog](#changelog)
- [Support](#support)

# Preface

Our product is evolving and we are rebranding it to reflect our vision for the new future.

appveen data.stack is powered by the same tech behind Omni Data Platform, but it comes with better performance and usability. With all the improvements done to the platform, you can use it more productively.

Also, the biggest of all improvements in appveen data.stack 1.0 is that it is now cloud-ready.

In all aspects you should treat appveen data.stack 1.0 as a new product. But if you are an existing customer, this document explains what changes went into the product.

# 1.0 - Mar 8, 2021

data.stack has been built on top of ODP 3.9 and some of these changes does not guarantee backward compatibility. Please refer to the [Moving to appveen data.stack 1.0 from Omni-Data Platform 3.9](./Moving%20to%20appveen%20data.stack%201.0%20from%20Omni-Data%20Platform%203.9.pdf) document to help you migrate.

## Features

* STORY1909: Support for multiple time zones
* STORY1871: Support multiple auth modes via backend.
* STORY1906: Data service definition from string -> JSON
* STORY1918: Data service API endpoint update
* STORY1671: Hook payload structure changes
* STORY1910: Workflow backend improvements

## Issues fixed

* None

## Builds

| Component | Image | Checksum |
|--|--|--|
| Proxy | data.stack:proxy.1.0.0 | |
| Gateway | data.stack:gw.1.0.0 | |
| Service manager | data.stack:sm.1.0.0 | |
| Base image | data.stack:base.1.0.0 | |
| Partner manager | data.stack:pm.1.0.0 | |
| B2B gateway | data.stack:b2bgw.1.0.0 | |
| User management | data.stack:user.1.0.0 | |
| Notification engine | data.stack:ne.1.0.0 | |
| Monitoring | data.stack:mon.1.0.0 | |
| Security | data.stack:sec.1.0.0 | |

## Changelog

[1.0.0 Changelog](./1.0.0-Changelog.md)

# Support

For any incidents, queries or feedback, please reach out to support@appveen.com