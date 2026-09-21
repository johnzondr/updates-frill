# 2025 Updates

## 12/18/2025

**Email Tracking in Activity Log**\
We've enhanced the Activity Log to automatically track email communications. Every email sent, including Booking Confirmations, Appointment Reminders, Payment Reminders, Project Complete, and Follow-Up emails, now creates a detailed event showing the recipient, subject, and real-time delivery status (Sent, Delivered, Opened, or Failed). Each entry includes a "View Email" button to see the full content. This provides complete transparency into email delivery and helps troubleshoot communication issues.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>



**More Flexible Invoice Dates in QuickBooks**\
We've enhanced the QuickBooks integration with configurable invoice issue dates. You now have control over the date that appears on invoices sent to QuickBooks. Choose the date that works best for your business: use the date the booking was made, the date the shoot is scheduled, or the date we sync it to QuickBooks. To set your preferred date date simply access Configure Booking>Invoicing and selected the invoice option.<br>

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>



**Official Receipts in Payment History**\
You can now easily access official payment receipts. A new "View Receipt" button now appears next to payments in your payment history. Clicking it opens the official Stripe receipt in a new tab. This gives you easy access to proper payment documentation for your records or accounting needs.<br>

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>





## 12/8/2025

**New Feature: QuickBooks Integration**\
We are excited to announce the release of our highly anticipated QuickBooks integration. This feature is designed to streamline your accounting workflows by automatically syncing invoices between Tonomo and QuickBooks.

**Important Notes for Version 1 Release:**

* **Tax Support**: The initial release does not support tax synchronization. To use this integration at this time, please ensure you are not applying taxes within Tonomo.
* **Batch Invoicing**: Batch invoicing for brokerages is not yet available in this version.

