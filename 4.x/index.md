# Documentation

Welcome to the October CMS documentation. This is where you can find information on how to use and extend October CMS, along with the definitions found in the API handbook.

## [Getting Started](setup/installation.md)

Learn how to install October CMS on your server and get up and running.

---

## Getting Started

#### [Installation](setup/installation.md)

* [Minimum System Requirements](setup/installation.md#minimum-system-requirements)
* [Installing October CMS](setup/installation.md#installing-october-cms)
* [Wizard Installation](setup/installation.md#wizard-installation)
* [Troubleshooting Installation](setup/installation.md#troubleshooting-installation)

#### [Directory Structure](setup/directory-structure.md)

* [Root Directory](setup/directory-structure.md#root-directory)
  * [App Directory](setup/directory-structure.md#app-directory)
  * [Bootstrap Directory](setup/directory-structure.md#bootstrap-directory)
  * [Config Directory](setup/directory-structure.md#config-directory)
  * [Plugins Directory](setup/directory-structure.md#plugins-directory)
  * [Storage Directory](setup/directory-structure.md#storage-directory)
  * [Modules Directory](setup/directory-structure.md#modules-directory)
  * [Themes Directory](setup/directory-structure.md#themes-directory)
  * [Vendor Directory](setup/directory-structure.md#vendor-directory)
* [App Directory](setup/directory-structure.md#app-directory-2)
  * [Assets Directory](setup/directory-structure.md#assets-directory)
  * [Blueprints Directory](setup/directory-structure.md#blueprints-directory)
  * [Others Directories](setup/directory-structure.md#others-directories)

#### [Setting Up the Scheduler](setup/scheduler.md)

* [Setting Up Queue Workers](setup/scheduler.md#setting-up-queue-workers)
* [Cron Without Command Line](setup/scheduler.md#cron-without-command-line)

#### [Deployment](setup/deployment.md)

* [Deploying with Composer](setup/deployment.md#deploying-with-composer)
* [Deploying without Composer](setup/deployment.md#deploying-without-composer)

## Configuration

#### [Common Configuration](setup/configuration.md)

* [Environment Configuration](setup/configuration.md#environment-configuration)
  * [Environment-Specific Configuration Files](setup/configuration.md#environment-specific-configuration-files)
* [Production Configuration](setup/configuration.md#production-configuration)
  * [Debug Mode](setup/configuration.md#debug-mode)
  * [CSRF protection](setup/configuration.md#csrf-protection)
  * [Public Folder](setup/configuration.md#public-folder)
  * [Setting a Fallback Theme](setup/configuration.md#setting-a-fallback-theme)
  * [Disabling the Editor](setup/configuration.md#disabling-the-editor)

#### [Web Server Configuration](setup/web-server-config.md)

* [Security & Performance](setup/web-server-config.md#security-performance)
* [Public Folder](setup/web-server-config.md#public-folder)
* [Improving Performance](setup/web-server-config.md#improving-performance)
* [Shared Hosting Security](setup/web-server-config.md#shared-hosting-security)
* [Using a Reverse Proxy](setup/web-server-config.md#using-a-reverse-proxy)
* [Safe Mode](setup/web-server-config.md#safe-mode)
* [Server-specific Configuration](setup/web-server-config.md#server-specific-configuration)

#### [Database Configuration](setup/database-config.md)

* [SQLite Configuration](setup/database-config.md#sqlite-configuration)
* [Read / Write Connections](setup/database-config.md#read-write-connections)
* [Index Lengths Using MySQL / MariaDB](setup/database-config.md#index-lengths-using-mysql-mariadb)

#### [Mail Configuration](setup/mail-config.md)

* [Driver Prerequisites](setup/mail-config.md#driver-prerequisites)
* [Mailgun driver](setup/mail-config.md#mailgun-driver)
* [Postmark Driver](setup/mail-config.md#postmark-driver)
* [SES driver](setup/mail-config.md#ses-driver)
* [Mail & Local Development](setup/mail-config.md#mail-local-development)
* [Log Driver](setup/mail-config.md#log-driver)
* [Universal To](setup/mail-config.md#universal-to)
* [Pretend Mail Mode](setup/mail-config.md#pretend-mail-mode)

#### [Errors & Logging](setup/errors-logging.md)

* [Configuration](setup/errors-logging.md#configuration)

## Resources

#### [Updating October CMS](resources/updating-october.md)

* [Database Migration](resources/updating-october.md#database-migration)
* [Bleeding Edge Updates](resources/updating-october.md#bleeding-edge-updates)
* [Upgrade Guide from v1, v2 and v3](resources/updating-october.md#upgrade-guide-from-v1-v2-and-v3)

#### [Installing Plugins & Themes](resources/installing-packages.md)

* [Project Management](resources/installing-packages.md#project-management)
  * [Synchronize Project](resources/installing-packages.md#synchronize-project)
  * [Set Project](resources/installing-packages.md#set-project)
* [Plugin Management](resources/installing-packages.md#plugin-management)
  * [Install Plugin](resources/installing-packages.md#install-plugin)
  * [Check Dependencies](resources/installing-packages.md#check-dependencies)
  * [Refresh Plugin](resources/installing-packages.md#refresh-plugin)
  * [List Plugins](resources/installing-packages.md#list-plugins)
  * [Disable Plugin](resources/installing-packages.md#disable-plugin)
  * [Enable Plugin](resources/installing-packages.md#enable-plugin)
  * [Remove Plugin](resources/installing-packages.md#remove-plugin)
* [Theme Management](resources/installing-packages.md#theme-management)
  * [Install Theme](resources/installing-packages.md#install-theme)
  * [Check Protected](resources/installing-packages.md#check-protected)
  * [List Themes](resources/installing-packages.md#list-themes)
  * [Enable Theme](resources/installing-packages.md#enable-theme)
  * [Remove Theme](resources/installing-packages.md#remove-theme)
  * [Copy Theme](resources/installing-packages.md#copy-theme)

#### [Migrating a Laravel Project](resources/migrate-laravel-project.md)

* [Install Laravel 9/10 and then October Rain](resources/migrate-laravel-project.md#install-laravel-9-10-and-then-october-rain)
* [Authenticate and Install October CMS](resources/migrate-laravel-project.md#authenticate-and-install-october-cms)
* [Replace Illuminate references with Rain Library](resources/migrate-laravel-project.md#replace-illuminate-references-with-rain-library)
  * [Update Application Container](resources/migrate-laravel-project.md#update-application-container)
  * [Update HTTP Kernel](resources/migrate-laravel-project.md#update-http-kernel)
  * [Update Console Kernel](resources/migrate-laravel-project.md#update-console-kernel)
  * [Update Exception Handler](resources/migrate-laravel-project.md#update-exception-handler)
* [Publish October CMS Files](resources/migrate-laravel-project.md#publish-october-cms-files)
* [Final Steps](resources/migrate-laravel-project.md#final-steps)
  * [Extra Steps](resources/migrate-laravel-project.md#extra-steps)

---

## [CMS Guide](cms/themes/themes.md)

Build your website using a simple file structure using themes.

### CMS

#### [Themes](cms/themes/themes.md)

* [Directory Structure](cms/themes/themes.md#directory-structure)
  * [Subdirectories](cms/themes/themes.md#subdirectories)
* [Template Structure](cms/themes/themes.md#template-structure)
  * [Configuration Section](cms/themes/themes.md#configuration-section)
  * [PHP Code Section](cms/themes/themes.md#php-code-section)
  * [Twig Markup Section](cms/themes/themes.md#twig-markup-section)
* [Theme Logging](cms/themes/themes.md#theme-logging)

#### [Pages](cms/themes/pages.md)

* [Page Configuration](cms/themes/pages.md#page-configuration)
  * [URL Syntax](cms/themes/pages.md#url-syntax)
* [Dynamic Pages](cms/themes/pages.md#dynamic-pages)
  * [Page Execution Life Cycle](cms/themes/pages.md#page-execution-life-cycle)
  * [Sending a Custom Response](cms/themes/pages.md#sending-a-custom-response)
  * [Handling Forms](cms/themes/pages.md#handling-forms)
* [404 Page](cms/themes/pages.md#_404-page)
* [Error Page](cms/themes/pages.md#error-page)
* [Setting the Page Title](cms/themes/pages.md#setting-the-page-title)
  * [Using Page Properties](cms/themes/pages.md#using-page-properties)
  * [Using Placeholder Variables](cms/themes/pages.md#using-placeholder-variables)
* [Injecting Page Assets Programmatically](cms/themes/pages.md#injecting-page-assets-programmatically)

#### [Partials](cms/themes/partials.md)

* [Rendering Partials](cms/themes/partials.md#rendering-partials)
* [Passing Variables to Partials](cms/themes/partials.md#passing-variables-to-partials)
  * [Variable Scope](cms/themes/partials.md#variable-scope)
  * [Parsing Markup as a Variable](cms/themes/partials.md#parsing-markup-as-a-variable)
* [Dynamic Partials](cms/themes/partials.md#dynamic-partials)
  * [Partial Execution Life Cycle](cms/themes/partials.md#partial-execution-life-cycle)
  * [Calling AJAX Handlers in Partials](cms/themes/partials.md#calling-ajax-handlers-in-partials)

#### [Layouts](cms/themes/layouts.md)

* [Using a Dynamic Page Title](cms/themes/layouts.md#using-a-dynamic-page-title)
* [Placeholders](cms/themes/layouts.md#placeholders)
* [Dynamic Layouts](cms/themes/layouts.md#dynamic-layouts)
  * [Layout Execution Life Cycle](cms/themes/layouts.md#layout-execution-life-cycle)
  * [Method and Variable Access](cms/themes/layouts.md#method-and-variable-access)
  * [Priority Layouts](cms/themes/layouts.md#priority-layouts)

#### [Content Blocks](cms/themes/content.md)

* [Introduction](cms/themes/content.md#introduction)
* [Rendering Content Blocks](cms/themes/content.md#rendering-content-blocks)
* [Passing Variables to Content Blocks](cms/themes/content.md#passing-variables-to-content-blocks)
  * [Global Variables](cms/themes/content.md#global-variables)

#### [Components](cms/themes/components.md)

* [Introduction](cms/themes/components.md#introduction)
* [Components Aliases](cms/themes/components.md#components-aliases)
* [Using External Property Values](cms/themes/components.md#using-external-property-values)
* [Passing Variables to Components](cms/themes/components.md#passing-variables-to-components)
* [Customizing Default Markup](cms/themes/components.md#customizing-default-markup)
  * [Moving Default Markup to a Partial](cms/themes/components.md#moving-default-markup-to-a-partial)
  * [Overriding Component Partials](cms/themes/components.md#overriding-component-partials)
* [The "View Bag" Component](cms/themes/components.md#the-view-bag-component)
  * [AJAX Handlers and Partials](cms/themes/components.md#ajax-handlers-and-partials)

#### [Snippets](cms/themes/snippets.md)

* [Creating Snippets from Partials](cms/themes/snippets.md#creating-snippets-from-partials)
  * [Defining Options](cms/themes/snippets.md#define-options)
* [Creating Snippets from Components](cms/themes/snippets.md#create-snippets-from-components)
* [Usage Examples](cms/themes/snippets.md#usage-examples)
  * [Viewing a Tailor Record](cms/themes/snippets.md#viewing-a-tailor-record)
  * [Embedding a YouTube Video](cms/themes/snippets.md#embedding-a-youtube-video)
  * [Basic Contact Form](cms/themes/snippets.md#basic-contact-form)

### Tailor

#### [Introduction](cms/tailor/introduction.md)

* [Directory Structure](cms/tailor/introduction.md#directory-structure)
  * [App Blueprints](cms/tailor/introduction.md#app-blueprints)
  * [Theme Blueprints](cms/tailor/introduction.md#theme-blueprints)
* [Blueprint Types](cms/tailor/introduction.md#blueprint-types)
* [Blueprint Structure](cms/tailor/introduction.md#blueprint-structure)
* [Integration with Multisite](cms/tailor/introduction.md#integration-with-multisite)
* [Migrating Blueprints](cms/tailor/introduction.md#migrating-blueprints)
  * [Refreshing Content](cms/tailor/introduction.md#refreshing-content)
  * [Propagating Content](cms/tailor/introduction.md#propagating-content)
  * [Pruning Content](cms/tailor/introduction.md#pruning-content)

#### [Blueprints](cms/tailor/blueprints.md)

* [Entry](cms/tailor/blueprints.md#entry)
  * [Entry Variants](cms/tailor/blueprints.md#entry-variants)
  * [Content Groups](cms/tailor/blueprints.md#content-groups)
  * [Custom Messages](cms/tailor/blueprints.md#custom-messages)
  * [Disabling Required Fields](cms/tailor/blueprints.md#disabling-required-fields)
  * [Page Finder Configuration](cms/tailor/blueprints.md#page-finder-configuration)
* [Global](cms/tailor/blueprints.md#global)
* [Mixin](cms/tailor/blueprints.md#mixin)
  * [Using the Mixin](cms/tailor/blueprints.md#using-the-mixin)

#### [Content Fields](cms/tailor/content-fields.md)

* [List and Filter Properties](cms/tailor/content-fields.md#list-and-filter-properties)
  * [Field Configuration](cms/tailor/content-fields.md#field-configuration)
  * [External Configuration](cms/tailor/content-fields.md#external-configuration)
* [Form Field Validation](cms/tailor/content-fields.md#form-field-validation)
* [Modifying Core Fields](cms/tailor/content-fields.md#modifying-core-fields)

#### [Defining Navigation](cms/tailor/navigation.md)

* [Extra Navigation](cms/tailor/navigation.md#extra-navigation)

#### [Models](cms/tailor/models.md)

* [Model Classes](cms/tailor/models.md#model-classes)
* [Entry Records](cms/tailor/models.md#entry-records)
  * [Structure Entry](cms/tailor/models.md#structure-entry)
  * [Stream Entry](cms/tailor/models.md#stream-entry)
  * [Retrieving Multiple Entries](cms/tailor/models.md#retrieving-multiple-entries)
  * [Retrieving a Single Entry](cms/tailor/models.md#retrieving-a-single-entry)
  * [Inserting & Updating Entries](cms/tailor/models.md#inserting-updating-entries)
* [Global Record](cms/tailor/models.md#global-record)
  * [Available Attributes](cms/tailor/models.md#available-attributes)
  * [Retrieving a Global Record](cms/tailor/models.md#retrieving-a-global-record)
* [Working With Related Fields](cms/tailor/models.md#working-with-related-fields)
  * [Eager Loading Relations](cms/tailor/models.md#eager-loading-relations)
  * [Creating Related Fields](cms/tailor/models.md#creating-related-fields)
* [Extending Model Constructors](cms/tailor/models.md#extending-model-constructors)
* [Extending Tailor Models](cms/tailor/models.md#extending-tailor-models)
  * [Replacing the Entire Model](cms/tailor/models.md#replacing-the-entire-model)
  * [Associating Tailor to Regular Models](cms/tailor/models.md#associating-tailor-to-regular-models)
  * [Associating Regular Models to Tailor](cms/tailor/models.md#associating-regular-models-to-tailor)
  * [Building a Custom Content Field](cms/tailor/models.md#building-a-custom-content-field)

### Available Components

#### [Section](cms/components/section.md)

* [Available Properties](cms/components/section.md#available-properties)
* [Basic Usage](cms/components/section.md#basic-usage)
* [Changing the Lookup Identifier](cms/components/section.md#changing-the-lookup-identifier)
* [Checking Record Existence](cms/components/section.md#checking-record-existence)
* [Accessing the Entry Type](cms/components/section.md#accessing-the-entry-type)
* [Using the Full Slug](cms/components/section.md#using-the-full-slug)

#### [Collection](cms/components/collection.md)

* [Available Properties](cms/components/collection.md#available-properties)
* [Basic Usage](cms/components/collection.md#basic-usage)
* [Performing Queries](cms/components/collection.md#performing-queries)
  * [Accessing the Entry Type](cms/components/collection.md#accessing-the-entry-type)
  * [Paginating Records](cms/components/collection.md#paginating-records)
  * [Searching Records](cms/components/collection.md#searching-records)
* [Eager Loading Related Records](cms/components/collection.md#eager-loading-related-records)
* [Counting Records](cms/components/collection.md#counting-records)

#### [Global](cms/components/global.md)

* [Available Properties](cms/components/global.md#available-properties)
* [Basic Usage](cms/components/global.md#basic-usage)

#### [Resources](cms/components/resources.md)

* [Available Properties](cms/components/resources.md#available-properties)
* [Basic Usage](cms/components/resources.md#basic-usage)
* [Injecting Variables](cms/components/resources.md#injecting-variables)
* [Injecting Assets](cms/components/resources.md#injecting-assets)
* [Using Custom Headers](cms/components/resources.md#using-custom-headers)

#### [Site Picker](cms/components/sitepicker.md)

* [Basic Usage](cms/components/sitepicker.md#basic-usage)
* [Loading Sites for a Different Page](cms/components/sitepicker.md#loading-sites-for-a-different-page)
* [Translating URL Parameters](cms/components/sitepicker.md#translating-url-parameters)

### Theme Development

#### [Theme Settings](cms/themes/settings.md)

* [Theme Information File](cms/themes/settings.md#theme-information-file)
* [Version File](cms/themes/settings.md#version-file)
* [Theme Preview Image](cms/themes/settings.md#theme-preview-image)
* [Theme Dependencies](cms/themes/settings.md#theme-dependencies)
* [Theme Customization](cms/themes/settings.md#theme-customization)
* [Using Theme Data in CSS](cms/themes/settings.md#using-theme-data-in-css)
* [Using Theme Data with Combined Assets](cms/themes/settings.md#using-theme-data-with-combined-assets)

#### [Localization](cms/themes/localization.md)

* [Theme Lock File](cms/themes/localization.md#theme-lock-file)
* [Creating a New Child Theme](cms/themes/localization.md#creating-a-new-child-theme)

#### [Child Themes](cms/themes/child-themes.md)

#### [Database-driven Themes](cms/themes/database-themes.md)

* [Importing from Database to Filesystem](cms/themes/database-themes.md#importing-from-database-to-filesystem)

#### [Seeding Themes](cms/themes/seeding-themes.md)

* [Seeding a Theme](cms/themes/seeding-themes.md#seeding-a-theme)
* [Directory Structure](cms/themes/seeding-themes.md#directory-structure)
* [Importing Languages](cms/themes/seeding-themes.md#importing-languages)
* [Importing Data](cms/themes/seeding-themes.md#importing-data)
  * [Tailor Blueprint Data](cms/themes/seeding-themes.md#tailor-blueprint-data)
  * [Media File Data](cms/themes/seeding-themes.md#media-file-data)
* [Importing Blueprints](cms/themes/seeding-themes.md#importing-blueprints)

### Media Manager

#### [Introduction](cms/media/introduction.md)

* [Linking to Media](cms/media/introduction.md#linking-to-media)
* [Configuration Options](cms/media/introduction.md#configuration-options)
* [Audio and Video Players](cms/media/introduction.md#audio-and-video-players)
* [Events](cms/media/introduction.md#events)

#### [Providers](cms/media/providers.md)

* [Local Disk](cms/media/providers.md#local-disk)
* [Configuring Amazon S3 access](cms/media/providers.md#configuring-amazon-s3-access)
* [Troubleshooting](cms/media/providers.md#troubleshooting)

### Resources

#### [Multisite](cms/resources/multisite.md)

* [Managing Sites](cms/resources/multisite.md#managing-sites)
* [Site Picker Component](cms/resources/multisite.md#site-picker-component)
* [Browser Language Detection](cms/resources/multisite.md#browser-language-detection)
* [Site Groups](cms/resources/multisite.md#site-groups)
* [Role Restrictions](cms/resources/multisite.md#role-restrictions)
* [Multisite Features](cms/resources/multisite.md#multisite-features)
  * [Disabling Multisite](cms/resources/multisite.md#disabling-multisite)
* [PHP Interface](cms/resources/multisite.md#php-interface)

#### [Building API Endpoints](cms/resources/building-apis.md)

* [Sending a Response](cms/resources/building-apis.md#sending-a-response)
  * [Collections](cms/resources/building-apis.md#collections)
* [Conditions](cms/resources/building-apis.md#conditions)
  * [Checking the HTTP Method](cms/resources/building-apis.md#checking-the-http-method)
  * [Aborting the Request](cms/resources/building-apis.md#aborting-the-request)
* [Working with Pages and Layouts](cms/resources/building-apis.md#working-with-pages-and-layouts)
  *   [Using Layouts as Middleware](#using-layouts-as-middleware)
  * [Calling AJAX Handlers](cms/resources/building-apis.md#calling-ajax-handlers)
* [Working with Resources](cms/resources/building-apis.md#working-with-resources)
  * [Models & Collections](cms/resources/building-apis.md#models-collections)
  * [Pagination](cms/resources/building-apis.md#pagination)
* [Usage Examples](cms/resources/building-apis.md#usage-examples)
  * [Returning Users with Avatar Thumbnails](cms/resources/building-apis.md#returning-users-with-avatar-thumbnails)

---

## [AJAX Framework](cms/ajax/introduction.md)

Learn more about the the AJAX framework used by October CMS.

### AJAX

#### [Introduction](cms/ajax/introduction.md)

* [Including the Framework](cms/ajax/introduction.md#including-the-framework)
* [Extra Features](cms/ajax/introduction.md#extra-features)
* [How AJAX Requests Work](cms/ajax/introduction.md#how-ajax-requests-work)
* [Usage Example](cms/ajax/introduction.md#usage-example)

#### [Event Handlers](cms/ajax/handlers.md)

* [AJAX Handlers](cms/ajax/handlers.md#ajax-handlers)
  * [Calling a Handler](cms/ajax/handlers.md#calling-a-handler)
  * [Form Serialization](cms/ajax/handlers.md#form-serialization)
  * [Generic Handler](cms/ajax/handlers.md#generic-handler)
  * [Component Handlers](cms/ajax/handlers.md#component-handlers)
* [Redirects in AJAX Handlers](cms/ajax/handlers.md#redirects-in-ajax-handlers)
* [Returning Data from AJAX Handlers](cms/ajax/handlers.md#returning-data-from-ajax-handlers)
* [Running Code Before Handlers](cms/ajax/handlers.md#running-code-before-handlers)
* [Throwing an AJAX Exception](cms/ajax/handlers.md#throwing-an-ajax-exception)
* [Dispatching Browser Events](cms/ajax/handlers.md#dispatching-browser-events)

#### [Updating Partials](cms/ajax/update-partials.md)

* [Pulling Partial Updates](cms/ajax/update-partials.md#pulling-partial-updates)
  * [Self-Updating Partials](cms/ajax/update-partials.md#self-updating-partials)
  * [Global Partial Updates](cms/ajax/update-partials.md#global-partial-updates)
* [Update Definition](cms/ajax/update-partials.md#update-definition)
  * [Appending and Prepending Content](cms/ajax/update-partials.md#appending-and-prepending-content)
  * [Using Custom HTML Selectors](cms/ajax/update-partials.md#using-custom-html-selectors)
* [Pushing Partial Updates](cms/ajax/update-partials.md#pushing-partial-updates)
* [Passing Variables to Partials](cms/ajax/update-partials.md#passing-variables-to-partials)

#### [Data Attributes API](cms/ajax/attributes-api.md)

* [Usage Examples](cms/ajax/attributes-api.md#usage-examples)

#### [JavaScript API](cms/ajax/javascript-api.md)

* [Usage Examples](cms/ajax/javascript-api.md#usage-examples)
* [Global AJAX Events](cms/ajax/javascript-api.md#global-ajax-events)
* [Usage Examples](cms/ajax/javascript-api.md#usage-examples-2)

#### [Turbo Router](cms/ajax/turbo-router.md)

* [Routing Links](cms/ajax/turbo-router.md#routing-links)
* [Disable Routing](cms/ajax/turbo-router.md#disable-routing)
* [Disable for Specific Links](cms/ajax/turbo-router.md#disable-for-specific-links)
* [Disable Visit Scrolling](cms/ajax/turbo-router.md#disable-visit-scrolling)
* [Persisting Page Elements](cms/ajax/turbo-router.md#persisting-page-elements)
* [Setting a Root Path](cms/ajax/turbo-router.md#setting-a-root-path)
* [Native Error Pages](cms/ajax/turbo-router.md#native-error-pages)
* [Page Caching](cms/ajax/turbo-router.md#page-caching)
  * [Listening for the Cache Event](cms/ajax/turbo-router.md#listening-for-the-cache-event)
  * [Detecting a Cached Page Load](cms/ajax/turbo-router.md#detecting-a-cached-page-load)
  * [Disabling the Cache](cms/ajax/turbo-router.md#disabling-the-cache)
* [Working with JavaScript](cms/ajax/turbo-router.md#working-with-javascript)
  * [Inline Script Elements](cms/ajax/turbo-router.md#inline-script-elements)
  * [Making Controls Idempotent](cms/ajax/turbo-router.md#making-controls-idempotent)
  * [Disposing Controls](cms/ajax/turbo-router.md#disposing-controls)
  * [Pause Rendering](cms/ajax/turbo-router.md#pause-rendering)
* [Global Events](cms/ajax/turbo-router.md#global-events)
* [Usage Examples](cms/ajax/turbo-router.md#usage-examples)
* [Working with Hot Reloading](cms/ajax/turbo-router.md#working-with-hot-reloading)

#### [Hot Controls](cms/ajax/hot-controls.md)

* [Registering an Observable Control](cms/ajax/hot-controls.md#registering-an-observable-control)
* [Initializing a Control](cms/ajax/hot-controls.md#initializing-a-control)
  * [Configuration](cms/ajax/hot-controls.md#configuration)
  * [Child Elements](cms/ajax/hot-controls.md#child-elements)
* [Referencing Other Controls](cms/ajax/hot-controls.md#referencing-other-controls)
* [Working with Events](cms/ajax/hot-controls.md#working-with-events)
  * [Local Events](cms/ajax/hot-controls.md#local-events)
  * [Global Events](cms/ajax/hot-controls.md#global-events)
  * [Dispatching Events](cms/ajax/hot-controls.md#dispatching-events)
* [Usage Examples](cms/ajax/hot-controls.md#usage-examples)
  * [Vanilla JS Example](cms/ajax/hot-controls.md#vanilla-js-example)
  * [Google Maps Example](cms/ajax/hot-controls.md#google-maps-example)
  * [Vue.js Example](cms/ajax/hot-controls.md#vue-js-example)

### Features

#### [Validation](cms/features/validation.md)

* [Flash Validation](cms/features/validation.md#flash-validation)
* [Inline Validation](cms/features/validation.md#inline-validation)
  * [Validating a Single Field](cms/features/validation.md#validating-a-single-field)
* [Using the Validation Service](cms/features/validation.md#using-the-validation-service)
  * [Custom Error Messages & Attributes](cms/features/validation.md#custom-error-messages-attributes)
* [Displaying Error Messages](cms/features/validation.md#displaying-error-messages)
  * [Displaying Errors with Fields](cms/features/validation.md#displaying-errors-with-fields)
  * [Displaying Errors with Flash Messages](cms/features/validation.md#displaying-errors-with-flash-messages)
* [Working with JavaScript](cms/features/validation.md#working-with-javascript)
* [Complete Usage Example](cms/features/validation.md#complete-usage-example)

#### [File Uploads](cms/features/uploads.md)

* [Uploading Files](cms/features/uploads.md#uploading-files)
  * [Uploading Multiple Files](cms/features/uploads.md#uploading-multiple-files)
  * [Validating File Uploads](cms/features/uploads.md#validating-file-uploads)
* [Uploading to Models](cms/features/uploads.md#uploading-to-models)

#### [File Downloads](cms/features/downloads.md)

* [Download Buttons](cms/features/downloads.md#download-buttons)
* [Download Responses](cms/features/downloads.md#download-responses)
* [Usage Example](cms/features/downloads.md#usage-example)

#### [Loading Indicators](cms/features/loaders.md)

* [Progress Bar](cms/features/loaders.md#progress-bar)
* [Loading Button](cms/features/loaders.md#loading-button)
* [Toggling Elements](cms/features/loaders.md#toggling-elements)
  * [Detecting Global Requests](cms/features/loaders.md#detecting-global-requests)
  * [Targeting Specific Handlers](cms/features/loaders.md#targeting-specific-handlers)
* [Working with JavaScript](cms/features/loaders.md#working-with-javascript)

#### [Flash Messages](cms/features/flash-messages.md)

* [Built-in Flash Messages](cms/features/flash-messages.md#built-in-flash-messages)
  * [Loading Flash Message](cms/features/flash-messages.md#loading-flash-message)
  * [Styling the Flash Message](cms/features/flash-messages.md#styling-the-flash-message)
* [Custom Flash Messages](cms/features/flash-messages.md#custom-flash-messages)
* [Working with JavaScript](cms/features/flash-messages.md#working-with-javascript)

#### [Pagination](cms/features/pagination.md)

* [Paginating Data](cms/features/pagination.md#paginating-data)
  * [Multiple Pagination Instances](cms/features/pagination.md#multiple-pagination-instances)
  * [Using Custom Pagination Markup](cms/features/pagination.md#using-custom-pagination-markup)
* [AJAX Pagination](cms/features/pagination.md#ajax-pagination)
* [Load More Pagination](cms/features/pagination.md#load-more-pagination)

#### [Redirects](cms/features/redirects.md)

* [Redirecting to a CMS Page](cms/features/redirects.md#redirecting-to-a-cms-page)
* [Redirects in Twig](cms/features/redirects.md#redirects-in-twig)
* [Redirects in AJAX](cms/features/redirects.md#redirects-in-ajax)

#### [Polling](cms/features/polling.md)

* [Lazy Loading Requests](cms/features/polling.md#lazy-loading-requests)
* [Polling Requests](cms/features/polling.md#polling-requests)
* [Lazy Loading Partials](cms/features/polling.md#lazy-loading-partials)

#### [Modals](cms/features/modals.md)

* [Modal Content](cms/features/modals.md#modal-content)
* [Modal Trigger](cms/features/modals.md#modal-trigger)
* [Modal Container](cms/features/modals.md#modal-container)

---

## [Markup Guide](markup/templating.md)

Reference guide for the Twig template syntax for displaying content.

### Markup

#### [Templating](markup/templating.md)

* [Variables](markup/templating.md#variables)
* [Tags](markup/templating.md#tags)
* [Filters](markup/templating.md#filters)
* [Functions](markup/templating.md#functions)
* [Access logic](markup/templating.md#access-logic)
* [Unsupported features](markup/templating.md#unsupported-features)

### Properties

#### [this.page](markup/property/this-page.md)

* [Properties](markup/property/this-page.md#properties)
  * [layout](markup/property/this-page.md#layout)
  * [id](markup/property/this-page.md#id)
  * [title](markup/property/this-page.md#title)
  * [description](markup/property/this-page.md#description)
  * [meta_title](markup/property/this-page.md#meta-title)
  * [meta_description](markup/property/this-page.md#meta-description)
  * [hidden](markup/property/this-page.md#hidden)
  * [fileName](markup/property/this-page.md#filename)
  * [baseFileName](markup/property/this-page.md#basefilename)

#### [this.layout](markup/property/this-layout.md)

* [Properties](markup/property/this-layout.md#properties)
  * [id](markup/property/this-layout.md#id)
  * [description](markup/property/this-layout.md#description)

#### [this.theme](markup/property/this-theme.md)

* [Properties](markup/property/this-theme.md#properties)
  * [id](markup/property/this-theme.md#id)
  * [config](markup/property/this-theme.md#config)

#### [this.param](markup/property/this-param.md)

* [Accessing Page Parameters](markup/property/this-param.md#accessing-page-parameters)

#### [this.controller](markup/property/this-controller.md)

#### [this.environment](markup/property/this-environment.md)

* [Example](markup/property/this-environment.md#example)

#### [this.session](markup/property/this-session.md)

* [this.session.get()](markup/property/this-session.md#this-session-get)
* [this.session.has()](markup/property/this-session.md#this-session-has)
* [this.session.put()](markup/property/this-session.md#this-session-put)
* [this.session.forget()](markup/property/this-session.md#this-session-forget)

#### [this.request](markup/property/this-request.md)

* [this.request.method](markup/property/this-request.md#this-request-method)
* [this.request.ajax](markup/property/this-request.md#this-request-ajax)
* [this.request.pjax](markup/property/this-request.md#this-request-pjax)
* [this.request.pjaxCached](markup/property/this-request.md#this-request-pjaxcached)

#### [this.site](markup/property/this-site.md)

* [Retrieving Data From the Site](markup/property/this-site.md#retrieving-data-from-the-site)
* [Checking the Active Site](markup/property/this-site.md#checking-the-active-site)
* [Getting the Current Selected Locale](markup/property/this-site.md#getting-the-current-selected-locale)

### Tags

#### [{% page %}](markup/tag/page.md)

#### [{% partial %}](markup/tag/partial.md)

* [Variables](markup/tag/partial.md#variables)
* [Passing Markup as a Variable](markup/tag/partial.md#passing-markup-as-a-variable)
  * [Composable Partials](markup/tag/partial.md#composable-partials)
* [Setting Partial Contents to a Twig Variable](markup/tag/partial.md#setting-partial-contents-to-a-twig-variable)
* [Checking a Partial Exists](markup/tag/partial.md#checking-a-partial-exists)

#### [{% ajaxPartial %}](markup/tag/ajax-partial.md)

* [Short Update Syntax](markup/tag/ajax-partial.md#short-update-syntax)
* [Lazy Loading Partials](markup/tag/ajax-partial.md#lazy-loading-partials)
* [Calling AJAX Handlers](markup/tag/ajax-partial.md#calling-ajax-handlers)
  * [Capture Lifecycle](markup/tag/ajax-partial.md#capture-lifecycle)

#### [{% content %}](markup/tag/content.md)

* [Variables](markup/tag/content.md#variables)
* [Setting Contents to a Twig Variable](markup/tag/content.md#setting-contents-to-a-twig-variable)
* [Checking a Content File Exists](markup/tag/content.md#checking-a-content-file-exists)
* [Parsing Content as a String](markup/tag/content.md#parsing-content-as-a-string)

#### [{% component %}](markup/tag/component.md)

* [Variables](markup/tag/component.md#variables)
* [Customizing Components](markup/tag/component.md#customizing-components)

#### [{% placeholder %}](markup/tag/placeholder.md)

* [Replacing Content](markup/tag/placeholder.md#replacing-content)
* [Handling Multiple Calls](markup/tag/placeholder.md#handling-multiple-calls)
* [Default Placeholder Content](markup/tag/placeholder.md#default-placeholder-content)
* [Checking a Placeholder Exists](markup/tag/placeholder.md#checking-a-placeholder-exists)
* [Using Placeholders as Variables](markup/tag/placeholder.md#using-placeholders-as-variables)
* [System Placeholders](markup/tag/placeholder.md#system-placeholders)
  * [{% scripts %}](markup/tag/placeholder.md#scripts)
  * [{% styles %}](markup/tag/placeholder.md#styles)
  * [{% meta %}](markup/tag/placeholder.md#meta)
* [Custom Attributes](markup/tag/placeholder.md#custom-attributes)

#### [{% flash %}](markup/tag/flash.md)

* [Setting Flash Messages to a Twig Variable](markup/tag/flash.md#setting-flash-messages-to-a-twig-variable)

#### [{% verbatim %}](markup/tag/verbatim.md)

#### [{% macro %}](markup/tag/macro.md)

* [Calling Macros](markup/tag/macro.md#calling-macros)
* [Nested Macros](markup/tag/macro.md#nested-macros)
* [Context Variable](markup/tag/macro.md#context-variable)

#### [{% for %}](markup/tag/for.md)

* [Looping a Collection](markup/tag/for.md#looping-a-collection)
* [Adding a Condition](markup/tag/for.md#adding-a-condition)
* [The Loop Variable](markup/tag/for.md#the-loop-variable)

#### [{% if %}](markup/tag/if.md)

* [Expression Rules](markup/tag/if.md#expression-rules)

### Filters

#### [|app](markup/filter/app.md)

#### [|page](markup/filter/page.md)

* [Reverse Routing](markup/filter/page.md#reverse-routing)
* [Persistent URL Parameters](markup/filter/page.md#persistent-url-parameters)

#### [|link](markup/filter/link.md)

* [link()](markup/filter/link.md#link)
* [PHP Interface](markup/filter/link.md#php-interface)

#### [|theme](markup/filter/theme.md)

* [Combining CSS and JavaScript](markup/filter/theme.md#combining-css-and-javascript)
  * [Combiner Aliases](markup/filter/theme.md#combiner-aliases)
  * [External Combiner Paths](markup/filter/theme.md#external-combiner-paths)

#### [|trans](markup/filter/trans.md)

* [Pluralization](markup/filter/trans.md#pluralization)
* [Shorter Syntax](markup/filter/trans.md#shorter-syntax)

#### [|media](markup/filter/media.md)

* [PHP Interface](markup/filter/media.md#php-interface)

#### [|resize](markup/filter/resize.md)

* [Custom Filenames](markup/filter/resize.md#custom-filenames)
* [Custom Folder Names](markup/filter/resize.md#custom-folder-names)
* [Available Sources](markup/filter/resize.md#available-sources)
* [PHP Interface](markup/filter/resize.md#php-interface)

#### [|default](markup/filter/default.md)

#### [|raw](markup/filter/raw.md)

#### [|md](markup/filter/md.md)

* [|md_safe](markup/filter/md.md#md-safe)
* [|md_clean](markup/filter/md.md#md-clean)

#### [|currency](markup/filter/currency.md)

* [PHP Interface](markup/filter/currency.md#php-interface)

### Functions

#### [ajaxHandler()](markup/function/ajax-handler.md)

* [Accessing Data](markup/function/ajax-handler.md#accessing-data)
* [Using Responses](markup/function/ajax-handler.md#using-responses)
* [Handling Errors](markup/function/ajax-handler.md#handling-errors)
* [Handling Redirects](markup/function/ajax-handler.md#handling-redirects)
* [Handling Flash Messages](markup/function/ajax-handler.md#handling-flash-messages)

#### [response()](markup/function/response.md)

#### [redirect()](markup/function/redirect.md)

#### [collect()](markup/function/collect.md)

* [shuffle](markup/function/collect.md#shuffle)
* [sortBy](markup/function/collect.md#sortby)

#### [config()](markup/function/config.md)

* [env()](markup/function/config.md#env)

#### [carbon()](markup/function/carbon.md)

* [format](markup/function/carbon.md#format)
* [isoFormat](markup/function/carbon.md#isoformat)
* [diffForHumans](markup/function/carbon.md#diffforhumans)
* [Cache Busting URLs](markup/function/carbon.md#cache-busting-urls)
* [Date Format Cheat Sheet](markup/function/carbon.md#date-format-cheat-sheet)

#### [pager()](markup/function/pager.md)

* [Modifying the URL](/4.x/markup/function/pager.html#modifying-the-url)
* [Accessing Pager Variables](markup/function/pager.md#accessing-pager-variables)
* [Rendering the Pager](markup/function/pager.md#rendering-the-pager)
  * [Default Template](markup/function/pager.md#default-template)
  * [Simple Template](markup/function/pager.md#simple-template)
  * [AJAX Template](markup/function/pager.md#ajax-template)
* [Using Custom Markup](markup/function/pager.md#using-custom-markup)

#### [abort()](markup/function/abort.md)

#### [dump()](markup/function/dump.md)

* [d()](markup/function/dump.md#d)

#### [str()](markup/function/str.md)

* [str_limit()](markup/function/str.md#str-limit)
* [str_words()](markup/function/str.md#str-words)
* [str_replace](markup/function/str.md#str-replace)
* [str_camel()](markup/function/str.md#str-camel)
* [str_studly()](markup/function/str.md#str-studly)
* [str_snake()](markup/function/str.md#str-snake)
* [str_plural()](markup/function/str.md#str-plural)
* [str_upper()](markup/function/str.md#str-upper)
* [str_lower()](markup/function/str.md#str-lower)
* [str_ucfirst()](markup/function/str.md#str-ucfirst)
* [str_lcfirst()](markup/function/str.md#str-lcfirst)
* [str_repeat()](markup/function/str.md#str-repeat)
* [str_pad_both()](markup/function/str.md#str-pad-both)
* [str_pad_left()](markup/function/str.md#str-pad-left)
* [str_pad_right()](markup/function/str.md#str-pad-right)
* [str_reverse()](markup/function/str.md#str-reverse)

#### [form()](markup/function/form.md)

* [form_open()](markup/function/form.md#form-open)
* [form_ajax()](markup/function/form.md#form-ajax)
* [form_close()](markup/function/form.md#form-close)
* [Passing Attributes to the Generated Element](markup/function/form.md#passing-attributes-to-the-generated-element)

#### [html()](markup/function/html.md)

* [html_strip()](markup/function/html.md#html-strip)
* [html_limit()](markup/function/html.md#html-limit)
* [html_clean()](markup/function/html.md#html-clean)
* [html_email()](markup/function/html.md#html-email)
* [html_mailto()](markup/function/html.md#html-mailto)

---

## [Extending October CMS](extend/system/plugins.md)

Plugins are foundation for adding new features to the CMS by extending it.

### System Design

#### [Plugins](extend/system/plugins.md)

* [Registration File](extend/system/plugins.md#registration-file)
  * [Basic Plugin Information](extend/system/plugins.md#basic-plugin-information)
* [Booting and Initialization](extend/system/plugins.md#booting-and-initialization)
* [Dependency Definitions](extend/system/plugins.md#dependency-definitions)
* [Version History](extend/system/plugins.md#version-history)
  * [Plugin Dependencies](extend/system/plugins.md#plugin-dependencies)
* [Plugin Version File](extend/system/plugins.md#plugin-version-file
  * [Important Updates](extend/system/plugins.md#important-updates)
  * [Migration and Seed Files](extend/system/plugins.md#migration-and-seed-files)

#### [Models](extend/system/models.md)

* [Defining Models](extend/system/models.md#defining-models)
  * [Supported Properties](extend/system/models.md#supported-properties)
* [Model Events](extend/system/models.md#model-events)
  * [Basic Usage](extend/system/models.md#basic-usage)
* [Extending Models](extend/system/models.md#extending-models)

#### [Controllers](extend/system/controllers.md)

* [Initialization Logic](extend/system/controllers.md#initialization-logic)
* [Actions, Views and Routing](extend/system/controllers.md#actions-views-and-routing)
* [Passing Data to Views](extend/system/controllers.md#passing-data-to-views)
* [Setting the Navigation Context](extend/system/controllers.md#setting-the-navigation-context)
* [Overriding a Response](extend/system/controllers.md#overriding-a-response)

#### [Rendering Views](extend/system/views.md)

* [Partials](extend/system/views.md#partials)
  * [Hint Partials](extend/system/views.md#hint-partials)
  * [Checking if Hints are Hidden](extend/system/views.md#checking-if-hints-are-hidden)
* [Layouts and Child Layouts](extend/system/views.md#layouts-and-child-layouts)
  * [Form with Sidebar](extend/system/views.md#form-with-sidebar)
* [Extending the Layout](extend/system/views.md#extending-the-layout)

#### [Behaviors](extend/system/behaviors.md)

* [Comparison to Traits](extend/system/behaviors.md#comparison-to-traits)
* [Extending Constructors](extend/system/behaviors.md#extending-constructors)
  * [Soft Definition](extend/system/behaviors.md#soft-definition)
* [Dynamically Implementing a Behavior](extend/system/behaviors.md#dynamically-implementing-a-behavior)
* [Dynamically Creating Methods](extend/system/behaviors.md#dynamically-creating-methods)
  * [Checking the Existence of a Method](extend/system/behaviors.md#checking-the-existence-of-a-method)
  * [List All Available Methods](extend/system/behaviors.md#list-all-available-methods)
* [Usage Example](extend/system/behaviors.md#usage-example)
  * [Behavior / Extension class](extend/system/behaviors.md#behavior-extension-class)
  * [Extending a Class](extend/system/behaviors.md#extending-a-class)
  * [Using the Extension](extend/system/behaviors.md#using-the-extension)

#### [Widgets](extend/system/widgets.md)

* [Generic Widgets](extend/system/widgets.md#generic-widgets)
  * [Class Definition](extend/system/widgets.md#class-definition)
* [Binding Widgets to Controllers](extend/system/widgets.md#binding-widgets-to-controllers)
* [Running Code Before AJAX Handlers](extend/system/widgets.md#running-code-before-ajax-handlers)

#### [AJAX](extend/system/ajax.md)

* [Backend AJAX Handlers](extend/system/ajax.md#backend-ajax-handlers)
* [Triggering AJAX Requests](extend/system/ajax.md#triggering-ajax-requests)
* [Behavior AJAX Handlers](extend/system/ajax.md#behavior-ajax-handlers)
* [Widget AJAX Handlers](extend/system/ajax.md#widget-ajax-handlers)

### Core Concepts

#### [Available Exceptions](extend/system/exceptions.md)

* [Exception Handling](extend/system/exceptions.md#exception-handling)
* [Where to Place Error Handlers](extend/system/exceptions.md#where-to-place-error-handlers)
* [HTTP Exceptions](extend/system/exceptions.md#http-exceptions)
* [Custom Error Page](extend/system/exceptions.md#custom-error-page)

#### [Sending Mail](extend/system/sending-mail.md)

* [Message Content](extend/system/sending-mail.md#message-content)
  * [Defining Templates in the Backend Panel](extend/system/sending-mail.md#defining-templates-in-the-backend-panel)
  * [Defining Layouts in the Backend Panel](extend/system/sending-mail.md#defining-layouts-in-the-backend-panel)
  * [Defining Views in the Filesystem](extend/system/sending-mail.md#defining-views-in-the-filesystem)
  * [Registering Templates, Layouts & Partials](extend/system/sending-mail.md#registering-templates-layouts-partials)
  * [Global Variables](extend/system/sending-mail.md#global-variables)
* [Sending Mail](extend/system/sending-mail.md#sending-mail)
  * [Quick Sending](extend/system/sending-mail.md#quick-sending)
  * [Building the Message](extend/system/sending-mail.md#building-the-message)
  * [Sending Attachments](extend/system/sending-mail.md#sending-attachments)
  * [Inline Attachments](extend/system/sending-mail.md#inline-attachments)
* [Queueing Mail](extend/system/sending-mail.md#queueing-mail)
  * [Queueing a Mail Message](extend/system/sending-mail.md#queueing-a-mail-message)
  * [Delayed Message Queueing](extend/system/sending-mail.md#delayed-message-queueing)
  * [Pushing to Specific Queues](extend/system/sending-mail.md#pushing-to-specific-queues)

#### [Localization](extend/system/localization.md)

* [Active Language](extend/system/localization.md#active-language)
* [Localization File Structure](extend/system/localization.md#localization-file-structure)
* [Accessing Localization Strings](extend/system/localization.md#accessing-localization-strings)
  * [Pluralized Values](extend/system/localization.md#pluralized-values)
* [Overriding Localization Strings](extend/system/localization.md#overriding-localization-strings)
  * [Programatically Overriding Strings](extend/system/localization.md#programatically-overriding-strings)
* [Contributing Language Strings](extend/system/localization.md#contributing-language-strings)
  * [Using Crowdin](extend/system/localization.md#using-crowdin)
  * [Using GitHub](extend/system/localization.md#using-github)

#### [Routing & Middleware](extend/system/routing.md)

* [Basic Routing](extend/system/routing.md#basic-routing)
  * [Registering Multiple Methods](extend/system/routing.md#registering-multiple-methods)
* [Routing to a Class](extend/system/routing.md#routing-to-a-class)
* [Route Parameters](extend/system/routing.md#route-parameters)
  * [Optional Parameters](extend/system/routing.md#optional-parameters)
  * [Regular Expression Constraints](extend/system/routing.md#regular-expression-constraints)
* [Named Routes](extend/system/routing.md#named-routes)
* [Route Groups](extend/system/routing.md#route-groups)
  * [Sub-domain Routing](extend/system/routing.md#sub-domain-routing)
  * [Route Prefixes](extend/system/routing.md#route-prefixes)
  * [Route Middleware](extend/system/routing.md#route-middleware)
* [Global Middleware](extend/system/routing.md#global-middleware)
* [Throwing 404 Errors](extend/system/routing.md#throwing-404-errors)

#### [Task Scheduling](extend/system/scheduling.md)

* [Defining Schedules](extend/system/scheduling.md#defining-schedules)
  * [Schedule Frequency Options](extend/system/scheduling.md#schedule-frequency-options)
  * [Preventing Task Overlaps](extend/system/scheduling.md#preventing-task-overlaps)
* [Task Output](extend/system/scheduling.md#task-output)
* [Task Hooks](extend/system/scheduling.md#task-hooks)

#### [Unit Testing](extend/system/unit-testing.md)

* [Creating Plugin Tests](extend/system/unit-testing.md#creating-plugin-tests)
* [Creating a Test Class](extend/system/unit-testing.md#creating-a-test-class)
* [Registering and Booting Plugins](extend/system/unit-testing.md#registering-and-booting-plugins)
* [Working with the Database](extend/system/unit-testing.md#working-with-the-database)
  * [Changing the Database](extend/system/unit-testing.md#changing-the-database)

### Extending the CMS

#### [Extension Methodology](extend/extending.md)

* [Extending by Plugin Registration](extend/extending.md#extending-by-plugin-registration)
* [Extending with Events](extend/extending.md#extending-with-events)
  * [Subscribing to Events](extend/extending.md#subscribing-to-events)
  * [Declaring / Firing Events](extend/extending.md#declaring-firing-events)
* [Extending Backend Views](extend/extending.md#extending-backend-views)
* [Usage Examples](extend/extending.md#usage-examples)
  * [Extending a User Model](extend/extending.md#extending-a-user-model)
  * [Extending Backend Forms](extend/extending.md#extending-backend-forms)
  * [Extending a Backend List](extend/extending.md#extending-a-backend-list)
  * [Extending a Component](extend/extending.md#extending-a-component)

#### [Building Twig Tags](extend/twig-tags.md)

* [Registering a Filter](extend/twig-tags.md#registering-a-filter)
* [Registering a Function](extend/twig-tags.md#registering-a-function)
* [Escaped Output](extend/twig-tags.md#escaped-output)
* [Advanced Options](extend/twig-tags.md#advanced-options)

#### [Building Tailor Fields](extend/tailor-fields.md)

* [Processing Config](extend/tailor-fields.md#processing-config)
* [Defining the Backend Element](extend/tailor-fields.md#defining-the-backend-element)
  * [Form Field](extend/tailor-fields.md#form-field)
  * [List Column](extend/tailor-fields.md#list-column)
  * [Filter Scope](extend/tailor-fields.md#filter-scope)
* [Extending the Model](extend/tailor-fields.md#extending-the-model)
* [Extending the Database Table](extend/tailor-fields.md#extending-the-database-table)
* [Complete Usage Example](extend/tailor-fields.md#complete-usage-example)
* [Form Widgets vs. Content Fields](extend/tailor-fields.md#form-widgets-vs-content-fields)

#### [Building CMS Components](extend/cms-components.md)

* [Component Class Definition](extend/cms-components.md#component-class-definition)
  * [Component Registration](extend/cms-components.md#component-registration)
* [Component Properties](extend/cms-components.md#component-properties)
* [Routing Parameters](extend/cms-components.md#routing-parameters)
* [Handling the Page Execution Cycle](extend/cms-components.md#handling-the-page-execution-cycle)
  * [Page Execution Life Cycle Handlers](extend/cms-components.md#page-execution-life-cycle-handlers)
  * [Component Initialization](extend/cms-components.md#component-initialization)
  * [Halting With a Response](extend/cms-components.md#halting-with-a-response)
* [AJAX Handlers](extend/cms-components.md#ajax-handlers)
* [Default Markup](extend/cms-components.md#default-markup)
* [Component Partials](extend/cms-components.md#component-partials)
  * [Referencing "self"](extend/cms-components.md#referencing-self)
  * [Unique Identifier](extend/cms-components.md#unique-identifier)
* [Rendering Partials from Code](extend/cms-components.md#rendering-partials-from-code)
* [Injecting Page Assets with Components](extend/cms-components.md#injecting-page-assets-with-components)

#### [Building Console Commands](extend/console-commands.md)

* [Building a Command](extend/console-commands.md#building-a-command)
  * [Defining Arguments](extend/console-commands.md#define-arguments)
  * [Defining Options](extend/console-commands.md#define-options)
  * [Retrieving Input](extend/console-commands.md#retrieving-input)
  * [Writing Output](extend/console-commands.md#writing-output)
* [Registering Commands](extend/console-commands.md#registering-commands)
* [Calling Other Commands](extend/console-commands.md#calling-other-commands)

### Backend Panel

#### [Navigation](extend/backend/navigation.md)

* [Navigation Counters](extend/backend/navigation.md#navigation-counters)
* [Item Display Types](extend/backend/navigation.md#item-display-types)
* [Extending the Backend Menu](extend/backend/navigation.md#extending-the-backend-menu)

#### [Users](extend/backend/users.md)

* [Backend User Helper](extend/backend/users.md#backend-user-helper)
* [Groups](extend/backend/users.md#groups)
* [Change Backend User Password](extend/backend/users.md#change-backend-user-password)

#### [Permissions](extend/backend/permissions.md)

* [Permission Codes](extend/backend/permissions.md#permission-codes)
* [Nested Permissions](extend/backend/permissions.md#nested-permissions)
* [Access Levels](extend/backend/permissions.md#access-levels)
* [Super Users](extend/backend/permissions.md#super-users)
* [Roles](extend/backend/permissions.md#roles)
* [Role Hierarchy](extend/backend/permissions.md#role-hierarchy)
* [Registering Permissions](extend/backend/permissions.md#registering-permissions)
* [Restricting Access to Backend Pages](extend/backend/permissions.md#restricting-access-to-backend-pages)
* [Restricting Access to Features](extend/backend/permissions.md#restricting-access-to-features)

### Form Design

#### [Form Controller](extend/forms/form-controller.md)

* [Configuring the Form Behavior](extend/forms/form-controller.md#configuring-the-form-behavior)
  * [Create Page](extend/forms/form-controller.md#create-page)
  * [Update Page](extend/forms/form-controller.md#update-page)
  * [Preview Page](extend/forms/form-controller.md#preview-page)
  * [Custom Messages](extend/forms/form-controller.md#custom-messages)
  * [Restricting with Permissions](extend/forms/form-controller.md#restricting-with-permissions)
  * [Defining Form Fields](extend/forms/form-controller.md#defining-form-fields)
* [Form Views](extend/forms/form-controller.md#form-views)
  * [Create View](extend/forms/form-controller.md#create-view)
  * [Update View](extend/forms/form-controller.md#update-view)
  * [Preview View](extend/forms/form-controller.md#preview-view)
* [Form Designs](extend/forms/form-controller.md#form-designs)
  * [Display Modes](extend/forms/form-controller.md#display-modes)
  * [Popup Display Mode](extend/forms/form-controller.md#popup-display-mode)
* [Extending Form Behavior](extend/forms/form-controller.md#extending-form-behavior)
  * [Extending the Form Configuration](extend/forms/form-controller.md#extending-the-form-configuration)
  * [Overriding Controller Action](extend/forms/form-controller.md#overriding-controller-action)
  * [Overriding Form Save Data](extend/forms/form-controller.md#overriding-form-save-data)
  * [Overriding Controller Redirect](extend/forms/form-controller.md#overriding-controller-redirect)
  * [Extending Form Model Query](extend/forms/form-controller.md#extending-form-model-query)
  * [Extending Form Fields](extend/forms/form-controller.md#extending-form-fields)
  * [Filtering Form Fields](extend/forms/form-controller.md#filtering-form-fields)
* [Validating Form Fields](extend/forms/form-controller.md#validating-form-fields)

#### [Relation Controller](extend/forms/relation-controller.md)

* [Configuring the Relation Behavior](extend/forms/relation-controller.md#configuring-the-relation-behavior)
  * [Custom Messages](extend/forms/relation-controller.md#custom-messages)
  * [Nested Definitions](extend/forms/relation-controller.md#nested-definitions)
* [Relationship Types](extend/forms/relation-controller.md#relationship-types)
  * [Has Many](extend/forms/relation-controller.md#has-many)
  * [Belongs to Many](extend/forms/relation-controller.md#belongs-to-many)
  * [Belongs to Many (with Pivot Data)](extend/forms/relation-controller.md#belongs-to-many-with-pivot-data)
  * [Belongs To](extend/forms/relation-controller.md#belongs-to)
  * [Has One](extend/forms/relation-controller.md#has-one)
* [Displaying a Relation Manager](extend/forms/relation-controller.md#displaying-a-relation-manager)
* [Extending Relation Behavior](extend/forms/relation-controller.md#extending-relation-behavior)
  * [Extending Relation Configuration](extend/forms/relation-controller.md#extending-relation-configuration)
  * [Extending the View Widget](extend/forms/relation-controller.md#extending-the-view-widget)
  * [Extending the Manage Widget](extend/forms/relation-controller.md#extending-the-manage-widget)
  * [Extending the Pivot Widget](extend/forms/relation-controller.md#extending-the-pivot-widget)
  * [Extending the Filter Widgets](extend/forms/relation-controller.md#extending-the-filter-widgets)
  * [Extending the Refresh Results](extend/forms/relation-controller.md#extending-the-refresh-results)

#### [Field Dependencies](extend/forms/field-dependencies.md)

* [Filtering Fields](extend/forms/field-dependencies.md#filtering-fields)
* [Updating with AJAX](extend/forms/field-dependencies.md#updating-with-ajax)

#### [Form Widgets](extend/forms/form-widgets.md)

### List Design

#### [List Controller](extend/lists/list-controller.md)

* [Configuring the List Behavior](extend/lists/list-controller.md#configuring-the-list-behavior)
  * [Adding a Toolbar](extend/lists/list-controller.md#adding-a-toolbar)
  * [Filtering the List](extend/lists/list-controller.md#filtering-the-list)
* [Defining List Columns](extend/lists/list-controller.md#defining-list-columns)
* [Displaying the List](extend/lists/list-controller.md#displaying-the-list)
* [Multiple List Definitions](extend/lists/list-controller.md#multiple-list-definitions)
* [Extending List Behavior](extend/lists/list-controller.md#extending-list-behavior)
  * [Extending the List Configuration](extend/lists/list-controller.md#extending-the-list-configuration)
  * [Overriding Controller Action](extend/lists/list-controller.md#overriding-controller-action)
  * [Overriding Views](extend/lists/list-controller.md#overriding-views)
  * [Extending Column Definitions](extend/lists/list-controller.md#extending-column-definitions)
  * [Inject CSS Row Class](extend/lists/list-controller.md#inject-css-row-class)
  * [Overriding Column URL](extend/lists/list-controller.md#overriding-column-url)
  * [Extending Filter Scopes](extend/lists/list-controller.md#extending-filter-scopes)
  * [Extending the Model Query](extend/lists/list-controller.md#extending-the-model-query)
  * [Extending the Records Collection](extend/lists/list-controller.md#extending-the-records-collection)
  * [Custom Column Types](extend/lists/list-controller.md#custom-column-types)

#### [Sorting Records](extend/lists/structures.md)

* [Configuring a Behavior](extend/lists/structures.md#configuring-a-behavior)
* [Supported Model Types](extend/lists/structures.md#supported-model-types)
  * [Nested Set](extend/lists/structures.md#nested-set)
  * [Simple Tree](extend/lists/structures.md#simple-tree)
  * [Sortable Model](extend/lists/structures.md#sortable-model)
* [Sorting Related Records](extend/lists/structures.md#sorting-related-records)
  * [Sortable Relation Model Trait](extend/lists/structures.md#sortable-relation-model-trait)

#### [Filtering Records](extend/lists/filters.md)

* [Configuring a Behavior](extend/lists/filters.md#configuring-a-behavior)
* [Defining Filter Scopes](extend/lists/filters.md#defining-filter-scopes)
  * [Filter Dependencies](extend/lists/filters.md#filter-dependencies)

#### [Filter Widgets](extend/lists/filter-widgets.md)

* [Class Definition](extend/lists/filter-widgets.md#class-definition)
* [Filter Widget Properties](extend/lists/filter-widgets.md#filter-widget-properties)
* [Filter Widget Registration](extend/lists/filter-widgets.md#filter-widget-registration)
* [Displaying the Filter State](extend/lists/filter-widgets.md#displaying-the-filter-state)
* [Displaying the Filter Form](extend/lists/filter-widgets.md#displaying-the-filter-form)
* [Capturing the Filter Value](extend/lists/filter-widgets.md#capturing-the-filter-value)
* [Applying the Scope to the Query](extend/lists/filter-widgets.md#applying-the-scope-to-the-query)
* [Working with Inline Filters](extend/lists/filter-widgets.md#working-with-inline-filters)

### Import & Export

#### [Import Export Controller](extend/importexport/importexport-controller.md)

* [Configuring the Behavior](extend/importexport/importexport-controller.md#configuring-the-behavior)
  * [Import Page](extend/importexport/importexport-controller.md#import-page)
  * [Export Page](extend/importexport/importexport-controller.md#export-page)
  * [Format Options](extend/importexport/importexport-controller.md#format-options)
* [Import and Export Views](extend/importexport/importexport-controller.md#import-and-export-views)
  * [Import View](extend/importexport/importexport-controller.md#import-view)
  * [Export View](extend/importexport/importexport-controller.md#export-view)
* [Integration with List Behavior](extend/importexport/importexport-controller.md#integration-with-list-behavior)

#### [Import Export Model](extend/importexport/importexport-model.md)

* [Import Model](extend/importexport/importexport-model.md#import-model)
  * [Importing with PHP](extend/importexport/importexport-model.md#importing-with-php)
* [Export Model](extend/importexport/importexport-model.md#export-model)
  * [Exporting with PHP](extend/importexport/importexport-model.md#exporting-with-php)
* [Custom Options](extend/importexport/importexport-model.md#custom-options)

### Settings & Config

#### [Introduction](extend/settings/settings.md)

* [Settings Page Registration](extend/settings/settings.md#settings-page-registration)
  * [Settings Properties](extend/settings/settings.md#settings-properties)
  * [Linking to a Model Class](extend/settings/settings.md#linking-to-a-model-class)
* [Linking to a Controller Class](extend/settings/settings.md#linking-to-a-controller-class)
  * [Settings Page Class Definition](extend/settings/settings.md#settings-page-class-definition)

#### [File Settings](extend/settings/file-settings.md)

* [Config File Structure](extend/settings/file-settings.md#config-file-structure)
  * [Accessing Configuration Values](extend/settings/file-settings.md#accessing-configuration-values)
  * [Overriding Configuration Values](extend/settings/file-settings.md#overriding-configuration-values)

#### [Model Settings](extend/settings/model-settings.md)

* [Database Settings](extend/settings/model-settings.md#database-settings)
  * [Model Class Definition](extend/settings/model-settings.md#model-class-definition)
* [Writing to a Settings Model](extend/settings/model-settings.md#writing-to-a-settings-model)
* [Reading From a Settings Model](extend/settings/model-settings.md#reading-from-a-settings-model)
* [Integration with Multisite](extend/settings/model-settings.md#integration-with-multisite)

### Dashboard Design

#### [Dash Controller](extend/dashboards/dash-controller.md)

* [Data Sources](extend/dashboards/dash-controller.md#data-sources)
  * [Default Widget Types](extend/dashboards/dash-controller.md#default-widget-types)
* [Creating Default Plugin Dashboards](extend/dashboards/dash-controller.md#creating-default-plugin-dashboards)

#### [Data Sources](extend/dashboards/data-sources.md)

* [Creating Data Sources](extend/dashboards/data-sources.md#creating-data-sources)
  * [Registering Dimensions](extend/dashboards/data-sources.md#registering-dimensions)
  * [Registering Metrics](extend/dashboards/data-sources.md#registering-metrics)
  * [Returning Data from a Data Source](extend/dashboards/data-sources.md#returning-data-from-a-data-source)
  * [Formatting Metrics Data](extend/dashboards/data-sources.md#formatting-metrics-data)
  * [Custom Display Formatting](extend/dashboards/data-sources.md#custom-display-formatting)
  * [Displaying Extra Dimension Data](extend/dashboards/data-sources.md#displaying-extra-dimension-data)
  * [Using the Data Source](extend/dashboards/data-sources.md#using-the-data-source)

#### [Report Widgets](extend/dashboards/report-widgets.md)

* [Class Definition](extend/dashboards/report-widgets.md#class-definition)
* [Report Widget Properties](extend/dashboards/report-widgets.md#report-widget-properties)
* [Report Widget Registration](extend/dashboards/report-widgets.md#report-widget-registration)

#### [Vue Report Widgets](extend/dashboards/vue-report-widgets.md)

* [Creating Custom Dashboard Widgets](extend/dashboards/vue-report-widgets.md#creating-custom-dashboard-widgets)
  * [Creating and Registering Custom Widgets](extend/dashboards/vue-report-widgets.md#creating-and-registering-custom-widgets)
  * [Server-Side Class](extend/dashboards/vue-report-widgets.md#server-side-class)
  * [Client-Side Component](extend/dashboards/vue-report-widgets.md#client-side-component)
  * [Registering a Widget](extend/dashboards/vue-report-widgets.md#registering-a-widget)
  * [Handling Events](extend/dashboards/vue-report-widgets.md#handling-events)

### Database

#### [Basic Usage](extend/database/basics.md)

* [Running Raw SQL Queries](extend/database/basics.md#running-raw-sql-queries)
  * [Selecting Records](extend/database/basics.md#selecting-records)
  * [Modifying Records](extend/database/basics.md#modifying-records)
  * [General Statements](extend/database/basics.md#general-statements)
* [Multiple Database Connections](extend/database/basics.md#multiple-database-connections)
* [Database Transactions](extend/database/basics.md#database-transactions)
* [Database Events](extend/database/basics.md#database-events)
  * [Query Logging](extend/database/basics.md#query-logging)

#### [Query Builder](extend/database/query.md)

* [Retrieving Results](extend/database/query.md#retrieving-results)
  * [Plucking Values](extend/database/query.md#plucking-values)
  * [Chunking Results](extend/database/query.md#chunking-results)
  * [Aggregate Functions](extend/database/query.md#aggregate-functions)
* [Select Statements](extend/database/query.md#select-statements)
  * [Raw Expressions](extend/database/query.md#raw-expressions)
  * [Raw Methods](extend/database/query.md#raw-methods)
* [Joins](extend/database/query.md#joins)
  * [Advanced Join Statements](extend/database/query.md#advanced-join-statements)
  * [Subquery Joins](extend/database/query.md#subquery-joins)
  * [Unions](extend/database/query.md#unions)
* [Where Clauses](extend/database/query.md#where-clauses)
  * [Or Statements](extend/database/query.md#or-statements)
  * [More Where Statements](extend/database/query.md#more-where-statements)
  * [Search Statement](extend/database/query.md#search-statement)
* [Compound Where Clauses](extend/database/query.md#compound-where-clauses)
  * [Exists Statements](extend/database/query.md#exists-statements)
  * [JSON Where Statements](extend/database/query.md#json-where-statements)
  * [Conditional Clauses](extend/database/query.md#conditional-clauses)
* [Order, Group, Limit](extend/database/query.md#order-group-limit)
  * [Ordering](extend/database/query.md#ordering)
  * [Grouping](extend/database/query.md#grouping)
  * [Limit and Offset](extend/database/query.md#limit-and-offset)
* [Inserts](extend/database/query.md#inserts)
  * [Auto-Incrementing IDs](extend/database/query.md#auto-incrementing-ids)
* [Updates](extend/database/query.md#updates)
  * [Update or Insert](extend/database/query.md#update-or-insert)
  * [Upsert](extend/database/query.md#upsert)
  * [Updating JSON columns](extend/database/query.md#updating-json-columns)
  * [Increment / Decrement](extend/database/query.md#increment-decrement)
* [Deletes](extend/database/query.md#deletes)
* [Pessimistic Locking](extend/database/query.md#pessimistic-locking)
* [Caching Queries](extend/database/query.md#caching-queries)
* [Debugging](extend/database/query.md#debugging)

#### [Model Queries](extend/database/model.md)

* [Retrieving Multiple Models](extend/database/model.md#retrieving-multiple-models)
  * [Accessing Column Values](extend/database/model.md#accessing-column-values)
  * [Adding Additional Constraints](extend/database/model.md#adding-additional-constraints)
  * [Collections](extend/database/model.md#collections)
  * [Chunking Results](extend/database/model.md#chunking-results)
* [Retrieving a Single Model](extend/database/model.md#retrieving-a-single-model)
  * [Not Found Exceptions](extend/database/model.md#not-found-exceptions)
  * [Retrieving Aggregates](extend/database/model.md#retrieving-aggregates)
* [Inserting & Updating Models](extend/database/model.md#inserting-updating-models)
  * [Basic Inserts](extend/database/model.md#basic-inserts)
  * [Basic Updates](extend/database/model.md#basic-updates)
  * [Mass Assignment](extend/database/model.md#mass-assignment)
  * [Other Creation Methods](extend/database/model.md#other-creation-methods)
* [Deleting Models](extend/database/model.md#deleting-models)
* [Query Scopes](extend/database/model.md#query-scopes)

#### [Relationships](extend/database/relations.md)

* [Defining Relationships](extend/database/relations.md#defining-relationships)
* [Detailed Definitions](extend/database/relations.md#detailed-definitions)
* [Relationship Types](extend/database/relations.md#relationship-types)
  * [One To One](extend/database/relations.md#one-to-one)
  * [One To Many](extend/database/relations.md#one-to-many)
  * [Many To Many](extend/database/relations.md#many-to-many)
  * [Has Many Through](extend/database/relations.md#has-many-through)
  * [Has One Through](extend/database/relations.md#has-one-through)
* [Polymorphic Relations](extend/database/relations.md#polymorphic-relations)
  * [Polymorphic One To One](extend/database/relations.md#polymorphic-one-to-one)
  * [Polymorphic One To Many](extend/database/relations.md#polymorphic-one-to-many)
  * [Polymorphic Many To Many](extend/database/relations.md#polymorphic-many-to-many)
* [Querying Relations](extend/database/relations.md#querying-relations)
  * [Access via Relationship Method](extend/database/relations.md#access-via-relationship-method)
  * [Access via Dynamic Property](extend/database/relations.md#access-via-dynamic-property)
  * [Querying Relationship Existence](extend/database/relations.md#querying-relationship-existence)
  * [Counting Related Records](extend/database/relations.md#counting-related-records)
* [Eager Loading](extend/database/relations.md#eager-loading)
  * [Constraining Eager Loads](extend/database/relations.md#constraining-eager-loads)
  * [Lazy Eager Loading](extend/database/relations.md#lazy-eager-loading)
* [Inserting Related Models](extend/database/relations.md#inserting-related-models)
  * [Insert via Relationship Method](extend/database/relations.md#insert-via-relationship-method)
  * [Insert via Dynamic Property](extend/database/relations.md#insert-via-dynamic-property)
  * [Many To Many Relations](extend/database/relations.md#many-to-many-relations)
  * [Touching Parent Timestamps](extend/database/relations.md#touching-parent-timestamps)
* [Deferred Binding](extend/database/relations.md#deferred-binding)
  * [Generating a Session Key](extend/database/relations.md#generating-a-session-key)
  * [Defer a Relation Binding](extend/database/relations.md#defer-a-relation-binding)
  * [Defer a Relation Unbinding](extend/database/relations.md#defer-a-relation-unbinding)
  * [List All Bindings](extend/database/relations.md#list-all-bindings)
  * [Cancel All Bindings](extend/database/relations.md#cancel-all-bindings)
  * [Commit All Bindings](extend/database/relations.md#commit-all-bindings)
  * [Lazily Commit Bindings](extend/database/relations.md#lazily-commit-bindings)
  * [Clean Up Orphaned Bindings](extend/database/relations.md#clean-up-orphaned-bindings)
  * [Disable Deferred Binding](extend/database/relations.md#disable-deferred-binding)

#### [Migrations & Seeding](extend/database/structure.md)

* [Migration Structure](extend/database/structure.md#migration-structure)
* [Creating Tables](extend/database/structure.md#creating-tables)
  * [Connection & Storage Engine](extend/database/structure.md#connection-storage-engine)
* [Renaming / Dropping Tables](extend/database/structure.md#renaming-dropping-tables)
* [Creating Columns](extend/database/structure.md#creating-columns)
  * [Available Column Types](extend/database/structure.md#available-column-types)
  * [Column Modifiers](extend/database/structure.md#column-modifiers)
* [Modifying Columns](extend/database/structure.md#modifying-columns)
  * [Renaming Columns](extend/database/structure.md#renaming-columns)
  * [Dropping Columns](extend/database/structure.md#dropping-columns)
* [Creating Indexes](extend/database/structure.md#creating-indexes)
  * [Renaming Indexes](extend/database/structure.md#renaming-indexes)
  * [Dropping Indexes](extend/database/structure.md#dropping-indexes)
  * [Foreign Key Constraints](extend/database/structure.md#foreign-key-constraints)
* [Seeder Structure](extend/database/structure.md#seeder-structure)
  * [Calling Additional Seeders](extend/database/structure.md#calling-additional-seeders)

#### [File Attachments](extend/database/attachments.md)

* [Creating New Attachments](extend/database/attachments.md#creating-new-attachments)
  * [Handling Multiple Attachments](extend/database/attachments.md#handling-multiple-attachments)
* [Viewing Attachments](extend/database/attachments.md#viewing-attachments)
  * [Accessing the Local Path](extend/database/attachments.md#accessing-the-local-path)
* [Resizing Thumbs](extend/database/attachments.md#resizing-thumbs)
* [Output and Download](extend/database/attachments.md#output-and-download)
* [Usage Example](extend/database/attachments.md#usage-example)
* [Validation Example](extend/database/attachments.md#validation-example)

#### [Collections](extend/database/collection.md)

* [Available Methods](extend/database/collection.md#available-methods)
* [Custom Collections](extend/database/collection.md#custom-collections)

#### [Pagination](extend/database/pagination.md)

* [Basic usage](extend/database/pagination.md#basic-usage)
  * [Paginating Query Builder Results](extend/database/pagination.md#paginating-query-builder-results)
  * [Paginating Model Results](extend/database/pagination.md#paginating-model-results)
  * [Manually Creating a Paginator](extend/database/pagination.md#manually-creating-a-paginator)
* [Displaying Results in a View](extend/database/pagination.md#displaying-results-in-a-view)
* [Converting results to JSON](extend/database/pagination.md#converting-results-to-json)

#### [Mutators](extend/database/mutators.md)

* [Accessors & Mutators](extend/database/mutators.md#accessors-mutators)
* [Date Mutators](extend/database/mutators.md#date-mutators)
* [Attribute Casting](extend/database/mutators.md#attribute-casting)

#### [Serialization](extend/database/serialization.md)

* [Basic Usage](extend/database/serialization.md#basic-usage)
* [Hiding Attributes from JSON](extend/database/serialization.md#hiding-attributes-from-json)
* [Appending Values to JSON](extend/database/serialization.md#appending-values-to-json)

#### [Traits](extend/database/traits.md)

* [Attribute Manipulation](extend/database/traits.md#attribute-manipulation)
  * [Nullable](extend/database/traits.md#nullable)
  * [Hashable](extend/database/traits.md#hashable)
  * [Purgeable](extend/database/traits.md#purgeable)
  * [Encryptable](extend/database/traits.md#encryptable)
  * [Sluggable](extend/database/traits.md#sluggable)
* [Sorting and Reordering](extend/database/traits.md#sorting-and-reordering)
  * [Sortable](extend/database/traits.md#sortable)
  * [Simple Tree](extend/database/traits.md#simple-tree)
  * [Nested Tree](extend/database/traits.md#nested-tree)
* [Utility Functions](extend/database/traits.md#utility-functions)
  * [Validation](extend/database/traits.md#validation)
  * [Soft Deleting](extend/database/traits.md#soft-deleting)
  * [Multisite](extend/database/traits.md#multisite)
  * [Revisionable](extend/database/traits.md#revisionable)

### Services

#### [Application](extend/services/application.md)

* [Service Providers](extend/services/application.md#service-providers)
* [Application Events](extend/services/application.md#application-events)
* [Application Helpers](extend/services/application.md#application-helpers)

#### [Cache](extend/services/cache.md)

* [Configuration](extend/services/cache.md#configuration)
* [Cache Prerequisites](extend/services/cache.md#cache-prerequisites)
* [Cache Usage](extend/services/cache.md#cache-usage)
* [Retrieving Items from the Cache](extend/services/cache.md#retrieving-items-from-the-cache)
* [Storing Items in the Cache](extend/services/cache.md#storing-items-in-the-cache)
* [Removing Items from the Cache](extend/services/cache.md#removing-items-from-the-cache)

#### [Collection](extend/services/collection.md)

* [Creating Collections](extend/services/collection.md#creating-collections)
* [Available Methods](extend/services/collection.md#available-methods)
* [Method Listing](extend/services/collection.md#method-listing)

#### [Log](extend/services/log.md)

#### [Event](extend/services/event.md)

* [Basic Usage](extend/services/event.md#basic-usage)
* [Subscribing to Events](extend/services/event.md#subscribing-to-events)
  * [Where to Register Listeners](extend/services/event.md#where-to-register-listeners)
  * [Subscribe Using Priority](extend/services/event.md#subscribe-using-priority)
  * [Halting Events](extend/services/event.md#halting-events)
  * [Wildcard Listeners](extend/services/event.md#wildcard-listeners)
* [Firing Events](extend/services/event.md#firing-events)
* [Passing Arguments by Reference](extend/services/event.md#passing-arguments-by-reference)
  * [Queued Events](extend/services/event.md#queued-events)
* [Using Classes as Listeners](extend/services/event.md#using-classes-as-listeners)
  * [Subscribe to Individual Methods](extend/services/event.md#subscribe-to-individual-methods)
  * [Subscribe to Entire Class](extend/services/event.md#subscribe-to-entire-class)
* [Event Emitter Trait](extend/services/event.md#event-emitter-trait)

#### [Form & HTML](extend/services/html.md)

* [Introduction](extend/services/html.md#introduction)
* [Opening a Form](extend/services/html.md#opening-a-form)
* [Form Tokens](extend/services/html.md#form-tokens)
* [Form Model Binding](extend/services/html.md#form-model-binding)
* [Labels](extend/services/html.md#labels)
* [Text Fields](extend/services/html.md#text-fields)
* [Checkboxes and Radio Buttons](extend/services/html.md#checkboxes-and-radio-buttons)
* [Number](extend/services/html.md#number)
* [File Input](extend/services/html.md#file-input)
* [Drop-down Lists](extend/services/html.md#drop-down-lists)
* [Buttons](extend/services/html.md#buttons)
* [Custom Macros](extend/services/html.md#custom-macros)

#### [Resizer](extend/services/resizer.md)

* [Introduction](extend/services/resizer.md#introduction)
* [Resize a File on Disk](extend/services/resizer.md#resize-a-file-on-disk)
  * [Resize Parameters](extend/services/resizer.md#resize-parameters)
  * [Available Modes](extend/services/resizer.md#available-modes)
* [Resize a File to Browser](extend/services/resizer.md#resize-a-file-to-browser)

#### [HTTP Client](extend/services/http.md)

* [Basic Usage](extend/services/http.md#basic-usage)
* [Handling the Response](extend/services/http.md#handling-the-response)
* [Sending Request Data](extend/services/http.md#sending-request-data)
* [Error Handling](extend/services/http.md#error-handling)

#### [Hash & Crypt](extend/services/hash-crypt.md)

* [Configuration](extend/services/hash-crypt.md#configuration)
* [Hashing](extend/services/hash-crypt.md#hashing)
* [Encryption](extend/services/hash-crypt.md#encryption)

#### [Helpers](extend/services/helpers.md)

* [Arrays](extend/services/helpers.md#arrays-2)
* [Paths](extend/services/helpers.md#paths-2)
* [Strings](extend/services/helpers.md#strings-2)
* [Miscellaneous](extend/services/helpers.md#miscellaneous-2)

#### [Parser](extend/services/parser.md)

* [Markdown Parser](extend/services/parser.md#markdown-parser)
  * [Using HTML in Markdown](extend/services/parser.md#using-html-in-markdown)
* [Twig Template Parser](extend/services/parser.md#twig-template-parser)
* [Bracket Parser](extend/services/parser.md#bracket-parser)
* [YAML Configuration Parser](extend/services/parser.md#yaml-configuration-parser)
* [Initialization (INI) Configuration Parser](extend/services/parser.md#initialization-ini-configuration-parser)
  * [October Flavored INI](extend/services/parser.md#october-flavored-ini)
* [Dynamic Syntax Parser](extend/services/parser.md#dynamic-syntax-parser)
  * [View Mode](extend/services/parser.md#view-mode)
  * [Editor Mode](extend/services/parser.md#editor-mode)
  * [Supported Tags](extend/services/parser.md#supported-tags)

#### [Queue](extend/services/queue.md)

* [Configuration](extend/services/queue.md#configuration)
  * [Driver Prerequisites](extend/services/queue.md#driver-prerequisites)
* [Basic Usage](extend/services/queue.md#basic-usage)
* [Queueing closures](extend/services/queue.md#queueing-closures)
* [Running the queue worker](extend/services/queue.md#running-the-queue-worker)
* [Daemon Queue Worker](extend/services/queue.md#daemon-queue-worker)
  * [Deploying with daemon queue workers](extend/services/queue.md#deploying-with-daemon-queue-workers)
  * [Coding for daemon queue workers](extend/services/queue.md#coding-for-daemon-queue-workers)
* [Supervisor Configuration](extend/services/queue.md#supervisor-configuration)
  * [Installing Supervisor](extend/services/queue.md#installing-supervisor)
  * [Configuring Supervisor](extend/services/queue.md#configuring-supervisor)
  * [Starting Supervisor](extend/services/queue.md#starting-supervisor)
* [Failed Jobs](extend/services/queue.md#failed-jobs)
  * [Retrying Failed Jobs](extend/services/queue.md#retrying-failed-jobs)

#### [Request & Input](extend/services/request-input.md)

* [Basic Input](extend/services/request-input.md#basic-input)
* [Cookies](extend/services/request-input.md#cookies)
* [Old Input](extend/services/request-input.md#old-input)
* [Files](extend/services/request-input.md#files)
* [Request Information](extend/services/request-input.md#request-information)

#### [Response & View](extend/services/response-view.md)

* [Basic Responses](extend/services/response-view.md#basic-responses)
  * [Attaching Headers to Responses](extend/services/response-view.md#attaching-headers-to-responses)
  * [Attaching Cookies to Responses](extend/services/response-view.md#attaching-cookies-to-responses)
* [Other Response Types](extend/services/response-view.md#other-response-types)
  * [View Responses](extend/services/response-view.md#view-responses)
  * [JSON Responses](extend/services/response-view.md#json-responses)
  * [File Downloads](extend/services/response-view.md#file-downloads)
  * [File Responses](extend/services/response-view.md#file-responses)
* [Redirects](extend/services/response-view.md#redirects)
  * [Returning a Redirect with Flash Data](extend/services/response-view.md#returning-a-redirect-with-flash-data)
* [Response Macros](extend/services/response-view.md#response-macros)
* [Views](extend/services/response-view.md#views)

#### [Session](extend/services/session.md)

* [Configuration](extend/services/session.md#configuration)
* [Storing Data](extend/services/session.md#storing-data)
* [Retrieving Data](extend/services/session.md#retrieving-data)
* [Deleting Data](extend/services/session.md#deleting-data)
* [Regenerating the Session](extend/services/session.md#regenerating-the-session)
* [Flash Data](extend/services/session.md#flash-data)

#### [Site Manager](extend/services/site.md)

* [Checking Site Configuration State](extend/services/site.md#checking-site-configuration-state)
* [Retrieving a Site](extend/services/site.md#retrieving-a-site)
* [Accessing Multiple Sites](extend/services/site.md#accessing-multiple-sites)
* [Site Context](extend/services/site.md#site-context)

#### [Storage](extend/services/storage.md)

* [Configuration](extend/services/storage.md#configuration)
  * [Basic Usage](extend/services/storage.md#basic-usage)
  * [Obtaining Disk Instances](extend/services/storage.md#obtaining-disk-instances)
  * [Retrieving Files](extend/services/storage.md#retrieving-files)
  * [Storing Files](extend/services/storage.md#storing-files)
  * [Deleting Files](extend/services/storage.md#deleting-files)
  * [Directories](extend/services/storage.md#directories)

#### [Validation](extend/services/validation.md)

* [Basic Usage](extend/services/validation.md#basic-usage)
  * [Checking the Validation Results](extend/services/validation.md#checking-the-validation-results)
  * [Validating Files](extend/services/validation.md#validating-files)
* [Throwing a Validation Exception](extend/services/validation.md#throwing-a-validation-exception)
  * [Validating the Request](extend/services/validation.md#validating-the-request)
* [Working with Error Messages](extend/services/validation.md#working-with-error-messages)
* [Error Messages & Views](extend/services/validation.md#error-messages-views)
  * [Named Error Bags](extend/services/validation.md#named-error-bags)
* [Available Validation Rules](extend/services/validation.md#available-validation-rules)
* [Conditionally Adding Rules](extend/services/validation.md#conditionally-adding-rules)
* [Validating Arrays](extend/services/validation.md#validating-arrays)
* [Custom Error Messages](extend/services/validation.md#custom-error-messages)
  * [Specifying Custom Messages in Language Files](extend/services/validation.md#specifying-custom-messages-in-language-files)
  * [Overriding Validation Messages Globally](extend/services/validation.md#overriding-validation-messages-globally)
* [Custom Validation Rules](extend/services/validation.md#custom-validation-rules)
  * [Globally Registered Rules](extend/services/validation.md#globally-registered-rules)
  * [Local Rule Objects](extend/services/validation.md#local-rule-objects)

### Resources

#### [Publishing Packages](extend/resources/publishing-packages.md)

* [Publishing Plugins](extend/resources/publishing-packages.md#publishing-plugins)
* [Publishing Themes](extend/resources/publishing-packages.md#publishing-themes)
* [Declaring Dependencies](extend/resources/publishing-packages.md#declaring-dependencies)
  * [Requiring a Version of October CMS](extend/resources/publishing-packages.md#requiring-a-version-of-october-cms)
  * [Requiring Another Plugin](extend/resources/publishing-packages.md#requiring-another-plugin)
  * [Requiring Another Theme](extend/resources/publishing-packages.md#requiring-another-theme)
  * [Developing With Third Party Packages](extend/resources/publishing-packages.md#developing-with-third-party-packages)
* [Tagging a Release](extend/resources/publishing-packages.md#tagging-a-release)
  * [Semantic Versioning](extend/resources/publishing-packages.md#semantic-versioning)
  * [Listing Your Tags](extend/resources/publishing-packages.md#listing-your-tags)
  * [Creating a New Tag](extend/resources/publishing-packages.md#creating-a-new-tag)
  * [Incrementing the Version File](extend/resources/publishing-packages.md#incrementing-the-version-file)
* [Private Plugins and Themes](extend/resources/publishing-packages.md#private-plugins-and-themes)
  * [Install from a Remote Source](extend/resources/publishing-packages.md#install-from-a-remote-source)
  * [Install from a Local Source](extend/resources/publishing-packages.md#install-from-a-local-source)

#### [Using Laravel Packages](extend/resources/using-laravel-packages.md)

---

## [API Handbook](element/form-fields.md)

Reference guide for form fields, list columns, filter scopes, etc.

### Definitions

#### [Form Fields](element/form-fields.md)

* [Available Fields](element/form-fields.md#available-fields)
* [Field Properties](element/form-fields.md#field-properties)
* [Tab Properties](element/form-fields.md#tab-properties)
* [Custom Field Types](element/form-fields.md#custom-field-types)
* [Nested Field Selection](element/form-fields.md#nested-field-selection)
* [Field Facades](element/form-fields.md#field-facades)
* [Field Conditions](element/form-fields.md#field-conditions)
* [Trigger Events](element/form-fields.md#trigger-events)
* [Input Preset Converter](element/form-fields.md#input-preset-converter)

#### [List Columns](element/list-columns.md)

* [Available Columns](element/list-columns.md#available-columns)
* [Column Properties](element/list-columns.md#column-properties)
* [Custom Value Selection](element/list-columns.md#custom-value-selection)
* [Nested Column Selection](#nested-column-selection)
* [Direct SQL Selection](#direct-sql-selection)
* [Related Column Selection](#related-column-selection)
* [Tooltip](#tooltip)

#### [Filter Scopes](element/filter-scopes.md)

* [Available Scopes](element/filter-scopes.md#available-scopes)
* [Scope Properties](element/filter-scopes.md#scope-properties)
* [Applying Model Scopes](element/filter-scopes.md#applying-model-scopes)
* [Scope Dependencies](element/filter-scopes.md#scope-dependencies)

#### [Inspector Types](element/inspector-types.md)

* [Available Types](element/inspector-types.md#available-types)
* [Available Configuration](element/inspector-types.md#available-configuration)
* [Validation Rules](element/inspector-types.md#validation-rules)
* [Required Validator](element/inspector-types.md#required-validator)
* [Regex Validator](element/inspector-types.md#regex-validator)
* [Integer Validator](element/inspector-types.md#integer-validator)
* [Float Validator](element/inspector-types.md#float-validator)
* [Length Validator](element/inspector-types.md#length-validator)

#### [Defining Options](element/define-options.md)

* [Option Arrays](element/define-options.md#option-arrays)
* [Option Presets](element/define-options.md#option-presets)
* [Option Methods](element/define-options.md#option-methods)
* [Detailed Option Definitions](element/define-options.md#detailed-option-definitions)

#### [Available Icons](element/available-icons.md)

* [Phosphor Icons](element/available-icons.md#phosphor-icons)
* [October Icons](element/available-icons.md#october-icons)
* [Available October Icons](element/available-icons.md#available-october-icons)

#### [Available Commands](element/available-commands.md)

* [Setup & Maintenance](element/available-commands.md#setup-maintenance)
  * [Command - october:update](element/available-commands.md#command-october-update)
  * [Command - october:migrate](element/available-commands.md#command-october-migrate)
  * [Command - october:passwd](element/available-commands.md#command-october-passwd)
  * [Command - october:optimize](element/available-commands.md#command-october-optimize)
* [Project Management](element/available-commands.md#project-management)
  * [Command - project:sync](element/available-commands.md#command-project-sync)
  * [Command - project:set](element/available-commands.md#command-project-set)
* [Plugin Management](element/available-commands.md#plugin-management)
  * [Command - plugin:install](element/available-commands.md#command-plugin-install)
  * [Command - plugin:check](element/available-commands.md#command-plugin-check)
  * [Command - plugin:refresh](element/available-commands.md#command-plugin-refresh)
  * [Command - plugin:list](element/available-commands.md#command-plugin-list)
  * [Command - plugin:disable](element/available-commands.md#command-plugin-disable)
  * [Command - plugin:enable](element/available-commands.md#command-plugin-enable)
  * [Command - plugin:remove](element/available-commands.md#command-plugin-remove)
* [Theme Management](element/available-commands.md#theme-management)
  * [Command - theme:install](element/available-commands.md#command-theme-install)
  * [Command - theme:check](element/available-commands.md#command-theme-check)
  * [Command - theme:list](element/available-commands.md#command-theme-list)
  * [Command - theme:use](element/available-commands.md#command-theme-use)
  * [Command - theme:remove](element/available-commands.md#command-theme-remove)
  * [Command - theme:copy](element/available-commands.md#command-theme-copy)
* [Utilities](element/available-commands.md#utilities)
  * [Command - cache:clear](element/available-commands.md#command-cache-clear)
  * [Command - october:fresh](element/available-commands.md#command-october-fresh)
  * [Command - october:mirror](element/available-commands.md#command-october-mirror)
  * [Command - october:util](element/available-commands.md#command-october-util)

### Tailor Fields

#### [Mixin](element/content/field-mixin.md)

#### [Entries](element/content/field-entries.md)

* [Applying Conditions](element/content/field-entries.md#applying-conditions)
* [SQL Query Condition](element/content/field-entries.md#sql-query-condition)
* [PHP Query Scopes](element/content/field-entries.md#php-query-scopes)
* [Defining the Inverse Relation](element/content/field-entries.md#defining-the-inverse-relation)
* [List Column Display](element/content/field-entries.md#list-column-display)
* [Display as a Counter](element/content/field-entries.md#display-as-a-counter)
* [Advanced Record Management](element/content/field-entries.md#advanced-record-management)

#### [Nested Items](element/content/field-nesteditems.md)

### Form UI

#### [Section](element/form/ui-section.md)

#### [Hint](element/form/ui-hint.md)

#### [Horizontal Rule](element/form/ui-ruler.md)

#### [Partial](element/form/ui-partial.md)

* [Accessing Variables](element/form/ui-partial.md#accessing-variables)
* [Using View Templates](element/form/ui-partial.md#using-view-templates)

### Form Fields

#### [Text](element/form/field-text.md)

#### [Number](element/form/field-number.md)

* [Server-side Validation](element/form/field-number.md#server-side-validation)

#### [Password](element/form/field-password.md)

#### [Email](element/form/field-email.md)

* [Server-side Validation](element/form/field-email.md#server-side-validation)

#### [Textarea](element/form/field-textarea.md)

#### [Dropdown](element/form/field-dropdown.md)

* [Dynamic Options](element/form/field-dropdown.md#dynamic-options)
* [Custom Select2 Configuration](element/form/field-dropdown.md#custom-select2-configuration)

#### [Radio List](element/form/field-radio.md)

* [Dynamic Options](element/form/field-radio.md#dynamic-options)

#### [Balloon Selector](element/form/field-balloon.md)

#### [Checkbox](element/form/field-checkbox.md)

#### [Checkbox List](element/form/field-checkboxlist.md)

#### [Switch](element/form/field-switch.md)

### Form Widgets

#### [Code Editor](element/form/widget-codeeditor.md)

#### [Color Picker](element/form/widget-colorpicker.md)

* [Dynamic Available Colors](element/form/widget-colorpicker.md#dynamic-available-colors)

#### [Data Table](element/form/widget-datatable.md)

#### [Date Picker](element/form/widget-datepicker.md)

#### [File Upload](element/form/widget-fileupload.md)

#### [Markdown Editor](element/form/widget-markdown.md)

#### [Media Finder](element/form/widget-mediafinder.md)

* [Selecting Multiple Items](element/form/widget-mediafinder.md#selecting-multiple-items)

#### [Nested Form](element/form/widget-nestedform.md)

#### [Record Finder](element/form/widget-recordfinder.md)

* [Usage in Tailor](element/form/widget-recordfinder.md#usage-in-tailor)

#### [Relation](element/form/widget-relation.md)

* [Applying Conditions](element/form/widget-relation.md#applying-conditions)
* [SQL Query Condition](element/form/widget-relation.md#sql-query-condition)
* [PHP Query Scopes](element/form/widget-relation.md#php-query-scopes)
* [Relation Controller Integration](element/form/widget-relation.md#relation-controller-integration)

#### [Repeater](element/form/widget-repeater.md)

* [Grouped Repeaters](element/form/widget-repeater.md#grouped-repeaters)
* [Example of Using Related Records](element/form/widget-repeater.md#example-of-using-related-records)

#### [Rich Editor / WYSIWYG](element/form/widget-richeditor.md)

* [Registering a Custom Button](element/form/widget-richeditor.md#registering-a-custom-button)
* [Trigger a Modal from a Custom Button](element/form/widget-richeditor.md#trigger-a-modal-from-a-custom-button)
* [Advanced Editor Options](element/form/widget-richeditor.md#advanced-editor-options)

#### [Page Finder](element/form/widget-pagefinder.md)

* [Linking to Pages](element/form/widget-pagefinder.md#linking-to-pages)
* [Creating New Page Types](element/form/widget-pagefinder.md#creating-new-page-types)
* [Registering New Page Types](element/form/widget-pagefinder.md#registering-new-page-types)
* [Returning Information About a Page Type](element/form/widget-pagefinder.md#returning-information-about-a-page-type)
* [Resolving Page Links](element/form/widget-pagefinder.md#resolving-page-links)
* [Resolving Nested Page Links](element/form/widget-pagefinder.md#resolving-nested-page-links)
* [Resolving Other Site Links](element/form/widget-pagefinder.md#resolving-other-site-links)
* [Usage Example](element/form/widget-pagefinder.md#usage-example)

#### [Sensitive](element/form/widget-sensitive.md)

#### [Tag List](element/form/widget-taglist.md)

#### [Currency](element/form/widget-currency.md)

#### [Boxes](element/form/widget-boxes.md)

### List Columns

#### [Text](element/lists/column-text.md)

#### [Number](element/lists/column-number.md)

* [Counting Relations](element/lists/column-number.md#counting-relations)

#### [File](element/lists/column-file.md)

#### [Image](element/lists/column-image.md)

#### [Switch](element/lists/column-switch.md)

#### [Summary](element/lists/column-summary.md)

#### [Date & Time](element/lists/column-datetime.md)

#### [Selectable](element/lists/column-selectable.md)

#### [Linkage](element/lists/column-linkage.md)

* [Custom Link Text](element/lists/column-linkage.md#custom-link-text)

#### [Partial](element/lists/column-partial.md)

* [Using View Templates](element/lists/column-partial.md#using-view-templates)

#### [Color Picker](element/lists/column-colorpicker.md)

#### [Currency](element/lists/column-currency.md)

### Filter Scopes

#### [Checkbox](element/filter/scope-checkbox.md)

#### [Switch](element/filter/scope-switch.md)

#### [Text](element/filter/scope-text.md)

* [PHP Interface](element/filter/scope-text.md#php-interface)

#### [Number](element/filter/scope-number.md)

* [PHP Interface](element/filter/scope-number.md#php-interface)

#### [Dropdown](element/filter/scope-dropdown.md)

* [PHP Interface](element/filter/scope-dropdown.md#php-interface)

#### [Group](element/filter/scope-group.md)

* [PHP Interface](element/filter/scope-group.md#php-interface)

#### [Date](element/filter/scope-date.md)

* [PHP Interface](element/filter/scope-date.md#php-interface)

### Inspector Types

#### [String](element/inspector/type-string.md)

#### [String List](element/inspector/type-stringlist.md)

#### [Text](element/inspector/type-text.md)

#### [Autocomplete](element/inspector/type-autocomplete.md)

* [Dynamic Options](element/inspector/type-autocomplete.md#dynamic-options)

#### [Checkbox](element/inspector/type-checkbox.md)

#### [Dropdown](element/inspector/type-dropdown.md)

* [Dynamic Options](element/inspector/type-dropdown.md#dynamic-options)
* [Page List Properties](element/inspector/type-dropdown.md#page-list-properties)

#### [Dictionary](element/inspector/type-dictionary.md)

* [Extra Validation](element/inspector/type-dictionary.md#extra-validation)

#### [Object](element/inspector/type-object.md)

#### [Object List](element/inspector/type-objectlist.md)

#### [Set](element/inspector/type-set.md)

---


