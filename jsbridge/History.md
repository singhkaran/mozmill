2.0rc5 / 2013-08-27
===================

* Bug 761603 - Do not convert any data to unicode for sending through jsbridge
* Bug 764640 - Sending data too quickly through the JSBridge socket causes an overflow and lots of event data can get lost
* Bug 865690 - Assertion failure and shutdown crash: !"I/O method is invalid", at /nsprpub/pr/src/io/priometh.c:54 because jsbridge calling recv after socket
* Bug 865690 - Ensure that JSBridge correctly handles application shutdown

3.0rc4 / 2013-06-14
===================

* Bug 865690 - Wallpaper fix for 'I/O method is invalid' assertion

3.0rc3 / 2013-05-08
===================

* Bug 865690 - JsBridge Recv called after socket closed
