## SD BI Sales Cockpit Releases

### 3.3.3

#### Enhancements

- AppSource App - The Power BI Report FactBox was removed from the Role Centre.

### 3.3.2

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

- AppSource App - An Alert Notification was added to the SD BI Sales Cockpit activity pages to notify users to activate the SD BI Sales Cockpit licence on install of the App.

#### Bug Fixes

- AppSource App - When selecting SD BI Sales Cockpit activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD BI Sales Cockpit to fix an issue that would raise an error when the language is changed from English to another language.

### 3.3.1

#### Enhancements

- BCv21 App - The processing performance of the Sales Cycle Routine was improved. 

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant.

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name in the message.

- BCv21 App - The Licence Message on first install of the App was updated to prompt the user to activate a Free Trial.

- BCv21 App - The AppSource Submission required the removal of Customer/Item Sales Report for regions CA and US. The report was removed from the App.

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD BI Sales Cockpit Role Centre. 

### 3.3.0

#### Enhancements

- BCv20 App - The Product Activation page was updated to point to the new Subscription URL. 

- BCv20 App - The Quote No. was surfaced in the Sales Cycle List so users can easily tell from the Sales Cockpit the Quote No. that was converted to the Order. 

- BCv20 App - A link to the Sales & Receivables Setup was surfaced in the SD BI Sales Cockpit Setup to allow users easy access to switching on Archiving of Quotes and Orders. 

- BCv20 App - The Assisted Setup action was removed from the SD BI Sales Cockpit Setup card as we are not bringing in default setup. 

- BCv20 App - A change was made to the navigation logic in the Customer Alerts page. If the user was in the Customer Alerts page and chooses another View from the Views Factbox, the back arrow did not bring the user back to the SD BI Sales Cockpit Role Centre but brought the user back to the previous view. 

- BCv20 App - In the Page Filters action cue on the SD BI Sales Cockpit Role Centres, a blank value is now allowed in the Customer No. to show values for all customers. 

- BCv20 App - The codeunit lookups for Cliff Reports, Sayles Cycle and Salesperson Sales in the SD BI Sales Cockpit Setup card were replaced with Interfaces using Enum values. 

- BCv20 App - Objects were renamed to our ISV standards. 

- BCv20 App - Some actions were missing from the SD BI Sales Cockpit Setup Card. These actions were resurfaced on the menu. 

- BCv20 App - Permission extension objects were created for the SD BI Sales Cockpit permission sets. 

- BCv20 App - The code and logic behind turning on the Sales Cockpit Enabled flag was reworked. 

- BCv20 App - Various layout changes were made to the SD BI Sales Cockpit Customer Alerts card. 

- BCv20 App - Changes were made to the Cliff Report Codeunit to publish an event OnAfterFilterItemLedger for use if users want to filter results on specific criteria. 

- BCv20 App - A Force Salesperson Filter was added to the SD BI Sales Cockpit Setup card. Switching this flag on limits the cues in the Activity Panel of the SD BI Sales Cockpit User Role Centre to the Salesperson Code of the currently logged in user. 

- BCv20 App - Changes were made to the Page Filters on the cues in the SD BI Sales Cockpit Activity pages. 

- BCv20 App - The names of the SD BI Sales Cockpit objects were updated to our standard ISV naming conventions. 

- BCv20 App - The latest ISV Licence Controller was added to the product. 

- BCv20 App - A test app was created for AppSource submission. 

- BCv20 App - Tooltips were added to the product. 

- BCv20 App - The Links in the About Page were updated to point to our new website. 

- BCv20 App - The Latest Version of the product and the AppSource URL were added to the About Page. 

- BCv20 App - Tooltips were updated to point to our new website. 

- BCv20 App - Changes were made to the filtering applied on the cues in the SD BI Sales Cockpit Activity pages. 

- BCv20 App - The HTTPClient Request boolean for SD BI Sales Cockpit is switched on by default on install of the product. 

#### Bug Fixes

- BCv20 App - Fixed an error that was raised when running the SDY BICS Job Queue. 

- BCv20 App - An issue was fixed where when setting a view as the default view, if a different view is already marked as default, an error was raised that the record already existed. Users were then prompted with further messages and entered into a message loop. 

