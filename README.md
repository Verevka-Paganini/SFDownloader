# SFDownloader

A lightweight, dependency-free native Android downloader built in Kotlin for browsing and downloading files from any SourceForge project.

### Key Features
- **Any SourceForge Project:** Browse files from any project by entering its project slug or full SourceForge URL, with saved project history.
- **Multi-Threaded Downloads:** Accelerates downloads using configurable parallel HTTP `Range` threads (`2`, `4`, `6`, or `8` threads).
- **Mirror Selection & Live Switching:** Choose between automatic geo-routing or specific SourceForge CDN mirrors, and switch mirrors on the fly during an active download without losing progress.
- **Pause & Resume:** Reliable chunk-level state persistence allowing downloads to be paused and resumed at any time.
- **Integrity & Checksum Verification:** Automatically validates file size and archive integrity upon completion, computes the SHA-256 hash, and lets you copy it with a single tap.
- **Background Foreground Service:** Runs reliably in the background with live progress, speed, and active mirror notifications.