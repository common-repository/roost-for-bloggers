=== Roost Web Push ===
Contributors: noticesoftware, danstever
Tags: Chrome, Chrome Notifications, Android, Safari, push, push notifications, web push notifications, Mavericks, Yosemite, mobile, web push, Roost, goroost, goroost.com Post, plugin, admin, posts, page, links, widget, ajax, social, wordpress, dashboard, news, notifications, services, desktop notifications, mobile notifications, Roost notifications, apple, google, Firefox, new post, osx, mac, Chrome OS
Requires at least: 4.1
Tested up to: 4.8
Stable tag: 2.5.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Push notifications for your website. Available in Chrome (Android and desktop) and Safari (desktop).

== Description ==

[Web Push by Roost](https://goroost.com/) allows websites to send notifications to their site visitors for updates about new posts. This plugin supports Chrome notifications and Safari for desktop.

Plugin Features:

* **Chrome Notifications** - Use notifications in Chrome (desktop and Android)
* **Firefox Notifications** - Web Push now supported in Firefox
* **Safari Web Push** - Take advantage of web push (desktop push notifications)
* **The Bell** - On-Site notifications AND supported in all browsers ([Want to know more about The Bell?](https://goroost.com/blog/bell-keep-users-loop))
* **Auto Notifications** - We take the work out of it. Automatically send notifications to your readers when creating a new post.
* **Category Filters** - Decide which content triggers a notification based on the category.
* **Notifications on Update** - Easily send notifications when updating posts.
* **Notification Prompt Controls** - Decide how and when the subscription prompt is shown to your visitors.
* **Custom Notification Headlines** - Set a custom headline for your notification to be used instead of a post title.
* **bbPress Subscriptions** - Allows site visitors to subscribe to forums, topics, or individual messages when posting replies.
* **Detailed Analytics** - Charts with detailed metrics about your visitors straight to your WordPress dashboard.
* **Manual Post Mode** - Send notifications for individual posts when creating. Just check the box.
* **Scheduled Post Notifications** - Not posting now? Don't worry. Your alerts will go out when your content posts.

*Roost account needed - Custom plans available.*

[youtube http://www.youtube.com/watch?v=Oae3alI9_jg]

== Installation ==

= From your WordPress dashboard =
1. Visit 'Plugins > Add New'
2. Search for 'Roost'
3. Activate Roost from your Plugins page
4. (a) Create your Roost account - (Click on "sign up now") OR (b) Log In an Existing Account - Click "Log In" and enter your username and password

= From WordPress.org =
1. Download the Roost Web Push Wordpress Plugin.
2. Upload the 'Roost' directory to your '/wp-content/plugins/' directory.
3. Activate Roost Web Push from your Plugins page.
4. (a) Create your Roost account - (Click on "sign up now") OR (b) Log In an Existing Account - Click "Log In" and enter your username and password

= Using Features =

**Chrome Notifications**
To use notifications in Chrome just activate the plugin and sign into your Roost account, we take care of the rest. The necessary files are dynamically generated upon request, eliminating the need to upload additional files or potentially change directory permissions. If you're curious, for detailed information view our [Chrome Integration Guide](https://goroost.com/best-practices/chrome-integration-guide).

**Safari Push Notifications**
To use Safari Web Push, simply activate the Roost plugin. No additional setup is needed.

**Category Filters**
With *Auto Push* enabled, you can select which categories are excluded from triggering notifications.

**Notifications on Updates**
A checkbox is now displayed above the *Publish* button when updating posts. If you want to send a notification when updating, just put a tick in the box. Easy.

**Notification Prompt Control**
Control how and when you display the subscription prompt to your site visitors. From the settings tab, you can set a minimum number of visits, or create a link or button to trigger the prompt. When a button or link is used, if the browser is not able to receive push notifications, we will automatically hide the link or button.

**Custom Notification Headlines**
Use custom text for your notification headline by setting it underneath the standard post content. If you set a custom headline, it will be used for your notification. Not setting a headline will default to your post title.

**bbPress**
With the bbPress extension for Roost, an additional subscribe option will appear next to the default bbPress subscription links. (This does NOT replace traditional subscription methods, only adds a new browser push channel.) Options include Forum subscriptions, Topic subscriptions, and subscribing to your individual posts. Notifications are sent about new content **only** to the visitors that have subscribed to the forum, topic, or post.

**Auto Push**
Auto Push is what makes this plugin stellar. When you create a new post, your post's title, link, and featured image *(Note: featured image will be used for the custom image with Chrome's notifications)* will be sent to all of your subscribed readers. That's it. Really. You don't have to do anything else. (It works just like magic.) When enabled, an auto push override check box is also placed on your post's admin page. If for some reason you do not want a notification to go out for that post, just check the box when publishing.

**Manual Post Mode**
With *Auto Push* disabled, a checkbox will appear just above the Publish button on your post page. Simply check the box *Send Notification with Roost* and a notification will be sent when publishing.

**Send Manual Alert**
You can send a manual notification to all subscribed users by entering your message text in the "Notification Text" box and a link in the "Notification Link" box.

**Roost Analytics & Roost JS**
Detailed metrics are provided in the dashboard. These metrics include subscribes, notifications sent, reads, and more.

**Advanced Settings - Use Segmented Send**
Use WordPress categories to target notifications based on Roost segments. ***DISCLAIMER*** You must be assigning users segments to send notifications. If not, notificaitons will not be sent to your subscribers.

**Advanced Settings - Use Custom Script**
In some cases, we’ll ask you to use a custom script. Paste it in the text area shown. (Enabling this feature will not include the normal Roost.js)

== Frequently Asked Questions ==

= What does Roost cost? =
Roost offers custom rate plans determined by the features you use, number of notifications per month sent, and depth of segmentation. Plans start at $399 / mo. Contact Roost at [goroost.com](https://goroost.com/#section-schedule).

= Is it really this easy to use push notifications in Chrome, Android, and Safari on my site? =
Yup! Cool right?

= Do I need and Apple Developer Account or Google Developer account? =
Nah. We've got you covered.

= Do you support Firefox web push? =
Sure do!

= Do my readers / subscribers have to create an account with Roost? =
Nope. Just you.


== Screenshots ==

1. Subscribe to Chrome notifications in Android! Receive Chrome notifications on Android! (OMG! LOL! IKR! FTW! LOLZ.)
2. Chrome dialog in Mac OS X.
3. Opt-in on Chrome in Windows. (Wait... What? We know right? Windows! #Boom!)
4. Notification being delivered on Chrome in Mac.
5. Chrome notification tray on OS X.
6. Subscription control from Chrome notification tray.
7. Easy for visitors to subscribe to your site in Safari. Easy peasy!
8. Notifications will be delivered in the top-right corner of your subscribers screen. (Safari)
9. Log in to your Roost account.
10. Roost plugin from the WordPress dashboard showing analytics.
11. Powerful control on how your visitors can subscribe and how your notifications are sent.

== Changelog ==
= 2.5.0 =
* Updates to required service worker / html files
* File directory structure

= 2.4.0 =
* Bugfix - Change API for notifiaction calls
* Text change on sign in page (watch for new pricing!)
* Updates to required service worker / html files
* Do not auto gen files (legacy support)
* Remove old uninstall script (legacy support)
* New API endpoint supports featured images

= 2.3.9 =
* Removed Upgrade notice

= 2.3.8 =
* Bugfix - Servers with strict PHP throwing errors on number_format() (Used on admin page)
* Added upgrade notice for end-of-life free plans
* Code Cleanup

= 2.3.7 =
* Added support for notifications on all post types (custom included) with an "Allow All Post Types" setting! Woo! -- With this selected Auto Push will be disabled and notifications will only be triggered if marked as such when publishing on the post page.
* Bugfix - Changed name on Roost save settings action to avoid namespace collision
* Bugfix - Only show custom Roost headline on post page if applicapble
* Code Cleanup

= 2.3.6 =
* MAJOR - Bugfix - Must upgrade to support new releases of Chrome (m45+)

= 2.3.5 =
* Compatible with PHP < v5.3

= 2.3.4 =
* Added setting to enable/disable featured images on notifications
* Bugfix - Added check to prevent JavaScript error on clients with non-support push browsers
* MAJOR - Bugfix - Old Chrome files need be present until after ServiceWorker upgrade takes place
* Bugfix - Prevent multiple ServiceWorkers from registering

= 2.3.3 =
* Ding-a-ling! [The Bell is here!](https://goroost.com/blog/bell-keep-users-loop) - Roost's on-site notifications
* Support for custom images on Chrome notifications
* MAJOR - Chrome files dynamically served - WP friendly fix (Previous versions may have fallen victim to directory and filesystem permissions)
* Bugfix - Prevent invalid login on multi-site selection
* Code Cleanup

= 2.3.2 =
* MAJOR - Bugfix - Chrome files not being regenerated after plugin upgrade

= 2.3.1 =
* Changed messaging for HTTPS check to a notice not warning (Was throwing false negatives)
* Added safety net for accidental Advanced Settings checkboxes

= 2.3.0 =
* Chrome Push Notifications Now Available!!! (#Boom! So much win... This feels good.)
* Small UI tweaks
* Corrected calculation for current subscribers in dashboard
* Remove deprecated settings
* Removes SSO option (May come back...)
* Switched to use permalink in url instead of post ID (We know... Should have been awhile ago.)
* *Palm to face* fixes

= 2.2.0 =
* Ability to exclude posts published in specified categories from automatically sending notifications
* Send notifications when updating a post
* Can automatically use WordPress categories to target notifications based on Roost segments (You must be assigning users segments to send notifications.)
* Use custom script instead of standard Roost JavaScript (Custom script provided by Roost.)
* Code Cleanup
* Bugfixes

= 2.1.8 =
* Fixed (encoded) URL that was causing W3C validation error
* Removed outdated metrics from the Roost dashboard inside WP Admin

= 2.1.7 =
* Major updates to roost.js (Includes performance boost and new APIs)
* Custom headline field in post screen moved to a meta box instead of injected textfield

= 2.1.6 =
* Added 30-day to Roost stats on graph (Yay for history!)
* Bugfix - Fixed bug that prevented notifications for Scheduled Posts
* Bugfix - Show custom headline only when logged into Roost
* 'roost' prefixed some classes / ids
* Hid custom post meta fields on post pages
* Code Cleanup

= 2.1.5 =
* Control for Prompt - auto prompt, after number of visits, off, on button / link click
* Added custom headline option for notification when publishing a post
* Cleared for takeoff with WordPress v4.0
* Bugfix - Roost JS now only loaded if logged into plugin.
* Bugfix - Total notifications sent in dashboard now really total notifications *Palm to Face*
* Code Cleanup

= 2.1.4 =
* Bugfix - Fixed bug that prevented stats from displaying when WordPress admin accessed via HTTPS
* Bugfix - Fixed bug that showed blank stats / setting screen on invalid login attempt
* Code Cleanup

= 2.1.3 =
* RoostJS now served from CDN (BAM! Blazing fast! You didn't see that one did you?)
* Removed mobile app setting
* Updated API URLs and references to goroost.com (Go Go Gadget Roosters... Or something like that.)
* Fixed bug when manual sending notification to eliminate multiple messages.

= 2.1.2 =
* Fixed bug that may have prevented new sites to Roost from being able to send manual notifications from the dashboard
* Fixed bug with charts not loading correct data on tab click

= 2.1.1 =
* Fixed bug that prevented Roost admin screen from showing in PHP versions older than 5.3.0
* Some more code cleanup

= 2.1 =
* Added special support for bbPress subscriptions
* Charts!!! Lots of Charts...
* Plugin redesign - Uses tabs to organize sections
* Changed how the Roost JS script is loaded - Now loading asynchronously
* Included option to send push notifications when publishing posts without using the "Auto Push" feature
* Simplified account creation (in the plugin and on Roost website) and included uploading a logo and naming your site - Auto-login on return
* Added support for signing into the plugin with Facebook, Twitter, and Google+ (SSO)
* Removed upgrade path from v1.0 - Should not impact anyone at this point
* Changed logo and username by log out (in the top right corner) to account email - Context makes more sense with multi-config accounts
* Fixed bug that removed Notification Override setting when doing a Quick Edit
* Put in null check when sending notifications - Prevents sending null alert with can cause errors
* Code cleanup

= 2.0.5 =
* Now supports Auto Push when posting from the WordPress mobile app and by email via Jetpack by WordPress.com
* New first time login screen
* Roost API check on activation to see if URL is reachable
* Code cleanup

= 2.0.4 =
* Changed hard limit to soft character limit on manual notifications
* Restricted notifications to a "post" post type only
* Added settings link on plugin page
* Roost stats now cached to improve admin page performance
* Fixed bug that caused resending notifications when using "Quick Edit" to modify posts
* Removed shortcodes
* Code cleanup

= 2.0.3 =
* Scheduled Notifications can now Trigger Alerts
* Fixed Stats Error on First Login
* Character Count on Manual Notifications

= 2.0.2 =
* Corrected Total Time On Site calculation
* Fixed additional bug with character encoding
* Adjusted styling on admin pages

= 2.0.1 =
* Fixed bug that prevented notifications from sending

= 2.0 =
* Automatically activate Safari Web Push with plugin
* Simplified interface
* Pulling All-Time stats for your Roost account into Wordpress Dashboard
* Added a Roost Push override on post pages to prevent notification
* Simplified install process - Plugin no longer creates it's own table
* Added support for featured images from posts (For new Roost app - Soon in Apple App Store and Google Play)
* Settings now all controlled from server
* Added Roost Bar shortcode
* Fixed character encoding issue on auto push notifications

= 1.1 =
* Added support for Safari Web Push (Desktop Push Notifications) on OS X Mavericks
* Prefixed functions to avoid conflicts
* Updated settings to be removed on uninstall instead of deactivation
* Included Roost JS on every page via wp_footer() - (Needed for Roost analytics such as page views and time on site)

= 1.0 =
* Initial Release

== Upgrade Notice ==
= 2.4.0 =
* MAJOR - Bugfix - Change API for notifiaction calls

= 2.3.9 =
* Removed Upgrade Notice

= 2.3.8 =
* Minor Bugfix - Upgrade Notice

= 2.3.7 =
* Added ability to send for all post types. Custom post types included.

= 2.3.6 =
* MAJOR - Bugfix - Must upgrade to support new releases of Chrome (m45+)

= 2.3.5 =
* Support for older versions of PHP ( Compatible with PHP < v5.3 )

= 2.3.4 =
* MAJOR - Bugfix - Old Chrome files need be present until after ServiceWorker upgrade takes place.

= 2.3.3 =
* The Bell is here!!! & MAJOR - Chrome files dynamically served - Eliminates chance of file / dir permission errors.

= 2.3.2 =
* MAJOR - Bugfix - Chrome files not generated on plugin upgrade.

= 2.3.1 =
* Minor - UX tweaks - HTTPS check now non-blocking notice not warning.

= 2.3.0 =
* Chrome Push Notifications Now Available!!! (#Boom! So much win... This feels good.)

= 2.2.0 =
* Exclude categories from Auto Push - Send notification on post updates - Targeted sending with Roost segments - Custom script option

= 2.1.8 =
* Fixed URL causing W3C validation error -- removed invalid metrics in dashboard

= 2.1.7 =
* Major updates to roost.js (Performance updates and new APIs)
* Moved custom headline field to meta box on post screen

= 2.1.6 =
* Fixed bug with scheduled posts

= 2.1.5 =
* Added prompt control and option for custom text on notifications when publishing a post. Also, pre-check compatible with WordPress v4.0

= 2.1.4 =
* Bugfix - Fixed bug that prevented stats from displaying when WordPress admin accessed via HTTPS

= 2.1.3 =
* RoostJS now served from CDN (BAM! Blazing fast! You didn't see that one did you?)
* Removed mobile app setting

= 2.1.2 =
* Fixed a bug when sending manual notifications from the dashboard and with charts

= 2.1.1 =
* Fixed bug that prevented Roost admin screen from showing in PHP versions older than 5.3.0

= 2.1 =
* Charts and Graphs! bbPress support! Plugin redesign! Other Major Updates! Does it get any better?

= 2.0.5 =
* Now supports Auto Push when posting from the WordPress mobile app and by email via Jetpack by WordPress.com

= 2.0.4 =
* Limited Auto Push to 'post' types only. Fixes situation with other plugin's custom post types triggering notifications.

= 2.0.3 =
* Now with support for Scheduled Notifications! Bam! Oh, and some bugfixes and other cool stuff.

= 2.0.2 =
* Corrected Total Time On Site calculation
* Fixed additional bug with character encoding
* Adjusted styling on admin pages

= 2.0.1 =
* Fixed bug that prevented notifications from sending

= 2.0 =
* Bug fixes and analytics. Simplified interface and design update to match Wordpress 3.8 design.
