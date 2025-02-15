---
keywords: mboxDefine, mboxdefine, mbox define, mboxUpdate, mboxupdate, mbox update, at.js, functions, function, mboxDefine0
description: Use the [!UICONTROL mboxDefine()] and [!UICONTROL mboxUpdate()] functions for the [!DNL Adobe Target] at.js JavaScript library to define or update an mbox. (at.js 1.x)
title: How Do I Use the [!UICONTROL mboxDefine()] And [!UICONTROL mboxUpdate()] Functions?
feature: at.js
role: Developer
exl-id: 0a7dbea2-1cbd-4a5b-ba68-4c76a88d65c4
---
# [!UICONTROL mboxDefine()] and [!UICONTROL mboxUpdate()] - at.js 1.x

Define and update an mbox in [!DNL Adobe Target].

>[!NOTE]
>
>These functions are available for at.js versions 1.*x* only. These functions were deprecated with the release of at.js 2.*x*. These functions return default content if used with at.js 2.*x*.

`[!UICONTROL mboxDefine()]` and `[!UICONTROL mboxCreate()]` are tied to HTML DIV elements where the offer should be displayed. These HTML DIV elements should have the `mboxDefault` class. If the HTML elements won't have this class attached, you could see some noticeable flicker.

## mboxDefine

Creates an internal mapping between a nodeId and an mbox name, but does not execute the request. Used in conjunction with `[!UICONTROL mboxUpdate()]`. Built into at.js mostly to ease the transition from mbox.js (now deprecated) to at.js.

## mboxUpdate

Executes the request and applies the offer to the element identified by the `nodeId` in the `mboxDefine()`. Can also be used to update an mbox initiated by `[!UICONTROL mboxCreate]`. Built into at.js mostly to ease the transition from mbox.js (now deprecated) to at.js. `mboxDefine()`/ `mboxUpdate()` could be replaced by [adobe.target.getOffer()](/help/dev/implement/client-side/atjs/atjs-functions/adobe-target-getoffer.md) and [adobe.target.applyOffer()](/help/dev/implement/client-side/atjs/atjs-functions/adobe-target-applyoffer.md) using the selector option.

## Example

```javascript {line-numbers="true"}
<div id="someId" class="mboxDefault"></div> 
<script> 
 mboxDefine('someId','mboxName','param1=value1','param2=value2'); 
 mboxUpdate('mboxName','param3=value3','param4=value4'); 
</script>
```
