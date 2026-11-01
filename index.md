# Kinraidee Privacy Policy

_Last updated: 1 November 2026_

Kinraidee (กินอะไรดี) helps you decide what to eat. This policy explains what data the app uses, where it goes, and the choices you have. Kinraidee is in development; this policy will be updated before public launch.

## Summary

- **Without an account**, your preferences, meal log, saved items and health data **stay on your device**.
- **If you sign in** (Google or LINE), they are also kept in your account on our server so all your devices stay in sync. Today's health readings always stay on your device.
- We **do not sell** your data, show ads, or use tracking or advertising SDKs.
- Health data is used **only** to suggest meals. It is never used for advertising and never shared with third parties.
- You can delete everything at any time: **Delete my data** (no account) or **Delete account** (signed in), in You → Settings.

## Data kept on your device

- Language, onboarding answers (spice level, cuisines, allergies/diet, budget, goal)
- Likes/skips, saved dishes and places, meal log (dishes, portions, nutrition estimates)
- Your chosen location or area
- Health data read from Apple Health or WHOOP (see below), and optional body details you enter (age, sex, weight, height)
- An anonymous random device ID (not linked to your name, email or phone)

## Accounts (optional)

Signing in is optional; the app works fully without it. You can sign in with Google or LINE. We receive your account ID and, depending on the provider, your name, email address and profile picture.

When you are signed in, we keep these in your account on our server:

- Language, onboarding answers, meal reminders, likes/skips and saved dishes and places
- Your meal log
- **With your health consent:** your body details (age, sex, weight, height) and your WHOOP connection. The WHOOP access tokens are encrypted, and only our server uses them, to get you short-lived access.

When you first sign in on a device, what is on that device is added to your account. Signing out removes your data from that device; it stays in your account. Each account's data can be read only by that account.

Not kept on our server: today's readings from Apple Health or WHOOP (calories burned, workouts, sleep, recovery, strain), and your location.

## Data sent to our server

Our server runs on Supabase (Singapore region).

- **Nearby places:** to find restaurants, the app sends the dish search term, your location and your anonymous device ID to our server, which asks Google Places. We store only place IDs and coordinates for a rounded area of about 2 km, shared by all users, for at most 30 days. To prevent abuse, we count requests per device ID per day and keep these counts for 7 days.
- **Place popularity:** when you tap Go or save a place, we store the place ID, the action, the date and your anonymous device ID, to rank popular places for everyone. Kept up to 90 days.
- **WHOOP sign-in:** when you connect WHOOP, our server exchanges the sign-in code for access tokens, because this step needs a secret key. Without an account, the tokens are returned to your device and not stored on our server. With an account, they are stored encrypted in your account (see above).
- **Account data:** see "Accounts" above.

## Health data

Health features are optional and start only after you give explicit consent in the app.

- **Apple Health (iPhone):** with your permission, Kinraidee reads active energy burned, workouts, sleep, weight, height, date of birth and biological sex, and writes the meals you log (energy, protein, carbohydrates, fat and dish names). When you are signed in, meals you log on another device (such as the web) are also written to Apple Health on your iPhone. You can change these permissions at any time in the Health app or iOS Settings.
- **WHOOP:** with your permission, Kinraidee reads recovery, sleep, cycles (strain and energy), workouts and body measurements. Kinraidee does not write to WHOOP. Meals you log may appear in WHOOP through Apple Health if you turn on WHOOP's own nutrition import. You can disconnect WHOOP in the app or in your WHOOP account.
- Health readings are processed on your device to estimate a calorie target and choose dishes. If you are signed in, only your body details and WHOOP connection are kept in your account, as described above. Health data is not sold, not used for advertising and not shared with anyone.

Kinraidee is a wellness tool, not a medical device, and does not give medical advice.

## Third-party services

- **Google Maps and Google Places:** maps and place names are provided by Google. Google's privacy policy applies to map loading: https://policies.google.com/privacy
- **Google and LINE sign-in:** if you choose to sign in, the provider's privacy policy applies to the sign-in step: https://policies.google.com/privacy and https://line.me/en/terms/policy/
- **Unsplash:** dish photos load directly from Unsplash servers: https://unsplash.com/privacy
- **WHOOP:** https://www.whoop.com/privacy/
- **Grab and LINE MAN:** the Order button copies the dish name and opens their app or website. We send them no data.

## Your rights

Under Thailand's Personal Data Protection Act (PDPA), you may access, correct, delete or withdraw consent for your data.

- Without an account, your data is stored only on your device; delete it with **Delete my data**.
- Signed in, **Delete account** permanently deletes your account and everything in it from our server, and disconnects WHOOP.
- Turning off health features in You → Health also removes your body details and WHOOP connection from your account.
- To revoke health access, use the Health app, iOS Settings or your WHOOP account, or disconnect WHOOP in the app.
- For the anonymous popularity and request records, contact us with your device ID, shown in Settings.

## Children

Kinraidee is not intended for children under 13.

## Changes

We will update this page when the app changes, and update the date above.

## Contact

Questions or requests: shinelerd@gmail.com