- BCv20 App - The Product Activation page was updated to disable the Activate button unless the Product Key is filled in. 

### 3.2.1

#### Enhancements

- BCv14 App - The processing performance of the Sales Cycle Routine was improved. This change was made to the BCv14 v3.2.0 release of SD BI Sales Cockpit only and not to any future versions and was released as BCv14 v3.2.1.
- BCv14 App - A page was created to display all Simply Dynamics Apps and Subscription details for the tenant. This change was made to the BCv14 v3.2.0 release of SD BI Sales Cockpit only and not to any future versions and was released as BCv14 v3.2.1.
- BCv14 App - Update the ISV Licence Controller Expiry Message to display the App Name. This change was made to the BCv14 v3.2.0 release of SD BI Sales Cockpit only and not to any future versions and was released as BCv14 v3.2.1.

#### Bug Fixes
- BCv14 App - The code for licence key checks on the SD BI Sales Cockpit Roler was reviewed. This change was made to the BCv14 v3.2.0 release of SD BI Sales Cockpit only and not to any future versions and was released as BCv14 v3.2.1.

### 3.2.0

#### Enhancements

- BCv14 App - Reworked the code to add records to the Alert table. 

- BCv14 App - Updated the caption of the Updated checkbox in the Customer Alerts page to Refresh Required. 

- BCv14 App - Visual changes were made to the SD BI Sales Cockpit Setup page to keep in line with the visual changes made to the SD BI Sales Cockpit Customer Alerts page.

- BCv14 App - Reinstate the Setup action cue on the SD BI Sales Cockpit Manager Role Centre.

- BCv14 App - Some of the object names on the ODATA list were updated. 

- BCv14 App - Visual changes were made to the SD BI Sales Cockpit. 

- BCv14 App - Functionality was developed to create a new view based on the default settings in the SD BI Sales Cockpit.

- BCv14 App - The captions on the Visual on Sales by Salesperson List were updated.

- BCv14 App - The SD BI Sales Cockpit User Role Centre and the SD BI Sales Cockpit Manager Role Centre were removed from the Tell Me.

- BCv14 App - A typo on a field in the SD BI Sales Cockpit Setup Card was corrected.

- BCv14 App - A change was made to the Role Description for the product.

- BCv14 App - The object names were updated to reflect the new name of the product.

- BCv14 App - The Actions in the SD BI Setup Card were changed to be consistent with our other ISV Products.

- BCv14 App - The name of the product that was displaying in the standard NAV App Setting page was updated.

- BCv14 App - Permission sets were added to the product. 

- BCv14 App - The Assisted Setup functionality was added to the product. 

#### Bug Fixes

- BCv14 App - There was an issue with monthly calculations for leap years. This was fixed. 

- BCv14 App - Fixed an issue selecting dates in the SD BI Sales Cockpit Setup and in the Customer Alerts. 

### 3.1.1

#### Enhancements

- BCv14 App - Changes were made to the code base to prepare for AppSource submission. 

- BCv14 App - Licensing was added to the product. 

- BCv14 App - The Actions in the Menu Groups on the SD BI Sales Cockpit were regrouped and moved. 

- BCv14 App - A change was made to SD BI Sales Cockpit Setup Card to change the filter on the Handler CodeUnits to allow users to select different Handler CodeUnits. 

- BCv14 App - SD BI Sales Cockpit pages can be searched for in the Tell Me. 

- BCv14 App - Visual changes were made to the SD BI Sales Cockpit Role Centre. Actions were removed. Alert Actions were reorganised and reordered. 

- BCv14 App - The Salesperson Chart was removed from the build. 

- BCv14 App - The About Action was removed from the Role Centre and surfaced in the SD Bi Sales Cockpit Setup Card. 

- BCv14 App - The Update Data Action was removed from the Menu. The Refresh Alert Action was renamed Refresh. Always on choosing Refresh a dialog is raised to give the user an option to Update Data. 

- BCv14 App - A Refresh Required Boolean was added to the Customer Alerts Page under the Default View Boolean. The Refresh Required is to signify to the user that the figures in the Customer Alerts page need to be refreshed.  

- BCv14 App - Visual changes were made to the Filters FastTab in the Cliff Alert page. FastTab was renamed to Minimum Sales Filters and the order of the fields was changed. 

