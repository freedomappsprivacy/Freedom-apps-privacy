<div align="center">

# 🛡️ Awesome FOSS & Privacy Alternatives

**The most complete list of Free & Open Source (FOSS) and privacy-respecting alternatives to mainstream software.**

Curated and expanded from the biggest lists in the space.

</div>

---

## 🔑 Legend

| Symbol | Meaning |
|---|---|
| **FOSS** ✅ | Fully open source |
| **FOSS** ⚠️ | Partially open (e.g. open clients, closed server/backend) |
| **FOSS** ❌ | Closed source, but privacy-relevant / notable alternative |
| **Privacy** ⭐–⭐⭐⭐⭐⭐ | How privacy-respecting by design & policy (1–5) |
| **Platform** | `Lin` Linux · `Win` Windows · `Mac` macOS · `And` Android · `iOS` · `Web` · `Self` self-hosted · `Ext` browser extension |

> Focus is on **Linux / cross-platform**; select Windows-only tools (e.g. debloat utilities) are marked. Star ⭐ this repo if you find it useful — contributions welcome!

---

## 📚 Table of Contents

<table>
<tr><td valign="top">

**🌐 Web & Search**
- [Browsers — Desktop](#browsers--desktop)
- [Browsers — Mobile](#browsers--mobile)
- [Browser Extensions](#browser-extensions)
- [Search Engines](#search-engines)

**💬 Communication**
- [Encrypted Messaging](#encrypted-messaging)
- [P2P / Serverless Messaging](#p2p--serverless-messaging)
- [Team Collaboration](#team-collaboration)
- [Video Calls & VOIP](#video-calls--voip)
- [Email Providers](#email-providers)
- [Email Clients](#email-clients)
- [Email Aliasing & Forwarding](#email-aliasing--forwarding)
- [Virtual Phone Numbers](#virtual-phone-numbers)

**👥 Social & Fediverse**
- [Mainstream App Alternatives](#mainstream-app-alternatives)
- [Fediverse Platforms](#fediverse-platforms)

**🔵 [Google Apps Alternatives](#google-apps-alternatives)**

</td><td valign="top">

**☁️ Cloud & Sync**
- [Cloud Storage & File Sync](#cloud-storage--file-sync)
- [Backup Tools](#backup-tools)
- [Anonymous File Sharing](#anonymous-file-sharing)

**🔐 Security & Encryption**
- [Password Managers](#password-managers)
- [2FA / Authenticator Apps](#2fa--authenticator-apps)
- [File & Disk Encryption](#file--disk-encryption)
- [Metadata Removal](#metadata-removal)
- [Secure Data Wiping](#secure-data-wiping)
- [Antivirus & Scanning](#antivirus--scanning)
- [Online Privacy Test Tools](#online-privacy-test-tools)

**🌍 Network & Anonymity**
- [VPN & Mesh Networking](#vpn--mesh-networking)
- [DNS & Ad-Blocking](#dns--ad-blocking)
- [Router Firmware & Firewalls](#router-firmware--firewalls)
- [Network Monitoring](#network-monitoring)

**💻 Operating Systems**
- [Anonymity-Focused](#anonymity-focused)
- [Pentesting / Investigation](#pentesting--investigation)
- [Gaming](#gaming)
- [Beginner / Windows-Refugee](#beginner--windows-refugee)
- [Mainstream Distros](#mainstream-distros)
- [Minimal / Low-RAM](#minimal--low-ram)
- [Immutable / Hardened](#immutable--hardened)
- [Debloated Windows](#debloated-windows)
- [Boot & USB Tools](#boot--usb-tools)

</td><td valign="top">

**📱 Mobile & Android**
- [Android App Stores](#android-app-stores)
- [Mobile ROMs](#mobile-roms)
- [Fossify Suite](#fossify-suite)
- [Android Essentials & PIM](#android-essentials--pim)
- [Mobile Privacy & Firewall](#mobile-privacy--firewall)
- [Android Runtimes & Virtualization](#android-runtimes--virtualization)

**🗂️ Productivity**
- [Notes & Knowledge](#notes--knowledge)
- [Office Suites](#office-suites)
- [Project & Task Management](#project--task-management)
- [PDF Tools](#pdf-tools)
- [Personal Finance](#personal-finance)

**🎬 Media**
- [Media Servers & Streaming](#media-servers--streaming)
- [Image & Video Editing](#image--video-editing)
- [Media Downloaders](#media-downloaders)
- [Screen Recording & Streaming](#screen-recording--streaming)
- [E-Books & Reading](#e-books--reading)
- [Maps & Navigation](#maps--navigation)

**📰 [News & RSS](#news--rss)**

**🤖 [Privacy-Respecting AI](#privacy-respecting-ai)**

**🖥️ System & Self-Hosting**
- [Self-Hosting Platforms](#self-hosting-platforms)
- [Torrenting / P2P](#torrenting--p2p)
- [Windows Compatibility on Linux](#windows-compatibility-on-linux)

**🏠 Niche & Smart Home**
- [Presence Detection](#presence-detection)
- [Weather](#weather)

**📋 [Curated Meta-Lists](#curated-meta-lists)**

</td></tr>
</table>

---

## Featured Picks

The single best pick(s) per everyday use case, if you just want to get started:

| Use Case | Top Picks |
|---|---|
| 🌐 Desktop browser | **LibreWolf** · Mullvad Browser · Tor Browser |
| 📱 Mobile browser | **Mull** · Tor Browser (Android) · Vanadium |
| 💬 Messaging | **Signal** · SimpleX Chat · Molly |
| 📧 Email | **Tuta** · Proton Mail |
| ☁️ Cloud storage | **Nextcloud** · Syncthing · CryptPad |
| 🔑 Passwords | **Bitwarden** · KeePassXC · Vaultwarden |
| 🔐 Encryption | **VeraCrypt** · Cryptomator · age |
| 🌍 VPN | **Mullvad** · Proton VPN · IVPN |
| 🔎 Search | **SearXNG** · Brave Search · Mojeek |
| 🛡️ DNS filtering | **NextDNS** · Pi-hole · AdGuard Home |
| 📝 Notes | **Joplin** · Standard Notes · Logseq |
| 🤖 Local AI | **Ollama** · Jan · GPT4All |
| 🎬 Media server | **Jellyfin** · Immich |
| ✂️ Video editing | **Kdenlive** · LosslessCut · Shotcut |
| 📱 Android stock-app suite | **Fossify Suite** |

---

# 🌐 Web & Search

## Browsers — Desktop

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [LibreWolf](https://librewolf.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Hardened Firefox fork, uBlock bundled, no telemetry |
| [Mullvad Browser](https://mullvad.net/en/browser) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Tor Browser's anti-fingerprinting, built for VPN use |
| [Tor Browser](https://www.torproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Anonymity via the Tor network |
| [Firefox](https://www.mozilla.org/firefox) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Independent Gecko engine; harden with [arkenfox](https://github.com/arkenfox/user.js) |
| [Brave](https://brave.com) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Chromium-based, built-in ad/tracker blocking, Tor tabs |
| [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Chromium with all Google services removed |
| [Waterfox](https://www.waterfox.net) | ✅ | ⭐⭐⭐ | Lin/Win/Mac | Firefox fork, telemetry-free |
| [Pale Moon](https://www.palemoon.org) | ✅ | ⭐⭐⭐ | Lin/Win | Independent Goanna-engine fork, lightweight |
| [GNU IceCat](https://www.gnu.org/software/gnuzilla/) | ✅ | ⭐⭐⭐⭐ | Lin | GNU's fully-free Firefox derivative |
| [GNOME Web (Epiphany)](https://apps.gnome.org/Epiphany/) | ✅ | ⭐⭐⭐ | Lin | WebKit-based, minimal, GNOME default |
| [Falkon](https://www.falkon.org) | ✅ | ⭐⭐⭐ | Lin/Win | QtWebEngine-based, KDE default |
| [Qutebrowser](https://qutebrowser.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Keyboard-driven, vim-style |

## Browsers — Mobile

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Vanadium](https://github.com/GrapheneOS/Vanadium) | ✅ | ⭐⭐⭐⭐⭐ | And | Hardened Chromium, default on GrapheneOS |
| [Tor Browser for Android](https://www.torproject.org/download/#android) | ✅ | ⭐⭐⭐⭐⭐ | And | Official Tor Browser |
| [Mull](https://gitlab.com/divested-mobile/mull-fenix) | ✅ | ⭐⭐⭐⭐⭐ | And | LibreWolf-equivalent for Android (F-Droid) |
| [Cromite](https://www.cromite.org) | ✅ | ⭐⭐⭐⭐ | And | Actively-maintained Bromite successor, ad-blocking |
| [Brave (mobile)](https://brave.com/mobile/) | ✅ | ⭐⭐⭐⭐ | And/iOS | Built-in ad/tracker blocking |
| [Firefox Focus](https://www.mozilla.org/firefox/browsers/mobile/focus/) | ✅ | ⭐⭐⭐⭐ | And/iOS | Privacy-first, auto-clears history |
| [Onion Browser](https://onionbrowser.com) | ✅ | ⭐⭐⭐⭐⭐ | iOS | Tor-based, the iOS Tor option |

## Browser Extensions

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [uBlock Origin](https://ublockorigin.com) | ✅ | ⭐⭐⭐⭐⭐ | The essential ad/tracker/malware blocker |
| [Privacy Badger](https://privacybadger.org) | ✅ | ⭐⭐⭐⭐⭐ | EFF's auto-learning tracker blocker |
| [ClearURLs](https://github.com/ClearURLs/Addon) | ✅ | ⭐⭐⭐⭐⭐ | Strips tracking parameters from URLs |
| [Decentraleyes](https://decentraleyes.org) | ✅ | ⭐⭐⭐⭐ | Serves CDN libraries locally, blocks CDN tracking |
| [LocalCDN](https://www.localcdn.org) | ✅ | ⭐⭐⭐⭐ | Actively-maintained Decentraleyes fork |
| [Firefox Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/) | ✅ | ⭐⭐⭐⭐⭐ | Isolate cookies/identities per container tab |
| [Canvas Blocker](https://github.com/kkapsner/CanvasBlocker) | ✅ | ⭐⭐⭐⭐ | Blocks canvas-based fingerprinting |
| [User-Agent Switcher](https://github.com/ray-lothian/UserAgent-Switcher) | ✅ | ⭐⭐⭐ | Spoof/rotate your browser user-agent |
| [Snowflake](https://snowflake.torproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Run a Tor bridge in your browser to help censored users |
| [Vimium](https://github.com/philc/vimium) | ✅ | ⭐⭐⭐⭐ | Keyboard-only browsing (bonus, not privacy-specific) |

> ⚠️ Fewer extensions = smaller fingerprint. A hardened browser + uBlock Origin covers most needs; don't over-install.

## Search Engines

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [SearXNG](https://searxng.org) | ✅ | ⭐⭐⭐⭐⭐ | Self/Web | Metasearch aggregator, self-hostable; [public instances](https://searx.space) |
| [YaCy](https://yacy.net) | ✅ | ⭐⭐⭐⭐⭐ | Self | P2P engine with its own crawler — build your own index |
| [Brave Search](https://search.brave.com) | ❌ | ⭐⭐⭐⭐ | Web | Independent index, no tracking |
| [Mojeek](https://www.mojeek.com) | ❌ | ⭐⭐⭐⭐ | Web | Independent British crawler, own index |
| [DuckDuckGo](https://duckduckgo.com) | ❌ | ⭐⭐⭐ | Web | Privacy-oriented, Bing-backed, has .onion |
| [Qwant](https://www.qwant.com) | ❌ | ⭐⭐⭐ | Web | French, no tracking/cookies, Bing-backed |
| [Startpage](https://www.startpage.com) | ❌ | ⭐⭐⭐ | Web | Anonymized Google results (Dutch) |
| [MetaGer](https://metager.org) | ⚠️ | ⭐⭐⭐⭐ | Web | German non-profit metasearch, has .onion |
| [Ecosia](https://www.ecosia.org) | ❌ | ⭐⭐⭐ | Web | Tree-planting, Bing-backed |
| [Yandex](https://yandex.com) | ❌ | ⭐ | Web | Least-censored major engine, Russian, **not private** |

---

# 💬 Communication

## Encrypted Messaging

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Signal](https://signal.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Gold standard, E2EE by default, minimal metadata |
| [Molly](https://molly.im) | ✅ | ⭐⭐⭐⭐⭐ | And | Hardened Signal fork (encrypted DB, panic-wipe) |
| [SimpleX Chat](https://simplex.chat) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | No phone/username/ID at all — best metadata privacy |
| [Session](https://getsession.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | No phone number, onion-routed |
| [Element (Matrix)](https://element.io) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Federated, self-hostable, E2EE |
| [XMPP](https://xmpp.org) (Conversations/Gajim) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Open federated standard, OMEMO encryption |
| [Threema](https://threema.ch) | ⚠️ | ⭐⭐⭐⭐ | And/iOS/Desktop | Anonymous ID, Swiss, paid |
| [Delta Chat](https://delta.chat) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Chat over any email account, no new account needed |

> ⚠️ Avoid closed-source "secure" messengers (Telegram's default chats are **not** E2EE; Wickr owned by Amazon). If code can't be inspected, encryption claims can't be verified.

## P2P / Serverless Messaging

No central server to raid, subpoena or shut down.

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Briar](https://briarproject.org) | ✅ | ⭐⭐⭐⭐⭐ | And | Tor/WiFi/Bluetooth mesh, works offline, forums |
| [Cwtch](https://cwtch.im) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And | Metadata-resistant, Tor onion services |
| [Jami](https://jami.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Fully distributed P2P, no servers, video+chat |
| [Tox](https://tox.chat) (qTox) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac/And | Encrypted distributed chat network |
| [Ricochet Refresh](https://www.ricochetrefresh.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Tor-based, no metadata, no servers |
| [RetroShare](https://retroshare.cc) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | F2F encrypted network, chat/mail/files/forums |

## Team Collaboration

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Element (Matrix)](https://element.io) | ✅ | ⭐⭐⭐⭐ | Self/all | Slack/Discord alt, federated, self-hostable |
| [Rocket.Chat](https://rocket.chat) | ✅ | ⭐⭐⭐⭐ | Self | Feature-rich, Slack-like, self-hosted |
| [Mattermost](https://mattermost.com) | ✅ | ⭐⭐⭐⭐ | Self | Slack alternative, great for dev teams |
| [Revolt](https://revolt.chat) | ✅ | ⭐⭐⭐⭐ | Web/Self | Discord-like UI, actively growing |
| [Nextcloud Talk](https://nextcloud.com/talk/) | ✅ | ⭐⭐⭐⭐⭐ | Self | Chat/video/screenshare bundled with Nextcloud |

## Video Calls & VOIP

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Jitsi Meet](https://meet.jit.si) | ✅ | ⭐⭐⭐⭐⭐ | Web/Self | No account needed, E2EE option |
| [Jami](https://jami.net) | ✅ | ⭐⭐⭐⭐⭐ | all | P2P video/voice/screenshare |
| [Element Call](https://element.io/call) | ✅ | ⭐⭐⭐⭐ | Web/all | Matrix-based group calls |
| [Mumble](https://www.mumble.info) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Low-latency voice chat, self-hostable |
| [Linphone](https://www.linphone.org) | ✅ | ⭐⭐⭐⭐ | all | SIP-based E2EE audio/video/IM |

## Email Providers

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Tuta](https://tuta.com) | ✅ | ⭐⭐⭐⭐⭐ | Web/And/iOS | E2EE, German, quantum-safe crypto, anon signup |
| [Proton Mail](https://proton.me/mail) | ⚠️ | ⭐⭐⭐⭐⭐ | Web/And/iOS/Bridge | FOSS clients, Swiss, .onion, anon payment |
| [Mailbox.org](https://mailbox.org) | ❌ | ⭐⭐⭐⭐ | Web | German, eco-friendly, OpenPGP, custom domains |
| [Mailfence](https://mailfence.com) | ❌ | ⭐⭐⭐⭐ | Web/And/iOS | OpenPGP, bundled calendar/contacts |
| [Posteo](https://posteo.de) | ❌ | ⭐⭐⭐⭐ | Web | German, anonymous payment, eco-friendly |
| [StartMail](https://www.startmail.com) | ❌ | ⭐⭐⭐⭐ | Web | Dutch, from the Startpage team |
| [Disroot](https://disroot.org) | ✅ | ⭐⭐⭐⭐ | Web | Non-profit collective, no logs |
| [AtomicMail](https://atomicmail.io) | ❌ | ⭐⭐⭐⭐ | Web | No phone verification needed |
| [Forward Email](https://forwardemail.net) | ✅ | ⭐⭐⭐⭐⭐ | Web/Self | 100% open, quantum-safe, self-hostable |
| [Mailcow](https://mailcow.email) | ✅ | ⭐⭐⭐⭐⭐ | Self | Full self-hosted mail server stack (Docker) |
| [Mail-in-a-Box](https://mailinabox.email) | ✅ | ⭐⭐⭐⭐⭐ | Self | Simplified self-hosted mail server |

## Email Clients

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Thunderbird](https://www.thunderbird.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard FOSS desktop mail client, built-in encryption |
| [Betterbird](https://www.betterbird.eu) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Thunderbird fork with extra features/fixes |
| [K-9 Mail / Thunderbird Android](https://k9mail.app) | ✅ | ⭐⭐⭐⭐⭐ | And | Long-standing Android client, PGP via OpenKeychain |
| [FairEmail](https://email.faircode.eu) | ✅ | ⭐⭐⭐⭐⭐ | And | Privacy-focused, lightweight, unified inbox |
| [Roundcube](https://roundcube.net) | ✅ | ⭐⭐⭐⭐ | Self | Browser-based IMAP webmail |
| [SnappyMail](https://snappymail.eu) | ✅ | ⭐⭐⭐⭐ | Self | Fast modern web mail client |

## Email Aliasing & Forwarding

Hide your real address; generate a unique alias per site.

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [addy.io](https://addy.io) (AnonAddy) | ✅ | ⭐⭐⭐⭐⭐ | Web/Self/And/iOS | Unlimited aliases, self-hostable, free plan |
| [SimpleLogin](https://simplelogin.io) | ✅ | ⭐⭐⭐⭐⭐ | Web/Self/And/iOS | Open, self-hostable, Proton-owned |
| [Firefox Relay](https://relay.firefox.com) | ✅ | ⭐⭐⭐⭐ | Web/Ext | By Mozilla, 1-click aliases |

## Virtual Phone Numbers

For anonymous SMS verification without giving your real number.

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Silent.link](https://silent.link) | ❌ | ⭐⭐⭐⭐ | Anonymous eSIM, SMS/calls/data, pay in BTC |
| [JMP.chat](https://jmp.chat) | ⚠️ | ⭐⭐⭐⭐ | Number via XMPP/Matrix/SIP, US/Canada |
| [MoneroSMS](https://monerosms.com) | ❌ | ⭐⭐⭐⭐ | Anonymous SMS activation, pay in XMR |

---

# 👥 Social & Fediverse

## Mainstream App Alternatives

### 📘 Facebook
| Option | FOSS | Note |
|---|---|---|
| [Friendica](https://friendi.ca) | ✅ | Connects with Mastodon/Diaspora/other networks |
| [Diaspora](https://diasporafoundation.org) | ✅ | Decentralized, federated, no ads |
| [Minds](https://www.minds.com) | ✅ | Crypto-rewards social network |

### 🐦 Twitter / X
| Option | FOSS | Note |
|---|---|---|
| [Mastodon](https://joinmastodon.org) | ✅ | Biggest decentralized alternative |
| [Nitter](https://github.com/zedeus/nitter) | ✅ | Privacy frontend (⚠️ many instances unstable) |
| [Misskey](https://misskey-hub.net) | ✅ | Feature-rich Fediverse server |

### 📸 Instagram
| Option | FOSS | Note |
|---|---|---|
| [Pixelfed](https://pixelfed.org) | ✅ | Photo-sharing Fediverse alternative |
| [Barinsta](https://github.com/austinhuang0131/barinsta) | ✅ | Privacy-friendly Instagram client (Android) |

### ▶️ YouTube
| Option | FOSS | Note |
|---|---|---|
| [NewPipe](https://newpipe.net) | ✅ | Lightweight Android client, background play |
| [FreeTube](https://freetubeapp.io) | ✅ | Private desktop client |
| [Invidious](https://invidious.io) | ✅ | Self-hostable privacy frontend |
| [Piped](https://piped.video) | ✅ | Similar to Invidious, actively maintained |
| [LibreTube](https://libre-tube.github.io) | ✅ | Android frontend on Piped backend |
| [PeerTube](https://joinpeertube.org) | ✅ | Full decentralized video hosting |

### 💬 WhatsApp
See [Encrypted Messaging](#encrypted-messaging) — **Signal**, **SimpleX**, **Element**.

### 🤖 Reddit
| Option | FOSS | Note |
|---|---|---|
| [Lemmy](https://join-lemmy.org) | ✅ | Federated Reddit-style platform |
| [Redlib](https://github.com/redlib-org/redlib) | ✅ | Privacy frontend (Libreddit successor) |
| [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit) | ✅ | Android client, strong anonymous mode |
| [RedReader](https://github.com/QuantumBadger/RedReader) | ✅ | Lightweight Android client |
| [Kbin / Mbin](https://mbin.grjy.info) | ✅ | Reddit+Lemmy-style Fediverse |

### 🎮 Discord
| Option | FOSS | Note |
|---|---|---|
| [Revolt](https://revolt.chat) | ✅ | Discord-like UI, actively growing |
| [Element (Matrix)](https://element.io) | ✅ | Full chat/voice alternative |

## Fediverse Platforms

Interconnected, independently-run servers (ActivityPub). All FOSS, all self-hostable.

| Platform | Replaces | Note |
|---|---|---|
| [Mastodon](https://joinmastodon.org) | Twitter/X | Largest, most well-known |
| [Misskey](https://misskey-hub.net) | Twitter/X | Feature-rich, experimental UI |
| [Firefish](https://firefish.dev) / [Iceshrimp](https://iceshrimp.dev) | Twitter/X | Actively-developed Misskey forks |
| [Pleroma](https://pleroma.social) | Twitter/X | Lightweight, low resource use |
| [Akkoma](https://akkoma.social) | Twitter/X | Actively-maintained Pleroma fork |
| [GoToSocial](https://gotosocial.org) | Twitter/X | Lightweight, great for small servers |
| [Friendica](https://friendi.ca) | Facebook | Cross-network connectivity |
| [Hubzilla](https://hubzilla.org) | Facebook | Nomadic identity, permissions |
| [Pixelfed](https://pixelfed.org) | Instagram | Photo sharing |
| [PeerTube](https://joinpeertube.org) | YouTube | Decentralized video |
| [Lemmy](https://join-lemmy.org) | Reddit | Link aggregation/forums |
| [Kbin / Mbin](https://mbin.grjy.info) | Reddit | Reddit+Lemmy hybrid |
| [WriteFreely](https://writefreely.org) | Medium | Minimalist federated blogging |
| [Funkwhale](https://funkwhale.audio) | Spotify/SoundCloud | Federated audio streaming |
| [BookWyrm](https://joinbookwyrm.com) | Goodreads | Book tracking & reviews |
| [Mobilizon](https://joinmobilizon.org) | FB Events | Event planning |
| [Owncast](https://owncast.online) | Twitch | Self-hosted live streaming |

---

# 🔵 Google Apps Alternatives

> Some are components, not 1-to-1 replacements — noted where relevant.

| Google App | Alternatives | Note |
|---|---|---|
| Gmail | [Tuta](https://tuta.com), [Proton Mail](https://proton.me/mail) | See [Email](#email-providers) |
| Drive | [Nextcloud](https://nextcloud.com), [Seafile](https://www.seafile.com), [Syncthing](https://syncthing.net) | See [Cloud Storage](#cloud-storage--file-sync) |
| Docs/Sheets/Slides | [OnlyOffice](https://www.onlyoffice.com), [Collabora](https://www.collaboraoffice.com/collabora-online/), [CryptPad](https://cryptpad.org) | Self-hostable |
| Calendar | [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar), [Proton Calendar](https://proton.me/calendar), [Tuta Calendar](https://tuta.com/calendar) | CalDAV; sync via [DAVx⁵](https://www.davx5.com) |
| Photos | [Immich](https://immich.app), [Ente](https://ente.io), [PhotoPrism](https://www.photoprism.app), [Nextcloud Memories](https://memories.gallery) | Immich = closest 1:1 |
| Play Store | See [Android App Stores](#android-app-stores) | — |
| Gboard | [HeliBoard](https://github.com/Helium314/HeliBoard), [FlorisBoard](https://florisboard.org), [OpenBoard](https://github.com/openboard-team/openboard), [AnySoftKeyboard](https://anysoftkeyboard.github.io) | No-internet-permission keyboards |
| Assistant | [Home Assistant Voice](https://www.home-assistant.io/voice_control/) | Local processing |
| Translate | [LibreTranslate](https://libretranslate.com) | Fully open, self-hostable |
| Meet | [Jitsi](https://meet.jit.si), [Element Call](https://element.io/call) | See [Video](#video-calls--voip) |
| Analytics | [Matomo](https://matomo.org), [Plausible](https://plausible.io), [Umami](https://umami.is), [GoatCounter](https://www.goatcounter.com) | Self-hostable, cookieless |
| Lens | [firefox-translator](https://github.com/DavidVentura/firefox-translator), Tesseract OCR, [Binary Eye](https://github.com/markusfisch/BinaryEye) | ⚠️ No full 1:1 FOSS replacement |
| Maps | [Organic Maps](https://organicmaps.app), [OsmAnd](https://osmand.net), [OpenStreetMap](https://www.openstreetmap.org) | See [Maps](#maps--navigation) |
| News | See [News & RSS](#news--rss) | — |
| Authenticator | See [2FA Apps](#2fa--authenticator-apps) | — |
| Chrome | See [Browsers](#browsers--desktop) | — |
| Contacts/Sync | [DAVx⁵](https://www.davx5.com) + Nextcloud | CardDAV/CalDAV sync |

---

# ☁️ Cloud & Sync

## Cloud Storage & File Sync

| App | FOSS | Privacy | Platform | Zero-Knowledge | Note |
|---|---|---|---|---|---|
| [Nextcloud](https://nextcloud.com) | ✅ | ⭐⭐⭐⭐⭐ | Self | Optional (E2EE module) | Full suite: files, calendar, contacts, office |
| [Syncthing](https://syncthing.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And | N/A (P2P) | Peer-to-peer sync, no central server |
| [Seafile](https://www.seafile.com) | ✅ | ⭐⭐⭐⭐ | Self | Optional | Fast sync, good for large files |
| [CryptPad](https://cryptpad.org) | ✅ | ⭐⭐⭐⭐⭐ | Self/Web | ✅ Yes | Zero-knowledge encrypted docs/collaboration |
| [ownCloud](https://owncloud.com) | ✅ | ⭐⭐⭐⭐ | Self | Optional | Nextcloud's predecessor |
| [Proton Drive](https://proton.me/drive) | ⚠️ | ⭐⭐⭐⭐⭐ | Web/And/iOS | ✅ Yes | E2EE, Swiss, FOSS clients |
| [MEGA](https://mega.nz) | ⚠️ | ⭐⭐⭐⭐ | all | ✅ Yes | Client-side encryption, generous free tier |
| [Filen](https://filen.io) | ⚠️ | ⭐⭐⭐⭐ | all | ✅ Yes | E2EE consumer storage |
| [Internxt](https://internxt.com) | ⚠️ | ⭐⭐⭐⭐ | Web/Lin/Win/Mac | ✅ Yes | Zero-knowledge, EU-based |
| [pCloud](https://www.pcloud.com) | ❌ | ⭐⭐⭐ | all | Paid add-on | Optional client-side encryption |
| [Tresorit](https://tresorit.com) | ❌ | ⭐⭐⭐⭐ | all | ✅ Yes | Business-focused, E2EE |

> 💡 Prefer non-E2EE cloud? Wrap it with [Cryptomator](https://cryptomator.org) — client-side encryption on top of any provider.

## Backup Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [BorgBackup](https://www.borgbackup.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Mac | Deduplicating, encrypted, mature |
| [Restic](https://restic.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Fast, encrypted, many cloud backends |
| [Kopia](https://kopia.io) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Encrypted, deduplicating, has GUI |
| [Duplicati](https://duplicati.com) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | GUI, scheduled encrypted cloud backups |
| [Vorta](https://vorta.borgbase.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Mac | Desktop GUI for BorgBackup |

## Anonymous File Sharing

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [OnionShare](https://onionshare.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Share files anonymously via Tor, no account/server |
| [Syncthing](https://syncthing.net) | ✅ | ⭐⭐⭐⭐⭐ | all | P2P, direct device-to-device |
| [croc](https://github.com/schollz/croc) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Simple encrypted CLI file transfer between any 2 machines |
| [Send (Tumpi)](https://github.com/timvisee/send) | ✅ | ⭐⭐⭐⭐ | Self/Web | Revival of Firefox Send, E2EE file sharing |

---

# 🔐 Security & Encryption

## Password Managers

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Bitwarden](https://bitwarden.com) | ✅ | ⭐⭐⭐⭐⭐ | all | Full-featured, cloud or self-hosted |
| [KeePassXC](https://keepassxc.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Fully offline local vault |
| [KeePassDX](https://www.keepassdx.com) | ✅ | ⭐⭐⭐⭐⭐ | And | KeePass client for Android |
| [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | ✅ | ⭐⭐⭐⭐⭐ | Self | Lightweight Bitwarden-compatible server |
| [Proton Pass](https://proton.me/pass) | ⚠️ | ⭐⭐⭐⭐⭐ | all | E2EE, part of Proton suite |
| [Padloc](https://padloc.app) | ✅ | ⭐⭐⭐⭐ | all | Modern, clean, self-hostable |
| [Psono](https://psono.com) | ✅ | ⭐⭐⭐⭐ | Self | Team-focused, self-hosted |
| [Password Safe](https://pwsafe.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Schneier-designed, offline |
| [KeePass](https://keepass.info) | ✅ | ⭐⭐⭐⭐⭐ | Win (+ports) | The original; many clients/ports exist |

## 2FA / Authenticator Apps

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Aegis](https://getaegis.app) | ✅ | ⭐⭐⭐⭐⭐ | And | Encrypted vault, backups, the Android favorite |
| [Ente Auth](https://ente.io/auth) | ✅ | ⭐⭐⭐⭐⭐ | all | E2EE cross-device sync, works offline too |
| [2FAS](https://2fas.com) | ✅ | ⭐⭐⭐⭐ | And/iOS | Encrypted backups, no account needed |
| [Stratum](https://stratumauth.com) | ✅ | ⭐⭐⭐⭐ | And | (formerly Authenticator Pro), Wear OS companion |
| [FreeOTP](https://freeotp.github.io) | ✅ | ⭐⭐⭐⭐⭐ | And/iOS | Simple, Red Hat-backed |
| [Proton Authenticator](https://proton.me/authenticator) | ✅ | ⭐⭐⭐⭐⭐ | all | New, cross-platform, Proton account |
| [Bitwarden Authenticator](https://bitwarden.com/products/authenticator/) | ✅ | ⭐⭐⭐⭐⭐ | And/iOS | Standalone TOTP from Bitwarden |
| [Tofu](https://www.tofuauth.com) | ✅ | ⭐⭐⭐⭐⭐ | iOS | Clean, minimal |
| [KeePassXC (TOTP)](https://keepassxc.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Passwords + TOTP in one vault |

## File & Disk Encryption

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [VeraCrypt](https://www.veracrypt.fr) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Encrypted containers / full-disk, TrueCrypt successor |
| [Cryptomator](https://cryptomator.org) | ✅ | ⭐⭐⭐⭐⭐ | all | Client-side encryption for any cloud folder |
| [LUKS / cryptsetup](https://gitlab.com/cryptsetup/cryptsetup) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Native Linux full-disk encryption standard |
| [GnuPG (GPG)](https://gnupg.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Standard for file/email encryption & signing |
| [age](https://github.com/FiloSottile/age) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Modern, simple, minimal file encryption |
| [gocryptfs](https://nuetzlich.net/gocryptfs/) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Mac | Encrypted overlay filesystem |
| [Picocrypt](https://github.com/Picocrypt/Picocrypt) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Tiny, simple single-file encryptor |
| [LUKSbox](https://github.com/PentHertz/LUKSbox) | ✅ | ⭐⭐⭐⭐ | Lin/Mac/Win | Container w/ FIDO2, TPM, post-quantum keyslots (pre-1.0) |
| [DiskCryptor](https://www.diskcryptor.org) | ✅ | ⭐⭐⭐⭐ | Win | Open BitLocker alternative |

## Metadata Removal

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [MAT2](https://0xacab.org/jvoisin/mat2) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Metadata Anonymisation Toolkit (EXIF/GPS/author strip) |
| [ExifCleaner](https://github.com/szTheory/exifcleaner) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | GUI drag-and-drop metadata remover |
| [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) | ✅ | ⭐⭐⭐⭐⭐ | And | Strip metadata before sharing on Android |

## Secure Data Wiping

| Tool | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [nwipe](https://github.com/martijnvanbrummelen/nwipe) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Modern DBAN fork, multi-pass wiping (GUI+CLI) |
| [shredOS](https://github.com/PartialVolume/shredos.x86_64) | ✅ | ⭐⭐⭐⭐⭐ | Bootable | Bootable disk-wiping OS based on nwipe |
| [BleachBit](https://www.bleachbit.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win | Clean caches + free-space wipe (CCleaner alt) |
| `shred` (coreutils) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Standard CLI secure-delete |

## Antivirus & Scanning

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [ClamAV](https://www.clamav.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Standard open AV engine |
| [rkhunter](https://rkhunter.sourceforge.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin | Rootkit scanner |
| [Lynis](https://cisofy.com/lynis/) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Mac | Security auditing & hardening scanner |

## Online Privacy Test Tools

Free web tools to check your own exposure (no install needed).

| Tool | Note |
|---|---|
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if your email/passwords are in known breaches |
| [Exodus Privacy](https://reports.exodus-privacy.eu.org) | See which trackers an Android app contains before installing |
| [Cover Your Tracks](https://coveryourtracks.eff.org) | EFF tool testing browser fingerprinting/tracking protection |
| [AmIUnique](https://amiunique.org) | How unique/identifiable your browser fingerprint is |
| [BrowserLeaks](https://browserleaks.com) | Detailed report of what your browser leaks |
| [IPLeak](https://ipleak.net) | IP, DNS, WebRTC leak testing |
| [VirusTotal](https://www.virustotal.com) | Scan a file/URL against many AV engines |

---

# 🌍 Network & Anonymity

## VPN & Mesh Networking

Only **audited, no-logs** providers are listed; the "Proven no-logs" column reflects independent audits or court cases.

| App | FOSS | Privacy | Proven no-logs | Platform | Note |
|---|---|---|---|---|---|
| [Mullvad](https://mullvad.net) | ⚠️ | ⭐⭐⭐⭐⭐ | ✅ Audited | all | Anonymous account #, cash/Monero accepted |
| [Proton VPN](https://protonvpn.com) | ⚠️ | ⭐⭐⭐⭐⭐ | ✅ Audited | all | FOSS clients, Swiss, has free plan |
| [IVPN](https://www.ivpn.net) | ⚠️ | ⭐⭐⭐⭐⭐ | ✅ Audited | all | Anonymous signup, strong ethics, no ads |
| [OVPN](https://www.ovpn.com) | ⚠️ | ⭐⭐⭐⭐⭐ | ✅ Court-proven | all | Swedish, diskless servers |
| [AirVPN](https://airvpn.org) | ⚠️ | ⭐⭐⭐⭐ | Self-reported | all | Activist-run, very transparent |
| [WireGuard](https://www.wireguard.com) | ✅ | ⭐⭐⭐⭐⭐ | N/A (protocol) | all | The modern VPN protocol underlying most above |
| [Orbot](https://orbot.app) | ✅ | ⭐⭐⭐⭐⭐ | N/A (Tor) | And/iOS | Route any app through Tor |
| [Tailscale](https://tailscale.com) | ⚠️ | ⭐⭐⭐⭐ | N/A (mesh) | all | WireGuard mesh; self-host control via Headscale |
| [Headscale](https://headscale.net) | ✅ | ⭐⭐⭐⭐⭐ | N/A | Self | FOSS self-hosted Tailscale control server |
| [Netbird](https://netbird.io) | ✅ | ⭐⭐⭐⭐ | N/A (mesh) | all | Open WireGuard mesh, self-hostable |
| [Nebula](https://github.com/slackhq/nebula) | ✅ | ⭐⭐⭐⭐ | N/A (mesh) | all | Slack's open mesh overlay network |
| [Nostr VPN](https://nostrvpn.org) | ✅ | ⭐⭐⭐⭐ | N/A (mesh) | all | Mesh VPN using Nostr keypairs, no accounts (early-stage) |

## DNS & Ad-Blocking

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| **[NextDNS](https://nextdns.io)** | ❌ | ⭐⭐⭐⭐ | all | Cloud DNS filtering, cross-device, per-device profiles, no-log |
| [Pi-hole](https://pi-hole.net) | ✅ | ⭐⭐⭐⭐⭐ | Self | Network-wide DNS ad blocking |
| [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) | ✅ | ⭐⭐⭐⭐⭐ | Self | Pi-hole alternative, easier setup, DoH/DoT built-in |
| [Technitium DNS](https://technitium.com/dns/) | ✅ | ⭐⭐⭐⭐⭐ | Self | Full self-hosted DNS server + ad blocking |
| [uBlock Origin](https://ublockorigin.com) | ✅ | ⭐⭐⭐⭐⭐ | Ext | Browser-level blocker (pairs with DNS) |
| [Blokada](https://blokada.org) | ✅ | ⭐⭐⭐⭐ | And/iOS | On-device DNS ad blocking, no root |
| [Quad9](https://quad9.net) | ❌ | ⭐⭐⭐⭐ | all | Non-profit malware-blocking resolver (Swiss) |
| [ControlD](https://controld.com) | ❌ | ⭐⭐⭐⭐ | all | Customizable filtering DNS |

## Router Firmware & Firewalls

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [OpenWrt](https://openwrt.org) | ✅ | ⭐⭐⭐⭐⭐ | Router | The standard FOSS router firmware |
| [OPNsense](https://opnsense.org) | ✅ | ⭐⭐⭐⭐⭐ | Self (x86) | Actively-developed firewall/router OS |
| [pfSense CE](https://www.pfsense.org) | ✅ | ⭐⭐⭐⭐⭐ | Self (x86) | Full-featured open firewall/router |
| [IPFire](https://www.ipfire.org) | ✅ | ⭐⭐⭐⭐⭐ | Self (x86) | Security-focused firewall distro |

## Network Monitoring

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Wireshark](https://www.wireshark.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard packet/protocol analyzer |
| [Sniffnet](https://www.sniffnet.net) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Friendly traffic monitor, all-local processing |
| [SnoopSnitch](https://opensource.srlabs.de/projects/snoopsnitch) | ✅ | ⭐⭐⭐⭐⭐ | And | Detects fake base stations (IMSI catchers) |

---

# 💻 Operating Systems

## Anonymity-Focused
| OS | FOSS | Note |
|---|---|---|
| [Tails](https://tails.net) | ✅ | Amnesic, all traffic via Tor, leaves no trace |
| [Whonix](https://www.whonix.org) | ✅ | Gateway+Workstation VMs, all traffic via Tor |
| [Kicksecure](https://www.kicksecure.com) | ✅ | Hardened Debian base (foundation of Whonix) |

## Pentesting / Investigation
| OS | FOSS | Note |
|---|---|---|
| [Kali Linux](https://www.kali.org) | ✅ | Best-known pentesting distro |
| [Parrot OS](https://parrotsec.org) | ✅ | Security + privacy focus, lighter than Kali |
| [BlackArch](https://blackarch.org) | ✅ | Arch-based, huge tool repo |

## Gaming
| OS | FOSS | Note |
|---|---|---|
| [Bazzite](https://bazzite.gg) | ✅ | SteamOS-like, immutable, desktop + handheld |
| [Nobara](https://nobaraproject.org) | ✅ | Fedora-based, gaming-optimized |
| [SteamOS](https://store.steampowered.com/steamos) | ⚠️ | Valve's own (Steam Deck) |

## Beginner / Windows-Refugee
| OS | FOSS | Note |
|---|---|---|
| [Linux Mint](https://linuxmint.com) | ✅ | Most beginner-friendly, familiar UI |
| [Zorin OS](https://zorin.com/os) | ⚠️ | Windows-like layout, some paid features |
| [Pop!_OS](https://pop.system76.com) | ✅ | Clean, good for beginners + power users |

## Mainstream Distros
| OS | FOSS | Note |
|---|---|---|
| [Debian](https://www.debian.org) | ✅ | The stability backbone of the Linux world |
| [Ubuntu](https://ubuntu.com) | ✅ | Most widely used, Debian-based |
| [Fedora](https://fedoraproject.org) | ✅ | Cutting-edge, Red Hat-sponsored |
| [openSUSE](https://www.opensuse.org) | ✅ | Strong tooling (YaST), rolling + fixed |
| [Arch Linux](https://archlinux.org) | ✅ | Rolling, build-it-yourself |
| [Manjaro](https://manjaro.org) | ✅ | Arch made accessible |
| [EndeavourOS](https://endeavouros.com) | ✅ | Arch-based, friendly installer |
| [Void Linux](https://voidlinux.org) | ✅ | Independent, runit (no systemd) |
| [Gentoo](https://www.gentoo.org) | ✅ | Source-based, fully customizable |
| [NixOS](https://nixos.org) | ✅ | Declarative, reproducible config |
| [MX Linux](https://mxlinux.org) | ✅ | Debian-based, light, great on old hardware |

## Minimal / Low-RAM
| Distro | RAM | Note |
|---|---|---|
| [Tiny Core Linux](https://www.tinycorelinux.net) | ~64MB | Extremely minimal, modular |
| [antiX](https://antixlinux.com) | ~128MB | Debian-based, systemd-free option |
| [Puppy Linux](https://puppylinux-woof-ce.github.io) | ~128–256MB | Runs entirely from RAM |
| [Bodhi Linux](https://www.bodhilinux.com) | ~256MB | Moksha desktop, lightweight |
| [Q4OS](https://q4os.org) | ~256MB | Trinity/KDE, very light |
| [SparkyLinux](https://sparkylinux.org) | ~256MB | Debian-based, minimal editions |

## Immutable / Hardened
| OS | FOSS | Note |
|---|---|---|
| [Qubes OS](https://www.qubes-os.org) | ✅ | Compartmentalized security via VMs |
| [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/) | ✅ | Immutable desktop, atomic updates |
| [Secureblue](https://secureblue.dev) | ✅ | Hardened Fedora Atomic images |

## Debloated Windows
> Windows-based (for unavoidable dual-boot/VM use), not Linux alternatives.

| Tool | FOSS | Note |
|---|---|---|
| [Tiny11](https://github.com/ntdevlabs/tiny11builder) | ✅ | Stripped-down Windows 11 image |
| [AtlasOS](https://atlasos.net) | ✅ | Performance/privacy Windows tweak set |
| [ReviOS](https://revi.cc) | ✅ | Debloated Windows image |
| [Chris Titus WinUtil](https://github.com/ChrisTitusTech/winutil) | ✅ | Script to debloat/configure existing Windows |

## Boot & USB Tools
| App | FOSS | Platform | Note |
|---|---|---|---|
| [Ventoy](https://www.ventoy.net) | ✅ | Lin/Win | Multi-ISO bootable USB, no re-flashing |
| [balenaEtcher](https://etcher.balena.io) | ✅ | Lin/Win/Mac | Simple ISO-to-USB writer |
| [EtchDroid](https://github.com/etchdroid/etchdroid) | ✅ | And | Write OS images to USB from Android, no root |
| [netboot.xyz](https://netboot.xyz) | ✅ | Self | Network-boot dozens of OSes via iPXE |

---

# 📱 Mobile & Android

## Android App Stores

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [F-Droid](https://f-droid.org) | ✅ | ⭐⭐⭐⭐⭐ | The original FOSS Android app catalogue |
| [Droid-ify](https://github.com/Droid-ify/client) | ✅ | ⭐⭐⭐⭐⭐ | Fast, modern F-Droid client |
| [Neo Store](https://github.com/NeoApplications/Neo-Store) | ✅ | ⭐⭐⭐⭐⭐ | Feature-rich F-Droid client |
| [Accrescent](https://accrescent.app) | ✅ | ⭐⭐⭐⭐⭐ | New store, strong app-signing security |
| [Obtainium](https://github.com/ImranR98/Obtainium) | ✅ | ⭐⭐⭐⭐⭐ | Install/update apps straight from GitHub/GitLab |
| [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore) | ✅ | ⭐⭐⭐⭐ | Anonymous frontend to Google Play |
| [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) | ✅ | ⭐⭐⭐⭐ | Extra F-Droid repo, many more apps |
| [Uptodown](https://uptodown.com) | ❌ | ⭐⭐ | Non-Play APK store, no account |
| [Amazon Appstore](https://www.amazon.com/appstore) | ❌ | ⭐⭐ | Sideloadable alt ecosystem |

## Mobile ROMs

| ROM | FOSS | Privacy | Note |
|---|---|---|---|
| [GrapheneOS](https://grapheneos.org) | ✅ | ⭐⭐⭐⭐⭐ | Security & privacy hardened, Pixel-only |
| [CalyxOS](https://calyxos.org) | ✅ | ⭐⭐⭐⭐⭐ | Privacy-focused, microG option |
| [DivestOS](https://divestos.org) | ✅ | ⭐⭐⭐⭐⭐ | LineageOS-based, extended patches/devices |
| [LineageOS](https://lineageos.org) | ✅ | ⭐⭐⭐⭐ | Broadest device support |
| [/e/OS](https://e.foundation) | ✅ | ⭐⭐⭐⭐ | De-googled, consumer-friendly |
| [PostmarketOS](https://postmarketos.org) | ✅ | ⭐⭐⭐⭐ | Real Linux on phones, mainline kernel |
| [Ubuntu Touch](https://ubuntu-touch.io) | ✅ | ⭐⭐⭐⭐ | Full Linux mobile OS (UBports) |

## Fossify Suite

A cohesive, ad-free, no-internet-permission suite of stock-app replacements (successor to Simple Mobile Tools). All ✅ FOSS, GPL-3.0, ⭐⭐⭐⭐⭐.

| App | Replaces | Link |
|---|---|---|
| Fossify Gallery | Google Photos (local) | [F-Droid](https://f-droid.org/packages/org.fossify.gallery/) |
| Fossify Calendar | Google Calendar | [F-Droid](https://f-droid.org/packages/org.fossify.calendar/) |
| Fossify Contacts | Google Contacts | [F-Droid](https://f-droid.org/packages/org.fossify.contacts/) |
| Fossify Phone | Google Phone/Dialer | [F-Droid](https://f-droid.org/packages/org.fossify.phone/) |
| Fossify Messages | Google Messages | [F-Droid](https://f-droid.org/packages/org.fossify.messages/) |
| Fossify File Manager | Files | [F-Droid](https://f-droid.org/packages/org.fossify.filemanager/) |
| Fossify Notes | Google Keep | [F-Droid](https://f-droid.org/packages/org.fossify.notes/) |
| Fossify Music Player | local music apps | [F-Droid](https://f-droid.org/packages/org.fossify.musicplayer/) |
| Fossify Camera | stock camera | [F-Droid](https://f-droid.org/packages/org.fossify.camera/) |
| Fossify Clock | stock clock | [F-Droid](https://f-droid.org/packages/org.fossify.clock/) |
| Fossify Calculator | stock calculator | [F-Droid](https://f-droid.org/packages/org.fossify.calculator/) |
| Fossify Keyboard | Gboard (basic) | [F-Droid](https://f-droid.org/packages/org.fossify.keyboard/) |
| Fossify Voice Recorder | stock recorder | [F-Droid](https://f-droid.org/packages/org.fossify.voicerecorder/) |
| Fossify Draw | sketch/notes | [F-Droid](https://f-droid.org/packages/org.fossify.draw/) |
| Fossify Launcher | stock launcher | [F-Droid](https://f-droid.org/packages/org.fossify.home/) |

## Android Essentials & PIM

Other must-have FOSS Android apps (all on F-Droid unless noted).

| App | FOSS | Replaces / Purpose | Note |
|---|---|---|---|
| [DAVx⁵](https://www.davx5.com) | ✅ | CalDAV/CardDAV sync | Sync calendar/contacts with Nextcloud etc. |
| [Tasks.org](https://tasks.org) | ✅ | Google Tasks/Todoist | CalDAV-compatible to-do lists |
| [Markor](https://github.com/gsantner/markor) | ✅ | Google Keep/notes | Markdown/text notes, file-based, offline |
| [KDE Connect](https://kdeconnect.kde.org) | ✅ | Phone Link | Clipboard/file/notification bridge to desktop |
| [Organic Maps](https://organicmaps.app) | ✅ | Google Maps | Offline OSM maps, navigation, no tracking |
| [OsmAnd](https://osmand.net) | ✅ | Google Maps | Powerful OSM maps/navigation |
| [HeliBoard](https://github.com/Helium314/HeliBoard) | ✅ | Gboard | Customizable, multilingual, offline keyboard |
| [Material Files](https://github.com/zhanghai/MaterialFiles) | ✅ | Files | Material file manager, SMB/FTP/WebDAV |
| [Librera Reader](https://librera.mobi) | ✅ | e-reader | PDF/EPUB/MOBI reader, no ads |
| [Saber](https://github.com/saber-notes/saber) | ✅ | Samsung Notes | Handwriting notes app for stylus |
| [Aves](https://github.com/deckerst/aves) | ✅ | Gallery | Feature-rich gallery alternative |
| [AntennaPod](https://antennapod.org) | ✅ | podcast app | The FOSS podcast manager |
| [Breezy Weather](https://github.com/breezy-weather/breezy-weather) | ✅ | weather app | Multi-source, no tracking |
| [Lawnchair](https://lawnchair.app) | ✅ | launcher | Pixel-like customizable launcher |
| [Kvæsitso](https://kvaesitso.mm20.de) | ✅ | launcher | Search-first launcher, Nextcloud integration |

## Mobile Privacy & Firewall

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [RethinkDNS + Firewall](https://rethinkdns.com) | ✅ | ⭐⭐⭐⭐⭐ | Firewall + DNS + WireGuard, no root |
| [NetGuard](https://netguard.me) | ✅ | ⭐⭐⭐⭐⭐ | Per-app no-root firewall |
| [TrackerControl](https://trackercontrol.org) | ✅ | ⭐⭐⭐⭐⭐ | Detect & block in-app trackers |
| [AFWall+](https://github.com/ukanth/afwall) | ✅ | ⭐⭐⭐⭐⭐ | Advanced iptables firewall (root) |
| [Exodus Privacy](https://exodus-privacy.eu.org) | ✅ | ⭐⭐⭐⭐⭐ | Reveal trackers in your installed apps |
| [Insular](https://gitlab.com/secure-system/Insular) | ✅ | ⭐⭐⭐⭐ | Sandbox/clone apps away from your data |
| [Shelter](https://gitea.angry.im/PeterCxy/Shelter) | ✅ | ⭐⭐⭐⭐ | Work-profile app isolation |
| [XPrivacyLua](https://lua.xprivacy.eu) | ✅ | ⭐⭐⭐⭐⭐ | Feed apps fake data for permissions (root) |
| [SuperFreezZ](https://superfreezz.gitlab.io) | ✅ | ⭐⭐⭐⭐ | Freeze background app activity |
| [Warden](https://github.com/kmods-magisk/Warden) | ✅ | ⭐⭐⭐⭐ | App tracker/analytics disabler |

## Android Runtimes & Virtualization

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Waydroid](https://waydro.id) | ✅ | ⭐⭐⭐⭐ | Full Android in a Linux container (Wayland) |
| [Termux](https://termux.dev) + [proot-distro](https://github.com/termux/proot-distro) | ✅ | ⭐⭐⭐⭐ | Real Linux distro on Android, no root |
| [UserLAnd](https://github.com/CypherpunkArmory/UserLAnd) | ✅ | ⭐⭐⭐⭐ | GUI-friendly Linux distros on Android |

---

# 🗂️ Productivity

## Notes & Knowledge

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Joplin](https://joplinapp.org) | ✅ | ⭐⭐⭐⭐⭐ | all | Evernote alt, E2EE sync |
| [Standard Notes](https://standardnotes.com) | ✅ | ⭐⭐⭐⭐⭐ | all | Simple, extensible, E2EE |
| [Logseq](https://logseq.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/And/iOS | Local-first knowledge graph |
| [Trilium Notes](https://github.com/zadam/trilium) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Hierarchical, self-hosted, powerful |
| [Anytype](https://anytype.io) | ✅ | ⭐⭐⭐⭐⭐ | all | Local-first, E2EE, Notion-style |
| [Notesnook](https://notesnook.com) | ✅ | ⭐⭐⭐⭐⭐ | all | E2EE Evernote alternative |
| [AFFiNE](https://affine.pro) | ✅ | ⭐⭐⭐⭐ | all | Notion/Miro-style all-in-one |
| [Obsidian](https://obsidian.md) | ⚠️ | ⭐⭐⭐⭐ | all | Free, local-first, but not open source |
| [SilverBullet](https://silverbullet.md) | ✅ | ⭐⭐⭐⭐⭐ | Self | Self-hosted markdown knowledge base |

## Office Suites

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [LibreOffice](https://www.libreoffice.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | The standard offline suite |
| [OnlyOffice](https://www.onlyoffice.com) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac/Self | Best MS Office compatibility |
| [Collabora Online](https://www.collaboraoffice.com/collabora-online/) | ✅ | ⭐⭐⭐⭐⭐ | Self | LibreOffice-based, Nextcloud integration |
| [Apache OpenOffice](https://www.openoffice.org) | ✅ | ⭐⭐⭐⭐ | Lin/Win/Mac | Older LibreOffice sibling |

## Project & Task Management

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Vikunja](https://vikunja.io) | ✅ | ⭐⭐⭐⭐⭐ | Self | Todoist/Trello-style, self-hosted |
| [Focalboard](https://www.focalboard.com) | ✅ | ⭐⭐⭐⭐ | Self | Trello-style kanban (Mattermost) |
| [OpenProject](https://www.openproject.org) | ✅ | ⭐⭐⭐⭐⭐ | Self | Full PM suite, Gantt (Community = FOSS) |
| [Planka](https://planka.app) | ✅ | ⭐⭐⭐⭐ | Self | Realtime Trello alternative |
| [Tasks.org](https://tasks.org) | ✅ | ⭐⭐⭐⭐⭐ | And | CalDAV to-do lists |

## PDF Tools

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | ✅ | ⭐⭐⭐⭐⭐ | Self | Full PDF toolkit: merge/split/OCR/convert, local |
| [Slay PDF](https://slaypdf.com/) | ✅ | ⭐⭐⭐⭐⭐ | Web | Local browser PDF editor: split/merge/sign/edit, no uploads |
| [PDFsam](https://pdfsam.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Merge/split/rotate desktop tool |
| [Xournal++](https://xournalpp.github.io) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Annotate/handwrite on PDFs |
| [Okular](https://okular.kde.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | KDE document/PDF viewer + annotation |

## Personal Finance

| App | FOSS | Privacy | Platform | Note |
|---|---|---|---|---|
| [Firefly III](https://www.firefly-iii.org) | ✅ | ⭐⭐⭐⭐⭐ | Self | Full personal finance manager, budgets |
| [Actual Budget](https://actualbudget.org) | ✅ | ⭐⭐⭐⭐⭐ | Self/Lin/Win/Mac | Fast envelope-budgeting (YNAB alt) |
| [GnuCash](https://www.gnucash.org) | ✅ | ⭐⭐⭐⭐⭐ | Lin/Win/Mac | Double-entry accounting |
| [Ivy Wallet](https://github.com/Ivy-Apps/ivy-wallet) | ✅ | ⭐⭐⭐⭐⭐ | And | Simple money manager |

---

# 🎬 Media

## Media Servers & Streaming

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Jellyfin](https://jellyfin.org) | ✅ | ⭐⭐⭐⭐⭐ | Fully open Plex alternative |
| [Immich](https://immich.app) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted photo/video backup, Google Photos-style |
| [Kodi](https://kodi.tv) | ✅ | ⭐⭐⭐⭐⭐ | Media center software |
| [Navidrome](https://www.navidrome.org) | ✅ | ⭐⭐⭐⭐⭐ | Music streaming server, Subsonic API |
| [Audiobookshelf](https://www.audiobookshelf.org) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted audiobook/podcast server |
| [Nova Video Player](https://github.com/nova-video-player/aos-AVP) | ✅ | ⭐⭐⭐⭐ | Local/network (SMB/FTP) player, Netflix-style UI |
| [VLC](https://www.videolan.org) | ✅ | ⭐⭐⭐⭐⭐ | Universal media player |
| [mpv](https://mpv.io) | ✅ | ⭐⭐⭐⭐⭐ | Minimal, scriptable, high-quality player |
| [Emby](https://emby.media) | ⚠️ | ⭐⭐⭐ | Core open, premium closed |

## Image & Video Editing

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [GIMP](https://www.gimp.org) | ✅ | ⭐⭐⭐⭐⭐ | Photoshop alternative |
| [Krita](https://krita.org) | ✅ | ⭐⭐⭐⭐⭐ | Digital painting |
| [Inkscape](https://inkscape.org) | ✅ | ⭐⭐⭐⭐⭐ | Vector graphics (Illustrator alt) |
| [Darktable](https://www.darktable.org) | ✅ | ⭐⭐⭐⭐⭐ | RAW processing (Lightroom alt) |
| [RawTherapee](https://rawtherapee.com) | ✅ | ⭐⭐⭐⭐⭐ | RAW processing |
| [Kdenlive](https://kdenlive.org) | ✅ | ⭐⭐⭐⭐⭐ | Full non-linear video editor |
| [Shotcut](https://shotcut.org) | ✅ | ⭐⭐⭐⭐⭐ | Cross-platform video editor |
| [Flowblade](https://github.com/jliljebl/flowblade) | ✅ | ⭐⭐⭐⭐⭐ | Linux multitrack editor |
| [OpenShot](https://www.openshot.org) | ✅ | ⭐⭐⭐⭐⭐ | Beginner-friendly video editor |
| [LosslessCut](https://github.com/mifi/lossless-cut) | ✅ | ⭐⭐⭐⭐⭐ | Cut/trim/merge without re-encoding |
| [MKVToolNix](https://mkvtoolnix.download) | ✅ | ⭐⭐⭐⭐⭐ | Create/edit/mux MKV without re-encoding |
| [HandBrake](https://handbrake.fr) | ✅ | ⭐⭐⭐⭐⭐ | Video transcoder/converter |
| [Natron](https://natrongithub.github.io) | ✅ | ⭐⭐⭐⭐⭐ | Node compositing (After Effects alt) |
| [Blender](https://www.blender.org) | ✅ | ⭐⭐⭐⭐⭐ | 3D + video editing/compositing |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | ❌ | ⭐⭐⭐ | Freeware pro-grade, closed source |

## Media Downloaders

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | ✅ | ⭐⭐⭐⭐⭐ | The standard CLI downloader, 1000s of sites |
| [Seal](https://github.com/JunkFood02/Seal) | ✅ | ⭐⭐⭐⭐⭐ | Android yt-dlp GUI |
| [Parabolic](https://github.com/NickvisionApps/Parabolic) | ✅ | ⭐⭐⭐⭐⭐ | Desktop yt-dlp GUI |

## Screen Recording & Streaming

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [OBS Studio](https://obsproject.com) | ✅ | ⭐⭐⭐⭐⭐ | Standard for recording & live streaming |
| [Kooha](https://github.com/SeaDve/Kooha) | ✅ | ⭐⭐⭐⭐⭐ | Simple GNOME/Wayland screen recorder |
| [SimpleScreenRecorder](https://www.maartenbaert.be/simplescreenrecorder/) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight Linux recorder |

## E-Books & Reading

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Calibre](https://calibre-ebook.com) | ✅ | ⭐⭐⭐⭐⭐ | Standard e-book library manager/converter |
| [Calibre-Web](https://github.com/janeczku/calibre-web) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted web UI for a Calibre library |
| [Koreader](https://github.com/koreader/koreader) | ✅ | ⭐⭐⭐⭐⭐ | Powerful e-reader (e-ink/Android/Linux) |
| [Librera](https://librera.mobi) | ✅ | ⭐⭐⭐⭐⭐ | Android reader, PDF/EPUB/MOBI |
| [Thorium Reader](https://www.edrlab.org/software/thorium-reader/) | ✅ | ⭐⭐⭐⭐⭐ | Desktop EPUB reader |

## Maps & Navigation

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Organic Maps](https://organicmaps.app) | ✅ | ⭐⭐⭐⭐⭐ | Offline OSM maps, no tracking, Android Auto |
| [OsmAnd](https://osmand.net) | ✅ | ⭐⭐⭐⭐⭐ | Powerful OSM maps/navigation |
| [OpenStreetMap](https://www.openstreetmap.org) | ✅ | ⭐⭐⭐⭐⭐ | The open map data behind them all |
| [Magic Earth](https://www.magicearth.com) | ❌ | ⭐⭐⭐⭐ | OSM-based navigation w/ traffic |

---

# 📰 News & RSS

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [FreshRSS](https://freshrss.org) | ✅ | ⭐⭐⭐⭐⭐ | Full-featured self-hosted aggregator |
| [Miniflux](https://miniflux.app) | ✅ | ⭐⭐⭐⭐⭐ | Minimalist self-hosted reader |
| [Tiny Tiny RSS](https://tt-rss.org) | ✅ | ⭐⭐⭐⭐⭐ | Long-running self-hosted reader |
| [NetNewsWire](https://netnewswire.com) | ✅ | ⭐⭐⭐⭐⭐ | Native Mac/iOS, no tracking |
| [Feeder](https://github.com/spacecowboy/Feeder) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight Android RSS |
| [Fluent Reader](https://github.com/yang991178/fluent-reader) | ✅ | ⭐⭐⭐⭐⭐ | Desktop RSS reader |
| [Fraidycat](https://fraidyc.at) | ✅ | ⭐⭐⭐⭐⭐ | Follow feeds without algorithms |
| [NewsBlur](https://newsblur.com) | ✅ | ⭐⭐⭐⭐ | Social RSS, hosted or self-hosted |
| [Ground News](https://ground.news) | ❌ | ⭐⭐⭐ | Media-bias comparison (not FOSS, media-literacy tool) |

---

# 🤖 Privacy-Respecting AI

Run models locally — your prompts never leave your machine.

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Ollama](https://ollama.com) | ✅ | ⭐⭐⭐⭐⭐ | Run LLMs locally, easy model management |
| [Jan](https://jan.ai) | ✅ | ⭐⭐⭐⭐⭐ | Offline ChatGPT-style desktop app |
| [GPT4All](https://www.nomic.ai/gpt4all) | ✅ | ⭐⭐⭐⭐⭐ | Local LLM runner, simple UI |
| [Open WebUI](https://github.com/open-webui/open-webui) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted ChatGPT-style UI for Ollama |
| [LocalAI](https://localai.io) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted OpenAI-compatible backend |
| [Kobold.cpp](https://github.com/LostRuins/koboldcpp) | ✅ | ⭐⭐⭐⭐⭐ | Local LLM for creative writing/roleplay |
| [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) | ✅ | ⭐⭐⭐⭐⭐ | Advanced local LLM interface |
| [Wan2GP](https://github.com/deepbeepmeep/Wan2GP) | ✅ | ⭐⭐⭐⭐⭐ | Local image/video generation |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | ✅ | ⭐⭐⭐⭐⭐ | Node-based local image-generation |
| [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) | ✅ | ⭐⭐⭐⭐⭐ | Local speech-to-text |
| [LM Studio](https://lmstudio.ai) | ❌ | ⭐⭐⭐⭐ | Free (closed) local LLM GUI |

---

# 🖥️ System & Self-Hosting

## Self-Hosting Platforms

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [YunoHost](https://yunohost.org) | ✅ | ⭐⭐⭐⭐⭐ | All-in-one self-hosting OS, 100s of 1-click apps |
| [CasaOS](https://casaos.io) | ✅ | ⭐⭐⭐⭐ | Friendly home-server dashboard |
| [Cosmos](https://cosmos-cloud.io) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosting w/ built-in security/reverse-proxy |
| [Portainer CE](https://www.portainer.io) | ✅ | ⭐⭐⭐⭐ | Web UI for Docker management |
| [Coolify](https://coolify.io) | ✅ | ⭐⭐⭐⭐⭐ | Self-hosted Heroku/Netlify (PaaS) alternative |
| [Nginx Proxy Manager](https://nginxproxymanager.com) | ✅ | ⭐⭐⭐⭐ | Easy reverse proxy + SSL GUI |

## Torrenting / P2P

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [qBittorrent](https://www.qbittorrent.org) | ✅ | ⭐⭐⭐⭐⭐ | Most popular FOSS client, no ads |
| [Transmission](https://transmissionbt.com) | ✅ | ⭐⭐⭐⭐⭐ | Lightweight, cross-platform |
| [Deluge](https://deluge-torrent.org) | ✅ | ⭐⭐⭐⭐⭐ | Plugin-extensible |
| [rTorrent](https://github.com/rakshasa/rtorrent) | ✅ | ⭐⭐⭐⭐⭐ | Terminal + ruTorrent web UI, headless |
| [Tribler](https://www.tribler.org) | ✅ | ⭐⭐⭐⭐⭐ | Built-in Tor-like anonymity layer |
| [libretorrent](https://gitlab.com/proninyaroslav/libretorrent) | ✅ | ⭐⭐⭐⭐⭐ | FOSS Android torrent client |

## Windows Compatibility on Linux

| App | FOSS | Note |
|---|---|---|
| [Wine](https://www.winehq.org) | ✅ | Run Windows apps directly, no VM |
| [Proton](https://github.com/ValveSoftware/Proton) | ✅ | Wine-based, powers Steam on Linux gaming |
| [Bottles](https://usebottles.com) | ✅ | Friendly Wine prefix manager |
| [Lutris](https://lutris.net) | ✅ | Game manager across Wine/Proton/emulators |
| [WinPodX](https://github.com/kernalix7/winpodx) | ✅ | Real Windows in a container, apps as native Linux windows |

---

# 🏠 Niche & Smart Home

## Presence Detection

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [ESPectre](https://github.com/francescopace/espectre) | ✅ | ⭐⭐⭐⭐⭐ | WiFi-CSI motion detection on ESP32, no camera/mic, HA integration |
| [ESPHome WiFi-CSI](https://github.com/PeterkoCZ91/esphome-wifi-csi) | ✅ | ⭐⭐⭐⭐⭐ | Presence + breathing detection via WiFi CSI |

## Weather

| App | FOSS | Privacy | Note |
|---|---|---|---|
| [Breezy Weather](https://github.com/breezy-weather/breezy-weather) | ✅ | ⭐⭐⭐⭐⭐ | Android, multi-source, no account/tracking |

---

# 📋 Curated Meta-Lists

Cross-reference these for anything still missing:

| List | Note |
|---|---|
| [awesome-privacy (Lissy93)](https://github.com/Lissy93/awesome-privacy) | Large general privacy-alternatives list |
| [PrivacyGuides.org](https://www.privacyguides.org) | Vetted recommendations with rationale + threat models |
| [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) | The largest self-hosted software catalogue |
| [awesome-android-security](https://github.com/saeidshirazi/awesome-android-security) | Android security tooling |
| [The New Oil](https://thenewoil.org) | Beginner-friendly privacy guides |
| [Awesome-Selfhosted (alternatives)](https://awesome-selfhosted.net) | Browsable web version |

---

<div align="center">
### 🐦 Please follow my friend who helped make this list possible

[@Labyrinthusian](https://twitter.com/Labyrinthusian)
*This list is a living document — contributions, corrections and additions welcome via PR.*

**License:** [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain, use freely.

</div>
