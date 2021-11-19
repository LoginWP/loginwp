=== LoginWP (Formerly Peter's Login Redirect) Pro ===
tags: login, logout, redirect, admin, administration, dashboard, users, authentication
Requires at least: 4.6
Tested up to: 5.8
Stable tag: 4.0.0.6
License: GPL-2.0+

Redirect users to different locations after logging in and logging out.

== Description ==
Define a set of redirect rules for specific users, users with specific roles, users with specific capabilities, and a blanket rule for all other users. Also, set a redirect URL for post-registration.

== Frequently Asked Questions ==
See the website for more info https://loginwp.com/

== Changelog ==

= 4.0.0.6 =
* Added LearnDash Enrolled Course and User Group redirect conditions.
* Added WooCommerce Purchased Product, Purchased Product Category, Active User Subscription, Active Membership Plan redirect conditions.
* Added MemberPress Subscribed Membership redirect condition.
* Added Restrict Content Pro Has Membership redirect condition.
* Added LifterLMS Enrolled Course and Enrolled Membership redirect conditions.

= 4.0.0.5 =
* Added escaping to url fields in redirection UI
* Added https://yoursite.tld/?loginwp_link_redirect=true for triggering login redirection.

= 4.0.0.4 =
* Added MemberMouse integration.
* Prefixed class exist check with backslash.
* Fixed broken link to license page from admin notice.

= 4.0.0.3 =
* Fixed multisite installation bug.
* Fixed issue where database migration didn’t work.

= 4.0.0.2 =
* Fixed bug where redirect_to_front_page function returned null.
* Improved Restrict Content Pro support.

= 4.0.0.1 =
* Fixed issue where placeholders wasn't getting saved as url.
* Improved BuddyPress/BuddyBoss support.

= 4.0.0.0 =
* The genesis