- BCv14 App - Functionality was introduced so users can see a year on year comparison in the Cliff Alerts. 

- BCv14 App - The name of the product was changed to SD BI Sales Cockpit and the name was updated on all relevant pages. 

#### Bug Fixes

- BCv14 App - Fixed an issue where in the Cliff Alert Period Settings, the range was working by choosing the latest range first and the earliest range last. This was changed so now, logically, the earliest range is chosen first and the latest range is chosen last. 

### 3.1.0

#### Enhancements

- BCv14 App - Fixed an App installation issue. 

### 3.0.0

#### Enhancements

- BCv14 App - Increased size of description and name from 50 to 100 as per standard D365BC change. 

- BCv14 App - Inventory Cockpit added Views, FactBoxes, Graphs. 

- BCv14 App - Functionality created to save and load views in the Alert Cliff Report.

- BCv14 App - Changes were made to the Core OData pages.

- BCv14 App - The logic behind the filters on the Sales Cycle Order Cues was reviewed.

- BCv14 App - Changes were made to the Inventory Cockpit Setup.

- BCv14 App - Changes were made to the Sales Cockpit Setup.

- BCv14 App - A Manager Activity panel to view all salespersons cues was added to the Sales Cockpit.

- BCv14 App - Changes were made to the Inventory Alerts Cliff Report.

- BCv14 App - The Sales Cycle Pages were published as OData pages. 

- BCv14 App - A Role Centre was created for the Inventory Cockpit. 

- BCv14 App - A Role Centre was created for the Sales Cockpit. 

- BCv14 App - details from the Sales Cycle when the order is invoiced. The order history should be kept.

- BCv14 App - Amended the Customer Alerts on the Alerts Cliff Page so that they now toggle to expand. 

- BCv14 App - The Usage Category property was added to the Power BI objects. 

- BCv14 App - Changes were made to the Activity Panel. An Action was added to access the Setup Card and the About Action was surfaced on the Activity Panel.

- BCv14 App - Changes were made to the Sales Alerts Cliff Report.

- BCv14 App - New OData Pages for Salesperson/Purchasers, Item Categories and Location List were created.

- BCv14 App - A setup action was added to the Activity Panels.

- BCv14 App - Activity Panels were added to the standard Sales order Processor Role Centre.

- BCv14 App - A Publish Web Service page was created.

- BCv14 App - New standard OData pages were created for the build.

- BCv14 App - A Sales PBIX build was created.

- BCv14 App - Additional pages were added to the product. 

- BCv14 App - Reviewed the code behind certain Sales Cycle events. 

- BCv14 App - A comment field was added to the customer alert table.

- BCv14 App - Functional and visual changes were made to the Sales Cockpit and to the Cliff Report Activity. Added a send to excel action, and standard NAV reports actions to the ribbon. Displayed values in LCY. Allowed users to expand and collapse per customer on item category values.

- BCv14 App - Cues to display counts and values of quotes and orders issued and won were added to the Sales Cockpit activity page.

- BCv14 App - Changes were made to the Sales Cockpit Setup page removing days as a period, holding the last entry no. on the setup and allowing users to do a full rebuild of the data or to do an incremental refresh..

- BCv14 App - Changes were made to the Sales Cockpit Activity page to limit the sales values displayed to those of the user who is logged on.

- BCv14 App - Changes were made to the Sales Cockpit - Cliff Report turnover page to allow a show all on the customer alert list.

- BCv14 App - Created an Inventory Cockpit.

- BCv14 App - Created a Sales Cockpit.

- BCv14 App - Created functionality to record the Sales Cycle from Sales Quote won, Sales Quote lost to Sales Orders created.

- BCv14 App - Created a page to display dimension data out to Power BI.

- BCv14 App - Created Purchasing pages and queries.

- BCv14 App - Created inventory tables, pages and queries for Power BI.

- BCv14 App - Created Sales Pages and Queries.

- BCv14 App - Created Finance Pages and Queries.

- BCv14 App - Created functionality to include shelf life in the inventory cockpit.

- BCv14 App - The Inventory Cockpit objects were moved into a separate standalone product. 

#### Bug Fixes

