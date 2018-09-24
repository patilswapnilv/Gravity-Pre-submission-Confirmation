===Gravity Pre-submission Confirmation===
Contributors:      patilswapnilv
Plugin Name:       Gravity Pre-submission Confirmation
Plugin URI:        https://wordpress.org/plugins/gravity-pre-submission-confirmation
Tags:              gravity forms,confirmation, pre-submit, gravity forms extension, pre-submit confirmation
Author URI:        http://swapnilpatil.in
Author:            patilswapnilv
Version:           1.0.0
Donate link:       http://swapnilpatil.in/contribution
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 3.5
Tested up to:      4.9.8
Stable tag:        1.0.2


A WordPress plugin which adds a pre-submission confirmation page to your Graviy forms where users can preview their entered data before they submit it.

== Description ==
This is an easy way to add a quick pre-submission confirmation page to your forms where users can preview the information entered in the form before they submit it. Gravity Forms does not provide any way to do this by default; however, with this plugin and a few simple form configuration instructions, you’ll have pre-submission confirmations working like magic!

###Features

* Adds a quick pre-submission confirmation page to Gravity Forms.
* No configurations; Just Plugin & Play!

== Installation ==

= For automatic installation: =
The simplest way to install is to click on 'Plugins' then 'Add' and type 'Gravity Pre-submission Confirmation' in the search field. Click install then Activate.

= For manual installation 1: =

1. Download the plugin zip file from [WordPress Plugin repo](https://wordpress.org/plugins/gravity-pre-submission-confirmation)
2. Login to your website and go to the Plugins section of your admin panel.
3. Click the Add New button.
4. Under Install Plugins, click the Upload link.
5. Select the plugin zip file (gf-confirmation.x.x.x.zip) from your computer then click the Install Now button.
6. You should see a message stating that the plugin was installed successfully.
7. Click the Activate Plugin link.

= For manual installation 2: =

1. You should have access to the server where WordPress is installed. If you don't, ask your system administrator to help you out.
2. Copy the plugin zip file (gravity-pre-submission-confirmation.zip) up to your server and unzip it somewhere on the file system.
3. Copy the "gravity-pre-submission-confirmation" folder into the /wp-content/plugins directory of your WordPress installation.
4. Login to your website and go to the Plugins section of your admin panel.
5. Look for "gf-confirmation" and click Activate.

=Usage=

1. Activate the plugin from Admin > Plugins menu.
2. Add a page break in your gravity form at the end of the form for the pre-submission confirmation. You can do this using the Page Break field type.
3. Add an HTML field from the “Standard Fields” section.
4. THe easiest way is to add {all_fields} to this section. But if you need more customizatios, go ahead and select the HTML field for editing. The “Content” setting of this field now supports all merge tags like {Name (First):4}, {Question:5}.
5. Update the Gravity form.

== Screenshots ==
1. Page break
2. HTML Field


== Changelog ==

= Version 1.0.0 =
    Initial Release.

= Version 1.0.2 =
    Added support for PHP 7 and made translation ready.

 = Version 1.0.3 =
    Tested for WordPress 4.9.8


== Upgrade Notice ==

    = 1.0.0 =
    This is the first stable release. Details if necessary would be provided from the next version onwards.

== Frequently Asked Questions ==
1. Where are the options to add confirmation? I could find any menu option.
    The plugin does not add any menu options, or any knid of options as such. All you need to do it add a Page break to your form at the end, and add a HTML field with the gravity form html elements, OR simply add {all_fields} to eco all the fields within the entry.

2. How do I report a bug?
    Though I have tested the plugin as much as I could, but in-case you come across a bug, there are two ways to report it.
    First you can submit a issue via [github](https://github.com/patilswapnilv/gf-confirmation).
    OR
    You can let me know about it via the support forum.

== Donations ==
More than any donations, Contribution will be more helpful. Hence, Contributors are always welcome.
To contribute, just send a pull request over the [Github repo](https://github.com/patilswapnilv/gf-confirmation)
