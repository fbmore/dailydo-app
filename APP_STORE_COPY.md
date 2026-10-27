# DailyDo — App Store Listing (1.3)

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

> Type it, paste it, say it or share it: DailyDo turns it into a task with a reminder, a note, a link or a podcast. Synced privately across iPhone, iPad and Mac. [159]

## Description (4000)

```
Everything in your head, in one place.

DailyDo is the fastest way to get a thought out of your head and into the right place. Type it, paste it, dictate it, or share it from any app, and DailyDo works out what it is: a task with a reminder, a note, a link, a timer, a document, or a podcast to play. No folders to choose, no forms to fill, no account to create.

SMART CAPTURE
• "Pick up prescription tomorrow at 5pm" becomes a task with a reminder.
• Paste a URL and it becomes a link, titled automatically.
• Jot a long thought and it becomes a note, with a title written for you on your device.
• Paste a podcast or RSS feed and you're subscribed.

CAPTURE FROM ANYWHERE
• Share into DailyDo from Safari, Photos, Mail or any app.
• Smart paste from the clipboard.
• Voice dictation and voice notes with automatic transcription.
• Home Screen widgets show what's pinned, overdue and due today.

TASKS THAT HOLD THE LINE
• Reminders with Mark Done and Snooze right from the notification.
• Alarms that break through Focus for the things you can't miss.
• Repeating tasks you can complete day by day, with streaks.
• Postpone to tomorrow or a week out in one tap.

MORE THAN A TODO LIST
• Notes, links and a reading list that builds itself.
• Podcasts: a built-in player with Up Next, speeds and transcripts.
• Multi-stage timers for cooking, workouts and focus sessions.
• Documents: scan with text recognition, snap photos, attach files.
• Tags with colors, twelve accent colors, light, dark and Night Mode.

PRIVATE BY DESIGN
• No account. No sign-up. No ads. No analytics.
• Your data lives on your device and syncs through your own private iCloud.
• Smart features run on your device.

IPHONE, IPAD AND MAC
One purchase, everywhere: your items stay in sync across all your devices through iCloud.

FREE TO START, PRO TO GO BIG
DailyDo is free for up to 50 active items, and completed items never count. Capture is never blocked. DailyDo Pro removes the limit:
• Pro Monthly: $2.99 per month
• Pro Yearly: $24.99 per year, with a 14-day free trial
• Lifetime: $69.99, one-time purchase
Prices are in USD and vary by country. Subscriptions renew automatically unless cancelled at least 24 hours before the end of the current period; your Apple Account is charged for renewal within 24 hours before the period ends. Manage or cancel any time in Settings → [your name] → Subscriptions. Any unused free-trial time is forfeited when you buy a subscription.

Terms of Use: https://fbmore.github.io/dailydo-app/terms.html
Privacy Policy: https://fbmore.github.io/dailydo-app/privacy.html
Apple's Standard EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
```

[2,675]

## Keywords (100)

`tasks,todo,notes,reminders,capture,checklist,timer,scanner,ocr,voice,memo,podcast,gtd,inbox,planner` [99]

(No "DailyDo", no "app", no words already in the name or subtitle.)

## What's New in 1.3

```
• Widgets now focus on what matters: pinned, overdue and today's tasks.
• Repeating tasks can be completed day by day, independently.
• New "Postpone a Week" in task menus; moving a date in Quick Create reschedules the task.
• Night Mode: red on black, easy on your eyes at night (Settings).
• DailyDo for Mac, synced with your iPhone and iPad through iCloud.
• DailyDo Pro: unlimited active items. Free stays free for up to 50.
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

## Screenshot plan

Sizes: iPhone 6.9" (1320×2868), iPhone 6.5" (1284×2778), iPad 13" (2064×2752), Mac (2880×1800).
The site's `shots/` folder already has light/dark captures for most of these screens.

| # | Screen | Caption |
|---|--------|---------|
| 1 | Quick Create mid-typing "call the pharmacy tomorrow at 5", chip shows Task | Type it. DailyDo files it. |
| 2 | Tasks tab: Today, overdue and pinned | Your day, sorted for you |
| 3 | Share sheet from Safari into DailyDo | Capture from any app |
| 4 | Notes list with auto titles | Notes that title themselves |
| 5 | Podcast player with Up Next | Your podcasts, right next to your tasks |
| 6 | Document scan with recognised text | Scan it, search it |
| 7 | Accent picker / Night Mode | Make it yours |
| 8 | iPad + Mac side by side | iPhone, iPad and Mac, privately synced |
| 9 | Paywall | Free for 50 items. Pro for everything. |
