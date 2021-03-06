# INREMA Player

Das Standard-Package von INREMA. Einfache Playlists mit Videos und Bildern erstellen, welche zeitlich gesteuert werden können.


# Offline

This package can work offline, but only if some features are not used:

 * Playlists that use a date/time in their schedule will not work unless
 the the device got a correct system time using NTP. Alternatively it
 is possible to use a hardware based RTC to store time across reboots.
 * Anything using remote content will not work. This includes the browser,
 frab and streaming abilities.


## Changelog

### Version beta18

 * Added "Copy" button to copy a page.
 * Click on an image/video filename in the tile list to change the assets.

### Version beta17

 * Now compatible with the Pi4

### Version beta16

 * Added 'fallback' schedule option: Playlist scheduled as 'fallback' are only active if no other non-fallback playlist is scheduled.

### Version beta15

 * Fixed weather forecast day names.
 * Items that are always schedulable will show even if the device has no correct time
 * Added audio option to stream

### Version beta14

 * Added audio option to videos
 * More browser plugin options
 * Add option to disable a page by selecting "Deactivate" in its duration dropdown

### Version beta13

 * Fixed the weather 24h forecast tile. It would sometimes stop showing its content
 after a while.

### Version beta12

 * Added experimental support to show web content from any publicly reachable url. The
rendered browser output might be cached for a few minutes. You also can't show any kind
of animated web content that way. It works best for news pages or similar static content.

### Version beta11

 * Added a streaming tile. You can specify any support stream url (`rtsp://`, `http://.../stream.m3u8`) or
 a stream generated by the *Multicast Video Streamer* package:

### Version beta10

 * Added a weather plugin

### Version beta9

 * Updated Twitter API client to load longer tweets.

### Version beta8

 * Fixed incorrect handling of hour based schedules.
 * Made 'Simulate Time' feature use the selected timezone instead of UTC.

### Version beta7

 **Warning**: The plugins feature has been removed and setups that used this feature will require reconfiguration.

 * Added Layout feature. Allows you to define a base layout that you can then reuse in all pages.
 * More Interface Cleanups. Still not very good, but we're getting there. Feedback welcome!
 * More precise layout as you can now manually specify coordinates
 * Interactivity: Use a connected Keyboard to cycle or jump to individual pages

### Version beta6

 * Added debug mode that only shows a single page on repeat
 * Added Markdown support.

### Version beta5

 * Compact view for playlist editing. Rapidly create pages by just dragging assets to the playlist
 * Slightly improved asset search.

### Version beta4

 * Avoid using new JS syntax to make it more compatible with older browsers
 * Added icon

### Version beta3

 * Added Timespan based scheduling

### Version beta2

 * Added support for raw videos and basic animations for images

### Version beta1

 * Initial release
