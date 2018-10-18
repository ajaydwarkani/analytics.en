---
description: Offline mode returns placeholder data to speed up the process of creating and editing requests.
seo-description: Offline mode returns placeholder data to speed up the process of creating and editing requests.
seo-title: Offline mode for creating and editing requests
solution: Analytics
title: Offline mode for creating and editing requests
topic: Report builder
uuid: ea1ce5ca-bc9b-482b-b7e9-0d4a275e969c
index: y
internal: n
snippet: y
translate: y
---

# Offline mode for creating and editing requests

When you create or edit new request, Report API calls are made to retrieve the response. This slows down the request creation process, because you have to wait for the data to return before going to the next step. Offline mode returns placeholder data only, so no API calls have to be made. 

To enable offline mode: 

1. Click **[!UICONTROL  Options]** in the Report Builder menu. ![](assets/offline_mode.png) 

1. Check the checkbox next to **[!UICONTROL  Turn on offline mode for creating and editing requests]**.
1. In the **[!UICONTROL  Display Metric Data as]** field, enter the placeholder data that you want returned in your request. For example, enter "1".
1. Click **[!UICONTROL  OK]**.
1. Now create and run your request (in offline mode) using the Request Wizard.
1. Your request with "1" as the placeholder data will look similar to this: ![](assets/offline_mode_example.png) 

   >[!IMPORTANT]
   >
   >Make sure you disable Offline Mode before running your requests with real data. To do so, just go back to **[!UICONTROL  Options]** and remove the checkmark. 
