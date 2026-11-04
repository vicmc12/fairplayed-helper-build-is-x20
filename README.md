# FairPlayed helper build

This repository builds the public FairPlayed research helper at upstream commit
`bad7df138839b5e0ac8b9f20cc4689140b8436fb` on a GitHub-hosted Mac.
Run the workflow manually to produce an unsigned arm64 iPhone/iPad helper IPA.
The artifact expires after one day.

The build has no target App Store app, Apple account credentials, signing
certificates, provisioning profiles, or device identifiers. Only the pinned
public helper source is compiled. Target-specific packaging and signing are
performed separately by the operator.

This is an experimental build configuration. Producing an unsigned IPA does
not establish that the helper will install or decrypt a particular app on
a particular device. The source author's documented workflow and limitations
are available at https://github.com/morzelowski/FairPlayed.
