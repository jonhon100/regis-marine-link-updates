# Regis Marine Link — Android updates

This public repository distributes signed Android APK builds; the application source is maintained separately in a private development repository.

The app can check published releases and request an Android installation with user approval. Development builds are for testing only, not marine safety or navigation.

Each release must use tag `build-N` matching Android `versionCode` and contain an APK asset named `regis-marine-link.apk`. Android verifies the same signing certificate for in-place updates. No signed APK is published yet.
