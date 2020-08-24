
# Changelog

## 2.176.0.1 (17/JUL/2020)
* Fixes a stability issue.

## 2.176.0.0 (8/JUL/2020)
* Improves device model reporting for Xbox One.
* Support to fetch Framework name initially.
* Introduces setCDNServerIP() API to support setting of CDN Edge Server’s IP address.
* Supports error collection for download failure errors.

## 2.175.0.38205 (28/ARP/2020)
* Fixes issue that occurred when destroying MediaPlayerProxy object.

## 2.166.0.37741 (27/SEP/2019)
* Fixes issue while recreating MediaPlayerProxy/MediaElementProxy object.
* Introduces new logic for setDuration() API which takes higher precedence over the Conviva library's auto-detected content length values.
* Introduces new logic for setBitrate() API which takes higher precedence over the Conviva library's auto-detected bitrate values.
* Reduces heartbeat size by removing the default bitrate information from cwsStateChange event.

## 2.156.0.37173 (06/MAR/2019)
* Supports customer specific gatewayUrl using CUSTOMER_KEY.
* Enhances auto-detection of content length.

## 2.142.0.36024 (22/JUN/2018)
* Supports DASH VOD and Live (update 21/NOV/2018).
* Implements setSeekStart API to manually send seek start events.
* Fixes reporting of multiple state change events during content metadata updates.
* Removes detection and collection of SSID.

## 2.141.0.35771 (07/MAY/2018)
* Improves handling of tags after update content metadata.
* Handles Unicode (UTF-8) support for metadata.
* Fixes issue with resource leaking.

## 2.122.0.32826 (31/MAR/2017)
* Support for mutable metadata update.
* Added API documentation.
* Added CSharp Demo file to demonstrate usage of Conviva functions.
* Supported in Windows 10 Anniversary Update build 14393.x and above.

## 2.119.0.32167 (13/JAN/2017)
* Support for MediaPlayer and MediaPlayerElement.
* Support for new metadata.