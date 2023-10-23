## macOS configuration profiles

`.mobileconfig` profiles to tune macOS settings

#### ⚠️ CAUTION ⚠️

`macos/danger-zone` contains profile to configure global password restrictions. Its use generally is _discouraged_, as
there is a chance of lockout (if the current password doesn't meet restrictions).

In very rare circumstances, when both of the following occurs:
- user is locked out
- macOS has personalization errors

RecoveryOS is accessible _only with FileVault recovery key_. If forgotten, despite supplying valid password,
user faces de-facto irreversible data loss, as neither macOS, nor RecoveryOS login is possible.
