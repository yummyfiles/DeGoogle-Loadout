<div align="center">

# DEGOGGLE LOADOUT

**a practical list of tools, apps, and guides for using less Google**

[FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) · [Privacy](https://www.privacyguides.org/) · [Self-hosting](https://github.com/awesome-selfhosted/awesome-selfhosted)

</div>

---

## What is this?

DeGoogle Loadout is a growing collection of alternatives to Google services, privacy-friendly tools, browser extensions, Android options, and guides for taking more control over your data.

This is not about pretending that one setup works for everyone. Some people want to leave Google completely. Others only want to replace Chrome, Search, Photos, or Drive. Both are valid starting points.

**Use what fits your needs. Keep what you need. Replace what you can.**

> Privacy, security, and anonymity are different things. Read what a tool actually protects instead of assuming that every privacy label means the same thing.

## Contents

- [Quick-start loadouts](#quick-start-loadouts)
- [Google replacements](#google-replacements)
- [Browsers](#browsers)
- [Browser extensions](#browser-extensions)
- [Search engines](#search-engines)
- [Email and calendars](#email-and-calendars)
- [Cloud storage and syncing](#cloud-storage-and-syncing)
- [Photos](#photos)
- [Maps and navigation](#maps-and-navigation)
- [YouTube alternatives](#youtube-alternatives)
- [Android](#android)
- [App stores](#app-stores)
- [Password managers and 2FA](#password-managers-and-2fa)
- [Messaging](#messaging)
- [Office and notes](#office-and-notes)
- [Linux and desktop tools](#linux-and-desktop-tools)
- [Self-hosting](#self-hosting)
- [Migration checklist](#migration-checklist)
- [Useful directories](#useful-directories)
- [Contributing](#contributing)

---

## Quick-start loadouts

### Minimal change

For people who want to start without rebuilding their entire setup:

- Browser: [Firefox](https://www.mozilla.org/firefox/) or [Brave](https://brave.com/)
- Content blocking: [uBlock Origin](https://github.com/gorhill/uBlock)
- Search: [DuckDuckGo](https://duckduckgo.com/), [Brave Search](https://search.brave.com/), or [Startpage](https://www.startpage.com/)
- Passwords: [Bitwarden](https://bitwarden.com/) or [KeePassXC](https://keepassxc.org/)
- 2FA: [Aegis](https://github.com/beemdevelopment/Aegis)

### Mostly FOSS

- Browser: [Firefox](https://www.mozilla.org/firefox/), [LibreWolf](https://librewolf.net/), or [Mullvad Browser](https://mullvad.net/browser)
- Search: [SearXNG](https://docs.searxng.org/) or [Brave Search](https://search.brave.com/)
- Email: [Tuta](https://tuta.com/) or [Proton Mail](https://proton.me/mail)
- Cloud: [Nextcloud](https://nextcloud.com/), [Syncthing](https://syncthing.net/), or [Seafile](https://www.seafile.com/)
- Photos: [Immich](https://immich.app/) or [Ente](https://ente.io/)
- Office: [LibreOffice](https://www.libreoffice.org/), [ONLYOFFICE](https://www.onlyoffice.com/), or [CryptPad](https://cryptpad.org/)

### De-Googled Android direction

- OS: [GrapheneOS](https://grapheneos.org/) on supported Pixel devices
- App source: [F-Droid](https://f-droid.org/), [Accrescent](https://accrescent.app/), or [Obtainium](https://github.com/ImranR98/Obtainium)
- Local apps: [Fossify](https://fossify.org/)
- Keyboard: [HeliBoard](https://github.com/Helium314/HeliBoard)
- 2FA: [Aegis](https://github.com/beemdevelopment/Aegis)

---

## Google replacements

| Google service | Alternatives | Notes |
|---|---|---|
| Chrome | Firefox, LibreWolf, Mullvad Browser, Brave | Browser choices have different privacy and compatibility tradeoffs |
| Search | SearXNG, Brave Search, DuckDuckGo, Startpage, Mojeek | Search indexes and privacy policies differ |
| Gmail | Tuta, Proton Mail, Mailbox.org | Check recovery, calendar, and alias needs before switching |
| Drive | Nextcloud, Seafile, Syncthing, Proton Drive | Decide whether you need collaboration, backup, or syncing |
| Docs / Sheets / Slides | LibreOffice, ONLYOFFICE, CryptPad, Collabora | Local editing and browser collaboration are different workflows |
| Photos | Immich, Ente, PhotoPrism, Nextcloud Memories | Confirm backup, mobile sync, and sharing features |
| Maps | Organic Maps, OsmAnd, HERE WeGo, OpenStreetMap | Offline maps may not include live traffic or transit |
| YouTube | Invidious, Piped, NewPipe, LibreTube, PeerTube | Availability and reliability vary by instance or client |
| Google Calendar | Nextcloud Calendar, Proton Calendar, Tuta Calendar | CalDAV support can matter for syncing |
| Google Keep | Joplin, Standard Notes, Obsidian, Notesnook | Check sync model and whether the app is fully open source |
| Google Photos editor | GIMP, Krita, darktable, RawTherapee | Desktop tools offer more control but may take longer to learn |
| Google Translate | LibreTranslate, Lingva Translate, Argos Translate | Machine translation quality varies by language |
| Google Analytics | Matomo, Plausible, Umami, GoatCounter | Choose based on hosting and analytics requirements |
| Google Fonts | Self-hosted fonts, Fontsource | Download and serve only the fonts you actually use |
| Google Authenticator | Aegis, 2FAS, ente Auth, KeePassXC | Export and back up your 2FA secrets safely |

---

## Browsers

### Desktop

- [Firefox](https://www.mozilla.org/firefox/) — independent browser engine with extensive customization.
- [LibreWolf](https://librewolf.net/) — Firefox-based browser with privacy-focused defaults.
- [Mullvad Browser](https://mullvad.net/browser) — anti-fingerprinting-focused browser developed with the Tor Project.
- [Tor Browser](https://www.torproject.org/) — designed to route browsing through Tor and reduce linkability.
- [Brave](https://brave.com/) — Chromium-based browser with built-in blocking features.
- [ungoogled-chromium](https://github.com/ungoogled-software/ungoogled-chromium) — Chromium with Google web-service dependencies removed or reduced.

### Mobile

- [Firefox for Android](https://www.mozilla.org/firefox/browsers/mobile/android/)
- [Mull](https://f-droid.org/packages/us.spotco.fennec_dos/)
- [Cromite](https://github.com/uazo/cromite)
- [IronFox](https://github.com/ironfox-oss/IronFox)
- [Tor Browser for Android](https://www.torproject.org/download/#android)

No browser is automatically private just because it is a fork. Review defaults, update practices, extensions, and the browser's threat model.

## Browser extensions

Start small. Installing dozens of extensions can increase complexity and may make your browser easier to identify.

- [uBlock Origin](https://github.com/gorhill/uBlock) — content and tracker blocking.
- [Privacy Badger](https://privacybadger.org/) — learns to block invisible trackers.
- [ClearURLs](https://github.com/ClearURLs/Addon) — removes known tracking parameters from URLs.
- [Decentraleyes](https://decentraleyes.org/) — local delivery of selected web libraries.
- [Cookie AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete) — removes cookies from closed tabs or containers.
- [LocalCDN](https://codeberg.org/nobody/LocalCDN) — local replacement for supported CDN resources.
- [Skip Redirect](https://github.com/sblask-webextensions/webextension-skip-redirect) — skips some redirect tracking links.
- [SponsorBlock](https://sponsor.ajay.app/) — skips crowdsourced sponsored segments in videos.
- [Return YouTube Dislike](https://returnyoutubedislike.com/) — restores estimated dislike information.
- [LibRedirect](https://github.com/libredirect/libredirect) — redirects supported sites to alternative frontends.
- [Dark Reader](https://darkreader.org/) — dark mode for websites.
- [Bitwarden](https://bitwarden.com/) — password manager browser extension.

## Search engines

- [SearXNG](https://docs.searxng.org/) — metasearch engine that can be self-hosted.
- [Brave Search](https://search.brave.com/) — search engine with an independent index.
- [DuckDuckGo](https://duckduckgo.com/) — privacy-oriented search engine.
- [Startpage](https://www.startpage.com/) — privacy proxy for search results.
- [Mojeek](https://www.mojeek.com/) — independent crawler and index.
- [Kagi](https://kagi.com/) — paid search engine with customization and no traditional ad model.
- [Marginalia Search](https://search.marginalia.nu/) — independent search engine focused on non-commercial web content.

## Email and calendars

- [Tuta](https://tuta.com/) — encrypted email and calendar services.
- [Proton Mail](https://proton.me/mail) — encrypted email with paid and free plans.
- [Mailbox.org](https://mailbox.org/) — privacy-oriented email and productivity services.
- [Posteo](https://posteo.de/en) — privacy-focused email provider.
- [Nextcloud Calendar](https://nextcloud.com/calendar/) — self-hostable calendar.
- [Radicale](https://radicale.org/) — lightweight CalDAV and CardDAV server.

Before changing email providers, update account recovery addresses, export important messages, and keep access to your old address long enough to catch forgotten accounts.

## Cloud storage and syncing

- [Nextcloud](https://nextcloud.com/) — broad self-hosted file and collaboration platform.
- [Seafile](https://www.seafile.com/) — file syncing and sharing platform.
- [Syncthing](https://syncthing.net/) — peer-to-peer file synchronization without a central cloud.
- [Proton Drive](https://proton.me/drive) — end-to-end encrypted cloud storage.
- [Cryptomator](https://cryptomator.org/) — encrypts files before they are stored in a cloud folder.
- [Kopia](https://kopia.io/) — encrypted, compressed, deduplicated backups.
- [Restic](https://restic.net/) — fast, secure, efficient backup program.

Sync is not the same as backup. Keep at least one independent backup copy when the data matters.

## Photos

- [Immich](https://immich.app/) — self-hosted photo and video management.
- [Ente Photos](https://ente.io/photos/) — end-to-end encrypted photo storage.
- [PhotoPrism](https://www.photoprism.app/) — self-hosted photo organization.
- [Nextcloud Memories](https://github.com/pulsejet/memories) — photo timeline for Nextcloud.
- [Fossify Gallery](https://fossify.org/) — local Android gallery app.

## Maps and navigation

- [Organic Maps](https://organicmaps.app/) — offline maps based on OpenStreetMap.
- [OsmAnd](https://osmand.net/) — feature-rich OpenStreetMap navigation.
- [OpenStreetMap](https://www.openstreetmap.org/) — community-maintained map data.
- [CoMaps](https://comaps.app/) — privacy-focused offline mapping project.
- [GraphHopper](https://www.graphhopper.com/) — routing engine with open-source components.

## YouTube alternatives

- [NewPipe](https://github.com/TeamNewPipe/NewPipe) — lightweight Android client.
- [LibreTube](https://github.com/libre-tube/LibreTube) — Android frontend using Piped.
- [Invidious](https://github.com/iv-org/invidious) — alternative YouTube frontend.
- [Piped](https://github.com/TeamPiped/Piped) — privacy-friendly YouTube frontend.
- [FreeTube](https://github.com/FreeTubeApp/FreeTube) — desktop YouTube client.
- [PeerTube](https://joinpeertube.org/) — decentralized video platform.

Third-party frontends can break when upstream services change. Keep a backup way to access content you rely on.

## Android

### Operating systems

- [GrapheneOS](https://grapheneos.org/) — hardened Android distribution for supported Pixel devices.
- [CalyxOS](https://calyxos.org/) — privacy-focused Android distribution with optional microG components.
- [LineageOS](https://lineageos.org/) — community Android distribution with broad device support.
- [/e/OS](https://e.foundation/e-os/) — de-Googled Android-based operating system.
- [postmarketOS](https://postmarketos.org/) — Linux distribution for mobile devices with varying hardware support.
- [Ubuntu Touch](https://ubports.com/) — mobile Linux-based platform.

Check exact device support, bootloader restrictions, banking app compatibility, update policy, and backup options before installing another OS.

### App stores and installation

- [F-Droid](https://f-droid.org/) — catalog of free and open-source Android apps.
- [Accrescent](https://accrescent.app/) — app store focused on verified and secure distribution.
- [Obtainium](https://github.com/ImranR98/Obtainium) — obtains app updates from developer releases and repositories.
- [Aurora Store](https://gitlab.com/AuroraStore/AuroraStore) — alternative client for Google Play.
- [Droid-ify](https://github.com/Droid-ify/client) — modern F-Droid client.

### Useful Android apps

- [Fossify](https://fossify.org/) — local-first replacements for common phone apps.
- [HeliBoard](https://github.com/Helium314/HeliBoard) — open-source Android keyboard.
- [Aegis](https://github.com/beemdevelopment/Aegis) — encrypted 2FA manager.
- [K-9 Mail](https://github.com/thundernest/k-9) — open-source email client.
- [FairEmail](https://email.faircode.eu/) — privacy-oriented email client.
- [SimpleX Chat](https://simplex.chat/) — messaging without user IDs based on phone numbers.
- [Organic Maps](https://organicmaps.app/) — offline maps.

## Password managers and 2FA

- [Bitwarden](https://bitwarden.com/) — cross-platform password manager with an open-source codebase.
- [KeePassXC](https://keepassxc.org/) — local password manager for desktop.
- [KeePassDX](https://www.keepassdx.com/) — Android KeePass client.
- [Proton Pass](https://proton.me/pass) — password manager with encrypted storage.
- [Aegis](https://github.com/beemdevelopment/Aegis) — Android authenticator.
- [ente Auth](https://ente.io/auth/) — cross-platform authenticator.
- [2FAS](https://2fas.com/) — authenticator with mobile and browser workflows.

Back up your password vault and 2FA recovery codes. A privacy-focused tool is not useful if you permanently lose access to your accounts.

## Messaging

- [Signal](https://signal.org/) — end-to-end encrypted messaging with a phone-number-based registration model.
- [SimpleX Chat](https://simplex.chat/) — messaging designed without permanent user IDs.
- [Matrix](https://matrix.org/) — decentralized communication protocol.
- [Element](https://element.io/) — Matrix client.
- [Session](https://getsession.org/) — decentralized messaging network.
- [Jami](https://jami.net/) — peer-to-peer communication platform.

## Office and notes

- [LibreOffice](https://www.libreoffice.org/) — free office suite for local documents.
- [ONLYOFFICE](https://www.onlyoffice.com/) — office suite with desktop and self-hosted options.
- [CryptPad](https://cryptpad.org/) — privacy-focused collaborative office suite.
- [Collabora Online](https://www.collaboraonline.com/) — browser-based office suite.
- [Joplin](https://joplinapp.org/) — open-source notes and to-do application.
- [Standard Notes](https://standardnotes.com/) — encrypted notes platform.
- [Obsidian](https://obsidian.md/) — local Markdown knowledge base; not fully open source.
- [Logseq](https://logseq.com/) — local-first outliner and knowledge base.
- [Zotero](https://www.zotero.org/) — research and reference manager.

## Linux and desktop tools

- [EndeavourOS](https://endeavouros.com/) — Arch-based Linux distribution.
- [Fedora](https://fedoraproject.org/) — Linux distribution with strong upstream involvement.
- [Debian](https://www.debian.org/) — community-maintained Linux distribution.
- [KDE Plasma](https://kde.org/plasma-desktop/) — customizable desktop environment.
- [Hyprland](https://hyprland.org/) — dynamic Wayland compositor.
- [VLC](https://www.videolan.org/vlc/) — media player.
- [mpv](https://mpv.io/) — lightweight media player.
- [GIMP](https://www.gimp.org/) — image editor.
- [Krita](https://krita.org/) — digital painting and image editing.
- [OBS Studio](https://obsproject.com/) — recording and streaming software.
- [Thunderbird](https://www.thunderbird.net/) — email and calendar client.

## Self-hosting

Useful projects for people who want to run services themselves:

- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — large catalog of self-hosted software.
- [Docker](https://www.docker.com/) — container platform.
- [Podman](https://podman.io/) — daemonless container engine.
- [Caddy](https://caddyserver.com/) — web server with automatic HTTPS.
- [Nginx](https://nginx.org/) — web server and reverse proxy.
- [Authentik](https://goauthentik.io/) — identity provider and access management.
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — unofficial Bitwarden-compatible server.
- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) — network-wide DNS filtering.
- [Pi-hole](https://pi-hole.net/) — DNS sinkhole for blocking unwanted domains.

Self-hosting moves responsibility to you. Updates, backups, exposed ports, passwords, and monitoring still matter.

## Migration checklist

- [ ] Make a list of Google services you actually use.
- [ ] Identify which accounts depend on your Gmail address.
- [ ] Export important data before deleting anything.
- [ ] Set up a password manager.
- [ ] Save 2FA recovery codes in a secure location.
- [ ] Choose a replacement email address.
- [ ] Move important files to a local or independent storage location.
- [ ] Install a browser and content blocker.
- [ ] Change your default search engine.
- [ ] Review Android app permissions and background access.
- [ ] Disable unnecessary location history, ad personalization, and activity tracking.
- [ ] Test your replacements before closing old accounts.
- [ ] Keep an emergency recovery plan.

## Useful directories

- [Privacy Guides](https://www.privacyguides.org/) — privacy and security recommendations.
- [Awesome Privacy](https://github.com/pluja/awesome-privacy) — curated privacy-respecting software list.
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — self-hosted software directory.
- [F-Droid](https://f-droid.org/) — free and open-source Android app catalog.
- [AlternativeTo](https://alternativeto.net/) — software alternative discovery.
- [DeGoogle Directory](https://mighil.com/degoogle/) — Google replacement directory.

## Contributing

Found a useful project, a dead link, or an outdated recommendation?

1. Check that the project is still maintained or clearly mark it as inactive.
2. Prefer official project links over download mirrors.
3. Explain what the tool replaces and any important limitations.
4. Avoid calling something completely private or secure without evidence.
5. Open a pull request with a short explanation of the change.

This list aims to be useful, not perfect. Recommendations can change as projects, policies, and maintenance status change.

---

<div align="center">

**use less of what you don't need. keep control of what matters.**

</div>
