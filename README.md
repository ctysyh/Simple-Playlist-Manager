\# 🎵 Modern Web Playlist Manager — README



> ✅ Single File · 📁 Offline-First · 🔄 Multi-Playlist · 🚫 No Network · 💾 Auto-Save



A lightweight, offline-first playlist manager that puts you in full control. All data is saved within \*\*a local folder you choose\*\*. Create, rename, delete, and switch between multiple playlists. Automatically restores your last session on restart.



---



\## 🌟 Core Features



\- \*\*📁 Project Folder System\*\*  

&nbsp; On first launch, select a local folder (e.g., `~/Documents/MyPlaylists/`). All playlist `.json` files are stored together here.



\- \*\*➕➖🗑️ Full Playlist Lifecycle Management\*\*  

&nbsp; - \*\*Create\*\* → Auto-generates a `.json` file  

&nbsp; - \*\*Rename\*\* → File name updates automatically  

&nbsp; - \*\*Delete\*\* → Removes file from disk + confirmation dialog  

&nbsp; - \*\*Switch\*\* → One-click load via sidebar or dropdown



\- \*\*💾 Auto-Restore Session\*\*  

&nbsp; Automatically reloads your last project folder and active playlist on restart — pick up right where you left off.



\- \*\*🎵 Song Management\*\*  

&nbsp; - Add/Edit/Delete songs (title, artist, album, link)  

&nbsp; - Drag-and-drop reordering + real-time search filter  

&nbsp; - Sort by: Time, Title, Artist, Album



\- \*\*🔒 Privacy-First \& Offline\*\*  

&nbsp; - No server, no signup, no internet required  

&nbsp; - Data saved as standard JSON — editable manually or importable  

&nbsp; - Auto-saves before closing (if file is linked)



---



\## 🖥️ UI Overview



```

┌──────────────────────────────────────────────────────┐

│ \[Song Title Input]                                   │ ← Add Song Area

│ \[Artist] \[Album] \[＋ Add Song]                       │

├──────────────────────────────────────────────────────┤

│ 🔍 Search...  \[By Time] \[By Title] \[By Artist] \[By Album] │ ← Search \& Sort

├──────────────────────────────────────────────────────┤

│ My Playlist (42 songs)                               │ ← Playlist Header

│ ┌──┬───────────┬───────┬───────┬───────┬─────────┐ │

│ │# │ Title     │ Artist│ Album │ Time  │ Actions │ │

│ ├──┼───────────┼───────┼───────┼───────┼─────────┤ │

│ │1 │ Nocturne  │ Jay   │ Nov   │ 4:30  │ 🗑️      │ │

│ └──┴───────────┴───────┴───────┴───────┴─────────┘ │

└──────────────────────────────────────────────────────┘

```



\- \*\*Top Dropdown\*\*: Quick playlist switching  

\- \*\*✏️ next to playlist name\*\*: Rename playlist  

\- \*\*🗑️ next to playlist name\*\*: Delete playlist (with confirmation)  

\- \*\*Save Button\*\*: Manually save current playlist anytime



---



\## ⚙️ Technical Highlights



\- \*\*File System API\*\*: `showDirectoryPicker()`, `getFileHandle()`, `move()` for direct file operations

\- \*\*IndexedDB\*\*: Persists directory handles \& playlist metadata (filename, display name, modified time)

\- \*\*Permission Handling\*\*: Auto-checks/requests folder read-write permissions on launch

\- \*\*Filename Sanitization\*\*: Auto-strips illegal characters for cross-platform safety

\- \*\*Responsive Design\*\*: Works beautifully on desktop and mobile



---



\## ✅ Ready for Use



\- \[x] Multiple playlists as individual `.json` files  

\- \[x] All files stored in user-selected directory  

\- \[x] Renaming updates underlying filename  

\- \[x] Deleting playlist = deleting file  

\- \[x] Auto-restores folder \& playlist on restart  

\- \[x] Auto-loads last edited playlist (or first one)



---



\## 🚀 Quick Start



1\. Download `playlist-manager.html` (single file)

2\. Open in browser (Chrome or Edge recommended)

3\. First launch → Choose a local folder as your playlist root

4\. Start creating and managing your personal playlists!



> 💡 Tip: Everything runs locally — your data always belongs to you.



---



\## 🔮 Future Roadmap (Planned)



\- Playlist tagging / categorization

\- Export to CSV / Spotify playlist format

\- Cover art support \& playlist descriptions



---



\*\*Made with ❤️ for music lovers who value privacy \& control.\*\*  

\*No install · No signup · No tracking · No ads\*

