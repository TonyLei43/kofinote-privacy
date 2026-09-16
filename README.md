# KofiNote Privacy Policy

_Last updated: 16 September 2026_

KofiNote is a café notebook. Most of what you put into it never leaves your
phone. This page says exactly what does, where it goes, and how to remove it.

## What stays on your device

None of the following is ever uploaded, and we cannot see it:

- Your visit and order log — dates, drinks, prices, ratings and notes
- Photos you attach to an entry
- Your reviews, and the traits and tags you record about a café
- List covers and background images you choose
- Any list you have not explicitly chosen to share

This data lives in the app's own storage on your device. Deleting the app
deletes it permanently, and there is no backup of it on our side.

## What we collect

### Your account

Signing in is required to use KofiNote, because the friends features need a
stable identity. We use **Firebase Authentication** (Google) with Sign in with
Apple or Sign in with Google. Firebase stores a user ID and the email address
your provider supplies. If you use Apple's "Hide My Email", Apple gives us a
relay address instead of your real one.

We never see your Apple or Google password.

### Your profile

Stored in **Firebase Realtime Database** (Google):

- Your display name
- Your handle — the name other people type to find you
- Your emoji avatar
- Your profile photo, if you set one, resized to a 128-pixel square

Your profile is readable by any signed-in KofiNote user, so that someone who
knows your handle can find you. It deliberately contains nothing sensitive.

### Your friends

Who you are friends with, and any pending friend requests. A friend request
carries a copy of the sender's profile so the recipient can see who is asking.

### Lists you choose to share

Nothing is shared automatically. When you share a list, we upload that list's
name, description, and a snapshot of each café in it — its name, address,
coordinates and public Google rating. Only your friends can read it. Stop
sharing at any time from the list's menu, and the copy is deleted.

### Your location

If you grant location access, your coordinates are sent to the **Google Places
API** to find cafés near you and to show how far away they are. This is a
request-and-response: your location is not stored on our servers, and it is
never attached to your account or your identity.

## Third parties

- **Google Firebase** — authentication and database. [Google Privacy Policy](https://policies.google.com/privacy)
- **Google Places API** — café search and café details. [Google Privacy Policy](https://policies.google.com/privacy)

We use no advertising networks and no analytics services.

## Tracking

We do not track you. KofiNote contains no advertising identifiers, no
cross-app or cross-site tracking, and no third-party analytics. We do not sell
or share your data with data brokers.

## Deleting your data

**Your account:** Profile → Settings → **Delete account**. This immediately
removes your profile, handle, avatar, friend connections and any shared lists
from our servers, and deletes your authentication record. It cannot be undone.

Your local café log, photos and reviews are **not** affected by account
deletion, because they were never uploaded. To remove those, delete the app.

**A note on friends:** if a friend has you in their list, removing yourself may
leave your user ID in their copy until they next refresh, at which point you
disappear from it. No profile data of yours remains readable.

## Children

KofiNote is not directed at children under 13, and we do not knowingly collect
information from them.

## Changes

If this policy changes, the date at the top changes with it. Material changes
will be announced in the app's release notes.

## Contact

Questions about this policy or your data: please
[open an issue on this repository](https://github.com/TonyLei43/kofinote-privacy/issues).
