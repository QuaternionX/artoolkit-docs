---
meta_title: How to develop Augmented Reality applications with the ARToolKit SDK
menu_title: ARToolKit Documentation
description: ARToolKit is software that lets programmers easily develop Augmented Reality applications.
---

# ARToolKit Documentation

ARToolKit is software that lets programmers easily develop Augmented Reality applications. Augmented Reality (AR) is the embedding of computer generated content into the natural environment, and has many potential applications in entertainment, media, advertising, industry, and academic research.

The source code for this project is hosted on [GitHub][artk_github] and the compiled SDKs for all platforms (Mac OS X, PC, Linux, Android, iOS), along with the ARToolKit plug-in for Unity, are available at our [Downloads][artk_sdk_download] page.

Each of the individual platform downloads include a README file and example applications to help you get started immediately.  The documentation pages here include: detailed APIs, tutorials, and examples from novice to expert levels. Further support can be found by joining the [ARToolKit Community Forum][artk_forums].

## Features

<div class="feature_list">
<div class="feature">
![modular code][modular]

#### Transparent, Modular Code
Complete access to the computer vision algorithm allows you to modify the source code to fit your specific application.
</div>
<div class="feature">
![cross platform development friendly][cross_platform]

#### Cross Platform
ARToolKit has compiled SDKs for Windows, Mac OS, Linux, iOS and Android all ready to download and use.
</div>
<div class="feature">
![mobile development focused][mobile]

#### Mobile Focused
OpenGL ES2.x support, sensor integration and automatic camera calibration utilities ease the development process.
</div>
<div class="feature">
![natural feature tracking][nft]

#### Natural Feature Tracking
Traditional square markers, barcodes or regular images can be used as targets.
</div>
<div class="feature">
![stereo and optical see-though][optical]

#### Stereo and Optical See-Through
ARToolKit supports a wide range of smart glasses and is easy to calibrate for new devices.
</div>
<div class="feature">
![unity logo][unity]

#### Supports Unity on All Major Platforms
Unity users can publish a single AR application to all Desktop and mobile platforms.
</div>
<div class="feature">
![openscenegraph][osg]

#### Full OpenSceneGraph Support
Support for the advanced rendering features of OSG gives a wide range of rendering and model format options.
</div>
<div class="feature">
![calibration tools][tools]

#### Tools Accelerate Development Time
Tools are provided for camera calibration, barcode/NFT marker generation and optical/stereo calibration.
</div>
</div>

## About The Documentation

The documentation contains a complete description of the ARToolKit library, how to install it, and how to use its functionality in AR applications. Several simple sample applications are provided with ARToolKit to enable the programmer to get started immediately. ARToolKit includes the tracking libraries and complete source code for these libraries enabling programming to port the code to a variety of platforms or customize it for their own applications.

## About ARToolKit

ARToolKit is multi-platform, running on the Windows, Mac OS X, Linux, iOS and Android operating systems. The functionality of each version of the toolkit is the same, but the performance may vary depending on the different hardware configurations. ARToolKit can be easily ported to other new and experimental platforms.

One of the most difficult parts of developing an augmented reality application is precisely calculating the user's viewpoint in real time so that the virtual images are exactly aligned with real world objects. ARToolKit uses computer vision techniques to calculate the real camera position and orientation relative to square shapes or flat textured surfaces, allowing the programmer to overlay virtual objects. ARToolKit currently supports classical square marker, 2D barcode, multimarker, and natural feature tracking. Furthermore, ARToolKit supports any combination of the above together. The fast, precise tracking provided by ARToolKit has enabled the rapid development of thousands of new and interesting AR applications.

ARToolKit supports both video and optical see-through augmented reality. Video see-through AR is where virtual images are overlaid on live video of the real world. The alternative is optical see-through augmented reality, where computer graphics are overlaid directly on a view of the real world. Optical see-through augmented reality typically requires a see-through head mounted display and has more complicated camera calibration and registration requirements.

## Tutorials and Examples

* [ARApp (iOS)][example_arapp]
* [Android Examples][android_examples]
* [Codex Interactivus][codex_interactivus]
* [nftSimple (NFT)][example_nftsimple]
* [Optical See-Though][example_optical]
* [simpleLite Tutorial][example_simplelite]

## Quick Links

### Getting Started
* [Installing ARToolKit][about_installing]
* [Setting up a Video Capture Device][config_video_capture]
* [Calibrating your Camera][camera_calibration]
* [Training Markers][marker_training]
* [Training NFT Markers][marker_nft_training]

