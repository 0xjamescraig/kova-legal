---
title: Privacy Policy
permalink: /privacy/
---

# Kova — Privacy Policy

**Effective date:** August 12, 2026
**Last updated:** August 14, 2026

This Privacy Policy explains how James Craig, a sole proprietor operating as
"Kova" ("Kova," "we," "us"), handles your information in the Kova iPhone app. We
built Kova to be private by default: **we do not show ads, we do not sell your
data, and you can delete your account and all of your data from inside the app at
any time.**

If you have questions, contact us at **james20june@gmail.com**.

---

## 1. Who is responsible for your data

James Craig (a sole proprietor operating as Kova), located in Ontario, Canada, is
the controller (and, under Canadian law, the organization) responsible for your
personal information. For users in the EU/UK, we are the "controller" under the
GDPR/UK GDPR.

## 2. Information we collect

**You provide directly:**
- **Account** — when you sign in with Apple, we receive a unique identifier and,
  if you choose to share it, your name and email. If you use Apple's "Hide My
  Email," we only receive Apple's private relay address.
- **Profile** — sex, birth date, height, weight, goal weight, activity level,
  goals, dietary preferences/allergies, and time zone that you enter so the app
  can compute targets and personalize coaching.
- **Logs** — foods and water you log (name, calories, macros, source), and your
  daily journal check-ins (mood ratings and any free-text notes).
- **Coach messages** — the messages you send to the AI coach and the responses.
- **Meal photos** — photos you scan. See §4 — these are processed to identify
  foods and are **not stored** by Kova.
- **Health data (optional).** If you connect Apple Health, Kova reads your steps,
  sleep, workouts, resting heart rate, and heart-rate variability to sharpen your
  coaching, and writes the meals, water, and breathwork minutes you log back to
  Apple Health. You choose exactly what to share in the Health app and can
  disconnect at any time. This data is used only for your own coaching and **never
  appears in any shared, exportable, or public part of the app.**

**Collected automatically:**
- **Subscription status** (free/premium) and daily AI-scan usage counts.
- **Usage events** — basic first-party analytics about which features you use
  (for example: completing a scan, logging a meal, sending a coach message,
  viewing the paywall, saving a journal check-in), tied to your account, so we can
  understand usage and improve Kova.
- **Crash & performance diagnostics** — via Apple's MetricKit, we collect crash
  and hang diagnostics (technical data such as call stacks and device/OS info) to
  find and fix problems. These do **not** include the content of your logs, meal
  photos, journal, or coach messages.
- **Basic technical data** needed to operate the service (e.g., authentication
  tokens). We do **not** use third-party advertising or analytics SDKs — the above
  is first-party only, stored in our own database, and never sold.

## 3. How we use your information

- To provide the app's core features: meal scanning, food/water logging, the
  food database search, the AI coach, journaling, and your dashboard.
- To compute and personalize your nutrition targets and coaching.
- To operate subscriptions and enforce plan limits.
- To secure the service and prevent abuse.

We process this information to perform our contract with you (to provide the app),
and, where applicable, based on your consent or our legitimate interest in
operating and securing Kova.

## 4. AI processing (Google Gemini) — please read

Kova's meal scanning and AI coach are powered by **Google's Gemini API**.

- **Meal, receipt, and menu scans:** the photo you scan (a meal, a receipt, or a
  restaurant menu) is sent to Google's Gemini API to identify foods and estimate
  nutrition. **Kova does not store these photos** — the image is processed to
  produce the result and is not retained in our database.
- **AI coach:** your coach messages, together with relevant context from your own
  data (for example your targets, today's logged nutrition, and your latest
  journal check-in), are sent to Google's Gemini API to generate grounded
  responses. Your coach conversation is stored in your account so the coach can
  remember context; you can delete it by deleting your account.
- **Plate Twin (optional).** When you open your day's Plate Twin, Kova generates
  one artistic flat-lay image of that day. **Only the names of the foods you
  logged that day are sent to Google's Gemini API to generate the image — nothing
  else: not your identity, not any photos, not your journal, and not your calorie
  or macro numbers.** The generated image is stored privately in your own account
  (a private, owner-only storage bucket) and is never public; older images are
  deleted automatically. Google processes the food names as our service provider
  to return the image and does not use them for advertising.
- **Apple Health signals in coaching (optional).** If you connect Apple Health,
  body signals for a day — resting heart rate, heart-rate variability, sleep, and
  steps — may be sent to Google's Gemini API **as part of your own private
  coaching** (your Day Audit reflection). They are used only to generate that
  reflection for you and are **never rendered into an image or shown in any shared,
  exportable, or public part of the app**. The Pulse Check's resting-heart-rate
  baseline is computed and kept **on your device only** — it is never sent to
  Google or to our servers.

Google processes this data as our service provider to return results to Kova.
**Under the paid Gemini API, Google does not use your prompts or the content Kova
sends to train or improve its models.** We do not use this content for
advertising, and we do not sell it. Google's handling of Gemini API data is
governed by Google's terms; see
<https://ai.google.dev/gemini-api/terms> and <https://policies.google.com/privacy>.

