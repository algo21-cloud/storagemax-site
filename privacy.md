---
title: Privacy Policy
permalink: /privacy/
description: "StorageMax does not collect, store, or transmit any of your data. Read our full privacy policy."
---

# StorageMax — Privacy Policy

**Last updated:** May 19, 2026

StorageMax is an iPhone photo-cleanup app. We believe the simplest privacy
policy is the truest one: **StorageMax does not collect, store, or transmit
your personal data.**

## What StorageMax does on your device

When you grant photo access, StorageMax:

- Scans your Photo Library to detect screenshots, duplicates, similar
  shots, blurry photos, large videos, and Live Photos.
- Computes small perceptual hashes (dHash) and Laplacian variance
  scores to identify clutter. These are calculated on your device
  only — they never leave your iPhone.
- Caches small thumbnail previews using Apple's `PHCachingImageManager`
  for performance.

When you swipe to delete, StorageMax calls `PHPhotoLibrary.performChanges`
through Apple's native Photos framework. iOS handles the actual
deletion — StorageMax has no access to your photo files outside the
standard Photos API.

## What StorageMax does NOT do

- StorageMax does not include any analytics SDK.
- StorageMax does not make any network requests with your personal data.
- StorageMax does not show ads or share data with advertisers.
- StorageMax does not request App Tracking Transparency permission.
- StorageMax does not back up, sync, or upload your photos to any server.

The only network traffic StorageMax generates is Apple's own StoreKit
purchase verification when you subscribe — handled entirely between
your iPhone and Apple's servers. We never see your payment info.

## Data we store on your device

StorageMax persists a small amount of data locally in
`UserDefaults` and the app's sandboxed container:

- Whether you've completed onboarding
- Your quiz answers (age bucket, category preference, goal)
- A list of photo identifiers you've bookmarked
- Your subscription state (mirrored from Apple's StoreKit)
- A flag indicating whether you've seen the swipe-deck tutorial

This data never leaves your device. Deleting StorageMax removes all of it.

## Photo permissions

StorageMax needs access to your Photo Library to function. iOS shows you
the standard permission prompt the first time the app reads or
modifies your library. You can change this anytime in
**Settings → Privacy & Security → Photos → StorageMax**.

You can grant full access or limited access. With limited access,
StorageMax can only see the photos you explicitly share with it.

## Subscription privacy

StorageMax offers an auto-renewing weekly subscription ($9.99/week with a
7-day free trial). Apple handles billing. The only information
StorageMax sees is whether your subscription is active or not — a single
boolean state returned by StoreKit. We never see your Apple ID,
email, name, or payment details.

## Children

StorageMax is rated 4+ and contains no objectionable content. We do not
knowingly collect any data from anyone, including children.

## Changes to this policy

If we ever change this policy (we don't expect to), the new version
will be posted at this URL with an updated "Last updated" date.

## Contact

Questions? Email **support@storagemax.app**.
