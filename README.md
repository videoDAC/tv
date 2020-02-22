# Görli TV

Görli TV is a single-channel startup TV network, where viewers must pay in göETH to watch the channel.

Viewers pay per minute (+ gas), direct to the streamer's address, in real time.

It uses a Minimum Viable Product (MVP) Pay-As-You-Go Livestream Player Application, developed in [Kotlin](https://kotlinlang.org/) by Video DAC.

## Pre-requisites

- In order to watch Görli TV, you will need an Android device, version 4.1 or higher.

- It would also be helpful if you already have göETH.
  - If you don't already have göETH, talk to the nice people in [goerli/testnet channel on gitter](https://gitter.im/goerli/testnet).

## Codebase and Test APKs

The [git commit hash](https://github.com/videoDAC/apps/commit/5f3214a4c2a1bb87acb15e09f751046c8636d1c2) for the launch version the Görli TV Android App is `5f3214a4c2a1bb87acb15e09f751046c8636d1c2` and the master codebase is available on [Video DAC's project homepage on Github](https://github.com/videoDAC/apps).

Here is [a zip of the APK files](https://github.com/videoDAC/apps/files/4238030/gorli-tv-apks.zip) which can be installed on your Android device (4.1 upwards):

- `gorli-tv-debug.apk` for local testing and debugging.
- `gorli-tv-release.apk` has been released to Google Play store under [Görli TV](https://play.google.com/store/apps/details?id=com.videodac.hls).

## User Experience

Once configured, and charged with a credit balance in göETH, this app becomes the ultimate in simplicity.

It works like this:

> **Tap app launcher** to turn TV **ON**

> **Tap screen** to turn TV **OFF**

More details:

- Sound is played either through the device's in-built speaker or headphones - as you like.
- Volume can be controlled via the device's hardware buttons.
- There are no on-screen controls for fast-forward / rewind, as this is _only_ streaming live. Now. In the present moment.

But first you have to pass the following hurdles of user journey and testing. Please leave issues above :)

### User Journey

When the user first opens the app, she sees that the app is loading a wallet:

![Screenshot_20200222-023138](https://user-images.githubusercontent.com/59374467/75072497-9b87c400-551d-11ea-8543-3fb016d97019.png)

When a user's wallet loads, the app informs the user of some stuff she needs to know about her livestream player app.

![Screenshot_20200222-023143](https://user-images.githubusercontent.com/59374467/75072546-b0fcee00-551d-11ea-9f43-cfade2a66c98.png)

She likes to support independent ventures on Ethereum, so she chooses to pay, directly to the publisher, in order to watch.

If she taps the screen, the app will close, and the wallet's address will be copied to clipboard.

She can send göETH to this address by pasting it into a Web 3 wallet which supports Görli testnet (such as [WallETH](https://play.google.com/store/apps/details?id=org.walleth) or [MetaMask](https://play.google.com/store/apps/details?id=io.metamask)).

Once the user has loaded her wallet with some credit, in göETH, then it will load the livestream:

![Screenshot_20200222-023157](https://user-images.githubusercontent.com/59374467/75072740-19e46600-551e-11ea-91fd-15e2229820d6.png)

## Test Logs

The end to end testing of this software was performed, with [Etherscan transaction logs here, for a (now burned) burner wallet](https://goerli.etherscan.io/address/0xab060b3d2e0dc7fb6e62d7074448f32b748aa2d3).

4 minutes of watching Görli TV live. What heaven!

![Screenshot from 2020-02-22 03-07-13](https://user-images.githubusercontent.com/59374467/75074789-6b8eef80-5522-11ea-8ffd-800d4563adaf.png)

## Open Issues

Here is [a list of open issues relating to this app](https://github.com/videoDAC/apps/issues).

It contains known bugs, proposed enhancements and research topics.


## Call for Content

Please note, the content currently being displayed is usually just a test signal.

It can (and probably will) be replaced with live (and more interesting) content really easily.

If you want to appear on Görli TV, please email us at [Video DAC](mailto:videodac@protonmail.com) to find out how.

We will even share the göETH we receive with you :)