**AI estimates are approximations, not medical or dietary advice.** Nutrition
figures are AI-generated estimates; where a food is matched, we link its source
in the U.S. Department of Agriculture (USDA) FoodData Central database.

## 5. Nutrition data sources (USDA and Open Food Facts)

Food search and citations use **USDA FoodData Central**, a public U.S. government
database. When you search or when a scanned food is matched, we send the food
term (not your personal information) to USDA to retrieve nutrition data.

Food search also uses **Open Food Facts**, a community database of packaged
products, to cover branded items. As with USDA, we send only the food term (not
your personal information), and where a result comes from Open Food Facts we
credit it in the app ("Data from Open Food Facts"). Open Food Facts data is made
available under the Open Database License (ODbL).

## 6. Who we share information with (sub-processors)

We do not sell your personal information and we do not share it for advertising.
We use a small set of service providers to run Kova:

| Provider | Purpose | Notes |
|---|---|---|
| **Supabase** | Database, authentication, and backend hosting | Your data is stored in **Postgres hosted in Canada (ca-central-1)** |
| **Apple** | Sign in with Apple; subscription billing | Governed by Apple's Privacy Policy |
| **Google (Gemini API)** | AI meal/receipt/menu analysis, coach responses, and Plate Twin images (§4) | Processes photos transiently + coach context + food names for Plate Twin |
| **USDA FoodData Central** | Nutrition data source (§5) | Receives food terms only, no personal data |
| **Open Food Facts** | Branded/packaged food data (§5) | Receives food terms only, no personal data; data under ODbL |

**Apple Health:** if you connect it, your health data is read and written **on your
device**, and Apple Health is not a sub-processor. Your body signals are **never
shown in any shared, exportable, or public part of the app**, and the Pulse Check
baseline stays **on your device**. The one exception is your **own private
coaching**: as described in §4, a day's body signals may be sent to Google's Gemini
API to generate your reflection, and are used for nothing else.

## 7. Where your data is stored and processed

Your Kova account data is stored in **Canada** (Supabase, ca-central-1). Some
processing necessarily occurs outside Canada — for example, Apple (authentication
and payments) and Google (Gemini AI processing) may process data in the United
States or other countries. Where we transfer personal data internationally, we
rely on appropriate safeguards as required by applicable law (including, for the
EU/UK, standard contractual clauses used by these providers).

## 8. Data retention and deletion

We keep your information for as long as your account exists. **You can delete your
account at any time in the app: Settings → Delete account.** Deletion is
permanent and removes your profile, logs, journal, and coach history from our
database, along with any Plate Twin images stored in your private bucket. Meal,
receipt, and menu photos are never stored, so there is nothing to delete there.
Plate Twin images are also deleted automatically after about 30 days. Backups, if
any, are cycled out on a rolling basis.

If you connect Apple Health, the Pulse Check heart-rate baseline is stored **only
on your device** and is removed when you delete the app; a day's body signals used
for a coaching reflection are sent to Google transiently (see §4) and are not
stored by us beyond your coach history. A check-in you open from a Pulse Check is
saved with a small context tag (for example, "elevated stretch") in your account
so the coach has context; it is deleted when you delete your account.

## 9. Your rights

Depending on where you live, you have rights over your personal information:

- **Canada (PIPEDA):** access to and correction of your personal information, and
  the ability to withdraw consent.
- **EU/UK (GDPR):** access, rectification, erasure, restriction, portability,
  objection, and the right to lodge a complaint with your supervisory authority.
- **U.S. states (e.g., California/CPRA, and similar laws):** the right to know,
  access, delete, and correct, and the right to opt out of "sale"/"sharing" and
  targeted advertising. **We do not sell or share your personal information and we
  do not use it for targeted advertising**, so there is nothing to opt out of.

You can exercise most of these rights directly in the app (edit your profile;
delete your account). For anything else, email **james20june@gmail.com** and we
will respond as required by law. We will not discriminate against you for
exercising your rights.

## 10. Security

Data is encrypted in transit (HTTPS/TLS). Access to your data is protected by
per-user database security rules so that you can only access your own records.
Sensitive keys (AI and other service credentials) are held server-side and never
shipped in the app. No method of transmission or storage is 100% secure, but we
work to protect your information.

## 11. Children

Kova is built for adults and is rated 17+ on the App Store. It is not directed to
children under 13 (or the minimum age required in your country), and at sign-up we
ask your date of birth and **do not create an account for anyone under 13**. We do
not knowingly collect personal information from children under 13. If you believe a
child has provided us information, contact us and we will delete it.

## 12. Changes to this policy

We may update this policy from time to time. We will change the "Last updated"
date above and, for material changes, provide notice in the app.

## 13. Contact

James Craig (operating as Kova)
Ontario, Canada
james20june@gmail.com
