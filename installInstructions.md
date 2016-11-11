# Browser Agent Tab for Navigation Timing API metrics

# Short Description
This extension provides a CA APM Browser Agent tab that displays Navigation Timing API metrics.

# Description
This extension provides a CA APM Browser Agent tab that displays the Browser Metric Overview and Browser Timings Navigation Timing API metrics.

For installation instructons, see the ReadMe.MD file.

# APM version
CA APM 10.1 and later

# Dependencies
Tested with CA APM 10.1. CA APM 10.1 and later.

# Limitations
Only works for Page Load metrics, not AJAX or Javascript metrics.

# License - GUENTER POINT TO EULA HERE?
[Apache License 2.0](LICENSE).

# Installation

## Install Using CA APM Control Center

### 10.5 

1. Download the bundle (extension) from the CA APM Marketplace.
   http://marketplace.ca.com/shop/ca/?cat=29
2. Go to the Bundles page and click the **Import** button.
2. Navigate to the downloaded bundle and click **Open**.
3. On the Packages page, add the bundle to the desired package.

### 10.2 and 10.3

1. Download the extension (bundle) from the CA APM Marketplace.
   http://marketplace.ca.com/shop/ca/?cat=29
2. Navigate to the downloaded bundle.
3. Copy the bundle to the <APMCommandCenterServer>/import directory. 
   The bundle is automatically imported into the APM Command Center database and moved to the bundles directory.
4. Copy the ext/xmltv/browser.typeviewers.xml file from the downloaded extension into the MOM <*EM_HOME*>ext/xmltv directory.

## Install Manually

### 10.5 and later

1. Download the extension from the CA APM Marketplace.
   http://marketplace.ca.com/shop/ca/?cat=29
2. Navigate to the downloaded extension and untar the file.
3. Copy the .tar file to the <*Agent_Home*>/extensions/deploy directory.
   The agent automatically automatically installs and deploys the extension, which starts monitoring the managed application.
4. Copy the ext/xmltv/browser.typeviewers.xml file from the downloaded extension into the MOM <*EM_HOME*>ext/xmltv directory.

### 10.3 and earlier

1. Download the extension from the CA APM Marketplace.
   http://marketplace.ca.com/shop/ca/?cat=29
2. Navigate to the downloaded extension and unzip or untar as appropriate into the <*Agent_Home*> directory.
3. Add the extension jar file to the <*Agent_Home*>/core/ext directory.
4. Add the .pbd or pbl files to the <*Agent_Home*>/core/config directory.
5. Update the IntroscopeAgent.profile file
   * Navigate to <*Agent_Home*>/core/config to update the IntroscopeAgent.profile file.
   * Add the pbd files to the directives in the IntroscopeAgent.profile.
6. Copy the ext/xmltv/browser.typeviewers.xml file from the downloaded extension into the MOM <*EM_HOME*>ext/xmltv directory.

# Support
This document and extension are made available from CA Technologies. They are provided as examples at no charge as a courtesy to the CA APM Community at large. This extension might require modification for use in your environment. However, this extension is not supported by CA Technologies, and inclusion in this site should not be construed to be an endorsement or recommendation by CA Technologies. This extension is not covered by the CA Technologies software license agreement and there is no explicit or implied warranty from CA Technologies. The extension can be used and distributed freely amongst the CA APM Community, but not sold. As such, it is unsupported software, provided as is without warranty of any kind, express or implied, including but not limited to warranties of merchantability and fitness for a particular purpose. CA Technologies does not warrant that this resource will meet your requirements or that the operation of the resource will be uninterrupted or error free or that any defects will be corrected. The use of this extension implies that you understand and agree to the terms listed herein.
Although this extension is unsupported, please let us know if you have any problems or questions. You can add comments to the CA CA APM Community site so that the author(s) can attempt to address the issue or question.
Unless explicitly stated otherwise this extension is only supported on the same platforms as the CA APM Java agent. 

# Support URL
https://github.com/CA-APM/browser-agent-typeview/issues

# Product Compatibilty Matrix
http://pcm.ca.com/

# Categories
Examples

# Change Log
Changes for each extension version.

Version | Author | Comment
--------|--------|--------
1.0 | guenter.grossberger@ca.com | First version of the extension.
