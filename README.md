# PawnQuill

A lightweight PAWN IDE for SA-MP and open.mp with a clean, modern interface.

PawnQuill is a cross-platform desktop editor focused on PAWN development. It is being built for Windows, macOS, and Linux, with a simple interface inspired by modern desktop applications.

> **Project status:** early development. PAWN-specific language tooling, build workflows, and SA-MP/open.mp integration are being developed on top of the current editor foundation.

## What PawnQuill is for

PawnQuill is intended to make PAWN development easier without turning the editor into a general-purpose IDE.

The project is focused on:

- PAWN source files (.pwn and .inc)
- SA-MP and open.mp projects
- Compiler and build workflows
- Include and dependency handling
- Code navigation and language tooling
- Integrated terminal and project tools
- A fast, clean desktop experience

## Platform

PawnQuill is planned for:

- Windows
- macOS
- Linux

The interface takes some visual inspiration from macOS, but PawnQuill is not a macOS-only application.

## Technology

PawnQuill uses TypeScript, Rust, Tauri, Monaco Editor, and other open-source components.

The current codebase uses **SideX** as a technical foundation. SideX is a separate project and remains credited here:

https://github.com/Sidenai/sidex

PawnQuill is developed as an independent project and is not affiliated with or endorsed by Sidenai, Siden Technologies Inc., Microsoft, SA-MP, or open.mp.

## Development

Typical development setup:

    npm install
    npm run tauri dev

Build:

    npm run tauri build

The exact build requirements may change while the project is being developed.

## Roadmap

The long-term direction includes:

- PAWN syntax and language tooling
- IntelliSense-style completion
- Go to definition and symbol navigation
- Compiler diagnostics
- Project templates
- SA-MP and open.mp server workflows
- Include and dependency discovery
- Faster search and indexing
- Git integration
- Cross-platform packaging
- A cleaner, more responsive desktop UI

## Credits and licensing

PawnQuill contains code derived from third-party projects.

The original licenses and copyright notices for those components are preserved. In particular, portions derived from SideX and Visual Studio Code / Code - OSS remain subject to their applicable licenses.

PawnQuill's own original work is covered by the **PawnQuill Public Source License (PPSL) 1.0** unless a file or component states otherwise.

See:

- `LICENSE` for the PawnQuill Public Source License
- `LICENSE_TH.md` for the Thai translation
- `NOTICE.md` for project attribution
- `THIRD_PARTY_NOTICES.md` for third-party licensing information

## ไทย

PawnQuill เป็น IDE สำหรับภาษา PAWN ที่ทำขึ้นเพื่อการพัฒนา SA-MP และ open.mp โดยเน้นความเรียบง่าย ความเร็ว และการใช้งานที่สะดวก

รองรับ Windows, macOS และ Linux โดยหน้าตาของโปรแกรมได้รับแรงบันดาลใจบางส่วนจาก macOS แต่ไม่ได้จำกัดการใช้งานไว้เฉพาะ macOS

โปรเจกต์อยู่ในช่วงพัฒนาเริ่มต้น และจะค่อย ๆ เพิ่มระบบเฉพาะสำหรับ PAWN เช่น autocomplete, diagnostics, compiler workflow, include/dependency handling และเครื่องมือสำหรับ SA-MP/open.mp

PawnQuill เป็นโปรเจกต์อิสระ และไม่ได้เป็นผลิตภัณฑ์ของ Sidenai, Siden Technologies Inc., Microsoft, SA-MP หรือ open.mp

ดูรายละเอียดลิขสิทธิ์และเครดิตได้จากไฟล์ Markdown ที่ระบุไว้ด้านบน
