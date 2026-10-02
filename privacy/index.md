---
title: "ArthaVibes Privacy Policy"
permalink: /privacy/
---

# ArthaVibes Privacy Policy

Last updated: 3 October 2026

ArthaVibes is a personal income and expense tracker for Android. This policy explains what the app does with
your information. The short version: **everything stays on your phone. We do not collect, receive, sell or
share any of your data.**

## 1. The app has no internet access

ArthaVibes does not have Android's internet permission, so it cannot send anything off your phone. There are
no accounts, no servers, no analytics, no advertising and no crash-reporting services in the app. Premium
purchases go through the Google Play Store app on your phone (section 5a), not through ArthaVibes.

## 2. SMS messages

This applies to the standard version of ArthaVibes. The "lite" version does not ask for SMS access and never
reads SMS.

**Why the app reads SMS.** Banks, cards and wallets send an SMS for most payments. ArthaVibes reads these
messages to add your income and expenses automatically, so you do not have to type them. This is the app's
main feature.

**You choose.** Before Android asks you for SMS permission, the app shows a screen that explains what it reads
and why. You can say no and still use the app by adding transactions yourself. You can turn SMS tracking off
at any time in **Settings > SMS auto-tracking**, or remove the permission in your phone's settings.

**What is read.** When you turn SMS tracking on, the app checks the messages in your SMS inbox from the period
you choose (for example the last 3 months), and then each new SMS as it arrives.

**What is kept.** All checking happens on your phone.

- From a message sent by a bank, card or wallet that describes a payment, the app keeps only the details of
  the transaction: amount, date, whether money came in or went out, the last digits of the account or card,
  the merchant or payee name, the reference number, and the sender's name (for example "HDFCBK").
- Messages from people (sent from a phone number), one-time passwords (OTPs) and offers are dropped as soon as
  they are recognised. Nothing from them is saved: not the text and not the phone number. The app only records
  a one-way fingerprint (a SHA-256 hash) of each message it has already checked, so it does not check the same
  message twice. The message cannot be read back from this fingerprint.
- The text of your messages is **not** saved, unless you turn on **Settings > Keep raw SMS text**. If you do,
  the text of messages from bank, card and wallet senders is saved in the app's encrypted database on your
  phone, so you can see which message a transaction came from. Turning the setting off deletes the saved texts.
  Messages from people are never saved, even with this setting on.

**What is never done.** Your SMS messages, and anything taken from them, are never sent to us or to anyone
else, never used for advertising, credit scoring or lending, and never sold.

## 3. Other information you enter

Transactions you add by hand, categories, accounts, budgets, recurring entries and notes are saved only on
your phone, in the same encrypted database. Your settings are kept in a separate settings file on your phone;
it contains no amounts, messages or names.

## 4. How your data is protected

- The app's database is encrypted (SQLCipher, AES-256). The encryption key is protected by your phone's
  Android Keystore and never leaves the phone.
- You can turn on **App lock**, so the app asks for your fingerprint, face or screen lock before it opens.
  While App lock is on, the app's screens are also hidden from screenshots and from the recent-apps preview.
- Android's automatic cloud backup is turned off for ArthaVibes, so your data is not copied to a cloud backup
  by the app.

## 5. Permissions the app asks for

Android asks you before the app can use these:

| Permission | Why |
| --- | --- |
| SMS (read and receive; standard version only) | To add transactions from bank, card and wallet messages (section 2) |
| Notifications | To tell you when a budget reaches 80% or 100%, and to show progress while the first SMS scan runs. Optional |

The app also uses permissions that Android grants without asking: biometric (for App lock, only when you turn
it on), and a few that let Android's background task system run scheduled work, such as adding recurring
entries on their dates, even after the phone restarts, and Google Play billing (to buy Premium, section 5a).
None of them give access to the internet.

## 5a. Premium purchases

Premium is bought through Google Play. Google handles the payment under
[Google's privacy policy](https://policies.google.com/privacy); we never see your card, UPI or bank details.

- From Google Play the app receives only what it needs to unlock Premium: which product you own (monthly,
  yearly or lifetime), whether it is paid, pending or renewing, and a purchase token. It keeps an encrypted note
  on your phone that Premium is active, so Premium keeps working when you are offline.
- The app gives Google Play a random identifier created on your phone, so purchases can be matched to this
  install. It is not your name, email address or phone number.
- No transactions, amounts, merchants, categories, accounts or SMS details are ever sent to Google Play.

## 6. Backups and exports

You can save a backup file, a CSV spreadsheet, or a PDF or Excel report of your transactions from **Settings**. The app writes these
files only when you ask, to the place you choose with Android's file picker. After that, the file is under
your control: if you save it to a cloud folder or share it, the privacy policy of that service applies. Backup
files never contain SMS text.

## 7. Deleting your data

- **Settings > Delete all data** permanently deletes every transaction, category, account, budget, recurring
  entry and saved SMS detail from the app. Your settings and Premium purchase are kept.
- Uninstalling the app deletes all of its data from your phone.
- We cannot delete or recover your data for you, because we never have a copy of it.

## 8. Sharing

We do not share any data with anyone, because we do not receive any. The app contains no third-party
services that collect data. Payments for Premium are handled by Google Play (section 5a).

## 9. Children

ArthaVibes is meant for adults (18 and over) and is not directed at children.

## 10. Changes to this policy

If the app changes how it uses your information, we will update this policy and the "Last updated" date
above, and describe the change in the app's release notes. If a change would ever mean sending data off your
phone, the app would ask for your permission first.

## 11. Contact

Questions or concerns about privacy: **support@arthavibes.in**
