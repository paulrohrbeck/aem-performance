# AEM Performance
A collection of links and resources for creating faster websites with AEM. These are not endorsements but help to create a full picture of the problem space so that you can pick and choose whatever solution works best in your scenario.

## Articles
* [Efficient Error Handling with AEM, Dispatcher, and Apache Web Server](https://experiencemanaged.com/posts/efficient-error-handling-with-aem-dispatcher-and-apache-web-server.html)
* [Dispatcher Caching based on Resource Types](https://medium.com/@preeti.bhaya/dispatcher-caching-based-on-resource-types-afc712e6f5ef)

## Adobe documentation pages
* [Configuring Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/configuring/dispatcher-configuration.html)
* [Optimizing the Dispatcher cache](https://helpx.adobe.com/experience-manager/kb/optimizing-the-dispatcher-cache.html)
* [Optimizing AEM Site Caches](https://helpx.adobe.com/experience-manager/kb/optimizing-aem-site-caches.html)

## Videos
* [Optimizing the CQ Dispatcher Cache](https://my.adobeconnect.com/p7th2gf8k43)

## Solutions
* [AEM ACS Commons - Versioned ClientLibs](https://adobe-consulting-services.github.io/acs-aem-commons/features/versioned-clientlibs/index.html) - Allow CSS and JavaScript served via AEM ClientLibs to be cached client-side with long TTLs
* [AEM ACS Commons - Dispatcher TTL](https://adobe-consulting-services.github.io/acs-aem-commons/features/dispatcher-ttl/index.html) - Allows Response Headers to be set instructing AEM Dispatcher to respect a TTL-based timeout
* [AEM ACS Commons - Named Transform Image Servlet](https://adobe-consulting-services.github.io/acs-aem-commons/features/named-image-transform/index.html) - Allows specific image transforms to be defined centrally via OSGi configurations
* [AEM ACS Commons - ETag Support](https://adobe-consulting-services.github.io/acs-aem-commons/features/etag/index.html) - Sets an Entity Tag (ETag) response header based on the message digest (usually MD5) of the response body and its headers to support Conditional Requests.
* [AEM ACS Commons - Dispatcher FLush Rules](https://adobe-consulting-services.github.io/acs-aem-commons/features/dispatcher-flush-rules/index.html) - Create smarter cache invalidation rules to get around limitations with stat file level.
* [Apache Sling Dynamic Include](https://sling.apache.org/documentation/bundles/dynamic-includes.html) - Replaces dynamic components (eg. current time or foreign exchange rates) with server-side include tags (eg. SSI or ESI)
* [Purge Surgeon](https://github.com/AvionosLLC/purge-surgeon) - OSGi bundle that uses the Akamai Fast Purge API to purge content from Akamai when content is replicated

## Image optimization tools
* [Squoosh](https://squoosh.app/) - Online tool for minimizing images
* [ImageOptim](https://imageoptim.com/mac) - Mac app for minimizing images in bulk
