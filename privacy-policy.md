---
title: Landed Privacy Policy
permalink: /privacy-policy.html
---

# Landed Privacy Policy

**Effective date:** August 21, 2026
**Last updated:** October 7, 2026

*This is a first draft written to reflect exactly what the Landed app does today. It isn't legal advice — have a lawyer review it.*

## 1. Who this covers

This policy applies to Landed, a mobile app that helps you keep track of your travel bookings — flights, hotels, cars, and more — in one place.

## 2. What we collect

**Account information.** When you sign in with Google or Apple, we receive the basic profile information they share (such as your name and email address; with Apple you can choose to hide your email behind a private relay address) to create your Landed account. If you use Landed without signing in, we create an anonymous account for you with a random account ID instead. Your account ID is used to keep your data separate from everyone else's.

**Gmail access (optional).** If you choose to connect your Gmail account, Landed requests **read-only** access to your Gmail so it can search for booking confirmation emails (flights, hotels, trains, etc.) and add them to your trip list automatically. Landed can never send email from your account, delete anything in your inbox, or modify your messages. Only the content of emails that look like booking confirmations is processed — Landed doesn't read or store your inbox generally.

**Booking and trip data.** Whatever you enter yourself (manually or via the Gmail auto-detection above) — trip names, dates, flight numbers, hotel names, confirmation numbers, vendor names, addresses, notes, budgets and expenses you track, and to-do items you add for a trip.

**Photos and documents.** If you attach photos or documents to a trip or booking, they are uploaded and stored with your account so you can view them later, including offline. Landed only accesses the specific photos or files you choose to attach; it doesn't read your photo library in general.

**Notification data.** If you turn on notifications, we store a push notification token for your device so we can send you reminders and "new bookings found" alerts.

**App diagnostics.** To find and fix bugs, Landed sends crash reports, performance data, and device and app information (such as device model, operating system version, and app version) to our error-monitoring provider, Sentry. This can include short, masked recordings of app screens, in which text and images are hidden so your booking details are never visible. This data is linked to your account's technical identifiers, and we use it only to keep the app stable.

**We do not collect:** location data, payment card or bank account details (budgets and expenses are only amounts you type in yourself), contacts, advertising identifiers, or any data unrelated to organizing your travel bookings. We do not track you across other companies' apps or websites.

## 3. How we use it

- To show you your bookings and trips inside the app, including your photos and documents.
- To send you reminders and notifications you've turned on.
- To detect, diagnose, and fix crashes and performance problems.
- To detect new booking confirmations in your connected Gmail account (if you've connected one) and add them to your list for your review.
- Email content that looks like a booking confirmation is sent to Anthropic's Claude API to extract structured details (dates, vendor, confirmation number, etc.) from the email text. This is an automated process — no one at Landed reads your email manually.

We do not use your data for advertising, and we do not sell your data to anyone.

## 4. Who we share data with

Landed uses a small number of service providers to run the app. Each only receives the data it needs to do its job:

- **Google** — for sign-in and, if you connect it, read-only Gmail access, per Google's API Services User Data Policy.
- **Anthropic** — processes the text of candidate booking emails to extract structured booking details. Anthropic does not use API data to train its models, per Anthropic's standard commercial API terms.
- **Supabase** — hosts our database, file storage (for photos and documents), and authentication system. Your data is stored in Supabase's infrastructure.
- **Sentry** — receives crash reports, performance data, and masked app-screen recordings so we can fix bugs. We configure it to avoid sending your booking details.
- **Expo and Apple** — deliver push notifications to your device using your device's push token.

We don't share your data with any other third party, and we don't sell it.

## 5. How long we keep your data

We keep your data as long as your account exists. You can delete individual bookings, trips, photos, or to-do items at any time in the app. Diagnostic data sent to Sentry is kept for a limited period under Sentry's standard retention settings and is not used for anything else. You can also **permanently delete your entire account and all associated data** at any time from Settings → Danger Zone → Delete Account. This is immediate and can't be undone.

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
