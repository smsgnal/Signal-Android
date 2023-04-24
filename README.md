# SMSgnal Overview

THIS IS **NOT** AN OFFICIAL SIGNAL CLIENT - USE AT YOUR OWN RISK! PRs are very welcome.

Upstream Signal Android has decided to drop support for SMS as of April 2023. This repo intends to be identical to mainstream Signal, but with support for SMS. This was created for my personal usage, but I wanted to share it because of the massive public outcry requesting that mainline Signal keep support for SMS. Hopefully others find this useful as well.

Please note that there is no promise of any kind here; hopefully a community can grow around this project to suppport it until the Signal leadership can come to their senses. Please show your support for SMS in Signal Android by starring this repo.


# Status

As of:
* April 23, 2023 the current version (6.19.1) appears fully functional.


# Usage

You will need to compile and install the APK yourself. Follow the steps here: https://web.archive.org/web/20230424035915/https://community.signalusers.org/t/building-signal-android/15485/4 from "anon61006462". Specifically, sections:
* A. Setup the build environment and download the source code
  * Use this repo's git url instead
* E. Building and signing the APK
  * The variant is called `playProdSmsgnal`
  
If you have any issues, please create an issue on this repo, **NOT** upstream.


# Signal Android 

Signal is a simple, powerful, and secure messenger.

Signal uses your phone's data connection (WiFi/3G/4G/5G) to communicate securely. Millions of people use Signal every day for free and instantaneous communication anywhere in the world. Send and receive high-fidelity messages, participate in HD voice/video calls, and explore a growing set of new features that help you stay connected. Signal’s advanced privacy-preserving technology is always enabled, so you can focus on sharing the moments that matter with the people who matter to you.

Currently available on the Play Store and [signal.org](https://signal.org/android/apk/).

<a href='https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height='80px'/></a>

## Contributing Bug reports
We use GitHub for bug tracking. Please search the existing issues for your bug and create a new one if the issue is not yet tracked!

https://github.com/signalapp/Signal-Android/issues

## Joining the Beta
Want to live life on the bleeding edge and help out with testing?

You can subscribe to Signal Android Beta releases here:
https://play.google.com/apps/testing/org.thoughtcrime.securesms

If you're interested in a life of peace and tranquility, stick with the standard releases.

## Contributing Code

If you're new to the Signal codebase, we recommend going through our issues and picking out a simple bug to fix (check the "easy" label in our issues) in order to get yourself familiar. Also please have a look at the [CONTRIBUTING.md](https://github.com/signalapp/Signal-Android/blob/main/CONTRIBUTING.md), that might answer some of your questions.

For larger changes and feature ideas, we ask that you propose it on the [unofficial Community Forum](https://community.signalusers.org) for a high-level discussion with the wider community before implementation.

## Contributing Ideas
Have something you want to say about Signal projects or want to be part of the conversation? Get involved in the [community forum](https://community.signalusers.org).

Help
====
## Support
For troubleshooting and questions, please visit our support center!

https://support.signal.org/

## Documentation
Looking for documentation? Check out the wiki!

https://github.com/signalapp/Signal-Android/wiki

# Legal things
## Cryptography Notice

This distribution includes cryptographic software. The country in which you currently reside may have restrictions on the import, possession, use, and/or re-export to another country, of encryption software.
BEFORE using any encryption software, please check your country's laws, regulations and policies concerning the import, possession, or use, and re-export of encryption software, to see if this is permitted.
See <http://www.wassenaar.org/> for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security (BIS), has classified this software as Export Commodity Control Number (ECCN) 5D002.C.1, which includes information security software using or performing cryptographic functions with asymmetric algorithms.
The form and manner of this distribution makes it eligible for export under the License Exception ENC Technology Software Unrestricted (TSU) exception (see the BIS Export Administration Regulations, Section 740.13) for both object code and source code.

## License

Copyright 2013-2022 Signal

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html

Google Play and the Google Play logo are trademarks of Google LLC.
