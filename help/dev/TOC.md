---
user-guide-title: Adobe [!DNL Target] Developer Guide
breadcrumb-title: Target Developer Guide
user-guide-description: Learn how to tailor and personalize your customers' experience to maximize revenue on your web and mobile sites, apps, social media, and other digital channels.
---

# Target Implementation Guide {#developer}

+ [Overview](overview.md)
+ Implementation {#implementation}
  + Before you implement {#before-implement}
    + [Before you implement](before-implement/considerations-before-you-implement-target.md)
    + [Prepare to implement Target](before-implement/prepare-to-implement-target.md)
  + Privacy and security {#privacy}
     + [Privacy overview](before-implement/privacy/privacy.md)
     + [Privacy and data protection regulations](before-implement/privacy/cmp-privacy-and-general-data-protection-regulation.md)
     + [Target cookies](before-implement/privacy/cookie-behavior.md)
     + [Delete the Target cookie](before-implement/privacy/cookie-deleting.md)
     + [Google Chrome SameSite cookie policies](before-implement/privacy/google-chrome-samesite-cookie-policies.md)
     + [Apple Intelligent Tracking Prevention (ITP) 2.x](before-implement/privacy/apple-itp-2x.md)
     + [Content Security Policy (CSP) directives](before-implement/privacy/content-security-policy.md)
     + [Allowlist Target edge nodes](before-implement/privacy/allowlist-edges.md)
  + Methods to get data into Target {#methods}
     + [Methods overview](before-implement/methods-to-get-data-into-target/methods-to-get-data-into-target.md)
     + [Page parameters](before-implement/methods-to-get-data-into-target/page-parameters.md)
     + [In-page profile attributes](before-implement/methods-to-get-data-into-target/in-page-profile-attributes.md)
     + [Script profile attributes](before-implement/methods-to-get-data-into-target/script-profile-attributes.md)
     + [Data providers](before-implement/methods-to-get-data-into-target/data-providers.md)
     + [Bulk profile update API](before-implement/methods-to-get-data-into-target/bulk-profile-update-api.md)
     + [Single profile update API](before-implement/methods-to-get-data-into-target/single-profile-update-api.md)
     + [Customer attributes](before-implement/methods-to-get-data-into-target/customer-attributes.md)
     + [Profile API settings](before-implement/methods-to-get-data-into-target/profile-api-settings.md)
  + [Target security overview](before-implement/target-security-overview.md)
  + [Supported browsers](before-implement/supported-browsers.md)
  + [TLS (Transport Layer Security) encryption changes](before-implement/tls-transport-layer-security-encryption.md)
  + [CNAME and Adobe Target](before-implement/implement-cname-support-in-target.md)
  + Delivery API Overview {#delivery-api}
    + [Introduction](before-implement/delivery-api-overview/introduction.md)
    + [SDKs](before-implement/delivery-api-overview/sdks.md)
    + [Getting Started](before-implement/delivery-api-overview/getting-started.md)
    + [User Permissions (Premium)](before-implement/delivery-api-overview/user-permissions.md)
    + [Identifying Visitors](before-implement/delivery-api-overview/identifying-visitors.md)
    + [Single or Batch Delivery](before-implement/delivery-api-overview/single-or-batch.md)
    + [Prefetch](before-implement/delivery-api-overview/prefetch.md)
    + [Notifications](before-implement/delivery-api-overview/notifications.md)
    + [Integration with Experience Cloud](before-implement/delivery-api-overview/integration.md)
    + [Known Limitations](before-implement/delivery-api-overview/known-limitations.md)
    + [Client Hints](before-implement/delivery-api-overview/client-hints.md)
+ Client-side web: implement Target {#client-side}
   + [Overview: implement Target for client-side web](implement/client-side/overview.md)
   + [AEP Web SDK implementation overview](implement/client-side/aep-web-sdk.md)
   + at.js implementation {#at-js-implementation}
      + [Overview of at.js](implement/client-side/atjs/how-atjs-works/overview.md)
      + How at.js works {#at-js}
         + [How at.js works overview](implement/client-side/atjs/how-atjs-works/how-atjs-works.md)
         + [How at.js manages flicker](implement/client-side/atjs/how-atjs-works/manage-flicker-with-atjs.md)
        + [at.js integrations](implement/client-side/atjs/how-atjs-works/target-atjs-integrations.md)
      + How to deploy at.js {#deploy-at-js}
         + [How to deploy at.js](implement/client-side/atjs/how-to-deployatjs/how-to-deployatjs.md)
         + [Implement Target using Adobe Experience Platform](implement/client-side/atjs/how-to-deployatjs/cmp-implementing-target-using-adobe-launch.md)
         + [Implement Target without a tag manager](implement/client-side/atjs/how-to-deployatjs/implementing-target-without-a-tag-manager.md)
         + [Implement Target using Dynamic Tag Manager (DTM)](implement/client-side/atjs/how-to-deployatjs/implementing-target-using-dynamic-tag-management.md)
         + [Implement Target for Single Page Applications (SPAs)](implement/client-side/atjs/how-to-deployatjs/target-atjs-single-page-application.md)
      + On-device decisioning {#on-device-decisioning}
         + [On-device decisioning overview](implement/client-side/atjs/on-device-decisioning/on-device-decisioning.md)
         + [Supported features](implement/client-side/atjs/on-device-decisioning/supported-features.md)
         + [Rule artifact](implement/client-side/atjs/on-device-decisioning/rule-artifact.md)
         + [Troubleshooting](implement/client-side/atjs/on-device-decisioning/troubleshooting-on-device-decisioning.md)
      + at.js functions {#functions-overview}
         + [at.js functions overview](implement/client-side/atjs/atjs-functions/atjs-functions.md)
         + [adobe.target.getOffer()](implement/client-side/atjs/atjs-functions/adobe-target-getoffer.md)
         + [adobe.target.getOffers() - at.js 2.x](implement/client-side/atjs/atjs-functions/adobe-target-getoffers-atjs-2.md)
         + [adobe.target.applyOffer()](implement/client-side/atjs/atjs-functions/adobe-target-applyoffer.md)
         + [adobe.target.applyOffers() - at.js 2.x](implement/client-side/atjs/atjs-functions/adobe-target-applyoffers-atjs-2.md)
         + [adobe.target.triggerView() - at.js 2.x](implement/client-side/atjs/atjs-functions/adobe-target-triggerview-atjs-2.md)
         + [adobe.target.trackEvent()](implement/client-side/atjs/atjs-functions/adobe-target-trackevent.md)
         + [mboxCreate() - at.js 1.x](implement/client-side/atjs/atjs-functions/mboxcreate-atjs.md)
         + [targetGlobalSettings()](implement/client-side/atjs/atjs-functions/targetgobalsettings.md)
         + [mboxDefine() and mboxUpdate() - at.js 1.x](implement/client-side/mboxdefine-mboxupdate-atjs-1x.md)
         + [targetPageParams()](implement/client-side/targetpageparams.md)
         + [targetPageParamsAll()](implement/client-side/atjs/atjs-functions/targetpageparamsall.md)
         + [registerExtension() - at.js 1.x](implement/client-side/atjs/atjs-functions/registerextension-atjs-1x.md)
         + [sendNotifications() - at.js 2.1](implement/client-side/atjs/atjs-functions/adobe-target-sendnotifications-atjs-21.md)
         + [at.js custom events](implement/client-side/atjs/atjs-functions/atjs-custom-events.md)
         + [Debug at.js using the Adobe Experience Cloud Debugger](implement/client-side/target-debugging-atjs/target-debugging-atjs.md)
         + [Use cloud-based instances with Target](implement/client-side/target-debugging-atjs/targeting-using-cloud-based-instances.md)
      + [at.js FAQs](implement/client-side/atjs/target-atjs-faq.md)
      + [at.js version details](implement/client-side/atjs/target-atjs-versions.md)
      + [Upgrading from at.js 1.x to at.js 2.x](implement/client-side/atjs/upgrading-from-atjs-1x-to-atjs-20.md)
      + [at.js cookies](implement/client-side/atjs/atjs-cookies.md)
   + Understand the Global mbox {#global-mbox}
      + [Understand the global mbox overview](implement/client-side/atjs/global-mbox/global-mbox-overview.md)
      + [Customize a global mbox](implement/client-side/atjs/global-mbox/customize-global-mbox.md)
      + [Use a global mbox from a legacy implementation](implement/client-side/atjs/global-mbox/mbox-global-target-standard.md)
      + [Pass parameters to a global mbox](implement/client-side/atjs/global-mbox/pass-parameters-to-global-mbox.md)
      + [Global mbox frequently asked questions](implement/client-side/atjs/global-mbox/global-mbox-faq.md)

  + Server Side: implement Target {#server-side}
     + [Server Side: implement Target overview](c-api-and-sdk-overview/api-and-sdk-overview.md)
     + [Transition from Target legacy APIs to Adobe I/O](c-api-and-sdk-overview/target-api-documentation.md)
     + [On-device decisioning](implement/c-api-and-sdk-overview/on-device-decisioning.md)

+ [Jump to Administration Guide](https://blah.html)
+ Administration {#administration}

<!--

+ [Implement Target overview](implementing-target.md)

+ Target for mobile apps {#mobile-apps}
   + [Target for mobile apps overview](c-target-mobile-app/target-mobile-app.md)
   + [How Target works in mobile apps](c-target-mobile-app/mobile-how-target-works-mobile-apps.md)
   + [Enable Target in the SDK](c-target-mobile-app/mobile-enable-target-in-sdk.md)
   + [iOS - create a Target location and success metric](c-target-mobile-app/mobile-create-location-and-metric.md)
   + [iOS - send custom user data](c-target-mobile-app/mobile-custom-user-data.md)
   + [Target mobile preview](c-target-mobile-app/target-mobile-preview.md)
   + [Prefetch offer content](c-target-mobile-app/prefetch-offer-content.md)
   + [Target for mobile apps FAQ](c-target-mobile-app/target-for-mobile-apps-faq.md)
   + [Use Location Service](c-target-mobile-app/use-location-service.md)
+ [Hybrid implementation](implement/hybrid-implementation.md)
+ Email: implement Target {#implement-email}
   + [Email: implement Target overview](c-non-javascript-based-implementation/non-javascript-based-implementation.md)
   + [Create an Adbox for an image](c-non-javascript-based-implementation/testing-content-with-the-adbox.md)
   + [Test an email image Adbox](c-non-javascript-based-implementation/testing-email-image-adbox.md)
   + [Work with redirectors](c-non-javascript-based-implementation/working-with-redirectors.md)
-->
