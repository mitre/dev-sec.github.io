---
#title: "Heimdall"
layout: heimdall
---


## [Heimdall](https://github.com/mitre/heimdall)

Heimdall is a centralized aggregation tool for InSpec evaluations

### Description
Heimdall supports viewing of InSpec profiles and evaluations in a convenient
interface.  Data uploads can be automated through usage of curl, and added as
a step after an InSpec pipeline stage.

### Heimdall vs Heimdall-Lite

There two versions of the MITRE Heimdall Viewer - the full [Heimdall](https://github.com/mitre/heimdall/) and the [Heimdall-Lite](https://github.com/mitre/heimdall-lite/)  version. We produced each to meet different needs and use-cases.

### Features

|  | [Heimdall-Lite](https://github.com/mitre/heimdall-lite/) | [Heimdall](https://github.com/mitre/heimdall/) |
|:--------------------------------------------------------------------------|:--------------|:-------------------------------------|
| Installation Requirements | any web server | rails 5.x Server <br /> MongoDB instance |
| Overview Dashboard & Counts | x | x |
| 800-53 Partition and TreeMap View | x | x |
| Data Table / Control Summary  | x | x |
| InSpec Code / Control Viewer | x | x |
| SSP Content Generator | x | x |
| PDF Report and Print View | x | x |
|  |  |  |
| Users & Roles & multi-team support |  | x |
| Authentication & Authorization | Hosting Webserver | Hosting Webserver<br />LDAP<br />GitHub OAUTH & SAML<br />GitLab OAUTH & SAML |
| Advanced Data / Filters for Reports and Viewing |  | x |
| Multiple Report Output<br />(DISA Checklist XML, CAT, XCCDF-Results, and more) |  | x |
| Authenticated REST API |  | x |
| InSpec Run 'Delta' View |  | x |
| Multi-Report Tagging, Filtering and Compairison |  | x |

### Use Cases

| [Heimdall-Lite](https://github.com/mitre/heimdall-lite/) | [Heimdall](https://github.com/mitre/heimdall/) |
|:------------------------------------|:--------------------------------------------------------|
| Ship the App & Data via simple Email | Multiple Teams Support |
| Minimal Footprint & Deployment Time | Timeline and Report History |
| Local or disconnected Use | Centralized Deployment Model  |
| One-Time Quick Reviews | Need to view the delta between one or more runs |
| Decentralized Deployment  | Need to view subsets of the 800-53 control alignment |
| Minimal A&A Time | Need to produce more complex reports in multiple formats |

### Screenshots

#### Login Page

![image alt text](/images/heimdall_login.png)


# [Asgard](https://github.com/mitre/asgard)

### Description

Asgard is a work in progress application which houses Heimdall, Vulcan, InSpec Tools and other utilities for working within the InSpec Compliance Framework

### Features

* Heimdall
* Vulcan
* InSpec Tools
