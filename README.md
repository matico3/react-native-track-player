[APM](https://github.com/lovegaoshi/azusa-player-mobile) fork of [RNTP](https://github.com/doublesymmetry/react-native-track-player)

Added changes to fit the requirements of nextmedia radio app
[![Android compile check](https://github.com/lovegaoshi/react-native-track-player/actions/workflows/compile-check.yml/badge.svg)](https://github.com/lovegaoshi/react-native-track-player/actions/workflows/compile-check.yml)

Please note this is a personal fork of [RNTP](https://github.com/doublesymmetry/react-native-track-player) for [APM](https://github.com/lovegaoshi/azusa-player-mobile)'s development. Its forked out of upstream because RNTP unfortunately was on a development hiatus and the community has been quiet for a very long time, while the entire react native community [1](https://github.com/evergrace-co/react-native-audio-pro),[2](https://docs.expo.dev/versions/latest/sdk/audio/) does NOT have anything better for audio playback. Many of the features APM uses, such as crossfade and Android Auto capabilities, were NOT merged upstream, unlikely to be merged in the foreseeable future, and won't be seen elsewhere either.

Functionalities used by APM [passes the play store review](https://play.google.com/store/apps/details?id=com.noxplay.noxplayer&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1).

This fork and APM proudly remains open-source and APM is published under GPLv3. As this fork is specifically developed for APM, contributions are welcome but changes modifying any APM features will NOT be accepted. For feature usages it's encouraged to look at the example app and APM. For library usages it's recommend to FORK yourself and modify any APM specific features and resources as needed.
