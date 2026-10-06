# Capture Privacy Policy

**Effective date:** October 6, 2026

This Privacy Policy explains how the Capture Android application (**package name: `com.thoughtcapture.app`**), published by **justgw**, accesses, uses, stores, and protects information. Capture is designed as a local-first voice capture application.

## Information processed by Capture

### Audio recordings

Capture accesses the microphone only when the user starts a recording. Recordings are stored in the app's private storage on the user's device. Capture does not upload recordings to a Capture-operated server.

### Transcripts and organized content

Transcripts, edits, titles, categories, lists, and other organized results are stored locally in the app's private storage. Capture does not upload this content to a Capture-operated server.

### Operational diagnostics

The current app records limited operational events in local Android debug logs to help diagnose actions such as a capture starting, completing, failing, being edited, or being deleted. These events do not contain audio, transcript text, titles, notes, or organized content and are not transmitted to a Capture analytics server.

## Speech recognition

By default, Capture uses the speech recognition service installed on the device. Depending on the device, language pack, system settings, and recognition provider, that service may process audio on the device or through the provider's network. Processing by that provider is governed by the provider's own privacy policy. Capture does not operate the system speech recognition service.

Enhanced transcription is optional and disabled by default. When selected, a downloaded Whisper model processes supported recordings locally on the device. If enhanced transcription cannot run, Capture may fall back to the device speech recognition service.

## Optional on-device AI

On-device Understand is optional and disabled by default. When the user downloads a compatible model and enables the feature, transcript cleanup, title generation, classification, and structured organization run locally on the device. Capture does not provide a cloud AI fallback.

Optional Whisper and language models are downloaded over HTTPS from third-party model hosting services, currently including Hugging Face. Download requests do not include recordings, transcripts, prompts, titles, categories, or model output. As with any internet request, the hosting provider may receive standard network information such as the requesting IP address and user agent under its own privacy policy.

## Google Play purchases

Optional Pro purchases are processed by Google Play. Capture does not receive or store full payment-card details. The app receives purchase status and transaction identifiers needed to unlock and restore Pro access. Google processes purchase information under the Google Privacy Policy and Google Play terms.

## Permissions

- **Microphone:** required to record user-requested audio.
- **Notifications:** used to show recording, transcription, and processing status.
- **Network access:** used for optional model downloads, Google Play Billing, and any network processing performed by the selected system speech service.

## Sharing and sale of data

Capture does not sell personal data. Capture does not share recordings, transcripts, or organized content with advertisers or data brokers. Information may be processed by the device speech recognition provider or Google Play only when the user uses the corresponding service, as described above.

## Storage, retention, and deletion

Captures remain on the device until the user deletes them, clears the app's data, or uninstalls the app. Deleting a capture removes its local database record and associated local audio file. Downloaded models remain until the user removes them, clears app data, or uninstalls the app. Deleting a model does not delete captures or existing organized results.

Capture does not require a Capture account. Google Play purchase records are managed by Google and may remain available to restore purchases with the same Google account.

## Security

Capture stores app data in Android private application storage and uses HTTPS for model downloads. No storage or transmission method can be guaranteed to be completely secure, but Capture limits data access and transmission to the functions described in this policy.

## Children's privacy

Capture is not directed to children under 13, and the developer does not knowingly collect personal information from children through a Capture-operated service.

## Changes to this policy

This policy may be updated when Capture's features or data practices change. The effective date at the top of this page identifies the latest revision. Material changes will be reflected in the app or its store listing as appropriate.

## Contact

Capture is published by **justgw**. For privacy questions or requests, open an inquiry through the [privacy support page](https://github.com/justgw/thoughtcapture-legal/issues). Do not include recordings, transcripts, payment information, or other sensitive content in a public issue.
