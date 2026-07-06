# 🛡️ Awesome FOSS & Privacy Alternatives

A massive, curated list of Free and Open Source Software (FOSS) and privacy-respecting alternatives to mainstream, tracking-heavy software — combining and expanding on the biggest lists in this space (awesome-privacy, awesome-selfhosted, and more).

> ⭐ Star this repo if you find it useful. Contributions welcome!

---

## 📚 Categories

- [Android App Stores](#android-app-stores)
- [Authenticator / 2FA Apps](#authenticator--2fa-apps)
- [Browsers](#browsers)
- [Cloud Storage & File Sync](#cloud-storage--file-sync)
- [DNS & Ad-Blocking](#dns--ad-blocking)
- [Email](#email)
- [Google Apps Alternatives](#google-apps-alternatives)
- [Image & Video Editing](#image--video-editing)
- [Media Servers & Streaming](#media-servers--streaming)
- [Mobile ROMs](#mobile-roms)
- [News & RSS](#news--rss)
- [Notes & Productivity](#notes--productivity)
- [Office Suites](#office-suites)
- [Operating Systems](#operating-systems)
- [Password Managers](#password-managers)
- [Privacy-Respecting AI](#privacy-respecting-ai)
- [Search Engines](#search-engines)
- [Social Media & Mainstream App Alternatives](#social-media--mainstream-app-alternatives)
- [Torrenting / P2P Clients](#torrenting--p2p-clients)
- [VPN & Networking](#vpn--networking)

---

## Android App Stores

| App | Type | Note |
|---|---|---|
| [F-Droid](https://f-droid.org) | FOSS | The original catalogue of FOSS Android apps |
| [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore) | FOSS | Anonymous frontend to the real Google Play Store |
| [Accrescent](https://accrescent.app) | FOSS | New app store focused on security, privacy & usability |
| [Obtainium](https://github.com/ImranR98/Obtainium) | FOSS | Installs/updates apps directly from GitHub/GitLab releases |
| [Droid-ify](https://github.com/Droid-ify/client) | FOSS | Lightweight, modern F-Droid client |
| [IzzyOnDroid repo](https://apt.izzysoft.de/fdroid/) | FOSS | Extra F-Droid repository with many more apps |
| [Neo Store](https://github.com/NeoApplications/Neo-Store) | FOSS | Modern F-Droid client fork |

---

## Authenticator / 2FA Apps

| App | Type | Note |
|---|---|---|
| [Aegis Authenticator](https://getaegis.app) | FOSS (Android) | Encrypted vault, backup/import support |
| [FreeOTP](https://freeotp.github.io) | FOSS | Simple, Red Hat-backed |
| [andOTP](https://github.com/andOTP/andOTP) | FOSS (archived, still usable) | Encrypted backups |
| [Tofu Authenticator](https://github.com/pluja/tofu) | FOSS (iOS) | Clean, minimal |
| [Ente Auth](https://ente.io/auth) | FOSS, E2E encrypted sync | Cross-platform, cloud backup option |

---

## Browsers

### Desktop
| App | Note |
|---|---|
| [Firefox](https://www.mozilla.org/firefox) | Main independent browser, Gecko engine |
| [LibreWolf](https://librewolf.net) | Hardened Firefox fork, no telemetry |
| [Mullvad Browser](https://mullvad.net/en/browser) | Built with Tor Project, strong anti-fingerprinting |
| [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | Chromium without Google services |
| [Tor Browser](https://www.torproject.org) | Anonymity via the Tor network |
| [Brave](https://brave.com) | Chromium-based, built-in ad/tracker blocking |

### Mobile
| App | Note |
|---|---|
| [Vanadium](https://github.com/GrapheneOS/Vanadium) | Default hardened browser on GrapheneOS |
| [Firefox Focus](https://www.mozilla.org/firefox/browsers/mobile/focus/) | Privacy-first, auto-clears history |
| [Firefox (mobile)](https://www.mozilla.org/firefox/browsers/mobile/) | Full version with extension support |
| [Mull](https://github.com/gordinskoyroman/mull-fenix) | LibreWolf-equivalent for Android, via F-Droid |
| [Bromite](https://github.com/bromite/bromite) | Ungoogled Chromium for Android (check maintenance status) |

---

## Cloud Storage & File Sync

| App | Type | Note |
|---|---|---|
| [Nextcloud](https://nextcloud.com) | FOSS, self-hostable | Full suite: files, calendar, contacts, office |
| [Seafile](https://www.seafile.com) | FOSS, self-hostable | Fast sync, good for large files |
| [Syncthing](https://syncthing.net) | FOSS | Peer-to-peer sync, no central server |
| [CryptPad](https://cryptpad.org) | FOSS, self-hostable | Zero-knowledge encrypted collaboration |
| [ownCloud](https://owncloud.com) | FOSS, self-hostable | Nextcloud's predecessor/alternative |

---

## DNS & Ad-Blocking

| App | Type | Note |
|---|---|---|
| [Pi-hole](https://pi-hole.net) | FOSS, self-hostable | Network-wide ad blocking via DNS |
| [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) | FOSS, self-hostable | Pi-hole alternative, easier setup |
| [NextDNS](https://nextdns.io) | Freemium, privacy-respecting | Cloud DNS filtering, cross-device |

---

## Email

| App | Type | Note |
|---|---|---|
| [Tutanota (Tuta)](https://tuta.com) | FOSS, E2E encrypted | German-based |
| [Proton Mail](https://proton.me/mail) | FOSS clients, E2E encrypted | Swiss-based |
| [Mailbox.org](https://mailbox.org) | Not FOSS, privacy-respecting | German, PGP support |
| [Mailcow](https://mailcow.email) | FOSS, self-hostable | Full mail server stack |
| [Mail-in-a-Box](https://mailinabox.email) | FOSS, self-hostable | Simplified self-hosted mail server |

---

## Google Apps Alternatives

> Note: some of these are components rather than 1-to-1 replacements — noted where relevant.

| Google App | Alternative(s) | Note |
|---|---|---|
| Gmail | [Tuta](https://tuta.com), [Proton Mail](https://proton.me/mail) | See Email section |
| Google Drive | [Nextcloud](https://nextcloud.com), [Seafile](https://www.seafile.com), [Syncthing](https://syncthing.net) | See Cloud Storage section |
| Google Docs/Sheets/Slides | [OnlyOffice](https://www.onlyoffice.com), [Collabora Online](https://www.collaboraoffice.com/collabora-online/), [CryptPad](https://cryptpad.org) | Cloud-editable, self-hostable |
| Google Calendar | [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar), [Proton Calendar](https://proton.me/calendar), [Tuta Calendar](https://tuta.com/calendar) | CalDAV-based options available |
| Google Photos | [Ente Photos](https://ente.io), [PhotoPrism](https://www.photoprism.app), [Nextcloud Memories](https://memories.gallery) | Ente is closest 1:1 with mobile apps |
| Google Play Store | See [Android App Stores](#android-app-stores) | — |
| Gboard | [FlorisBoard](https://florisboard.org), [OpenBoard](https://github.com/openboard-team/openboard), [AnySoftKeyboard](https://anysoftkeyboard.github.io), [Simple Keyboard](https://github.com/rkkr/simple-keyboard) | No internet permission needed for any of these |
| Google Assistant | [Home Assistant Voice / local voice pipelines](https://www.home-assistant.io/voice_control/) | Self-hosted, local processing (relevant given your HA setup) |
| Google Translate | [LibreTranslate](https://libretranslate.com) | Fully open translation API/app |
| Google Meet | [Jitsi Meet](https://meet.jit.si), [Element Call](https://element.io/call) | No account needed for Jitsi |
| Google Analytics | [Matomo](https://matomo.org), [Plausible](https://plausible.io), [Umami](https://umami.is) | Self-hostable web analytics |
| Google Lens | [firefox-translator](https://github.com/DavidVentura/firefox-translator) (OCR+translate overlay), Tesseract-based OCR apps, [Binary Eye](https://github.com/markusfisch/BinaryEye) (QR/barcode) | ⚠️ No full 1:1 FOSS replacement exists — Lens combines OCR, translation, object/landmark ID, and QR scanning; these tools cover individual pieces only |
| Google Maps | [OpenStreetMap](https://www.openstreetmap.org), [OrganicMaps](https://organicmaps.app), [Magic Earth](https://www.magicearth.com) | OSM-based, offline capable |

---

## Image & Video Editing

| App | Type | Note |
|---|---|---|
| [GIMP](https://www.gimp.org) | FOSS | Photoshop alternative |
| [Krita](https://krita.org) | FOSS | Digital painting focus |
| [Inkscape](https://inkscape.org) | FOSS | Vector graphics, Illustrator alternative |
| [Kdenlive](https://kdenlive.org) | FOSS | Video editing |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | Freeware (not FOSS) | Professional-grade, often listed alongside FOSS tools |
| [Shotcut](https://shotcut.org) | FOSS | Cross-platform video editor |

---

## Media Servers & Streaming

| App | Type | Note |
|---|---|---|
| [Jellyfin](https://jellyfin.org) | FOSS, self-hostable | Fully open Plex alternative — relevant given your Shield Pro setup |
| [Plex](https://www.plex.tv) | Freemium, not FOSS | Widely used but proprietary |
| [Kodi](https://kodi.tv) | FOSS | Media center software |
| [Navidrome](https://www.navidrome.org) | FOSS, self-hostable | Music streaming server, Spotify-style |

---

## Mobile ROMs

| ROM | Type | Note |
|---|---|---|
| [GrapheneOS](https://grapheneos.org) | FOSS | Security & privacy hardened, Pixel-only |
| [LineageOS](https://lineageos.org) | FOSS | Broadest device support |
| [CalyxOS](https://calyxos.org) | FOSS | Privacy-focused, includes microG option |
| [DivestOS](https://divestos.org) | FOSS | LineageOS-based, extended device support & security patches |
| [/e/OS](https://e.foundation) | FOSS | De-googled, consumer-friendly |

---

## News & RSS

| App | Type | Note |
|---|---|---|
| [FreshRSS](https://freshrss.org) | FOSS, self-hostable | Full-featured RSS aggregator |
| [Miniflux](https://miniflux.app) | FOSS, self-hostable | Minimalist RSS reader |
| [NewsBlur](https://newsblur.com) | Open source, hosted or self-hosted | Social RSS reader |
| [Feedbro](https://nodetics.com/feedbro/) | FOSS (browser extension) | RSS reader in-browser |
| [NetNewsWire](https://netnewswire.com) | FOSS (Mac/iOS) | Native feel, no tracking |

---

## Notes & Productivity

| App | Type | Note |
|---|---|---|
| [Joplin](https://joplinapp.org) | FOSS | Evernote alternative, E2E encrypted sync |
| [Standard Notes](https://standardnotes.com) | FOSS, E2E encrypted | Simple, extensible |
| [Logseq](https://logseq.com) | FOSS | Privacy-first knowledge management |
| [AFFiNE](https://affine.pro) | FOSS | Notion/Miro-style all-in-one |
| [Notesnook](https://notesnook.com) | FOSS, E2E encrypted | Evernote alternative |

---

## Office Suites

| App | Type | Note |
|---|---|---|
| [LibreOffice](https://www.libreoffice.org) | FOSS | Standard offline suite |
| [OnlyOffice](https://www.onlyoffice.com) | FOSS, self-hostable | Best MS Office file compatibility |
| [Collabora Online](https://www.collaboraoffice.com/collabora-online/) | FOSS, self-hostable | LibreOffice-based, integrates with Nextcloud |

---

## Operating Systems

### Anonymity-Focused
| OS | Note |
|---|---|
| [Tails](https://tails.net) | Amnesic, routes everything through Tor, leaves no trace |
| [Whonix](https://www.whonix.org) | Gateway + Workstation VM setup, all traffic via Tor |
| [Kicksecure](https://www.kicksecure.com) | Hardened Debian-based OS, foundation for Whonix |

### Investigation / Pentesting
| OS | Note |
|---|---|
| [Kali Linux](https://www.kali.org) | Most well-known pentesting distro |
| [Parrot OS](https://parrotsec.org) | Security + privacy focus, lighter than Kali |
| [BlackArch](https://blackarch.org) | Arch-based, huge tool repository |

### Gaming
| OS | Note |
|---|---|
| [Bazzite](https://bazzite.gg) | SteamOS-like, immutable, great for handhelds/desktop |
| [Nobara](https://nobaraproject.org) | Fedora-based, gaming-optimized patches |
| [SteamOS](https://store.steampowered.com/steamos) | Valve's own, Steam Deck's OS |

### Windows-Refugee Friendly
| OS | Note |
|---|---|
| [Linux Mint](https://linuxmint.com) | Most beginner-friendly, familiar UI |
| [Zorin OS](https://zorin.com/os) | Windows-like layout out of the box |
| [Pop!_OS](https://pop.system76.com) | Clean, good for both beginners and power users |

### Debloated Windows
| Tool | Note |
|---|---|
| [Tiny11](https://github.com/ntdevlabs/tiny11builder) | Stripped-down Windows 11 image |
| [AtlasOS](https://atlasos.net) | Performance/privacy-focused Windows tweak set |
| [ReviOS](https://revi.cc) | Debloated Windows image |

### General Hardened / Daily-Driver
| OS | Note |
|---|---|
| [Qubes OS](https://www.qubes-os.org) | Compartmentalized security via VMs |
| [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) | Immutable desktop, atomic updates |

---

## Password Managers

| App | Type | Note |
|---|---|---|
| [Bitwarden](https://bitwarden.com) | FOSS | Full-featured, cloud or self-hosted |
| [KeePassXC](https://keepassxc.org) | FOSS | Fully offline, local vault |
| [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | FOSS | Lightweight Bitwarden-compatible server for self-hosting |
| [Password Safe](https://pwsafe.org) | FOSS | Bruce Schneier-designed, offline |
| [PassBolt](https://www.passbolt.com) | FOSS, self-hostable | Team-oriented, OpenPGP-based |

---

## Privacy-Respecting AI

| App | Type | Note |
|---|---|---|
| [Ollama](https://ollama.com) | FOSS | Run LLMs locally, easy model management |
| [LM Studio](https://lmstudio.ai) | Freeware (not FOSS) | Local LLM GUI, often paired with Ollama-alike tools |
| [Jan](https://jan.ai) | FOSS | Local, offline ChatGPT-alternative |
| [GPT4All](https://www.nomic.ai/gpt4all) | FOSS | Local LLM runner with simple UI |
| [Wan2GP](https://github.com/deepbeepmeep/Wan2GP) | FOSS | Local image/video generation (you already run this) |
| [Text Generation WebUI (oobabooga)](https://github.com/oobabooga/text-generation-webui) | FOSS | Advanced local LLM interface |

---

## Search Engines

| App | Type | Note |
|---|---|---|
| [SearXNG](https://searxng.org) | FOSS, self-hostable | Metasearch engine, combines results from multiple sources |
| [YaCy](https://yacy.net) | FOSS, self-hostable | Peer-to-peer search engine with its own crawler — build your own index |
| [Mojeek](https://www.mojeek.com) | Independent crawler, not FOSS | One of the few with its own index (no Bing/Google data) |
| [Brave Search](https://search.brave.com) | Not FOSS, own index | Independent index, no tracking |
| [DuckDuckGo](https://duckduckgo.com) | Not FOSS, privacy-oriented | Uses Bing data under the hood |
| [Startpage](https://www.startpage.com) | Not FOSS, privacy proxy | Anonymized Google results |
| [Ecosia](https://www.ecosia.org) | Not FOSS | Tree-planting initiative, uses Bing data |
| [Yandex](https://yandex.com) | Not private | Least censored of the major search engines, Russian-based |

---

## Social Media & Mainstream App Alternatives

### Facebook
| Option | Type | Note |
|---|---|---|
| [Diaspora](https://diasporafoundation.org) | FOSS, federated | Decentralized, no ads |
| [Friendica](https://friendi.ca) | FOSS, federated | Connects with Mastodon/Diaspora/other networks |
| [Minds](https://www.minds.com) | Open source | Crypto-rewards social network |

### Twitter / X
| Option | Type | Note |
|---|---|---|
| [Mastodon](https://joinmastodon.org) | FOSS, federated | Biggest decentralized Twitter alternative |
| [Nitter](https://github.com/zedeus/nitter) | FOSS, self-hostable | Privacy frontend (⚠️ many public instances currently unstable due to API changes) |
| [Misskey](https://misskey-hub.net) | FOSS, federated | Twitter-style Fediverse server (you already run one) |

### Instagram
| Option | Type | Note |
|---|---|---|
| [Pixelfed](https://pixelfed.org) | FOSS, federated | Photo-sharing Fediverse alternative |
| [Barinsta](https://github.com/austinhuang0131/barinsta) | FOSS (Android) | Privacy-friendly Instagram client |

### YouTube
| Option | Type | Note |
|---|---|---|
| [Invidious](https://invidious.io) | FOSS, self-hostable | Privacy frontend, no ads/tracking |
| [Piped](https://piped.video) | FOSS, self-hostable | Similar to Invidious, actively maintained |
| [FreeTube](https://freetubeapp.io) | FOSS (desktop) | Private YouTube client |
| [NewPipe](https://newpipe.net) | FOSS (Android) | Lightweight, background play |
| [PeerTube](https://joinpeertube.org) | FOSS, federated | Full decentralized video-hosting platform |

### WhatsApp
| Option | Type | Note |
|---|---|---|
| [Signal](https://signal.org) | FOSS | Gold standard, E2E encrypted |
| [Session](https://getsession.org) | FOSS | No phone number required |
| [Element (Matrix)](https://element.io) | FOSS, federated | Decentralized, self-hostable |

### Reddit
| Option | Type | Note |
|---|---|---|
| [Lemmy](https://join-lemmy.org) | FOSS, federated | Full Reddit-style alternative platform |
| [Redlib](https://github.com/redlib-org/redlib) | FOSS, self-hostable | Privacy frontend (successor to discontinued Libreddit) |

### Discord
| Option | Type | Note |
|---|---|---|
| [Element (Matrix)](https://element.io) | FOSS, federated | Full chat/voice alternative |
| [Revolt](https://revolt.chat) | FOSS | Discord-like UI, actively growing |

---

## Torrenting / P2P Clients

| App | Type | Note |
|---|---|---|
| [qBittorrent](https://www.qbittorrent.org) | FOSS | Most popular FOSS torrent client, no ads |
| [Transmission](https://transmissionbt.com) | FOSS | Lightweight, cross-platform |
| [Deluge](https://deluge-torrent.org) | FOSS | Plugin-extensible |

---

## VPN & Networking

| App | Type | Note |
|---|---|---|
| [Mullvad](https://mullvad.net) | Not FOSS server-side, FOSS clients | No account info required, cash payments accepted |
| [ProtonVPN](https://protonvpn.com) | FOSS clients | Swiss-based |
| [IVPN](https://www.ivpn.net) | FOSS clients | Strong privacy stance |
| [WireGuard](https://www.wireguard.com) | FOSS | Underlying modern VPN protocol used by most above |
| [PIA (Private Internet Access)](https://www.privateinternetaccess.com) | FOSS clients | Long-standing provider, no-logs audited |

---

*This list is a work in progress — contributions and corrections welcome.*
