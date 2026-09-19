<div align="center">

# DEGOGGLE LOADOUT

**a massive list of tools, apps, and ways to use less Google without making your life annoying**

[FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) · [Privacy](https://www.privacyguides.org/) · [Linux](https://www.linux.org/) · [Self-hosting](https://github.com/awesome-selfhosted/awesome-selfhosted)

</div>

---

## so what is this?

I made this because finding decent alternatives to Google shouldn't mean opening 40 tabs, reading 12 privacy policies, and hoping the project wasn't abandoned three years ago.

This is a big collection of software, services, guides, and general ideas for slowly moving away from Google. That can mean replacing Gmail, switching browsers, using a different search engine, installing a de-Googled Android ROM, hosting your own services, or simply turning off a few things you don't need.

You do **not** have to replace everything at once. You don't need to become a full-time privacy person. You don't need a server rack in your bedroom. You can just change one thing when it makes sense.

Some tools here are fully free and open source. Some are only partially open source. Some are paid services. Some are self-hosted. Some are simply useful alternatives that reduce how much you depend on Google.

Read the descriptions. Check the project yourself. Don't blindly trust something just because it has the word `privacy` in its description.

> **use what you want. keep what you need. replace what you can.**

### a quick reality check

Privacy, security, anonymity, decentralization, and being free from Google are related, but they are not identical.

- A service can be private without being open source.
- A project can be open source without being secure.
- A self-hosted app gives you more control, but also more responsibility.
- A VPN does not make you anonymous everywhere.
- Using Linux does not automatically make every activity private.
- Removing Google apps does not magically remove every tracker.
- A privacy-friendly service can still have outages, bugs, or limitations.

The goal here isn't perfection. It's having more control and making informed choices.

---

## contents

- [quick start](#quick-start)
- [how to use this list](#how-to-use-this-list)
- [google replacements](#google-replacements)
- [search engines](#search-engines)
- [web browsers](#web-browsers)
- [browser extensions](#browser-extensions)
- [browser hardening](#browser-hardening)
- [email](#email)
- [calendars and contacts](#calendars-and-contacts)
- [cloud storage](#cloud-storage)
- [file synchronization](#file-synchronization)
- [photos and galleries](#photos-and-galleries)
- [maps and navigation](#maps-and-navigation)
- [youtube alternatives](#youtube-alternatives)
- [music and podcasts](#music-and-podcasts)
- [documents and office tools](#documents-and-office-tools)
- [notes and knowledge management](#notes-and-knowledge-management)
- [password managers](#password-managers)
- [two-factor authentication](#two-factor-authentication)
- [messaging](#messaging)
- [social media alternatives](#social-media-alternatives)
- [android](#android)
- [android app stores](#android-app-stores)
- [android apps](#android-apps)
- [linux and desktop](#linux-and-desktop)
- [media tools](#media-tools)
- [creative tools](#creative-tools)
- [communication and meetings](#communication-and-meetings)
- [privacy and security tools](#privacy-and-security-tools)
- [vpn and dns](#vpn-and-dns)
- [self-hosting](#self-hosting)
- [server management](#server-management)
- [backup strategy](#backup-strategy)
- [data migration](#data-migration)
- [account cleanup](#account-cleanup)
- [tracking and telemetry](#tracking-and-telemetry)
- [open-source directories](#open-source-directories)
- [useful privacy resources](#useful-privacy-resources)
- [common mistakes](#common-mistakes)
- [simple setups](#simple-setups)
- [advanced setups](#advanced-setups)
- [migration checklist](#migration-checklist)
- [contributing](#contributing)

---

## quick start

If you want a simple starting point, do this in whatever order makes sense for you:

1. Install [Firefox](https://www.mozilla.org/firefox/) or another browser you actually like.
2. Install [uBlock Origin](https://github.com/gorhill/uBlock).
3. Try [DuckDuckGo](https://duckduckgo.com/), [Brave Search](https://search.brave.com/), or a [SearXNG](https://docs.searxng.org/) instance.
4. Move your passwords into [Bitwarden](https://bitwarden.com/) or [KeePassXC](https://keepassxc.org/).
5. Replace Google Authenticator with [Aegis](https://github.com/beemdevelopment/Aegis), [2FAS](https://2fas.com/), or [ente Auth](https://ente.io/auth/).
6. Start using a separate email address for accounts and newsletters.
7. Export important Google data before deleting or abandoning anything.
8. Keep your old account until you know nothing important depends on it.

You can stop after step one. Seriously.

---

## how to use this list

This repository is not a checklist where you have to install everything.

When looking at a replacement, think about:

- **What do I actually need it to do?**
- **Does it work on my devices?**
- **Does it have the features I use every day?**
- **Can I export my data?**
- **Is it maintained?**
- **Who operates it?**
- **Can I trust the people or organization running it?**
- **What happens if the service disappears?**
- **Does it require an account?**
- **Is it open source, and does that matter for this use case?**
- **Would self-hosting be worth the maintenance?**

A tool that you actually use is usually more useful than a theoretically perfect tool that makes your life miserable.

---

# google replacements

This table is a starting point, not a strict one-to-one replacement chart. Some alternatives have different goals and some Google products combine features that normally require multiple apps.

| Google service | alternatives |
|---|---|
| Chrome | [Firefox](https://www.mozilla.org/firefox/), [LibreWolf](https://librewolf.net/), [Mullvad Browser](https://mullvad.net/browser), [Brave](https://brave.com/) |
| Search | [Brave Search](https://search.brave.com/), [DuckDuckGo](https://duckduckgo.com/), [Mojeek](https://www.mojeek.com/), [SearXNG](https://docs.searxng.org/), [Kagi](https://kagi.com/) |
| Gmail | [Proton Mail](https://proton.me/mail), [Tuta](https://tuta.com/), [Posteo](https://posteo.de/en), [mailbox.org](https://mailbox.org/) |
| Google Calendar | [Nextcloud Calendar](https://nextcloud.com/calendar/), [Proton Calendar](https://proton.me/calendar), [Etar](https://github.com/Etar-Group/Etar) |
| Google Contacts | [Nextcloud Contacts](https://nextcloud.com/contacts/), [DAVx⁵](https://www.davx5.com/), local contacts apps |
| Google Drive | [Nextcloud](https://nextcloud.com/), [Seafile](https://www.seafile.com/), [Proton Drive](https://proton.me/drive), [Syncthing](https://syncthing.net/) |
| Google Docs | [LibreOffice](https://www.libreoffice.org/), [ONLYOFFICE](https://www.onlyoffice.com/), [CryptPad](https://cryptpad.org/) |
| Google Sheets | [LibreOffice Calc](https://www.libreoffice.org/), [ONLYOFFICE](https://www.onlyoffice.com/), [CryptPad](https://cryptpad.org/) |
| Google Slides | [LibreOffice Impress](https://www.libreoffice.org/), [ONLYOFFICE](https://www.onlyoffice.com/), [Reveal.js](https://revealjs.com/) |
| Google Photos | [Immich](https://immich.app/), [Ente Photos](https://ente.io/), [PhotoPrism](https://www.photoprism.app/), [LibrePhotos](https://github.com/LibrePhotos/librephotos) |
| Google Maps | [OpenStreetMap](https://www.openstreetmap.org/), [Organic Maps](https://organicmaps.app/), [OsmAnd](https://osmand.net/), [CoMaps](https://comaps.app/) |
| YouTube | [PeerTube](https://joinpeertube.org/), [NewPipe](https://github.com/TeamNewPipe/NewPipe), [FreeTube](https://github.com/FreeTubeApp/FreeTube), [Invidious](https://github.com/iv-org/invidious) |
| YouTube Music | [InnerTune](https://github.com/z-huang/InnerTune), [ViMusic](https://github.com/vfsfitvnm/ViMusic), [Spotify alternatives](#music-and-podcasts) |
| Google Keep | [Joplin](https://joplinapp.org/), [Standard Notes](https://standardnotes.com/), [Logseq](https://logseq.com/), [Obsidian](https://obsidian.md/) |
| Google Authenticator | [Aegis](https://github.com/beemdevelopment/Aegis), [2FAS](https://2fas.com/), [ente Auth](https://ente.io/auth/) |
| Google Meet | [Jitsi Meet](https://jitsi.org/), [BigBlueButton](https://bigbluebutton.org/), [Element Call](https://element.io/call) |
| Google Analytics | [Matomo](https://matomo.org/), [Plausible](https://plausible.io/), [Umami](https://umami.is/), [GoAccess](https://goaccess.io/) |
| Google Fonts | [Fontsource](https://fontsource.org/), self-hosted fonts, system fonts |
| Google Tag Manager | self-managed analytics, [Matomo](https://matomo.org/), direct scripts |
| reCAPTCHA | [hCaptcha](https://www.hcaptcha.com/), [Friendly Captcha](https://friendlycaptcha.com/), custom rate limiting |
| Firebase | [Supabase](https://supabase.com/), [Appwrite](https://appwrite.io/), [PocketBase](https://pocketbase.io/), self-hosted backends |
| Google Cloud | [Hetzner](https://www.hetzner.com/), [DigitalOcean](https://www.digitalocean.com/), [Vultr](https://www.vultr.com/), self-hosted hardware |

---

# search engines

Search is one of the easiest things to change because you can try multiple engines without moving all your data.

## general search

- [Brave Search](https://search.brave.com/) — independent search index with privacy-focused positioning.
- [DuckDuckGo](https://duckduckgo.com/) — familiar search interface with privacy-oriented defaults.
- [Mojeek](https://www.mojeek.com/) — independent search engine with its own index.
- [Kagi](https://kagi.com/) — paid search engine with an ad-free approach.
- [Startpage](https://www.startpage.com/) — privacy-oriented interface using results from external providers.
- [Qwant](https://www.qwant.com/) — European search engine with privacy-focused branding.
- [Marginalia Search](https://search.marginalia.nu/) — useful for finding smaller and less commercial websites.
- [Wiby](https://wiby.me/) — search engine focused on simpler web pages.

## metasearch

- [SearXNG](https://docs.searxng.org/) — metasearch engine that can combine results from multiple sources.
- [Whoogle](https://github.com/benbusby/whoogle-search) — self-hostable search interface.
- [LibreY](https://github.com/Ahwxorg/LibreY) — privacy-friendly search interface.
- [4get](https://github.com/xyTom/4get) — self-hostable metasearch engine.

A public instance may still have logging, rate limits, or its own policies. Self-hosting does not automatically make the upstream search providers private.

## search habits that help

- Try using more specific terms instead of opening every result.
- Search for documentation directly when you know the project.
- Use community forums and issue trackers for technical problems.
- Add `site:` when searching a particular website.
- Check multiple engines if results look overly commercial.
- Don't assume the first result is the best result.
- Bookmark useful websites instead of searching for the same thing every time.

---

# web browsers

There is no single browser that is perfect for everyone. Browser choice depends on compatibility, privacy goals, extensions, performance, and how much configuration you want to do.

## Firefox-based browsers

- [Firefox](https://www.mozilla.org/firefox/) — flexible, widely supported, and not based on Chromium.
- [LibreWolf](https://librewolf.net/) — Firefox-based browser with privacy-focused defaults.
- [Mullvad Browser](https://mullvad.net/browser) — designed with anti-fingerprinting goals.
- [Tor Browser](https://www.torproject.org/) — designed to route traffic through the Tor network and reduce tracking.
- [Floorp](https://floorp.app/) — customizable Firefox-based browser.
- [Zen Browser](https://zen-browser.app/) — Firefox-based browser with a different interface and workflow.

## Chromium-based browsers

- [Brave](https://brave.com/) — Chromium-based browser with built-in blocking features.
- [ungoogled-chromium](https://github.com/ungoogled-software/ungoogled-chromium) — Chromium with Google-specific integrations removed or reduced.
- [Thorium](https://thorium.rocks/) — Chromium-based browser focused on performance.
- [Vivaldi](https://vivaldi.com/) — highly customizable browser with many built-in features.

Chromium-based does not automatically mean bad, and Firefox-based does not automatically mean private. Review the defaults, extensions, sync features, and telemetry behavior of the exact browser you use.

## mobile browsers

- [Firefox for Android](https://www.mozilla.org/firefox/browsers/mobile/android/)
- [Mull](https://gitlab.com/divested-mobile/mull-fenix)
- [Mullvad Browser](https://mullvad.net/browser)
- [Cromite](https://github.com/uazo/cromite)
- [Brave](https://brave.com/download/)
- [Tor Browser for Android](https://www.torproject.org/download/#android)
- [Fennec F-Droid](https://f-droid.org/packages/org.mozilla.fennec_fdroid/)

Check whether a browser supports the extensions, password manager, and websites you actually use.

---

# browser extensions

Install extensions because you need them, not because a random setup video installed 45 of them.

## blocking and privacy

- [uBlock Origin](https://github.com/gorhill/uBlock) — blocks ads, trackers, and other unwanted network requests.
- [uBlock Origin Lite](https://github.com/gorhill/uBlock) — a lighter version with browser-platform limitations.
- [Privacy Badger](https://privacybadger.org/) — blocks certain invisible trackers.
- [Decentraleyes](https://decentraleyes.org/) — attempts to provide local copies of some common resources.
- [ClearURLs](https://github.com/ClearURLs/Addon) — removes known tracking parameters from URLs.
- [LocalCDN](https://codeberg.org/nobody/LocalCDN) — provides local resources for supported libraries.
- [Cookie AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete) — removes cookies from closed tabs under configured rules.
- [Temporary Containers](https://addons.mozilla.org/firefox/addon/temporary-containers/) — separates browsing sessions into temporary containers.
- [Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/) — keeps websites separated into containers.
- [LibRedirect](https://github.com/libredirect/libredirect) — redirects supported websites to alternative frontends.
- [Skip Redirect](https://addons.mozilla.org/firefox/addon/skip-redirect/) — simplifies some redirect URLs.

## youtube and media

- [SponsorBlock](https://sponsor.ajay.app/) — skips community-marked sponsored segments.
- [Return YouTube Dislike](https://returnyoutubedislike.com/) — displays estimated dislike information.
- [DeArrow](https://dearrow.ajay.app/) — uses community-provided alternative titles and thumbnails.
- [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube) — adds customization options to YouTube.

## productivity

- [Bitwarden](https://bitwarden.com/) — password manager extension.
- [Dark Reader](https://darkreader.org/) — dark mode for websites.
- [Violentmonkey](https://violentmonkey.github.io/) — userscript manager.
- [Tampermonkey](https://www.tampermonkey.net/) — userscript manager with broad compatibility.
- [SingleFile](https://github.com/gildas-lormeau/SingleFile) — saves complete web pages into a single HTML file.
- [Web Archives](https://addons.mozilla.org/firefox/addon/web-archives/) — helps find archived versions of pages.
- [LanguageTool](https://languagetool.org/) — writing and grammar assistance.

## extension warnings

- Every extension adds another party that can potentially access browser data.
- Some extensions require access to every website you visit.
- Avoid installing extensions from random websites.
- Review permissions before installing.
- Remove extensions you no longer use.
- Keep extensions updated.
- Don't install multiple extensions that do the same thing without a reason.
- Extensions can make your browser more unique and may affect fingerprinting.

---

# browser hardening

Browser hardening is about reducing unwanted exposure while keeping websites usable.

## basic settings

- Turn on built-in tracking protection.
- Block third-party cookies where practical.
- Review location, camera, microphone, and notification permissions.
- Disable notifications from websites you don't need.
- Don't allow every website to run unnecessary permissions.
- Review saved passwords and autofill settings.
- Disable browser sync if you don't need it, or understand what it syncs.
- Keep the browser updated.
- Use separate browser profiles for separate purposes.
- Avoid logging into every website in the same browser profile.

## separate browser profiles

A simple setup might look like this:

- **Everyday:** normal browsing and regular accounts.
- **School/work:** accounts and websites related to school or work.
- **Testing:** websites, extensions, and development work.
- **Private:** fewer logins and a separate cookie store.

This is not perfect anonymity. It is simply a way to reduce accidental mixing between sessions.

## fingerprinting

Browser fingerprinting uses details about your browser and device to help identify you. Changing dozens of settings randomly can sometimes make you more unique instead of less.

For anti-fingerprinting browsers, consistent defaults may be more useful than endless customization. Decide whether fingerprinting resistance is actually part of your threat model before sacrificing compatibility.

---

# email

Email is difficult to replace completely because almost every service still supports it. You can, however, choose a provider that fits your needs and reduce how much you expose.

## providers

- [Proton Mail](https://proton.me/mail) — privacy-oriented email service with encrypted features.
- [Tuta](https://tuta.com/) — privacy-focused email provider with encrypted mailbox features.
- [Posteo](https://posteo.de/en) — privacy-oriented email provider.
- [mailbox.org](https://mailbox.org/) — email and office services.
- [Disroot](https://disroot.org/) — privacy-friendly services operated by a nonprofit foundation.
- [Riseup](https://riseup.net/) — services for activists and communities, subject to eligibility and policies.
- [Fastmail](https://www.fastmail.com/) — paid email provider focused on a polished email experience.
- [Migadu](https://www.migadu.com/) — email hosting with flexible domain options.
- [Purelymail](https://purelymail.com/) — low-cost email hosting option.

## custom domains

A custom domain can make changing providers easier because your email address is tied to your domain instead of the provider.

Example:

- `you@example.com`

Instead of:

- `you@gmail.com`

You still need to pay for the domain, manage DNS records, and keep the domain renewed. A custom domain is not automatically private, but it can improve portability.

## email aliases

- [SimpleLogin](https://simplelogin.io/)
- [Addy.io](https://addy.io/)
- [Firefox Relay](https://relay.firefox.com/)
- [DuckDuckGo Email Protection](https://duckduckgo.com/email/)
- [AnonAddy](https://github.com/anonaddy/anonaddy)

Aliases can help you identify which service leaked or sold an address and make it easier to disable unwanted mail.

## email habits

- Use a recovery email you can actually access.
- Keep recovery codes somewhere safe.
- Don't use the same password for your email and other accounts.
- Be careful with attachments and unexpected links.
- Use aliases for newsletters and one-off signups.
- Keep your important email address separate from random registrations.
- Export important mail if you depend on a provider.

---

# calendars and contacts

- [Nextcloud Calendar](https://nextcloud.com/calendar/) — calendar service that can be self-hosted.
- [Nextcloud Contacts](https://nextcloud.com/contacts/) — contact management with CardDAV support.
- [DAVx⁵](https://www.davx5.com/) — synchronizes CalDAV and CardDAV accounts on Android.
- [Etar](https://github.com/Etar-Group/Etar) — open-source Android calendar.
- [Simple Calendar](https://github.com/FossifyOrg/Calendar) — local-first calendar app from Fossify.
- [ICSx⁵](https://icsx5.bitfire.at/) — subscription calendar app.
- [DecSync CC](https://f-droid.org/packages/com.michaeltroger.davdroid/) — explore compatible decentralized synchronization workflows.

Before switching, check whether your school, work, or family depends on shared Google calendars.

---

# cloud storage

## hosted services

- [Proton Drive](https://proton.me/drive)
- [Tresorit](https://tresorit.com/)
- [Sync.com](https://www.sync.com/)
- [pCloud](https://www.pcloud.com/)
- [Filen](https://filen.io/)
- [Internxt](https://internxt.com/)
- [Mailbox.org](https://mailbox.org/)
- [Disroot](https://disroot.org/)

## self-hosted services

- [Nextcloud](https://nextcloud.com/)
- [Seafile](https://www.seafile.com/)
- [ownCloud](https://owncloud.com/)
- [Pydio Cells](https://pydio.com/)
- [File Browser](https://github.com/filebrowser/filebrowser)
- [SFTP](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol)
- [WebDAV](https://en.wikipedia.org/wiki/WebDAV)

## encrypted folders

- [Cryptomator](https://cryptomator.org/)
- [rclone crypt](https://rclone.org/crypt/)
- [gocryptfs](https://github.com/rfjakob/gocryptfs)
- [VeraCrypt](https://www.veracrypt.fr/)
- [age](https://age-encryption.org/)

Encryption tools differ in usability, metadata protection, and recovery options. Test your recovery process before putting important files into an encrypted container.

---

# file synchronization

Synchronization keeps files consistent across devices. It is not the same thing as a backup.

- [Syncthing](https://syncthing.net/) — peer-to-peer file synchronization.
- [KDE Connect](https://kdeconnect.kde.org/) — connects devices for file sharing and controls.
- [LocalSend](https://localsend.org/) — local network file sharing.
- [PairDrop](https://pairdrop.net/) — browser-based local file sharing.
- [Warp](https://github.com/localsend/localsend) — check project availability and platform support before using.
- [rsync](https://rsync.samba.org/) — command-line synchronization tool.
- [rclone](https://rclone.org/) — command-line tool for managing files across storage providers.

Good synchronization practices:

- Avoid editing the same file on multiple devices at the same time unless the tool supports it.
- Keep version history where possible.
- Do not treat a synchronized deletion as a safe backup.
- Test whether permissions and timestamps are preserved.
- Keep at least one copy disconnected from the main system.

---

# photos and galleries

- [Immich](https://immich.app/) — self-hosted photo and video management.
- [Ente Photos](https://ente.io/) — encrypted photo storage and management.
- [PhotoPrism](https://www.photoprism.app/) — self-hosted photo organization.
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) — open-source photo management.
- [Piwigo](https://piwigo.org/) — photo gallery software.
- [Lychee](https://lycheeorg.github.io/) — self-hosted photo-management platform.
- [Aves](https://github.com/deckerst/aves) — Android gallery app.
- [Fossify Gallery](https://github.com/FossifyOrg/Gallery) — local gallery app.
- [ImageMagick](https://imagemagick.org/) — image conversion and processing.
- [ExifTool](https://exiftool.org/) — reads and edits metadata.

Remember that photos can contain location metadata, device details, faces, documents, and other information you might not want to share.

Before uploading photos:

- Check EXIF metadata.
- Consider removing exact location data.
- Review shared album permissions.
- Use separate albums for public and private content.
- Keep an offline copy of originals.

---

# maps and navigation

- [OpenStreetMap](https://www.openstreetmap.org/) — community-maintained map data.
- [Organic Maps](https://organicmaps.app/) — offline maps based on OpenStreetMap.
- [CoMaps](https://comaps.app/) — community-oriented offline mapping project.
- [OsmAnd](https://osmand.net/) — feature-rich maps and navigation.
- [Magic Earth](https://www.magicearth.com/) — navigation application with privacy-focused features.
- [HERE WeGo](https://wego.here.com/) — mapping and navigation service.
- [GraphHopper](https://www.graphhopper.com/) — routing engine and services.
- [BRouter](https://brouter.de/) — routing engine used by some mapping applications.

Offline maps are useful, but download the regions you need before traveling. Also check how each app handles search requests, routing, location access, and analytics.

---

# youtube alternatives

## applications

- [NewPipe](https://github.com/TeamNewPipe/NewPipe) — Android client that does not require the official YouTube app.
- [FreeTube](https://github.com/FreeTubeApp/FreeTube) — desktop YouTube client focused on privacy.
- [LibreTube](https://github.com/libre-tube/LibreTube) — Android client using compatible backend services.
- [Clipious](https://github.com/lamarios/clipious) — Android client for Invidious.
- [Grayjay](https://grayjay.app/) — video aggregation client.
- [PeerTube](https://joinpeertube.org/) — decentralized video platform.
- [Invidious](https://github.com/iv-org/invidious) — alternative front end for YouTube.
- [Piped](https://github.com/TeamPiped/Piped) — alternative front end and backend project.

Third-party frontends can break when upstream services change. Avoid relying on a single instance for something important.

## youtube habits

- Subscribe through RSS where possible.
- Download videos you have permission to keep.
- Use [yt-dlp](https://github.com/yt-dlp/yt-dlp) for supported downloads.
- Use [SponsorBlock](https://sponsor.ajay.app/) to skip sponsored segments.
- Use [DeArrow](https://dearrow.ajay.app/) to reduce misleading titles and thumbnails.
- Avoid signing into YouTube in every browser profile.
- Keep a list of creators you care about outside of the platform.

---

# music and podcasts

## music players

- [MusicX](https://github.com/yummyfiles/MusicX) — FOSS offline music player project.
- [VLC](https://www.videolan.org/vlc/)
- [Strawberry](https://www.strawberrymusicplayer.org/)
- [Elisa](https://apps.kde.org/elisa/)
- [Tauon Music Box](https://tauonmusicbox.rocks/)
- [Quod Libet](https://quodlibet.readthedocs.io/)
- [Lollypop](https://wiki.gnome.org/Apps/Lollypop)
- [Clementine](https://www.clementine-player.org/)
- [foobar2000](https://www.foobar2000.org/)

## music services

- [Bandcamp](https://bandcamp.com/)
- [Jamendo](https://www.jamendo.com/)
- [SoundCloud](https://soundcloud.com/)
- [Funkwhale](https://funkwhale.audio/)
- [Ampache](https://ampache.org/)
- [Navidrome](https://www.navidrome.org/)
- [Jellyfin](https://jellyfin.org/)
- [Subsonic](http://www.subsonic.org/pages/index.jsp)

## podcasts

- [AntennaPod](https://antennapod.org/)
- [Kasts](https://apps.kde.org/kasts/)
- [gPodder](https://gpodder.github.io/)
- [Podverse](https://podverse.fm/)
- [Feeder](https://github.com/spacecowboy/Feeder)
- [F-Droid podcast apps](https://f-droid.org/en/packages/)

RSS feeds can make podcasts less dependent on platform-specific recommendation systems.

---

# documents and office tools

- [LibreOffice](https://www.libreoffice.org/) — full office suite.
- [ONLYOFFICE](https://www.onlyoffice.com/) — office suite with compatibility-focused editing.
- [Calligra](https://calligra.org/) — KDE office and creative suite.
- [CryptPad](https://cryptpad.org/) — collaborative encrypted office applications.
- [Etherpad](https://etherpad.org/) — collaborative text editor.
- [Collabora Online](https://www.collaboraonline.com/) — online office suite based on LibreOffice technology.
- [Grist](https://www.getgrist.com/) — spreadsheet and database-style tool.
- [AppFlowy](https://appflowy.io/) — open-source workspace project.
- [HedgeDoc](https://hedgedoc.org/) — collaborative Markdown editor.
- [Excalidraw](https://excalidraw.com/) — hand-drawn style whiteboard.
- [Draw.io](https://www.drawio.com/) — diagramming tool.
- [Mermaid](https://mermaid.js.org/) — diagrams generated from text.

## document habits

- Prefer open formats such as ODT, ODS, Markdown, TXT, CSV, and PDF when appropriate.
- Keep editable originals instead of only exporting PDFs.
- Avoid storing the only copy of a document in a browser tab.
- Check formatting when exchanging files with people using different office suites.
- Use version control for text-based documents when it makes sense.

---

# notes and knowledge management

- [Joplin](https://joplinapp.org/) — note-taking with synchronization options.
- [Standard Notes](https://standardnotes.com/) — encrypted note-taking service.
- [Logseq](https://logseq.com/) — local-first outliner and knowledge base.
- [Obsidian](https://obsidian.md/) — local Markdown-based knowledge management tool; not fully open source.
- [Zettlr](https://www.zettlr.com/) — Markdown editor and academic writing tool.
- [TriliumNext Notes](https://github.com/TriliumNext/Notes) — hierarchical knowledge base.
- [SiYuan](https://b3log.org/siyuan/en/) — personal knowledge management system.
- [QOwnNotes](https://www.qownnotes.org/) — plain-text note-taking application.
- [MarkText](https://github.com/marktext/marktext) — Markdown editor.
- [Ghostwriter](https://ghostwriter.kde.org/) — distraction-free Markdown editor.
- [Zim](https://zim-wiki.org/) — desktop wiki.
- [TiddlyWiki](https://tiddlywiki.com/) — personal wiki that can run locally.

## note-taking advice

- Use plain text or Markdown when portability matters.
- Don't build a complicated system before you know what you need.
- Keep a clear export path.
- Avoid storing passwords or recovery codes in an ordinary notes app.
- Back up your notes folder.
- Use tags and folders only when they actually help.
- A simple folder with text files can be enough.

---

# passwords and two-factor authentication

## password managers

- [Bitwarden](https://bitwarden.com/) — hosted and self-hostable password manager options.
- [KeePassXC](https://keepassxc.org/) — local desktop password manager.
- [KeePassDX](https://www.keepassdx.com/) — Android password manager for KeePass databases.
- [KeePassium](https://keepassium.com/) — iOS KeePass client.
- [1Password](https://1password.com/) — commercial password manager.
- [Proton Pass](https://proton.me/pass) — password manager from Proton.
- [gopass](https://www.gopass.pw/) — command-line password manager.
- [pass](https://www.passwordstore.org/) — Unix password store.
- [Psono](https://psono.com/) — password manager with self-hosting options.
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — unofficial Bitwarden-compatible server.

## authenticator apps

- [Aegis](https://github.com/beemdevelopment/Aegis)
- [2FAS](https://2fas.com/)
- [ente Auth](https://ente.io/auth/)
- [andOTP](https://github.com/andOTP/andOTP) — check maintenance status before choosing it.
- [FreeOTP](https://github.com/freeotp/freeotp-android)
- [KeePassXC TOTP](https://keepassxc.org/)

## account security basics

- Use a different password for every important account.
- Use long passwords or passphrases.
- Turn on multi-factor authentication where available.
- Save recovery codes offline.
- Keep your email account especially secure.
- Don't share one-time codes with anyone.
- Be careful with password-reset messages.
- Review active sessions periodically.
- Remove old devices and applications from account access lists.
- Keep an emergency plan for losing your phone.

---

# messaging

- [Signal](https://signal.org/) — private messaging with end-to-end encryption.
- [SimpleX Chat](https://simplex.chat/) — messaging system designed without permanent user IDs.
- [Matrix](https://matrix.org/) — open network for decentralized communication.
- [Element](https://element.io/) — Matrix client.
- [Session](https://getsession.org/) — privacy-focused messaging network.
- [Jami](https://jami.net/) — distributed communication platform.
- [Briar](https://briarproject.org/) — peer-to-peer messaging with offline communication features.
- [XMPP](https://xmpp.org/) — open messaging protocol.
- [Conversations](https://conversations.im/) — Android XMPP client.
- [Delta Chat](https://delta.chat/) — messaging application that uses email infrastructure.
- [IRC](https://www.irchelp.org/) — classic real-time chat protocol.
- [Revolt](https://revolt.chat/) — open-source chat platform.
- [Stoat](https://stoat.chat/) — community chat platform.

The best messenger is often the one your friends and family will actually use. Security features do not help much if everyone moves back to an insecure platform because the alternative is inconvenient.

---

# social media alternatives

- [Mastodon](https://joinmastodon.org/) — federated microblogging platform.
- [Bluesky](https://bsky.app/) — social platform using the AT Protocol.
- [Misskey](https://misskey-hub.net/) — federated social platform.
- [Lemmy](https://join-lemmy.org/) — federated discussion platform.
- [Kbin alternatives](https://github.com/ernestwisniewski/awesome-activitypub) — explore ActivityPub projects.
- [PeerTube](https://joinpeertube.org/) — federated video platform.
- [Pixelfed](https://pixelfed.org/) — federated image-sharing platform.
- [Friendica](https://friendi.ca/) — decentralized social networking platform.
- [Diaspora](https://diasporafoundation.org/) — distributed social network.
- [WriteFreely](https://writefreely.org/) — minimalist federated publishing platform.
- [Ghost](https://ghost.org/) — publishing platform with self-hosting options.
- [WordPress](https://wordpress.org/) — publishing software that can be self-hosted.

Federated services are not automatically private. Your posts may still be public, your instance may log activity, and moderation policies vary between servers.

---

# android

Android is not one single experience. Your device manufacturer, operating system, Google apps, app store, permissions, and installed applications all matter.

## operating systems

- [GrapheneOS](https://grapheneos.org/) — hardened Android operating system for supported devices.
- [CalyxOS](https://calyxos.org/) — privacy-focused Android distribution with optional microG.
- [LineageOS](https://lineageos.org/) — community Android distribution.
- [/e/OS](https://e.foundation/e-os/) — Android-based operating system with de-Googling goals.
- [DivestOS](https://divestos.org/) — discontinued project; check current status before relying on old guides.
- [postmarketOS](https://postmarketos.org/) — Linux distribution for supported mobile devices.
- [Ubuntu Touch](https://ubports.com/) — mobile operating system based on Ubuntu.
- [Sailfish OS](https://sailfishos.org/) — mobile operating system with device-specific support.

Always check exact device support, bootloader unlock requirements, banking app compatibility, camera quality, updates, and recovery procedures before installing a custom operating system.

## reducing Google without changing the OS

You can still reduce dependence on Google on a stock Android phone:

- Disable apps you don't use.
- Review permissions.
- Replace the default browser.
- Use a different search engine.
- Install F-Droid or another trusted source where appropriate.
- Use local gallery, music, and file manager apps.
- Turn off unnecessary notification access.
- Remove unused accounts.
- Review location history and ad personalization settings.
- Avoid installing apps that require excessive permissions.

Some system components cannot be removed without root or changing the operating system. Don't disable random system packages without researching what they do.

---

# android app stores

- [F-Droid](https://f-droid.org/) — catalog of free and open-source Android apps.
- [Accrescent](https://accrescent.app/) — Android app store focused on secure distribution.
- [Obtainium](https://github.com/ImranR98/Obtainium) — obtains updates from developer release sources.
- [Aurora Store](https://gitlab.com/AuroraStore/AuroraStore) — alternative client for Google Play.
- [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) — additional F-Droid repository.
- [Neo Store](https://github.com/NeoApplications/Neo-Store) — F-Droid client.
- [Droid-ify](https://github.com/Droid-ify/client) — F-Droid client.
- [Obtainium](https://github.com/ImranR98/Obtainium) — useful for tracking releases from upstream projects.

Do not add repositories just because they contain an app you want. A repository can distribute software with different review standards, signing practices, and maintenance levels.

---

# android apps

## everyday apps

- [Fossify](https://fossify.org/) — local-first everyday Android applications.
- [Simple Mobile Tools](https://www.simplemobiletools.com/) — older project family; check ownership and current distribution status.
- [K-9 Mail](https://github.com/thundernest/k-9) — open-source email client.
- [FairEmail](https://email.faircode.eu/) — privacy-oriented email client.
- [HeliBoard](https://github.com/Helium314/HeliBoard) — open-source keyboard.
- [OpenBoard](https://github.com/openboard-team/openboard) — open-source keyboard project.
- [Organic Maps](https://organicmaps.app/) — offline maps.
- [VLC](https://www.videolan.org/vlc/download-android.html) — media player.
- [NewPipe](https://github.com/TeamNewPipe/NewPipe) — alternative video client.
- [AntennaPod](https://antennapod.org/) — podcast application.
- [DAVx⁵](https://www.davx5.com/) — calendar and contact synchronization.
- [Markor](https://github.com/gsantner/markor) — Markdown and text editor.
- [Etar](https://github.com/Etar-Group/Etar) — calendar.
- [Aves](https://github.com/deckerst/aves) — gallery.
- [LocalSend](https://localsend.org/) — local file sharing.
- [KDE Connect](https://kdeconnect.kde.org/) — device integration.

## permissions to pay attention to

Be suspicious when a basic app asks for permissions it clearly doesn't need.

Examples worth reviewing:

- A flashlight app asking for contacts.
- A calculator asking for microphone access.
- A wallpaper app asking for SMS access.
- A keyboard requesting network access without a clear reason.
- A QR scanner asking for your entire file system.
- A game requesting accessibility access.

Some permissions are legitimate for certain features. The point is to understand why the permission is requested instead of automatically accepting everything.

---

# linux and desktop

Linux can reduce dependence on platform-specific ecosystems, but the distribution and applications you choose still matter.

## distributions

- [Arch Linux](https://archlinux.org/)
- [EndeavourOS](https://endeavouros.com/)
- [Debian](https://www.debian.org/)
- [Fedora](https://fedoraproject.org/)
- [Linux Mint](https://linuxmint.com/)
- [openSUSE](https://www.opensuse.org/)
- [NixOS](https://nixos.org/)
- [Tails](https://tails.net/)
- [Qubes OS](https://www.qubes-os.org/)
- [Whonix](https://www.whonix.org/)
- [Alpine Linux](https://alpinelinux.org/)
- [Void Linux](https://voidlinux.org/)
- [Ubuntu](https://ubuntu.com/)

## desktop environments and window managers

- [KDE Plasma](https://kde.org/plasma-desktop/)
- [GNOME](https://www.gnome.org/)
- [XFCE](https://xfce.org/)
- [Cinnamon](https://projects.linuxmint.com/cinnamon/)
- [MATE](https://mate-desktop.org/)
- [Hyprland](https://hyprland.org/)
- [Sway](https://swaywm.org/)
- [i3](https://i3wm.org/)
- [AwesomeWM](https://awesomewm.org/)
- [bspwm](https://github.com/baskerville/bspwm)
- [river](https://github.com/riverwm/river)

## desktop applications

- [Kitty](https://sw.kovidgoyal.net/kitty/)
- [Alacritty](https://alacritty.org/)
- [Foot](https://codeberg.org/dnkl/foot)
- [Neovim](https://neovim.io/)
- [Vim](https://www.vim.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [VSCodium](https://vscodium.com/)
- [Zed](https://zed.dev/)
- [Kate](https://kate-editor.org/)
- [Dolphin](https://apps.kde.org/dolphin/)
- [Thunar](https://docs.xfce.org/xfce/thunar/start)
- [PCManFM](https://wiki.lxde.org/en/PCManFM)
- [fastfetch](https://github.com/fastfetch-cli/fastfetch)
- [btop](https://github.com/aristocratos/btop)
- [htop](https://htop.dev/)
- [ncdu](https://dev.yorhel.nl/ncdu)
- [ranger](https://github.com/ranger/ranger)
- [yazi](https://github.com/sxyazi/yazi)
- [tmux](https://github.com/tmux/tmux)
- [zoxide](https://github.com/ajeetdsouza/zoxide)
- [fzf](https://github.com/junegunn/fzf)

---

# media tools

- [VLC](https://www.videolan.org/vlc/)
- [mpv](https://mpv.io/)
- [Celluloid](https://celluloid-player.github.io/)
- [Kodi](https://kodi.tv/)
- [Jellyfin](https://jellyfin.org/)
- [Jellyseerr](https://github.com/Fallenbagel/jellyseerr)
- [Plex](https://www.plex.tv/) — convenient, but not fully open source.
- [HandBrake](https://handbrake.fr/)
- [FFmpeg](https://ffmpeg.org/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [LosslessCut](https://github.com/mifi/lossless-cut)
- [MKVToolNix](https://mkvtoolnix.download/)
- [Audacity](https://www.audacityteam.org/)
- [Tenacity](https://github.com/tenacityteam/tenacity)
- [Ardour](https://ardour.org/)
- [EasyEffects](https://github.com/wwmm/easyeffects)
- [Helvum](https://gitlab.freedesktop.org/pipewire/helvum)
- [qpwgraph](https://github.com/rncbc/qpwgraph)

---

# creative tools

## images and design

- [GIMP](https://www.gimp.org/)
- [Krita](https://krita.org/)
- [Inkscape](https://inkscape.org/)
- [Pinta](https://www.pinta-project.com/)
- [MyPaint](https://mypaint.app/)
- [darktable](https://www.darktable.org/)
- [RawTherapee](https://rawtherapee.com/)
- [ImageMagick](https://imagemagick.org/)
- [Upscayl](https://github.com/upscayl/upscayl)
- [Graphite](https://graphite.rs/)
- [Penpot](https://penpot.app/)
- [Inkscape](https://inkscape.org/)

## video and 3D

- [Kdenlive](https://kdenlive.org/)
- [Shotcut](https://shotcut.org/)
- [OpenShot](https://www.openshot.org/)
- [Olive](https://www.olivevideoeditor.org/)
- [Blender](https://www.blender.org/)
- [Natron](https://natrongithub.github.io/)
- [OBS Studio](https://obsproject.com/)
- [LosslessCut](https://github.com/mifi/lossless-cut)

## audio

- [Ardour](https://ardour.org/)
- [Audacity](https://www.audacityteam.org/)
- [Tenacity](https://github.com/tenacityteam/tenacity)
- [LMMS](https://lmms.io/)
- [Hydrogen](https://hydrogen-music.org/)
- [MuseScore](https://musescore.org/)
- [Carla](https://kx.studio/Applications:Carla)

---

# communication and meetings

- [Jitsi Meet](https://jitsi.org/)
- [BigBlueButton](https://bigbluebutton.org/)
- [Element Call](https://element.io/call)
- [Whereby](https://whereby.com/)
- [Mumble](https://www.mumble.info/)
- [Jami](https://jami.net/)
- [Nextcloud Talk](https://nextcloud.com/talk/)
- [Galene](https://galene.org/)
- [Miro alternatives](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [Etherpad](https://etherpad.org/)
- [HedgeDoc](https://hedgedoc.org/)

For meetings, check whether the service requires an account, records sessions, stores metadata, or sends participants through a third-party server.

---

# privacy and security tools

- [KeePassXC](https://keepassxc.org/)
- [Bitwarden](https://bitwarden.com/)
- [VeraCrypt](https://www.veracrypt.fr/)
- [Cryptomator](https://cryptomator.org/)
- [age](https://age-encryption.org/)
- [GnuPG](https://gnupg.org/)
- [OpenSSH](https://www.openssh.com/)
- [OpenVPN](https://openvpn.net/)
- [WireGuard](https://www.wireguard.com/)
- [Tor](https://www.torproject.org/)
- [Tails](https://tails.net/)
- [Whonix](https://www.whonix.org/)
- [Qubes OS](https://www.qubes-os.org/)
- [ClamAV](https://www.clamav.net/)
- [Lynis](https://cisofy.com/lynis/)
- [OpenSCAP](https://www.open-scap.org/)
- [Portmaster](https://safing.io/portmaster/)
- [OpenSnitch](https://github.com/evilsocket/opensnitch)
- [Wireshark](https://www.wireshark.org/)
- [tcpdump](https://www.tcpdump.org/)
- [nmap](https://nmap.org/)

Only use security testing tools on systems and networks you own or have permission to test.

---

# vpn and dns

## vpn providers and projects

- [Mullvad VPN](https://mullvad.net/)
- [Proton VPN](https://protonvpn.com/)
- [IVPN](https://www.ivpn.net/)
- [Windscribe](https://windscribe.com/)
- [WireGuard](https://www.wireguard.com/)
- [OpenVPN](https://openvpn.net/)
- [Algo VPN](https://github.com/trailofbits/algo)
- [Outline](https://getoutline.org/)

A VPN changes which network sees your traffic first. It does not stop websites from recognizing you through logins, cookies, browser fingerprinting, or other signals.

## dns services

- [NextDNS](https://nextdns.io/)
- [Control D](https://controld.com/)
- [AdGuard DNS](https://adguard-dns.io/)
- [Quad9](https://quad9.net/)
- [Mullvad DNS](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls)
- [Cloudflare DNS](https://1.1.1.1/)
- [Pi-hole](https://pi-hole.net/)
- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html)
- [Technitium DNS](https://technitium.com/dns/)

DNS filtering can block some trackers and malicious domains, but it cannot block everything. Apps can use their own DNS, hardcoded IP addresses, or encrypted connections.

---

# self-hosting

Self-hosting means you operate the service yourself or manage the server where it runs.

That can be great. It can also mean updates at 2 AM because something broke.

## useful self-hosted projects

- [Nextcloud](https://nextcloud.com/) — files, calendar, contacts, collaboration, and more.
- [Immich](https://immich.app/) — photo and video management.
- [Jellyfin](https://jellyfin.org/) — media server.
- [Navidrome](https://www.navidrome.org/) — music server.
- [FreshRSS](https://freshrss.org/) — RSS reader.
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) — Bitwarden-compatible server.
- [Gitea](https://about.gitea.com/) — Git hosting.
- [Forgejo](https://forgejo.org/) — community Git hosting platform.
- [Woodpecker CI](https://woodpecker-ci.org/) — CI/CD system.
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — monitoring dashboard.
- [Homepage](https://github.com/gethomepage/homepage) — application dashboard.
- [Dashy](https://dashy.to/) — customizable dashboard.
- [Mealie](https://mealie.io/) — recipe manager.
- [Grocy](https://grocy.info/) — household management.
- [Paperless-ngx](https://docs.paperless-ngx.com/) — document management.
- [Calibre-Web](https://github.com/janeczku/calibre-web) — ebook library interface.
- [Kavita](https://www.kavitareader.com/) — digital library server.
- [Audiobookshelf](https://www.audiobookshelf.org/) — audiobook and podcast server.
- [Linkding](https://github.com/sissbruecker/linkding) — bookmark manager.
- [Wallabag](https://wallabag.org/) — read-it-later application.
- [Miniflux](https://miniflux.app/) — RSS reader.
- [Memos](https://www.usememos.com/) — lightweight note-taking service.
- [Outline](https://www.getoutline.com/) — knowledge base platform.
- [Excalidraw](https://github.com/excalidraw/excalidraw) — collaborative whiteboard.
- [SearXNG](https://github.com/searxng/searxng) — metasearch engine.
- [Whoogle](https://github.com/benbusby/whoogle-search) — search interface.
- [Matrix Synapse](https://github.com/element-hq/synapse) — Matrix homeserver.
- [Mumble](https://www.mumble.info/) — voice communication server.
- [Lemmy](https://join-lemmy.org/) — federated discussion platform.
- [PeerTube](https://joinpeertube.org/) — federated video platform.
- [Mastodon](https://joinmastodon.org/) — federated social platform.

## before self-hosting

Ask yourself:

- Do I have reliable hardware?
- Do I have enough storage?
- Do I understand updates?
- Do I have backups?
- Can I recover if the server dies?
- Do I need public internet access?
- Can I use a VPN or private network instead?
- Am I comfortable managing accounts and permissions?
- What happens if I stop maintaining it?
- Does the project have documentation?

Self-hosting an important service without backups is just making yourself the single point of failure.

---

# server management

- [Docker](https://www.docker.com/)
- [Podman](https://podman.io/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Kubernetes](https://kubernetes.io/)
- [Ansible](https://www.ansible.com/)
- [Caddy](https://caddyserver.com/)
- [Nginx](https://nginx.org/)
- [Traefik](https://traefik.io/traefik/)
- [Tailscale](https://tailscale.com/)
- [Headscale](https://github.com/juanfont/headscale)
- [WireGuard](https://www.wireguard.com/)
- [Restic](https://restic.net/)
- [Kopia](https://kopia.io/)
- [BorgBackup](https://www.borgbackup.org/)
- [Prometheus](https://prometheus.io/)
- [Grafana](https://grafana.com/)
- [Loki](https://grafana.com/oss/loki/)
- [Netdata](https://www.netdata.cloud/)
- [Uptime Kuma](https://github.com/louislam/uptime-kuma)
- [CrowdSec](https://www.crowdsec.net/)
- [Fail2ban](https://www.fail2ban.org/)

## basic server rules

- Keep the operating system updated.
- Use SSH keys instead of password login where practical.
- Disable services you don't need.
- Avoid exposing admin panels directly to the public internet.
- Use a firewall.
- Keep logs, but understand what they contain.
- Back up configuration files.
- Test restores.
- Use separate accounts instead of sharing one administrator account.
- Document how your setup works.
- Don't expose Docker sockets casually.
- Don't copy commands from random tutorials without understanding them.

---

# backup strategy

A backup is only useful if you can restore it.

## the 3-2-1 idea

A common backup approach is:

- **3** copies of important data.
- **2** different storage types or locations.
- **1** copy stored away from the main device or location.

You can adapt this to your situation. The exact number matters less than having more than one copy and testing recovery.

## backup tools

- [Restic](https://restic.net/)
- [Kopia](https://kopia.io/)
- [BorgBackup](https://www.borgbackup.org/)
- [Borgmatic](https://torsion.org/borgmatic/)
- [Duplicati](https://www.duplicati.com/)
- [Déjà Dup](https://apps.gnome.org/DejaDup/)
- [Timeshift](https://github.com/linuxmint/timeshift)
- [rsnapshot](https://rsnapshot.org/)
- [rsync](https://rsync.samba.org/)
- [Syncthing](https://syncthing.net/) — synchronization, not a complete backup by itself.

## what to back up

- Password manager vault.
- Recovery codes.
- Personal documents.
- Photos and videos.
- Project source code.
- SSH keys, if appropriate and protected.
- Application configuration files.
- Browser bookmarks.
- Important email.
- Contacts and calendars.
- Encryption keys.
- Server configuration.
- Database dumps.

Do not keep your only backup on the same drive as the original data.

---

# data migration

Moving away from a service is much easier when you export your data before you need it.

## general migration process

1. List what you currently use.
2. Identify which parts actually matter.
3. Find a replacement.
4. Read the replacement's import documentation.
5. Export your old data.
6. Make a backup of the export.
7. Import the data.
8. Test the replacement.
9. Keep the old account active for a while.
10. Update recovery information and connected services.
11. Remove the old service only after checking dependencies.

## export formats to look for

- CSV
- JSON
- Markdown
- TXT
- HTML
- ICS
- VCF
- ODT
- ODS
- PDF
- ZIP
- SQL dumps

Prefer formats that can be opened by multiple applications. A proprietary export may be useful, but it can make future migration harder.

## migration examples

### Gmail

- Export important messages.
- Update your email address on important accounts.
- Set up forwarding if available and appropriate.
- Notify contacts who need the new address.
- Check account recovery settings.
- Keep the old mailbox until you know it is no longer needed.

### Google Drive

- Download important files.
- Convert documents to formats your new software supports.
- Preserve folder structure where useful.
- Check shared files and ownership.
- Verify that downloaded files open correctly.
- Keep a second copy of the export.

### Google Photos

- Export original photos and videos.
- Check whether metadata was preserved.
- Verify that files are not corrupted.
- Organize photos before uploading them elsewhere.
- Keep an offline copy.

### Google Contacts

- Export contacts as VCF where possible.
- Import them into your new contacts provider.
- Check duplicate entries.
- Confirm phone numbers and email addresses.
- Make sure synchronization works on every device.

### Google Calendar

- Export calendars as ICS.
- Import them into your new calendar.
- Check recurring events and time zones.
- Recreate sharing permissions if necessary.
- Verify notifications.

---

# account cleanup

You don't have to delete every account immediately. Start by understanding what exists.

## cleanup checklist

- Review your Google account's connected applications.
- Remove old third-party integrations.
- Check logged-in devices.
- Review recovery email and phone number.
- Download important data.
- Review location history settings.
- Review ad personalization settings.
- Review YouTube watch and search history.
- Review saved payment methods.
- Remove old subscriptions.
- Review Google Play app history.
- Check old accounts you no longer use.
- Change reused passwords.
- Enable multi-factor authentication.
- Delete old emails and files only after checking whether you need them.

## account inventory

A basic spreadsheet or text file can help you track:

| service | email used | replacement | migrated? | notes |
|---|---|---|---|---|
| email | your old address | new provider | no | update recovery accounts |
| storage | old account | new storage | no | export files first |
| calendar | old account | new calendar | no | check shared events |
| photos | old account | new gallery | no | verify originals |
| authentication | old app | new authenticator | no | save recovery codes |

Do not put passwords or recovery codes into a publicly shared spreadsheet.

---

# tracking and telemetry

Telemetry is not always malicious. Developers often need crash reports, performance data, and usage statistics to improve software. The important part is understanding what is collected, why it is collected, and whether you can control it.

## things to review

- App permissions.
- Crash reporting.
- Analytics settings.
- Personalized advertising.
- Location history.
- Contact uploading.
- Clipboard access.
- Notification access.
- Accessibility permissions.
- Background activity.
- Cloud synchronization.
- Device identifiers.
- Third-party SDKs.
- Embedded trackers on websites.

## website privacy tools

- [uBlock Origin](https://github.com/gorhill/uBlock)
- [Privacy Badger](https://privacybadger.org/)
- [ClearURLs](https://github.com/ClearURLs/Addon)
- [Cookie AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete)
- [Decentraleyes](https://decentraleyes.org/)
- [LocalCDN](https://codeberg.org/nobody/LocalCDN)
- [LibRedirect](https://github.com/libredirect/libredirect)
- [EFF Cover Your Tracks](https://coveryourtracks.eff.org/)
- [Mozilla Observatory](https://observatory.mozilla.org/)
- [Have I Been Pwned](https://haveibeenpwned.com/)

A website privacy test is only a snapshot. Passing a test does not prove that a website is completely safe or private.

---

# open-source directories

These directories are useful when you want to discover projects beyond the most popular apps.

- [F-Droid](https://f-droid.org/)
- [AlternativeTo](https://alternativeto.net/)
- [Privacy Guides](https://www.privacyguides.org/)
- [Awesome Privacy](https://github.com/pluja/awesome-privacy)
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [Awesome Linux](https://github.com/luong-komorebi/Awesome-Linux-Software)
- [Awesome Open Source](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [OpenAlternative](https://openalternative.co/)
- [GitHub Explore](https://github.com/explore)
- [Codeberg](https://codeberg.org/)
- [SourceHut](https://sourcehut.org/)
- [GitLab](https://gitlab.com/)
- [FossHub](https://www.fosshub.com/)
- [Flathub](https://flathub.org/)
- [Snapcraft](https://snapcraft.io/)
- [Repology](https://repology.org/)

Check the license, recent commits, issue activity, release process, and download sources before installing software.

---

# useful privacy resources

- [Privacy Guides](https://www.privacyguides.org/)
- [Electronic Frontier Foundation](https://www.eff.org/)
- [Security in a Box](https://securityinabox.org/)
- [Techlore](https://techlore.tech/)
- [The New Oil](https://thenewoil.org/)
- [PrivacyTools](https://www.privacytools.io/)
- [Arkenfox wiki](https://github.com/arkenfox/user.js/wiki)
- [Mozilla support](https://support.mozilla.org/)
- [Tor Project documentation](https://support.torproject.org/)
- [GrapheneOS documentation](https://grapheneos.org/faq)
- [EFF Surveillance Self-Defense](https://ssd.eff.org/)
- [Open Source Security Foundation](https://openssf.org/)
- [OWASP](https://owasp.org/)

No guide can know your exact situation. Use resources as references, then make choices based on your own needs.

---

# common mistakes

## trying to replace everything in one day

This usually creates unnecessary stress. Start with the services you dislike most or the ones that are easiest to replace.

## choosing a tool only because it says privacy

Look at ownership, maintenance, documentation, security practices, and the actual data flow.

## forgetting recovery methods

If you replace your email or authenticator app without preparing recovery options, you can lock yourself out of your accounts.

## treating synchronization as backup

If a file is deleted everywhere through synchronization, you may lose every copy. Use versioned backups.

## installing too many extensions

More extensions can create maintenance problems, compatibility issues, and a more unique browser profile.

## trusting random download sites

Prefer official project websites, distribution repositories, verified releases, and package signatures where available.

## exposing self-hosted services unnecessarily

You probably do not need to expose every dashboard to the public internet. Private networks and VPN-based access may be safer and simpler.

## ignoring updates

A privacy-focused app with unpatched security issues is still a problem.

## assuming open source means automatically secure

Open source allows inspection and collaboration, but security also depends on review, maintenance, dependencies, release practices, and how the software is deployed.

## making privacy too inconvenient

If your setup is so annoying that you stop using it, it may not be sustainable. Make changes that fit your life.

---

# simple setups

These are example combinations, not strict recommendations.

## beginner desktop setup

- Browser: Firefox
- Blocking: uBlock Origin
- Search: DuckDuckGo or Brave Search
- Passwords: Bitwarden
- 2FA: Aegis or 2FAS
- Notes: Joplin
- Office: LibreOffice
- Media: VLC
- File sharing: LocalSend
- Maps: Organic Maps

## local-first setup

- Browser: Firefox
- Passwords: KeePassXC
- Notes: Markdown files or Joplin
- Office: LibreOffice
- Photos: local folders with a backup drive
- Music: MusicX, VLC, or Strawberry
- Sync: Syncthing
- Backup: Restic or Kopia
- Encryption: Cryptomator

## Android setup

- Browser: Firefox, Mull, or Brave
- App source: F-Droid plus trusted official sources
- Keyboard: HeliBoard or OpenBoard
- Maps: Organic Maps
- Gallery: Aves or Fossify Gallery
- Email: K-9 Mail or FairEmail
- Video: NewPipe
- Podcasts: AntennaPod
- File sharing: LocalSend
- Authenticator: Aegis

## self-hosted starter setup

- Server OS: Debian or Ubuntu Server
- Containers: Docker or Podman
- Remote access: Tailscale or WireGuard
- Reverse proxy: Caddy
- Monitoring: Uptime Kuma
- Backups: Restic or BorgBackup
- Dashboard: Homepage
- First service: FreshRSS, Linkding, or a small file service

Start small. A single maintained service is better than 30 abandoned containers.

---

# advanced setups

If you want to go further, you can gradually add:

- A private DNS resolver.
- Network-wide DNS filtering.
- A separate browser profile for testing.
- Hardware-backed authentication keys.
- A password manager with emergency recovery.
- Encrypted backups.
- A private VPN network.
- A self-hosted RSS reader.
- A personal photo server.
- A local media server.
- A Git forge.
- Monitoring and alerting.
- Infrastructure-as-code.
- A documented disaster recovery plan.
- A separate device for sensitive accounts.
- A firewall with explicit rules.
- Automatic security updates where appropriate.
- Regular restore tests.

Don't add advanced systems just to collect them. Every service you run is another thing you need to understand and maintain.

---

# migration checklist

## before switching

- [ ] Write down the services you currently depend on.
- [ ] Decide which service you want to replace first.
- [ ] Research at least two alternatives.
- [ ] Check device and platform support.
- [ ] Check whether your data can be exported.
- [ ] Check whether your new service can import it.
- [ ] Read the privacy policy and terms.
- [ ] Check pricing and limits.
- [ ] Check whether the project is maintained.
- [ ] Make a backup.

## during switching

- [ ] Create the new account if needed.
- [ ] Set a unique password.
- [ ] Enable multi-factor authentication.
- [ ] Import or copy your data.
- [ ] Test the main features.
- [ ] Test mobile and desktop access.
- [ ] Check notifications.
- [ ] Check sharing and collaboration.
- [ ] Update recovery information.
- [ ] Tell important contacts about changes.

## after switching

- [ ] Keep the old service temporarily.
- [ ] Check whether any account still uses the old email.
- [ ] Update saved bookmarks.
- [ ] Update password manager entries.
- [ ] Export a copy of the new data.
- [ ] Set up a backup.
- [ ] Review permissions.
- [ ] Remove unused integrations.
- [ ] Delete old data only when you are certain.
- [ ] Document anything you might forget later.

---

# contributing

Found something missing, outdated, broken, or just plain wrong?

Open an issue or pull request. Please include:

- The official project link.
- What the project does.
- Which category it belongs in.
- Whether it is open source, partially open source, or proprietary.
- Whether it is hosted, self-hosted, or both.
- Any important limitations.
- Whether the project is still maintained, if you know.

Please avoid adding random software just because it exists. The goal is to make this list useful, not to create a giant pile of links that nobody checks.

If a project is discontinued, compromised, misleading, or no longer maintained, feel free to open an issue so it can be reviewed.

---

# final thoughts

You don't need to delete your entire digital life overnight.

You can start by changing your browser. Or your search engine. Or your password manager. Or the app you use for notes. Or nothing at all until you find something worth changing.

The internet is full of useful projects made by people who aren't trying to build another giant platform around every part of your life. Some are polished. Some are weird. Some are unfinished. Some are better for specific people than others.

Try things. Read documentation. Keep backups. Don't trust marketing blindly. Don't make your setup harder than it needs to be.

**use less of what you don't need. keep control of what matters.**
