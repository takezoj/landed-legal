---
title: Landed Privacy Policy
permalink: /privacy-policy.html
---

# Landed Privacy Policy

**Effective date:** August 21, 2026
**Last updated:** September 10, 2026

*This is a first draft written to reflect exactly what the Landed app does today. It isn't legal advice — have a lawyer review it.*

## 1. Who this covers

This policy applies to Landed, a mobile app that helps you keep track of your travel bookings — flights, hotels, cars, and more — in one place.

## 2. What we collect

**Account information.** When you sign in with Google, we receive your Google account's basic profile information (name, email address) to create your Landed account.

**Gmail access (optional).** If you choose to connect your Gmail account, Landed requests **read-only** access to your Gmail so it can search for booking confirmation emails (flights, hotels, trains, etc.) and add them to your trip list automatically. Landed can never send email from your account, delete anything in your inbox, or modify your messages. Only the content of emails that look like booking confirmations is processed — Landed doesn't read or store your inbox generally.

**Booking and trip data.** Whatever you enter yourself (manually or via the Gmail auto-detection above) — trip names, dates, flight numbers, hotel names, confirmation numbers, vendor names, notes, and to-do items you add for a trip.

**We do not collect:** location data, payment or financial information, contacts, photos, or any data unrelated to organizing your travel bookings.

## 3. How we use it

Every use of your data exists solely to provide or improve the features described in this policy — organizing your travel bookings inside Landed. We never use your data for any unrelated purpose.

- To show you your bookings and trips inside the app.
- To detect new booking confirmations in your connected Gmail account (if you've connected one) and add them to your list for your review.
- Email content that looks like a booking confirmation is sent, automatically and without human review, to Anthropic's Claude API for the sole purpose of extracting structured details (dates, vendor, confirmation number, etc.) so that booking can be added to your trip list. This processing exists only to power this one in-app feature — the extracted email text is not used for any other purpose, is not used to train any AI/ML model, and is not retained by Landed beyond this one-time extraction (see Section 5).

We do not use your data for advertising, and we do not sell your data to anyone.

**Limited Use compliance.** Landed's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Gmail data is used exclusively to provide the booking-detection feature described above, is never used to train or improve any generalized AI/ML model, and is never transferred to any party except as necessary to provide that feature (Anthropic, solely for the one-time extraction described above) or as required by law.

## 4. Who we share data with

Landed uses a small number of service providers to run the app. Each only receives the data it needs to do its job, solely to provide Landed's own features to you — never for the service provider's own independent use, advertising, or model training:

- **Google** — for sign-in and, if you connect it, read-only Gmail access, per Google's API Services User Data Policy.
- **Anthropic** — receives only the text of a candidate booking email, solely to extract structured booking details for that one feature (Section 3). Anthropic does not use API data to train its models, per Anthropic's standard commercial API terms, and Landed does not use this integration for any purpose beyond this one feature.
- **Supabase** — hosts our database and authentication system. Your data is stored in Supabase's infrastructure.

We don't share your data with any other third party, and we don't sell it.

## 5. How long we keep your data

We keep your data as long as your account exists. You can delete individual bookings, trips, or to-do items at any time in the app. You can also **permanently delete your entire account and all associated data** at any time from Settings → Danger Zone → Delete Account. This is immediate and can't be undone.

## 6. Your choices

- As of this writing, deleting your account (see above) is the way to fully revoke Landed's Gmail access — there isn't yet a way to disconnect Gmail on its own while keeping the rest of your account.
- You can review, edit, or delete any booking or trip in the app at any time.
- You can delete your account and all your data at any time (see above).
- You can also revoke Landed's access to your Google account directly from your [Google Account permissions page](https://myaccount.google.com/permissions).

## 7. Security

We use industry-standard practices to protect your data, including per-user data isolation at the database level (row-level security) so no user can access another user's data. No method of storage or transmission is 100% secure, and we can't guarantee absolute security.

## 8. Children's privacy

Landed is not directed at children, and we don't knowingly collect data from anyone under 13.

## 9. Changes to this policy

If this policy changes in a meaningful way, we'll update the "Last updated" date above and make a reasonable effort to notify you, such as through an in-app notice.

## 10. Contact

Questions about this policy or your data? Contact landedconcierge@gmail.com.
