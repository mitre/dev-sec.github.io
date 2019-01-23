---
#title: "Vulcan"
layout: vulcan
---

## [Vulcan](https://github.com/mitre/vulcan)

### Description

Vulcan is a tool to help streamline the process of creating STIGs and InSpec security compliance profiles. It models the STIG intent form and
the process of aligning security controls from SRG items into actual STIG security controls.  Vulcan also gives the option while aligning the security controls to
insert inspec code and test across any type of system supported by InSpec.

### Features

* Model the STIG creation process between the creator(vendor) and the approver(sponsor)
* Write and test InSpec code on a local system, or across SSH, AWS, and Docker
* Easily view the progress on what the status is of each control
* Communicate through the application to make the best decisions on controls
* Confidential data in the database is encrypted using symmetric encryption
* Authenticate via the local server, through github, and through configuring an LDAP server.

### Screenshots

#### Login Page

![image alt text](/images/vulcan_login.png)


On the left hand side you can login as a local user, and on the right hand side you can log in as a LDAP user. Creating a new local user can be done by clicking sign up on the left hand side of the page. The very first user created on a fresh install will be an administrator user. Administrators are required to assign users to either the sponsor or vendor groups, which have different abilities.

#### Admin Dashboard

![image alt text](/images/create_vendor_and_sponsor.png)

Before users can be added to a specific group vendor or sponsor, the administrator must fill out these forms for either the vendor of the sponsor. Once these are filled out, the users needing assignment can be assigned to their respective group.


![image alt text](/images/vulcan_admin_dashboard.png)


Once vendors and sponsors are created, the users will be able to be assigned to their respective vendor or sponsor groups.

#### Viewing Uploaded SRGs

![image alt text](/images/uploaded_srgs_vulcan.png)

When an SRG is uploaded, users can view them here. They have titles, description of what the control is, and who published it and when. You can manually expand by selecting show controls.


![image alt text](/images/show_controls.png)

Once you expand into the show controls, you will see this layout. Information includes SRG ID, severity and title of the control. You can drill down one more into show on the far right.


![image alt text](/images/show_controls_second.png)

This is the furthest you can drill down into a control. It includes pertinent information

#### Uploading New SRGs

![image alt text](/images/upload_srg_vulcan.png)

On this screen you can upload your SRGs to Vulcan. 
