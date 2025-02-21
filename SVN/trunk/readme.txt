=== Change Admin Email ===
Contributors: johndeebdd
Donate link: https://generalchicken.guru/
Tags: rollback, email, admin_email
Requires at least: 4.9
Tested up to: 5.6
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: trunk

== Description ==
This plugin allows an administrator to change the "site admin email", without sending a confirmation email. This can be useful for testing purposes, localhost setups, or any other situation where outbound email is disabled. A new "feature" of WordPress 4.9 is that the administrator cannot change the site admin email without outgoing email setup on the server, and recipient email credentials. This plugin restores the admin's ability to change this setting without sending a confirmation email. Note that the "site admin email" is the global email used for admin purposes on the site. It is the "from" address when the site sends an email. The "site admin email" may be different from the administrator's personal user email, which is associated with the user.

## Usage
Once activated, an administrator can change the admin email from the Settings >> General page.

== Installation ==
Clone or copy the file into your plugins directory, then activate the plugin from the admin menu. No other settings required.
