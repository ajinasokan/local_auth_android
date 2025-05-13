This is a fork of offical local_auth_android lib with patches to support devices without fingerprint sensor.

## androidx.biometric

Flutter local_auth is still using biometric lib from 2021 which does't have patches for devices like Poco C3 and Redmi 10A which doesn't have a fingerprint sensor.

Using alpha version of androidx biometric lib `androidx.biometric:biometric:1.2.0-alpha05` for the new patches.

## stickyAuth

Need to disable sticky auth, otherwise the non biometric auth page shows up twice:

Issue: https://github.com/flutter/flutter/issues/157249
