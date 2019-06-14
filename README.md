[<img src="https://de.shopware.com/media/unknown/2d/80/8c/shopware_signet_blue.svg" alt="Shopware Logo" title="Shopware" align="right" width="100">](https://shopware.com/)

# Awesome Shopware [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the [Shopware](https://github.com/shopware/shopware) ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Contents

- [Backend Plugins](#backend-plugins)
- [Command Line](#command-line)
- [Configuration](#configuration)
- [Connectors](#connectors)
- [Development Plugins](#development-plugins)
- [IDE / PhpStorm Plugins](#ide--phpstorm-plugins)
- [Error Reporting](#error-reporting)
- [Plugin Examples](#plugin-examples)
- [Frontend Development Resources](#frontend-development-resources)
- [Frontend Plugins](#frontend-plugins)
- [Local Development](#local-development)
- [Payment Plugins](#payment-plugins)
- [Themes](#themes)
- [Tracking](#tracking)
- [Media Adapter](#media-adapter)

## Backend Plugins

- [ShyimBackendNotification](https://github.com/shyim/ShyimBackendNotification) - Backend Notification when multiple users working parallel.
- [Backend Order](https://github.com/shopwareLabs/SwagBackendOrder) - Plugin which allows you to create orders via backend module.
- [Import Export](https://github.com/shopwareLabs/SwagImportExport) - Import and Export articles, categories.
- [Shopware Migration](https://github.com/shopwareLabs/SwagMigration) - Migrate to Shopware from Magento, Gambio, Oxid, xt:Commerce, Prestashop, WooCommerce.
- [Query Manager](https://github.com/webmatch/WbmQueryManager) - Adds a Query Manager to the backend.
- [Template Manager](https://github.com/webmatch/WbmTemplateManager) - Adds a Template Manager to the backend.
- [ReCaptcha Backend Login](https://github.com/KSK-Agentur/HeptacomBackendCaptcha) - ReCaptcha for the backend login.
- [More Shopware Shortcuts](https://github.com/uehler/shopware-shortcuts) - Adds more Shopware Shortcuts.
- [Google Authenticator Login](https://github.com/shyim/shopware-google-auth) - Adds Google Authenticator support for the backend login.
- [Mittwald Security Plugin](https://github.com/mittwald/shopware-security-tools) - Adds some security tools.
- [Extended Plugin Manager](https://github.com/FriendsOfShopware/FroshExtendedPluginManager) - Adds plugin store links to the Plugin Manager.
- [TinyMCE Custom Font](https://github.com/shopwareLabs/SwagTinyMceCustomFont) - Adds custom font support to the backend editor.
- [MailArchive](https://github.com/FriendsOfShopware/FroshMailArchive) - Adds an archive for all sent mails in Shopware.
- [Order Documents: Allow multiple documents per type](https://github.com/buddhaCode/BucoAllowMultipleDocuments) - Allow creation of multiple documents per type and order.
- [Orders: Documents API](https://github.com/buddhaCode/BucoOrderDocumentsApi) - REST API endpoint to access and delete order documents.
- [Orders: Part documents](https://github.com/buddhaCode/BucoPartDocuments) - Create order documents for just a subset of positions of an order.

## Command Line

- [sw-cli-tools](https://github.com/shopwareLabs/sw-cli-tools) - The shopware CLI tools are your console helpers for all kind of shopware tasks.
- [scs-commander](https://github.com/VIISON/scs-commander) - A CLI tool for managing plugins in the Shopware Community Store.

## Configuration

- [Nginx](https://github.com/bcremer/shopware-with-nginx) - Nginx configuration for Shopware.
- [Caddy](https://github.com/janbuecker/shopware-with-caddy) - Caddy configuration for Shopware.

## Connectors

- [Plenty Markets](https://github.com/plentymarkets/plentymarkets-shopware-connector) - Plenty Markets Connector.
- [Shopware Connect](https://github.com/shopware/SwagConnect) - Shopware Connect.
- [Shopware API SDK PHP](https://github.com/LeadCommerceDE/shopware-sdk) - Shopware API SDK written in PHP.
- [Shopware API SDK JavaScript](https://github.com/apertureless/shopware-api-client) - Shopware API SDK written in JavaScript.
- [Shopware API SDK Python](https://github.com/micronax/python-shopware-rest-client) - Shopware API SDK written in Python.
- [Shopware API SDK C#](https://github.com/shopdoktor/shopware-csharp-api-connector) - Shopware API SDK written in C#.
- [Shopware API SDK Go](https://github.com/philipgatzka/swclient) - Shopware API SDK written in Go.

## Development Plugins

- [Adminer for Shopware](https://github.com/FriendsOfShopware/FroshAdminer) - A web database client integration.
- [Shopware Profiler](https://github.com/FriendsOfShopware/FroshProfiler) - A symfony profiler integration.
- [Whoops for Shopware](https://github.com/shyim/whoops-for-shopware) - An error message beautifier.
- [Mail Catcher](https://github.com/FriendsOfShopware/FroshMailCatcher) - Catches mails and displays them in the backend for easier mail debugging.
- [Theme Settings Export](https://github.com/simkli/SimklThemeSettingExport) - Import and export of theme settings to transfer settings between installations.
- [PackagistPluginManager](https://github.com/shyim/ShyimPluginManager) - A packagist integration for Shopware plugins.
- [Viewport Resizer](https://github.com/webmatch/WbmViewportResizer) - Shopware plugin to preview the frontend in responsive viewports.
- [View Snapshots](https://github.com/FriendsOfShopware/FroshViewSnapshots) - Records views (snapshots) and restore them at a later time.
- [Custom JavaScript/CSS Manager](https://github.com/dneustadt/DneCustomJsCss) - Manage custom JavaScript and CSS/LESS containers.
- [Prod2Testing](https://github.com/mschop/shopware-prod2testing) - Anonymize Shopware database for use of live data in development environments.
- [HTTP Cache Exclude](https://github.com/FriendsOfShopware/FroshHttpCacheIpExclude) - Exclude clients from Shopware HTTP Cache by IP, Params or Cookies

## IDE / PhpStorm Plugins

- [Shopware Plugin](https://github.com/Haehnchen/idea-php-shopware-plugin) - PhpStorm Shopware plugin.
- [Symfony Plugin](https://github.com/Haehnchen/idea-php-symfony2-plugin) - PhpStorm Symfony Plugin.
- [PHP Annotations](https://github.com/Haehnchen/idea-php-annotation-plugin) - PhpStorm Annotations plugin.
- [PHP Toolbox](https://github.com/Haehnchen/idea-php-toolbox) - PHP Toolbox includes some Shopware configurations.

## Error Reporting

- [Bugsnag](https://github.com/shopware-blog/shopware-bugsnag) - Bugsnag Error reporting.
- [Rollbar](https://github.com/shyim/ShyimRollbar) - Rollbar Error reporting.
- [Sentry](https://github.com/1drop/shopware-sentry) - Sentry Error reporting.

## Plugin Examples

- [Model Test](https://github.com/bcremer/SwagModelTest) - Custom Model (Shopware 5.2).
- [Session Handler](https://github.com/bcremer/SwagSessionHandler) - Session Handler (Shopware 5.2).
- [Product Discount](https://github.com/shopwareLabs/SwagProductDiscount) - Plugin Prototype (Shopware next).
- [Subscriber Test](https://github.com/rofthedeep/SubscriberTest) - Writing Tests for Shopware Subscriber.

## Frontend Development Resources

- [shopware-missing-mixins](https://github.com/screeny05/shopware-missing-mixins) - A collection of handy LESS mixins for Shopware.
- [shopware-missing-includes](https://github.com/screeny05/shopware-missing-includes) - A collection of Smarty includes for Shopware.
- [shopware-vueify](https://github.com/screeny05/shopware-vueify) - Write Vue.js components for use within the Shopware StateManager.
- [shopware-typedef](https://github.com/screeny05/shopware-typedef) - Shopware 5 Typescript definitions.

## Frontend Plugins

- [360° Product viewer](https://github.com/shopwareLabs/SwagThreeSixtyViewer) - 360° Product viewer for detail pages.
- [WebP Support](https://github.com/FriendsOfShopware/FroshWebp) - Adds WebP Support to Shopware.
- [Disqus](https://github.com/shyim/ShyimDisqus) - Replaces blog comments with Disqus.
- [Customer-specific prices](https://github.com/shopwareLabs/SwagUserPrice) - Customer-specific prices.
- [Share Buttons](https://github.com/KSK-Agentur/HeptacomAdvancedShare) - Adds social share buttons.
- [Thumbnail Sizes in Frontend](https://github.com/shyim/ShyimThumbnailSize) - Makes thumbnail sizes in frontend available.
- [Optimus.io Optimizer](https://github.com/FriendsOfShopware/FroshOptimusMediaOptimizer) - Optimus.io image optimizer.
- [AMP](https://github.com/KSK-Agentur/HeptacomAmp) - Adds AMP support.
- [Browser Language](https://github.com/shopwareLabs/SwagBrowserLanguage) - Language detection for multi shop setups.
- [Custom Sort](https://github.com/shopwareLabs/SwagCustomSort) - Customize article sorting in categories.
- [HybridAuth](https://github.com/portrino/shopware-hybrid-auth) - Shopware plugin for social login (Amazon, Google, Facebook, LinkedIn).
- [Mini Basket Tax Information](https://github.com/marcmanusch/PaulMiniBasketFix) - Adds tax information to the ajax basket.
- [Article Accessory Direct Buy](https://github.com/aquatuning/atsd-article-accessory-direct-buy) - Buy article accessory from detail pages.
- [Variant Switch](https://github.com/FriendsOfShopware/FroshVariantSwitch) - Update variants in basket and checkout views.
- [GDPR Compliance](https://github.com/mnaczenski/MNAddDSVGO) - Adds GDPR compliance.
- [Security Headers](https://github.com/kielcoding/KielCodingSecurityHeaders) - Adds security headers.
- [Performance Improvements](https://github.com/FriendsOfShopware/FroshPerformance) - Adds http2 push, minifies html etc.
- [Shopping Worlds on Shop Pages](https://github.com/runelaenen/RuneShoppingWorldPages) - Can replace Shop Page content with Shopping World
- [Data Table Layout](https://github.com/FriendsOfShopware/FroshDataTableLayout) - Adds data table to the available product layouts of categories/search/manufacturer
- [Font assets preloading](https://github.com/buddhaCode/BcFontPreload) - Preload font assets to reduce roundtrips and speed up frontend loading.
- [HTTP Cache: Forms](https://github.com/buddhaCode/BucoFormsHttpCache) - HTTP caching, warming and invalidation for contact forms
- [HTTP Cache: Shop pages in modal boxes](https://github.com/buddhaCode/BucoStaticXhrHttpCache) - HTTP cache warming for shop pages in modal boxes

## Local Development

- [shopware-docker](https://github.com/shopwareLabs/shopware-docker) - A Docker setup ready for Shopware development.
- [shopware-vagrant](https://github.com/shopwareLabs/shopware-vagrant) - A Vagrant setup ready for Shopware development.
- [netshops/docker-setup](https://github.com/Netshops-Commerce-GmbH/docker-setup) - Another docker setup made for web applications (Shopware configs included).

## Payment Plugins

- [Paypal](https://github.com/shopwareLabs/SwagPaymentPaypal) - A PayPal integration for Shopware.
- [Paypal Plus](https://github.com/shopwareLabs/SwagPaymentPaypalPlus) - Paypal Plus integration.
- [Payone](https://github.com/PAYONE-GmbH/shopware-5) - Payone integration.
- [Stripe](https://github.com/VIISON/ShopwareStripePayment) - Stripe integration.
- [Ratepay](https://github.com/ratepay/shopware5-module) - Ratepay integration.
- [MercadoPago](https://github.com/pthreat/StangeMercadoPago) - MercadoPago integration.
- [Wallee](https://github.com/wallee-payment/shopware) - Wallee integration.
- [Paymill](https://github.com/paymill/paymill-shopware) - Paymill integration.
- [Mollie](https://github.com/mollie/Shopware) - Mollie integration.
- [Wirecard](https://github.com/wirecard/shopware-wcs) - Wirecard integration.
- [Heidelpay](https://github.com/heidelpay-sp/ShopwareStandardModul) - Heidelpay integration.
- [G2A Pay](https://github.com/g2a-official/g2a-pay-shopware) - G2A Pay integration.
- [iPayment](https://github.com/shopwareLabs/SwagPaymentIpayment) - IPayment integration.

## Themes

- [Bootstrap based Theme](https://github.com/conexco/shopware-bootstrap-theme) - Shopware Bootstrap theme.
- [Flat Theme](https://github.com/8mylezOrganization/shopware-8mzFlatResponsiveTheme) - Responsive theme in flat look.
- [Views Theme](https://github.com/Blur-Creative/theme-views) - Responsive, customizable, flexible and multipurpose theme.

## Tracking

- [Google Integration](https://github.com/shopwareLabs/SwagGoogle) - Google Analytics, Universal Analytics and Google Adwords integration.
- [Google Remarketing](https://github.com/arvatis/GoogleRemarketing) - Google Remarketing integration.
- [Google Certified Stores](https://github.com/arvatis/GoogleCertifiedStores) - Google Certified Shop integration.
- [Nosto](https://github.com/Nosto/nosto-shopware) - Nosto integration.
- [Tag Manager Integration](https://github.com/webmatch/WbmTagManager) - Google Tag Manager integration with backend configuration of data layer variables.
- [Tawk.to](https://github.com/shyim/ShopwareTawkTo) - Tawk.to Chat integration.
- [Livezilla](https://github.com/marcmanusch/PaulLiveZillaKnowledgeBase) - Livezilla Integration.
- [Stetic](https://github.com/stetic/stetic-shopware) - Stetic integration.
- [Bing Tracking](https://github.com/marcmanusch/PaulBingTracking) - Bing tracking integration.
- [Matomo](https://github.com/tinect/TinectMatomo) - Matomo/Piwik tracking integration.

## Media Adapter

- [S3](https://github.com/shopwareLabs/SwagMediaS3) - Amazon S3 Media adapter.
- [GCP](https://github.com/shopwareLabs/SwagMediaGCP) - Google Cloud Storage adapter.
- [SFTP](https://github.com/shopwareLabs/SwagMediaSftp) - SFTP adapter.
- [Azure](https://github.com/shopwareLabs/SwagMediaAzure) - Microsoft Azure adapter.
- [BunnyCDN](https://github.com/FriendsOfShopware/FroshBunnycdnMediaStorage) - BunnyCDN adapter.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
