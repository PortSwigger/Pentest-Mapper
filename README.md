# Pentest Mapper #

Pentest Mapper is a Burp Suite extension that integrates the Burp Suite request logging with a custom application testing checklist. The extension provides a straightforward flow for application penetration testing. The extension includes functionalities to allow users to map the flow of the application for pentesting to better analyse the application and its vulnerabilities. The API calls from each flow can be connected with the function or flow name. The extension allows users to map or connect each flow or API to vulnerability with the custom checklist. 

# Installation

- Extension is available on Burp Suite BApp Store

# Documentation

https://anof-cyber.github.io/Pentest-Mapper/

# Features Summary
 **1. Checklist**
 
 Allows to load the custom checklist 
 
 **2. API Mapper**
 
 Allow to keep track of each API call, Flow and Test Cases for each API calls.
 
 **3. Vulnerability**
 
 Allows to keep track of vulnerabilities, Map each paramter and API call to vulnerability from the Checklist and severity
 
 **4. Config** 
 
 Allow to set Auto save the project or extension data and auto load the checklist. Also import and export all data with one click



# Features

 **1. Checklist**

The checklist allows users to create or upload the custom checklist to map each API call to the vulnerability from the custom uploaded checklist.

![picture](./images/CheckList.png)


 **2. API Mapper**

The API Mapper tab allows logging the HTTP request from the poxy or repeater tab and mapping the request with the flow and sorting the request based on the flow. Also, the tab allows users to write the comment or test cases for each API call logged into the extension. The tab allows mapping each API with the vulnerability from the checklist.

![picture](./images/APIMapper.png)

![picture](./images/APIMapper2.png)


 **3. Vulnerabilities**

The tab stores the URL and parameters and allows users to map the selected API to the vulnerabilities.

![picture](./images/Vulnerability-selection.png)
![picture](./images/severity.png)

 **4. Config**
 
The config tab allow you to set time for auto save after specific time peried and select the output location. You can also set the auto load the checklist file and Import and export data with one click. You can also turn on off the Auto Save and Auto Logging request from proxy for scope domain
 
![picture](./images/Config.png)

**Sending Request**

![picture](./images/Sendreq.png)

___

# TBD

* ~~Single Click Import and Export~~
* ~~Auto Save the project Data~~
* ~~Auto Logging Scope APIs and requests with Optional mode~~
* ~~Seach option for all 3 tables to manage long table~~
* ~~Solving long checklist selection from vulnerability~~
* ~~Updating checklist file automatically~~
* ~~Map Vulnerabilities with Severity~~
* Custom and Default CVSS score generation
* Multiple row selection for API Mapper
* ~~Turn on off auto save from config~~
* ~~Optimization of code~~
* ~~Allowing individual request to mark as completed~~
* ~~Allowing Request and Response for Vulnerability~~

