# Guide to Google reCAPTCHA

## What is Google reCAPTCHA?

From the [Google reCAPTCHA](https://www.google.com/recaptcha/intro/index.html) page:

> reCAPTCHA is a free service that protects your website from spam and
> abuse. reCAPTCHA uses an advanced risk analysis engine and adaptive
> CAPTCHAs to keep automated software from engaging in abusive activities
> on your site. It does this while letting your valid users pass through
> with ease.

Your site comes with the Google reCAPTCHA module pre-installed.

## Adding reCAPTCHA to web forms

Google reCAPTCHA challenges are automatically added to web forms, so long as
the reCAPTCHA module is properly configured. You do not need to take any
steps to add a reCAPTCHA challenge to web forms.

> **Note:** You will not see the reCAPTCHA challenge when logged in as
> an authenticated user. To test the web form with reCAPTCHA enabled,
> log out or enable your browser's privacy mode.

## Configuring the Google reCAPTCHA Module

> **Note:** If your website is managed by CCS Web Solutions, the
> Google reCAPTCHA module will be configured for you when your site is
> launched. Only attempt to configure the reCAPTCHA module
> with your site key if you host the site yourself.

Before you can configure the reCAPTCHA module, you must 
[register for the reCAPTCHA service](https://www.google.com/recaptcha/admin)
to obtain a site key and secret key.

> **Note:** If your website is managed by CCS Web Solutions, you **do not**
> need to register for the reCAPTCHA service or obtain keys.

After you have registered for the service and obtained your keys:

1. Log in to your site as administrator.

2. Go to Administration >> Configuration >> People >> CAPTCHA >> RECAPTCHA
   (admin/config/people/captcha/recaptcha).

3. Enter your site key and secret key.

4. Click *Save Configuration*.

