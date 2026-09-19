<div align="center">

# DEGOGGLE LOADOUT

**stuff to help you use less Google without making your life annoying**

[FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) · [Privacy](https://www.privacyguides.org/) · [Linux](https://www.linux.org/)

</div>

---

## so what is this?

I made this because finding decent alternatives to Google shouldn't mean digging through 40 different websites and hoping the app is still maintained.

This is a collection of FOSS apps, privacy-friendly services, browser extensions, Android options, and other useful stuff for slowly moving away from Google.

You don't have to replace everything at once. Start with one thing, see if it works for you, and go from there.

**use what you want. keep what you need. replace what you can.**

> quick note: privacy, security, and anonymity aren't the same thing. Check what a tool actually does instead of trusting a random privacy label.

## contents

- [quick start](#quick-start)
- [Google replacements](#google-replacements)
- [browsers](#browsers)
- [extensions](#extensions)
- [Android](#android)
- [passwords and 2FA](#passwords-and-2fa)
- [messaging](#messaging)
- [cloud and backups](#cloud-and-backups)
- [office and notes](#office-and-notes)
- [Linux and desktop](#linux-and-desktop)
- [self-hosting](#self-hosting)
- [migration checklist](#migration-checklist)

---

## quick start

If you don't feel like changing your whole setup overnight:

- Browser: [Firefox](https://www.mozilla.org/firefox/) or [Brave](https://brave.com/)
- Ad/tracker blocking: [uBlock Origin](https://github.com/gorhill/uBlock)
- Search: [DuckDuckGo](https://duckduckgo.com/), [Brave Search](https://search.brave.com/), or [SearXNG](https://docs.searxng.org/)
- Passwords: [Bitwarden](https://bitwarden.com/) or [KeePassXC](https://keepassxc.org/)
- 2FA: [Aegis](https://github.com/beemdevelopment/Aegis)
- Notes: [Joplin](https://joplinapp.org/) or [Obsidian](https://obsidian.md/)

You can literally just replace one service and stop there. No need to make it a whole project unless you want to.

## Google replacements

| Google thing | alternatives |
|---|---|
| Chrome | [Firefox](https://www.mozilla.org/firefox/), [LibreWolf](https://librewolf.net/), [Mullvad Browser](https://mullvad.net/browser) |
| Search | [SearXNG](https://docs.searxng.org/), [Brave Search](https://search.brave.com/), [Mojeek](https://www.mojeek.com/) |
| Gmail | [Tuta](https://tuta.com/), [Proton Mail](https://proton.me/mail), [Posteo](https://posteo.de/en) |
| Drive | [Nextcloud](https://nextcloud.com/), [Seafile](https://www.seafile.com/), [Proton Drive](https://proton.me/drive) |
| Docs | [LibreOffice](https://www.libreoffice.org/), [ONLYOFFICE](https://www.onlyoffice.com/), [CryptPad](https://cryptpad.org/) |
| Photos | [Immich](https://immich.app/), [Ente](https://ente.io/), [PhotoPrism](https://www.photoprism.app/) |
| Maps | [Organic Maps](https://organicmaps.app/), [OsmAnd](https://osmand.net/), [OpenStreetMap](https://www.openstreetmap.org/) |
| YouTube | [NewPipe](https://github.com/TeamNewPipe/NewPipe), [FreeTube](https://github.com/FreeTubeApp/FreeTube), [PeerTube](https://joinpeertube.org/) |
| Calendar | [Nextcloud Calendar](https://nextcloud.com/calendar/), [Proton Calendar](https://proton.me/calendar) |
| Keep | [Joplin](https://joplinapp.org/), [Standard Notes](https://standardnotes.com/), [Logseq](https://logseq.com/) |
| Authenticator | [Aegis](https://github.com/beemdevelopment/Aegis), [2FAS](https://2fas.com/), [ente Auth](https://ente.io/auth/) |

## browsers

- [Firefox](https://www.mozilla.org/firefox/) — customizable and not Chromium-based.
- [LibreWolf](https://librewolf.net/) — Firefox with privacy-focused defaults.
- [Mullvad Browser](https://mullvad.net/browser) — focused on reducing fingerprinting.
- [Tor Browser](https://www.torproject.org/) — routes traffic through Tor.
- [Brave](https://brave.com/) — Chromium-based with built-in blocking.
- [ungoogled-chromium](https://github.com/ungoogled-software/ungoogled-chromium) — Chromium with Google integrations removed or reduced.

## extensions

- [uBlock Origin](https://github.com/gorhill/uBlock) — ads and tracker blocking.
- [ClearURLs](https://github.com/ClearURLs/Addon) — removes tracking parameters.
- [LibRedirect](https://github.com/libredirect/libredirect) — redirects supported websites to alternative frontends.
- [SponsorBlock](https://sponsor.ajay.app/) — skips sponsored segments in videos.
- [Return YouTube Dislike](https://returnyoutubedislike.com/) — brings back estimated dislikes.
- [Dark Reader](https://darkreader.org/) — dark mode for websites.
- [Bitwarden](https://bitwarden.com/) — password manager extension.

Don't install every extension you see. More extensions can mean more maintenance and a more unique browser fingerprint.

## Android

### operating systems

- [GrapheneOS](https://grapheneos.org/) — hardened Android for supported Pixel devices.
- [CalyxOS](https://calyxos.org/) — privacy-focused Android with optional microG.
- [LineageOS](https://lineageos.org/) — community Android distribution.
- [/e/OS](https://e.foundation/e-os/) — Android-based de-Googled OS.
- [postmarketOS](https://postmarketos.org/) — Linux for supported mobile devices.

### apps and stores

- [F-Droid](https://f-droid.org/) — FOSS Android apps.
- [Accrescent](https://accrescent.app/) — app store focused on secure distribution.
- [Obtainium](https://github.com/ImranR98/Obtainium) — gets updates from developer sources.
- [Aurora Store](https://gitlab.com/AuroraStore/AuroraStore) — alternative Google Play client.
- [Fossify](https://fossify.org/) — local-first everyday apps.
- [HeliBoard](https://github.com/Helium314/HeliBoard) — open-source keyboard.
- [K-9 Mail](https://github.com/thundernest/k-9) — open-source email client.
- [Organic Maps](https://organicmaps.app/) — offline maps.

Check device support and backup options before switching operating systems. A custom ROM isn't automatically the right choice for every phone.

## passwords and 2FA

- [Bitwarden](https://bitwarden.com/)
- [KeePassXC](https://keepassxc.org/)
- [KeePassDX](https://www.keepassdx.com/)
- [Aegis](https://github.com/beemdevelopment/Aegis)
- [ente Auth](https://ente.io/auth/)
- [2FAS](https://2fas.com/)

Back up your vault and recovery codes somewhere safe. Getting locked out of your own accounts would be kinda bad.

## messaging

- [Signal](https://signal.org/)
- [SimpleX Chat](https://simplex.chat/)
- [Matrix](https://matrix.org/) / [Element](https://element.io/)
- [Session](https://getsession.org/)
- [Jami](https://jami.net/)

## cloud and backups

- [Nextcloud](https://nextcloud.com/)
- [Syncthing](https://syncthing.net/)
- [Seafile](https://www.seafile.com/)
- [Cryptomator](https://cryptomator.org/)
- [Kopia](https://kopia.io/)
- [Restic](https://restic.net/)

Syncing isn't the same as backing up. Keep another copy of anything you really don't want to lose.

## office and notes

- [LibreOffice](https://www.libreoffice.org/)
- [ONLYOFFICE](https://www.onlyoffice.com/)
- [CryptPad](https://cryptpad.org/)
- [Joplin](https://joplinapp.org/)
- [Logseq](https://logseq.com/)
- [Obsidian](https://obsidian.md/) — useful, but not fully open source.

## Linux and desktop

- [Fedora](https://fedoraproject.org/)
- [Arch Linux](https://archlinux.org/)
- [Debian](https://www.debian.org/)
- [KDE Plasma](https://kde.org/plasma-desktop/)
- [Hyprland](https://hyprland.org/)
- [VLC](https://www.videolan.org/vlc/)
- [GIMP](https://www.gimp.org/)
- [Krita](https://krita.org/)
- [OBS Studio](https://obsproject.com/)

## self-hosting

If you want more control and don't mind managing a server:

- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [Nextcloud](https://nextcloud.com/)
- [Immich](https://immich.app/)
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- [Jellyfin](https://jellyfin.org/)
- [FreshRSS](https://freshrss.org/)

Self-hosting is cool, but it also means you're responsible for updates, backups, and keeping things working. Don't host something important without understanding that part.

## migration checklist

- [ ] Pick one Google service to replace first.
- [ ] Export your important data before switching.
- [ ] Set up the replacement and test it.
- [ ] Update recovery emails and account details.
- [ ] Tell people if your email or contact method changes.
- [ ] Keep your old account around until you're sure nothing depends on it.
- [ ] Back up your new setup.
- [ ] Remove the old service when you're ready.

## contributing

Found something missing, outdated, or just plain wrong? Open an issue or pull request.

Please include the official project link and keep recommendations reasonably maintained. This list is meant to be useful, not a giant dump of random apps.

---

**use less of what you don't need. keep control of what matters.**