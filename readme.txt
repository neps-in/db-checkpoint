# DB Snapshot #
**Contributors:       Gary Kovar
**Donate link:        https://bethematch.org/
**Tags:               database, wp-cli
**Requires at least:  4.4
**Tested up to:       4.6.1
**Stable tag:         0.1.0
**License:            GPLv2
**License URI:        http://www.gnu.org/licenses/gpl-2.0.html

Extends WP-CLI to include a db checkpoint for development purposes.

## Description ##

If [WP-CLI](http://wp-cli.org/ "WP-CLI") is available this plugin adds 2 new commands.
 `wp dbsnap` creates a snapshot of your database.  No fuss, no muss...
 `wp dbsnapback` restores the snapshot.  That simple...

If you need 2 different checkpoints you can name them
`wp dbsnap db-before-i-do-something-sketchy`
`wp dbsnapback db-before-i-do-something-sketchy`

## Installation ##

### Manual Installation ###

1. Upload the entire `/db-checkpoint` directory to the `/wp-content/plugins/` directory.
2. Activate DB CheckPoint through the 'Plugins' menu in WordPress.

## Frequently Asked Questions ##
= Where are the db exports stored? =
wp-content/checkpoint-storage/

## Changelog ##

### 0.1.0 ###
* First release