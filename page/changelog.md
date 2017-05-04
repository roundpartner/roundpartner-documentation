#Change Log
RoundPartner is constantly being updated to ensure it has all the features required to keep a window cleaning business running smoothly. This page highlights some of the features and improvements we have made.

You can send us a feature request or report a bug using the form at the bottom of this page.

## 30th April 2017
### New Features
- Added Go Cardless Integration
- Added importing customers with iCal Calendar
- New [CMS Micro Service](https://github.com/thomaslorentsen/go-cms) to deliver content pages
- New [Go Cardless Micro Service](https://github.com/roundpartner/go-cardless-events) to track go cardless events

### Improvements
- Only display Extras column when used
- Improved stability and monitoring of Rackspace services
- Improved error reporting
- Help pages are now pulled from [Documentation Repo](https://github.com/roundpartner/roundpartner-documentation) by [CMS Micro Service](https://github.com/thomaslorentsen/go-cms)

## 1st March 2017
### Improvements:
- Store sessions into Redis cache
- Disable pagination when viewing jobs by day

## 1st February 2017
### New Features:
- Packages can now recur automatically

### Improvements
- Changed how Jobs Pending Report gets its data

## 5th December 2016

### New Features:


*   Report section has been rebuilt with payments and jobs report that can be filtered


### Improvements:

*   Jobs that are overdue are highlighted on the rounds details page
*   Jobs can be marked as completed on the rounds details page
*   Formatted address on round detail pages
*   Added customer telephone number to mobile job listings
*   Added a print button to the expenses page
*   Added a button to create new prospects on the customer listing page

## 12th September 2016

### New Features:

*   <span style="line-height:21.75px;">Jobs can be ordered by postcode by selecting it from the options in Account -> Customise -> Default job listing order</span>

### Improvements:

*   <span style="line-height:21.75px;">Month of the year is displayed on calendar view</span>
*   <span style="line-height:21.75px;">Complete multiple jobs more than once on job listings</span>
*   <span style="line-height:21.75px;">Complete multiple payments more than once on the payments listings</span>
*   <span style="line-height:21.75px;">Improved Job spreadsheet generated in likeness to the job listings</span>
*   General improvements and optimisation

## 18th July 2016

### New Features:

*   <span style="line-height:21.75px;">You can now download customer and booking data by going to My Account in the top left navigation menu, under export/import you can select All Data.</span>

### Improvements:

*   <span style="line-height:21.75px;">Updated version of pdf file generator</span>
*   <span style="line-height:21.75px;">Improvements to background processing of jobs such as invoice generation and back ups</span>
*   <span style="line-height:21.75px;">Jobs are ordered by Street and Town by default</span>
*   <span style="line-height:21.75px;">Migrated RoundPartner project to [GitHub](https://github.com/)</span>
*   <span style="line-height:21.75px;">Fixed customer pages not being displayed correctly after a job has been deleted</span>

## 26th September 2014

### Improvements

*   <span style="line-height:21.75px;">Fixed payments in customer screen limited to the last 15 payments</span>
*   <span style="line-height:21.75px;">Renewed SSL key</span>
*   <span style="line-height:21.75px;">Patched servers with Shellshock security vulnerability fix</span>

## 3rd August 2014

### New Features

*   <span style="line-height:21.75px;">Add multiple jobs to a round</span>
*   <span style="line-height:21.75px;">Export a round to spreadsheet</span>

### Improvements

*   <span style="line-height:21.75px;">Show notes on the planner when pressing a job on the locked planner page</span>
*   <span style="line-height:21.75px;">Allow unmarking a job as paid on the job update screen</span>
*   <span style="line-height:21.75px;">Navigating to /mobile forces the mobile site to be active on any device</span>
*   <span style="line-height:21.75px;">Fixed broken link to notes on teams page</span>
*   <span style="line-height:21.75px;">Added job frequency and unpaid count to exported spreadsheets</span>
*   <span style="line-height:21.75px;">Fixed deleted jobs not being deleted from mobile web app</span>
*   <span style="line-height:21.75px;">Added new payment methods</span>
*   <span style="line-height:21.75px;">Fixed job ordering when viewing by team</span>
*   Multiple performance and security improvements

## 19th May 2014

### Improvements

*   <span style="line-height:21.75px;">Fixed broken add street link on dashboard</span>
*   <span style="line-height:21.75px;">Fixed search error when filtering by team</span>

## 20th April 2014

### Improvements

*   <span style="line-height:21.75px;">Added job frequency to job excel report</span>
*   <span style="line-height:21.75px;">Allow viewing job worth report by week</span>
*   <span style="line-height:21.75px;">Added configuration option to display post code in addresses</span>
*   <span style="line-height:21.75px;">Fixed weekly job worth report on dashboard not displaying total for all jobs for the last week of the month</span>
*   <span style="line-height:21.75px;">Fixed error when creating a job with a deleted address</span>

## 9th April 2014

### Security Update

Our servers were checked for the [Heart Bleed Security Vulnerability](http://heartbleed.com/) and were found to not be affected.

## 31st March 2014

### New Features

*   <span style="line-height:21.75px;">Schedule jobs by week of the month (week 1, week 2, week 3, etc)</span>
*   <span style="line-height:21.75px;">Added customers in credit report in reports section</span>

### Improvements

*   <span style="line-height:21.75px;">Improvements to customer import functionality</span>
*   <span style="line-height:21.75px;">Fixed error in firefox when toggling widget menus</span>
*   <span style="line-height:21.75px;">Fixed one off jobs being rescheduled after completion</span>
*   <span style="line-height:21.75px;">Hide package details from crew members</span>
*   <span style="line-height:21.75px;">Fixed customer update button appearing after an account had expired</span>
*   <span style="line-height:21.75px;">Fixed double encoding on notes page</span>
*   <span style="line-height:21.75px;">Fixed typo on config page</span>
*   <span style="line-height:21.75px;">Other smaller improvements and optimisation</span>

## 4th February 2014

### New Features

*   <span style="line-height:21.75px;">Crews/Teams (Stage 2) (beta) - Members can now create teams and assign rounds/users to a team. Users assigned to a team will automatically view their assigned rounds in the job, payment and calendar views</span>

### Improvements

*   Order is remembered when dragging jobs on the planner
*   Major changes to user access and authentication
*   Allow purchasing services from the package screen
*   Customer name is displayed in planner if available
*   Added total price to each day on planner
*   <span style="line-height:21.75px;">Adding payment method to expenses</span>
*   <span style="line-height:21.75px;">Invoices are now using cloud files (this will still require users to authenticate to download invoice)</span>
*   <span style="line-height:21.75px;">Performance enhancements to iCal feed. Feed is now updates once very 30 minutes</span>
*   <span style="line-height:21.75px;">Minor styling fixes and improvements</span>
*   <span style="line-height:21.75px;">Increased max allowed file size for George Import</span>

## 27th January 2014

### New Features

*   <span style="line-height:21.75px;">Teams/Crews (Stage 1)  (beta) - Members can now allow new users who can log in to their account.</span>
*   <span style="line-height:21.75px;">New completed job and payments reports displayed by month or week. You can view this from either the accounts report or the accounts summary and pressing the magnifying glass</span>
*   <span style="line-height:21.75px;">Added **Cancel Customer** to customer detail page. Allows a customer to be cancelled and reactivated</span>
*   <span style="line-height:21.75px;">Added **Delete Customer**, previously **Hide Customer**, which now deletes the customer, payments and jobs from the system</span>

### Improvements

*   <span style="line-height:21.75px;">Added button on new customer form to create a new address</span>
*   <span style="line-height:21.75px;">Added a link to next booking on rounds customer listing  
    </span>
*   <span style="line-height:21.75px;">Added notes field to create payment form on desktop site</span>
*   <span style="line-height:21.75px;">Ability to delete addresses and jobs from the edit sections</span>
*   <span style="line-height:21.75px;">Mobile detection updated (support for more mobiles)</span>
*   Fixed popups appearing when on a tablet making it difficult to complete or pay jobs
*   Fixed sorting by address showing customers multiple times if they have deleted addresses
*   Removed closing tag on mobile booking page which may caused an error on some older mobile devices
*   Invoices now supported in API
*   Fixed discounts not being applied in certain cases
*   Fixes to authentication code which may have prevented some accounts being created properly

## 16th January 2014

### New Features

*   <span style="line-height:21.75px;">Created new user type to allow accounts to have multiple users (alpha)</span>

### Improvements

*   <span style="line-height:21.75px;">Added payment method to mobile site when completing jobs</span>
*   <span style="line-height:21.75px;">Addresses and Jobs can be deleted (this will also delete bookings!)</span>
*   <span style="line-height:21.75px;">Fixed account expired message not appearing in quick links</span>
*   <span style="line-height:21.75px;">Removed hard limit of jobs in when viewing customer</span>
*   <span style="line-height:21.75px;">Removed pop up from calendar making it difficult to drag jobs</span>
*   <span style="line-height:21.75px;">Fixed error on mobile site after log out</span>
*   <span style="line-height:21.75px;">Exporting customers are now in spreadsheet format with a few additional columns</span>
*   <span style="line-height:21.75px;">Fixed customers not being imported if an invalid email was used when importing from George</span>

## 27th December 2013

### New Features

*   <span style="line-height:21.75px;">Added amount field to booking page on mobile to allow setting the amount paid by a customer</span>

### Improvements

*   Updated Yii Framework to a [newer version](http://static.yiiframework.com/files/CHANGELOG-1.1.14.txt) (includes some bug fixes)
*   Improvements to logging and error handling
*   Improvements and fixes to data deletion
*   Google map displayed on customer page if available
*   Added google map address search to customer add page
*   Added google map address search to add street page
*   Expenses can now have custom categories
*   Added customisation to accounts and job widgets on home page
*   <span style="line-height:21.75px;">Multiple bug fixes and improvements</span>

## 14th November 2013

### New Features

*   <span style="line-height:21.75px;">Added address auto completion functionality to prospects on desktop site.</span>
*   <span style="line-height:21.75px;">Added google map to prospect customer page when the new address look up functionality has been used</span>
*   <span style="line-height:21.75px;">Export on jobs and reports generate an Excel spreadsheet by default. The original CSV file can be downloaded using the arrow displayed on the button</span>

## 1st November 2013

### New Features

*   <span style="line-height:21.75px;">Added completed jobs report with export functionality</span>
*   <span style="line-height:21.75px;">Added expense summary report</span>
*   <span style="line-height:21.75px;">Job next due date displayed in round</span>

### Improvements

*   <span style="line-height:21.75px;">Improved sorting to customer section. You can now order customers by pressing the heading of the table</span>
*   <span style="line-height:21.75px;">Notes and Rounds added to API (to be rolled out into the mobile web app)</span>
*   <span style="line-height:21.75px;">Improvements to George import functionality (now supports setting jobs with monthly intervals)</span>
*   <span style="line-height:21.75px;">Updated quick links on home page with new links</span>

## 24th October 2013

### New Features

*   <span style="line-height:21.75px;">We have released a Beta version of our new offline mobile web app. Read more about it [here](https://roundpartner.co.uk/page/webapp).</span>
*   <span style="line-height:21.75px;">New API is available (contact us to learn how to integrate with it)</span>

## 9th October 2013

### New Features

*   Exporting jobs to Excel supported on jobs sections using the export button

### Improvements

*   <span style="line-height:21.75px;">Account summary now displays week of the year and date range</span>
*   <span style="line-height:21.75px;">Fixed account summary being calculated from Saturday instead of Monday</span>

## 27th September 2013

### Improvements

*   <span style="line-height:21.75px;">SSL Certificate updated (You may need to clear your cache for this to work)</span>
*   <span style="line-height:21.75px;">Searching for customers, job types and addresses now added to the jobs and payments section</span>
*   <span style="line-height:21.75px;">Cleaned up customer details section</span>
*   <span style="line-height:21.75px;">Cleaned up the rounds section</span>
*   <span style="line-height:21.75px;">Fixed calendar linking incorrectly after account expires</span>
*   <span style="line-height:21.75px;">Changes to authentication code (This is going to be used by the new teams functionality that is being built)</span>

## 12th September 2013

### New Features

*   Added Customise link to the Account drop down menu in the top right
*   Multiple job scheduled date can be updated from the job listing by pressing update button
*   Double clicking job in calendar goes to the update page (doesn't work on touchscreen)
*   Added restart job button in the customer detail section

### Improvements

*   <span style="line-height:21.75px;">Calendar Live feed page rebuilt to display subscribe button on iOS and feed details on other phones (Android)</span>
*   <span style="line-height:21.75px;">Multiple changes to rounds section of the site such as the addition of balances</span>
*   <span style="line-height:21.75px;">Under Customer in the Account drop down you can now hide the customer column from the booking and payments listings</span>
*   <span style="line-height:21.75px;">Prospects can now be updated from the mobile site</span>
*   <span style="line-height:21.75px;">Extras are now displayed in the customer detail section on the desktop and mobile site</span>
*   <span style="line-height:21.75px;">Fixed prospects showing in customer listings</span>
*   <span style="line-height:21.75px;">Package selection has been rebuilt and new 6 month plan has been added</span>
*   <span style="line-height:21.75px;">Fixed error occuring when updating rounds after an address had been deleted</span>
*   <span style="line-height:21.75px;">Fixed problem resulting in invoice never being generated in some instances</span>

## 2nd September 2013

### New Features

*   <span style="line-height:21.75px;">ICalendar feed to synchronise jobs to calendar app</span>
*   <span style="line-height:21.75px;">Add extras to a job on mobile site</span>

### Improvements

*   <span style="line-height:21.75px;">Added missing vat fields to mobile site</span>
*   <span style="line-height:21.75px;">Changed address listing to show addresses when narrowing down by road on mobile</span>
*   <span style="line-height:21.75px;">Fixed invoices not being generated</span>

## 21st August 2013

### New Features

*   <span style="line-height:21.75px;">You can now create prospective customers from the mobile site</span>
*   <span style="line-height:21.75px;">Prospective customers can be viewed from the customer section and using the **View Prospects** button on the desktop site</span>
*   A booking time can now be set from the job booking page
*   Booking time is shown throughout the system if a time is set
*   You can now set a preferred booking time from the job section

### Improvements

*   <span style="line-height:21.75px;">Added a lock button to the calendar to prevent moving jobs around when viewing</span>

## 14th August 2013

### New Features

*   <span style="line-height:21.75px;">Added mobile app icon to the mobile site which appears when creating a bookmark or adding to home screen (This may required recreating the bookmark to appear)</span>
*   <span style="line-height:21.75px;">When creating a job a preferred day can be selected. When jobs are scheduled using this, the day on the same week is set automatically.</span>
*   <span style="line-height:21.75px;">You can now set working days from the [Customise RoundPartner](/account/config) section. When jobs are scheduled only working days will be selected. Currently defaults to Monday to Friday</span>
*   <span style="line-height:21.75px;">Expenses can be created and viewed on the mobile site</span>
*   <span style="line-height:21.75px;">Added print button to the payment listing section</span>
*   <span style="line-height:21.75px;">Added a link to view payments within a round on the round section</span>

### Improvements

*   <span style="line-height:21.75px;">The scheduled date can now be edited on the mobile site</span>
*   <span style="line-height:21.75px;">The job interval type (weekly, monthly, etc) can now be set when creating a job on the mobile site</span>
*   <span style="line-height:21.75px;">More payment types added to the mobile site</span>
*   <span style="line-height:21.75px;">The date picker used when scheduling jobs now supports setting the time (this is part of a new feature that will allow booking a job in for a particular time)</span>
*   <span style="line-height:21.75px;">Fixed job/payment search not returning any results when searching for a round</span>
*   <span style="line-height:21.75px;">Fixed bug resulting in deleted addresses to appear in rounds section</span>
*   <span style="line-height:21.75px;">Rounds now require a name and current unnamed rounds can now be viewed</span>

## 9th August 2013

### New Features

*   <span style="line-height:21.75px;">Rounds can be deleted by selecting the round in rounds sections and using the delete button</span>
*   <span style="line-height:21.75px;">The default order for bookings and payments can be set in the [Customise RoundPartner](/account/config) section</span>

### Improvements

*   <span style="line-height:21.75px;">Job listings on mobile now highlight in red when job is overdue</span>
*   <span style="line-height:21.75px;">The scheduled data is now displayed in the mobile job listing</span>
*   <span style="line-height:21.75px;">Number of days remaining before account expires is displayed in the [accounts](/account/) section</span>
*   <span style="line-height:21.75px;">Fixed % symbol appearing next to VAT number</span>
*   <span style="line-height:21.75px;">Fixed pagination not being set correctly after customers and payments had been removed from the database</span>

## 8th July 2013

### Improvements

*   <span style="line-height:21.75px;">Payments not currently attached to an invoice can now be deleted</span>

## 2nd July 2013

### Improvements

*   <span style="line-height:21.75px;">Fixed deleted customers showing on mobile customer listings</span>
*   <span style="line-height:21.75px;">Added columns to the job tab on the customer view section to show if a job has been completed and or paid</span>

## 24th June 2013

### New Features

*   <span style="line-height:21.75px;">Addresses can be added to a round from the customer view page</span>
*   <span style="line-height:21.75px;">Jobs can be created from the customer view page</span>

### Improvements

*   <span style="line-height:21.75px;">Fixed addresses displaying in a random order in the round view when added through the add street feature</span>
*   <span style="line-height:21.75px;">Added checkbox to mark multiple jobs as paid on the payment listing</span>
*   <span style="line-height:21.75px;">Added checkbox to mark multiple jobs as completed on the jobs listing</span>
*   <span style="line-height:21.75px;">Completed jobs can no longer be moved on the calendar</span>
*   <span style="line-height:21.75px;">Added edit button to the payment tab when viewing a customer</span>
*   <span style="line-height:21.75px;">Job report on home page is displayed weekly and now shows work value</span>

## 2nd June 2013

### Improvements

*   <span style="line-height:21.75px;">Job intervals can now be created to be monthly, quarterly or yearly.</span>
*   <span style="line-height:21.75px;">Fixed verification link appearing incorrectly when accounts with multiple users</span>

## 28th May 2013

### New Features

*   On the payment page - jobs can be marked as complete without automically adding a new payment

### Improvements

*   <span style="line-height:21.75px;">Moved help button into the main navigation menu</span>
*   <span style="line-height:21.75px;">On the 27th May the database was migrated to a new cloud server to increase performance and security</span>
*   <span style="line-height:21.75px;">Fixed multiple bugs on report section. Added a print button and a menu to display tomorrows jobs</span>

## 9th May 2013

### New Features

*   <span style="line-height:21.75px;">Quick add multiple customers located on the same street using the <b>Add Street</b> button on the customer listing section</span>

### Improvements  

*   <span style="line-height:21.75px;">Job prices can be updated from the booking edit form to apply price too all future jobs</span>
*   <span style="line-height:21.75px;">Display round type on round listings (rounds generated automatically are given a type and will be possible to filter out in future)</span>
*   <span style="line-height:21.75px;">Changed hide customer to remove customer</span>

## 29th April 2013

### New Features

*   <span style="line-height:21.75px;">Adding custom configuration which can be found under **Customise RoundPartner** section in **My Account**</span>
*   <span style="line-height:21.75px;">Number of rows displayed on job and payment listings can be set in the custom configuration section</span>
*   <span style="line-height:21.75px;">Added VAT support throughout the system. This can be activated in **Business Details** section in **My Account**</span>
*   <span style="line-height:21.75px;">VAT can be inputted on expenses section</span>

### Improvements

*   <span style="line-height:21.75px;">Changes to how jobs are displayed throughout the system</span>

## 16th April 2013

### New Features

*   <span style="line-height:21.75px;">Added button to view jobs due today which can be printed</span>

### Improvements

*   <span style="line-height:21.75px;">Balance details added when hovering over balance in listings</span>
*   <span style="line-height:21.75px;">Added payments to round widget</span>
*   <span style="line-height:21.75px;">Job saved notification displayed on mobile site</span>
*   <span style="line-height:21.75px;">Fixed validation on price fields and added currency sign to field</span>
*   <span style="line-height:21.75px;">Jobs marked as completed or paid can not be deleted</span>
*   <span style="line-height:21.75px;">Fixed deleted jobs displaying in balances</span>

## 19th March 2013

### New Features

*   <span style="line-height:21.75px;">We are currently developing an offline version of the mobile site to allow viewing jobs without requiring a constant internet connectivity</span>

### Improvements

*   <span style="line-height:21.75px;">You can now delete an address from a round when editing the round</span>
*   <span style="line-height:21.75px;">Hovering over the balance on the customer listing shows the outgoing and ingoing payment</span>
*   <span style="line-height:21.75px;">Reporting includes recently added payments</span>

## 10th March 2013

### New Features

*   <span style="line-height:21.75px;">Mobile site now supports an easier way to update jobs and payments</span>
*   <span style="line-height:21.75px;">Printable job lists</span>

### Improvements

*   <span style="line-height:21.75px;">Mobile site updated with new functionality and style</span>
*   <span style="line-height:21.75px;">Desktop site updated with new functionality and style</span>
*   <span style="line-height:21.75px;">Lot of changes to core code allowing for planned future functionality to be added</span>

## 25th February 2013

### New Features

*   <span style="line-height:21.75px;">Added round tab to customers</span>
*   <span style="line-height:21.75px;">Added button to add job from the customer detail section</span>
*   <span style="line-height:21.75px;">Allow searching addresses from jobs section</span>
*   <span style="line-height:21.75px;">Allow ordering customers by either name (businessname, firstname, lastname) or address (street)</span>
*   <span style="line-height:21.75px;">More detailed customer listing on rounds section</span>

### Improvements

*   <span style="line-height:21.75px;">Updated site style/look. New style now allows for more improved functionality to be built</span>
*   <span style="line-height:21.75px;">New "responsive" navigation menu and listings allowing for the site to work on smaller tablet devices</span>
*   <span style="line-height:21.75px;">Cleaned up dashboard widgets</span>
*   <span style="line-height:21.75px;">Increased number of days that can be synced to Google Calendar</span>
*   <span style="line-height:21.75px;">Tidied up multiple sections accross the site</span>
*   <span style="line-height:21.75px;">Fixed in certain places where customer and address were not linked to customer details page on listings  
    </span>
*   <span style="line-height:21.75px;">Fixed calendar not always displaying month correctly</span>
*   <span style="line-height:21.75px;">Lots of minor bug fixes and interface cleanup</span>

## 10th February 2013

### New Features

*   Invoice header can now be customised
*   Rounds now available on mobile site. You can now view jobs, payments and customers by round
*   Added payment listing to mobile site
*   Added "forgotten password" link to login page to allow resetting password if it is forgotten

### Improvements

*   More customisation to invoice headers and footers, including adding your own logo (currently requires an externally hosted image)
*   Added more help/tutorial messages across the system
*   Added additional details displayed on mobile site lists and detail pages
*   Fixed bug causing invoices with special characters to not be generated
*   Removed "mark complete" button when job already complete on mobile site
*   Jobs can now be marked as complete if it is due withing the next 5 days

## 3rd February 2013

### New Features

*   Google Calendar Synchronisation now allows selecting which calendar to insert jobs into
*   Added account summary widget
*   Accounts verification email can now be resent
*   Synchronise to google calendar button added to quick links on dashboard

### Improvements

*   <span style="font-size:15px;line-height:1.45em;">Removed underlines from customer, jobs and payment page tables</span>  

*   Changes to script minification to reduce page loading speeds
*   Fixed February not appearing on planner on certain days of the month

## 27th January 2013

### Features

*   Improvements to customer search feature
*   Google calendar synchronisation
*   Allow hiding customers when no longer needed
*   Improvements to internal parts of the system

### Bugs

*   Fixed bug caused when viewing a customer with no address
*   Multiple bug fixes

## 1st January 2013

### Features

*   Customers and jobs can be imported from George
*   Customers are searchable by their name or address
*   Expenses added (beta)
*   Added a simple accounts report overview (beta)
*   Added payment method when creating a payment

### Bugs

*   Fixed lots of minor ui issues

## 19th December 2012

### Features

*   Adding tutorial messages that can be hidden

### Bugs

*   Fixed customer title being set to Mr on edit form
*   Fixed news widget displaying incorrect dates for news items

## 10th December 2012

### Features

*   Improvements to invoice tab with pdf invoice generation (more customisation will be available soon!)
*   Overdue payments are highlighted red on payment tab
*   Overdue jobs are highlighted on job tab
*   Planner highlights overdue and completed jobs
*   Customers can be downloaded as a CSV for local backup
*   Jobs can be removed
*   Multiple UI changes (including rebuild of address management)
*   Customers and jobs can be created on mobile

### Bugs

*   Fixed mobile site not keeping users logged in
*   Fixed GO button not working when login in to mobile site
*   Fixed minor mobile site navigation issues

## 26th November 2012

### Features

*   Enabled year selection to date picker
*   Multiple changes to notes displayed across the system
*   Order customers by name on mobile site
*   Allow adding customers on mobile site
*   Added job type detail to planner

### Bugs

*   Fixed calendar not displaying jobs scheduled on certain days
*   Fixed calendar navigation button not working correctly
*   Fixed tooltips not displaying correctly after pagination
*   Fixed unable to create customer after site registration