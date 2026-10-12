# Awesome Desktop Pets

A curated map of desktop pets, AI companions, transparent overlays, and small desktop-widget projects.

The list focuses on projects that are interesting to builders: real desktop overlay techniques, character packs, transparent windows, local AI companions, productivity pets, and cross-platform pet frameworks.

[![Validate catalog](https://github.com/StaryMoon/awesome-desktop-pets/actions/workflows/validate.yml/badge.svg)](https://github.com/StaryMoon/awesome-desktop-pets/actions/workflows/validate.yml)

## Why this list

Desktop pets are back, but the ecosystem is scattered across old eSheep-style toys, Shimeji runners, Live2D assistants, AI coding pets, and local LLM companions. This repo keeps a practical index for people who want to build or compare them.

Builder notes: [docs/builder-guide.md](docs/builder-guide.md)

## Quick Picks

| Need | Try |
|---|---|
| Pixel pet for coding-agent watching | [clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) |
| Classic eSheep-style desktop pet | [desktopPet](https://github.com/Adrianotiger/desktopPet) |
| Local-first LLM desktop pet | [MiniCPM-Desk-Pet](https://github.com/OpenBMB/MiniCPM-Desk-Pet) |
| Arknights character desktop pets | [Ark-Pets](https://github.com/isHarryh/Ark-Pets) |
| Shimeji desktop pet runner | [Shijima-Qt](https://github.com/pixelomer/Shijima-Qt) |
| macOS glass planner with a small desktop pet | [DailyDesk](https://github.com/StaryMoon/DailyDesk) |
| Transparent-window framework example | [UnityDesktopPetFramework](https://github.com/OnyxAmber/UnityDesktopPetFramework) |

## Catalog

### AI and Coding Pets

| Project | Stack | Notes |
|---|---|---|
| [clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) | JavaScript | Pixel desktop pet that watches Claude Code, Codex, Cursor, and other AI coding agents. |
| [Agentic-Desktop-Pet](https://github.com/jihe520/Agentic-Desktop-Pet) | Python | Agentic desktop pet with LLM, memory, emotion, and RPG-style interaction. |
| [MiniCPM-Desk-Pet](https://github.com/OpenBMB/MiniCPM-Desk-Pet) | JavaScript | Local-first desktop pet powered by MiniCPM. |
| [AI-Girlfriend-Desktop-Pet](https://github.com/DD-MASTERT/AI-Girlfriend-Desktop-Pet) | Python | Live2D AI desktop pet with speech, screen recognition, and multiple model backends. |
| [yuns-desktop-pet](https://github.com/JianguSheng/yuns-desktop-pet) | JavaScript | Electron AI pet assistant with multi-model chat, MCP tools, and vision analysis. |
| [chatgpt-desktopPet](https://github.com/kirbystudy/chatgpt-desktopPet) | JavaScript | Electron + Live2D desktop pet with ChatGPT support. |
| [DesktopPet](https://github.com/xccds/DesktopPet) | GDScript | Godot desktop pet with AI-powered chat. |

### Classic and Character Pets

| Project | Stack | Notes |
|---|---|---|
| [desktopPet](https://github.com/Adrianotiger/desktopPet) | C# | Modern eSheep-style desktop pet inspired by the 1995 original. |
| [DesktopPet](https://github.com/huiyadanli/DesktopPet) | C# | Desktop pet inspired by Ukagaka / Sakura-style companions. |
| [DesktopPet](https://github.com/WolfChen1996/DesktopPet) | Python | Friendly framework for making personal desktop pets. |
| [Ark-Pets](https://github.com/isHarryh/Ark-Pets) | Java | Arknights desktop pets. |
| [VirtualCockroach](https://github.com/FerryYoungFan/VirtualCockroach) | ActionScript | Cockroach desktop pet. Weird, memorable, and very desktop-pet-coded. |
| [Maltese_DesktopPet](https://github.com/Jimmmmmies/Maltese_DesktopPet) | Python | PyQt5 desktop pet themed around a small white dog character. |
| [desktop-pet](https://github.com/datawhalechina/desktop-pet) | Python | Minimal desktop pet demo with Wenxin Yiyan and Raspberry Pi Pico. |
| [Desktop Cat](https://github.com/wt0812/desktop-cat) | C# / PowerShell | Single-file Windows pixel cat: no installer, no network, 12 animations, persisted position and affection. |

### Runners and Frameworks

| Project | Stack | Notes |
|---|---|---|
| [Shijima-Qt](https://github.com/pixelomer/Shijima-Qt) | C++ | Shimeji desktop pet runner. |
| [UnityDesktopPetFramework](https://github.com/OnyxAmber/UnityDesktopPetFramework) | C# | Transparent-window interactive example based on Unity URP. |
| [3d-desktop-pet](https://github.com/zlmica/3d-desktop-pet) | Vue | 3D desktop pet experiment. |
| [DesktopPetBasedOnU3D](https://github.com/unishiki/DesktopPetBasedOnU3D) | C# | U3D desktop pet project code and structure. |
| [DesktopPet](https://github.com/xccds/DesktopPet) | GDScript | Godot desktop pet with AI-powered chat. |
| [Shirros/desktop-pet](https://github.com/Shirros/desktop-pet) | Python | Python desktop pet experiment with ChatGPT support. |

### Productivity Widgets with Pet Energy

| Project | Stack | Notes |
|---|---|---|
| [DailyDesk](https://github.com/StaryMoon/DailyDesk) | Swift/AppKit | macOS glass desktop planner with recurring tasks, desktop pin behavior, and a tiny desktop pet. |
| [myCat](https://github.com/yumiaura/myCat) | Python | Qt overlay desktop cat with a strong small-tool vibe. |
| [pet-therapy](https://github.com/raman0c17/pet-therapy) | macOS | Desktop pets for macOS. |
| [3d-desktop-pet](https://github.com/zlmica/3d-desktop-pet) | Vue | 3D desktop pet experiment that is useful as a web-rendered widget reference. |

## Builder Notes

Common technical problems:

- Transparent always-on-top windows are platform-specific. AppKit, Qt, Electron, Unity, Godot, and browser overlays all solve it differently.
- Click-through behavior should be explicit. A good pet should not steal focus unexpectedly.
- Idle animation matters more than feature count. A pet that moves too much becomes visual noise.
- Local AI companions need hard safety boundaries: no hidden file access, no silent network calls, clear model/backend settings.
- Character packs are the real long-term moat. Good tooling for importing sprites, GIFs, and behavior states matters.

## Add a Project

Open a PR that updates `catalog.json` and the README. A useful entry should include:

- project URL
- platform / framework
- short note about what makes it different
- whether it is a pet, overlay, AI companion, runner, or widget

Please prefer maintained projects with readable setup instructions.

## License

CC0-1.0 for the list text. Each linked project keeps its own license.
