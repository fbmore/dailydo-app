# DailyDo — App Store Listing (1.6)

Paste into App Store Connect → DailyDo (app 6751297766). Fill in **both** the iOS and the macOS
version pages. Character counts are in brackets.

## App Name (30)

`DailyDo: Capture Anything` [25]

Currently "Daily-Do" in App Store Connect, presumably because "DailyDo" alone was taken. Try the
name above first; the home-screen name stays **DailyDo** either way (`CFBundleDisplayName`).

## Subtitle (30)

`Tasks, notes, links & podcasts` [30]

Alternates: `One inbox for your whole day` [28] · `Capture first, organize never` [29]

## Promotional Text (170, editable without a new build)

`Capture anything, then share it, work on it together with the people in it, or print it as a calendar or a list. Synced privately across iPhone, iPad and Mac.`

## Description (4000)

iOS (the Mac version drops the alarms line and says "A calendar view of everything that's due." instead of the widgets line):

```
Everything in your head, in one place.

Capture anything, share it, work on it together, and print it in the right order. Type it, paste it, say it, or share it from any app, and DailyDo works out what it is: a task with a reminder, a note, a link, a timer, a document, or a podcast to play. No folders to choose, no forms to fill, no account to create.

CAPTURE ANYTHING
• "Pick up prescription tomorrow at 5pm" becomes a task with a reminder.
• Paste a URL and it becomes a link, titled automatically.
• Jot a long thought and it becomes a note, with a title written for you on your device.
• Paste a podcast or RSS feed and you're subscribed.
• Share into DailyDo from Safari, Photos, Mail or any app, or paste from the clipboard.
• Dictate, or record voice notes with automatic transcription.
• Ask Siri: "Add a task in DailyDo", "What's due today in DailyDo?", "Start a timer in DailyDo".

SHARE IT
• Send tasks as a link other DailyDo users tap to import, or as plain text for anyone.
• Publish notes, checklists, photos and files as a web page that opens in any browser, no app needed. Pages expire on their own, and you can take one down any time.

WORK ON IT TOGETHER
• Share an item with the people in it: a packing list, a shopping run, a plan.
• Everyone you invite can edit, check things off, and see who else is on it.
• Shared through iCloud with only the people you invite. Stop sharing whenever you like.

PRINT IT, IN THE RIGHT ORDER
• Print any task list straight from its menu, with every item, on as many pages as it takes.
• As a calendar, with a column for each day, or as a list with dates, tags and notes.
• Items without a date get their own page, so nothing is left off. Uncheck anything you don't need.

TASKS THAT HOLD THE LINE
• Reminders with Mark Done and Snooze right from the notification.
• Alarms that break through Focus for the things you can't miss.
• Repeating tasks you can complete day by day, with streaks.
• A calendar view, and Home Screen widgets for what's pinned, overdue and due today.

MORE THAN A TODO LIST
• Notes with checklists, links, and a reading list that builds itself.
• Podcasts: a built-in player with Up Next, speeds and transcripts.
• Multi-stage timers for cooking, workouts and focus sessions.
• Documents: scan with text recognition, snap photos, attach files.
• Tags with colors, twelve accent colors, light, dark and Night Mode.

PRIVATE UNTIL YOU SHARE IT
• No account. No sign-up. No ads. No analytics.
• Your data lives on your device and syncs through your own private iCloud.
• Smart features run on your device.
• Nothing reaches anyone else unless you send it, collaborate on it, or publish it.

IPHONE, IPAD AND MAC
One purchase, everywhere: your items stay in sync across all your devices through iCloud.

FREE TO START, PRO TO GO BIG
DailyDo is free for up to 50 active items, and completed items never count. Capture is never blocked. DailyDo Pro removes the limit:
• Pro Monthly: $2.99 per month
• Pro Yearly: $24.99 per year, with a 14-day free trial
• Lifetime: $69.99, one-time purchase
Prices are in USD and vary by country. Subscriptions renew automatically unless cancelled at least 24 hours before the end of the current period; your Apple Account is charged for renewal within 24 hours before the period ends. Manage or cancel any time in Settings → [your name] → Subscriptions. Any unused free-trial time is forfeited when you buy a subscription.

Terms of Use: https://getdailydo.com/terms.html
Privacy Policy: https://getdailydo.com/privacy.html
Apple's Standard EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
```