### Marker Types and Usage
* [About Markers][marker_about]
* [About 2D-Barcode Markers][marker_barcode]
* [About Multimarkers][marker_multi]
* [Troubleshooting Marker Recognition Issues][marker_troubleshooting]
* [ARToolKit NFT Utilities][marker_nft_utilities]

### Advanced Topics
* [Using an Optical See-Through Display][config_optical_see-through]
* [Configuring ARToolKit for Stereo Tracking][config_camera_stereo_tracking]
* [Adjusting ARToolKit for lighting conditions][config_adjusting_exposure]
* [Building libARvideo on Windows][windows_building_libarvideo]
* [Hardware Selection][about_hardware_selection]
* [Building from Source][build_artoolkit]
* [Advanced FAQ][about_faq]

### General Topics
* [Feature Comparison - *What's new?*][about_feature_comparison]
* [Setting an Environment Variable][general_environment_variables]
* [Deploying an Application on Windows/OS X][general_deploy_application]
* [Graphics, Models, and Rendering][about_rendering]

### Related Documentation (Off-Site)
* [ARToolKit v2.x documentation][external_2x_docs]
* [Inside ARToolKit][external_inside_artoolkit] Tutorial given at ART 02 by Hirokazu Kato
* [Marker Tracking and HMD Calibration for a Video-Based Augmented Reality Conferencing System][external_hmd_conferencing] by Hirokazu Kato and Mark Billinghurst.
* [A Registration Method based on Texture Tracking using ARToolKit][external_registration_method] by Hirokazu Kato, Keihachiro Tachibana, Mark Billinghurst, and Michael Grafe.

[about_installing]: 1_Getting_Started/about_installing.md
[config_video_capture]: 2_Configuration/config_video_capture.md
[camera_calibration]: 2_Configuration/config_camera_calibration.md
[marker_training]: 3_Marker_Training/marker_training.md
[marker_nft_training]: 3_Marker_Training/marker_nft_training.md
[marker_about]: 3_Marker_Training/marker_about.md
[marker_barcode]: 3_Marker_Training/marker_barcode.md
[marker_multi]: 3_Marker_Training/marker_multi.md
[marker_troubleshooting]: 3_Marker_Training/marker_troubleshooting.md
[marker_nft_utilities]: 3_Marker_Training/marker_nft_utilities.md
[config_optical_see-through]: 8_Advanced_Topics/config_optical_see_through.md
[config_camera_stereo_tracking]: 8_Advanced_Topics/config_camera_stereo_tracking.md
[config_adjusting_exposure]: 2_Configuration/config_adjusting_exposure.md
[windows_building_libarvideo]: 8_Advanced_Topics/windows_building_libarvideo.md
[about_hardware_selection]: 8_Advanced_Topics/about_hardware_selection.md
[build_artoolkit]: 8_Advanced_Topics/build_artoolkit.md
[about_faq]: 8_Advanced_Topics/about_faq.md
[about_feature_comparison]: 1_Getting_Started/about_feature_comparison.md
[general_environment_variables]: 1_Getting_Started/general_environment_variables.md
[general_deploy_application]: 1_Getting_Started/general_deploy_application.md
[about_rendering]: 1_Getting_Started/about_rendering.md
[android_examples]: 4_Android/android_examples.md
[example_arapp]: 7_Examples/example_arapp.md
[codex_interactivus]: 7_Examples/example_codex_interactivus.md
[example_nftsimple]: 7_Examples/example_nftsimple.md
[example_optical]: 7_Examples/example_optical.md
[example_simplelite]: 7_Examples/example_simplelite.md

[lgpl]: http://artoolkit.org/artoolkit-licensing
[artk_github]: https://github.com/artoolkit
[artk_sdk_download]: http://artoolkit.org/download-artoolkit-sdk
[artk_forums]: http://artoolkit.org/community/forums/
[external_2x_docs]: http://www.hitl.washington.edu/artoolkit/documentation/
[external_inside_artoolkit]: http://www.hitl.washington.edu/artoolkit/Papers/ART02-Tutorial.pdf
[external_hmd_conferencing]: http://www.hitl.washington.edu/artoolkit/Papers/IWAR99.kato.pdf
[external_registration_method]: http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=1320435


[optical]: _media/features/smart-glasses.png
[modular]: _media/features/modular-icon.png
[osg]: _media/features/osg-icon.png
[tools]: _media/features/tools-icon.png
[nft]: _media/features/nft-icon.png
[mobile]: _media/features/mobile-icon.png
[cross_platform]: _media/features/platform-icon.png
[unity]: _media/features/support-trophy.png
