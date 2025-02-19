=== Mailman ===
Contributors: ZendyLabs, whizdev
Tags: email, smtp
Requires at least: 3.9.1
Tested up to: 5.5.1
Stable tag: 1.0.19
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Mailman improves deliverabilty of emails sent by your website by using SMTP rather than the built-in Wordpress PHP mailer.

== Description ==

Mailman: the friendly email delivery system for Wordpress. Mailman makes sure all the email messages sent by your Wordpress site are delivered successfully by using SMTP rather than the built-in Wordpress PHP mailer.

== Installation ==

1. Upload the `zendy-mailman` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enter your SMTP info in the plugin settings; from your Wordpress dashboard menu, go to `Settings` > `Mailman`

== Frequently Asked Questions ==

= Where do I find my SMTP settings? =

Your web host (or email provider) will provide that for you. Note: common SMTP settings are available from the plugin settings screen.

= What does Mailman do? =

Mailman increases the delivery rate of emails sent by your Wordpress site (like contact form notifications and new subscriber alerts). In other words, the emails sent by your Wordpress website are less likely to be flagged as spam.

= How does Mailman work? =

On shared hosting servers (most Wordpress sites are on shared hosting servers) the Wordpress mailer often gets flagged as spam or even blacklisted. Mailman uses SMTP mail instead of relying on the Wordpress mailer.

= What use cases and third-party plugins have been tested? =

* Wordpress email notification: new user registration, comment notification, etc.
* Gravity Forms plugin

== Screenshots ==

1. The settings page
2. The testing & troubleshooting page
3. The FAQ, including settings for some of the most popular email providers 

== Changelog ==

= 1.0.21 =
* Meta: Committing from new whiz.dev profile

= 1.0.20 =
* Meta: Updated documentation
* Meta: Zendy is closed - moving plugin to whiz.dev

= 1.0.19 =
* Meta: Changed author and plugin name
* Meta: Tested for WordPress 5.5.1

= 1.0.18 =
* Meta: Changed plugin URL link

= 1.0.17 =
* Meta: Tested for WordPress 4.5.1

= 1.0.16 =
* Meta: Tested for WordPress 4.3

= 1.0.15 =
* Meta: Tested on WP 4.2.2
* Meta: Updated plugin meta row
* Meta: Removed premium support option - just email us if you see a bug in the plugin :)

= 1.0.14 =
* Meta: Updated plugin links to new zendy website

= 1.0.13 =
* Meta: Added section comments to style.css

= 1.0.12 =
* Meta: Tested for WordPress 4.1

= 1.0.11 =
* Meta: Fixed version number error

= 1.0.10 =
* Meta: tested WP 4.0

= 1.0.9 =
* Meta: updated FAQ

= 1.0.8 =
* Meta: tested plugin on Wordpress 3.9.2
* Meta: added link to Zendy Labs HQ documentation on plugin FAQ
* Meta: added GoDaddy Mail settings to documentation

= 1.0.7 =
* Meta: added Hotmail/Outlook settings to documentation
* Meta: added Yahoo! Mail settings to documentation
* Fix: fixed a display error where the chosen type of encryption was not always displayed properly.

= 1.0.6 =
* Fix: fixed errors on activation on some nginx installs
* Meta: Removed change.log file; all changelog info is now in readme.txt

= 1.0.5 =
* Meta: changed stable tag
* Fix: changed end of file to attempt to fix a bug on activation on some nginx installs

= 1.0.4 =
* Meta: removed screenshots from plugin files; they are now in the Wordpress plugin subversion repository, in the /assets folder

= 1.0.3 =
* Meta: changed stable tag number

= 1.0.2 =
* Meta: changed description of Wordpress plugin for Wordpress.org plugin directory

= 1.0.1 =
* Meta: added screenshots for Wordpress.org plugin directory

= 1.0 =
* Initial release
* Feature: all emails sent via built-in Wordpress mailer will use SMTP instead of PHP mail.
* Feature: test your plugin SMTP settings by sending email via the test form.
* Feature: FAQ, including settings for some of the most popular email providers




