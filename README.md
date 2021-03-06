[![Donate to help me out](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=LSEF6AFFPFLU4&lc=US&item_name=PitaJ%27s%20open%20source%20development&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted "Donate to help me out")

#nodebb-plugin-calendar

![Full screen image](http://i.imgur.com/k6umK8N.png)

[**More images here**](http://imgur.com/a/7qQAV)

This plugin adds a *super cool* site-wide calendar to NodeBB.

##Installation

[Guide for NodeBB versions 0.6.x and 0.7.x](https://community.nodebb.org/topic/4401/nodebb-plugin-calendar-fully-featured-calendar-plugin-for-nodebb-testers-needed/10): 

1. Open a command window in the NodeBB directory 
2. Run `npm remove nodebb-plugin-calendar`
2. Navigate to the node_modules directory (cd node_modules)
3. Delete the nodebb-plugin-calendar directory with del nodebb-plugin-calendar or rm -r nodebb-plugin-calendar
4. Clone the master branch of the git repository git clone https://github.com/pitaj/nodebb-plugin-calendar
5. Navigate to the nodebb-plugin-calendar directory with cd nodebb-plugin-calendar
6. Install npm dependencies with the command npm install
Those commands should install it correctly. It should then be visible in the ACP (maybe after a restart) to be activated.

Other options (only for older NodeBB versions):

 1.  Install the plugin through the ACP
 2.  Run `npm install nodebb-plugin-calendar` in the root directory of the NodeBB install

I haven't added the newest version to npm yet because I'm still ironing out some bugs.

Don't forget to restart after installing the plugin. After installing, a calendar icon should appear next to the rest in the header menu

##Configuration
Before do anything with the Calendar, make sure you have the correct settings set up in the ACP plugin setting page. It will tell you what to do.

After you've saved the settings in the plugin page, make sure you configure the category you selected for events to match the permissions for each user and group in the plugin settings. This will eventually be automated.

Note: If you don't know the id# of the category you want the events to be posted in, edit something about the event, and when you click save, the alert will tell you the event id#. Then you can change back whatever you did.

##Features
* Synchronization between different users' activities on the Calendar page
* Full permissions system separate from that of the main site
* Individual event permissions for viewing and editing of the event
* Public events (even guests can see them)
* Simplistic, graceful UI (infinite scroll OMG!)
* Comments system using NodeBB topics
* Response system for easy user responses
* Click a day on the calendar to select it, and show its events in the sidebar
* Click an event in either the sidebar or the calendar to show its details in the sidebar
* Jump to year and month from the fields above the Calendar
* Configurable automated notifications for upcoming events
* Awesome new interface, with mobile support!
* Support for (optionally) using [arasbm's Whoisin plugin](https://github.com/arasbm/nodebb-plugin-whoisin) to power the response system

####In The Works

* iCal export
* Event permalinks on calendar page

## Suggestions? Encountered a Bug?
Please submit all feature requests and bugs with the [Issue tracker at Github.](https://github.com/pitaj/nodebb-plugin-calendar/issues) Thanks
