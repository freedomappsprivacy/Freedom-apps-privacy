# 🛡️ Awesome FOSS & Privacy Alternatives

The most complete list of Free and Open Source Software (FOSS) and privacy-respecting alternatives to mainstream software. Focus is on Linux / cross-platform tools, with select Windows/Android/iOS entries noted where relevant.

**Legend:**
- **FOSS:** ✅ Fully open source · ⚠️ Partially open (e.g. open clients, closed server) · ❌ Closed source but privacy-relevant
- **Privacy:** ⭐ (1-5) — how privacy-respecting the service/app is by design and policy
- **Platform:** where it runs — `Lin` Linux, `Win` Windows, `Mac` macOS, `Android`, `iOS`, `Self-hosted` (server, any OS via Docker/native), `Web` (browser-based)

> ⭐ Star this repo if you find it useful. Contributions welcome!

---

## 📚 Table of Contents

**[Featured Picks](#featured-picks)**

**Web & Search**
- [Browsers — Desktop](#browsers--desktop)
- [Browsers — Mobile](#browsers--mobile)
- [Search Engines](#search-engines)

**Communication**
- [Messaging Apps](#messaging-apps)
- [Email](#email)
- [Video Calls & Meetings](#video-calls--meetings)

**Social Media & Fediverse**
- [Mainstream App Alternatives](#mainstream-app-alternatives)
- [Fediverse Platforms](#fediverse-platforms)

**[Google Apps Alternatives](#google-apps-alternatives)**

**Cloud, Storage & Backup**
- [Cloud Storage & File Sync](#cloud-storage--file-sync)
- [Backup Tools](#backup-tools)

**Security, Encryption & Identity**
- [Password Managers](#password-managers)
- [Authenticator / 2FA Apps](#authenticator--2fa-apps)
- [Encryption Tools](#encryption-tools)
- [Metadata Removal & Privacy Auditing](#metadata-removal--privacy-auditing)
- [Secure Data Wiping](#secure-data-wiping)
- [Anonymous File Sharing](#anonymous-file-sharing)
- [Antivirus & Malware Scanning](#antivirus--malware-scanning)

**Anonymity, VPN & Networking**
- [VPN & Mesh Networking](#vpn--mesh-networking)
- [DNS & Ad-Blocking](#dns--ad-blocking)
- [Router Firmware & Firewalls](#router-firmware--firewalls)
- [Network Monitoring & Analysis](#network-monitoring--analysis)

**Operating Systems**
- [Anonymity-Focused](#anonymity-focused)
- [Investigation / Pentesting](#investigation--pentesting)
- [Gaming](#gaming)
- [Windows-Refugee Friendly](#windows-refugee-friendly)
- [Mainstream / Standard Distros](#mainstream--standard-distros)
- [Minimal / Low-RAM](#minimal--low-ram)
- [General Hardened / Daily-Driver](#general-hardened--daily-driver)
- [Debloated Windows](#debloated-windows)
- [Boot & Network Boot Tools](#boot--network-boot-tools)

**Mobile & Android**
- [Android App Stores](#android-app-stores)
- [Mobile ROMs](#mobile-roms)
- [Mobile Runtimes & Virtualization](#mobile-runtimes--virtualization)
- [Mobile Privacy & Firewall Tools](#mobile-privacy--firewall-tools)

**Productivity & Office**
- [Notes & Productivity](#notes--productivity)
- [Office Suites](#office-suites)
- [Project & Task Management](#project--task-management)
- [PDF Tools](#pdf-tools)
- [Personal Finance](#personal-finance)

**Media**
- [Media Servers & Streaming](#media-servers--streaming)
- [Image & Video Editing](#image--video-editing)
- [Media Downloaders](#media-downloaders)
- [Screen Recording & Streaming](#screen-recording--streaming)
- [E-Books & Reading](#e-books--reading)

**[News & RSS](#news--rss)**

**[Privacy-Respecting AI](#privacy-respecting-ai)**

**Self-Hosting & System Utilities**
- [Self-Hosting Platforms & Panels](#self-hosting-platforms--panels)
- [Torrenting / P2P Clients](#torrenting--p2p-clients)
- [Windows Compatibility on Linux](#windows-compatibility-on-linux)

**Smart Home & Niche Tools**
- [Presence Detection](#presence-detection)
- [Weather](#weather)

**[Curated Meta-Lists](#curated-meta-lists)**

---

## Featured Picks

Quick reference — the most-recommended pick(s) per use case:

| Use Case | Top Picks | Category |
|---|---|---|
| Browser (Desktop) | LibreWolf, Mullvad Browser, Tor Browser | Browsers |
| Browser (Mobile) | Mull, Tor Browser (Android), Vanadium | Browsers |
| Messaging | Signal, SimpleX Chat, Molly | Messaging Apps |
| Email | Tuta, Proton Mail | Email |
| Cloud Storage | Nextcloud, Syncthing, CryptPad | Cloud Storage |
| Password Manager | Bitwarden, KeePassXC, Vaultwarden | Password Managers |
| Encryption | VeraCrypt, Cryptomator, age | Encryption Tools |
| VPN | Mullvad, ProtonVPN, IVPN | VPN & Mesh Networking |
| Search | SearXNG | Search Engines |
| Notes | Joplin, Standard Notes, Logseq | Notes & Productivity |
| Local AI | Ollama, Jan, GPT4All | Privacy-Respecting AI |
| Media Server | Jellyfin, Immich | Media Servers & Streaming |
| Video Editing | Kdenlive, LosslessCut, Shotcut | Image & Video Editing |

---

## Browsers — Desktop

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Firefox](https://www.mozilla.org/firefox) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Main independent browser, Gecko engine |
| [LibreWolf](https://librewolf.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Hardened Firefox fork, no telemetry |
| [Mullvad Browser](https://mullvad.net/en/browser) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Built with Tor Project, strong anti-fingerprinting |
| [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Chromium without Google services |
| [Tor Browser](https://www.torproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Anonymity via the Tor network |
| [Brave](https://brave.com) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Chromium-based, built-in ad/tracker blocking |
| [Waterfox](https://www.waterfox.net) | ✅ | ⭐⭐⭐ | Lin/Win/Mac | Firefox fork, telemetry-free, older extension support |
| [Pale Moon](https://www.palemoon.org) | ✅ | ⭐⭐⭐ | Lin/Win | Independent Goanna-engine fork, very lightweight |
| [GNOME Web (Epiphany)](https://apps.gnome.org/Epiphany/) | ✅ | ⭐⭐⭐ | Lin | WebKit-based, minimal, GNOME default |
| [Falkon](https://www.falkon.org) | ✅ | ⭐⭐⭐ | Lin/Win | QtWebEngine-based, KDE default |
| [Qutebrowser](https://qutebrowser.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Keyboard-driven, vim-style, minimal UI |

## Browsers — Mobile

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Vanadium](https://github.com/GrapheneOS/Vanadium) | ✅ | ⭐⭐⭐⭐⭐ | Android | Default hardened browser on GrapheneOS |
| [Tor Browser for Android](https://www.torproject.org/download/#android) | ✅ | ⭐⭐⭐⭐⭐ | Android | Official Tor Browser |
| [Brave (mobile)](https://brave.com/mobile/) | ✅ | ⭐⭐⭐⭐ | Android/iOS | Built-in ad/tracker blocking |
| [Firefox Focus](https://www.mozilla.org/firefox/browsers/mobile/focus/) | ✅ | ⭐⭐⭐⭐ | Android/iOS | Privacy-first, auto-clears history |
| [Firefox (mobile)](https://www.mozilla.org/firefox/browsers/mobile/) | ✅ | ⭐⭐⭐ | Android/iOS | Full version with extension support |
| [Mull](https://gitlab.com/divested-mobile/mull-fenix) | ✅ | ⭐⭐⭐⭐⭐ | Android | LibreWolf-equivalent, via F-Droid |
| [Cromite](https://github.com/uazo/cromite) | ✅ | ⭐⭐⭐⭐ | Android | Actively maintained ungoogled/Bromite continuation |
| [Onion Browser](https://onionbrowser.com) | ✅ | ⭐⭐⭐⭐⭐ | iOS | Tor-based |

---

## Search Engines

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [SearXNG](https://searxng.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Metasearch engine, combines results from multiple sources |
| [YaCy](https://yacy.net) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Peer-to-peer engine with its own crawler — build your own index |
| [Mojeek](https://www.mojeek.com) | ❌ | ⭐⭐⭐⭐ | Web | Independent crawler, one of few with its own index |
| [Brave Search](https://search.brave.com) | ❌ | ⭐⭐⭐⭐ | Web | Independent index, no tracking |
| [DuckDuckGo](https://duckduckgo.com) | ❌ | ⭐⭐⭐ | Web | Privacy-oriented, uses Bing data under the hood |
| [Startpage](https://www.startpage.com) | ❌ | ⭐⭐⭐ | Web | Anonymized Google results proxy |
| [Ecosia](https://www.ecosia.org) | ❌ | ⭐⭐⭐ | Web | Tree-planting initiative, uses Bing data |
| [Yandex](https://yandex.com) | ❌ | ⭐ | Web | Least censored major engine, Russian-based, not private |
| [Presearch](https://presearch.com) | ⚠️ | ⭐⭐⭐ | Web | Decentralized/crypto-incentivized search |

---

## Messaging Apps

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Signal](https://signal.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Gold standard, E2EE by default, minimal metadata |
| [Molly](https://molly.im) | ✅ | ⭐⭐⭐⭐⭐ | Android | Signal fork with extra hardening (encrypted local DB, panic-wipe) — great fit for GrapheneOS |
| [SimpleX Chat](https://simplex.chat) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | No phone/username/ID at all — strongest metadata protection |
| [Session](https://getsession.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | No phone number, onion-routing based |
| [Threema](https://threema.ch) | ⚠️ | ⭐⭐⭐⭐ | Android/iOS/Win/Mac/Lin | Anonymous random ID, Swiss-based, paid app |
| [Briar](https://briarproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Android | Works via Tor/WiFi/Bluetooth mesh, no internet required |
| [Wire](https://wire.com) | ✅ | ⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Team/business focused |
| [Element (Matrix)](https://element.io) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Self-hostable, federated |
| [Jami](https://jami.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Fully P2P/distributed, no central server at all |
| [Delta Chat](https://delta.chat) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Messaging over standard email infrastructure |
| [Cwtch](https://cwtch.im) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android | Metadata-resistant, built on Tor onion services |
| [TeleGuard](https://teleguard.com) | ❌ | ⭐⭐⭐ | Android/iOS | By Swisscows, zero personal info needed but closed-source |

---

## Email

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Tutanota (Tuta)](https://tuta.com) | ✅ | ⭐⭐⭐⭐⭐ | Web/Android/iOS | E2EE, German-based |
| [Proton Mail](https://proton.me/mail) | ⚠️ | ⭐⭐⭐⭐⭐ | Web/Android/iOS/Lin/Win/Mac | FOSS clients, Swiss-based |
| [Disroot Email](https://disroot.org) | ✅ | ⭐⭐⭐⭐ | Web | Non-profit collective, no logs |
| [AtomicMail](https://atomicmail.io) | ❌ | ⭐⭐⭐⭐ | Web | No phone verification, Web3/crypto-wallet linked identity |
| [Mailbox.org](https://mailbox.org) | ❌ | ⭐⭐⭐⭐ | Web | German, PGP support |
| [Posteo](https://posteo.de) | ❌ | ⭐⭐⭐⭐ | Web | German, anonymous payment options |
| [Runbox](https://runbox.com) | ❌ | ⭐⭐⭐ | Web | Norway-based, no ads |
| [StartMail](https://www.startmail.com) | ❌ | ⭐⭐⭐⭐ | Web | Dutch-based, from Startpage team |
| [Skiff Mail](https://skiff.com) | ⚠️ | ⭐⭐⭐ | Web | ⚠️ Acquired by Notion in 2024, service discontinued — don't sign up |
| [Mailcow](https://mailcow.email) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full self-hosted mail server stack |
| [Mail-in-a-Box](https://mailinabox.email) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Simplified self-hosted mail server |

## Video Calls & Meetings

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Jitsi Meet](https://meet.jit.si) | ✅ | ⭐⭐⭐⭐⭐ | Web/Self-hosted | No account needed, E2EE option |
| [Element Call](https://element.io/call) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS/Web | Integrated with Matrix ecosystem |
| [Nextcloud Talk](https://nextcloud.com/talk/) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Bundled with Nextcloud, video/chat/screen-share |

---

## Mainstream App Alternatives

### Facebook
| Option | FOSS | Note |
|---|---|---|
| [Diaspora](https://diasporafoundation.org) | ✅ | Decentralized, federated, no ads |
| [Friendica](https://friendi.ca) | ✅ | Connects with Mastodon/Diaspora/other networks |
| [Minds](https://www.minds.com) | ✅ | Crypto-rewards social network |

### Twitter / X
| Option | FOSS | Note |
|---|---|---|
| [Mastodon](https://joinmastodon.org) | ✅ | Biggest decentralized Twitter alternative |
| [Nitter](https://github.com/zedeus/nitter) | ✅ | Privacy frontend (⚠️ many public instances unstable due to API changes) |
| [Misskey](https://misskey-hub.net) | ✅ | Twitter-style Fediverse server |
| [Pleroma](https://pleroma.social) | ✅ | Lightweight Fediverse server |

### Instagram
| Option | FOSS | Note |
|---|---|---|
| [Pixelfed](https://pixelfed.org) | ✅ | Photo-sharing Fediverse alternative |
| [Barinsta](https://github.com/austinhuang0131/barinsta) | ✅ | Privacy-friendly Instagram client, Android |

### YouTube
| Option | FOSS | Note |
|---|---|---|
| [Invidious](https://invidious.io) | ✅ | Privacy frontend, no ads/tracking |
| [Piped](https://piped.video) | ✅ | Similar to Invidious, actively maintained |
| [FreeTube](https://freetubeapp.io) | ✅ | Private desktop client |
| [NewPipe](https://newpipe.net) | ✅ | Lightweight Android client, background play |
| [LibreTube](https://libre-tube.github.io) | ✅ | Android frontend using Piped backend |
| [PeerTube](https://joinpeertube.org) | ✅ | Full decentralized video-hosting platform |

### WhatsApp
| Option | FOSS | Note |
|---|---|---|
| [Signal](https://signal.org) | ✅ | Gold standard, E2EE |
| [Session](https://getsession.org) | ✅ | No phone number required |
| [Element (Matrix)](https://element.io) | ✅ | Decentralized, self-hostable |

### Reddit
| Option | FOSS | Note |
|---|---|---|
| [Lemmy](https://join-lemmy.org) | ✅ | Full Reddit-style federated platform |
| [Redlib](https://github.com/redlib-org/redlib) | ✅ | Privacy frontend (successor to discontinued Libreddit) |
| [Kbin / Mbin](https://mbin.grjy.info) | ✅ | Fediverse platform combining Reddit+Lemmy-style features |
| [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit) | ✅ | Third-party client, strong anonymous mode, still actively maintained |
| [RedReader](https://github.com/QuantumBadger/RedReader) | ✅ | Lightweight, actively maintained third-party client |

### Discord
| Option | FOSS | Note |
|---|---|---|
| [Element (Matrix)](https://element.io) | ✅ | Full chat/voice alternative |
| [Revolt](https://revolt.chat) | ✅ | Discord-like UI, actively growing |

## Fediverse Platforms

The Fediverse is a network of interconnected, independently-run servers (via ActivityPub protocol) — an alternative to centralized social media. All entries below are FOSS and self-hosted.

| Platform | Replaces | Note |
|---|---|---|
| [Mastodon](https://joinmastodon.org) | Twitter/X | Largest, most well-known Fediverse platform |
| [Misskey](https://misskey-hub.net) | Twitter/X | Feature-rich, more experimental UI/UX |
| [Firefish](https://firefish.dev) / [Iceshrimp](https://iceshrimp.dev) | Twitter/X | Misskey forks with continued active development |
| [Pleroma](https://pleroma.social) | Twitter/X | Lightweight server software, low resource use |
| [Akkoma](https://akkoma.social) | Twitter/X | Pleroma fork, more actively maintained |
| [GoToSocial](https://gotosocial.org) | Twitter/X | Lightweight Mastodon-compatible server, good for low-resource hosting |
| [Friendica](https://friendi.ca) | Facebook | Connects across multiple Fediverse platforms |
| [Hubzilla](https://hubzilla.org) | Facebook | Advanced identity/permission system, nomadic identity |
| [Socialhome](https://socialhome.network) | Facebook | Profile/stream-based social network |
| [diaspora*](https://diasporafoundation.org) | Facebook | One of the earliest federated social networks |
| [Pixelfed](https://pixelfed.org) | Instagram | Photo-sharing |
| [PeerTube](https://joinpeertube.org) | YouTube | Decentralized video hosting |
| [Lemmy](https://join-lemmy.org) | Reddit | Link-aggregation/forum platform |
| [Kbin / Mbin](https://mbin.grjy.info) | Reddit | Combines Reddit+Lemmy-style features |
| [WriteFreely](https://writefreely.org) | Medium/Blogging | Minimalist federated blogging |
| [Funkwhale](https://funkwhale.audio) | Spotify/SoundCloud | Federated audio/music streaming |
| [Bookwyrm](https://joinbookwyrm.com) | Goodreads | Federated book tracking & reviews |
| [Mobilizon](https://joinmobilizon.org) | Facebook Events | Federated event planning |
| [Owncast](https://owncast.online) | Twitch | Self-hosted live streaming |

---

## Google Apps Alternatives

> Some of these are components rather than 1-to-1 replacements — noted where relevant.

| Google App | Alternative(s) | Note |
|---|---|---|
| Gmail | [Tuta](https://tuta.com), [Proton Mail](https://proton.me/mail) | See [Email](#email) |
| Google Drive | [Nextcloud](https://nextcloud.com), [Seafile](https://www.seafile.com), [Syncthing](https://syncthing.net) | See [Cloud Storage](#cloud-storage--file-sync) |
| Google Docs/Sheets/Slides | [OnlyOffice](https://www.onlyoffice.com), [Collabora Online](https://www.collaboraoffice.com/collabora-online/), [CryptPad](https://cryptpad.org) | Cloud-editable, self-hostable |
| Google Calendar | [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar), [Proton Calendar](https://proton.me/calendar), [Tuta Calendar](https://tuta.com/calendar) | CalDAV-based options |
| Google Photos | [Ente Photos](https://ente.io), [Immich](https://immich.app), [PhotoPrism](https://www.photoprism.app), [Nextcloud Memories](https://memories.gallery) | Immich is the fastest-growing self-hosted option |
| Google Play Store | See [Android App Stores](#android-app-stores) | — |
| Gboard | [FlorisBoard](https://florisboard.org), [HeliBoard](https://github.com/Helium314/HeliBoard), [OpenBoard](https://github.com/openboard-team/openboard), [AnySoftKeyboard](https://anysoftkeyboard.github.io), [Simple Keyboard](https://github.com/rkkr/simple-keyboard) | HeliBoard is an actively-developed OpenBoard fork with better UX |
| Google Assistant | [Home Assistant Voice / local pipelines](https://www.home-assistant.io/voice_control/) | Self-hosted, local processing |
| Google Translate | [LibreTranslate](https://libretranslate.com) | Fully open translation API/app |
| Google Meet | [Jitsi Meet](https://meet.jit.si), [Element Call](https://element.io/call) | See [Video Calls](#video-calls--meetings) |
| Google Analytics | [Matomo](https://matomo.org), [Plausible](https://plausible.io), [Umami](https://umami.is), [GoatCounter](https://www.goatcounter.com) | GoatCounter: extremely lightweight, no cookies at all |
| Google Lens | [firefox-translator](https://github.com/DavidVentura/firefox-translator) (OCR+translate overlay), Tesseract-based OCR, [Binary Eye](https://github.com/markusfisch/BinaryEye) (QR/barcode) | ⚠️ No full 1:1 FOSS replacement exists — Lens combines OCR, translation, and object ID; these cover individual pieces only |
| Google Maps | [OpenStreetMap](https://www.openstreetmap.org), [OrganicMaps](https://organicmaps.app), [Magic Earth](https://www.magicearth.com) | OSM-based, offline capable |
| Google News | See [News & RSS](#news--rss) | — |
| Google Authenticator | See [Authenticator / 2FA Apps](#authenticator--2fa-apps) | — |
| Google Chrome | See [Browsers](#browsers--desktop) | — |

---

## Cloud Storage & File Sync

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Nextcloud](https://nextcloud.com) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full suite: files, calendar, contacts, office |
| [Seafile](https://www.seafile.com) | ✅ | ⭐⭐⭐⭐ | Self-hosted | Fast sync, good for large files |
| [Syncthing](https://syncthing.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android | Peer-to-peer sync, no central server |
| [CryptPad](https://cryptpad.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted/Web | Zero-knowledge encrypted collaboration |
| [ownCloud](https://owncloud.com) | ✅ | ⭐⭐⭐⭐ | Self-hosted | Nextcloud's predecessor/parallel project |
| [Proton Drive](https://proton.me/drive) | ⚠️ | ⭐⭐⭐⭐⭐ | Web/Android/iOS | E2EE, Swiss-based, FOSS clients |
| [MEGA](https://mega.nz) | ⚠️ | ⭐⭐⭐⭐ | Web/Lin/Win/Mac/Android/iOS | Client-side zero-knowledge encryption, generous free tier |
| [Internxt](https://internxt.com) | ⚠️ | ⭐⭐⭐⭐ | Web/Lin/Win/Mac | Zero-knowledge encryption, EU-based |
| [Filen](https://filen.io) | ⚠️ | ⭐⭐⭐⭐ | Web/Lin/Win/Mac/Android/iOS | E2EE consumer cloud storage |
| [pCloud](https://www.pcloud.com) | ❌ | ⭐⭐⭐ | Web/Lin/Win/Mac | Optional client-side encryption add-on |
| [Tresorit](https://tresorit.com) | ❌ | ⭐⭐⭐⭐ | Web/Lin/Win/Mac | Business-focused, E2EE |

## Backup Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [BorgBackup](https://www.borgbackup.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Mac | Deduplicating, encrypted backups, very mature |
| [Restic](https://restic.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Fast, encrypted, supports many storage backends (incl. cloud) |
| [Kopia](https://kopia.io) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Encrypted, deduplicating, has a GUI |
| [Duplicati](https://duplicati.com) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | GUI-based, scheduled encrypted backups to cloud/local |

---

## Password Managers

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Bitwarden](https://bitwarden.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS/Web | Full-featured, cloud or self-hosted sync |
| [KeePassXC](https://keepassxc.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Fully offline, local vault |
| [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Lightweight Bitwarden-compatible self-hosted server |
| [KeePass (original)](https://keepass.info) | ✅ | ⭐⭐⭐⭐⭐ | Win (+ports) | Windows-native original, many cross-platform ports exist |
| [Password Safe](https://pwsafe.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Bruce Schneier-designed, offline |
| [PassBolt](https://www.passbolt.com) | ✅ | ⭐⭐⭐⭐ | Self-hosted | Team-oriented, OpenPGP-based |
| [Proton Pass](https://proton.me/pass) | ⚠️ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS/Web | E2EE, part of Proton suite |

## Authenticator / 2FA Apps

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Aegis Authenticator](https://getaegis.app) | ✅ | ⭐⭐⭐⭐⭐ | Android | Encrypted vault, backup/import support |
| [FreeOTP](https://freeotp.github.io) | ✅ | ⭐⭐⭐⭐⭐ | Android/iOS | Simple, Red Hat-backed |
| [Ente Auth](https://ente.io/auth) | ✅ | ⭐⭐⭐⭐⭐ | Android/iOS/Web | E2EE cloud sync across devices |
| [Raivo OTP](https://github.com/raivo-otp/ios-application) | ✅ | ⭐⭐⭐⭐⭐ | iOS | iCloud E2EE backup |
| [KeePassXC (TOTP field)](https://keepassxc.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Combine password manager + TOTP in one vault |
| [Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro) | ✅ | ⭐⭐⭐⭐ | Android | Authy-style categories |
| [2FAS](https://2fas.com) | ✅ | ⭐⭐⭐⭐ | Android/iOS | Cross-platform, encrypted cloud backup |
| [andOTP](https://github.com/andOTP/andOTP) | ✅ | ⭐⭐⭐⭐ | Android | Archived but still usable, encrypted backups |

## Encryption Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [VeraCrypt](https://www.veracrypt.fr) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard for on-disk encrypted containers/full-disk encryption, TrueCrypt successor |
| [Cryptomator](https://cryptomator.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Transparent client-side encryption for any cloud storage folder |
| [GnuPG (GPG)](https://gnupg.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard for file/email encryption and signing |
| [age](https://github.com/FiloSottile/age) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Modern, simple file encryption tool, minimal footprint |
| [LUKS / LUKS2](https://gitlab.com/cryptsetup/cryptsetup) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Native Linux full-disk encryption, standard on most distros |
| [LUKSbox](https://github.com/PentHertz/LUKSbox) | ✅ | ⭐⭐⭐⭐ | Lin/Mac/Win | Encrypted container mountable as a drive; passphrase, FIDO2, TPM 2.0, post-quantum keyslots. Pre-1.0, actively developed |
| [Picocrypt](https://github.com/Picocrypt/Picocrypt) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Small, simple single-file encryption tool |

## Metadata Removal & Privacy Auditing

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [MAT2](https://0xacab.org/jvoisin/mat2) | ✅ | ⭐⭐⭐⭐⭐ | Lin (CLI/GUI via nautilus) | Metadata Anonymisation Toolkit — strips EXIF/author/GPS data before sharing files |
| [ExifCleaner](https://github.com/szTheory/exifcleaner) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | GUI drag-and-drop metadata remover for photos/docs |
| [Have I Been Pwned](https://haveibeenpwned.com) | ❌ | ⭐⭐⭐⭐ | Web | Not FOSS, but the standard tool for checking your own data-breach exposure |

## Secure Data Wiping

| Tool | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [nwipe](https://github.com/martijnvanbrummelen/nwipe) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Modern fork of DBAN, multi-pass secure disk wiping (GUI + CLI) |
| [shredOS](https://github.com/PartialVolume/shredos.x86_64) | ✅ | ⭐⭐⭐⭐⭐ | Bootable (Lin-based) | Bootable DBAN-alternative based on nwipe |
| `shred` (GNU coreutils) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Standard Linux command for secure file deletion |

## Anonymous File Sharing

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [OnionShare](https://onionshare.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Share files/folders anonymously via a Tor hidden service, no account, no central server |

## Antivirus & Malware Scanning

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [ClamAV](https://www.clamav.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard open-source antivirus engine, also used server-side |
| [rkhunter](https://rkhunter.sourceforge.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Rootkit hunter/scanner |

---

## VPN & Mesh Networking

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Mullvad](https://mullvad.net) | ⚠️ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | FOSS clients, no account info required, cash accepted, proven no-logs via independent audits |
| [ProtonVPN](https://protonvpn.com) | ⚠️ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | FOSS clients, Swiss-based, proven no-logs (independent audits, latest 2026 by Securitum) |
| [IVPN](https://www.ivpn.net) | ⚠️ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | FOSS clients, strong privacy stance, proven no-logs via audits |
| [OVPN](https://www.ovpn.com) | ⚠️ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Swedish, diskless servers, court-verified no-logs policy |
| [AirVPN](https://airvpn.org) | ⚠️ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Run by activists, transparent |
| [PIA (Private Internet Access)](https://www.privateinternetaccess.com) | ⚠️ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | FOSS clients, long-standing, audited no-logs |
| [WireGuard](https://www.wireguard.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Underlying modern VPN protocol used by most above |
| [Orbot](https://orbot.app) | ✅ | ⭐⭐⭐⭐⭐ | Android/iOS | Tor proxy/VPN — routes other apps' traffic through Tor |
| [Headscale](https://headscale.net) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | FOSS self-hosted Tailscale control server |
| [Tailscale](https://tailscale.com) | ⚠️ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | WireGuard-based mesh VPN, easy self-hosted alternative via Headscale |
| [Netbird](https://netbird.io) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Open-source WireGuard mesh VPN, self-hostable control plane |
| [Nostr VPN](https://nostrvpn.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Tailscale-style mesh VPN using Nostr keypairs instead of accounts — no coordination server needed; very new/early-stage project |

## DNS & Ad-Blocking

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Pi-hole](https://pi-hole.net) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Network-wide ad blocking via DNS |
| [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Pi-hole alternative, easier setup |
| [uBlock Origin](https://ublockorigin.com) | ✅ | ⭐⭐⭐⭐⭐ | Browser extension | Essential browser-level blocker, not DNS-based |
| [Blokada](https://blokada.org) | ✅ | ⭐⭐⭐⭐ | Android/iOS | Mobile DNS/ad blocking, no root needed |
| [NextDNS](https://nextdns.io) | ❌ | ⭐⭐⭐⭐ | Cross-platform | Cloud DNS filtering, cross-device, no-log policy |
| [ControlD](https://controld.com) | ❌ | ⭐⭐⭐⭐ | Cross-platform | Customizable filtering DNS service |

## Router Firmware & Firewalls

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [OpenWrt](https://openwrt.org) | ✅ | ⭐⭐⭐⭐⭐ | Router firmware | The standard FOSS router firmware, huge device support |
| [pfSense CE](https://www.pfsense.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted (x86) | Full-featured open-source firewall/router OS |
| [OPNsense](https://opnsense.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted (x86) | pfSense fork, very actively developed |
| [IPFire](https://www.ipfire.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted (x86) | Security-focused Linux firewall distribution |

## Network Monitoring & Analysis

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Sniffnet](https://www.sniffnet.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Cross-platform traffic monitor: stats, geolocation, protocol detection, all processing local |
| [Wireshark](https://www.wireshark.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard network protocol analyzer |

---

## Anonymity-Focused

| OS | FOSS | Note |
|---|---|---|
| [Tails](https://tails.net) | ✅ | Amnesic, routes everything through Tor, leaves no trace |
| [Whonix](https://www.whonix.org) | ✅ | Gateway + Workstation VM setup, all traffic via Tor |
| [Kicksecure](https://www.kicksecure.com) | ✅ | Hardened Debian-based OS, foundation for Whonix |

## Investigation / Pentesting

| OS | FOSS | Note |
|---|---|---|
| [Kali Linux](https://www.kali.org) | ✅ | Most well-known pentesting distro |
| [Parrot OS](https://parrotsec.org) | ✅ | Security + privacy focus, lighter than Kali |
| [BlackArch](https://blackarch.org) | ✅ | Arch-based, huge tool repository |

## Gaming

| OS | FOSS | Note |
|---|---|---|
| [Bazzite](https://bazzite.gg) | ✅ | SteamOS-like, immutable, great for handhelds/desktop |
| [Nobara](https://nobaraproject.org) | ✅ | Fedora-based, gaming-optimized patches |
| [SteamOS](https://store.steampowered.com/steamos) | ⚠️ | Valve's own, Steam Deck's OS, partially closed |

## Windows-Refugee Friendly

| OS | FOSS | Note |
|---|---|---|
| [Linux Mint](https://linuxmint.com) | ✅ | Most beginner-friendly, familiar UI |
| [Zorin OS](https://zorin.com/os) | ⚠️ | Windows-like layout, some paid pro features |
| [Pop!_OS](https://pop.system76.com) | ✅ | Clean, good for beginners and power users |

## Mainstream / Standard Distros

| OS | FOSS | Note |
|---|---|---|
| [Debian](https://www.debian.org) | ✅ | The stability backbone many other distros are built on |
| [Ubuntu](https://ubuntu.com) | ✅ | Most widely used desktop/server distro, Debian-based |
| [Fedora](https://fedoraproject.org) | ✅ | Cutting-edge, Red Hat-sponsored |
| [Arch Linux](https://archlinux.org) | ✅ | Rolling release, build-it-yourself philosophy |
| [Manjaro](https://manjaro.org) | ✅ | Arch made accessible, curated stable rolling release |
| [openSUSE (Tumbleweed/Leap)](https://www.opensuse.org) | ✅ | Strong tooling (YaST), both rolling and fixed releases |
| [EndeavourOS](https://endeavouros.com) | ✅ | Arch-based, minimal but user-friendly installer |
| [Void Linux](https://voidlinux.org) | ✅ | Independent, runit init instead of systemd |
| [Gentoo](https://www.gentoo.org) | ✅ | Source-based, full compile-time customization |
| [NixOS](https://nixos.org) | ✅ | Fully declarative, reproducible system configuration |
| [MX Linux](https://mxlinux.org) | ✅ | Debian-based, lightweight, popular on older/laptop hardware |

## Minimal / Low-RAM

| Distro | RAM Usage | Note |
|---|---|---|
| [Tiny Core Linux](https://www.tinycorelinux.net) | ~64MB | Extremely minimal, modular |
| [antiX](https://antixlinux.com) | ~128MB | Debian-based, systemd-free option |
| [Puppy Linux](https://puppylinux-woof-ce.github.io) | ~128-256MB | Runs entirely from RAM |
| [Bodhi Linux](https://www.bodhilinux.com) | ~256MB | Enlightenment desktop, lightweight |
| [Q4OS](https://q4os.org) | ~256MB | Trinity/KDE, very light |
| [absolute Linux](https://www.absolutelinux.org) | ~200MB | Slackware-based, IceWM |
| [SparkyLinux (minimal editions)](https://sparkylinux.org) | ~256MB | Debian-based, multiple lightweight editions |

## General Hardened / Daily-Driver

| OS | FOSS | Note |
|---|---|---|
| [Qubes OS](https://www.qubes-os.org) | ✅ | Compartmentalized security via VMs |
| [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) | ✅ | Immutable desktop, atomic updates |

## Debloated Windows

> These are Windows-based by nature (for dual-boot/VM use where Windows is still unavoidable) rather than Linux alternatives.

| Tool | FOSS | Note |
|---|---|---|
| [Tiny11](https://github.com/ntdevlabs/tiny11builder) | ✅ | Stripped-down Windows 11 image |
| [AtlasOS](https://atlasos.net) | ✅ | Performance/privacy-focused Windows tweak set |
| [ReviOS](https://revi.cc) | ✅ | Debloated Windows image |

## Boot & Network Boot Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Ventoy](https://www.ventoy.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win | Multi-ISO bootable USB creator, no re-flashing needed per ISO |
| [EtchDroid](https://github.com/etchdroid/etchdroid) | ✅ | ⭐⭐⭐⭐ | Android | Write OS images to USB directly from Android, no root needed |
| [netboot.xyz](https://netboot.xyz) | ✅ | ⭐⭐⭐⭐ | Self-hosted | Network-boot menu for dozens of OSes/tools via iPXE |

---

## Android App Stores

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [F-Droid](https://f-droid.org) | ✅ | ⭐⭐⭐⭐⭐ | The original catalogue of FOSS Android apps |
| [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore) | ✅ | ⭐⭐⭐⭐ | Anonymous frontend to the real Google Play Store |
| [Accrescent](https://accrescent.app) | ✅ | ⭐⭐⭐⭐⭐ | New store focused on security, privacy & app signing verification |
| [Obtainium](https://github.com/ImranR98/Obtainium) | ✅ | ⭐⭐⭐⭐⭐ | Installs/updates apps directly from GitHub/GitLab releases |
| [Droid-ify](https://github.com/Droid-ify/client) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight, modern F-Droid client |
| [Neo Store](https://github.com/NeoApplications/Neo-Store) | ✅ | ⭐⭐⭐⭐⭐ | Modern F-Droid client fork |
| [IzzyOnDroid repo](https://apt.izzysoft.de/fdroid/) | ✅ | ⭐⭐⭐⭐ | Extra F-Droid repository, many more apps |
| [Uptodown](https://uptodown.com) | ❌ | ⭐⭐ | Non-Play APK store, no account needed |
| [APKMirror](https://www.apkmirror.com) | ❌ | ⭐⭐ | Verified APK mirror, browser-only |
| [Amazon Appstore](https://www.amazon.com/appstore) | ❌ | ⭐⭐ | Pre-installed on Fire devices, sideloadable elsewhere |
| [Huawei AppGallery](https://appgallery.huawei.com) | ❌ | ⭐⭐ | Alternative ecosystem, mainly for Huawei devices |

## Mobile ROMs

| ROM | FOSS | Privacy | Note |
|---|---|---|---|
| [GrapheneOS](https://grapheneos.org) | ✅ | ⭐⭐⭐⭐⭐ | Security & privacy hardened, Pixel-only |
| [CalyxOS](https://calyxos.org) | ✅ | ⭐⭐⭐⭐⭐ | Privacy-focused, includes microG option |
| [DivestOS](https://divestos.org) | ✅ | ⭐⭐⭐⭐⭐ | LineageOS-based, extended device support & security patches |
| [LineageOS](https://lineageos.org) | ✅ | ⭐⭐⭐⭐ | Broadest device support |
| [/e/OS](https://e.foundation) | ✅ | ⭐⭐⭐⭐ | De-googled, consumer-friendly |
| [PostmarketOS](https://postmarketos.org) | ✅ | ⭐⭐⭐⭐ | Full Linux (not Android) on phones, mainline kernel focus |
| [Ubuntu Touch](https://ubuntu-touch.io) | ✅ | ⭐⭐⭐⭐ | Full Linux mobile OS, by UBports |

## Mobile Runtimes & Virtualization

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Waydroid](https://waydro.id) | ✅ | ⭐⭐⭐⭐ | Full Android in a Linux container (Wayland) — excellent for privacy-conscious users needing an Android app occasionally |
| [Termux](https://termux.dev) + [proot-distro](https://github.com/termux/proot-distro) | ✅ | ⭐⭐⭐⭐ | Run a real Linux distro (Debian/Ubuntu/Alpine) directly on Android, no root |
| [UserLAnd](https://github.com/CypherpunkArmory/UserLAnd) | ✅ | ⭐⭐⭐⭐ | GUI-friendly way to run Linux distros on Android via Termux/proot |
| [Andronix](https://andronix.app) | ⚠️ | ⭐⭐⭐ | Scripts to set up full Linux desktops on Android via Termux |

## Mobile Privacy & Firewall Tools

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [NetGuard](https://www.netguard.me) | ✅ | ⭐⭐⭐⭐⭐ | No-root Android firewall, per-app internet access control |
| [RethinkDNS](https://rethinkdns.com) | ✅ | ⭐⭐⭐⭐⭐ | Combined firewall + DNS + VPN, fully local, no-root |
| [TrackerControl](https://trackercontrol.org) | ✅ | ⭐⭐⭐⭐⭐ | Detects and blocks embedded trackers in installed apps |

---

## Notes & Productivity

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Joplin](https://joplinapp.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Evernote alternative, E2EE sync |
| [Standard Notes](https://standardnotes.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS/Web | Simple, extensible, E2EE |
| [Logseq](https://logseq.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Privacy-first knowledge management, local-first |
| [Trilium Notes](https://github.com/zadam/trilium) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Hierarchical, self-hosted, very powerful |
| [Notesnook](https://notesnook.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Evernote alternative, E2EE |
| [Anytype](https://anytype.io) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Local-first, E2EE, Notion-style |
| [AFFiNE](https://affine.pro) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/Web | Notion/Miro-style all-in-one |
| [Obsidian](https://obsidian.md) | ⚠️ | ⭐⭐⭐⭐ | Lin/Win/Mac/Android/iOS | Free, local-first, but not open source |

## Office Suites

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [LibreOffice](https://www.libreoffice.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Standard offline suite |
| [OnlyOffice](https://www.onlyoffice.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Self-hosted | Best MS Office file compatibility |
| [Collabora Online](https://www.collaboraoffice.com/collabora-online/) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | LibreOffice-based, integrates with Nextcloud |
| [Apache OpenOffice](https://www.openoffice.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | LibreOffice's predecessor, less actively developed |

## Project & Task Management

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Vikunja](https://vikunja.io) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full-featured self-hosted Todoist/Trello-style task manager |
| [OpenProject](https://www.openproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full project management suite, Gantt charts, Community Edition is FOSS |
| [Focalboard](https://www.focalboard.com) | ✅ | ⭐⭐⭐⭐ | Self-hosted | Trello-style kanban boards (now developed as part of Mattermost) |

## PDF Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full self-hosted PDF toolkit: merge, split, OCR, convert, watermark |
| [PDFsam](https://pdfsam.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Desktop merge/split/rotate tool |
| [LibreOffice Draw](https://www.libreoffice.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Basic PDF editing via LibreOffice |

## Personal Finance

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Firefly III](https://www.firefly-iii.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted | Full-featured personal finance manager, budgets/reports |

---

## Media Servers & Streaming

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Jellyfin](https://jellyfin.org) | ✅ | ⭐⭐⭐⭐⭐ | Fully open Plex alternative |
| [Kodi](https://kodi.tv) | ✅ | ⭐⭐⭐⭐⭐ | Media center software |
| [Navidrome](https://www.navidrome.org) | ✅ | ⭐⭐⭐⭐⭐ | Music streaming server, Spotify-style, Subsonic API |
| [Audiobookshelf](https://www.audiobookshelf.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted audiobook/podcast server |
| [Immich](https://immich.app) | ✅ | ⭐⭐⭐⭐⭐ | Fast-growing self-hosted photo/video backup, Google Photos-style |
| [Nova Video Player](https://github.com/nova-video-player/aos-AVP) | ✅ | ⭐⭐⭐⭐ | Local/network video player (FTP/SMB/NAS), Netflix-style UI, on F-Droid |
| [VLC](https://www.videolan.org) | ✅ | ⭐⭐⭐⭐⭐ | Universal media player, plays nearly everything |
| [Emby](https://emby.media) | ⚠️ | ⭐⭐⭐ | Core open, premium features closed |
| [Plex](https://www.plex.tv) | ❌ | ⭐⭐ | Freemium, widely used but proprietary, requires account |

## Image & Video Editing

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [GIMP](https://www.gimp.org) | ✅ | ⭐⭐⭐⭐⭐ | Photoshop alternative |
| [Krita](https://krita.org) | ✅ | ⭐⭐⭐⭐⭐ | Digital painting focus |
| [Inkscape](https://inkscape.org) | ✅ | ⭐⭐⭐⭐⭐ | Vector graphics, Illustrator alternative |
| [Darktable](https://www.darktable.org) | ✅ | ⭐⭐⭐⭐⭐ | RAW photo processing, Lightroom alternative |
| [RawTherapee](https://rawtherapee.com) | ✅ | ⭐⭐⭐⭐⭐ | RAW photo processing |
| [Kdenlive](https://kdenlive.org) | ✅ | ⭐⭐⭐⭐⭐ | Full-featured non-linear video editor |
| [Shotcut](https://shotcut.org) | ✅ | ⭐⭐⭐⭐⭐ | Cross-platform video editor |
| [Flowblade](https://github.com/jliljebl/flowblade) | ✅ | ⭐⭐⭐⭐⭐ | Linux multitrack non-linear video editor (GPL3) |
| [LosslessCut](https://github.com/mifi/lossless-cut) | ✅ | ⭐⭐⭐⭐⭐ | Cut/trim/merge video without re-encoding or quality loss |
| [MKVToolNix](https://mkvtoolnix.download) | ✅ | ⭐⭐⭐⭐⭐ | Create, edit, split, merge and inspect MKV files without re-encoding |
| [Natron](https://natrongithub.github.io) | ✅ | ⭐⭐⭐⭐⭐ | Node-based compositing, After Effects alternative |
| [Blender](https://www.blender.org) | ✅ | ⭐⭐⭐⭐⭐ | 3D + video editing/compositing |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | ❌ | ⭐⭐⭐ | Freeware, professional-grade, closed source |

## Media Downloaders

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | ✅ | ⭐⭐⭐⭐⭐ | The standard CLI downloader for YouTube and hundreds of other sites, actively maintained |

## Screen Recording & Streaming

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [OBS Studio](https://obsproject.com) | ✅ | ⭐⭐⭐⭐⭐ | The standard for screen recording and live streaming, huge plugin ecosystem |
| [Kooha](https://github.com/SeaDve/Kooha) | ✅ | ⭐⭐⭐⭐⭐ | Simple GNOME/Wayland screen recorder |

## E-Books & Reading

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Calibre](https://calibre-ebook.com) | ✅ | ⭐⭐⭐⭐⭐ | The standard FOSS e-book library manager/converter |
| [Calibre-Web](https://github.com/janeczku/calibre-web) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted web UI for a Calibre library — Kindle/Google Books-style browsing |

---

## News & RSS

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [FreshRSS](https://freshrss.org) | ✅ | ⭐⭐⭐⭐⭐ | Full-featured, self-hosted RSS aggregator |
| [Miniflux](https://miniflux.app) | ✅ | ⭐⭐⭐⭐⭐ | Minimalist, self-hosted RSS reader |
| [Tiny Tiny RSS](https://tt-rss.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted, long-running project |
| [NetNewsWire](https://netnewswire.com) | ✅ | ⭐⭐⭐⭐⭐ | Native Mac/iOS, no tracking |
| [Feeder](https://github.com/spacecowboy/Feeder) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight Android RSS app |
| [Fraidycat](https://fraidyc.at) | ✅ | ⭐⭐⭐⭐⭐ | Browser extension, follows feeds without algorithms |
| [NewsBlur](https://newsblur.com) | ✅ | ⭐⭐⭐⭐ | Social RSS reader, hosted or self-hosted |
| [Feedbro](https://nodetics.com/feedbro/) | ✅ | ⭐⭐⭐⭐ | Browser extension RSS reader |
| [Ground News](https://ground.news) | ❌ | ⭐⭐⭐ | Not FOSS, but shows political bias/framing comparison across outlets — a media-literacy tool rather than a privacy tool per se |

---

## Privacy-Respecting AI

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Ollama](https://ollama.com) | ✅ | ⭐⭐⭐⭐⭐ | Run LLMs locally, easy model management |
| [Jan](https://jan.ai) | ✅ | ⭐⭐⭐⭐⭐ | Local, offline ChatGPT-alternative |
| [GPT4All](https://www.nomic.ai/gpt4all) | ✅ | ⭐⭐⭐⭐⭐ | Local LLM runner with simple UI |
| [LocalAI](https://localai.io) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted OpenAI-API-compatible backend |
| [Kobold.cpp](https://github.com/LostRuins/koboldcpp) | ✅ | ⭐⭐⭐⭐⭐ | Local LLM runner geared toward creative writing/roleplay |
| [Text Generation WebUI (oobabooga)](https://github.com/oobabooga/text-generation-webui) | ✅ | ⭐⭐⭐⭐⭐ | Advanced local LLM interface |
| [Wan2GP](https://github.com/deepbeepmeep/Wan2GP) | ✅ | ⭐⭐⭐⭐⭐ | Local image/video generation |
| [LM Studio](https://lmstudio.ai) | ❌ | ⭐⭐⭐⭐ | Free but closed-source, popular local LLM GUI |

---

## Self-Hosting Platforms & Panels

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [YunoHost](https://yunohost.org) | ✅ | ⭐⭐⭐⭐⭐ | All-in-one self-hosting OS — installs dozens of apps (Nextcloud, email, etc.) with minimal sysadmin knowledge |
| [CasaOS](https://casaos.io) | ✅ | ⭐⭐⭐⭐ | Friendly home-server dashboard, Docker app management |
| [Portainer CE](https://www.portainer.io) | ✅ | ⭐⭐⭐⭐ | Web UI for managing Docker containers |

## Torrenting / P2P Clients

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [qBittorrent](https://www.qbittorrent.org) | ✅ | ⭐⭐⭐⭐⭐ | Most popular FOSS torrent client, no ads |
| [Transmission](https://transmissionbt.com) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight, cross-platform |
| [Deluge](https://deluge-torrent.org) | ✅ | ⭐⭐⭐⭐⭐ | Plugin-extensible |
| [rTorrent / ruTorrent](https://github.com/rakshasa/rtorrent) | ✅ | ⭐⭐⭐⭐⭐ | Terminal-based + web UI, great for headless servers |
| [Tribler](https://www.tribler.org) | ✅ | ⭐⭐⭐⭐⭐ | Built-in Tor-like anonymity layer |
| [BiglyBT](https://www.biglybt.com) | ✅ | ⭐⭐⭐⭐ | Vuze fork, feature-rich |

## Windows Compatibility on Linux

| App | FOSS | Note |
|---|---|---|
| [Wine](https://www.winehq.org) | ✅ | Run Windows executables directly on Linux, no VM |
| [Proton (Valve)](https://github.com/ValveSoftware/Proton) | ✅ | Wine-based compatibility layer, powers Steam Deck/Steam on Linux gaming |
| [Bottles](https://usebottles.com) | ✅ | Friendly Wine "prefix" manager with GUI |
| [WinPodX](https://github.com/kernalix7/winpodx) | ✅ | Runs a real Windows instance in a Podman/Docker container and shows each app as a native Linux window via FreeRDP RemoteApp — useful when Wine compatibility isn't enough |

---

## Presence Detection

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [ESPectre](https://github.com/francescopace/espectre) | ✅ | ⭐⭐⭐⭐⭐ | Motion/presence detection using WiFi CSI on ESP32 — no camera or microphone needed, Home Assistant integration |

## Weather

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Breezy Weather](https://github.com/breezy-weather/breezy-weather) | ✅ | ⭐⭐⭐⭐⭐ | FOSS Android weather app, no account, no tracking, multiple data source options |

---

## Curated Meta-Lists

Other big lists worth cross-referencing for anything still missing here:

| List | Note |
|---|---|
| [awesome-privacy (Lissy93)](https://github.com/Lissy93/awesome-privacy) | One of the largest general privacy-alternatives lists |
| [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | The largest self-hosted software list, organized by category |
| [deploy-your-own-saas](https://github.com/Atsika/deploy-your-own-saas) | Self-hosted alternatives mapped directly to specific SaaS products |
| [PrivacyGuides.org](https://www.privacyguides.org) | Curated, actively-maintained recommendations with rationale per pick |

---

*This list is a work in progress — contributions and corrections welcome.*
