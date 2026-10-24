# Privacy summary

Smylte is designed around a Library on your own device. This page explains the main data paths; it does not describe GitHub's or the supported websites' own data practices.

## On your device

- Saved Library records, downloaded media, image-text recognition and optional meaning search are handled locally.
- Backups remain wherever you save them. If you choose a cloud-synced folder, that folder's service can upload the files.
- Smylte does not require a separate developer account, include developer analytics, or relay saved content through a developer server.

## Requests to source websites

Saving and downloading use the relevant website and media hosts. Operations may use your current browser session where needed. These requests are not offline operations and remain subject to the source's access controls and limits.

## Optional Google Gemini categorization

AI categorization is opt-in and uses your own API key. Relevant selected post text, author handles, recognized image text and allowed category names go directly to Google Gemini. Merging similar categories sends existing and allowed category names.

The developer does not receive your key or this content. A key entered in the normal categorization settings is stored on your device for that feature; do not post it in GitHub issues. Provider limits, data practices and charges may apply. Local keyword/meaning search and manual organization do not require a cloud AI key.

## Sharing and exports

Creating share images happens locally. When you explicitly use the device's sharing function, the selected files go to the person or app you choose. Full Backup & Restore includes available media; JSON record export excludes downloaded media. Backup/export content should be treated as personal data, not attached to public issues.

## This public repository

This repository contains public product documentation and support forms. It does not contain Smylte application source, credentials, personal Libraries or installation packages. Anything you submit in a public GitHub issue can be read by others.

For the current installation listing and its linked privacy information, visit the [Chrome Web Store](https://chromewebstore.google.com/detail/smylte-save-social-media/eebefbknmfpjmhggmcapmljjilmkoebg).
