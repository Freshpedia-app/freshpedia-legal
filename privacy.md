---
title: Privacy Policy
---

# Freshpedia Privacy Policy

**Last updated: October 30, 2026**

Freshpedia ("the app", "we", "us") is a guide that teaches you how to pick fresh food at the store.
This policy explains what the app does and does not do with your information.

The short version: **the app has no accounts, never asks who you are, and does not sell your information.**
Nearly everything works on your device.
Two things leave it, and both are explained in full below: the "Check it" camera feature, which only runs when you start it, and a purchase check that asks whether this installation has paid.

## Information we collect

**We do not collect any personal information.**

The app has no accounts, no sign-up, and no login.
We never ask for your name, phone number, location, contacts, or payment details, and we never ask for access to your photo library.

**One feature sends something, and only when you use it.** "Check it" lets you photograph an item so the app can tell you what it is and how ripe it looks.
Reading the ripeness needs a server, so that picture is sent to be read and then immediately discarded.
The next section describes exactly what happens.

**The app also checks whether you have paid.** When it starts, and when you buy or restore, it asks our purchase service whether this installation holds a paid unlock.
That check carries a random identifier created for this purpose - not your name, your email, or your store account.
"Purchases" below describes exactly what is sent and why.

Nothing else in the app sends anything.

The other thing that can leave your phone only leaves it if **you** send it: the "Report a problem" link in Settings opens your own email app with a message addressed to us.
See "Contacting support" below for exactly what that message contains.

The app does not include analytics, advertising, tracking, or crash-reporting services, and it does not build a profile of you or your activity.

## The camera and "Check it"

"Check it" lets you point the camera at an item so the app can tell you what it is and how ripe it looks.

**We ask for camera access the first time you use the feature**, at the moment you use it, and the app explains why before your phone asks.
You can say no.
Everything else in the app keeps working without it - the guides never need the camera - and you can turn the permission off again at any time in your phone's settings.

The app uses the camera **only while you are on the Check it screen**.
It has no access to your photo library, it never reads photos you already have, and it never saves the picture it takes to your gallery.
The picture is held in the app's own private storage while you are looking at the result - so you can change which item it was without taking another one - and is deleted the moment you leave that screen.

### What happens to the picture

**Working out what the item is happens on your phone.**
Recognising that you are holding an avocado is done entirely on your device, and that step never sends the picture anywhere.

**Judging how ripe it looks needs a server.**
For that step, and only that step, the picture is sent over an encrypted (HTTPS) connection to our own service, hosted by Cloudflare, which passes it to **Google's Gemini API** to be read.
The answer comes back, and **the picture is discarded immediately.**

We do not store it, we do not keep a copy, we do not use it to train anything, and it is never attached to you or to anything else you have done in the app.
Google processes it for us under its API terms and does not use it to train its models.

Meat and fish are never sent at all.
The app will happily tell you what a cut of meat is, but it will not judge freshness from a photograph - your nose and hands are far better at that - so there is nothing to send.

### The identifier that travels with each check

Each check carries **a random identifier that your device creates the first time you use the feature**.
It is not your name, your email, your phone's ID, or anything that can be traced back to you.

It exists for exactly one purpose: our server counts how many checks that identifier has made this week, so the feature stays within its limit.
That count is stored on our server against the random identifier, expires on its own, and has nothing else attached to it.

### When you have no signal

The ripeness read is the one part of the app that needs a connection.
Without one the app says so plainly and still shows you the hand-checks - the things a camera could never judge anyway, like weight, smell, and give.

## Information stored on your device

The app saves a small amount of information locally on your device so it can remember your choices between sessions:

- **Saved items.** The guides you mark as favorites.
- **Purchase status.** Whether premium content has been unlocked on this device.
- **Your shopping list.** Items you add to the in-app list, including any item names you type yourself, quantities, which recipes an item came from, whether you have ticked it off, and when it was added.
- **Sampler position.** Which guide is currently open as the free "Fruit of the Week", and when it last changed.
- **A random identifier for "Check it".** Created on your device the first time you use the camera feature, and used only to count checks against the weekly limit, as described above.

Apart from that identifier - which is sent with each check and nothing else - this information is stored only in the app's private storage on your device.
It is never transmitted to us, and we cannot see it.
Deleting the app removes it from your device.

**One thing worth knowing about backups.** If you have Android's backup turned on, your phone may copy this app's saved data to **your own Google Drive**, the same way it does for your other apps.
That is why your favorites and shopping list can reappear when you reinstall the app or set up a new phone.
That backup belongs to your Google account, not to us - we have no access to it and cannot read it.
If you want to remove it as well, delete the app's backup from your Google account's backup settings.

## Content and offline use

