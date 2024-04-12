# eq-auth

Contributors: (this should be a list of WordPress.org user IDs)

Tags: comments, spam

Requires at least: 4.5

Tested up to: 6.5

Requires PHP: 5.6

Stable tag: 0.1.0

License: GPLv2 or later

License URI: [https://www.gnu.org/licenses/gpl-2.0.html](https://www.gnu.org/licenses/gpl-2.0.html)

A plugin for connecting to the eQual framework.

## Description

This plugin provides integration with the eQual framework for user authentication and management. It allows users to log
in to WordPress using eQual credentials and synchronizes user data between WordPress and eQual.

## Features

- **Seamless User Login:**
  Integration with eQual framework enables users to log in to WordPress using their eQual credentials, enhancing user
  experience.

- **User Data Synchronization:**
  The plugin synchronizes user data between WordPress and eQual, ensuring consistency and accuracy across platforms.

- **New User Registration:**
  Automatically syncs new user registrations with eQual to maintain a unified user database.

- **Password Reset Integration:**
  Allows users to reset their passwords in WordPress, updating the changes in eQual for enhanced security.

- **Profile Update Sync:**
  Updates user profiles in eQual when changes are made in WordPress, ensuring data integrity and consistency.

- **Smooth Logout Process:**
  Clears access token cookies upon user logout from WordPress, enhancing security and privacy.

## Hooks and Filters used

- wp_login
- user_register
- password_reset
- profile_update
- wp_logout

## Installation

1. Upload `eq-auth.php` to the `/public/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

## Frequently Asked Questions

### How do I integrate eQual authentication with WordPress?

Once the plugin is installed and activated, users will be able to log in to WordPress using their eQual credentials. The
plugin synchronizes user data between WordPress and eQual to ensure a seamless authentication experience.

### Can I customize the integration settings?

Currently, the integration settings are not customizable through the WordPress admin interface. However, you can modify
the plugin code directly to adjust the integration behavior according to your requirements.

## Changelog

### 0.1.0

- Initial release of the plugin.

## Upgrade Notice

### 0.1.0

- This version introduces basic integration with the eQual framework for user authentication.
