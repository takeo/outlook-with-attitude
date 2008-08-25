# OWAwesome
by Toby Sterrett

toby.sterrett@microsoft.com


### OVERVIEW
This userscript is an attempt to make Outlook Web Access bearable, and possibly even awesome. I'm starting with some much needed keyboard navigation. It is currently built using jQuery and is still pretty ghetto. The injection of jQuery uses some stuff that only works on Greasemonkey & Firefox, although I will work to figure out how to make it work in Fluid for some killer SSB action.

Make sure you update the @include with your OWA address

### WHAT IT DOES
To start it adds some keyboard navigation, a la Gmail.

#### Main tab navigation:

* 1 - goes to mail inbox
* 2 - goes to calendar
* 3 - goes to contacts

#### On-page navigation:

* f - focus the search box
* j - goes down one record of a table
* k - goes up one record of a table
* l - goes to the next page
* h - goes to the previous page
* x - selects a record's checkbox
* d - clicks the Delete button
* n - clicks the New button
* u - clicks the Junk button†
* r - clicks the Reply button†
* a - clicks the Reply to All button†
* w - clicks the Forward button†
* esc - clicks the Close button
* enter - opens the currently highlighted record

† Mail tab specific

#### To Do

* Make it work on Fluid
* Embed jQuery in the script instead of linking to jquery.com
* Autocheck for mail every few minutes
* Notification of new messages
* Make shortcuts more robust, such as reusing letters for different things when in different sections
* Overlay with the shortcuts for quick reference
* More functionality coverage in the shortcuts
* A new logo