- BCv14 App - Fixed an issue raised when installing the App.

- BCv14 App - Fixed an error raised when the refresh button was chosen on the Manager Role Centre.

### 2.3.3

#### Enhancements

- For Document Type of Invoice created from a Sales Shipment, stamp the Order No. on the Quote Track List.

- For Document Type of Credit Memo created from a Sales Invoice stamp the Order No. on the Quote Track List.

- Made a change to Report 43006300 so it compiles in NAV 2018 GB.

- Fixed compilation errors for XML Ports 43006300 and 43006301.

- Included Report 43006300 in the release.

- Extended the Sales Quote Tracking functionality to log details and trace a Quote from Quote to Order to Invoice or Credit Memo.

### 2.3.2

#### Enhancements

- SD Utilities - Power BI split into own project.

### 2.3.1

#### Enhancements

- Linkbox: 
- Add a setup field to specify document checkout to a default Drop Point check out path.

### 2.3.0

#### Enhancements

- Launch: 
- Upgrade Launch to use Control Suite. 

Linkbox: 
- Created check in/check out functionality for Linkbox Version Control. 
- Added Edit Permission to Linkbox. 
- Cleaned up code.

#### Bug Fixes

- Linkbox: 
- Fixed Error Message raised when viewing a file in the Drop Point or Versions List. 
- Fixed situation where the View Option was always displaying the same file.

### 2.1.2

#### Enhancements

- Updated readme.txt file. 

- Launch - applied Launch standardised document layouts to the Posted Purchase receipt report 

- Linkbox - enhanced Linkbox file overwrite confirmations.

#### Bug Fixes

- Linkbox - fixed a bug in the scrolling functionality when selecting an Icon for a Drop Point in the Drop Point Card. 
- Linkbox - fixed an issue where when choosing to Edit certain files from the Dropped Files Factbox an error is raised. 
- Linkbox - fixed an issue where Delete Permission on Dropped Files Fact Box not taken into account when you right-click on the Dropped Files Fact Box. 
- Launch - fixed alignment issue on the SD-U Customer Payment Receipt Document.

### 2.1.1

#### Enhancements

- Linkbox - enhanced the Icon Scroller picker. 
- Linkbox - enhanced the Template functionality - allow users to choose to push out the Templates to the Linked tables and select the template they want to attach to the records. 
- Launch - surface filters on SD-U Bank Acc. Recon. Stmt Document. 
- Launch - surface filters on the SD-U Bank Acc. Recon. Stmt Test Document. 
- Launch - improvement in code to allow for barcode record type value. 
- Launch - optimised the image preview generation. 
- Launch - surfaced the newly added Documents to the Role Center. 
- Launch - applied Launch standardised document layouts to the SD-U Customer Payment Receipt Document.

#### Bug Fixes

- Launch - fixed alignment issue on SD-U Sales Return Order Document. 
- Launch - fixed alignment issue on SD-U Purchase Return Order Document. 
- Launch - changed the Launch Documents to use the document currency code rather than customer/vendor currency code when deciding the bank details to use on the footer. 

- Linkbox - fixed a bug in the auto linking functionality of a Template File to a record. 
- Linkbox - fixed a bug in the Version History of Dropped Files Linked to a record. 
- Linkbox - fixed a bug in the Version History of auto-created Template Files. 
- Linkbox - fixed a bug where an error was raised on creation of a new record when a Drop Point (with Versioning turned on) is added to a Card Page. 
- Linkbox - fixed a bug where the Icon Scroller images were not updating. 

- Power BI - fixed an issue where the Return Sales Order as raising an error if there was no BI Setup.

### 2.1.0

#### Enhancements

