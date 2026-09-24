# MacroMuscle Privacy Policy

**Effective date:** September 24, 2026

MacroMuscle is an iOS workout and nutrition tracking app developed by Matt Fisher
("we", "us"). This policy explains what data the app handles and what happens to it.
The short version: **your data stays on your device**, with one optional
exception — the AI Macro Estimation feature, described below, which you must
turn on and use deliberately.

## Data the app stores

MacroMuscle stores the following data **locally on your device only**:

- Workout history — exercises, sets, weights, reps, training blocks, and plans
- Nutrition logs — foods, meals, calories, and macronutrients
- Body weight entries and weight goals
- Profile details you enter — body weight, height, and activity level
- App settings and preferences

There are no accounts, no sign-ups, and no servers operated by us. We cannot see,
access, or recover your data. If you delete the app without exporting a backup,
your data is gone.

## Data that leaves your device

### Crash and diagnostic data (Firebase Crashlytics)

If the app crashes, an anonymous crash report (stack trace, device model, OS
version, and app version) is sent to Google's Firebase Crashlytics service so we
can find and fix the bug. Crash reports:

- are **not linked to your identity** — we have no accounts, so there is nothing
  to link them to,
- **never contain your health data** — weights, nutrition entries, and workout
  contents are never included in logs or crash reports,
- are not used for advertising or tracking of any kind.

You can read Google's privacy documentation for Crashlytics at
<https://firebase.google.com/support/privacy>.

### AI Macro Estimation (optional)

MacroMuscle can estimate a food's calories and macros from a photo or a text
description you provide. This feature is off until you turn it on, and only
runs when you actively submit a photo or description — nothing is sent
automatically.

To use it, you enter your own API key for an AI provider you choose:
**Anthropic, OpenAI, or Google**. When you submit a photo or description,
it is sent directly from your device to that provider using your key.
MacroMuscle does not operate any of these services, does not see or store
the results anywhere but your device, and is not a party to how your
chosen provider handles the request beyond relaying it. Your API key is
stored in this device's Keychain, never in backups, and never sent
anywhere except to the provider you chose as part of your own requests.

This request is **not linked to your identity** — MacroMuscle has no
accounts, and the request only carries the key you supplied. It is billed
to your own account with that provider, not to us. Review the privacy
policy of whichever provider you choose:

- Anthropic: <https://www.anthropic.com/legal/privacy>
- OpenAI: <https://privacy.openai.com/policies>
- Google: <https://policies.google.com/privacy>

### Purchases (Apple)

Tips and the optional support subscription are processed entirely by Apple's
App Store. We never see your payment details. Apple's privacy policy applies:
<https://www.apple.com/legal/privacy/>.

## Apple Health (HealthKit)

If you enable **Health sync** in Settings, MacroMuscle will:

- **write** the body-weight entries you log in the app to Apple Health, and
- **read** new body-weight entries from Apple Health into the app.

HealthKit access is entirely optional and off by default. Health data is used
only to display and sync your weight inside the app. It is **never sent to us
or to any third party, never used for advertising or marketing, and never used
for any purpose other than the sync you enabled.** You can revoke access at any
time in the Health app under Sharing, or by turning the toggle off in
MacroMuscle's Settings.

## Tracking

MacroMuscle does **not** track you. There are no ads, no analytics identifiers
shared across apps, no data sales, and no third-party tracking SDKs.

## Your control over your data

- **Export** — Settings → Data Management → Export Data produces a complete
  backup file you own.
- **Delete** — Settings → Data Management → Clear All Data permanently erases
  everything, or simply delete the app.

## Age rating

MacroMuscle is rated 18+ on the App Store and is not directed at, marketed
to, or intended for use by anyone under 18. We do not knowingly collect
personal information from anyone under that age, including children under 13
(the age COPPA specifically protects).

## Changes to this policy

If the app's data practices change (for example, a new optional integration),
this policy will be updated and the effective date revised before the change
ships.

## Contact

Questions or concerns: **macromuscle.support@gmail.com**
