---
title: analytics and experience cloud id service requests
description: an overview of how the experience cloud id service works with the legacy analytics id
seo-title: adobe analytics and adobe experience cloud id service requests
seo-description: an overview of how the adobe experience cloud id service works with the legacy adobe analytics id
short-title: id service requests
doc-type: reference
audience: admin
index: true
translate: true
version: false
private-feature-pack: false
beta: false
redirect: false
product: core services id service
cloud: experience cloud
archetype: admin
user-guide: id service admin guide
git-edit: https://git.corp.adobe.com/AdobeDocs/core-services.en/tree/master/help/id-service/reference/reference-analytics/reference-analytics-legacy-analytics.md
git-issue: https://git.corp.adobe.com/AdobeDocs/core-services.en/issues/new
git-repo: https://git.corp.adobe.com/adobedocs/core-services.en
---
<!--Meta Data Values

**Required Meta for search optimization and page data**

title: free text string

description: free text string

seo-title: free text string

seo-description: free text string

**Optional Meta for extended capabilities**

audience:
all (default), admin, developer, end-user
 
index: true (default), false
 
translate:
true (default), false
 
doc-type:
reference (default), tutorials

version:
false (default), Classic, Standard, 6.5, 6.4, 6.3, 6.2
 
private-feature-pack:
false (default), true
 
beta:
false (default), true
 
redirect:
false (default), pathname
-->

# Analytics and Experience Cloud ID Requests

An overview of how the Experience Cloud ID service works with the legacy Analytics ID.

## Summary

Historically, the Experience Cloud ID service has been integrated tightly into Adobe Analytics. It remains an integral part of Analytics but now performs important functions for other solutions and features in the Experience Cloud. 

Because of this historical legacy, checking for or writing an Analytics ID works a little differently than with the generic process described in [How the Experience Cloud ID Service Requests and Sets IDs](../../getting-started/getting-started-id-request.md). For additional information on the order of operations for checking IDs, see [Setting Analytics and Experience Cloud IDs](reference-analytics-ids.md).

## The AMCV Cookie is Not Set in the Browser

If the Experience Cloud \(AMCV\) cookie is not present, then an ID service call to Adobe generates a response that varies depending on the presence or absence of a legacy Analytics ID. The legacy Analytics ID is stored in the [s\_vi cookie](https://marketing.adobe.com/resources/help/en_US/whitepapers/cookies/?f=cookies_analytics.html). 

Below describes how IDs are written to the AMCV cookie based on the state of the `s\_vi` cookie.

### s\_vi Cookie is Not Set

The ID service assigns visitors a Experience Cloud ID \(MID\). The MID identifies your visitors to Analytics and other Experience Cloud solutions.

### s\_vi Cookie is Set

When a site visitor with an `s\_vi` cookie first encounters the Experience Cloud ID service, this service:

+ Writes the Analytics ID stored in the `s\_vi` cookie to the AMCV cookie. This is written as the Analytics ID \(AID\). This action *does not* affect your visitor counts. Analytics will continue to identify users with their legacy IDs.
+ Writes the MID to the AMCV cookie. The MID identifies users across different solutions.

>[!NOTE]
>With a [grace period](reference-analytics-grace.md), the data center response always includes a legacy ID that is stored in the `s\_vi` cookie. During the grace period, the legacy ID is written to the AMCV cookie as the AID value.
Users identified by the `s\_fid` cookie will not have their legacy FID value migrated to the AMCV cookie. With an `s\_fid` cookie, users will be migrated as if no `s\_vi` cookie was present \(see above\) and appear as new visitors to your site. See [Analytics Cookies](https://marketing.adobe.com/resources/help/en_US/whitepapers/cookies/?f=cookies_analytics.html) for more information.

## The AMCV Cookie is Set in the Browser

If the AMCV cookie is present, Analytics will use the MID as the Analytics identifier if there is no legacy Analytics ID value in the cookie.