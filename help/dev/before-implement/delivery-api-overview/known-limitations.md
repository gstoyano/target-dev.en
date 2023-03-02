---
title: [!UICONTROL Adobe Target Delivery API] Known Limitations
description: What are the known limitations with the [!UICONTROL Adobe Target Delivery API]?
keywords: delivery api
---

# Known Limitations

1. There is no authentication for [!DNL Target] Delivery APIs.
1. This API does not process cookies or redirect calls.
1. Support for [!UICONTROL Automated Personalization] (AP) and [!UICONTROL Recommendations] activities: This API has two modes for fetching content: execute and prefetch mode. Prefetch mode can only be used for [!UICONTROL AB Test] and [!UICONTROL Experience Targeting] (XT) activities. Do not use prefetch mode for [!UICONTROL Automated Personalization] (AP), [!UICONTROL Auto-Allocate], [!UICONTROL Auto-Target], or [!UICONTROL Recommendations] activity types.