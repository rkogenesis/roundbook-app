# RoundBook: test builds

RoundBook is an Android app for doctors to keep track of their patients on rounds, in the ICU and in
OPD: census, notes, vitals, labs with trends, tasks, handover sheets, discharge summaries, bedside
calculators, thesis data and a duty log.

It works **fully offline**. The app has no internet permission, no account and no servers. Everything
you enter stays on your phone, encrypted.

This page only hosts test builds for invited testers. The source code is not public.

## Install
1. Open **[Releases → latest](https://github.com/rkogenesis/roundbook-app/releases/latest)** on your
   Android phone or tablet and tap the `.apk` file under *Assets*.
2. When Android asks, allow your browser or file app to **install unknown apps** (only needed once).
3. Open RoundBook, read the first screen, and turn on the **app lock** when it asks.

To update, install the newer `.apk` the same way. It installs over the old one and **keeps your data**.
Android 8.0 or newer.

## Please, while testing
- **Use dummy or de-identified patients.** This is a test build.
- **Turn on automatic backup:** Settings → Automatic backup, and choose a folder that syncs (for
  example Google Drive). Your data exists only on your phone, so if the app is removed or the phone
  is lost, a backup is the only way to get it back.
- Screenshots are blocked by default to protect patient data. To send a screenshot of a problem,
  allow them in Settings → Security, and make sure no real patient details are visible.

## Feedback
Tell the person who invited you what was confusing, slow or broken. **Never post patient
information anywhere, including in GitHub issues.**

## Check your download (optional)
Every release lists the SHA-256 of its APK. All builds are signed with the same key, certificate
SHA-256 `2d2e24d6fbd508b845032f260019ca420aba3833a53082e46d62b59be930dbe8`.

RoundBook is decision support only. It is not a medical device or a hospital record. Check every
result against the source and your own judgement.

© 2026 Sahil Nain. All rights reserved.
