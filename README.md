# Ember Downloads

Offline resource catalogue for Ember Audio Intelligence. Large model archives are fetched on first use and stored in app-private storage.

## Available resource

- **English offline speech recognition:** Vosk small US English 0.15.
- **Publisher:** Alpha Cephei.
- **Licence:** Apache-2.0.
- **Archive:** 41,166,628 bytes.
- **SHA-256:** `30f26242c4eb449f948e42cb302dd7a686cb29a3423a8367f99ff41780942498`.
- **Official model catalogue:** https://alphacephei.com/vosk/models

The Android app downloads this archive over HTTPS, checks the SHA-256 digest, validates the extracted model layout, and installs it under app-private storage before starting offline wake-word recognition.

## Planned resources

isiZulu speech recognition and offline translation remain planned. They are not advertised as installed or functional until a compatible model, licence, checksum, integration and device tests are complete.

Never mark a resource ready based only on a completed download. The model must load successfully in the runtime first.
