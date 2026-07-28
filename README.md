# Abdullah Çafer

**Software developer focused on Windows systems, desktop applications, and automation.**

I build practical tools that make complex or repetitive work simpler. My projects span native Win32 process control, .NET desktop interfaces, asynchronous Python systems, and local-first Electron applications. I care about predictable behavior, efficient resource use, clear interfaces, and software that people can install, understand, and maintain.

I’m open to software engineering opportunities—especially in Windows and desktop development, backend automation, developer tooling, and reliability-focused product work.

## Selected work

### [WinAnanicy](https://github.com/misutesu-desu/win-ananicy)

A reversible process rule engine for Windows 10 and 11.

- Built a native C++20 engine and a .NET 8 WPF control center.
- Applies CPU and I/O priority, affinity, EcoQoS, and CPU limits while matching rules are active, then restores the original process state.
- Ships as installer and portable releases with automated tests, CI, CodeQL analysis, checksums, verification documentation, and English/Turkish localization.

[Repository](https://github.com/misutesu-desu/win-ananicy) · [Latest release](https://github.com/misutesu-desu/win-ananicy/releases/latest)

### [MudaRemote](https://github.com/misutesu-desu/MudaRemote)

A long-running, event-driven Python automation application with a Windows interface and an active user community.

- Designed timing-sensitive, multi-account workflows around `asyncio`, live event handling, rate limiting, and coordinated state.
- Added secure token storage, atomic configuration writes, recovery paths, logging, and regression coverage for critical flows.
- Maintains standalone Windows releases, an update pipeline, documentation, localization, and community-driven iteration.

[Repository](https://github.com/misutesu-desu/MudaRemote) · [Latest release](https://github.com/misutesu-desu/MudaRemote/releases/latest)

### [ConvertAll Desktop](https://github.com/misutesu-desu/convertall-desktop)

A local-first file conversion application for Windows.

- Built with Electron, React, TypeScript, and Tailwind CSS.
- Handles image, document, audio, and video conversion locally without uploading user files.
- Integrates native tooling such as Sharp and FFmpeg and packages the result as Windows installer and portable builds.

[Repository](https://github.com/misutesu-desu/convertall-desktop)

## More projects

- [YT-Sentence-Flow](https://github.com/misutesu-desu/YT-Sentence-Flow) — a browser userscript that turns fragmented YouTube captions into readable sentences while preserving responsive positioning and styling.
- [FileHarbor](https://github.com/misutesu-desu/FileHarbor) — a configurable desktop utility that monitors and organizes files automatically.
- [MudaLoot](https://github.com/misutesu-desu/MudaLoot) — an event-driven automation extension built around controlled pacing and state synchronization.

## Technical focus

- **Languages:** C++20, C#, Python, TypeScript, JavaScript
- **Windows and desktop:** Win32 APIs, .NET 8, WPF, Electron, Windows packaging
- **Backend and automation:** `asyncio`, event-driven systems, state coordination, rate limiting, recovery logic
- **Frontend:** React, WPF/XAML, Tailwind CSS, responsive desktop interfaces
- **Quality and delivery:** CMake, GitHub Actions, CodeQL, automated tests, release pipelines, checksums, technical documentation

## How I work

I like owning the complete path from a problem to a usable release: understanding the real constraint, choosing a small and dependable design, testing failure paths, packaging the software, documenting it, and improving it with user feedback.

If you are hiring for work that overlaps with these areas, or would like to collaborate on an open-source project, I would be glad to hear from you.
