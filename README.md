# PGP Keys Filler

This is a temporary project to fill in missing PGP keys used to sign Maven artifacts
that are used as part of the build toolchain.  This is only a temporary measure
while attempting to contact and convince publishers of key Maven artifacts to
add their PGP key IDs to the [PGP keys map](https://github.com/s4u/pgp-keys-map)
project.

## Issue Template

### Add key to PGP keys map

Maven Central requires all published artifacts to be [signed using PGP](https://maven.apache.org/repository/guide-central-repository-upload.html#pgp-signature). If a publisher provides their key ID to [PGP keys map](https://github.com/s4u/pgp-keys-map) then end users can use the [Verify PGP signatures plugin](https://github.com/s4u/pgpverify-maven-plugin) to validate that the artifact has not been altered or replaced as part of a supply-chain attack.
