---
title: Privacy Policy
permalink: /privacy/
description: "Maxie does not collect, store, or transmit any of your data. Read our full privacy policy."
---

# Maxie — Privacy Policy

**Last updated:** May 19, 2026

Maxie is an iPhone photo-cleanup app. We believe the simplest privacy
policy is the truest one: **Maxie does not collect, store, or transmit
your personal data.**

## What Maxie does on your device

When you grant photo access, Maxie:

- Scans your Photo Library to detect screenshots, duplicates, similar
  shots, blurry photos, large videos, and Live Photos.
- Computes small perceptual hashes (dHash) and Laplacian variance
  scores to identify clutter. These are calculated on your device
  only — they never leave your iPhone.
- Caches small thumbnail previews using Apple's `PHCachingImageManager`
  for performance.

When you swipe to delete, Maxie calls `PHPhotoLibrary.performChanges`
through Apple's native Photos framework. iOS handles the actual
deletion — Maxie has no access to your photo files outside the
standard Photos API.

## What Maxie does NOT do

- Maxie does not include any analytics SDK.
- Maxie does not make any network requests with your personal data.
- Maxie does not show ads or share data with advertisers.
- Maxie does not request App Tracking Transparency permission.
- Maxie does not back up, sync, or upload your photos to any server.

The only network traffic Maxie generates is Apple's own StoreKit
purchase verification when you subscribe — handled entirely between
your iPhone and Apple's servers. We never see your payment info.

## Data we store on your device

Maxie persists a small amount of data locally in
`UserDefaults` and the app's sandboxed container:

- Whether you've completed onboarding
- Your quiz answers (age bucket, category preference, goal)
- A list of photo identifiers you've bookmarked
- Your subscription state (mirrored from Apple's StoreKit)
- A flag indicating whether you've seen the swipe-deck tutorial

This data never leaves your device. Deleting Maxie removes all of it.

## Photo permissions

Maxie needs access to your Photo Library to function. iOS shows you
the standard permission prompt the first time the app reads or
modifies your library. You can change this anytime in
**Settings → Privacy & Security → Photos → Maxie**.

You can grant full access or limited access. With limited access,
Maxie can only see the photos you explicitly share with it.

## Subscription privacy

Maxie offers an auto-renewing weekly subscription ($9.99/week with a
7-day free trial). Apple handles billing. The only information
Maxie sees is whether your subscription is active or not — a single
boolean state returned by StoreKit. We never see your Apple ID,
email, name, or payment details.

## Children

Maxie is rated 4+ and contains no objectionable content. We do not
knowingly collect any data from anyone, including children.

## Changes to this policy

If we ever change this policy (we don't expect to), the new version
will be posted at this URL with an updated "Last updated" date.

## Contact

Questions? Email **support@storagemax.app**.
