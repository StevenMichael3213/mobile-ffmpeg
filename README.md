The project is a fork of [mobile-ffmpeg](https://developer.android.com/ndk/guides/stable_apis#camera). It only supports limited processing of wav/pcm and mp3. If you want full features, please refer to the original project.

The release binary [v4.2.2.LTS.cv.1](https://github.com/StevenMichael3213/mobile-ffmpeg/releases/tag/v4.2.2.LTS.cv.1) is built by:
`./android.sh --lts --enable-lame`

### License

Copyright (c) 2018-2019 [mobile-ffmpeg](https://developer.android.com/ndk/guides/stable_apis#camera)

Modifications copyright (C) 2019 StevenMichael3213

This project is licensed under the LGPL v3.0. However, if source code is built using optional `--enable-gpl` flag or 
prebuilt binaries with `-gpl` postfix are used then MobileFFmpeg is subject to the GPL v3.0 license.

Source code of FFmpeg and external libraries is included in compliance with their individual licenses.

`openh264` source code included in this repository is licensed under the 2-clause BSD License but this license does 
not cover the `MPEG LA` licensing fees. If you build `mobile-ffmpeg` with `openh264` and distribute that library, then 
you are subject to pay `MPEG LA` licensing fees. Refer to [OpenH264 FAQ](https://www.openh264.org/faq.html) page for 
the details. Please note that `mobile-ffmpeg` does not publish a binary with `openh264` inside.

`strip-frameworks.sh` script included and distributed (until v4.x) is published under the [Apache License version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

In test applications; embedded fonts are licensed under the [SIL Open Font License](https://opensource.org/licenses/OFL-1.1), other digital assets are published in the public domain.
