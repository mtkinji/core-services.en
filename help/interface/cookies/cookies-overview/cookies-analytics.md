---
description: Adobe Analytics uses cookies to differentiate requests from different browsers and to store helpful information that an application can use later. They may also be used to associate browsing information to customer records.
keywords: cookies;privacy
seo-description: Adobe Analytics uses cookies to differentiate requests from different browsers and to store helpful information that an application can use later. They may also be used to associate browsing information to customer records.
seo-title: Analytics Cookies
solution: Marketing Cloud,Analytics,Target,Social
title: Analytics Cookies
uuid: e2d3d61d-2708-48b2-a7e6-2331f2aed8e0
index: y
internal: n
snippet: y
---

# Analytics Cookies{#analytics-cookies}

Adobe Analytics uses cookies to differentiate requests from different browsers and to store helpful information that an application can use later. They may also be used to associate browsing information to customer records.

 In particular, Analytics uses cookies to anonymously define new visitors, help analyze clickstream data, and track historical activity on the website, such as response to particular campaigns or the length of the sales cycle.

* [Cookie Name: s_ecid](../cookies-overview/cookies-mc.md#section-32fd753c3fa54452acd62b021434919a) 
* [Cookie Name: AMCV_###@AdobeOrg](../cookies-overview/cookies-mc.md#section-a12aa2a9296940ae82d8921b381b8fb0) 
* [Cookie Name: s_cc](../cookies-overview/cookies-analytics.md#section-03aa90aa7e36427b8cb12dc4a0f0291e) 
* [Cookie Name: s_sq](../cookies-overview/cookies-analytics.md#section-8abfff3a302d494f81a3cfb91e3b09ff) 
* [Cookie Name: s_vi](../cookies-overview/cookies-analytics.md#section-5d50a078de444d12b7d927d68ff3b679) 
* [Cookie Name: s_fid](../cookies-overview/cookies-analytics.md#section-65e33f9bfc264959ac1513e2f4b10ac7) 
* [Cookies Set By Plug-ins](../cookies-overview/cookies-analytics.md#section-a6b1cae8454945fab9eea5c7884c40fc)

More information is available in Analytics help about [First-Party Cookies](https://marketing.adobe.com/resources/help/en_US/whitepapers/first_party_cookies/fpcookies_overview.html).

## Cookie Name: s_ecid {#section-32fd753c3fa54452acd62b021434919a}

<table id="table_FF4C70D3D4CC425BA65162D5A9504F7D"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Attribute </p> </th> 
   <th colname="col2" class="entry"> <p>Description </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Information Stored </p> </td> 
   <td colname="col2"> <p> Contains a copy of the Experience Cloud ID (ECID) or MID. The MID is stored in a key-value pair that follows this syntax, s_ecid=MCMID|&lt;ECID&gt; </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Expiration </p> </td> 
   <td colname="col2"> <p>2 years </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Usage </p> </td> 
   <td colname="col2"> <p>This cookie is set by the customer's domain after the AMCV cookie is set by the client. The purpose of this cookie is to allow persistent ID tracking in the 1^st^ party state and is used as a reference ID if the AMCV cookie has expired. Check AMCV cookie here for more details. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Location </p> </td> 
   <td colname="col2"> <p>CNAME customers only. Not applicable for 3^rd^party scenarios. Cookie is stored on your domain, the same domain used by CNAME and your Analytics image request. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Size </p> </td> 
   <td colname="col2"> <p>45 bytes </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cookie Name: s_cc {#section-03aa90aa7e36427b8cb12dc4a0f0291e}

<table id="table_34AA90F2FFB84500A77D8F4C5008D453"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Attribute </p> </th> 
   <th colname="col2" class="entry"> <p>Description </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Information Stored </p> </td> 
   <td colname="col2"> <p> This cookie is set and read by the JavaScript code to determine if cookies are enabled (simply set to "True") </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Expiration </p> </td> 
   <td colname="col2"> <p> This cookie is a session cookie and expires when the browser is closed </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Usage </p> </td> 
   <td colname="col2"> <p> Only one cookie for all accounts </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Location </p> </td> 
   <td colname="col2"> <p> This cookie is stored at the domain of the page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Size </p> </td> 
   <td colname="col2"> <p> 4 bytes </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cookie Name: s_sq {#section-8abfff3a302d494f81a3cfb91e3b09ff}

<table id="table_05EEB54B5EA2409DB1D071FD1484E8F9"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Attribute </p> </th> 
   <th colname="col2" class="entry"> <p>Description </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Information Stored </p> </td> 
   <td colname="col2"> <p> This cookie is set and read by the JavaScript code when the ClickMap functionality and the Activity Map functionality are enabled; it contains information about the previous link that was clicked on by the user </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Expiration </p> </td> 
   <td colname="col2"> <p> This cookie is a session cookie and expires when the browser is closed </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Usage </p> </td> 
   <td colname="col2"> <p> Only one cookie for all accounts </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Location </p> </td> 
   <td colname="col2"> <p> This cookie is stored at the domain of the page </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Size </p> </td> 
   <td colname="col2"> <p> Depending on page URL size it varies, but typically 100-200 bytes </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cookie Name: s_vi {#section-5d50a078de444d12b7d927d68ff3b679}

<table id="table_774F04AA9E3847D9AE7803520B5AAAE3"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Attribute </p> </th> 
   <th colname="col2" class="entry"> <p>Description </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Information Stored </p> </td> 
   <td colname="col2"> <p> Unique visitor ID time/date stamp </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Expiration </p> </td> 
   <td colname="col2"> <p> 2 years </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Usage </p> </td> 
   <td colname="col2"> <p> This cookie is used to identify a unique visitor </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Location </p> </td> 
   <td colname="col2"> <p> This cookie is stored at the domain of the image request - typically 2O7.net if you are using third-party cookies, or your domain if using first-party cookies. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Size </p> </td> 
   <td colname="col2"> <p> 44 bytes </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Each Analytics visitor ID is associated with a visitor profile on Adobe servers. Visitor profiles are deleted after 1 year of inactivity regardless of any visitor ID cookie expiration.

## Cookie Name: s_fid {#section-65e33f9bfc264959ac1513e2f4b10ac7}

<table id="table_B0EDB50677D14A86A1BFB7CCAAE95C88"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Attribute </p> </th> 
   <th colname="col2" class="entry"> <p>Description </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Information Stored </p> </td> 
   <td colname="col2"> <p> Fallback unique visitor ID time/date stamp </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Expiration </p> </td> 
   <td colname="col2"> <p>5 years </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Usage </p> </td> 
   <td colname="col2"> <p> This cookie is used to identify a unique visitor if the standard <span class="codeph"> s_vi </span> cookie is unavailable due to third-party cookie restrictions. Not used for implementations that use first-party cookies. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Location </p> </td> 
   <td colname="col2"> <p> This cookie is stored on your domain as a first-party cookie. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Size </p> </td> 
   <td colname="col2"> <p> 33 bytes </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cookies Set By Plug-ins {#section-a6b1cae8454945fab9eea5c7884c40fc}

Additional cookies can be set depending on the use of Analytics plug-ins. These cookies are snippets of code available to the client for use in a variety of circumstances. These circumstances include: retrieving values from the URL; concatenating values to pass to Analytics; capturing form abandonment, and so on. For specifics on cookies that are set by each plug-in, contact ClientCare. An example would be the [!DNL s_vh] cookie used with the *Set Once Per* and *Set and Get Last Value* plug-ins.

Conversion variables (eVarX) passed in on a image request without JavaScript, such as code placed within an email, are attributed properly only if the email client and web browser share the same cookie space. 
