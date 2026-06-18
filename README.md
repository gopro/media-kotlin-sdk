<p align="center">
  <img src=".github/assets/GoProMediaSDK.jpg" alt="GoPro Media SDK" width="700">
</p>

<p align="center">
  <strong>Media SDK for Kotlin.</strong>
    <a href="https://gopro.github.io/media-kotlin-sdk"><img src="https://img.shields.io/badge/API%20Docs-0082FF?style=flat&colorA=222222" alt="API Docs"></a>
</p>

---

With the Media SDK, you can process GoPro `.360` spherical video files from
within your own Android Kotlin application.

> [!NOTE]
> Register and download the latest release at [gopro.com](https://gopro.com/en/us/info/developer-tools).

Enhance your user experience with
features such as:

#### <u>Equirectangular video export and transcoding</u>

GoPro MAX and MAX2 cameras store `.360` video in a dual track Equi-Angular Cubemap
(**EAC**) format. This raw format is compact and preserves maximum sensor data,
but it isn't directly playable by standard video players or compatible with most
downstream tools. The GoPro Media SDK transforms that raw capture into
universally consumable media with the ability to apply GoPro's award-winning
stabilization. For more information on this topic, see [THE INSIDE LINE: THIS IS
GOPRO MAX](https://gopro.com/en/us/news/max-tech-specs-stitching-resolution?srsltid=AfmBOorARukeKt1Ri_4Khnm_TLrGTmyKQKh84jJUN9kRT_tVD44TySZh).

#### <u>GPS Exchange Format (GPX) export</u>

GoPro MAX and MAX2 cameras can store GPS information for the video. The GoPro
Media SDK will extract the GPS data and create a standard GPS Exchange Format
(.gpx) file, ready for mapping applications or further analysis.

## Requirements

| Requirement | Minimum |
|---|---|
| Android `minSdk` | 33 |
| Kotlin | Coroutines support required (`kotlinx-coroutines`) |
| Architecture | `arm64-v8a`, `armeabi-v7a`, or `x86_64` |

## Documentation

The Media SDK API is delivered as an AAR library that hosts a set of free
functions with supporting enums and object classes. See
[GoPro Media SDK API](https://gopro.github.io/media-kotlin-sdk) for
more information about using the SDK and the APIs.

## Issues

Bug reports and feature requests are welcome. Please [open an issue](../../issues/new/choose)
rather than emailing support — public issues help the whole community and allow
GoPro to track and prioritize feedback.

Before filing, search [existing issues](../../issues) to avoid duplicates.

## Related SDKs

> [!TIP]
> See the [GoPro Media SDK for Swift (iOS)](https://github.com/gopro/media-swift-sdk)
