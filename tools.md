---
layout: default
title: Tools
---

# Extensions

# Bookmarklets

In addition to using the extensions we use, a bookmarklet can help you by only needing to click the bookmark instead of finding the link on the page. To install, you drag the link or icon into your browser's bookmarks toolbar. Then, when you are on the page with the form, click the bookmark to have it fill out the form for you.

## Click the first Select Visit Time button on the page.
<a class="float-left" href='javascript:$("#Marker0Div button").click();'><i class="fa fa-check fa-4x" aria-hidden="true"></i><span style="display:none;">Click 1st Button</span></a> This bookmarklet will click the first Select Visit Time button. Drag the checkmark to your bookmarks toolbar to use it.

Code: <code>javascript:$("#Marker0Div button").click();</code>

## Click the first time slot and submit the form.
<a class="float-left" href='javascript:$('input[name=preRegTimeSlotID]:first').attr('checked', true); $('form[name=DatesForm]').submit();'><i class="fa fa-bolt fa-4x" aria-hidden="true"></i><span style="display:none;">Click 1st Time. </span></a> This bookmarklet will click the first time slot and submit the forms. Drag the bolt icon to your bookmarks toolbar to use it.

Code: <code>javascript:$('input[name=preRegTimeSlotID]:first').attr('checked', true); $('form[name=DatesForm]').submit();</code>
