# Mirror: Breez SDK - Liquid, Swift bindings 0.11.13

This repository is an unmodified mirror of the 0.11.13 release of
`breez/breez-sdk-liquid-swift`. Flash (lnflash) keeps it so that apps which
already ship the Breez SDK - Liquid can still build. Breez has retired the
Liquid SDK: its documentation recommends moving to the Breez SDK - Spark,
and its GitHub repositories for the Liquid SDK now return 404.

## What is here

- `Sources/`, `README.md` and `LICENSE`: the `BreezSDKLiquid` CocoaPod
  0.11.13 as Breez published it (the `0.11.13` tag of
  github.com/breez/breez-sdk-liquid-swift).
- Release `0.11.13`, asset `breez_sdk_liquidFFI.xcframework.zip`: the
  `breez_sdk_liquidFFI` 0.11.13 binary as Breez published it
  (github.com/breez/breez-sdk-liquid-swift/releases/download/0.11.13/breez_sdk_liquidFFI.xcframework.zip).

## Provenance

CocoaPods downloaded both from Breez's own URLs on 2026-07-14, and the files
here come from that cache unchanged. The original zip was not cached, so the
xcframework was zipped again: the zip's checksum differs from Breez's, while
its contents are byte for byte what CocoaPods extracted.

- `breez_sdk_liquidFFI.xcframework.zip` sha256:
  `613cec741ec850ca83561de8353553de9a2201685f94d7e2c306747404910241`

## Use

Point CocoaPods at this mirror with podspec overrides, as lnflash/flash-mobile
does in `ios/podspecs/`.

Nothing here is changed or maintained. It exists to keep existing builds
working while apps move their users off Liquid. Breez licensed this code
under the MIT License; see `LICENSE`.
