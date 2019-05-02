# Webform

Drupal's Webform module allows you to collect information from site users. After a webform submission, users as well as adminsitrators can receive confirmation. Results can be exported into Excel or other spreadsheet applications.

_**/! Note**_: If Google reCAPTCHA is not enabled on your site please email your Drupal Contact at CCS or email ccs.websolutions@uoguelph.ca to enable this feature.

## Creating a Webform

### Basic Form Details

1. From the Administration bar, navigate to `Add content` &gt; `Webform`.
2. Enter a title for your webform and click `Save.`

### Form Components

1. Start adding components by entering the component label and the type of component it is, then click `Add`.
2. You can set any type of field as mandatory or optional.

#### Add Textfield or Textarea

A textfield is for short entries like names, while a textarea is a large area for longer responses.

1. Fill in a new label and choose the **Textfield** or **Textarea** type from the drop down menu. Click `Add`, and complete the options on the next screen.
   * On the next screen, you can specify the **Maxlength** of a textfield, a placeholder, or any prefix or postfix that you want to appear in the textfield.
   * You can also enable a textarea to be resizeable.

#### Add a "Select" field

1. Fill in a new label and choose the **Select options** type from the drop down menu. Click `Add` and complete the options on the next screen.
2. To create the list of options, go to `Options` and create Key Value Pairs.
   * These pairs consist of a machine readable key and a plain language value separated by a "\|" - you can find it by holding shift while pressing the backslash key "\" key on most keyboards.
3. Key value pairs MUST be specified as **safe\_key\|Some readable option**.
4. Enter one option per line.
5. Click `Save component`.

NOTE: When you are creating lists, the default type is radio buttons. The option to select a listbox instead is found down the page in the "Display" section. For accessibility reasons, do not use the radio buttons or checkboxes option, as these options are not screen reader friendly will fail accessibility checks.

### Configure E-Mail options

#### Receiving the submitted webform

1. Go to the `WEBFORM` tab and click on the `E-mails` sub-tab
2. Fill in the e-mail address you want the form to be sent to and click `Add`. You can add multiple e-mail addresses.
3. On the next page, you can set the Subject, From Address, From Name, and E-mail contents.

#### Sending a Confirmation Email to Users who have Submitted a webform

**Step 1a – Ensure that the webform has an Email input field \(using Type: E-mail\).**

1. Under `Find content`, search for your Webform and select `Edit`.
2. Select the `Webform` tab.
3. Select the `Form components` tab.
4. Under the list of form components, search for the Email form component that captures the email address for the confirmation email.
   * If there is an Email form component and the **Type** is `E-mail`, proceed to Step 2.
   * If there is an Email form component, but the **Type** is not `E-mail` proceed to Step 1b.
   * If there is no Email form component and you wish to add one, proceed to Step 1c.

**Step 1b – Delete the old Email input field that is not using Type: E-mail**

This step is only necessary if the “Type” for your Email form component is not `E-mail`.

1. At this point, you should be viewing the Webform/Form components tab of your webform. If you are not viewing this page, return to Step 1a.
2. Take note of any settings for the Email input field you wish to delete \(eg. Label, Required checkbox\). Remember that you will want to recreate these settings when you recreate the Email input field.
3. Select `Delete` on the Email form component row.
4. Proceed to Step 1c.

**Step 1c – Create a new Email input field that uses Type: E-mail**

1. At this point, you should be viewing the Webform/Form components tab of your webform. If you are not viewing this page, return to Step 1a.
2. At the bottom of the Form components table, use the very last row to add a new component.
   * Add the name of your new component using the **New component name** input field.
   * Select `E-mail` under the "Type" dropdown for your new component row.
   * Check `Required` if the email field is required.
   * Select `Add`.

**Step 2 – Configure your webform to send confirmation emails to users.**

At this point, you should have at least one Email form component on your webform that uses Type: `E-mail`. If you do not have an Email form component of type `E-Mail`, return to Step 1c.

1. Under `Find content`, search for your webform.
2. Select `Edit`.
3. Select the `WEBFORM` tab.
4. Select the `E-mails` tab.
5. Click on the `Component value` radio button and select the component of the webform that captures the email address \(it should match the label for your "Email" field\).
6. Click on the `Add` button.
7. On the next page, you can set the E-mail subject, E-mail From Address, E-mail From Name, and E-mail contents.
8. Once you’ve set the email details, click `Save e-mail settings`.