**Setup Instructions:**\
To configure your QuickBooks integration, please follow the steps outlined in the following video tutorial or refer to the [written guide](https://support.getautonomo.com/articles/5613124077-quickbooks-integration) in our documentation.

{% embed url="https://www.loom.com/share/a862a5d57e3e4c408b078a91d042a63b" %}



**New Client Indicator**\
The Order Management page now displays a "New Client" indicator for customers completing their first booking.

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>



**Minor fixes and improvements**<br>

* **Enhanced Mileage Filter:** The maximum date range for mileage reporting has been increased from 3 months to 12 months.
* **Calendar Integrity:** Fixed a bug where updating an order via the Orders Management page would delete any notes on the associated calendar event, even though the notes still appeared to exist in the Scheduler.
* **Data Synchronization:** Orders in the order dashboard are now correctly displayed on both the web dashboard and the mobile app.
* **Invoice Accuracy:** Changing a service to a higher custom pricing tier now correctly updates the invoice total in the new design.
* **UX Enhancement:** The "Add Appointment" and "Reschedule" buttons have been moved to a more prominent location within the Overview section in the new design.



<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

## 9/26/2025

**New Feature: Separate Appointments for Specific Services**

We've introduced a new feature allowing you to designate specific services as separate, bookable appointments within a single client order. This is perfect for offering specialized services that require different photographers or times.

{% embed url="https://www.loom.com/share/0c40255fab6840739ef9acfdedb78989" %}

**Key Updates:**

* **New Service Setting:** A "Book this service as a separate appointment" toggle is now available in each service's settings.
* **Flexible Client Booking:** When clients add both standard and "separate appointment" services to their cart, they will be prompted to schedule each designated service individually.
* **Updated Confirmation Emails:** Client confirmation emails will now clearly list each separate appointment time and its associated services and photographers.





**New Agent Welcome Email**

We've added an automated welcome email to help onboard new agents after their first booking.

**Key Features:**

* **Automated Trigger:** The email is sent automatically after an agent successfully completes their first-ever order.
* **One-Time Send:** The welcome email is sent only once per agent to avoid repetition.
* **Fully Customizable:** A new "New Agent Welcome Email" template is available in Configure Booking>General. You can fully customize the subject and body.
* **Toggle Control:** From your settings you can enable or disable this automated email globally.

<figure><img src="../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>





**New Single Property Website Template**

We've released a new property website template, **"Box."** You can now find and customize it in your admin panel. Check it out and share your feedback!

<figure><img src="../.gitbook/assets/Screenshot 2025-09-27 at 12.40.27 AM.png" alt=""><figcaption></figcaption></figure>



**White-Labeled Video Share Links**

We have improved the video share links within Tonomo to be completely white-labeled to your domain.  Share links for videos will not be "_projects.yourdomain.com/video/..."_  This will help you create a more professional and branded experience for your customers when they share videos online.

<figure><img src="../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>





**Bug Fixes Applied:**

* **Fixed Custom Questions Display:** \
  Resolved a bug where custom questions were not appearing on the Order Details page when an order was created through the Scheduler while skipping the "Notes" section. All custom questions now display correctly.
* **Fixed Booking Logic for "Send Two Photographers":** \
  Fixed a bug that prevented booking when "Send two photographers" was enabled but only one photographer was qualified for all services. The system now correctly allows the booking if the combined skills of two available photographers cover all required services.

<br>



## 9/10/2025

**New Feature: Batch invoicing for Brokerages**

{% embed url="https://www.loom.com/share/9cf49c39a9704082bb7d3ff193fe98d9?sid=d78ed46f-c3f8-44f3-a727-782d4e285b5b" %}

You can now group multiple orders into a single, consolidated invoice for one easy payment. This is perfect for high-volume clients like brokerages where a single person pays for many jobs at once, eliminating the need for manual consolidation.

* Streamline Billing: Simplify invoicing for your most active clients.
* Simplify Payments: Clients can pay for multiple orders with a single transaction.
* Save Time: Reduce administrative work and manual errors.



*   **Show batched invoice for admins in the new order details view**\
    If you access the order details page for any order that is part of a batched invoice in the order management section you will now see the option to see the batched invoice instead of seeing the separate invoice for that individual order.<br>

    <figure><img src="../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

<br>

#### **Bug Fixes & Improvements**

* Fixed an issue related to travel fee not being added when a client rescheduled an order.  Now all travel fees are added correctly whether the order is rescheduled by a client or by an admin.
* Fixed an issue where if a brokerage name was too long it would break the page layout.
* Removed "sync invoice" buttons for those who are not using Xero that may cause confusion.
* Set the default listing website template to color black
* For our Australian and New Zealand clients tax now reflects correctly as "GST"



## 8/13/2025

**Mileage Reporting**\
We’re excited to introduce our new Mileage Reporting feature, designed to help you effortlessly track the distance your photographers travel to and from shoots\
**Key Features:**

* **Easy Access** – Find the Mileage Reporting tool in the left-hand panel under the **Reporting** tab.
* **Flexible Filtering** – Filter reports by **date range** and **photographer** to view specific data.
* **View Options** – Choose to see travel distance for photographer&#x73;**, by event, or by day**.
* **Export Data** – Download reports as an **Excel sheet** for further analysis or record-keeping.

<figure><img src="../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>





**Order Details Redesign**\
We are happy to introduce a fresh and modern redesign of the Order Details page!  To enable the new design all you have to do is make sure the toggle "switch to the new look" is enabled.  You can find this on the top right hand corner of your current order details page.  Please watch this video to learn how to make the most of our new design.

{% embed url="https://www.loom.com/share/4dc118f31c6f4b4c896e07364709f399?sid=f587ddc0-9c97-4065-a8a6-c3c3bdbe0a7c" %}





**Minor Fixes**

* **Contractor Reporting** – Travel fees now correctly add to the total payout calculation in contractor reports.
* **Custom Tiers** – Fixed an issue where custom pricing tiers for services and packages weren’t populating correctly on invoices and calendar events.
* **Watermark Visibility** – Resolved a bug where watermarks would still appear on photos after setting payment status to "Promised Payment."
* **Custom Questions** – Questions linked to specific services now properly display in the Order Details section when adding that service to an existing order.

## 7/16/2025

**Automated Payment Reminder Emails for Unpaid "Pay to Unlock" Orders**\
We’re excited to introduce a new feature that helps streamline your payment collection process! You can now set up automated reminder emails to send to clients with unpaid **"Pay to Unlock"** orders. **This email will go out to clients every 7 days until the order is paid.**

**How to Enable & Configure:**

1. Go to **Configure Booking > General**.
2. Scroll down to **"Automated Reminders for Unpaid 'Pay to Unlock' Orders"**.
3. **Enable** the feature.
4. Click **"Edit Template"** to customize the email message and set the frequency of reminders.

This feature ensures your clients receive timely payment reminders, and reduces manual follow-ups.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>



#### **New Reporting Overview View: "Scheduled Date" Option**

We’ve updated the **Reporting Overview** page to give you more flexibility in analyzing your order data!

**What’s New:**

* **Two View Options:**
  * **Most Recent** (default view)
  * **Scheduled Date** (new!) – Organizes orders by their scheduled date for better planning and tracking.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>



**Minor Fixes**

*   #### **Incorrect Date/Time in Google Calendar Event Description After Rescheduling**

    We’ve resolved an issue where rescheduling an order on the **confirmation page** (immediately after booking) caused the wrong date and time to appear in the **Google Calendar event description**.  The Google Calendar event description now always reflects the **correct rescheduled date/time** and all other details.
*   #### **Calendar Events Displaying All Services Instead of Only Assigned Ones**

    We’ve fixed an issue where updating order details in the **Scheduler** caused calendar events to show **all services** on the order, rather than only the **assigned services** for each event.  Calendar events now **only show the assigned services** for each appointment, matching the expected behavior.
*   B**ug Fixes & Improvements: Service Editor Assignment**

    We’ve addressed several issues related to assigning editors to services to ensure accurate and expected behavior across the platform.



    **Editor Assigned to All Services**

    * **Problem:** Assigning an editor to one service incorrectly applied the assignment to all services.
    * **Fix:** Editors are now only assigned to the **selected service**, leaving others unassigned as expected.

    **Editor Not Removed After Deletion**

    * **Problem:** Deleting an editor and refreshing the page did not clear the assignment.
    * **Fix:** Editors are now **properly removed** upon deletion, and the service shows as unassigned after refresh.

    **Incorrect Project-Chat Assignment**

    * **Problem:** Assigning an editor to a single service also added them to the **entire project chat**.
    * **Fix:** Editors are now **only assigned to the intended service** without affecting the other services in project chat.

    **Multiple Editors per Service**

    * **Problem:** It was possible to assign **multiple editors** to a single service, causing reporting inconsistencies.
    * **Fix:** The system now **limits assignments to one editor per service** for accurate reporting.





## 7/2/2025

**Configurable Day-of-Week Fees**\
We're excited to introduce more pricing flexibility to your booking flows! You can now set custom fees for specific days of the week to better align with your business needs.\
**How to Set Up:**

1. Navigate to: Configure Booking > Booking Flows > Edit
2. Scroll to: "Set days available for booking and fees for specific days"
3. Toggle days on/off and input your custom fees

The new pricing will automatically apply to all new bookings and any rescheduled appointments moving forward.

<figure><img src="../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>



**Multiple service areas for photographers**\
Photographers can now be assigned to **multiple service areas**! This gives you greater flexibility when scheduling shoots across different locations.  In order to set this up, simply go to Configure Booking > Scheduling  and make sure you have already created the necessary service areas.   Then go to "Assign Service Areas" and assign the required areas to each photographer.

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>



**Custom Out-of-Service-Area Messages**\
We’ve added more control over your customer experience! Now you can **customize the message** clients see when they attempt to book outside your service area. To edit the custom message go to _Configure Booking > Scheduling > Service Areas_ and Edit the "Custom Message for Out-of-Area Bookings" field

<figure><img src="../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>



**Add Package payout to the Contractor reporting**\
You can now calculate contractor payouts using **package payout values** directly within the Contractor Reporting page. Previously, Tonomo calculated contractor payouts based on the individual services included in a package. However, this didn’t always reflect the actual earnings structure, since **bundled services often have a different payout rate** than when those services are sold individually.\
To use the contractor reporting page go to _reporting>contractor reporting_ and input the parameters you wish you view.<br>

<figure><img src="../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>



**Minor changes and fixes**

*   You can now remove the Unscheduled Orders tab in the order management page

    <figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
* &#x20;Fixed an issue that was adding additional travel fees when other photographers are added to the team section on the Order Management page.
*   Fixed an  issue where the drive time calculation was not working for external events with an address attached.  Now when you create an external event in google and add an address Tonomo should take into account the drive time from that event location to your next shoot.<br>

    <figure><img src="../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>
* Fixed and issue that was preventing customers from adding listing agents to orders.  When a customer adds a listing agent to an order, the system now checks if the phone number matches an existing user.  If a match is found:
  * A new account will not be created (avoiding duplicates).
  * The existing user can be added directly as the listing agent.

## 6/4/2025

**Newly Designed Contractor Reporting Page**\
We’re excited to share the latest updates to the **Contractor Reporting Page**, designed to give you more flexibility and clarity when reviewing appointments and earnings. Here’s what’s new:\
**Key Improvements:**

**Date Picker Enhancement**

* Now filters by **appointment dates** (not order dates) for more accurate reporting.

**Multi-Photographer Filtering**

* Select **multiple photographers** at once to streamline your view.

**Tips Calculation Logic**

* Tips per photographer are now calculated based on their share of earnings:\
  `(Photographer's Amount Earned / Total Order Earnings) * Tips`

**Updated Data Display:**

* **Photographer Names:** Now shows **both photographers** when the _"Send 2 Photographers"_ toggle is enabled.
* **Services:** Displays services tied to the specific appointment.
* **Payout Breakdown:** Clearer view of:
  * **Amount Earned**
  * **Travel Fee Earned** (automatically calculated %)
  * **Tips** (new proportional calculation)
  * **Total Payout** (`Amount Earned + Tips`)

These changes will help you track appointments, earnings, and payouts more efficiently.<br>

<figure><img src="../.gitbook/assets/Screenshot 2025-06-04 at 3.52.22 AM.png" alt=""><figcaption></figcaption></figure>

**Photographer Services Filter in Scheduler** \
We’ve added a **Photographer Services** section to the left panel of the scheduler! This helps you quickly find photographers based on the services needed for a specific order.  Each  service will feature a toggle, enable toggles to highlight only photographers who perform the selected services.\
\
**How It Works:**

1. **Default View**: All photographer columns are active (white).
2. **Toggle On**:
   * Photographers who perform the **selected service(s)** stay active.
   * Others are de-emphasized (gray).
3.  **Toggle Off**: Reverts to the default view.<br>

    <figure><img src="../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>



**Scheduled Dates for Batch Invoices**\
Batch invoices now include an automatic **Scheduled Date** field, making it easier to find and filter them alongside individual invoices in your workflow.  Tonomo automatically sets the batch's **Scheduled Date** to match the earliest date from its orders.<br>

<figure><img src="../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>



**Clearer Download & Share Buttons**\
We’ve redesigned the **Download** and **Share** buttons for videos to make them more intuitive and user-friendly.  Previously, the labels made it hard to distinguish between downloading and sharing. Now, you’ll see clearly labeled **"Download"** and **"Share"** buttons with intuitive icons<br>

<figure><img src="../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

**Recommended Time slots range -** Within configure booking > general > scheduling, you can now update recommended timeslots to be based on appoints between 2, 3, or 4 weeks.

<figure><img src="../.gitbook/assets/Screenshot 2025-06-04 at 3.44.41 AM.png" alt=""><figcaption></figcaption></figure>



## 5/13/2025

**Automatic Sunset Time Integration for Twilight Photoshoots**\
We have made twilight scheduling much easier!  Tonomo will now automatically pull the local sunset start time based on the shoot location and date. This ensures your twilight sessions are timed perfectly with optimal lighting.   You can enable this feature in **Configure Booking > General**.  You can also set a twilight offset to define how many minutes before and after sunset to set the twilight service hours.

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>



**Enhancements to split services**\
We’ve rolled out a set of improvements to make managing split services more intuitive and efficient in the Scheduler.

* **Color Dots for Service Statuses** - Easily distinguish between scheduled and unscheduled services with new color-coded dots—helping you spot the status of each service at a glance.
* **3 Dot Menu for Scheduled Services** - You can now take action directly from the three-dot menu on scheduled services within the Services section, making edits and updates more accessible.
* **Unified “Schedule Appointment” Button -** We’ve consolidated multiple call-to-actions into a single “Schedule Appointment” button at the bottom of the Services list for a cleaner, more consistent experience.
* **Highlight Linked Appointments** - Clicking a service in the services section now highlights the associated appointment on the calendar, so you can quickly see what’s connected and stay organized.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>



**New Webhook: Dropbox Folder Events**\
A new webhook has been implemented to support Dropbox folder tracking for orders.  The webhook is triggered when Dropbox folders associated with an order are created, modified, or deleted.  You can find this webhook in **Configure Booking > General**:&#x20;

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>



**Enhanced Client Confirmation Emails with Time Slot-Specific Details For Each Service**\
We’ve upgraded the client confirmation email system to include time slot-specific service and provider details.  You can now include what services will be completed on what date and by which provider, giving clients a clearer picture of their scheduled appointments.  You can set this up by editing your confirmation email template under **Configure Booking > General**, or by reaching out to our support team for assistance.<br>

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>



**Xero Improvements**

* Add an "undo batch invoicing" feature - You can now easily reverse previously batched invoices, giving you greater flexibility and control over your invoicing process.

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>



**Minor Bugfixes**

* The “**Disable confirmation email**” option in the booking flow is now working properly, and confirmation emails will no longer be sent when this setting is enabled.
* We’ve removed the **completed status validation** for Batch Invoicing, allowing clients to create batch invoices without having to mark the orders as complete.
* **All-day external events** now display correctly on the Scheduler, ensuring accurate event visibility and scheduling.



## 4/30/2025

**Client facing arrival window display**

Instead of providing exact start and end times for customers, you can now provide an arrival window to customers. This is a great way if you don't want to guarantee exact arrival times to customers.

You can configure an Arrival Window, a customizable time buffer added to the original appointment which informs clients that the photographer may arrive at any point within that window.  To set up your arrival window you can go to configure booking scheduling as shown below.

**Note: If you use this feature — it's recommended you disable inviting customers to calendar events to avoid confusion about exact start and end times for appointments.**

<figure><img src="../.gitbook/assets/image (161).png" alt=""><figcaption><p>The Arrival Window functions as a buffer period indicating to the client that the photographer will be arriving within that range.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (160).png" alt=""><figcaption><p>You can find this feature in configure booking scheduling</p></figcaption></figure>



**New Onboarding Guide Now Available**\
We've introduced a built-in onboarding guide to support new users during portal setup. The guide includes step-by-step instructions and video tutorials to help you configure your services, packages, booking flows, and scheduling with ease.  If you have already started the onboarding process and would like to view this guide on your portal please reach out and we will enable it for you.<br>

<figure><img src="../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>



**Bulk Sync Delivery Files**\
You can now select multiple ready-to-sync orders and sync them all at once. Just check the orders you want to sync, and a 'Sync Delivery Files' button will appear at the bottom of the screen as shown in the following screenshot.<br>

<figure><img src="../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>



**Brokerage Email Field Now Optional**\
Beforehand, updating any brokerage information fields would require you to fill out the email field in order for the save changes button to be enabled.  Thus making the email field required.  We've updated this so that the **Brokerage Email** field is now optional, allowing admins to edit brokerage information without being required to enter an email address. This streamlines updates and makes managing brokerage details easier.<br>

<figure><img src="../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

**Minor update**

* Exporting Orders now includes the order id in the excel file

**Bugfixes:**<br>

**Order Filtering by Due Date** – Fixed an issue where filtering by “Due Date” on the Orders Management page returned no results, even when matching orders existed.

**Invoice Label Translations** – Improved translation accuracy for invoice labels across supported languages.

**Service Name Editing in Project Chat** – Resolved an issue that prevented users from saving changes when renaming service names directly in the Project Chat.

Fixed a bug with orders incorrectly showing up in Unscheduled orders&#x20;





## 4/17/2025

**Daily text reminders for photographers**\
You can now send automated daily text reminders to your photographers, letting them know how many appointments they have that day and when their first appointment begins.  As with all our text notifications, this feature can be enabled and customized in the **Configure Booking > General > Text Notification section.**<br>

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>



**Hide Package Savings Amount on the invoice**\
You now have the flexibility to show or hide the savings amount on an invoice. When this option is enabled, customers will not see the individual service prices or the total savings on their invoice.  This setting is specific to each booking flow and can be enabled by navigating to the **Booking Flow Settings** and toggling **"Hide Savings Amount."**<br>

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>



**Export Customer Stats from Reporting**\
The **Customer Stats** section in your reporting overview can now be exported in both **XLSX** and **CSV** formats, making it easier to analyze and share your data.<br>

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>



**Disable Automatic Calendar Duration Updates**\
You now have the option to prevent Tonomo from automatically updating calendar event durations when changes are made to an order. This is especially helpful if you're manually adjusting calendar events, such as splitting events or setting custom durations, and want to maintain full control without the system overriding the durations you have set.  You can enable or disable this behavior in **Configure Booking > General > Automatically update event duration**<br>

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>



**Xero improvements and bugfixes**\
We've resolved an issue where orders synced through the Xero integration were not updating their status from **Unsynced** to **Synced**. Orders will now correctly reflect their sync status after successful integration with Xero.





## 4/8/2025

**Add filter for orders with escalated services**\
For those who use the escalation feature for services, you can now filter orders to only show escalations.  This is very simple and there is a toggle to enable this filter right on the order management page.  Once the toggle is enabled you will only see orders with services that have been set as an escalation.

<figure><img src="../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

**Service-Based Appointment Scheduling** \
As part of a larger update, we’ve released the first phase of assigning services to specific appointments and photographers. You can now locate an order and use our scheduler tool to create new appointments for individual services within that order. This also allows you to assign different photographers to each appointment as needed. &#x20;

The first step is to find an order then open it in the scheduler,  then you will see the "schedule appointment" as shown on the screenshot.  Upon clicking on that you will be prompted to schedule an event only for the selected services.  At this stage you may also select the photographer that will be assigned to this specific appointment.

This will be continue to be improved over time and aims to solve issues like:

* Contractor reporting numbers being accurate when 2 or more photographers are assigned to an order
* Ability to be able to split up shoots into different appointments for different photographers
* Accurate calendar events for multiple photographers when there is more than 1 appointment.

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

**Batch invoicing for Xero**

Within Tonomo you can now select multiple invoices and batch them together and send just one invoice to Xero.  This will be especially helpful for companies working with large agencies that invoice on a weekly or monthly basis.  This is a very simple tool to use, you only need to have your Xero account connected to Tonomo and then select the invoices you want to batch and click the "batch" button as seen on the screenshot. This will combine the invoices together. (A standalone version of this feature for customers that aren't using Xero will be released soon) :

<figure><img src="../.gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

**Add custom message for date & time on Order status page -** Whenever you need to explain the date and time to a customer you can now add a custom message that will show on the order status page.  You can find this in your booking flow settings:<br>

<figure><img src="../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>



## 3/13/2025

For all our Xero users you can now sync an invoice to Xero right from the order management page by clicking on the order you want to sync then on the right hand side in the accounting tab click "sync to accounting"



<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

We now have a confirmation pop up when canceling and postponing orders on the Order Management tab to avoid mistakes and deleted calendar events.

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

Minor improvements:

* Update “3d Tour” to “3D Tour” for Consistent Capitalization
* Email validation (it is no longer possible to create users with same emails)
* Add a brokerages tab on the accounting setup page
* When moving multiple orders to “In progress” some orders will not create Dropbox folders is fixed.
* Blurry Images in the Luxury Real Estate Template on Mobile is fixed.
* Can’t scroll through the list of photographers on the mobile app has been fixed



## 2/13/2025

**Set Credit as the default payment method when credits are available**: Now when a client has credit on their account and is undergoing payment the credit will be the default option for them to pay.  This will avoid people paying with card and thinking they have already applied the credit.

**0$ orders are now marked paid automatically:**  Beforehand orders that were 0$ were still marked as unpaid, thus creating confusion for clients and having to ask to manually move the order to paid status.  This is no longer the case as any order for 0$ will be automatically marked paid.

**All day events in google now show as busy to Tonomo:**  Beforehand to block off time users would use an "all day event" in google calendar.  The issue was that Tonomo did not recognize this type of event and would not block off time.  This is no longer the case and creating "all day events" within your google calendar is now an effective way to block off time within tonomo.

Minor bug fixes and improvements:

* Changing photographers within scheduler will no longer keep the previous photographer as a guest&#x20;
* Slow invoicing page has been fixed
* Creation date filter on the order management page was not working.  This has been fixed
* Ability to hide the "is scheduling flexible" question



## 1/28/2025

**New fields now shown the the scheduler within order details:**  We have added the following fields to the scheduler view:

* Custom questions
* Entry notes
* Feature notes
* Service based questions
* Brokerage preferences
* Client preferences
*   Customer private notes\
    <br>

    <figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>



**Add configuration option to hide payment information in the Customer portal:** To improve clarity for customers who do not pay invoices directly, we implemented a way to hide all payment related information across the customer portal.  To activate this feature simply go to configure booking>general and in the visibility and access permissions section toggle the "limit customer access"  option to enabled.<br>

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

**Thumbnails are now available on the order management page:** Sometimes its easier to remember an order through an image rather than reading an address.  For that reason we have made it possible for you to turn on "cover" thumbnails in the order management page.  To do this simply click on the \
"+" symbol shown in the screenshot and check the cover option.  If there is media available for that order it will show the thumbnail on the left hand side.<br>

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

**Bug fixes and minor improvements:**

* We improved the viewing of listing websites on mobile phones to make it more efficient and less prone to errors.
* We made it so entering a phone number is no longer required when creating an order through the scheduler.
* Previously when you changed a photographer on an order, the previous photographer was kept as an additional guest inside Tonomo's scheduling section.  This has now been fixed to work correctly
* There was a bug that when an order was created through order management it was being marked as paid automatically and if a service was added to the order the payment status would move to "promised payment." This has also been corrected now.
* We fixed a bug that used to cause the photographer to get added to the customer's calendar event when updating an event through order management.
