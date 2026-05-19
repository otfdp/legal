# Privacy Policy

**Last updated: 2026-05-17**

> This policy describes what data Color by Nonogram ("the App", "we") collects, how it's used, and your rights.
>
> **This is a draft prepared by the developer, not legal counsel.** Have it reviewed by a lawyer in your jurisdiction before publishing — local privacy laws (GDPR in the EU/UK, CCPA in California, LGPD in Brazil, etc.) impose specific disclosure requirements this template approximates but does not guarantee.

## Who we are

Color by Nonogram is published by **otfdp**. For privacy questions, requests, or to exercise your rights, contact **privacy@otfdp.com**.

## What we collect

### Anonymous account
When you first launch the App, we create an anonymous account with our backend provider (Supabase). This account is identified by a randomly-generated UUID. It is not linked to your name, email, phone number, or any other identifier from your device or app store account, unless and until you choose to sign in with an email later (currently a future feature).

### Game state
We store the following per anonymous account, on our backend:

- Puzzle progress (which puzzles you've started, solved, your best times)
- In-app currency state (energy balance, last regen timestamp)
- Entitlements (which packs / palettes / ads-removed status you own)
- Aggregate progression (total cells solved, derived level)

The same data is also cached locally on your device for offline play.

### Repaint canvas (free-fill mode)
After completing a puzzle, you can repaint it. Your custom color choices are stored **only on your device** and never sent to our backend.

### Device-level settings
We store local-only settings on your device: sound on/off, haptics on/off, auto-pick-next-picross preference, cell size, completed onboarding flag.

### Advertising identifiers
On native (iOS / Android) builds, our ad partner (Google AdMob) may read your device's advertising identifier (IDFA on iOS, GAID on Android) to deliver and measure ads. On iOS 14+, we are required to ask your permission first via the App Tracking Transparency prompt. You can decline; ads will still be served but will not be personalized.

In the European Economic Area, the UK, and Switzerland, we present Google's UMP consent form on first launch. You may withdraw consent at any time via **Settings → Privacy options**.

### Purchases
In-app purchases (packs, energy refills, remove-ads) are processed by Apple App Store or Google Play. Your payment information (card details, billing address, etc.) is handled entirely by Apple or Google and is **never seen by us**. We receive only:

- A transaction ID confirming the purchase succeeded
- The product ID purchased

These are stored against your anonymous account for entitlement tracking.

### What we do **not** collect

- Your name, email, postal address, phone number (unless you create an email account later)
- Your contacts, photos, microphone, camera, or precise location
- Any data from outside this App

## How we use what we collect

| Purpose | Data used |
|---|---|
| Saving and syncing your progress across reinstalls | Anonymous account + game state |
| Showing ads (and being paid for them) | Advertising ID, consent state, ad interactions |
| Granting entitlements after purchase | Transaction ID, product ID |
| Improving the App (aggregate analytics only) | Aggregate progression data |

We do not sell personal data. We do not share data with third parties except as listed below.

## Third parties

The App relies on these services, each with its own privacy policy:

- **Supabase** (backend storage and authentication) — https://supabase.com/privacy
- **Google AdMob** (advertising) — https://policies.google.com/privacy
- **Apple App Store** (iOS in-app purchases, app distribution) — https://www.apple.com/legal/privacy/
- **Google Play** (Android in-app purchases, app distribution) — https://policies.google.com/privacy

## Your rights

Depending on your jurisdiction, you may have the right to:

- **Access** the data we hold about you
- **Correct** inaccurate data
- **Delete** your data ("right to be forgotten")
- **Export** your data in a portable format
- **Object** to processing for direct marketing or analytics
- **Withdraw consent** for advertising at any time

To exercise any of these rights, email **privacy@otfdp.com** with a description of your request. Because accounts are anonymous, we may ask you to provide the anonymous account ID shown in the App's Settings screen so we can locate your data. We will respond within 30 days.

You can also:

- **Disable personalized ads** at any time by opening the **Privacy options** link in Settings (EEA/UK/CH users), or by revoking tracking permission in iOS Settings → Privacy & Security → Tracking.
- **Reset your advertising identifier** in your device's settings.

### California residents (CCPA / CPRA)

You have the right to know what categories of personal information we collect (listed above), to request deletion, to opt out of "sale" or "sharing" of personal information (we do not sell, and only "share" data with advertising partners as described above), and to non-discrimination for exercising these rights.

### EEA / UK residents (GDPR / UK GDPR)

Our legal basis for processing is:

- **Performance of a contract** (delivering App features you use)
- **Consent** (for personalized ads, where required)
- **Legitimate interest** (for non-personalized service operation and analytics)

You have the right to lodge a complaint with your local data protection authority.

## Children

The App is not directed to children under 13 (or under 16 in the EEA). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, contact **privacy@otfdp.com** and we will delete it.

## Security

Data in transit between the App and our backend is encrypted via HTTPS. Data at rest in our backend is encrypted by the provider (Supabase). Anonymous accounts have no associated credentials and cannot be "hacked into" in the traditional sense; however, no service is 100% secure, and we cannot guarantee absolute security.

## Data retention

Account data is retained while your anonymous account is active. If you delete the App from your device, your local cache is removed, but the anonymous account on our backend persists indefinitely so that reinstalling on the same device restores your progress (subject to platform-specific identifier rules). To permanently delete all data, email **privacy@otfdp.com**.

## Changes to this policy

We may update this policy from time to time. Material changes will be surfaced in the App on next launch. The "Last updated" date at the top reflects the most recent revision.

## Contact

**privacy@otfdp.com**
