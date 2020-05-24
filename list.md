# FOSS and privacy software

*Please read the comments under each table.*

## Android apps

Type | App | FOSS alternatives
:--- | :--- | :---
Calculator | \- | Calculator++
Calendar | \- | Simple Calendar
Camera | GCam | OpenCamera
Browser | Chrome, Opera | Brave\*, [Bromite](https://www.bromite.org/)\*, Firefox\* or Fennec F-Droid, Tor Browser\*
E-book/PDF reader | Acrobat Reader, AIReader | Librera, Book Reader, FBReader
~~Facebook~~\*\* | Frost
File manager | ES File Explorer, Total Commander | Amaze, Ghost Commander, Material Files
On-screen Keyboard | GBoard | OpenBoard, AOSP Keyboard\*
E-mail | Gmail | FairEmail, K-9 Mail
2FA | Google Authenticator | Aegis
Maps and navigation | Google Maps, Maps.me | OsmAnd+
Gallery | Google Photos | Simple Gallery
App store | Google Play Store | [Aurora Store](https://auroraoss.com/), [F-Droid](https://f-droid.org/)
Launcher | \- | KISS Launcher, T-UI\*\*\*, Lawnchair
Activity tracker pairing app | Mi Fit | Gadgetbridge\*\*\*
Music player | Google Music | Vinyl, Odyssey
Notes | Google Keep, OneNote | Markor, Joplin
RSS Feed | Aggregator | Feeder
\- | Reddit | Infinity for Reddit\*, Slide, RedReader\*\*\*
SMS | \- | QKSMS
Synchronization | \- | Syncthing, KDE Connect
\- | Twitter | Twidere
\- | VULCAN Dzienniczek+ | Wulkanowy
Video player | MX Player | VLC
\- | YouTube | NewPipe, SkyTube\*\*\*

### Root only apps

App | Description
:--- | :---
[Magisk](https://magiskroot.com/)\* | Tool for rooting your phone.
[TWRP](https://twrp.me/)\* | Recovery project.
[Adaway](https://adaway.org/) | Hosts based ad-blocker.

### Other recommended privacy apps

App | Description
:--- | :---
[Orbot](guardianproject.info/apps/orbot) | Tor proxy for Android.
UntrackMe | Links converter (eg. change youtu.be to invidio.us on the fly).
Scrambled Exif | Remove metadata from photos.
OpenKeychain | PGP encryption app for Android.

\* - Not avaliable in default F-Droid repository. See below. \
\*\* - Delete Facebook account if you don't need it. \
\*\*\* - Not recommended. See below.

#### Where get apps that aren't on F-Droid?

**Brave** - Use Aurora Store (Google Play frontend) or add [rfc2822's repo](https://gitlab.com/rfc2822/fdroid-firefox) to F-Droid..

**Bromite** - Add [Bromite repo](https://www.bromite.org/fdroid) to F-Droid.

**Firefox** - Install Fennec, use Aurora Store (Google Play frontend) or add [rfc2822's repo](https://gitlab.com/rfc2822/fdroid-firefox) to F-Droid.

**Tor Browser** - Add [Guardian Project repo](https://guardianproject.info/fdroid/) to F-Droid.

**AOSP Keyboard** - [APKMirror](https://www.apkmirror.com/apk/lineageos/android-keyboard-aosp-2/)

**Infinity for Reddit** - Add [IzzyOnDroid repo](https://apt.izzysoft.de/fdroid/repo) to F-Droid.

**Magisk** - https://github.com/topjohnwu/Magisk

**TWRP** - https://twrp.me/

#### Why not recommended?

**Gadgetbridge** - [TODO]

**RedReader** - [TODO]

**SkyTube** - [TODO]

**T-UI** - Not really efficient on touchscreen.

## Desktop apps

Type | App | FOSS alternatives
:--- | :--- | :---
3D modeling and animation | 3ds Max, Cinema 4D | [Blender](https://www.blender.org/)
Vector graphics | Adobe Illustrator | [Inkscape](https://inkscape.org)
Photo retouching | Adobe Lightroom | [darktable](https://www.darktable.org/), [RawTherapee](https://rawtherapee.com/)
Bitmap graphics | Adobe Photoshop | [GIMP](https://www.gimp.org/), [Krita](https://krita.org)
Video editor | Adobe Premiere | [Kdenlive](https://kdenlive.org/), [OpenShot](https://www.openshot.org/)
CAD | AutoCAD | [QCAD](https://qcad.org/en/)
Browser | Chrome, MS Edge, Vivaldi | [Firefox](https://www.mozilla.org/en-US/exp/firefox/new/), [Tor Browser](https://torproject.org), [Brave](https://brave.com/), [Ungoogled Chromium](https://github.com/Eloston/ungoogled-chromium), [Qutebrowser](https://qutebrowser.org/)
Code editor | Visual Studio | [VSCode](https://github.com/microsoft/vscode) (built from source or [VSCodium](https://vscodium.com/)), [vim](https://www.vim.org/) or [NeoVim](https://neovim.io/), [Emacs](https://www.gnu.org/software/emacs/)
Discord client\*\* | Discord | [gtkcord3](https://github.com/diamondburned/gtkcord3)
\- | Epic Games Launcher | [legendary](https://github.com/derrod/legendary)
Office suite | Microsoft Office | [Libre Office](https://www.libreoffice.org/), [Open Office](https://www.openoffice.org/)\*
Screencast/streaming app | [OBS Studio](https://obsproject.com/), [SimpleScreenRecorder](https://www.maartenbaert.be/simplescreenrecorder/)
BitTorrent client | µTorrent | [qBittorrent](https://www.qbittorrent.org/), [Transmission](https://transmissionbt.com/)

\* - not recommended \
\*\* - Using unofficial clients is not allowed in Discord TOS and might result in pernament account block. Use it at your own risk.

## Services

Type | Service | FOSS (or more private\*\*) alternatives
:--- | :--- | :---
Channel-based chat | Discord | [Keybase](https://keybase.io/)\*\*, \[[Riot.im](https://about.riot.im/), [FluffyChat](https://christianpauly.gitlab.io/fluffychat-website/) ([Matrix](https://en.wikipedia.org/wiki/Matrix_(protocol)) clients)\]
Polls | Strawpoll, Doodle | [Framadate](https://framadate.org/), [Disroot Polls](https://poll.disroot.org/)
Surveys and forms | Google Forms | Nextcloud app [Forms](https://apps.nextcloud.com/apps/forms)
Cooperative editing | Google Docs | [Etherpad](https://etherpad.org/), [Disroot Pad](https://pad.disroot.org/), [Disroot Cryptpad](https://cryptpad.disroot.org/)
\- | Facebook | [Mastodon](https://mastodon.social/about), [Disapora](https://joindiaspora.com/)
Git hosting | GitHub | [GitLab](https://gitlab.com/) (or selfhosted [Gitlab CE](https://gitlab.com/opensource/gitlab-ce)), [Codeberg](https://codeberg.org/), [Gitea](https://gitea.com/)
E-mail hosting | Gmail, Outlook | [Disroot](https://disroot.org)\*, [ProtonMail](https://protonmail.com/)\*, [Tutanota](https://www.tutanota.com/)\*, [Kolab Now](https://kolabnow.com/) (or selfhosted [Kolab](https://kolab.org/))
Cloud drive and sync | Google Drive, OneDrive | [Nextcloud](https://nextcloud.com/), [Syncthing](https://syncthing.net/) (only sync)
Font resources | Google Fonts | selfhosted fonts, [Font Library](https://fontlibrary.org/)
Machine translation | Google Translate | [DeepL Translator](https://www.deepl.com/translator)\*
Search engines | Google, Bing | [DuckDuckGo](https://duckduckgo.com)\*, [SearX](https://search.disroot.org/), [YaCy](https://yacy.net/)
Spell checking | Grammarly | [LanguageTool](https://languagetool.org/)
\- | Instagram | [Pixelfed](https://pixelfed.org/)
Group-based chat | Messenger, WhatsApp | [Signal](https://www.signal.org/), [Riot.im](https://about.riot.im/) ([Matrix](https://en.wikipedia.org/wiki/Matrix_(protocol)) client), [Telegram FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)\*
Password manager | Dashlane, LastPass, Google Password Manager | [KeePassXC](https://keepassxc.org/) (KeePassDX for Android), [Bitwarden](https://bitwarden.com/)
Pastebin | Pastebin.com | [Disroot Privatebin](https://bin.disroot.org/), [GitLab Snippets](https://gitlab.com/), [0x0](http://0x0.st/)\*\*
Music streaming | Spotify, Tidal | ~~downloaded~~ bought music
\- | Twitter | [Mastodon](https://joinmastodon.org), [Pleroma](https://pleroma.social), [Nitter](https://nitter.net/) (Twitter frontend)
Video/Voice Chat | Discord, Skype | [Jitsi Meet](https://meet.jit.si/), [Mumble](https://www.mumble.info/), Nextcloud app [Talk](https://apps.nextcloud.com/apps/spreed)
\- | YouTube | [LBRY](https://lbry.tv/), [invidio.us](https://invidio.us) (YouTube frontend)

\* - Not (fully) FOSS, but still a better alternative. \
\*\* - Not recommended. See below.

#### Why not recommended?

**Keybase** - [recently acquired by Zoom](https://keybase.io/blog/keybase-joins-zoom). Messages are still private (since they are encrypted), but the development might slow down or even stopped (Zoom cares about their devs, not about the app itself).

**0x0** - Doesn't keep pastes forever, doesn't have an UI (it's just a service).

## Games
Game | Description
:--- | :---
[osu!lazer](https://github.com/ppy/osu) | Iconic rhythm *click the circles* game now is officially open source.
[Open Arena](http://www.openarena.ws/smfnews.php) | Community-produced deathmatch FPS based on GPL idTech3 technology.
[Lutris](https://lutris.net/) | Open gaming platform for Linux.
[RetroArch](https://www.retroarch.com/) | *libretro* frontend. Combines all (or most of) your emulators and game engines in one place.
[Minetest](https://www.minetest.net/) | Voxel engine and game. Alternative to Minecraft.
[MultiMC](https://multimc.org/) | Advanced, open Minecraft launcher (the game is still propertiary).

#### [Big list of open source games](https://en.wikipedia.org/wiki/List_of_open-source_video_games)
