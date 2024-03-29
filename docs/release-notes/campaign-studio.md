# Classy Studio release notes

## 2024

### January 16

<span class="tag tag--feature">:material-party-popper: Features</span>

- Style and copy updates to the Donation Form to accommodate smaller devices.
- Donation Form button text colors will automatically switch between black and white depending on the background color to meet WCAG 2.0 AA standards.
- Admins can now update the background color of the Share and Social Links buttons.
- Update the design of Social Links to accommodate smaller screens better and add accessibility features.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Updated campaign page titles from “Donate to {NPO Name}” to “Donate to {Campaign Name}”.

#### Checkout

<span class="tag tag--feature">:material-party-popper: Features</span>

- Relocated the “Cover Transaction Fees” checkbox to align with itemized donation information on the summary.

- Added the ability to turn off Plaid in the event an organization wants to use the legacy accounting/routing manual method.

- Added commas to relevant number fields.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed issue where source codes weren’t being tracked.

- Fixed validation issue where birthday “year” input field was accepting single digits.

- Fixed validation issue where birthday “year” input field was red (indicating an error) on page load.

- Fixed issue where Program Designation was blank on the transaction record.

## 2023

### December 12

<span class="tag tag--feature">:material-party-popper: Features</span>

- Ability to place custom code blocks in sections with other blocks

- Email performance/deliverability statistics - **Note:** We identified a bug preventing Opened, Clicked, and Failed statuses from updating, so all emails are marked as Sent. We're working on a fix to include in our next release.

- PDF receipts

- Email Footer and Page footer updated to “Powered by Classy - A GoFundMe Company”

- When “Stretch to fit” is selected on an image element, it will stretch the full width and height of the section, assuming it is the only block in that section.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Several bug fixes for minor issues in the checkout experience

### November 15

<span class="tag tag--feature">:material-party-popper: Features</span>

- Classy for Salesforce integration compatibility (version 7.2 Julian and above)

- Omatic integration compatibility

- Facebook Sharing

- Supporter Chosen Program Designations

- Additional GA4 Custom Events

  - GA_purchase event

- Comment with Donation

- Dedication Emails

- Dedication Ecards

- Duplicating emails with Campaign Duplication

### October 25

#### Campaign Management

<span class="tag tag--feature">:material-party-popper: Features</span>

- Double the Donation Support

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed an issue where organizations with the full spelling of their organization state name could not create a new Studio campaign.

- Fixed an issue where the scroll bar was not appearing in step 2 of the campaign creation process.

#### Email

<span class="tag tag--feature">:material-party-popper: Features</span>

- Admins can now send test emails to themselves.

### October 5

#### Campaign Pages

<span class="tag tag--feature">:material-party-popper: Features</span>

- Redirect URLs for inactive campaigns.

- Donation Form design enhancements.

- Updated 404 page title and URL.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed issue with Footer displaying incorrect contact information.

#### Campaign Management

<span class="tag tag--feature">:material-party-popper: Features</span>

- Ability to turn on or off recurring end dates.

- Ability to duplicate a campaign.

- Admins can now choose whether the donor can hide their donation amount.

- Primary Phone number is no longer required.

- Custom Questions can now be reordered on the checkout page.

- There is a new option on image elements that allows you to set the image to the full width of a section.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed an issue where you were not able to choose a new default Program Designation after campaign creation.

- Fixed an issue where the anonymous donation option was always available to supporters even when toggled off in the builder.

- Fixed an issue where users were not able to publish their campaign based on checkout settings.

- Fixed an issue where 401 errors were displaying when the page was not in use for a certain period of time.

#### Email

<span class="tag tag--feature">:material-party-popper: Features</span>

- Admins can now send test emails to themselves.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed issue that prevented saved colors from displaying in color picker after refreshing the page.

#### Checkout

<span class="tag tag--bug">:material-bug: Fixes</span>

- Fixed issue where Venmo payment button was showing for unsupported browser/OS combos.

- Fixed issue where primary phone was always required.

- Fixed issue that prevented PayPal donations from being completed.

- Fixed issue where digital wallet card type wasn’t updating the donor covered fee amount.

### September 21

#### Email

<span class="tag tag--feature">:material-party-popper: Features</span>

- Admins can use the “merge tag” dropdown to add dynamic values to email text (e.g. “First name,” “Campaign name,” etc.)

- Admins can now apply links to email text and configure those links to open in a new tab.

<span class="tag tag--bug">:material-bug: Fixes</span>

- Logo images can now be added and configured for email headers

- Email footer now populates with campaign and org level settings for campaign contact and organization address.

!!! note

    This fix populates campaign/org settings only when the message is sent. A future update will display these values when viewed in the email builder.
