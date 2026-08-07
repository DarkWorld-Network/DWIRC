# DWIRC

DWIRC is a modern, open-source IRC client for Android, customized for the
[DarkWorld IRC Network](https://darkworld.network).

It is based on the GPL-licensed
[HexDroid](https://github.com/boxlabss/HexDroid) project and retains its
advanced IRC, encryption, scripting, bouncer and media capabilities.

## DarkWorld defaults

- Server: `irc.darkworld.network`
- TLS port: `6697`
- TLS certificate verification enabled
- Autojoin channel: `#DarkWorld`
- DarkWorld displayed first
- Other IRC networks fully supported

## Main features

- Multiple simultaneous IRC networks
- IRCv3, TLS and SASL
- ZNC and soju bouncer support
- Channel lists, private messages and notifications
- DCC file transfers
- SOCKS and Tor proxy support
- Message history and secure chat
- Android phone, tablet and TV support
- DarkWorld red-and-black theme
- No advertising or analytics

## Requirements

- Android 8.0 or later
- Java 17
- Android SDK Platform 37

## Build from source

    git clone -b develop https://github.com/DarkWorld-Network/DWIRC.git
    cd DWIRC
    chmod +x gradlew
    ./gradlew assembleDebug

Debug APK:

    app/build/outputs/apk/debug/app-debug.apk

## Support

- Website: [darkworld.network](https://darkworld.network)
- IRC: [DarkWorld #DarkWorld](ircs://irc.darkworld.network:6697/DarkWorld)
- Email: support@irc.darkworld.network
- Source: [DarkWorld-Network/DWIRC](https://github.com/DarkWorld-Network/DWIRC)
- Issues: [Issue tracker](https://github.com/DarkWorld-Network/DWIRC/issues)

## Privacy

See [PRIVACY.md](PRIVACY.md).

## Attribution

DWIRC is based on HexDroid by boxlabs. Original authors and contributors remain
credited in the application and source history.

Some encryption mechanisms retain HexDroid protocol identifiers for
wire-format compatibility.

## License

DWIRC is distributed under the GNU General Public License version 3 or later.
See [LICENSE](LICENSE).
