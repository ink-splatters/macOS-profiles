## macOS profiles

Opinionated macOS defaults implemeneted as [configuration profiles](https://support.apple.com/en-hk/guide/mac-help/mh35561/mac)

### Requirements

- only Apple Silicon is officially supported. You miles may vary with Intel system.
- TODO: mention last tested macOS version

### ⚠️ CAUTION ⚠️

Tampering with system-wide Password Policy potentially can lock you out. 

- it's not been tested by the author if it's still possible to enter `RecoveryOS` when such a lockout is combined with `FileVault` _disabled_ state
- it's not been tested by the author if it's still possible to enter `RecoveryOS` using credentials of Recovery-enabled user<sup>1</sup>,
  when such a lockout is combined with `FileVault` _enabled_ state
- __FileVault personal recovery key should always work__

Always enable `FileVault`. Always store your `FileVault` personal recovery key securely, outside of the system it's intended for.

.

