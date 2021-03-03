---
layout: default
title: Helpful Tools
---

# Extensions
These two extensions make up [our process](/our-process):
 - [C19 Magic NY Extension](https://chrome.google.com/webstore/detail/c19-magic-ny/feeepbmhmihglmdnafpaeddiinadkijb?hl=en&authuser=0){:target="_blank"} is an custom extension. When starated, it will automatically refresh the page every 10 seconds, give an audio and text notification and click the Select Visit Time button. It does not select a time.
 - [Auto Click Auto Fill](/autoclick){:target="_blank"} will help you automatically click the first available time slot. This extension takes a lot of setup.

We have also tried these two extensions. They are generic and work on any web page:
 - [Free Auto Refresh](https://www.google.com/url?q=https://chrome.google.com/webstore/detail/free-auto-refresh/lfkfikiejjfhpfbpgfolfkkdjpepmkal){:target="_blank"} works well and is explained in [our process](/our-process).
 - [Easy Auto Refresh](https://chrome.google.com/webstore/detail/easy-auto-refresh/aabcgdmkeabbnleenpncegpcngjpnjkc?hl=en){:target="_blank"} will refresh the page. You can pay for notifications.

# Bookmarklets
In addition to using the extensions we use, a bookmarklet can help you by only needing to click the bookmark instead of finding the link on the page. To install, you drag the link or icon into your browser's bookmarks toolbar. Then, when you are on the page with the form, click the bookmark to have it fill out the form for you.

<div class="row" markdown="1">

## Click the first Select Visit Time button on the page.
<a class="float-left mr-2" href='javascript:$("#Marker0Div button").click();'><i class="fa fa-check fa-4x" aria-hidden="true"></i><span style="display:none;">Click 1st Button</span></a> This bookmarklet will click the first Select Visit Time button. Drag the checkmark to your bookmarks toolbar to use it.

Code: <code>javascript:$("#Marker0Div button").click();</code>

</div><div class="row" markdown="1">

## Click the first time slot and submit the form.
<a class="float-left mr-2" href="javascript:$('input[name=preRegTimeSlotID]:first').attr('checked', true); $('form[name=DatesForm]').submit();"><i class="fa fa-bolt fa-4x px-3" aria-hidden="true"></i><span style="display:none;">Click 1st Button</span></a> This bookmarklet will click the first time slot and submit the forms. Drag the bolt icon to your bookmarks toolbar to use it.

Code: <code>javascript:$('input[name=preRegTimeSlotID]:first').attr('checked', true); $('form[name=DatesForm]').submit();</code>
