### The Home apps – Apple's apps, rebuilt for your own server

Native apps that look and feel like Apple's own – but your data lives on **your** server instead of iCloud.
Every app is free, open source (MIT), has no tracking and talks only to the server you choose.

| | App | Replaces | Server | Runs on | |
|---|---|---|---|---|---|
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeRoll/main/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon.png" width="48" alt=""> | **[HomeRoll](https://github.com/silentprovider423/HomeRoll)** | Photos | Immich | iPhone | Your whole photo library – grid, memories, editor, background backup. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeRoll-Desk/main/Mac/Assets.xcassets/AppIcon.appiconset/icon_128x128@1x.png" width="48" alt=""> | **[HomeRoll Desktop](https://github.com/silentprovider423/HomeRoll-Desk)** | Photos for Mac | Immich | Mac | Sidebar, menus, shortcuts and editor like Photos on the Mac. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeRoll-TV/main/docs/icon.png" width="48" alt=""> | **[HomeRoll TV](https://github.com/silentprovider423/HomeRoll-TV)** | Photos for Apple TV | Immich | Apple TV | Memories, albums and Top Shelf on the big screen. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeTune/main/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon.png" width="48" alt=""> | **[HomeTune](https://github.com/silentprovider423/HomeTune)** | Music | Navidrome | iPhone | FLAC up to 24/96, playlists, offline – every song in 432 Hz (440/528 selectable). |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeNotes/main/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon.png" width="48" alt=""> | **[HomeNotes](https://github.com/silentprovider423/HomeNotes)** | Notes | Nextcloud | iPhone | Folders, checklists, tables, images – offline with line-by-line merge. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomePost/main/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon.png" width="48" alt=""> | **[HomePost](https://github.com/silentprovider423/HomePost)** | Mail | IMAP/SMTP or JMAP | iPhone | Conversations, flags, undo send, remote images blocked. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeFind/main/Resources/Assets.xcassets/AppIcon.appiconset/icon-1024.png" width="48" alt=""> | **[HomeFind](https://github.com/silentprovider423/HomeFind)** | Find My | Dawarich | iPhone | Share your location with family, arrive/leave alerts, your devices. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeCast/main/Resources/Assets.xcassets/AppIcon.appiconset/icon-1024.png" width="48" alt=""> | **[HomeCast](https://github.com/silentprovider423/HomeCast)** | Podcasts | PinePods | iPhone | Queue, chapters, sleep timer, speed per show – synced with your server. |
| <img src="https://raw.githubusercontent.com/silentprovider423/HomeThread/main/iOS/Assets.xcassets/AppIcon.appiconset/icon-1024.png" width="48" alt=""> | **[HomeThread](https://github.com/silentprovider423/HomeThread)** | notes to self | own server (Docker) | iPhone + Mac | Your notes as chats and groups – polls, checklists, voice notes. Nothing is ever sent. |

**How they're made:** each Apple app was studied by its class names and interface texts only (no Apple code, nothing decompiled) – every action, menu and screen mapped, then rebuilt from scratch in SwiftUI.

**Install:** every repo has a release with an `.ipa` – sideload it with AltStore, SideStore or Sideloadly. Setup guides are in each repo's `docs/SETUP.md`.

<sub>Not affiliated with Apple or any of the server projects.</sub>

