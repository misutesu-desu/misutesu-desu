# Hi there, I'm Abdullah C. 👋

I am a developer specializing in backend systems, process automation, desktop utility development, and systems-level optimization. My focus is on building resource-efficient software, utilizing native APIs, and automating complex workflows.

---

### 🛠️ Technical Toolkit

- **Languages:** Python, C++, C#, JavaScript, SQL, C
- **Systems & Desktop:** Win32 APIs, Windows Services, .NET 8 (WPF), CMake
- **Asynchronous & Automation:** Asyncio, Event-driven architecture, Regular Expressions (RegEx)
- **AI & Data:** LLM Workflows, Prompt Engineering, Local Inference (Stable Diffusion, RVC)
- **Tools:** Git, GitHub, VS Code, Linux/Unix

---

### 🚀 Highlighted Projects

#### 💻 [win-ananicy](https://github.com/misutesu-desu/win-ananicy) (C++ / C#)
*A lightweight background process optimizer for Windows, designed to manage system resources dynamically.*
- **Core Engine:** Written in C++ utilizing native Win32 APIs (`SetPriorityClass`, `SetProcessAffinityMask`, `NtSetInformationProcess`) to adjust CPU/IO priorities and core affinities.
- **Resource Efficient:** Consumes `< 7MB RAM` and `0% CPU` when idling.
- **UI Dashboard:** Built with .NET 8 WPF featuring a Fluent design for interactive rule configuration.

#### 🤖 [MudaRemote](https://github.com/misutesu-desu/MudaRemote) & [MudaLoot](https://github.com/misutesu-desu/MudaLoot) (Python)
*An asynchronous automation suite designed for interaction with the Mudae Discord mini-game.*
- **Automation Logic:** Implements timing control, slash command support, and custom Regex parsing for real-time data extraction.
- **Reliability:** Built-in self-healing connection logic and multi-account synchronization.
- **Loot Extension:** Utilizes `asyncio.Event` synchronization for smart rate-limiting and pin management.

#### 📺 [YT-Sentence-Flow](https://github.com/misutesu-desu/YT-Sentence-Flow) (JavaScript / UserScript)
*A real-time semantic subtitle processor for YouTube that merges fragmented captions into logical sentences.*
- **UI/UX:** Features drag-and-drop mechanics, proportional font scaling based on player state, and zero latency.
- **Performance:** Hooks directly into network requests (XHR/Fetch) and utilizes `ResizeObserver` to monitor player dimensions dynamically.
