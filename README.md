# Smart-Head-Track
Smart Head Track for OpenTrack

This guide describes how to connect the iOS application **[Smart Head Track](https://apps.apple.com/app/smart-head-track-for-opentrack/id1531547793)** to **[OpenTrack](https://github.com/opentrack/opentrack/releases)** via a USB connection.

It requires either iTunes or both "Apple Mobile Device Support" and "Apple Application Support" to be installed.

1. Plug your phone into your PC's USB connection. If you haven't yet, launch iTunes once to make sure it asks for permissions to your phone.
2. Launch [OpenTrack](https://github.com/opentrack/opentrack/releases)
3. Set input mode to "UDP" and make sure port number is 4242, then press "Start".
4. Open UDP port 4242 in your firewall if you've never done before.
5. In Smart Head Track iOS application, change connection mode to "USB Cable"
6. You can see a message at the bottom **Connected**. If it's **Listening** or **Disconnected**, please unplug and plug USB cable again.
7. Download [headtrack.exe](https://github.com/tinac-support/Smart-Head-Track/raw/main/headtrack.exe) and Run it on your Windows PC.