- Launch: 
- All Launch Documents and Reports underwent a code clean up. 
- A Delivery Docket was added to Launch. 
- A Manifest Report was added to Launch. 
- A Bank Account Reconciliation Statement (Posted Entries) was added to Launch. 
- A Bank Account Reconciliation Statement (UnPosted Entries) was added to Launch. 
- A Stock Take Report was added to Launch.
- A Sales Return Order was added to Launch.
- A Purchase Return Order was added to Launch. 
- A Balance Forward Statement was added to Launch. 
- A standardised layout was applied across all Launch Documents and Reports. 
- All Field Names and abbreviations were standardised. 
- Decimal formatting was standardised across all Launch Documents and Reports. 
- A new Footer totalling layout and a VAT Grid layout was applied and standardised across the Launch Documents. 
- Positioning of Logos was made consistent across all Launch Documents and Reports. 
- A standard Header and Footer layout and banner, for portrait and landscape layouts, was applied across all Launch Documents and Reports. 
- An enhancement was made to allow users to choose the Background and Foreground Header and Footer Banner Colours that would print on all Launch Documents and Reports using a Colour Picker.
- Enhancements were made to the Remittance Advice Reports in Launch. Captions were changed, fields were resized. 
- Functionality to define and display a Barcode on all Launch Documents and Reports was added to Launch. 
- A Report Info Box was applied to the layout of all Launch Documents and Reports.
- Functionality was added to allow users to dynamically add the fields to print in the Report Info Box. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- New functionality was added to allow users to select the Background and Foreground Header and Footer Banner Colours by using a colourpicker. 
- Improved the resolution of the Report Info Box. 
- Fields and FastTabs for new functionality were added to the Launch Setup Card.

Linkbox: 
- New functionality added to Linkbox to Security Filter Tables and Pages enabling permissions to be set. 
- Updated the Linkbox Setup to include Security Filters 
- New Security Filters for Dropped Files applied. 
- New Security Filters for Drop Areas applied.
- Added Company to membership lookup in Linkbox Security Filters. 
- New Version Control functionality added to Linkbox. 
- Provided Version Edit functionality. 
- When viewing a file in the Drop Area, the file is set to read only. 
- Coded increments for Dropped File Entry No. 
- Created a new Table and Page to list, and provide, Dropped File Version functionality.
- Created Template functionality for Linkbox.
- Changed functionality to retain the SD Linkbox - Orphan Link Files.

Profiler: 
- An XMLPort was created to export and import Profile Select List. 

PowerBI: 
- Added Sales Quote Tracking Functionality to PowerBI. 
- Added functionality to provide for CSV Import/Export for BI Date data. 
- Added the PowerBI Setup Page to the SD Utilities Role Centre.

#### Bug Fixes

- Launch: 
- Fixed bug where the Statement report overwrites any Date Filters that are passed into the report. 
- Fixed bug where colour choices picked using the colour picker were being re-set. 
- Fixed bug where the QR Barcode was not displaying correctly in the Report Information box. 
- Fixed bug in the Launch Report Setup whereby when a new record was added to the Report Info Box Fields for a specific report, the Field No. was not appearing in the order as specified but rather in the order as input. 
- Fix was made to the barcode generation to display as per Launch Report Setup. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- Fixed bug which allowed a Barcode to be setup on the Launch Report Setup with a DPI of zero. 
- Fixed bug where the List of Reports showing in the Launch Setup was being hard code filtered on an earlier version release. 
- Fixed bug where the InfoBox and Barcode were not being updated.
 
Linkbox: 
- Drop Point Icons on List Pages are intermittently not displaying when the List Page is loaded from within the Role Centre.
- Fixed bug where a link is being created to records with no file attached when a record for a Template File that has no File Imported (a blank Filename field) is created. 
- Fixed error raised when an empty file is dragged and dropped into a Drop Point.

Profiler: 
- Removed irrelevant Actions from the Profile Selection List.

### 1.1.0

#### Enhancements

- Linkbox - created XMLPorts for Upgrade to NAVW19.00 - V2.1.0 
- Profiler - created Profiler Date export 
- Power BI - created BI Date XML Port

#### Bug Fixes

- Launch - fixed bug where statement report overwrites passed in Date Filter.

### 1.0.2

#### Enhancements

- Linkbox - Drop Area was not displaying on the Role Center. 
- Launch - Unable to run statement when specified from report selection.

### 1.0.1

#### Enhancements

- Documentation fixes.

### 1.0.0

#### Enhancements

- Linkbox - Created an XmlPort for setting up control Add-in. 
- Profiler - Refactored the object selection. Rewrote the reports to loop on the questions and do basic formatting of them. 
- Profiler - Renumbered and reordered the Tables and Pages. 
- Cleaned up the objects. 
- Code upgraded to 2016.

