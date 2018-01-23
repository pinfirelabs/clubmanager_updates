# New features
## Stored credit cards in the POS system
For our customers using Stripe, you can now run charges in the POS against stored credit cards of your members, as well as updated cards as an admin.  

![Saved cards in POS](https://cloud.headwayapp.co/changelogs_images/images/big/000/010/659-524f0f327b6165c1b63f5f8bbb39d83f3258b1f2.png)

## Saved event searches and calendar export
We've added a new ability to save event searches and export those to any iCal compatible client such as Google Calendar, Outlook or Apple iCal.  You can use this to integrate your events calendar from PCM into any other planning or calendar software you run.

## More granular recurring membership controls
For our customers on Stripe, we now offer some new, more granular controls over membership signup and cancellation.  We offer a switch to disable member signup and/or cancellation.  We've also added the ability to start a recurring membership at a later date.  Combined, this will assist clubs that have a cancellation window and/or initiation fee.

Administrators can now also create recurring memberships on behalf of their customers and manually override pricing as desired for one-off scenarios.

## Custom theming layer
We've added the basis for overriding the look and feel of the general layout and specific pages in our system so that we can better match the look of your organization's marketing website.  Contact us if you'd like a quote on a custom theme to change the look and feel of PCM to more closely match your website.

## Ensure all customers have a valid liability waiver
We now offer the option to force every person who interacts with your system to have a valid liability waiver on file.  With this option enabled (contact support@pinfirelabs.com), if someone logs into PCM and doesn't have a waiver on file, we force them to agree to continue using the platform.  

## Improvements to youth and family accounts
In addition to enforcing waiver signatures, we also track the name of the person who signed the waiver, allowing better enforceability, especially when registering children.  Also, during the password reset process, we now ask for the email AND first name of the user being reset.  This way, if there are multiple people with the same email (usually the case with a family with children), we ensure we reset the proper account.

Stay tuned next year for fully linked family and child accounts.

## Improved reservations calendar display
We now show header rows on the events calendar on a per-equipment-category basis allowing you to clearly group your boats together for bookings.

![Reservation calendar header rows.PNG](https://cloud.headwayapp.co/changelogs_images/images/big/000/010/658-8e23d0f3c19458f0c92c5d4069e2f786ceec4ce0.png)

## "Crew finder" reservation support
We now don't check for reservation overlap on items with the "allow multiple loans" flag.  With this, you can create dummy items, allowing members to create "crew finder"-type events for dinghies, even if you do not individually reserve those boats.  This allows them to post restricted events on the calendar other members can register for, without giving them full access to post any event.

# Small Improvements
* We've completely rewritten our equipment inventory page to better handle large amounts of equipment over multiple locations for our largest clubs.
* You can now use any custom field as a token in an email template, allowing you to have more granular customization over your organization's emails.
* We added the ability to have non-public custom fields on events so you can store staff-related information about classes that can be hidden from members.  You can also use a non-public custom field to customize your event-related emails to be event-specific as all custom fields can now be used in email templates.
* We can now enable the "online order receipt" to be sent for recurring membership renewals, allowing you to notify your members every time they are charged.
Coupons can now be used in the POS system, allowing you to offer discounts to your customers and members when purchasing in person.
* We added the ability to export results of a leadership position search to CSV so you can export contact information about your club leaders to a format of your choosing.
* The "event listing" custom report now shows the category of events, allowing for more granular reporting.
* We greatly improved the ability of our events calendar and event listings to be embedded in other websites via &lt;iframe&gt;.  Contact us to get special links to embed your PCM events calendar into your website.
* Once your members enter the checkout process for events or memberships, we block out all other links in the system, helping to drive conversions and purchases.
* Since we now handle liability waivers on a club-wide level (see 9/2016 release notes), we renamed the "liability waiver" field on events to "event policies" to better describe its current use.
* We can now add a delay to "event follow up" emails allowing you send them some number of hours past the end of an event, versus at midnight the following evening (as it was before).
* We added a new "membership revenue" custom report showing you member counts and revenue on a monthly basis.
* We now display the dates of purchased events on invoices to make it easier for customers to track their purchases.
* We now show a clarification on the create new account page to make it clearer for parents to create an account in their child's name when registering for youth camps.
** Stay tuned early next year for a much-improved youth registration process!

# Bug fixes
* We fixed a bug in our membership reports so we now consider all members within a time frame, not just those that began their membership within it.
* If you allow members to create maintenance requests, but not view the whole maintenance list, we now redirect to the home page instead of the view request page, preventing a permissions error once requests are created.
* We better handle the acquisition of credit cards on a phone when processing with Stripe.
* We now hide the option to "purchase a membership" or add a membership to your cart if there are no online-purchasable membership types for your organization.
* We fixed some bugs with write-in candidates when running elections through PCM.
* We fixed some bugs relating to multi-quantity line-item refunds.
* We fixed a bug where emails sent through our email lists would show the wrong domain on the FROM address.
* We fixed a bug, so that we now warn, but do not prevent purchase of, memberships that start in the future.

# Upcoming Features
We have many new features slated for development this summer and fall which will help you streamline your operations.  Stay tuned for:

## Credit card processing improvements

* Through a relationship with CardConnect and Clover, we will be able to allow larger clubs to open their own merchant accounts.  This will lead to lower processing rates and also allow for the taking of physical credit cards.
    * We will be integrating with Clover POS terminals, allowing clubs to realize significantly lower credit card processing fees.
* Favorites screens, bar tabs and tipping support in the POS system.  If your club has a restaurant or bar, we can now help you manage it!
* Improved coupon support including percentage-based coupons and membership, date and usage restrictions.  
    * Want to offer 20% classes for members?  We will soon be able to help you achieve that, and enforce it.
* Email campaigns.  We are working on integrating a drag-and-drop email newsletter creator, allowing you to create beautiful emails to send to your customers/members, directly from the PCM interface.
* Want to restrict reservations for club members to specific time slots or other criteria?  We will soon be offering equipment reservation business rule restrictions.
* Many more new features and additions not listed here!
