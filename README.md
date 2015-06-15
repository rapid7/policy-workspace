Nexpose Policy Workspace Repository
===================================

This repository contains simple custom [SCAP](https://en.wikipedia.org/wiki/Security_Content_Automation_Protocol) policies focused on different capabilities of Nexpose (e.g. checking for password policy, file access permissions).

### How to use

* Navigate through the 'Custom Policy Examples' folder to the XCCDF and OVAL documents. Study these to understand how SCAP checks are used in Nexpose
* Navigate to the custom policy zip files (e.g. [file permission policy](https://github.com/rapid7/policy-workspace/blob/master/Custom%20Policy%20Examples/File%20Permissions%20Policy/file-policy.zip)) and click on the button labeled 'Raw' to download the file. Upload the zip file to Nexpose as a custom policy. Add this policy to a scan template and test some systems
* Modify and combine checks to make your own custom policies