## Keywords (100)

`tasks,todo,notes,reminders,capture,checklist,share,collaborate,print,calendar,timer,voice,podcast`

## What's New in 1.6

```
• Print any task list from its menu, as a calendar or a list, with every item (including ones with no date) on as many pages as it takes. Uncheck what you don't need.
• Publish notes, checklists, photos and files as a web page anyone can open, no app needed. Pages expire on their own.
• Siri: add tasks (with alarms) and notes, ask what's due today, mark tasks done, open items and start timers.
• Published pages use the accent color you picked in Settings → Appearance.
```

## Categories and rating

- **Primary:** Productivity · **Secondary:** Utilities
- **Age rating:** no objectionable content, but answer **Yes to Unrestricted Web Access** while saved links open in the in-app browser with free navigation (see `APP_STORE_READINESS.md`).
- **Copyright:** `2026 FRANCESCO BERTOCCI, LLC`

## URLs

- **Support:** https://fbmore.github.io/dailydo-app/support.html
- **Marketing:** https://fbmore.github.io/dailydo-app/
- **Privacy Policy:** https://fbmore.github.io/dailydo-app/privacy.html
- **License Agreement:** keep Apple's standard EULA. Our terms link to it and are linked in the description.

## App Privacy questionnaire

Answer **"Yes, we collect data"**. The only collector is RevenueCat (purchases). Everything users
create lives on their device and in their own private CloudKit database, which the developer can't
read, so it is **not** collected.

| Data type | Collected | Linked to identity | Tracking | Purpose |
|-----------|-----------|--------------------|----------|---------|
| Purchases → **Purchase History** | Yes | No | No | App Functionality |
| Identifiers → **User ID** (RevenueCat anonymous app user ID) | Yes | No | No | App Functionality |
| Everything else (contact info, location, contacts, user content, browsing, search, usage, diagnostics) | No | — | — | — |

Rationale, from the audit's data inventory:
- There's no account, so the anonymous ID can't be tied to a person. That makes it "not linked".
- There are no analytics or crash reporting, so nothing falls under Usage Data or Diagnostics.
- Websites, podcast publishers, `itunes.apple.com` and `isbnsearch.org` are contacted directly by the device for the user's own requests. They are not sent to the developer, and Apple's definitions don't count them as collected.

## Review Notes

```
DailyDo needs no account and no demo login. All content is stored on the device and synced through the user's private iCloud (CloudKit private database).

In-app purchases: DailyDo Pro (ddpro_monthly, ddpro_annual with a 14-day trial, ddpro_lifetime) removes the 50-active-item limit. To see the paywall: Settings → DailyDo Pro, or create more than 50 active items (completed items don't count). Restore Purchases and Manage Subscription are on the paywall.

Permissions are requested only when a feature needs them: notifications for reminders, camera for scanning/photos/QR, microphone and speech for dictation and voice notes, photos for attaching and saving images, contacts for saving detected phone numbers as contacts.

The same app runs on iPhone, iPad and Mac (Mac Catalyst) and syncs through iCloud.
```

## Screenshots (1.6, uploaded)

Fictional `-demo` data, made with `scripts/store-screenshots.sh` and `scripts/store-screenshots-mac.sh` in the app repo
(`-demoScreen print | share | collaborate` open the new sheets). The ordered sets are in the app repo at
`marketing/screenshots/appstore-1.6/{iphone,ipad,mac}`.

| # | Screen | Story beat |
|---|--------|-----------|
| 1 | Quick Create (iPhone/iPad only) | Capture anything |
| 2 | Tasks: pinned, overdue, today, tomorrow | Your day, sorted |
| 3 | Share Tasks: Link / Text / Page | Share it |
| 4 | Shared packing list with two collaborators | Work on it together |
| 5 | Print sheet: Calendar / List, every item checked | Print it, in the right order |
| 6 | Notes | Notes that title themselves |
| 7 | Links | A reading list that builds itself |
| 8 | Search "lisbon" across everything | Find anything |
