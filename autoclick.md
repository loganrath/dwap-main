---
layout: default
title: Auto Select a Time Using Auto Click Auto Fill
---

We have had a lot of luck using this extension to automatically grab times. Installing and configuring this extension can be tricky and might require patience. The [Auto Click Auto Fill](https://chrome.google.com/extensions/detail/iapifmceeokikomajpccajhjpacjmibe){:target="_blank"} extension will automatically select the time if one is available.

# Step 1: Install the Extension
 1. Go to [https://chrome.google.com/extensions/detail/iapifmceeokikomajpccajhjpacjmibe](https://chrome.google.com/extensions/detail/iapifmceeokikomajpccajhjpacjmibe){:target="_blank"} install the extension.
 2. Use the puzzle piece icon to pin the extension to your browser.

# Step 2: Download and install the configuration File
This configuration file currently works, but we cannot guarantee that it will always work.
 1. Right-click on this [configuration file](https://raw.githubusercontent.com/loganrath/dwap-main/gh-pages/docs/autoclick_time.json){:target="_blank"} and save it to your computer using the Save Link as option.
  - If your computer does not recognize the .json format, change the file type dropdown to All files.  
  ![Screenshot showing file type as all files](/assets/images/autoclick-download.png)
 2. Click on the extension to open its settings.
 3. Click the import button at the top of the configuration section and then choose import.  
 ![Screenshot showing installation](/assets/images/autoclick-import.png)
 4. Select the file you downloaded in step 1.
 5. Under the Configuration heading, **if necessary** the URL field so that the number after apps in the first part of the URL matches the web address of your site. This could be apps2, apps4, apps5, apps7, or some other number.  
 ![Screenshot showing URL to fix](/assets/images/autoclick-url.png)
 6. Do not edit anything else for this configuration.
 7. Close the tab.

# Step 3: Close and Reopen Chrome
Quit and re-open Chrome. Then when you land on a page that has a time slot available, it should auto select it and show you the form to begin registration. If you receive an error message on the website, that means someone else grabbed the time before you. You can then start over looking for appointments.

# Step 4: Update as Needed
If the URL of the appointment page changes (e.g. from apps5 to apps7), you will need to repeat step 2 part 5 to make sure the correct domain in showing.


# To turn off this extension
You need to [disable the extension](https://support.google.com/chrome_webstore/answer/2664769?hl=en){:target="_blank"} in order for it to stop working.