All guides, photographs, and reference material are bundled inside the app itself.
Browsing guides does not require an internet connection, and opening a guide sends no request to us.
The app does check your purchase status when it starts - see "Purchases" - but that check carries nothing about what you read, and the guides work offline either way.

The one exception is the ripeness read in "Check it", which needs a connection because the reading happens on a server.
Identifying an item and every hand-check the app teaches work offline.

## Contacting support

Settings has a "Report a problem" link.
Tapping it opens **your own email app** with a message already addressed to us, pre-filled with three technical details so we can reproduce the problem: your **device manufacturer and model**, your **operating system version**, and the **app version**.

Nothing is sent unless you press send in your own mail app, and you can delete any of it first.
If you do send it, we receive those details and - because it is an ordinary email - the address you sent it from.
We use it only to answer you and fix the problem.

The app never emails us on its own.

## Purchases

The app offers optional paid content.

When you make a purchase, the transaction is handled entirely by **Google Play** (or the **Apple App Store** on iOS).
Those services process your payment and share only a confirmation that a valid purchase exists so the app can unlock your content.

**We never receive, see, or store your card number, billing address, or other payment details.**

### Keeping track of what you have paid for

We use **RevenueCat**, a purchase-management service, to tell the app whether this installation holds a paid unlock.

When the app starts, and when you buy or restore a purchase, it sends RevenueCat a **random identifier** that RevenueCat generates for this installation, the **purchase receipt** issued by the store, and basic technical details such as your platform and app version.
RevenueCat verifies the receipt with Google or Apple and answers yes or no.
It stores that purchase history against the random identifier, which is what lets you restore a purchase after reinstalling or on a new device.

**RevenueCat is not given your name, your email, or your store account**, because the app has none of them and never asks the store for them.

This check is also what makes refunds and cancellations work honestly: without it, a refunded or cancelled purchase would stay unlocked on the device indefinitely.

RevenueCat acts as our processor and handles this data only to provide this feature: https://www.revenuecat.com/privacy

Payments are governed by the store's own privacy policy:

- Google Play: https://policies.google.com/privacy
- Apple: https://www.apple.com/legal/privacy/

## App updates and technical data

When the app checks for or downloads an update, that request goes to our update provider (Expo) or to the app store.
Like any internet request, this may involve standard technical information such as your IP address and device type, which those providers handle under their own privacy policies.
We do not use this information to identify you, and we do not receive a record of your individual activity.

## Children's privacy

The app is a general-audience shopping guide and is not directed at children under 13.
It asks no one for personal information, so it asks none of children.
A photo taken with "Check it" is read and discarded without being stored, so nothing from it is retained about anyone.
If you believe a child has provided us personal information, please contact us - though in practice the app provides no way for this to occur.

## Data sharing

We do not sell, rent, or trade your information, and we never transfer anything to advertisers, data brokers, or analytics companies.

Three companies handle data on our behalf, each for one feature and nothing else:

- **Cloudflare** hosts the service your "Check it" photo is sent to, for as long as the check takes. It also stores the weekly count described above.
- **Google** reads that photo through its Gemini API and returns the answer.
- **RevenueCat** confirms whether this installation holds a paid unlock, and stores the purchase history against a random identifier. See "Purchases" above.

All three act as our processors: they handle this data to provide the feature and for nothing else.
They do not receive your name, your email, or any account of yours, because the app has none.

## Your rights and choices

Because no personal information reaches us, there is nothing for us to retrieve, correct, or delete on your behalf.
"Check it" photos are not stored, so there is no photo of yours for us to hold or hand back; the weekly count is kept against a random identifier that means nothing without your device, and it expires on its own.

You remain in full control:

- **To stop the app using the camera**, turn off the camera permission in your phone's settings, or simply do not use "Check it". Nothing else in the app depends on it.
- **To delete all app data**, uninstall the app. That removes the random identifiers from your device. The purchase history held by RevenueCat and by the store outlives it on purpose - it is what "Restore purchases" reads.
- **To manage or cancel a subscription**, use your Google Play or Apple App Store account settings.
- **To restore a previous purchase**, use "Restore purchases" in the app's Settings screen.

## Security

The app stores information only in its own private storage on your device, so your data is protected by your device's own security, such as your screen lock and the operating system's app sandboxing.

Everything the app sends - a "Check it" photo, and the purchase check - travels over an encrypted HTTPS connection.
The photo is discarded as soon as it has been read.

## Changes to this policy

We may update this policy as the app changes.
If we ever add a feature that collects personal information - for example, accounts, analytics, or advertising - we will update this policy and the app's Google Play Data Safety disclosure before that feature becomes active.

The "Last updated" date at the top of this page always reflects the current version.

## Contact

Questions about this policy or about privacy in the app:

**Email:** freshpediallc@gmail.com

**App:** Freshpedia
